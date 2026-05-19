---
version: alpha
name: Hermès
description: A maison-commerce interface where bright editorial storytelling and disciplined product grids share the same page. The system is anchored by Hermès orange, warm parchment surfaces, black utility chrome, and a restrained sans-serif editorial voice. Product photography stays isolated on pale square stages; homepage modules alternate cinematic media, short poetic copy, deep category browsing, and exacting four-up merchandise rows.

colors:
  primary: "#f37021"
  primary-deep: "#c75218"
  primary-soft: "#fff2e8"
  ink: "#191919"
  body: "#2b2b2b"
  body-muted: "#666666"
  body-subtle: "#8a8a8a"
  on-primary: "#ffffff"
  on-dark: "#ffffff"
  canvas: "#ffffff"
  canvas-warm: "#f8f4ef"
  surface-parchment: "#f3eee7"
  surface-sand: "#e9dfd2"
  surface-product: "#f7f4ef"
  surface-footer: "#f6f1eb"
  surface-dark: "#111111"
  surface-scrim: "rgba(0,0,0,0.24)"
  hairline: "#ded6cc"
  hairline-soft: "#eee8e1"
  border-strong: "#b8aa9c"
  focus-ring: "#f37021"
  shadow-soft: "0 18px 44px rgba(25,25,25,0.08)"

typography:
  hero-display:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 56px
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: -0.01em
  display-lg:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 42px
    fontWeight: 400
    lineHeight: 1.14
    letterSpacing: -0.005em
  display-md:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 30px
    fontWeight: 400
    lineHeight: 1.22
    letterSpacing: 0
  editorial-title:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 24px
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: 0
  body-lg:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: 0
  body:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-strong:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.45
    letterSpacing: 0
  product-name:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0
  price:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0
  nav-link:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: 0.02em
  utility:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.35
    letterSpacing: 0.08em
    textTransform: uppercase
  button:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: 0.02em
  caption:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  caption-strong:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 13px
    fontWeight: 600
    lineHeight: 1.45
    letterSpacing: 0.08em
    textTransform: uppercase
  legal:
    fontFamily: '"Helvetica Neue", Arial, sans-serif'
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 8px
  lg: 12px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 40px
  xxl: 64px
  section: 88px
  editorial: 120px

components:
  site-header:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 84px
    borderBottom: "1px solid {colors.hairline-soft}"
  logo-lockup:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.utility}"
    rounded: "{rounded.none}"
  menu-button:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.none}"
    padding: 12px 0px
  icon-button:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 44px
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 15px 26px
    height: 46px
  button-primary-active:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.none}"
  button-secondary:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    border: "1px solid {colors.border-strong}"
    padding: 14px 26px
    height: 46px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    borderBottom: "1px solid currentColor"
  text-link-accent:
    backgroundColor: transparent
    textColor: "{colors.primary-deep}"
    typography: "{typography.body}"
  hero-video:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    minHeight: 720px
  hero-copy:
    backgroundColor: "{colors.surface-scrim}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-md}"
    padding: 40px
  editorial-block:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.editorial-title}"
    padding: 88px 0px 56px
  category-tile:
    backgroundColor: "{colors.surface-product}"
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    rounded: "{rounded.none}"
    padding: 16px
  product-grid:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.product-name}"
    columns: 4
    gap: 24px
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
    aspectRatio: "1 / 1"
    padding: 28px
  product-price:
    backgroundColor: transparent
    textColor: "{colors.body-muted}"
    typography: "{typography.price}"
  search-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    border: "1px solid {colors.hairline}"
    padding: 13px 16px
    height: 46px
  newsletter-panel:
    backgroundColor: "{colors.surface-footer}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    padding: 40px
  footer:
    backgroundColor: "{colors.surface-footer}"
    textColor: "{colors.body}"
    typography: "{typography.caption}"
    padding: 64px 0px 40px
  footer-heading:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.caption-strong}"
    rounded: "{rounded.none}"
  footer-link:
    backgroundColor: transparent
    textColor: "{colors.body}"
    typography: "{typography.caption}"
