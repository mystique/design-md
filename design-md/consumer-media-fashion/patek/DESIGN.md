---
version: alpha
name: Patek Philippe
description: A museum-quiet luxury interface built on cinematic watchmaking films, serif editorial headlines, and expansive white space. The UI is intentionally subordinate to heritage storytelling: near-white canvases, warm black typography, muted taupe-gold accents, thin hairlines, and restrained uppercase CTAs. Rather than pushing commerce urgency, the system stages each section like a maison brochure where motion, craft photography, and legacy copy do the emotional work.

colors:
  primary: "#8c7a5b"
  primary-deep: "#6f6148"
  antique-gold: "#b7a27a"
  ink: "#181512"
  body: "#2f2a24"
  body-muted: "#6d655b"
  body-subtle: "#8e8579"
  on-dark: "#f7f4ef"
  canvas: "#fbfaf7"
  canvas-pure: "#ffffff"
  surface-ivory: "#f4f1ea"
  surface-stone: "#ebe5da"
  surface-taupe: "#d8cfbf"
  surface-dark: "#1f1a16"
  surface-hero-scrim: "rgba(20,16,12,0.28)"
  hairline: "#d8d1c5"
  hairline-soft: "#ece7de"
  border-strong: "#c6bcae"
  focus-ring: "#a89269"
  shadow-soft: "0 18px 40px rgba(24,21,18,0.08)"

typography:
  hero-display:
    fontFamily: '"Iowan Old Style, Baskerville, Georgia, Times New Roman, serif"'
    fontSize: 64px
    fontWeight: 400
    lineHeight: 1.04
    letterSpacing: -0.02em
  display-lg:
    fontFamily: '"Iowan Old Style, Baskerville, Georgia, Times New Roman, serif"'
    fontSize: 46px
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: -0.015em
  display-md:
    fontFamily: '"Iowan Old Style, Baskerville, Georgia, Times New Roman, serif"'
    fontSize: 34px
    fontWeight: 400
    lineHeight: 1.18
    letterSpacing: -0.01em
  eyebrow:
    fontFamily: '"Helvetica Neue, Arial, sans-serif"'
    fontSize: 12px
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: 0.18em
    textTransform: uppercase
  title:
    fontFamily: '"Helvetica Neue, Arial, sans-serif"'
    fontSize: 20px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0.02em
  body-lg:
    fontFamily: '"Helvetica Neue, Arial, sans-serif"'
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.72
    letterSpacing: 0.005em
  body:
    fontFamily: '"Helvetica Neue, Arial, sans-serif"'
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.75
    letterSpacing: 0.005em
  body-strong:
    fontFamily: '"Helvetica Neue, Arial, sans-serif"'
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.65
    letterSpacing: 0.01em
  caption:
    fontFamily: '"Helvetica Neue, Arial, sans-serif"'
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0.04em
  caption-strong:
    fontFamily: '"Helvetica Neue, Arial, sans-serif"'
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0.08em
    textTransform: uppercase
  nav-link:
    fontFamily: '"Helvetica Neue, Arial, sans-serif"'
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.3
    letterSpacing: 0.14em
    textTransform: uppercase
  utility:
    fontFamily: '"Helvetica Neue, Arial, sans-serif"'
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0.12em
    textTransform: uppercase
  button:
    fontFamily: '"Helvetica Neue, Arial, sans-serif"'
    fontSize: 13px
    fontWeight: 600
    lineHeight: 1
    letterSpacing: 0.16em
    textTransform: uppercase
  legal:
    fontFamily: '"Helvetica Neue, Arial, sans-serif"'
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0.02em

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 8px
  lg: 16px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 40px
  xxl: 64px
  section: 96px
  cinematic: 132px

