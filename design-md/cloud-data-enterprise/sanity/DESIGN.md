---
version: alpha
name: Sanity
description: A dark, code-forward content operations system for the AI era. Sanity's current homepage anchors on a near-black canvas, compressed waldenburgNormal typography, coral-red CTAs, electric-blue interaction states, monochrome product UI composites, code blocks, and editorial proof sections. The live site verified through Lightpanda leads with "Structure powers intelligence" and positions Sanity as "the back-end built for AI content operations" powering web, mobile, and agentic applications at scale.

colors:
  primary: "#f36458"
  primary-active: "#0052ef"
  primary-hover: "#0052ef"
  primary-on-dark: "#ffffff"
  ink: "#ffffff"
  body: "#b9b9b9"
  body-strong: "#ededed"
  body-muted: "#797979"
  ink-on-light: "#0b0b0b"
  body-on-light: "#212121"
  canvas: "#0b0b0b"
  canvas-deep: "#000000"
  surface-dark: "#212121"
  surface-dark-elevated: "#353535"
  surface-light: "#ededed"
  surface-white: "#ffffff"
  surface-blue-soft: "#afe3ff"
  surface-blue: "#55beff"
  accent-blue: "#0052ef"
  accent-green: "#19d600"
  accent-green-p3: "color(display-p3 .270588 1 0)"
  accent-magenta-p3: "color(display-p3 .960784 0 1)"
  accent-orange-p3: "color(display-p3 1 0.3333 0)"
  border-dark: "#0b0b0b"
  border-subtle: "#212121"
  border-medium: "#353535"
  border-light: "#ffffff"
  error: "#dd0000"
  compliance-green: "#37cd84"
  code-bg: "#0b0b0b"
  code-text: "#ededed"

typography:
  hero-display:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 112px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: -4.48px
  hero-secondary:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 72px
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: -2.88px
  display-lg:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 48px
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: -1.68px
  display-md:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 38px
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: -1.14px
  display-sm:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 32px
    fontWeight: 425
    lineHeight: 1.24
    letterSpacing: -0.32px
  title:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 24px
    fontWeight: 425
    lineHeight: 1.24
    letterSpacing: -0.24px
  subtitle:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 20px
    fontWeight: 425
    lineHeight: 1.13
    letterSpacing: -0.2px
  lead:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: -0.18px
  body:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-small:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: -0.15px
  caption:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: -0.13px
  nav-link:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0
  label:
    fontFamily: "waldenburgNormal, waldenburgNormal Fallback, ui-sans-serif, system-ui, sans-serif"
    fontSize: 11px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: 0
    textTransform: uppercase
  code:
    fontFamily: "IBM Plex Mono, ibmPlexMono Fallback, ui-monospace, SFMono-Regular, Menlo, monospace"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  code-caption:
    fontFamily: "IBM Plex Mono, ibmPlexMono Fallback, ui-monospace, SFMono-Regular, Menlo, monospace"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0

rounded:
  none: 0px
  xs: 3px
  sm: 5px
  md: 6px
  lg: 12px
  xl: 24px
  pill: 99999px
  full: 99999px