---

## Overview

Hermès online behaves like a luxury house that accepts commerce without becoming a generic storefront. The page opens with cinematic media, then moves into short editorial modules and exact product rows. Current homepage copy includes “Technique, color, and botany,” “Elegance buckled up,” “Tailored itineraries,” and “Time Your Way!” — brief, poetic headlines that frame merchandise as a scene or journey rather than a sale event.

The UI is quieter than the brand color suggests. Hermès orange is present as the institutional accent, but most interface surfaces are white, parchment, sand, and black. Products sit on pale square stages, usually in four-up grids, with the product name and price treated as plain text below the image. There is little visible card chrome; the product crop and whitespace create the structure.

Navigation is deep and maison-like. The menu exposes the full universe: Women, Men, Leather goods, Jewelry, Watches, Fragrances and make-up, Home, Home and Art of living, Equestrian, Gifts, Services, and institutional content. The header itself stays sparse: logo centered, Menu/Search on one side, account/cart utilities on the other.

**Key Characteristics:**
- Hermès orange as an accent and institutional signature, not as a constant page wash.
- White and warm parchment surfaces, with product images staged on pale neutral squares.
- Menu-first navigation that hides a very deep category taxonomy behind restrained chrome.
- Editorial homepage rhythm: cinematic media, short copy, single link, product grid.
- Four-up product rows with exact names and prices, no promotional badges or urgency treatments.
- Rectilinear luxury grammar: flat buttons, square product stages, thin rules, minimal radii.
- Footer treated as a major service area with Services, Orders, La Maison Hermès, Legal, customer service, newsletter, social, and locale controls.

## Colors

> **Source page analyzed:** https://www.hermes.com/us/en/ via lightpanda MCP on 2026-05-19. The observed page included a cookie banner, full header taxonomy, a video-led homepage, editorial sections, product rows, and the full footer.

### Brand & Accent