components:
  transparent-header:
    backgroundColor: transparent
    textColor: "{colors.canvas-pure}"
    typography: "{typography.utility}"
    height: 72px
  burger-button:
    backgroundColor: transparent
    textColor: "{colors.canvas-pure}"
    typography: "{typography.utility}"
    rounded: "{rounded.none}"
    padding: 12px 0px
  hero-film:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    minHeight: 760px
  hero-copy-panel:
    backgroundColor: "{colors.surface-hero-scrim}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-lg}"
    padding: 48px
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.canvas-pure}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 16px 28px
    height: 46px
  button-primary-hover:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.canvas-pure}"
    rounded: "{rounded.none}"
  button-secondary:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    border: "1px solid {colors.border-strong}"
    padding: 15px 28px
    height: 46px
  button-play-ghost:
    backgroundColor: "rgba(255,255,255,0.12)"
    textColor: "{colors.canvas-pure}"
    typography: "{typography.utility}"
    rounded: "{rounded.full}"
    padding: 10px 16px
  section-split-editorial:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-md}"
    padding: 96px 0px
  image-story-card:
    backgroundColor: "{colors.canvas-pure}"
    textColor: "{colors.body}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    shadow: "{colors.shadow-soft}"
  quote-over-media:
    backgroundColor: "{colors.surface-hero-scrim}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-md}"
    padding: 40px
  collection-spotlight:
    backgroundColor: "{colors.canvas-pure}"
    textColor: "{colors.ink}"
    typography: "{typography.display-md}"
    rounded: "{rounded.none}"
  footer-columns:
    backgroundColor: "{colors.surface-ivory}"
    textColor: "{colors.body}"
    typography: "{typography.caption}"
    padding: 72px 0px
  footer-accordion-trigger:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.caption-strong}"
    rounded: "{rounded.none}"
    borderTop: "1px solid {colors.hairline}"
    padding: 18px 0px
  locale-switch:
    backgroundColor: transparent
    textColor: "{colors.body}"
    typography: "{typography.utility}"
    rounded: "{rounded.none}"
    border: "1px solid {colors.hairline}"
    padding: 12px 16px

---

## Overview

Patek Philippe's site is not arranged like a high-conversion ecommerce funnel. It behaves more like a luxury maison publication: full-bleed films, long pauses of white space, editorial serif headlines, and carefully rationed calls to action. Even when the page links into collections or points of sale, the dominant message is heritage, craft, and permanence rather than product velocity.

The interface language is extremely restrained. Color lives mostly inside imagery: polished metal, lacquer, enamel, walnut, Geneva stone, soft daylight. The UI itself stays within warm whites, dark brown-black text, hairline taupe borders, and a single antique-gold action family. The result feels expensive because it refuses loudness. There are no aggressive sale badges, no dense icon rails, no playful radii, and no oversaturated CTA colors.

The homepage rhythm alternates between cinematic motion-led hero modules and quieter editorial sections with supporting copy and a single action. Lower on the page, this expands into image-plus-text storytelling blocks, then a broad institutional footer with many links exposed as either desktop columns or mobile accordions. The system is part museum label, part luxury brochure, part heritage archive.

**Key Characteristics:**
- Cinematic hero videos with overlaid serif headlines and sparse copy.
- Warm, low-contrast luxury neutrals instead of pure black-and-white minimalism.
- Serif for emotion and heritage; neo-grotesk sans for navigation, body, and metadata.
- Strong preference for rectangular frames and thin hairlines over pills and soft UI.
- Uppercase, letter-spaced CTAs that feel ceremonial rather than promotional.
- Long-form institutional storytelling integrated directly into the homepage.
- Footer taxonomy treated as part of the information architecture, not an afterthought.

## Colors

> **Source pages analyzed:** Patek Philippe homepage and its linked collection/manufacture/service pathways as exposed through the homepage navigation. The strongest recurring visual cues are warm ivory backgrounds, dark photographic overlays, and a restrained gold-taupe accent family.

