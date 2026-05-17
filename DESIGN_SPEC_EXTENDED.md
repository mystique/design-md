<!-- Copied and expanded from https://github.com/google-labs-code/design.md/blob/main/docs/spec.md -->
<!-- Expanded against the repository example: design-md/consumer-tech-platforms/apple/DESIGN.md -->

# DESIGN.md Extended Format

DESIGN.md is a self-contained, plain-text representation of a design system. It defines the visual identity of a brand, product, or interface family so that stylistic choices can be followed across design sessions, generated implementations, and different AI agents and tools.

This extended schema keeps the upstream `alpha` format intact, then broadens the prose and token rules to cover richer real-world documents such as the Apple design reference in this repository. Those documents are not just minimal token manifests. They combine machine-readable tokens with brand analysis, component rationale, responsive behavior, iteration guidance, and documented gaps.

A DESIGN.md file contains two parts:

1. Optional YAML front matter with machine-readable design tokens.
2. A Markdown body with human-readable design rationale, implementation guidance, and guardrails.

The YAML tokens are the normative values for implementation. The Markdown prose explains how to apply them, when to choose between variants, and which visual behaviors are intentionally absent.

# Design Tokens

Design tokens are embedded as YAML front matter at the beginning of the file. The block must begin with a line containing exactly `---` and end with a line containing exactly `---`.

```yaml
---
version: alpha
name: Apple
description: A photography-first interface with near-invisible UI chrome.
colors:
  primary: "#0066cc"
  canvas: "#ffffff"
typography:
  body:
    fontFamily: "SF Pro Text, system-ui, -apple-system, sans-serif"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.47
    letterSpacing: -0.374px
rounded:
  pill: 9999px
spacing:
  section: 80px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.canvas}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: 11px 22px
---
```

## Extended Schema

```yaml
version: <string>              # optional, current version: "alpha"
name: <string>                 # required
description: <string>          # optional, may be long-form

colors:
  <token-name>: <Color>

typography:
  <token-name>: <Typography>

rounded:
  <scale-level>: <Dimension>

spacing:
  <scale-level>: <Dimension | number>

components:
  <component-name>:
    <property-name>: <TokenValue>
```

## Primitive Types

**Color**

A color value should be a hex color in the sRGB color space.

```yaml
colors:
  primary: "#0066cc"
  on-dark: "#ffffff"
```

Consumers should accept 3, 6, or 8 digit hex values. Other CSS color formats may be preserved with a warning, but hex is the canonical format.

**Dimension**

A dimension is normally a string-like value with a unit suffix.

Valid canonical units:

- `px`
- `em`
- `rem`

Real documents may use YAML plain scalars such as `fontSize: 56px`; consumers should treat these as strings after parsing.

**Number**

A unitless numeric value. Common uses include `lineHeight: 1.47`, numeric spacing ratios, font weights, and grid counts.

**Composite CSS Value**

The upstream schema defines many properties as a single `Dimension`, but real design documents often need CSS shorthand values.

Examples:

```yaml
padding: 11px 22px
boxShadow: "rgba(0, 0, 0, 0.22) 3px 5px 30px 0"
```

Consumers should preserve composite CSS values as strings. Validators may warn if a property expected a single dimension, but should not reject the file solely because a shorthand value is used.

**Token Reference**

A token reference is wrapped in curly braces and points to another value in the YAML tree.

```yaml
backgroundColor: "{colors.primary}"
typography: "{typography.body}"
rounded: "{rounded.pill}"
```

For most token groups, references should point to primitive values. Within `components`, references to composite token groups, especially typography objects, are allowed.

# Token Groups

## `colors`

The `colors` group is a flat map of named color tokens.

Common token categories:

- Brand and accent colors: `primary`, `primary-focus`, `primary-on-dark`
- Text colors: `ink`, `body`, `body-muted`, `on-primary`, `on-dark`
- Surface colors: `canvas`, `surface`, `surface-black`, `surface-card`
- Border colors: `hairline`, `divider`, `divider-soft`
- State colors: `success`, `warning`, `error`, `focus`

