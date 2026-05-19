---
version: alpha
name: Saint Laurent
description: |
  A severe black-and-white luxury commerce system built from uppercase taxonomy, cinematic restraint, and rectangular product presentation. The interface uses almost no chromatic accent: black text on white, white text on black, thin gray hairlines, and occasional deep charcoal panels. Navigation is intentionally dense and editorial, exposing both fashion commerce and SL Productions cultural content through a disciplined mega-menu.

colors:
  primary: "#000000"
  primary-soft: "#1a1a1a"
  primary-muted: "#333333"
  ink: "#000000"
  body: "#1f1f1f"
  body-muted: "#666666"
  body-subtle: "#8c8c8c"
  on-primary: "#ffffff"
  on-dark: "#ffffff"
  canvas: "#ffffff"
  canvas-soft: "#f7f7f7"
  surface-product: "#f4f4f4"
  surface-menu: "#ffffff"
  surface-inverse: "#000000"
  surface-charcoal: "#111111"
  surface-scrim: "rgba(0,0,0,0.34)"
  hairline: "#d8d8d8"
  hairline-soft: "#eeeeee"
  border-strong: "#000000"
  focus-ring: "#000000"
  error: "#b00020"
  shadow-none: "none"

typography:
  hero-display:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 64px
    fontWeight: 400
    lineHeight: 0.96
    letterSpacing: 0.02em
    textTransform: uppercase
  display-lg:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 44px
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: 0.03em
    textTransform: uppercase
  display-md:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 30px
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: 0.035em
    textTransform: uppercase
  nav-primary:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: 0.04em
    textTransform: uppercase
  nav-secondary:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0.04em
    textTransform: uppercase
  nav-tertiary:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.75
    letterSpacing: 0.02em
    textTransform: uppercase
  body-lg:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-strong:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.45
    letterSpacing: 0
  product-name:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0.01em
    textTransform: uppercase
  product-meta:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0
  button:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: 0.08em
    textTransform: uppercase
  caption:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0.02em
  caption-strong:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.45
    letterSpacing: 0.08em
    textTransform: uppercase
  legal:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0.01em

rounded:
  none: 0px
  xs: 1px
  sm: 2px
  md: 4px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 72px
  editorial: 112px

components:
  site-header:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-primary}"
    height: 72px
    borderBottom: "1px solid {colors.hairline-soft}"
  logo-wordmark:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.display-md}"
    rounded: "{rounded.none}"
  nav-button:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.nav-primary}"
    rounded: "{rounded.none}"
    padding: 12px 0px
  utility-button:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.nav-secondary}"
    rounded: "{rounded.none}"
    padding: 10px 0px
  mega-menu:
    backgroundColor: "{colors.surface-menu}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-secondary}"
    rounded: "{rounded.none}"
    borderTop: "1px solid {colors.hairline-soft}"
  mega-menu-column-heading:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.nav-primary}"
    rounded: "{rounded.none}"
  mega-menu-link:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.nav-tertiary}"
  hero-media:
    backgroundColor: "{colors.surface-inverse}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    minHeight: 760px
  hero-overlay:
    backgroundColor: "{colors.surface-scrim}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-md}"
    padding: 40px
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 16px 28px
    height: 46px
  button-primary-active:
    backgroundColor: "{colors.primary-soft}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.none}"
  button-secondary:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    border: "1px solid {colors.border-strong}"
    padding: 15px 28px
    height: 46px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.nav-secondary}"
    borderBottom: "1px solid currentColor"
  product-grid:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.product-name}"
    columns: 4
    gap: 1px
  product-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.product-name}"
    rounded: "{rounded.none}"
    padding: 0px
  product-image-stage:
    backgroundColor: "{colors.surface-product}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    aspectRatio: "3 / 4"
    padding: 0px
  product-meta:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body-muted}"
    typography: "{typography.product-meta}"
  filter-bar:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-secondary}"
    borderBottom: "1px solid {colors.hairline}"
    padding: 18px 24px
  search-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    border: "1px solid {colors.border-strong}"
    padding: 13px 14px
    height: 44px
  cultural-index:
    backgroundColor: "{colors.surface-inverse}"
    textColor: "{colors.on-dark}"
    typography: "{typography.nav-secondary}"
    padding: 72px 0px
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.caption}"
    borderTop: "1px solid {colors.hairline}"
    padding: 56px 0px 32px
  footer-heading:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.caption-strong}"
    rounded: "{rounded.none}"
---

## Overview

Saint Laurent's online store is an exercise in severe reduction. The site presents luxury commerce through black, white, uppercase typography, and a dense editorial menu rather than a warm boutique tone. On the analyzed U.S. homepage, the visible navigation taxonomy begins with Highlights, Women, Men, and SL Productions, then expands into handbags, shoes, resort, seasonal drops, gifts, ready-to-wear, accessories, jewelry, and cultural film content.

