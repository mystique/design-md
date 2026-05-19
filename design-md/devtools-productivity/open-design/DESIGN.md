---
version: alpha
name: Open Design
description: "A local-first design-tool landing page staged like an independent editorial journal. Warm parchment paper carries everything: side rails, issue-number metadata, serif italic emphasis, field coordinates, dashed numeric rings, and artifact photography. The system mixes Inter Tight's compressed technical confidence with Playfair Display's magazine voice, using coral (#ed6f5c) as the single lively accent, mustard as a tiny star glint, and bone cards with thin ink hairlines instead of heavy chrome."

colors:
  primary: "#ed6f5c"
  primary-hover: "#e25e4a"
  primary-soft: "#f08e7c"
  accent-mustard: "#e9b94a"
  accent-olive: "#6e7448"
  ink: "#15140f"
  ink-soft: "#2a2620"
  ink-muted: "#5a5448"
  ink-faint: "#8b8676"
  canvas: "#efe7d2"
  canvas-warm: "#ece4cf"
  canvas-dark: "#ddd2b6"
  surface-bone: "#f7f1de"
  surface-bone-translucent: "#f7f1deb8"
  surface-white-wash: "#ffffff2e"
  line: "#d2c6a9"
  line-soft: "#e0d5b9"
  line-faint: "#e8ddc3"
  on-primary: "#ffffff"
  on-ink: "#efe7d2"
  shadow-ink: "#15140f"

typography:
  display-hero:
    fontFamily: "Inter Tight, Inter, -apple-system, BlinkMacSystemFont, system-ui, sans-serif"
    fontSize: 78px
    fontWeight: 800
    lineHeight: 1.0
    letterSpacing: -2.184px
  display-serif-hero:
    fontFamily: "Playfair Display, Times New Roman, serif"
    fontSize: 78px
    fontWeight: 500
    lineHeight: 1.0
    letterSpacing: -1.404px
    fontStyle: italic
  display-section:
    fontFamily: "Inter Tight, Inter, -apple-system, BlinkMacSystemFont, system-ui, sans-serif"
    fontSize: 66px
    fontWeight: 800
    lineHeight: 1.0
    letterSpacing: -1.848px
  display-editorial:
    fontFamily: "Playfair Display, Times New Roman, serif"
    fontSize: 56px
    fontWeight: 500
    lineHeight: 0.95
    letterSpacing: 0
  headline-card:
    fontFamily: "Inter Tight, Inter, -apple-system, BlinkMacSystemFont, system-ui, sans-serif"
    fontSize: 22px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: -0.308px
  lead:
    fontFamily: "Inter, -apple-system, system-ui, sans-serif"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: 0
  body:
    fontFamily: "Inter, -apple-system, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-sm:
    fontFamily: "Inter, -apple-system, system-ui, sans-serif"
    fontSize: 13.5px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  nav-link:
    fontFamily: "Inter Tight, Inter, -apple-system, BlinkMacSystemFont, system-ui, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.0
    letterSpacing: 0
  button:
    fontFamily: "Inter Tight, Inter, -apple-system, BlinkMacSystemFont, system-ui, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.0
    letterSpacing: -0.07px
  button-small:
    fontFamily: "Inter Tight, Inter, -apple-system, BlinkMacSystemFont, system-ui, sans-serif"
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.0
    letterSpacing: 0
  label:
    fontFamily: "Inter Tight, Inter, -apple-system, BlinkMacSystemFont, system-ui, sans-serif"
    fontSize: 11px
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: 2.42px
    textTransform: uppercase
  metadata:
    fontFamily: "Inter Tight, Inter, -apple-system, BlinkMacSystemFont, system-ui, sans-serif"
    fontSize: 10.5px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 1.89px
    textTransform: uppercase
  coordinate:
    fontFamily: "JetBrains Mono, SF Mono, Menlo, monospace"
    fontSize: 10px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0.4px
  code-inline:
    fontFamily: "JetBrains Mono, SF Mono, Menlo, monospace"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0
  roman:
    fontFamily: "Playfair Display, Times New Roman, serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.0
    letterSpacing: 0.7px
    fontStyle: italic