Real-world brand systems may use descriptive semantic names instead of generic scale names. This is valid when the names are consistent and explained in the `## Colors` section.

## `typography`

The `typography` group is a map of named typography tokens.

```yaml
typography:
  hero-display:
    fontFamily: "SF Pro Display, system-ui, -apple-system, sans-serif"
    fontSize: 56px
    fontWeight: 600
    lineHeight: 1.07
    letterSpacing: -0.28px
```

Supported typography properties:

- `fontFamily`
- `fontSize`
- `fontWeight`
- `lineHeight`
- `letterSpacing`
- `fontFeature`
- `fontVariation`

Consumers should preserve unknown typography properties with a warning. Brand documents may include strongly opinionated details such as negative tracking, rare weights, substitute fonts, or OpenType guidance in the Markdown body.

## `rounded`

The `rounded` group defines the border radius scale.

```yaml
rounded:
  none: 0px
  sm: 8px
  lg: 18px
  pill: 9999px
  full: 9999px
```

`pill` and `full` may share the same value. The prose should explain the semantic difference when both are present, for example pill-shaped CTAs versus circular icon controls.

## `spacing`

The `spacing` group defines structural spacing tokens.

```yaml
spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 17px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 80px
```

Spacing tokens may include non-power-of-two values when they are part of a brand rhythm. The Markdown body should explain why unusual values exist.

## `components`

The `components` group is a map of component identifiers to style properties.

```yaml
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: 11px 22px
  button-primary-active:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.pill}"
```

Common component property tokens:

- `backgroundColor`
- `textColor`
- `borderColor`
- `typography`
- `rounded`
- `padding`
- `margin`
- `size`
- `height`
- `width`
- `minHeight`
- `maxWidth`
- `border`
- `boxShadow`
- `opacity`
- `backdropFilter`

The upstream alpha schema lists a smaller property set. This extended schema allows additional CSS-like properties because real component descriptions often need borders, shadows, blur, opacity, and dimension constraints.

## Component Naming

Component names should be kebab-case.

Valid examples:

- `button-primary`
- `button-primary-active`
- `button-primary-focus`
- `product-tile-dark`
- `product-tile-dark-2`
- `search-input`
- `floating-sticky-bar`

Variants may be represented as separate component keys. Related variants should share a clear prefix.

Recommended suffixes:

- `-hover`
- `-active`
- `-pressed`
- `-focus`
- `-selected`
- `-disabled`
- Numeric or tonal variants, such as `-2` and `-3`, when the prose explains the difference.

# Markdown Sections

Every DESIGN.md should use `##` headings for top-level parsed sections. An optional `#` heading may appear for document titling and is not treated as a design section.

Sections can be omitted if irrelevant, but present sections should appear in this sequence.

## Canonical Section Order

1. `## Overview`
2. `## Colors`
3. `## Typography`
4. `## Layout`
5. `## Elevation & Depth`
6. `## Shapes`
7. `## Components`
8. `## Do's and Don'ts`

## Extended Section Order

The following sections may appear after the canonical sections:

9. `## Responsive Behavior`
10. `## Iteration Guide`
11. `## Known Gaps`

Consumers must preserve unknown `##` sections and should not reject a file because it contains extra guidance.

## Section Aliases

Accepted aliases:

- `Overview`: `Brand & Style`
- `Layout`: `Layout & Spacing`
- `Elevation & Depth`: `Elevation`
- `Do's and Don'ts`: `Dos and Don'ts`, `Do and Don't`, `Guidelines`

Duplicate canonical sections should be rejected unless they are clearly distinct subsections under another heading.

# Section Requirements

## Overview

Describes the holistic brand and interface feel.

It should cover:

- Brand personality
- Density and whitespace
- Visual hierarchy
- Signature interaction or composition patterns
- What should be visually absent
- The emotional or product positioning goal