### Brand & Accent
- **Maison Gold** (`{colors.primary}` — #8c7a5b): The most appropriate extracted accent for primary actions and premium emphasis. It mirrors the warm metal-and-wood palette that recurs across hero films and luxury product imagery.
- **Maison Gold Deep** (`{colors.primary-deep}` — #6f6148): Hover and pressed-state darkening for buttons or emphasis borders.
- **Antique Gold** (`{colors.antique-gold}` — #b7a27a): A softer highlight used for subtle separators, featured metadata, or premium tags when a lighter metallic note is needed.

### Surface
- **Main Canvas** (`{colors.canvas}` — #fbfaf7): The dominant page background. It reads softer and more archival than a clean tech white.
- **Pure White** (`{colors.canvas-pure}` — #ffffff): Used inside cards, media gutters, and places where imagery needs a crisp frame.
- **Ivory Surface** (`{colors.surface-ivory}` — #f4f1ea): Footer and quiet structural sections.
- **Stone Surface** (`{colors.surface-stone}` — #ebe5da): Lightly contrasted panels and inset content zones.
- **Taupe Surface** (`{colors.surface-taupe}` — #d8cfbf): A denser neutral for dividers, hover fills, or muted highlight bands.
- **Dark Surface** (`{colors.surface-dark}` — #1f1a16): Hero fallback color and dark cinematic grounding tone.
- **Hero Scrim** (`{colors.surface-hero-scrim}` — rgba(20,16,12,0.28)): Film overlay that keeps white headline text legible without turning the experience into high-contrast poster design.

### Text
- **Ink** (`{colors.ink}` — #181512): Main display text. Not true black; slightly warm and softened.
- **Body** (`{colors.body}` — #2f2a24): Default paragraph and navigation tone.
- **Body Muted** (`{colors.body-muted}` — #6d655b): Secondary descriptive copy.
- **Body Subtle** (`{colors.body-subtle}` — #8e8579): Tertiary metadata, legal lines, and passive UI.
- **On Dark** (`{colors.on-dark}` — #f7f4ef): Text over hero media and dark overlays.

### Borders & Focus
- **Hairline** (`{colors.hairline}` — #d8d1c5): Standard divider line.
- **Hairline Soft** (`{colors.hairline-soft}` — #ece7de): Very light section rules.
- **Border Strong** (`{colors.border-strong}` — #c6bcae): Outline button and active-frame border.
- **Focus Ring** (`{colors.focus-ring}` — #a89269): Accessible keyboard focus color aligned with the metallic accent family.

### Effects
- **Soft Shadow** (`{colors.shadow-soft}`): `0 18px 40px rgba(24,21,18,0.08)` for floating editorial media only. Shadows are rare and diffuse.

## Typography

### Font Family
- **Display / Editorial**: `Iowan Old Style, Baskerville, Georgia, Times New Roman, serif` or a similar refined serif. The homepage uses a classic luxury-magazine voice rather than modern brutalism or Swiss austerity.
- **Body / UI**: `Helvetica Neue, Arial, sans-serif`. Neutral, highly legible, and intentionally anonymous so the serif layer carries the brand expression.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.hero-display}` | 64px | 400 | 1.04 | -0.02em | Primary cinematic hero statement |
| `{typography.display-lg}` | 46px | 400 | 1.08 | -0.015em | Major editorial section headlines |
| `{typography.display-md}` | 34px | 400 | 1.18 | -0.01em | Secondary heritage/storytelling headlines |
| `{typography.eyebrow}` | 12px | 600 | 1.4 | 0.18em | Uppercase pre-head / category label |
| `{typography.title}` | 20px | 500 | 1.4 | 0.02em | Card titles and compact headings |
| `{typography.body-lg}` | 18px | 400 | 1.72 | 0.005em | Lead editorial paragraph |
| `{typography.body}` | 16px | 400 | 1.75 | 0.005em | Default copy |
| `{typography.body-strong}` | 16px | 600 | 1.65 | 0.01em | Emphasis in copy or labels |
| `{typography.caption}` | 14px | 400 | 1.6 | 0.04em | Footer links and ancillary text |
| `{typography.caption-strong}` | 14px | 600 | 1.5 | 0.08em | Footer headings / accordion triggers |
| `{typography.nav-link}` | 13px | 500 | 1.3 | 0.14em | Main nav and menu links |
| `{typography.utility}` | 12px | 500 | 1.4 | 0.12em | Small controls like locale or motion toggle |
| `{typography.button}` | 13px | 600 | 1 | 0.16em | Primary and secondary CTA buttons |
| `{typography.legal}` | 12px | 400 | 1.5 | 0.02em | Legal notices and privacy rows |

### Principles

- **Serif carries the aura.** The luxury signature comes almost entirely from the display type choice and spacing, not from ornate UI decoration.
- **Sans remains discreet.** Navigation, body, utility labels, and footer links are neutral and precise.
- **Uppercase is ceremonial.** Small UI text and CTAs rely on letter-spaced uppercase rather than bold weight or bright color to signal importance.
- **Body copy breathes.** Line-height stays generous, often around `1.7+`, reinforcing a brochure-reading pace.
- **Display text is elegant, not loud.** Weight remains 400; authority comes from scale and spacing, not heaviness.

## Spacing & Layout

- The homepage is built on **large vertical intervals**. Major sections feel separated by 96px to 132px rather than standard web-app spacing.
- Hero modules read as **cinematic chapters**, usually occupying most of the viewport with copy pinned to one edge rather than centered in a generic marketing stack.
- Content sections often use **split layouts**: large media block on one side, editorial copy on the other, with wide gutters.
- The footer becomes a **dense information slab**, contrasting with the generous breathing room above it.

## Components

### Header & Navigation

**`transparent-header`** sits over the opening hero. It is nearly invisible by design: transparent background, light text, sparse controls, and a burger/menu-first pattern rather than a fully exposed category bar. The header behaves more like a gallery overlay than an ecommerce masthead.

**`burger-button`** is text-led rather than icon-heavy. The word "Menu" matters as much as the iconography. This is part of the brand's understated confidence.

### Hero Modules

**`hero-film`** is the defining container: full-bleed video or cinematic still, darkened just enough for headline contrast. The site relies heavily on motion and polished editorial footage.

**`hero-copy-panel`** overlays the film with a soft scrim, white or ivory text, minimal copy, and a single primary CTA. Copy blocks remain compact; the image does most of the storytelling.

**`button-play-ghost`** appears over media controls and uses translucency rather than heavy framing. It should feel like a film control, not an app button.

### Buttons

**`button-primary`** uses Maison Gold on a rectangular chassis with uppercase, letter-spaced text. It is elegant but never oversized. No pill geometry.

**`button-secondary`** is transparent or canvas-backed with a thin border and the same uppercase ceremonial typography. Secondary actions remain formal, not casual.

### Editorial Sections

**`section-split-editorial`** structures long-form institutional storytelling. One side holds headline and copy; the other holds atmospheric stills, workshop photography, or museum imagery.

**`image-story-card`** is barely a card in the SaaS sense. It is more often a framed media block with caption text, sometimes with a gentle shadow if it floats over a lighter field.

**`quote-over-media`** is used when a short statement sits directly on image or video, usually in white text over a darkened region.

**`collection-spotlight`** handles sections like collections, museum, service, and points of sale. It pairs one strong image with a short statement and a single link outward.

### Footer

**`footer-columns`** becomes a major navigational system with many institutional links grouped into Manufacture, Collection, Service, Museum, and Contact.

On smaller screens, these transform into **`footer-accordion-trigger`** rows: uppercase heading, thin divider, expandable content beneath.

**`locale-switch`** and motion preferences are framed as quiet utility controls, not bright badges.

## Do's and Don'ts

### Do
- Use warm ivory and stone neutrals instead of stark white whenever the page needs softness.
- Let serif headlines carry the brand expression; keep the supporting UI quiet.
- Favor thin borders, wide margins, and editorial pacing over compact dense layouts.
- Use uppercase, letter-spaced CTAs with restrained rectangular framing.
- Make imagery cinematic and tactile: enamel, metal, walnut, ateliers, archival interiors, and close craft shots.
- Keep interaction density low. One clear action per module is usually enough.

### Don't
- Don't use saturated tech blues, neon accents, or commerce-red urgency treatments.
- Don't introduce playful rounded pills for primary UI. The brand language is rectilinear and formal.
- Don't overuse shadows, glassmorphism, or card stacking. This system is flatter and quieter.
- Don't switch body typography into a decorative serif; the serif is reserved for emotional hierarchy.
- Don't cram multiple competing CTAs into one storytelling section.
- Don't make the site feel like a generic ecommerce grid. It should remain closer to an editorial maison experience.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Small phone | ≤ 419px | Hero copy compresses to short stacked text; footer becomes accordion-only; motion controls stay visible |
| Phone | 420–767px | Single-column editorial sections; menu-first navigation; CTA widths may expand to full line |
| Tablet | 768–1023px | Split layouts collapse selectively; hero still dominates; footer may remain mixed accordion/columns |
| Desktop | 1024–1439px | Full editorial split layouts; larger hero type; broad gutters |
| Large desktop | ≥ 1440px | Maximum cinematic spacing, long media crops, and roomy footer columns |

### Behavior Notes

- The homepage is already designed mobile-first around a menu trigger rather than a massive exposed desktop nav.
- Footer information density increases substantially on desktop, but mobile preserves access through accordions rather than pruning taxonomy.
- Video and image modules should crop gracefully, keeping watch/product focal points centered or slightly off-center rather than fully centered by default.

## Content Strategy

- Lead with **legacy and craft**, then collections, then service and points of sale.
- Avoid performance-marketing language. Phrases should sound timeless, institutional, and assured.
- Repetition is acceptable when it reinforces maison values; this brand tolerates ceremonial cadence more than most consumer sites.

## Sources

- Homepage: https://www.patek.com/
- English homepage metadata and canonical page: https://www.patek.com/en