rounded:
  none: 0px
  xs: 4px
  sm: 6px
  md: 8px
  lg: 14px
  xl: 18px
  xxl: 24px
  pill: 999px
  full: 9999px

spacing:
  hair: 1px
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section-tight: 90px
  section: 130px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 14px 22px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.pill}"
  button-ghost:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 14px 22px
  nav-cta:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-ink}"
    typography: "{typography.button-small}"
    rounded: "{rounded.pill}"
    padding: 9px 16px
  nav-cta-ghost:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button-small}"
    rounded: "{rounded.pill}"
    padding: 9px 16px
  topbar:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-faint}"
    typography: "{typography.metadata}"
    height: 36px
  global-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 82px
  side-rail:
    backgroundColor: transparent
    textColor: "{colors.ink-faint}"
    typography: "{typography.metadata}"
    width: 36px
  editorial-rule:
    backgroundColor: transparent
    textColor: "{colors.ink-faint}"
    typography: "{typography.metadata}"
    padding: 18px 0 0
  hero-art-frame:
    backgroundColor: transparent
    textColor: "{colors.ink-faint}"
    rounded: "{rounded.none}"
    padding: 0
  annotation-chip:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-faint}"
    typography: "{typography.metadata}"
    rounded: "{rounded.sm}"
    padding: 10px 12px
  stat-ring:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.metadata}"
    rounded: "{rounded.full}"
    size: 34px
  stat-ring-coral:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.metadata}"
    rounded: "{rounded.full}"
    size: 34px
  bone-card:
    backgroundColor: "{colors.surface-bone}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.xl}"
    padding: 28px 26px 32px
  lab-image-card:
    backgroundColor: "{colors.surface-bone}"
    textColor: "{colors.ink}"
    rounded: "{rounded.lg}"
    padding: 0
  work-section-panel:
    backgroundColor: "{colors.surface-bone}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xxl}"
    padding: 90px 44px
  work-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.xl}"
    padding: 32px
  pill-filter:
    backgroundColor: transparent
    textColor: "{colors.ink-soft}"
    typography: "{typography.button-small}"
    rounded: "{rounded.pill}"
    padding: 9px 18px
  pill-filter-active:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-small}"
    rounded: "{rounded.pill}"
    padding: 9px 18px
  code-inline:
    backgroundColor: "{colors.surface-bone}"
    textColor: "{colors.ink}"
    typography: "{typography.code-inline}"
    rounded: "{rounded.xs}"
    padding: 1px 6px
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-muted}"
    typography: "{typography.body-sm}"
    padding: 96px 0 0
---

## Overview

Open Design's web presence is built as a **software studio disguised as an independent design magazine**. The page does not reach for the usual SaaS gradient hero, black dashboard chrome, or glassy AI motif. Instead, it opens on a warm parchment sheet, narrow editorial side rails, issue metadata, coordinates, roman section markers, serif italic insertions, and artifact plates. The design says "tooling", but the surface says "journal".

The most important move is the tension between two type voices. `Inter Tight` carries the product's practical, technical side: nav, labels, big display headlines, buttons, and metadata. `Playfair Display` interrupts that rational grid with italic editorial emphasis, roman numerals, and oversized magazine words. The brand personality comes from the alternation: precise agent-workflow language rendered with print-culture cues.

Color is restrained and warm. Parchment (`{colors.canvas}`) dominates every major section. Coral (`{colors.primary}`) is the only expressive action color and appears in labels, dots, CTAs, active filters, pulse indicators, and headline punctuation. Mustard and olive appear as small secondary signals, never as competing CTA colors. Depth comes from paper texture, thin ink hairlines, corner marks, photo plates, and one soft long shadow on cards.