Extended documents may include a short bullet list of key characteristics.

## Colors

Defines color palettes and their roles.

Useful subsections:

- `### Brand & Accent`
- `### Surface`
- `### Text`
- `### Hairlines & Borders`
- `### Brand Gradient`

The prose should map descriptive names to token names and hex values. It should also document when a brand intentionally has no gradients, no secondary accent, or no decorative colors.

## Typography

Defines font families, hierarchy, and type behavior.

Useful subsections:

- `### Font Family`
- `### Hierarchy`
- `### Principles`
- `### Note on Font Substitutes`

Typography tables are allowed and encouraged for large systems. They should include token name, size, weight, line height, letter spacing, and intended use.

## Layout

Defines spacing, grids, containers, and whitespace strategy.

Useful subsections:

- `### Spacing System`
- `### Grid & Container`
- `### Whitespace Philosophy`

The layout section may describe fixed max widths, full-bleed sections, gutters, card grids, stacking behavior, and unusual layout constants.

## Elevation & Depth

Defines how hierarchy is created.

This may include:

- Shadow levels
- Borders and hairlines
- Backdrop blur
- Tonal layering
- Product-only shadows
- Explicit bans on shadows for UI chrome

Tables are valid for elevation levels.

## Shapes

Defines corner radius, geometry, crop behavior, and image shape rules.

Useful subsections:

- `### Border Radius Scale`
- `### Photography Geometry`
- `### Icon Geometry`

Shape guidance may include when not to round elements.

## Components

Defines style and behavior for recurring UI parts.

Useful subsections:

- `### Top Navigation`
- `### Buttons`
- `### Cards & Containers`
- `### Inputs & Forms`
- `### Footer`

Each component description should reference YAML keys where possible.

Good:

```markdown
**`button-primary`** — Background `{colors.primary}`, text `{colors.on-primary}`,
rounded `{rounded.pill}`, padding 11px x 22px.
```

Components may document behavior that is not encoded in YAML, such as active transforms, focus outlines, sticky positioning, content structure, or responsive collapse.

## Do's and Don'ts

Provides practical guardrails.

This section may be split into:

- `### Do`
- `### Don't`

Guidelines should be concrete and reference tokens. Avoid vague advice when a token or component key exists.

## Responsive Behavior

Optional extended section.

Defines responsive breakpoints, touch targets, collapse rules, and image behavior.

Useful subsections:

- `### Breakpoints`
- `### Touch Targets`
- `### Collapsing Strategy`
- `### Image Behavior`

Breakpoint tables are allowed.

Example:

```markdown
| Name | Width | Key Changes |
|---|---|---|
| Phone | 420-640px | Single-column stack; hero typography drops to 34px |
| Desktop | 1069-1440px | Full layout; 4-5 column grids |
```

This section is descriptive unless matching tokens are added to the YAML front matter in a future spec version.

## Iteration Guide

Optional extended section.

Gives agents practical instructions for modifying or extending the design system.

It may include:

- Which component to edit first
- How to name variants
- Whether to use token references or literal values
- Which states to document
- Which effects are forbidden or reserved

This section is especially useful when a design system is used by multiple AI agents.

## Known Gaps

Optional extended section.

Documents intentionally missing areas of the design system.

Examples:

- Form validation states were not observed.
- Dark mode was not documented.
- Embedded media controls are platform widgets.
- Exact blur radius is implementation-dependent.
- Some image assets are content, not tokens.

Known gaps should prevent agents from inventing unsupported rules while still allowing future refinement.

# Prose and Token Relationship

Use prose to explain intent. Use tokens to define exact implementation values.

Preferred:

```markdown
Use `{colors.primary}` (#0066cc) for every interactive element.
```

Avoid:

```markdown
Use a nice blue for links.
```

When prose and YAML disagree, consumers should treat YAML as the implementation source of truth and flag the mismatch.