spacing:
  hairline: 1px
  micro: 2px
  xxs: 4px
  xs: 6px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 24px
  xxl: 32px
  xxxl: 48px
  section: 96px
  section-lg: 128px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-on-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: 8px 16px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.primary-on-dark}"
    rounded: "{rounded.pill}"
  button-secondary-dark:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: 8px 12px
  button-secondary-light:
    backgroundColor: "{colors.surface-white}"
    textColor: "{colors.ink-on-light}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: 8px 16px
    border: "1px solid {colors.ink-on-light}"
  button-ghost:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.body}"
    typography: "{typography.caption}"
    rounded: "{rounded.sm}"
    padding: 6px 12px
    border: "1px solid {colors.border-subtle}"
  text-link:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body}"
  text-link-hover:
    backgroundColor: transparent
    textColor: "{colors.accent-blue}"
    typography: "{typography.body}"
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.nav-link}"
    borderBottom: "1px solid {colors.border-subtle}"
  mega-menu:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.body}"
    border: "1px solid {colors.border-subtle}"
  hero-band:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.hero-display}"
    padding: 128px 24px
  product-demo-card:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 32px
    border: "1px solid {colors.border-medium}"
  code-window:
    backgroundColor: "{colors.code-bg}"
    textColor: "{colors.code-text}"
    typography: "{typography.code}"
    rounded: "{rounded.md}"
    padding: 24px
    border: "1px solid {colors.border-medium}"
  studio-panel:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.ink-on-light}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 24px
  feature-tab:
    backgroundColor: transparent
    textColor: "{colors.body-muted}"
    typography: "{typography.label}"
    padding: 8px 12px
  feature-tab-active:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
  logo-cloud:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.caption}"
  metric-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-lg}"
    rounded: "{rounded.none}"
  enterprise-band:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-lg}"
    padding: 96px 24px
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.caption}"
    padding: 64px 24px
---

## Overview

Sanity's current website is a dark, developer-native content operations system. The live homepage title is **"The Content Operating System for the AI era"**, and the hero headline is **"Structure powers intelligence"**. The supporting line defines the product clearly: **"The back-end built for AI content operations. Power web, mobile, and agentic applications at scale."**

The current navigation is product-heavy and should feel like a technical platform map. Products are grouped into **Content operations** (Studio, Content Agent, App SDK, Media Library, Content Releases, Agent API) and **Content backend** (Content Lake, Agent Context, MCP Server, Compute, Live CDN). Solutions split by industry and team. Resources include Sanity 101, Learn, Frameworks, Templates, Tools and plugins, Schemas and snippets, community, blog, events, customer stories, and guides.

The homepage alternates between product proof and technical proof: a hero with Start building / Watch demo actions, a large customer logo cloud, interactive Studio and code examples, automation/function demos, agent-context bot panels, feature tabs, customer metrics, enterprise trust, and a final "Less talk, more code" section with CLI install, MCP Server, and Agent toolkit.

The system's atmosphere is a nocturnal control room for structured content. It uses a near-black canvas, white/silver text, extremely compressed display type, code snippets, dark product cards, occasional light Studio panels, and one warm coral-red CTA. Electric blue is the activation signal on hover/focus.

## Colors

### Brand & Accent