The most distinctive signal is not color; it is discipline. Links are uppercase. Buttons are rectangular. Surfaces are flat. The interface avoids decorative brand color, rounded SaaS controls, and soft luxury neutrals. Even product and category names such as MOMBASA, AMALIA, ICARE, JAMIE, LE 5 à 7, LOULOU, PUFFER, CASSANDRE, GABY, NIKI, KATE, SAC DE JOUR, and OPYUM read as a typographic index.

The presence of **SL Productions** changes the brand system from simple ecommerce to cultural house. Directors and years appear in the navigation — Jim Jarmusch, Claire Denis, David Cronenberg, Paolo Sorrentino, Pedro Almodóvar, Jean-Luc Godard, Wong Kar Wai, Gaspar Noé — making the site feel part fashion catalog, part film archive.

**Key Characteristics:**
- Near-monochrome interface: black, white, charcoal, and gray hairlines.
- All-caps navigation and product taxonomy as the core brand voice.
- Dense mega-menu with both commerce and cultural content.
- Rectangular buttons and product stages; almost no rounded UI.
- Editorial severity over decorative luxury warmth.
- Product categories organized by season, gender, line, and object type.
- SL Productions treated as a first-class navigation area rather than a marketing footnote.

## Colors

> **Source page analyzed:** https://www.ysl.com/en-us via lightpanda MCP on 2026-05-19. The Markdown extractor returned empty, so DOM, title, links, buttons, navigation text, and page metadata were inspected directly.

### Brand & Accent

