---
version: alpha
name: Victoria's Secret
description: A black-and-white fashion retail system where the brand stays restrained and photography carries the seduction, scale, and seasonal energy. The interface is built from a sharp uppercase category nav, high-contrast editorial imagery, transparent or black rectangular CTAs, dense mega-menu taxonomy, and a soft pink loyalty/promo undertone. Chrome is deliberately quiet: white canvas, black ink, thin gray hairlines, square image crops, and minimal radius.

colors:
  primary: "#000000"
  primary-soft: "#1f1f1f"
  brand-pink: "#f7c8d3"
  brand-pink-soft: "#fbe7ec"
  promo-rose: "#a13f55"
  sale: "#c00000"
  ink: "#000000"
  body: "#1f1f1f"
  body-muted: "#666666"
  body-subtle: "#8a8a8a"
  canvas: "#ffffff"
  surface-soft: "#f7f7f7"
  surface-blush: "#fbe7ec"
  surface-dark: "#000000"
  hairline: "#d9d9d9"
  hairline-soft: "#eeeeee"
  overlay-scrim: "rgba(0,0,0,0.24)"
  on-primary: "#ffffff"
  on-dark: "#ffffff"

typography:
  logo-display:
    fontFamily: "Victoria Serif, Didot, Bodoni 72, Georgia, serif"
    fontSize: 42px
    fontWeight: 400
    lineHeight: 1.0
    letterSpacing: 0.04em
    textTransform: uppercase
  campaign-display:
    fontFamily: "Victoria Serif, Didot, Bodoni 72, Georgia, serif"
    fontSize: 56px
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: 0.02em
    textTransform: uppercase
  display-lg:
    fontFamily: "Victoria Serif, Didot, Bodoni 72, Georgia, serif"
    fontSize: 40px
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: 0.02em
  display-md:
    fontFamily: "Victoria Serif, Didot, Bodoni 72, Georgia, serif"
    fontSize: 30px
    fontWeight: 400
    lineHeight: 1.17
    letterSpacing: 0.01em
  title-lg:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: 24px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: 0
  title-md:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: 18px
    fontWeight: 500
    lineHeight: 1.33
    letterSpacing: 0
  body:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-strong:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0
  caption:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: 0
  caption-strong:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.43
    letterSpacing: 0
  micro:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.33
    letterSpacing: 0
  nav-link:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: 0.05em
    textTransform: uppercase
  utility-link:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.33
    letterSpacing: 0
  mega-heading:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 700
    lineHeight: 1.35
    letterSpacing: 0.04em
    textTransform: uppercase
  mega-link:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: 0
  button:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1
    letterSpacing: 0.06em
    textTransform: uppercase

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 8px
  pill: 9999px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 64px
  editorial: 80px

components:
  utility-bar:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.utility-link}"
    height: 36px
  brand-header:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.logo-display}"
    height: 72px
  category-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 44px
    borderBottom: "1px solid {colors.hairline-soft}"
  mega-menu:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.mega-link}"
    borderTop: "1px solid {colors.hairline-soft}"
    shadow: "0 8px 24px rgba(0,0,0,0.08)"
  search-input:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.body}"
    typography: "{typography.caption}"
    rounded: "{rounded.none}"
    height: 40px
    padding: 10px 14px
  hero-editorial:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.campaign-display}"
    rounded: "{rounded.none}"
    minHeight: 620px
  hero-copy-panel:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.display-lg}"
    padding: 48px
  promo-band:
    backgroundColor: "{colors.surface-blush}"
    textColor: "{colors.ink}"
    typography: "{typography.caption-strong}"
    height: 44px
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 14px 28px
    height: 44px
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    border: "1px solid {colors.ink}"
    padding: 13px 28px
    height: 44px
  button-on-image:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 14px 28px
    height: 44px
  editorial-tile:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.none}"
    padding: 0px
  image-promo-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.none}"
    padding: 0px
  product-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.caption}"
    rounded: "{rounded.none}"
    padding: 0px
  sale-badge:
    backgroundColor: transparent
    textColor: "{colors.sale}"
    typography: "{typography.caption-strong}"
  signup-panel:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    padding: 40px
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.mega-link}"
    borderTop: "1px solid {colors.hairline}"
    padding: 48px