# Validation Rules

## Required

- If YAML front matter exists, it must parse as YAML.
- `name` must be present in front matter.
- Top-level Markdown sections should use `##`.
- Duplicate canonical sections should be rejected.

## Recommended

- `version` should be `alpha`.
- Colors should be hex values.
- Token references should resolve.
- Component names should be kebab-case.
- Prose should reference token keys for important values.
- Component variants should share a prefix with their base component.

## Tolerated With Warning

- Unknown Markdown sections.
- Unknown token names.
- Unknown component properties.
- Composite CSS values where a single dimension was expected.
- YAML plain scalars that parse as strings, such as `56px`.
- Long-form `description` values.
- Additional subsections under canonical sections.

## Reject

- Invalid YAML front matter.
- Duplicate canonical sections.
- Token references that cannot resolve, if strict validation is requested.
- Non-map values for `colors`, `typography`, `rounded`, `spacing`, or `components`.

# Consumer Behavior for Unknown Content

| Scenario | Behavior | Example |
|---|---|---|
| Unknown section heading | Preserve; do not error | `## Iconography` |
| Unknown color token name | Accept if value is valid | `surface-tile-3: "#252527"` |
| Unknown typography token name | Accept as valid typography | `dense-link` |
| Unknown spacing value | Accept; store as string if not a valid dimension | `section: 80px` |
| Unknown component property | Accept with warning | `backdropFilter` |
| Composite property value | Preserve as string | `padding: 11px 22px` |
| Duplicate section heading | Error; reject the file | Two `## Colors` headings |

# Recommended Token Names

These names are non-normative. They are useful for consistency across documents.

**Colors**

- `primary`
- `primary-focus`
- `primary-on-dark`
- `secondary`
- `tertiary`
- `neutral`
- `canvas`
- `surface`
- `surface-card`
- `surface-muted`
- `ink`
- `body`
- `body-muted`
- `on-primary`
- `on-dark`
- `hairline`
- `divider`
- `error`
- `success`
- `warning`

**Typography**

- `hero-display`
- `display-lg`
- `display-md`
- `headline-lg`
- `headline-md`
- `body`
- `body-strong`
- `body-sm`
- `caption`
- `caption-strong`
- `label`
- `nav-link`
- `fine-print`
- `micro-legal`

**Rounded**

- `none`
- `xs`
- `sm`
- `md`
- `lg`
- `xl`
- `pill`
- `full`

**Spacing**

- `xxs`
- `xs`
- `sm`
- `md`
- `lg`
- `xl`
- `xxl`
- `section`
- `gutter`
- `margin`

**Components**

- `global-nav`
- `sub-nav`
- `button-primary`
- `button-secondary`
- `button-icon`
- `text-link`
- `card`
- `tile`
- `product-tile`
- `search-input`
- `footer`
- `sticky-bar`

# Minimal Document Example

```markdown
---
version: alpha
name: Example Brand
description: A concise design language for focused product surfaces.
colors:
  primary: "#1A1C1E"
  canvas: "#ffffff"
  on-primary: "#ffffff"
typography:
  body:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
rounded:
  sm: 4px
  full: 9999px
spacing:
  sm: 8px
  md: 16px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body}"
    rounded: "{rounded.full}"
    padding: 8px 16px
---

## Overview

The interface is direct, restrained, and content-first.

## Colors

`{colors.primary}` is the only accent and is reserved for actions.

## Typography

Body copy uses `{typography.body}`.

## Layout

Spacing follows the `{spacing.md}` rhythm.

## Components

**`button-primary`** uses the primary action treatment.

## Do's and Don'ts

### Do
- Use token references for recurring values.

### Don't
- Don't introduce untracked accent colors.
```

# Rich Document Example Pattern

A richer document may include the canonical sections plus `Responsive Behavior`, `Iteration Guide`, and `Known Gaps`. This is the expected pattern for brand reference files that document multiple pages, responsive states, and observed limitations.