- **Black** (`{colors.primary}` — #000000): The only true action color and the primary brand surface. Filled buttons, inverse media panels, and editorial anchors use black.
- **Soft Black** (`{colors.primary-soft}` — #1a1a1a): Pressed state for filled buttons or dark panel variants.
- **Muted Black** (`{colors.primary-muted}` — #333333): Secondary dark text and charcoal separators.

### Surface

- **Canvas** (`{colors.canvas}` — #ffffff): Main ecommerce surface and menu background.
- **Soft Canvas** (`{colors.canvas-soft}` — #f7f7f7): Product or utility sections where pure white needs a subtle break.
- **Product Surface** (`{colors.surface-product}` — #f4f4f4): Neutral product-stage background.
- **Inverse Surface** (`{colors.surface-inverse}` — #000000): Hero media fallback and SL Productions-style cultural surfaces.
- **Charcoal** (`{colors.surface-charcoal}` — #111111): Dark editorial modules that need softer contrast than pure black.

### Text

- **Ink** (`{colors.ink}` — #000000): Primary navigation, headings, buttons, and product names.
- **Body** (`{colors.body}` — #1f1f1f): Default prose.
- **Body Muted** (`{colors.body-muted}` — #666666): Product meta, price, secondary service copy.
- **Body Subtle** (`{colors.body-subtle}` — #8c8c8c): Passive metadata and legal text.
- **On Dark** (`{colors.on-dark}` — #ffffff): Text over black media or cultural panels.

### Borders & Effects

- **Hairline** (`{colors.hairline}` — #d8d8d8): Standard product, filter, and footer divider.
- **Hairline Soft** (`{colors.hairline-soft}` — #eeeeee): Header and low-emphasis menu rules.
- **Border Strong** (`{colors.border-strong}` — #000000): Outline buttons and high-contrast inputs.
- **Shadow None** (`{colors.shadow-none}`): Shadows are intentionally absent from the core system.

## Typography

### Font Family

- **Primary:** `Helvetica Neue, Arial, sans-serif`. The site voice is anonymous, sharp, and international.
- **Logo:** The Saint Laurent/YSL lockup should be treated as a brand asset, not approximated through body text.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.hero-display}` | 64px | 400 | 0.96 | 0.02em | Campaign and hero statements |
| `{typography.display-lg}` | 44px | 400 | 1.05 | 0.03em | Major uppercase editorial headline |
| `{typography.display-md}` | 30px | 400 | 1.15 | 0.035em | Section headings and logo-scale labels |
| `{typography.nav-primary}` | 13px | 500 | 1.25 | 0.04em | Primary nav groups |
| `{typography.nav-secondary}` | 12px | 400 | 1.45 | 0.04em | Mega-menu groups and utility controls |
| `{typography.nav-tertiary}` | 12px | 400 | 1.75 | 0.02em | Dense menu item lists |
| `{typography.body}` | 16px | 400 | 1.5 | 0 | Default prose |
| `{typography.product-name}` | 14px | 400 | 1.45 | 0.01em | Uppercase product names |
| `{typography.product-meta}` | 13px | 400 | 1.45 | 0 | Prices and variants |
| `{typography.button}` | 12px | 500 | 1 | 0.08em | Rectangular CTAs |
| `{typography.caption}` | 12px | 400 | 1.5 | 0.02em | Footer and legal support |

### Principles

- **Uppercase is structural.** It is not a decorative flourish; it defines navigation, categories, buttons, and product names.
- **Keep weights restrained.** Use 400 and 500 far more than 600 or 700. Authority comes from contrast and capitalization.
- **Letter spacing is controlled.** Navigation and buttons can open slightly; body copy should not be tracked out.
- **No expressive serif layer.** Saint Laurent's digital voice is stark sans-serif, not heritage serif.

## Layout

### Spacing System

- **Base unit:** 8px, with structural jumps at 24, 32, 48, 72, and 112px.
- **Header:** About 72px tall with minimal visible chrome.
- **Mega-menu:** Dense multi-column lists with narrow leading; hierarchy is carried by uppercase headings and spacing.
- **Product grids:** Tight, rectilinear, and image-led. Gutters can be as thin as 1px in high-fashion grid contexts.

### Grid & Container

- **Mega-menu columns:** Grouped by taxonomy. Examples from the current page: Highlights, Women, Men, SL Productions.
- **Product grid:** Four columns on desktop, with product stages and compact metadata.
- **Cultural pages:** Can invert to black surfaces and behave more like a film index than a shop page.

### Whitespace Philosophy

Whitespace is strict rather than soft. Large media moments may be expansive, but commerce grids and menu taxonomies are intentionally compressed. The contrast between cinematic emptiness and dense uppercase lists is part of the brand's tension.

## Components

### Header & Navigation

**`site-header`** is minimal and white with black text. It exposes Menu, Search, Login, Cart, and top-level category controls without decorative color.

**`nav-button`** is transparent and uppercase. Active state should use underline, border, or weight shift rather than color.

**`mega-menu`** is central to the site. It contains category groups such as Highlights, Women, Men, and SL Productions, then expands into product lines, seasons, and cultural indexes. Keep it typographic and flat.

**`mega-menu-link`** should read like an index entry. Avoid icons, thumbnails, badges, and colored pills inside the menu unless a specific campaign surface requires them.

### Hero & Cultural Surfaces

**`hero-media`** is black-backed and cinematic. It can carry white uppercase type or remain almost silent with a single CTA.

**`cultural-index`** supports the SL Productions side of the brand. It should feel like a film archive: black or charcoal canvas, white uppercase names, year groupings, and sparse links.

### Buttons & Links

**`button-primary`** is a black rectangle with white uppercase text. It should not be rounded.

**`button-secondary`** is a white or transparent rectangle with a black border. Use for lower-emphasis commerce actions and service flows.

**`text-link`** is an uppercase underlined link. This is often more appropriate than a filled button for editorial and menu CTAs.

### Product Browsing

**`product-grid`** is tight and rectangular. The grid should present products as a severe visual catalog rather than a lifestyle marketplace.

**`product-card`** is flat. Do not add drop shadows, rounded corners, ratings, or promotional overlays.

**`product-image-stage`** uses neutral gray or white and a tall fashion aspect ratio. Let photography carry depth.

**`filter-bar`** is a thin utility row with uppercase filters and black text. It should feel like a sorting instrument, not a pill-chip system.

## Do's and Don'ts

### Do

- Use black and white as the primary visual system.
- Set navigation, buttons, category names, and product names in uppercase.
- Keep geometry rectilinear: square cards, square buttons, square image stages.
- Let the mega-menu be dense; density is part of the fashion-index feel.
- Treat SL Productions as a cultural archive with its own dark editorial mode.
- Use hairlines instead of shadows to divide surfaces.

### Don't

- Don't introduce a luxury gold, beige, or warm neutral palette.
- Don't use rounded pills for filters or CTAs.
- Don't add gradients, glass effects, or soft shadows.
- Don't use colorful badges, sale ribbons, star ratings, or marketplace-style urgency.
- Don't replace uppercase taxonomy with casual sentence-case labels.
- Don't make the UI friendly at the expense of severity.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Small phone | ≤ 419px | Menu-first navigation; product grid becomes single column or tight two-up where imagery permits |
| Phone | 420–767px | Mega-menu becomes stacked accordion; utility controls remain text-based |
| Tablet | 768–1023px | Product grids become 2–3 columns; hero type reduces sharply |
| Desktop | 1024–1439px | Full mega-menu taxonomy and four-up product grids |
| Large desktop | ≥ 1440px | Large media modules expand; grids stay disciplined rather than adding excessive columns |

### Behavior Notes

- Preserve uppercase hierarchy on mobile; do not switch to conversational labels.
- Product stages should stay rectangular and crop fashion imagery deliberately.
- Dense menu lists can become accordions, but the taxonomy should not be pruned.
- Touch targets may be larger than their visual text; the visible design can remain spare.

## Content Strategy

- Lead with product line, season, and cultural authority rather than benefit copy.
- Product families and named bags matter: Mombasa, Icare, Jamie, Le 5 à 7, Loulou, Cassandre, Gaby, Niki, Kate, Sac de Jour.
- Cultural content should cite artist/director names and years in a restrained archive format.
- Avoid playful copy. The tone is terse, black-clad, and editorial.

## Sources

- Homepage: https://www.ysl.com/en-us
- Extracted with lightpanda MCP on 2026-05-19.