---

## Overview

Victoria's Secret's US web presence is a **fashion commerce page disguised as an editorial storefront**. The visible structure is direct: a slim utility layer for country/language and sister-brand links, a centered Victoria's Secret logo, a dense uppercase category nav, a large promotional main content area, email/SMS sign-up, social icons, and a multi-column footer. The main navigation opens into extremely broad mega menus covering new arrivals, bras, panties, sleep, beauty, swim, activewear, lingerie, clothing, accessories, and sale.

The brand system is intentionally monochrome. Black type on white chrome creates a luxury retail baseline; seasonal photography supplies color, texture, skin tone, lace, satin, swimwear, and beauty-packaging cues. Pink exists as an undertone rather than the main UI accent: useful for promotion bands, loyalty surfaces, or soft editorial moments, but never louder than the product imagery. CTAs are square black or white rectangles, not friendly pills.

**Key Characteristics:**
- Black-and-white retail chrome with pink used sparingly as a blush promotional accent.
- Centered logo mark, slim utility controls, and uppercase horizontal category navigation.
- Deep mega-menu taxonomy with uppercase group headings and compact link lists.
- Editorial photography is the primary brand expression; UI surfaces stay flat and restrained.
- Square corners dominate: hero images, promo tiles, cards, and buttons.
- CTA grammar is rectangular and high contrast: black fill or white fill with black text.
- Footer is dense and service-oriented, with social links, help, orders/returns, services, and legal rows.

## Colors

> **Source page analyzed:** `https://www.victoriassecret.com/us/` homepage visible structure. Direct stylesheet retrieval was blocked by Cloudflare in the local shell, so this document records observed structure plus conservative brand-system tokens.