**Key Characteristics:**
- Warm editorial parchment canvas with subtle grain, not a clean white SaaS page.
- Side rails and topbar metadata create the feeling of a numbered issue or field report.
- Inter Tight + Playfair Display pairing: compressed technical sans with italic magazine serif.
- Coral accent (`{colors.primary}`) used consistently for CTAs, labels, live dots, active pills, section numerals, and punctuation.
- Thin ink hairlines and dashed rings replace heavy borders and bright UI chrome.
- Artifact imagery is framed like plate photography: corner crop marks, annotations, captions, indexes.
- Cards are bone-colored, lightly shadowed, and paper-like rather than glassy or floating.
- Motion is editorial: reveal-on-scroll, slow marquee wires, tiny hover lifts, not springy product-app animation.

## Colors

> **Source analyzed:** `https://open-design.ai/` homepage and its loaded stylesheet `/_astro/_slug_.CnvQ8Wom.css`. Dynamic GitHub counts and release labels are content, not color tokens.

### Brand & Accent
- **Coral Signal** (`{colors.primary}` - #ed6f5c): The brand's active voice. Used for primary CTAs, label rules, dots, roman numerals, live pulses, active filters, and the hero period. It should read like editorial markup in red pencil, not like an error color.
- **Coral Hover** (`{colors.primary-hover}` - #e25e4a): Hover fill for primary CTAs. Slightly deeper than the base coral, used only when an interactive surface needs response.
- **Soft Coral** (`{colors.primary-soft}` - #f08e7c): A gentler accent value for secondary highlights and tonal variants.
- **Mustard Star** (`{colors.accent-mustard}` - #e9b94a): A tiny highlight, most visibly the star glyph in the GitHub CTA. Use sparingly as an ornament, not as a second brand color.
- **Olive Archive** (`{colors.accent-olive}` - #6e7448): A muted archival green for classification and companion system badges. It supports the field-note mood without competing with coral.

### Surface
- **Parchment** (`{colors.canvas}` - #efe7d2): The dominant page canvas. Topbar, nav, hero, wire band, section backgrounds, and footer all sit on this warm paper color.
- **Warm Parchment** (`{colors.canvas-warm}` - #ece4cf): A near-neighbor for subtle surface shifts.
- **Dark Parchment** (`{colors.canvas-dark}` - #ddd2b6): A deeper paper tone used for quiet separation and background shading.
- **Bone** (`{colors.surface-bone}` - #f7f1de): Cards, inline code, search panels, and paper modules. It is lighter than parchment and reads as a sheet placed on a sheet.
- **Translucent Bone** (`{colors.surface-bone-translucent}` - #f7f1deb8): Panel fills that need to show a little paper atmosphere underneath.
- **White Wash** (`{colors.surface-white-wash}` - #ffffff2e): Semi-transparent wash used inside cards and panels, especially preview headers and small surfaces.

### Text
- **Ink** (`{colors.ink}` - #15140f): The primary text color. Near-black with a brown undertone; it keeps the system from feeling stark.
- **Soft Ink** (`{colors.ink-soft}` - #2a2620): Lead paragraphs and secondary action text.
- **Muted Ink** (`{colors.ink-muted}` - #5a5448): Body metadata, card copy, and footer text.
- **Faint Ink** (`{colors.ink-faint}` - #8b8676): Side rails, coordinates, indexes, captions, and low-emphasis section metadata.
- **On Primary** (`{colors.on-primary}` - #ffffff): Text on coral CTA fills.
- **On Ink** (`{colors.on-ink}` - #efe7d2): Text on the black/nav CTA fill; it intentionally uses parchment rather than pure white.

### Hairlines & Borders
- **Line** (`{colors.line}` - #d2c6a9): Canonical visible hairline, derived from ink at about 16% opacity on parchment.
- **Line Soft** (`{colors.line-soft}` - #e0d5b9): Inner separators and low-emphasis borders, about 8% ink equivalent.
- **Line Faint** (`{colors.line-faint}` - #e8ddc3): Side-rail borders and atmospheric separators.

### Texture & Atmosphere
The page uses a fixed paper overlay composed of radial warmth and SVG fractal noise. This is part of the design language: paper grain is the background texture. Do not replace it with a purple/blue AI gradient, bokeh, or glassmorphism. Atmosphere should feel printed and archival.

## Typography

### Font Family
- **Display / UI Sans:** `Inter Tight, Inter, -apple-system, BlinkMacSystemFont, system-ui, sans-serif`. Used for hero headlines, nav, buttons, labels, stats, and cards. It gives the site a compact technical posture.
- **Body:** `Inter, -apple-system, system-ui, sans-serif`. Used for paragraphs and longer reading surfaces. More comfortable than Inter Tight at text sizes.
- **Editorial Serif:** `Playfair Display, Times New Roman, serif`. Used for italic emphasis inside display headlines, roman numerals, and magazine-scale footer words.
- **Mono:** `JetBrains Mono, SF Mono, Menlo, monospace`. Used for coordinates, command snippets, hashes, and developer identifiers.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---:|---:|---:|---:|---|
| `{typography.display-hero}` | 78px | 800 | 1.00 | -2.184px | Hero sans headline on desktop |
| `{typography.display-serif-hero}` | 78px | 500 italic | 1.00 | -1.404px | Italic words inside hero headline |
| `{typography.display-section}` | 66px | 800 | 1.00 | -1.848px | Section headlines |
| `{typography.display-editorial}` | 56px | 500 | 0.95 | 0 | Editorial serif display / plugin panels |
| `{typography.headline-card}` | 22px | 700 | 1.05 | -0.308px | Capability card titles |
| `{typography.lead}` | 17px | 400 | 1.65 | 0 | Long section lead paragraphs |
| `{typography.body}` | 16px | 400 | 1.55 | 0 | Default body copy |
| `{typography.body-sm}` | 13.5px | 400 | 1.55 | 0 | Compact card copy |
| `{typography.nav-link}` | 14px | 500 | 1.00 | 0 | Main navigation links |
| `{typography.button}` | 14px | 500 | 1.00 | -0.07px | Primary and ghost CTAs |
| `{typography.button-small}` | 13px | 500 | 1.00 | 0 | Nav CTAs and compact buttons |
| `{typography.label}` | 11px | 600 | 1.30 | 2.42px | Red editorial labels |
| `{typography.metadata}` | 10.5px | 500 | 1.40 | 1.89px | Topbar, rules, annotations |
| `{typography.coordinate}` | 10px | 400 | 1.40 | 0.4px | Coordinates, hashes, field data |
| `{typography.code-inline}` | 14px | 400 | 1.20 | 0 | Inline command snippets |
| `{typography.roman}` | 14px | 500 italic | 1.00 | 0.7px | Roman section indexes |

### Principles

- **Sans headlines are tight and heavy.** The main headline uses `Inter Tight` at weight 800 with negative tracking. It should feel compressed and intentional, not loose or friendly.
- **Serif italics are interruptions.** Use Playfair italic for key words and section numerals, not for entire paragraphs. The serif should feel like an editor's marginal note.
- **Metadata is uppercase and spaced out.** Topbar, side rails, section rules, and captions use 0.16-0.42em letter spacing. This is what makes the page feel like an issue, not a dashboard.
- **Body copy stays readable.** Long copy uses regular Inter at 16-17px with 1.55-1.65 line-height. The system is editorial but not dense.
- **Mono is factual.** Coordinates, commands, version labels, and hashes use JetBrains Mono. Do not use mono for decoration without data meaning.

## Layout

### Spacing System
- **Base rhythm:** 8px, with 10-14px micro-adjustments for metadata and button padding.
- **Section padding:** `{spacing.section}` (130px) for full editorial sections; `{spacing.section-tight}` (90px) for compact panels.
- **Container width:** 1360px default with 64px side padding on desktop; reduced to 44px, 32px, 24px, and 16px across smaller breakpoints.
- **Hero split:** Two-column composition: copy at roughly 0.78fr and artifact plate at 1.22fr.
- **Card gaps:** 18-22px in capability/lab grids; 36-80px for major two-column editorial layouts.

### Grid & Composition
Open Design uses grids as editorial scaffolding, not app layout. The top-level page alternates between:

- Hero split: copy + large art plate.
- Wire band: source label + two marquee rows.
- Two-column editorial sections: copy/art or art/copy.
- Dense card grids: capabilities, labs, method, partners.
- A framed selected-work panel with its own internal grid.

Section rules are crucial. Each major section begins with a hairline, roman numeral, taxonomy phrase, dot marker, and page count (`002 / 008`). This is the site's page-turn device; it should be preserved when adding sections.

### Whitespace Philosophy
Whitespace feels like margins in a printed magazine. The page is spacious but not sterile: side rails, metadata, corner marks, captions, and art indexes keep empty areas active. Large type and artifact imagery are allowed to breathe; card grids then create a denser catalog rhythm.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Paper flat | Parchment canvas, no shadow | Page background, nav, topbar, section bands |
| Hairline | 1px ink-derived line | Section rules, side rails, card borders, panel dividers |
| Wash panel | Bone or translucent bone fill | Cards, preview panels, inline code, plugin panels |
| Soft paper lift | `0 30px 60px -30px rgba(21, 20, 15, 0.18)` | Bone cards and image tiles |
| Artifact frame | Corner marks + annotations | Hero art, capability art, cta art |

Depth is paper-based. Cards lift gently, but there is no glossy shadow stack. The strongest visual depth comes from the relationship between the parchment background, lighter bone cards, printed grain, and framed artifact images.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---:|---|
| `{rounded.none}` | 0px | Full paper sections and art frames |
| `{rounded.xs}` | 4px | Inline code snippets |
| `{rounded.sm}` | 6px | Annotation chips and small overlays |
| `{rounded.md}` | 8px | Plugin panels and inputs |
| `{rounded.lg}` | 14px | Image tiles |
| `{rounded.xl}` | 18px | Bone cards and work cards |
| `{rounded.xxl}` | 24px | Large selected-work panel on tablet/mobile |
| `{rounded.pill}` | 999px | CTAs, filters, badges |
| `{rounded.full}` | 9999px | Dots, rings, circular buttons |

### Image Geometry
- **Hero art:** Large transparent artifact image, object-fit contain, annotated at all four corners. It is not placed inside a card.
- **Method images:** Step cards use image plates beneath text, usually in compact rectangular frames.
- **Lab cards:** Tall 4:5 image previews on bone cards.
- **Work cards:** Editorial cards with large visual previews and metadata rows.
- **Footer mega word:** Oversized serif/sans wordmark treatment functions like a typographic image.

## Components

### Navigation & Rails

**`topbar`** - Thin issue metadata bar above the main nav. Background `{colors.canvas}`, text `{colors.ink-faint}`, typography `{typography.metadata}`, bottom border `{colors.line}`. It carries volume/issue information, filing taxonomy, license, live release, and locale links.

**`global-nav`** - Sticky parchment navigation, height around 82px including vertical padding. Left brand lockup includes a 36px mark, brand name, and an optional metadata block. Center nav links use `{typography.nav-link}` with tiny superscript counts. Right cluster uses `{component.nav-cta-ghost}`, `{component.nav-cta}`, and a circular status dot.

**`side-rail`** - Fixed 36px vertical rail on both desktop edges. Text is uppercase, tightly tracked, and vertical. It provides the publication-frame effect. Hide below 1280px.

**`editorial-rule`** - Section header rule. Top border, roman numeral in coral serif italic, metadata group in uppercase sans, right-aligned section count. Required for major sections.

### Buttons

**`button-primary`** - Coral pill CTA with white text, `{typography.button}`, 14px x 22px padding, subtle coral shadow. Hover moves up 1px and shifts to `{colors.primary-hover}`. Used for "Star us on GitHub" and high-intent actions.

**`button-ghost`** - Transparent pill with ink text and a low-opacity ink border. Same padding and typography as primary. Used for secondary CTAs such as download or read-more actions.

**`nav-cta`** - Compact black pill in the nav. Background `{colors.ink}`, text `{colors.on-ink}`, 9px x 16px padding. Star glyph uses `{colors.accent-mustard}`.

**`nav-cta-ghost`** - Compact outlined pill in the nav. Transparent background, ink text, 1px ink hairline. Uses a down-arrow glyph for download.

**`pill-filter`** - Outlined category chip used in dense catalog sections. Active state becomes coral fill with white text and a softened count separator.

### Editorial Marks

**`label`** - Small uppercase coral label with a leading 18px horizontal rule. This appears before major headings and should always include enough letter-spacing to feel printed.

**`stat-ring`** - 34px circular stat badge with dashed or solid border. Used in hero stats for counts like `131`, `150`, and `12`. Coral variant marks the most expressive stat.

**`annotation-chip`** - Small translucent parchment/bone overlay used on hero art indexes. Rounded `{rounded.sm}`, border `{colors.line-soft}`, typography `{typography.metadata}` or `{typography.coordinate}`.

**`code-inline`** - Bone inline command capsule for snippets like `pnpm tools-dev`. Keep the radius small; it should feel like a printed command tag, not a pill CTA.

### Cards & Panels

**`bone-card`** - Core capability card. Background `{colors.surface-bone}`, rounded `{rounded.xl}`, padding `28px 26px 32px`, subtle long paper shadow plus inset hairline. Content structure: serif/coral number row, small icon, `{typography.headline-card}` title, `{typography.body-sm}` copy, circular arrow mark. Hover lifts by 3px.

**`lab-image-card`** - Visual catalog card with 4:5 image area, bone background, `{rounded.lg}` image crop, paper shadow, and compact metadata below. Used for systems/templates/craft previews.

**`work-section-panel`** - Large framed selected-work area. It sits inside page margins instead of spanning full bleed, uses bone fill, generous padding, and a large radius on smaller screens.

**`work-card`** - Editorial feature card inside the selected-work panel. Image, label row, title, description, and metadata row. Cards can be slightly rotated/offset on desktop, then normalize on tablet.

**`hero-art-frame`** - Frameless artifact container with corner marks, annotations, an index overlay, and object-fit contain imagery. This is a signature component; do not replace it with a generic screenshot card.

### Footer

**`footer`** - Parchment footer with multi-column link grid, brand block, download pill, bottom metadata row, and a giant typographic "Open Design." wordmark. Footer links are quiet and ink-toned; coral only appears in small live/heart accents and inline emphasis.

## Do's and Don'ts

### Do
- Use parchment (`{colors.canvas}`) as the dominant page color and bone (`{colors.surface-bone}`) for placed-card surfaces.
- Use coral (`{colors.primary}`) for the entire action and editorial-marking system: labels, dots, CTAs, active filters, section numerals, and headline punctuation.
- Pair heavy Inter Tight headlines with Playfair italic emphasis inside the same line.
- Preserve issue metadata: side rails, roman numerals, section counts, coordinates, hashes, and tiny catalog numbers.
- Use thin ink hairlines instead of heavy borders.
- Give artifact images corner marks, captions, and annotations so they feel like plates in a printed issue.
- Use long soft paper shadows only on cards and visual tiles, not on the nav or hero type.
- Keep button shapes pill-like but card shapes modest: pills for actions, 14-18px radius for paper modules.

### Don't
- Don't turn the brand into a generic AI gradient system. No purple-blue glow, glass panels, bokeh blobs, or neon grid backgrounds.
- Don't use pure white as the primary canvas; white appears only as a translucent wash.
- Don't introduce another CTA color. Mustard and olive are supporting editorial accents only.
- Don't set whole paragraphs in Playfair; serif is for emphasis, numerals, and display moments.
- Don't remove metadata as "decoration." The metadata is the structure that makes the site feel like Open Design.
- Don't over-round cards. The paper modules should feel designed, not bubbly.
- Don't put artifact imagery inside generic browser mockups unless the content itself is a browser preview.
- Don't use heavy drop shadows or elevation stacks. Depth should stay paper-soft.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---:|---|
| Wide desktop | > 1280px | Side rails visible; 1360px container with 64px padding |
| Desktop | 1081-1280px | Side rails hidden; container padding 44px; nav still full |
| Small desktop | 881-1080px | Container padding 32px; some footer/link columns hide; hero display scales down |
| Tablet | 641-880px | Hero and major two-column sections collapse to one column; nav links and nav CTAs hide; hero art becomes 4:5 |
| Large phone | 561-640px | Hero CTAs wrap; large wordmark scales; footer simplifies |
| Phone | 421-560px | Container padding 16px; card grids become one column; sections reduce to 80px padding |
| Small phone | <= 420px | Container padding 14px; metadata tightens; work cards reduce padding |

### Collapsing Strategy
- **Side rails:** desktop-only, hidden at `max-width: 1280px`.
- **Topbar:** keeps compact issue metadata, but middle metadata hides below `1200px`.
- **Nav:** main links, brand metadata, and nav CTAs hide at `max-width: 880px`; brand mark and name remain.
- **Hero:** two-column split collapses to a single-column stack below `880px`; image plate changes to a 4:5 aspect-ratio container.
- **Card grids:** 5-column lab grids compress to 2 columns at tablet and 1 column on phone; capability cards move from 2 columns to 1 column at small phone.
- **Section type:** large display sizes use CSS clamp; never scale with viewport width without min/max bounds.

### Motion
- Marquee rows move slowly and pause on hover.
- Reveal animations fade/translate/scale in with staggered delays.
- Buttons hover by changing fill and translating `-1px`.
- Cards hover by translating `-2px` to `-3px`.
- Respect `prefers-reduced-motion: reduce` by removing reveal and marquee motion.

## Iteration Guide

1. Start every major section with `{component.editorial-rule}` before adding content.
2. Use `{typography.label}` above section headings and keep the coral leading rule.
3. Combine Inter Tight display text with Playfair italic emphasis; do not choose only one voice.
4. Keep all primary actions on `{component.button-primary}` or `{component.nav-cta}`. Do not invent new CTA colors.
5. Use `{component.bone-card}` for capabilities and `{component.lab-image-card}` for catalog previews.
6. Prefer annotations, coordinates, issue numbers, and corner marks over decorative illustration.
7. Use token references in new components. Avoid inline hex values in prose or implementation.
8. When a new visual surface feels too plain, add editorial metadata or a hairline first; add shadow only if it is a placed paper/card object.

## Known Gaps

- Only the public homepage and shared stylesheet were analyzed; deeper pages such as `/skills/`, `/systems/`, `/templates/`, `/craft/`, and `/blog/` may introduce additional component variants.
- The documented colors convert several rgba border and wash values into stable hex approximations over the parchment base. The production CSS uses alpha values for many lines and fills.
- Exact image asset art direction is content-specific; this document captures the frame language, not the individual illustrations.
- Form validation, destructive states, and error messages were not surfaced in the analyzed homepage.
- Live GitHub stars, contributors, and release values are dynamic content and should not be treated as fixed design tokens.