- **Hermès Orange** (`{colors.primary}` — #f37021): The signature institutional color. Use for primary calls to action, focus, brand accents, and selective emphasis. It should feel like a stamp or box edge, not a background theme for every module.
- **Deep Orange** (`{colors.primary-deep}` — #c75218): Active state and text-accent variant when orange needs sufficient contrast on white.
- **Soft Orange** (`{colors.primary-soft}` — #fff2e8): A light wash for notices or selected states when a full orange fill would be too loud.

### Surface

- **Canvas** (`{colors.canvas}` — #ffffff): Main page background and product grid container.
- **Warm Canvas** (`{colors.canvas-warm}` — #f8f4ef): Transitional page bands and editorial gutters.
- **Parchment** (`{colors.surface-parchment}` — #f3eee7): Luxury neutral used for footer and quiet service panels.
- **Sand** (`{colors.surface-sand}` — #e9dfd2): Slightly denser inset surface for category browsing or hover panels.
- **Product Stage** (`{colors.surface-product}` — #f7f4ef): The pale square behind product photography. This is a key ecommerce surface.
- **Dark Surface** (`{colors.surface-dark}` — #111111): Video fallback, high-contrast media moments, and black utility overlays.

### Text

- **Ink** (`{colors.ink}` — #191919): Primary headings, navigation, product names.
- **Body** (`{colors.body}` — #2b2b2b): Default copy.
- **Body Muted** (`{colors.body-muted}` — #666666): Prices, secondary product details, footer supporting text.
- **Body Subtle** (`{colors.body-subtle}` — #8a8a8a): Legal copy, disabled states, passive metadata.
- **On Dark** (`{colors.on-dark}` — #ffffff): Text over film and dark overlays.

### Borders & Effects

- **Hairline** (`{colors.hairline}` — #ded6cc): Standard divider, search field border, footer rules.
- **Hairline Soft** (`{colors.hairline-soft}` — #eee8e1): Header separator and low-contrast section rules.
- **Border Strong** (`{colors.border-strong}` — #b8aa9c): Secondary button outline or active category frame.
- **Soft Shadow** (`{colors.shadow-soft}`): Rare editorial elevation only. Product cards are normally flat.

## Typography

### Font Family

- **Display / Body / UI:** `Helvetica Neue, Arial, sans-serif`. The online store reads as clean, precise, and international rather than heavily typographic. The brand expression comes from spacing, imagery, color, and tone.
- **Logo:** The Hermès wordmark is an image asset and should not be recreated as live text.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.hero-display}` | 56px | 400 | 1.08 | -0.01em | Large media-led statements |
| `{typography.display-lg}` | 42px | 400 | 1.14 | -0.005em | Major editorial section headline |
| `{typography.display-md}` | 30px | 400 | 1.22 | 0 | Secondary editorial headline |
| `{typography.editorial-title}` | 24px | 400 | 1.25 | 0 | Homepage module titles like “Elegance buckled up” |
| `{typography.body-lg}` | 18px | 400 | 1.65 | 0 | Lead paragraphs |
| `{typography.body}` | 16px | 400 | 1.55 | 0 | Default copy |
| `{typography.product-name}` | 15px | 400 | 1.45 | 0 | Product card names |
| `{typography.price}` | 14px | 400 | 1.4 | 0 | Product prices |
| `{typography.nav-link}` | 13px | 400 | 1.3 | 0.02em | Header and menu links |
| `{typography.utility}` | 12px | 500 | 1.35 | 0.08em | Footer headings, small utility labels |
| `{typography.button}` | 14px | 500 | 1 | 0.02em | Buttons and compact CTAs |
| `{typography.caption}` | 13px | 400 | 1.5 | 0 | Footer links and support copy |

### Principles

- **Plain sans-serif, precise rhythm.** Avoid decorative serif or overly modern grotesk styling. The voice should be neutral enough to let images and product names carry specificity.
- **Regular weight dominates.** Headlines are not heavy; they use scale and placement rather than boldness.
- **Editorial titles stay compact.** Homepage section titles are often closer to 24–30px than oversized campaign typography.
- **Product copy is exact.** Product cards use clear names, color/variant in accessible labels, and prices without marketing embellishment.

## Layout

### Spacing System

- **Base unit:** 8px, with 12/16/24/40/64 as the main structural intervals.
- **Editorial sections:** 88px to 120px of vertical space, depending on whether the section includes media.
- **Product grid gap:** 24px on desktop; the image stage does most of the visual separation.
- **Footer padding:** 64px top, with dense link columns below.

### Grid & Container

- **Product rows:** Four-up desktop grid. Homepage recommendation rows surfaced as groups of four products.
- **Category tiles:** Horizontal or multi-column browsing tiles above product rows, with simple labels like Women’s ready to wear, Women’s Shoes, Silk, Fashion Jewelry, Hats, Ties, Men’s shoes, Beach.
- **Content width:** Broad ecommerce container, usually near full width with comfortable gutters rather than narrow editorial columns.

### Whitespace Philosophy

Hermès uses whitespace as a boutique counter. Products are not enclosed in heavy cards; they sit apart because each product image has its own pale square, and the grid gives each object enough room to be inspected. The homepage can be commercially dense, but it avoids noisy ecommerce markers.

## Components

### Header & Navigation

**`site-header`** is a white, sparse masthead with centered Hermès logo, left-side Menu/Search controls, and right-side Account/Cart utilities. It should feel stable and institutional rather than promotional.

**`menu-button`** is text-forward. Use the visible word “Menu” with a simple icon if needed. The menu opens into a deep taxonomy rather than exposing all categories in the masthead.

**`icon-button`** is a 44px circular hit target with transparent fill. It should not use bright background fills unless placed over media.

### Hero & Editorial Modules

**`hero-video`** is the opening maison moment: full-width media, dark fallback, optional restrained overlay copy, and minimal controls. Video controls are platform-level and should not become decorative UI.

**`hero-copy`** uses a subtle dark scrim when text sits over media. Keep the copy short and poetic; the image should do most of the work.

**`editorial-block`** structures homepage moments such as “Technique, color, and botany” or “Tailored itineraries.” It contains a compact headline, short paragraph, and one link.

### Product Browsing

**`category-tile`** is a simple image or pale tile with a category label. The tile should invite browsing without feeling like a promo card.

**`product-grid`** is four columns on desktop. It contains repeated `product-card` items and should not add shadows or rounded frames.

**`product-card`** is flat. The image stage is square, the product name sits below, and price follows as muted text. No sale badges, no rating stars, no urgency counters.

**`product-image-stage`** is the most important product component: a pale square background, centered product photography, and generous internal padding.

### Buttons & Links

**`button-primary`** uses Hermès orange with a square, rectilinear shape. It is a deliberate action, not a pill. Use sparingly.

**`button-secondary`** is a transparent rectangle with a thin warm-gray border. It fits service modules, cookie preferences, and low-emphasis actions.

**`text-link`** is the dominant homepage CTA form. Underlined black text is often more brand-appropriate than a filled button for editorial modules.

### Search & Footer

**`search-input`** is square-edged, bordered, and quiet. Search is a utility surface, not a rounded SaaS pill.

**`footer`** is a major service and institutional zone. It includes Services, Orders, La Maison Hermès, Legal, customer service hours, newsletter subscription, social links, locale selector, and copyright. Treat it as a structured utility area, not a small legal afterthought.

## Do's and Don'ts

### Do

- Use `{colors.primary}` as a precise brand accent, especially for primary actions and focus.
- Stage product photography on `{colors.surface-product}` square backgrounds.
- Keep product grids flat, rectilinear, and quiet.
- Use underlined text links for editorial CTAs when a filled button would feel too commercial.
- Preserve deep category browsing and full footer taxonomy.
- Write copy with a poetic retail tone: objects, journeys, craft, color, and seasonality.

### Don't

- Don't turn Hermès orange into a dominant background theme.
- Don't use rounded pills for primary luxury actions.
- Don't add badges, star ratings, flash-sale labels, or urgency UI.
- Don't put heavy shadows on product cards.
- Don't substitute generic lifestyle stock imagery for precise product or maison imagery.
- Don't recreate the Hermès logo as typed text; use the official mark asset where a logo is required.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Small phone | ≤ 419px | Single-column product grid; hero copy stacks; footer becomes accordion-like |
| Phone | 420–767px | Two-column category tiles may collapse; product rows become 2 or 1 column depending on density |
| Tablet | 768–1023px | Product grid becomes 2–3 columns; menu-first navigation remains central |
| Desktop | 1024–1439px | Four-up product rows; full footer columns; broad media modules |
| Large desktop | ≥ 1440px | Content gutters expand; product grid remains disciplined rather than adding too many columns |

### Behavior Notes

- Keep the header simple on all breakpoints: logo, menu/search, account/cart.
- Product image stages should retain square aspect ratio across breakpoints.
- Editorial media crops should prioritize the product or crafted scene over abstract atmosphere.
- Footer taxonomy should remain accessible on mobile through stacked groups or accordions.

## Content Strategy

- Lead with seasonal maison storytelling, then expose product browsing.
- Keep homepage headlines short and evocative.
- Product rows should include exact product names and prices without promotional framing.
- Service content matters: contact, stores, care and repair, gifting, shipping, returns, and newsletter are part of the luxury service promise.

## Sources

- Homepage: https://www.hermes.com/us/en/
- Extracted with lightpanda MCP on 2026-05-19.