- **Sanity Red** (`{colors.primary}` - #f36458): Primary conversion color for "Get started", "Start building", and similar actions. It is the only warm CTA in the otherwise dark technical system.
- **Electric Blue** (`{colors.accent-blue}` - #0052ef): Universal hover and active state. Links, buttons, and interactive controls shift blue on hover. This color is also the focus-ring language.
- **Neon Green** (`{colors.accent-green-p3}` / fallback `#19d600`): Wide-gamut success or high-signal accent, used sparingly for status, premium indicators, and agent/system health moments.
- **Magenta P3** (`{colors.accent-magenta-p3}`): Rare specialized accent. Do not use as a normal section color.
- **Orange P3** (`{colors.accent-orange-p3}`): Highlight border or featured technical accent.

### Surface

- **Canvas** (`{colors.canvas}` - #0b0b0b): Default page background and dominant surface. It should feel like the native environment, not a dark-mode variant.
- **Canvas Deep** (`{colors.canvas-deep}` - #000000): Maximum-depth overlays, isolated deep panels, and some code contexts.
- **Surface Dark** (`{colors.surface-dark}` - #212121): Cards, menus, input surfaces, demo panels, tab active states.
- **Surface Dark Elevated** (`{colors.surface-dark-elevated}` - #353535): Stronger separation inside dark product demos and nested panels.
- **Surface Light** (`{colors.surface-light}` - #ededed): Inverted Studio-like surfaces and light product UI panels.
- **Surface White** (`{colors.surface-white}` - #ffffff): White button surfaces, bright UI cards, and selected product mockups.

### Text

- **Ink** (`{colors.ink}` - #ffffff): Primary text on dark backgrounds and hero headlines.
- **Body Strong** (`{colors.body-strong}` - #ededed): Secondary headings and stronger paragraphs.
- **Body** (`{colors.body}` - #b9b9b9): Default body copy on dark surfaces.
- **Body Muted** (`{colors.body-muted}` - #797979): Tertiary metadata, inactive tabs, labels, and low-priority footer text.
- **Ink on Light** (`{colors.ink-on-light}` - #0b0b0b): Text on white or light Studio panels.
- **Body on Light** (`{colors.body-on-light}` - #212121): Paragraph text on inverted panels.

### Hairlines & Borders

- **Border Subtle** (`{colors.border-subtle}` - #212121): Standard dark border for cards, inputs, nav separators, and menus.
- **Border Medium** (`{colors.border-medium}` - #353535): More visible containment for demo panels, code windows, and emphasized cards.
- **Border Light** (`{colors.border-light}` - #ffffff): Separation on inverted/light elements.
- **Border Dark** (`{colors.border-dark}` - #0b0b0b): Barely visible separation inside very dark layers.

### Semantic

- **Error** (`{colors.error}` - #dd0000): Validation errors and destructive states.
- **Compliance Green** (`{colors.compliance-green}` - #37cd84): Trust/compliance indicators such as security and privacy status.
- **Code Background** (`{colors.code-bg}` - #0b0b0b): Code panels and terminal surfaces.
- **Code Text** (`{colors.code-text}` - #ededed): Code foreground.

## Typography

### Font Family

Sanity's primary typeface is **waldenburgNormal**, used for display, body, navigation, captions, and UI labels. It has a compact, engineered feel that supports the "structured content" positioning. The code and terminal voice uses **IBM Plex Mono**.

Fallbacks should preserve the condensed technical tone. Use Space Grotesk, Inter Tight, or Inter for waldenburgNormal fallback; use IBM Plex Mono, JetBrains Mono, or a system monospace for code.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---:|---:|---:|---:|---|
| `{typography.hero-display}` | 112px | 400 | 1 | -4.48px | Homepage hero and giant editorial statements |
| `{typography.hero-secondary}` | 72px | 400 | 1.05 | -2.88px | Major secondary hero/section displays |
| `{typography.display-lg}` | 48px | 400 | 1.08 | -1.68px | Section heads, large proof moments |
| `{typography.display-md}` | 38px | 400 | 1.1 | -1.14px | Feature section titles |
| `{typography.display-sm}` | 32px | 425 | 1.24 | -0.32px | Card titles, compact section heads |
| `{typography.title}` | 24px | 425 | 1.24 | -0.24px | Product card and feature titles |
| `{typography.subtitle}` | 20px | 425 | 1.13 | -0.2px | Section markers and subheads |
| `{typography.lead}` | 18px | 400 | 1.5 | -0.18px | Hero body and large descriptions |
| `{typography.body}` | 16px | 400 | 1.5 | 0 | Default paragraphs and nav links |
| `{typography.body-small}` | 15px | 400 | 1.5 | -0.15px | Compact descriptions |
| `{typography.caption}` | 13px | 400 | 1.5 | -0.13px | Metadata and footer |
| `{typography.label}` | 11px | 600 | 1.1 | 0 | Uppercase tabs and technical labels |
| `{typography.code}` | 15px | 400 | 1.5 | 0 | Code blocks and terminal demos |
| `{typography.code-caption}` | 13px | 400 | 1.4 | 0 | File labels and code metadata |

### Principles

Sanity display type is compressed and precise. Large headings should use aggressive negative tracking; at 112px, `-4.48px` tracking is part of the brand. Body text relaxes to a readable 1.5 line-height, so the page can carry long technical explanations without becoming claustrophobic.

Keep the weight range narrow. Most text is 400, with 425 for headings and 600 only for small uppercase labels. Do not use heavy bold weights to create emphasis; use size, negative tracking, surface contrast, and blue activation instead.

IBM Plex Mono should appear wherever the system is proving technical credibility: schema examples, CLI output, terminal panels, function code, MCP references, and agent/tooling lists.

### Note on Font Substitutes

waldenburgNormal is a custom Sanity typeface. If it is unavailable, **Space Grotesk** is the closest widely available replacement for display, followed by **Inter Tight** or **Inter**. For code, **IBM Plex Mono** is preferred and publicly available; JetBrains Mono is acceptable if Plex is unavailable.

## Layout

### Spacing System

- **Base unit:** 8px.
- **Micro spacing:** `{spacing.hairline}` 1px, `{spacing.micro}` 2px, `{spacing.xxs}` 4px, `{spacing.xs}` 6px.
- **Component spacing:** `{spacing.sm}` 8px, `{spacing.md}` 12px, `{spacing.lg}` 16px, `{spacing.xl}` 24px, `{spacing.xxl}` 32px, `{spacing.xxxl}` 48px.
- **Section spacing:** `{spacing.section}` 96px, `{spacing.section-lg}` 128px.

Sanity sections can be dense because the content is technical, but major transitions need large dark breathing room. Code and Studio demos need generous padding so nested UI does not collapse into visual noise.

### Grid & Container

- **Max content width:** ~1200-1280px centered.
- **Hero:** large left-aligned or centered typographic block over a dark media/composite background.
- **Logo cloud:** repeated brand marks in a dense responsive grid; current logos include loveholidays, Mejuri, Redis, Replit, Arc'teryx, Brex, Figma, Shopify, Tecovas, Unity, Linear, Skims, Spotify, Anthropic, MoMA, Complex, Lady Gaga, Nordstrom, Rona, Hunter Douglas, and Baggu.
- **Product demos:** two-column or layered compositions pairing code windows, Studio panels, terminal output, and image/UI composites.
- **Feature tabs:** numbered vertical or horizontal list: Content-as-data, Editorial freedom, Content agent, Automation at scale, Power any application.
- **Footer:** multi-column technical sitemap with Products, Resources, Company, Trust and compliance, and Keep in touch.

### Whitespace Philosophy

The page rhythm should feel like moving through a structured system: dark hero, proof cloud, interactive product demo, automation demo, feature index, customer proof, enterprise trust, code CTA, footer. Dense technical panels are allowed, but each major band needs enough empty dark space for the next idea to register.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat dark | `{colors.canvas}` with no shadow | Body canvas, hero, footer |
| Dark card | `{colors.surface-dark}` with subtle border | Cards, menus, demo containers |
| Nested dark | `{colors.surface-dark-elevated}` | Inner panels and active tabs |
| Code surface | `{colors.code-bg}` + mono text | Terminal and code windows |
| Light product surface | `{colors.surface-light}` / white | Studio UI panels and editorial tools |
| Media composite | Full-bleed image/UI collage | Hero and feature proof |

The elevation system is color-block first. Shadows are not a core signature; depth comes from black-to-gray layering, code/editor chrome, and photographic or UI composites. Use borders to define dark surfaces.

### Decorative Depth

Sanity uses dark media and UI collages rather than ornamental gradients. Product proof images can layer code, Studio UI, structured content, and photographic fragments. This is especially visible in the "Everything your team needs in one place" section, where every feature combines a large media image with smaller UI screenshots.

Code blocks and terminals create their own internal depth through mono text, file labels, prompts, output lines, and command status. Keep this visible; do not flatten code panels into generic cards.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---:|---|
| `{rounded.none}` | 0px | Full-bleed sections, large media blocks |
| `{rounded.xs}` | 3px | Inputs, search fields, tiny code controls |
| `{rounded.sm}` | 5px | Ghost buttons, tabs, compact menu items |
| `{rounded.md}` | 6px | Cards, code windows, Studio panels |
| `{rounded.lg}` | 12px | Large demo cards and feature cards |
| `{rounded.xl}` | 24px | Rare large containers |
| `{rounded.pill}` | 99999px | Primary CTAs, secondary pill buttons, badges |
| `{rounded.full}` | 99999px | Circular icon buttons |

### Photography & Product Geometry

Product media is precise and rectangular. Full-bleed photography and image composites can use square corners, while nested UI panels use 6px to 12px radii. Do not make the whole system overly soft; Sanity should feel engineered.

Screenshots should show real tool structure: document trees, form fields, publishing state, history, release controls, code editors, terminal output, and agent status panels. Product images are part of the content model story.

## Components

### Top Navigation

**`top-nav`** — Dark navigation with Sanity wordmark, product mega-menus, Docs, Enterprise, Pricing, Login, Contact Sales, and Get started. The nav should use silver text on near-black, a subtle bottom border, and blue hover states. Primary CTA uses the coral-red pill.

**`mega-menu`** — Structured dark panel with grouped links and preview cards. Current Products menu splits into Content operations and Content backend. Menu preview cards can include imagery and short headlines such as "The only platform powering content operations" or customer stories like Tecovas.

### Buttons

**`button-primary`** — Coral-red pill. Background `{colors.primary}`, white text, 8px x 16px padding, full pill radius. On hover/active, shift to `{colors.accent-blue}`.

**`button-secondary-dark`** — Dark pill with silver text. Use for lower-priority nav actions and dark-surface controls. Hover also shifts blue.

**`button-secondary-light`** — White pill with near-black text and a black border. Use only on inverted/light panels or where a white action contrasts against the dark canvas.

**`button-ghost`** — Compact dark-gray rounded rectangle for filters, tabs, utility actions, and product demo controls.

**`text-link`** — Inline links should be white or silver by default and electric blue on hover. Do not introduce underline-heavy editorial link styling.

### Cards & Containers

**`hero-band`** — Near-black hero with giant compressed heading, supporting line, Start building and Watch demo actions, and a dark media background. It should feel cinematic but technical.

**`product-demo-card`** — Dark gray card with a 1px medium border, 12px radius, and internal code/Studio/UI fragments. Use for "Mirror how your content operations team works" and automation examples.

**`code-window`** — Mono technical block with `IBM Plex Mono`, dark background, code foreground, 6px radius, and 24px padding. Use for schema definitions, CLI install, Sanity typegen output, function examples, and MCP/agent tooling proof.

**`studio-panel`** — Light or white product UI panel showing fields, publishing controls, history, release scheduling, or document editing. Text flips to near-black.

**`logo-cloud`** — Dense customer logo grid on dark. Logos should feel like evidence, not decoration.

**`metric-card`** — Customer proof metric group. Use large white numbers and muted labels. Current examples include 300% faster release cycles, 90% updates owned by content teams, 5x faster dev velocity, 144x faster product launches, 10k products updated in 30 seconds, 80 hours saved per month, 60 lines of code, and zero added services.

### Inputs & Forms

**Text inputs / search inputs** should use near-black or dark-gray surfaces, silver text, muted placeholders, 3px radius, and a 1px subtle border. Focus should use blue ring/outline and may shift the background slightly toward a blue-black.

**Studio form fields** inside product demos can use light surfaces and near-black text. They should resemble actual content editing UI: Title, Description, Image, Publish, History, release controls, locale rows, and action lists.

### Footer

**`footer`** — Dark sitemap footer with Products, Resources, Company, Trust and compliance, and Keep in touch. Current details include GitHub, YouTube, LinkedIn, Bluesky, X, RSS, Discord, OSL/NOR and SFO/USA location indicators, system status, and site theme control. Keep footer dense and functional.

## Do's and Don'ts

### Do

- Use near-black (`{colors.canvas}`) as the default page environment.
- Use Sanity Red for primary conversion actions and electric blue for interaction states.
- Keep display type compressed with strong negative tracking.
- Use IBM Plex Mono for schema, CLI, terminal, and function examples.
- Show real product structure: Studio fields, document history, release controls, code, agent panels, and APIs.
- Use customer logos and metrics as proof elements.
- Let dark-gray surfaces and borders create depth instead of shadows.
- Preserve the product taxonomy: Studio, Content Agent, App SDK, Media Library, Content Releases, Agent API, Content Lake, Agent Context, MCP Server, Compute, and Live CDN.

### Don't

- Don't turn the site into a friendly pastel CMS design; Sanity's identity is dark, precise, and technical.
- Don't use pure white as the dominant canvas.
- Don't use coral-red for every highlight; reserve it for primary CTA and brand moments.
- Don't replace code examples with generic illustrations.
- Don't loosen display tracking at large sizes.
- Don't add heavy shadows or glassy blur effects.
- Don't make all cards pill-shaped; pills are for actions and badges.
- Don't hide footer/product navigation complexity. The platform breadth is part of the positioning.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---:|---|
| Mobile | < 768px | Nav collapses, hero display drops sharply, demos stack, code scrolls horizontally |
| Tablet | 768-1024px | Two-column sections where possible, logo cloud tightens, feature tabs may become horizontal |
| Desktop | 1024-1440px | Full mega-menu nav, large hero type, two-column demos, dense footer grid |
| Wide | > 1440px | Keep max content width capped; use more outer dark breathing room |

### Touch Targets

- Pill CTAs should be at least 40px tall on touch devices.
- Mega-menu rows and footer links need enough vertical spacing to tap reliably.
- Code blocks should not shrink below readable mono size; allow horizontal scroll.
- Studio panel controls should remain visibly tappable, even if they are illustrative.

### Collapsing Strategy

The hero should drop from 112px display type to 72px, then 48px or lower on mobile. Preserve tight tracking, but reduce it proportionally. Product demo layouts stack vertically. Code windows should keep line integrity and scroll horizontally rather than wrapping important syntax.

Feature tabs can become a stacked list. Logo clouds can reduce density but should still show enough brands to communicate trust. Footer groups should stack into clear sections.

### Image Behavior

Dark media and UI composites should crop around meaningful product detail, not generic texture. On mobile, prioritize readable Studio panels, code snippets, and agent/status text over wide cinematic crops.

## Iteration Guide

1. Start from the dark canvas and silver/white text before adding accents.
2. Use Sanity Red for the main CTA only; use electric blue for hover and focus.
3. Keep display typography compressed and low-weight.
4. Add code or product UI wherever a claim needs proof.
5. Use borders and gray surfaces for depth; avoid floating shadows.
6. Preserve technical product naming exactly when possible: Content Lake, Agent Context, MCP Server, Compute, Live CDN.
7. When creating a section, decide whether it is a product demo, customer proof, enterprise proof, code proof, or navigation utility; use the matching component pattern.
8. Check mobile code readability early.

## Known Gaps

- Source capture was performed with Lightpanda against `https://www.sanity.io/` on 2026-05-17. Full `networkidle` rendering produced a client-side exception, but `domcontentloaded` successfully exposed current navigation, hero text, product sections, customer proof, code examples, footer links, and metadata.
- Lightpanda did not expose reliable computed CSS values for every element, so low-level typography and color tokens combine the current homepage structure with the existing Sanity design analysis.
- The homepage includes interactive demos marked "Tap to interact" / "Click to interact"; static capture cannot verify their animated states.
- Exact image crop, video thumbnails, theme toggle behavior, and hover transitions should be checked in a visual browser if pixel-level fidelity is needed.