### Brand & Accent
- **Black** (`{colors.primary}` — #000000): The primary UI and brand chrome color. Used for logo artwork, category navigation text, primary buttons, iconography, and high-contrast editorial copy.
- **Soft Black** (`{colors.primary-soft}` — #1f1f1f): A reading-friendly near-black for body text and copy blocks.
- **Victoria Blush** (`{colors.brand-pink}` — #f7c8d3): The soft pink undertone associated with the brand. Use for loyalty, promo, gift, or romance-coded surfaces.
- **Blush Surface** (`{colors.brand-pink-soft}` — #fbe7ec): Very pale pink for low-pressure sign-up and promotion backgrounds.
- **Promo Rose** (`{colors.promo-rose}` — #a13f55): A deeper rose for text emphasis when a promotion needs more warmth than black.
- **Sale Red** (`{colors.sale}` — #c00000): Reserved for markdowns, sale badges, and clearance language.

### Surface
- **Canvas** (`{colors.canvas}` — #ffffff): Default page and header surface.
- **Soft Surface** (`{colors.surface-soft}` — #f7f7f7): Search fields, sign-up panels, and quiet utility backgrounds.
- **Blush Surface** (`{colors.surface-blush}` — #fbe7ec): Promotional bands and brand-affinity modules.
- **Dark Surface** (`{colors.surface-dark}` — #000000): Hero fallback, black editorial panels, and primary button fill.
- **Image Scrim** (`{colors.overlay-scrim}` — rgba(0,0,0,0.24)): Optional overlay when white text must sit over campaign photography.

### Text
- **Ink** (`{colors.ink}` — #000000): Logo, navigation, primary actions, and high-emphasis headlines.
- **Body** (`{colors.body}` — #1f1f1f): General text where pure black would feel too hard.
- **Muted Body** (`{colors.body-muted}` — #666666): Secondary metadata, footer support text, placeholder copy.
- **Subtle Body** (`{colors.body-subtle}` — #8a8a8a): Legal copy, disabled UI, low-emphasis utility links.
- **On Primary / On Dark** (`{colors.on-primary}` / `{colors.on-dark}` — #ffffff): Text on black buttons and dark photography.

### Hairlines & Borders
- **Hairline** (`{colors.hairline}` — #d9d9d9): Footer separators, input boundaries, utility dividers.
- **Soft Hairline** (`{colors.hairline-soft}` — #eeeeee): Header/nav separators and subtle card grid boundaries.

### Brand Gradient
No decorative gradient should be part of the system. Visual depth comes from fashion photography, fabric texture, and editorial cropping. If an overlay is required for text contrast, use a flat scrim token rather than a colorful gradient.

## Typography

### Font Family
- **Logo / editorial display:** A high-contrast fashion serif approximated by `Didot, Bodoni 72, Georgia, serif`. The real logo is an SVG asset and should not be recreated in live text except for fallback lockups.
- **UI / commerce text:** `Helvetica Neue, Arial, sans-serif`. The navigation, mega menus, CTAs, forms, product cards, and footer all read as crisp modern retail sans.
- **Case:** Category navigation and CTA labels are uppercase. Mega-menu headings are uppercase; link items use title case or natural product naming.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.logo-display}` | 42px | 400 | 1.0 | 0.04em | Text fallback for logo lockup |
| `{typography.campaign-display}` | 56px | 400 | 1.05 | 0.02em | Hero/editorial campaign headline |
| `{typography.display-lg}` | 40px | 400 | 1.10 | 0.02em | Large promo tile headlines |
| `{typography.display-md}` | 30px | 400 | 1.17 | 0.01em | Secondary editorial headlines |
| `{typography.title-lg}` | 24px | 500 | 1.25 | 0 | Tile section title |
| `{typography.title-md}` | 18px | 500 | 1.33 | 0 | Promo-card title |
| `{typography.body}` | 16px | 400 | 1.5 | 0 | Body copy, form copy |
| `{typography.body-strong}` | 16px | 600 | 1.5 | 0 | Strong inline retail copy |
| `{typography.caption}` | 14px | 400 | 1.43 | 0 | Product metadata and footer links |
| `{typography.caption-strong}` | 14px | 600 | 1.43 | 0 | Promo copy and small headings |
| `{typography.micro}` | 12px | 400 | 1.33 | 0 | Legal and utility text |
| `{typography.nav-link}` | 13px | 600 | 1.2 | 0.05em | Top category navigation |
| `{typography.mega-heading}` | 13px | 700 | 1.35 | 0.04em | Mega-menu group headings |
| `{typography.mega-link}` | 13px | 400 | 1.7 | 0 | Mega-menu link lists |
| `{typography.button}` | 14px | 600 | 1.0 | 0.06em | Rectangular CTA labels |

### Principles

- **Serif is editorial, sans is transactional.** Use the fashion serif for campaign moments only; product browsing and utility UI stay sans-serif.
- **Uppercase navigation is a brand signal.** The nav labels (`BRAS`, `PANTIES`, `SLEEP`, `BEAUTY`) should be tightly spaced, calm, and compact.
- **Avoid heavy display weights.** Luxury tone comes from contrast and spacing, not extra-bold type.
- **Let photography carry color.** Text should be black or white in most cases; rose/pink text is a controlled promotional exception.
- **Mega menus prioritize scannability.** Keep link text small, vertically relaxed, and grouped under strong uppercase headings.

## Layout

### Spacing System
- **Base unit:** 4px/8px with commerce-friendly steps: 12, 16, 24, 32, 48, 64.
- **Header stack:** utility row → centered logo/search row → category nav. Each row is shallow; the combined header feels broad but not tall.
- **Editorial sections:** `{spacing.section}` (64px) vertical padding for standard modules; `{spacing.editorial}` (80px) for hero/major campaign blocks.
- **Mega-menu columns:** dense multi-column grids with 24–32px column gutters.
- **Footer:** 48px top/bottom padding, tight link columns, legal row below.

### Grid & Container
- **Header content:** full width with constrained internal padding; logo centered, search and account/cart utilities aligned around it.
- **Hero:** full-bleed or wide editorial image region, usually one dominant visual per viewport.
- **Promo modules:** 2-up, 3-up, or 6-tile image grids, square/portrait crop dominant.
- **Mega menu:** full-width dropdown with category columns and promotional feature links.
- **Footer:** 3–4 column service grid, then legal links in a dense row.

### Whitespace Philosophy
Whitespace is used to make photography feel premium. The chrome around it is compact and retail-efficient. Avoid over-padding navigation and product grids; reserve air for the hero and editorial tile captions.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow | Header, cards, product grids, footer |
| Hairline | 1px gray border | Nav separators, form fields, footer divisions |
| Dropdown shadow | `0 8px 24px rgba(0,0,0,0.08)` | Mega-menu layer only |
| Scrim | `rgba(0,0,0,0.24)` | White text over image |

**Shadow philosophy.** Keep shadows rare. Product cards and editorial tiles should be flat; the only meaningful elevation belongs to dropdown navigation, where a shadow clarifies that the mega menu is layered over the page.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.none}` | 0px | Hero, tiles, product cards, nav, buttons |
| `{rounded.xs}` | 2px | Optional focus outlines and tiny utility affordances |
| `{rounded.sm}` | 4px | Rare form/control affordances |
| `{rounded.md}` | 8px | Avoid on homepage chrome unless inherited from third-party widgets |
| `{rounded.pill}` | 9999px | Only for social/avatar chips or isolated app-store badges |
| `{rounded.full}` | 9999px | Circular icon controls when unavoidable |

### Photography Geometry
- **Hero imagery:** full-width fashion campaign crop, portrait or cinematic landscape depending on campaign.
- **Promo tiles:** square-corner image cards with headline/CTA stacked beneath or overlaid.
- **Product cards:** rectangular image area, square corners, product name/price/offer below.
- **Logo:** always SVG/artwork; do not approximate the real mark with live text in production.

## Components

### Header & Navigation

**`utility-bar`** — Slim top layer for skip link behavior, Victoria's Secret/PINK switching, country flag, language, and currency. White background, black text, low visual weight.

**`brand-header`** — Centered brand logo row. The visible page uses an SVG Victoria's Secret logo; keep it black on white. Search appears as a utility action, not a large hero search experience.

**`category-nav`** — Horizontal uppercase commerce nav. Labels include `New!`, `BRAS`, `PANTIES`, `SLEEP`, `BEAUTY`, `SWIM`, `Activewear`, `LINGERIE`, `CLOTHING`, `ACCESSORIES`, and `SALE`. Use `{typography.nav-link}` and subtle bottom hairline. The nav should feel editorial and exact, not playful.

**`mega-menu`** — Dense full-width taxonomy dropdown. White surface, compact sans-serif columns, uppercase section headings (`STYLES`, `FEATURED`, `COLLECTIONS`, `DEALS TO LOVE`), and many links. The mega menu may use the only dropdown shadow in the system.

### Buttons & Actions

**`button-primary`** — Black rectangular CTA. Background `{colors.primary}`, white uppercase label, square corners, 44px height, 14px/600 label. Use for "Shop Now", sign-up actions, and purchase-driving CTAs.

**`button-secondary`** — White rectangular CTA with 1px black border and black uppercase label. Use when paired with a primary action or when sitting on a light editorial tile.

**`button-on-image`** — White rectangular CTA over photography. No rounded corners; maintain strong contrast. If image contrast is low, add `{colors.overlay-scrim}` to the image region rather than darkening the button.

### Content Modules

**`hero-editorial`** — The main campaign block. High-impact photography, minimal copy, one or two rectangular CTAs. Text may sit below the image on mobile and overlay on desktop when contrast allows.

**`promo-band`** — Slim promotional announcement strip. Use blush or white surface with compact bold copy. It should feel like a retail offer, not a decorative banner.

**`editorial-tile`** — Large image-led tile for collections such as bridal, strapless, scent events, or seasonal shops. Square crop, serif or medium sans headline, rectangular CTA.

**`image-promo-card`** — Repeated homepage card for category campaigns. Image first, title and CTA below. No shadow, no radius.

**`product-card`** — Commerce grid item. Square/portrait product image, product name, price, promo/sale badge, and swatch/meta details. Keep all text black or muted except `{component.sale-badge}`.

### Forms & Footer

**`search-input`** — Compact utility search field. Soft gray or white background, square corners, 40px height. It should not become a pill.

**`signup-panel`** — Email/SMS acquisition module. Soft gray or blush surface, centered title/copy, primary black CTA. The visible homepage exposes "SIGN UP FOR EMAILS & TEXTS" as a footer-adjacent conversion action.

**`footer`** — Dense support footer with social icons, `HELP`, `ORDERS & RETURNS`, `SERVICES`, copyright, and legal links. White background, hairline top border, compact 13–14px links.

## Do's and Don'ts

### Do
- Use black-and-white as the default interface language.
- Use pink/blush as a soft promotional support color, not as the main action color.
- Keep CTAs rectangular and high contrast.
- Use uppercase category navigation with modest letter-spacing.
- Let editorial fashion photography carry color, texture, and emotion.
- Keep mega-menu content dense, grouped, and scannable.
- Use the real SVG logo asset for the brand mark.

### Don't
- Don't add rounded pill CTAs to the core VS homepage system.
- Don't add decorative gradients, bokeh, or abstract color backgrounds.
- Don't make product cards float with shadows.
- Don't use pink for every interactive element; black remains the primary action color.
- Don't set the whole site in a high-contrast serif. The serif is for campaign/display moments; commerce UI is sans.
- Don't over-enlarge category navigation. It should be precise, compact, and retail-efficient.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Small phone | ≤ 374px | Logo compresses; nav becomes menu/search utility; CTAs stack full-width |
| Phone | 375–767px | Hero copy moves below image; promo cards become one-column; footer accordions likely replace columns |
| Tablet | 768–1023px | Category nav may horizontally scroll; promo grids move to 2 columns |
| Desktop | 1024–1439px | Full header stack, horizontal category nav, mega-menu columns |
| Wide desktop | ≥ 1440px | Hero/media widths lock to campaign art direction; margins absorb extra width |

### Touch Targets
- Header icons and utility controls should land at 40–44px minimum.
- Mobile CTAs should be full-width or at least 44px tall.
- Mega-menu desktop links can remain compact; mobile menu rows should increase vertical padding.

### Collapsing Strategy
- **Header:** utility bar and logo remain visible; category nav collapses into a menu/hamburger pattern on phone.
- **Mega menu:** desktop full-width dropdown → mobile drill-down category list.
- **Hero:** overlay desktop copy → stacked mobile copy when legibility requires it.
- **Promo grid:** multi-column editorial grid → single-column image stack on phone.
- **Footer:** multi-column link grid → accordion groups on mobile.

### Image Behavior
- Use art-directed crops: desktop hero can be wide and cinematic; mobile should favor portrait/square crops that keep model/product focus.
- Keep square corners across all crops.
- Lazy-load below-fold promo/product images; load first hero eagerly.
- Do not darken all images by default. Use scrim only when text overlays need it.

## Iteration Guide

1. Start with the header stack: `{component.utility-bar}`, `{component.brand-header}`, `{component.category-nav}`.
2. Treat the mega menu as a taxonomy component, not a marketing panel. Group links under uppercase headings.
3. Build campaign modules from image-first blocks and rectangular CTAs.
4. Use `{colors.primary}` for action buttons and `{colors.sale}` only for sale language.
5. Avoid rounding unless a third-party widget or isolated social/icon element requires it.
6. If a page feels flat, improve photography/cropping before adding chrome.
7. Keep footer/service modules dense and clear; this is utility commerce, not editorial storytelling.

## Known Gaps

- Local `curl` access to `victoriassecret.com` was blocked by Cloudflare, so exact production CSS variables and font file names could not be verified from the shell.
- The visible browser-extracted homepage showed navigation, mega-menu taxonomy, signup, social links, and footer content, but the dynamic hero image content was represented as `Loading`.
- Exact breakpoint values and internal component class names may differ from these tokens; the responsive model is inferred from the visible retail structure.
- The Victoria's Secret logo is an SVG asset; typography tokens approximate the editorial voice but should not replace the logo.
