---
version: alpha
name: Starbucks
description: |
  Starbucks' current web system is a warm retail and ordering surface built
  from SoDoSans, a four-tier green palette, full-pill buttons, product
  photography, warm cream/white content bands, and a dense corporate footer.
  The live homepage verified through Lightpanda leads with "It's a great day
  for coffee", then promotes Starbucks summer beverages, Unicorn Cake Pop,
  Khloud Protein Popcorn, Military Appreciation eGift cards, ordering, account
  access, store finding, and feedback. The system feels like clean cafe
  signage: friendly, direct, seasonal, and conversion-oriented without losing
  warmth.

colors:
  starbucks-green: "#006241"
  green-accent: "#00754a"
  house-green: "#1e3932"
  green-uplift: "#2b5148"
  green-light: "#d4e9e2"
  consent-green: "#008248"
  gold: "#cba258"
  gold-light: "#dfc49d"
  gold-lightest: "#faf6ee"
  white: "#ffffff"
  neutral-cool: "#f9f9f9"
  neutral-warm: "#f2f0eb"
  ceramic: "#edebe9"
  text-black: "rgba(0,0,0,0.87)"
  text-black-soft: "rgba(0,0,0,0.58)"
  text-white: "#ffffff"
  text-white-soft: "rgba(255,255,255,0.70)"
  rewards-green: "#33433d"
  black: "#000000"
  input-border: "#d6dbde"
  table-rule: "#e7e7e7"
  error: "#c82014"
  warning: "#fbbc05"
  valid-tint: "rgba(212,233,226,0.33)"
  invalid-tint: "rgba(200,32,20,0.05)"
  shadow-card-1: "rgba(0,0,0,0.14)"
  shadow-card-2: "rgba(0,0,0,0.24)"
  shadow-nav-1: "rgba(0,0,0,0.10)"
  shadow-nav-2: "rgba(0,0,0,0.06)"
  shadow-nav-3: "rgba(0,0,0,0.07)"

typography:
  display:
    fontFamily: SoDoSans
    fallback: Helvetica Neue, Helvetica, Arial, sans-serif
    fontSize: 80px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: -0.16px
  jumbo:
    fontFamily: SoDoSans
    fontSize: 58px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: -0.16px
  hero:
    fontFamily: SoDoSans
    fontSize: 45px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: -0.16px
  heading:
    fontFamily: SoDoSans
    fontSize: 24px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: -0.16px
  heading-regular:
    fontFamily: SoDoSans
    fontSize: 24px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: -0.16px
  body-lg:
    fontFamily: SoDoSans
    fontSize: 19px
    fontWeight: 400
    lineHeight: 1.75
    letterSpacing: -0.16px
  body:
    fontFamily: SoDoSans
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: -0.01em
  label:
    fontFamily: SoDoSans
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: -0.01em
  caption:
    fontFamily: SoDoSans
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: -0.01em
  rewards-serif:
    fontFamily: Lander Tall
    fallback: Iowan Old Style, Georgia, serif
    fontSize: 48px
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: 0
  careers-script:
    fontFamily: Kalam
    fallback: Comic Sans MS, cursive
    fontSize: 32px
    fontWeight: 400
    lineHeight: 1.2

spacing:
  xxs: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 40px
  xxl: 48px
  xxxl: 56px
  section: 64px
  outer-gutter: 16px
  outer-gutter-medium: 24px
  outer-gutter-large: 40px
  nav-xs: 64px
  nav-mobile: 72px
  nav-tablet: 83px
  nav-desktop: 99px
  frap: 56px
  frap-mini: 40px
  max-width: 1440px

rounded:
  card: 12px
  feedback-tab: "12px 12px 0 0"
  button: 50px
  circle: 50%
  input: 4px
  visa-card: "3.3333% / 5.298%"

elevation:
  card: "0 0 0.5px rgba(0,0,0,0.14), 0 1px 1px rgba(0,0,0,0.24)"
  nav: "0 1px 3px rgba(0,0,0,0.10), 0 2px 2px rgba(0,0,0,0.06), 0 0 2px rgba(0,0,0,0.07)"
  frap: "0 0 6px rgba(0,0,0,0.24), 0 8px 12px rgba(0,0,0,0.14)"
  frap-active: "0 0 6px rgba(0,0,0,0.24), 0 8px 12px rgba(0,0,0,0)"
  svc: "drop-shadow(0 4px 1px rgba(0,0,0,0.11)) drop-shadow(0 0 2px rgba(0,0,0,0.24))"

components:
  global-nav:
    backgroundColor: "{colors.white}"
    textColor: "{colors.text-black}"
    shadow: "{elevation.nav}"
    heightDesktop: 99px
    heightTablet: 83px
    heightMobile: 72px
    primaryLinks: Menu, Rewards, Gift Cards
    utilityLinks: Find a store, Sign in, Join now
  primary-button:
    backgroundColor: "{colors.green-accent}"
    textColor: "{colors.white}"
    border: "1px solid {colors.green-accent}"
    rounded: "{rounded.button}"
    padding: "7px 16px"
    activeTransform: "scale(0.95)"
  outlined-button:
    backgroundColor: transparent
    textColor: "{colors.green-accent}"
    border: "1px solid {colors.green-accent}"
    rounded: "{rounded.button}"
    padding: "7px 16px"
  black-button:
    backgroundColor: "{colors.black}"
    textColor: "{colors.white}"
    border: "1px solid {colors.black}"
    rounded: "{rounded.button}"
    padding: "7px 16px"
  dark-outline-button:
    backgroundColor: transparent
    textColor: "{colors.text-black}"
    border: "1px solid {colors.text-black}"
    rounded: "{rounded.button}"
    padding: "7px 16px"
  hero-strip:
    backgroundColor: "{colors.neutral-warm}"
    textColor: "{colors.text-black}"
    imageRatio: split or stacked
    cta: Start an order
    rounded: "{rounded.none}"
  seasonal-product-band:
    backgroundColor: "{colors.white}"
    textColor: "{colors.text-black}"
    image: product photography
    cta: Start an order or Explore menu
    layout: alternating image/text blocks
  feature-band-dark:
    backgroundColor: "{colors.house-green}"
    textColor: "{colors.text-white}"
    secondaryTextColor: "{colors.text-white-soft}"
    primaryCta: white filled with green text
    secondaryCta: white outline
  content-card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.text-black}"
    rounded: "{rounded.card}"
    shadow: "{elevation.card}"
  gift-card-tile:
    backgroundColor: illustrated photography
    rounded: "{rounded.card}"
    shadow: "{elevation.card}"
    cta: Send an eGift
  frap-button:
    backgroundColor: "{colors.green-accent}"
    textColor: "{colors.white}"
    size: 56px
    rounded: "{rounded.circle}"
    shadow: "{elevation.frap}"
    activeTransform: "scale(0.95)"
  feedback-tab:
    backgroundColor: "{colors.green-accent}"
    textColor: "{colors.white}"
    rounded: "{rounded.feedback-tab}"
    position: fixed bottom-right
  footer:
    backgroundColor: "{colors.white}"
    textColor: "{colors.text-black}"
    columns: About Us, Careers, Social Impact, For Business Partners, Order and Pick Up
    socialLinks: spotify, facebook, pinterest, instagram, youtube, x
---

## Overview

Starbucks' current homepage is a seasonal retail feed rather than a single hero page. Lightpanda captured the live page opening with **"It's a great day for coffee"** and a **Start an order** CTA, followed by a summer campaign: **"It's Starbucks summer"** with Tropical Butterfly Refreshers, Horchata, and other seasonal drinks. Below that are compact product/story bands for **Unicorn Cake Pop**, **Khloud Protein Popcorn**, and **Military Appreciation eGift cards**.

The site remains anchored by Starbucks' familiar global nav: Menu, Rewards, Gift Cards, Find a store, Sign in, Join now. The current footer is extensive and corporate: About Us, Careers, Social Impact, For Business Partners, Order and Pick Up, social links, privacy/legal/accessibility links, and copyright. A fixed **Provide feedback** tab appears as a persistent utility affordance.

The older document's system analysis still holds: warm cream/white surfaces, four-tier green palette, SoDoSans, full-pill buttons, soft shadows, and product photography. The update is that the current homepage is more modular and seasonal: alternating promotional bands with real product imagery and simple order/menu CTAs.

**Key Characteristics:**
- Navigation: Menu, Rewards, Gift Cards, Find a store, Sign in, Join now.
- Current homepage campaign: Starbucks summer, Tropical Butterfly Refreshers, Horchata, Unicorn Cake Pop, Khloud Protein Popcorn, Military Appreciation eGift.
- Four green roles: Starbucks Green for brand, Green Accent for CTAs, House Green for deep feature bands, Green Light for soft utility states.
- SoDoSans everywhere, with tight `-0.01em` / `-0.16px` tracking.
- Universal 50px pill buttons and `scale(0.95)` active press.
- Warm cream/ceramic surfaces instead of cold white-only composition.
- Product photography is direct and appetizing, not abstract brand illustration.
- Dense, accordion-like footer taxonomy supports the corporate ecosystem.

## Colors

### Brand Greens
- **Starbucks Green** (`#006241`): Brand anchor, headings, logo-driven moments, and Rewards headers.
- **Green Accent** (`#00754a`): Primary CTAs, order actions, feedback tab, floating order button.
- **House Green** (`#1e3932`): Dark feature bands, footer-style deep surfaces, and Rewards ceremony panels.
- **Green Uplift** (`#2b5148`): Secondary green depth or decorative support.
- **Green Light** (`#d4e9e2`): Soft validation and utility tint.

### Warm Surfaces
- **White** (`#ffffff`): Main content bands, nav, cards.
- **Neutral Warm** (`#f2f0eb`): Warm page canvas and breathable retail zones.
- **Ceramic** (`#edebe9`): Cream separator and soft band surface.
- **Neutral Cool** (`#f9f9f9`): Dropdowns and quiet utility panels.

### Accent & Text
- **Gold** (`#cba258`): Rewards ceremony and star-cost moments only.
- **Text Black** (`rgba(0,0,0,0.87)`): Primary text on light surfaces.
- **Text Black Soft** (`rgba(0,0,0,0.58)`): Metadata and secondary copy.
- **Text White / White Soft**: Dark green feature-band copy.
- **Error Red** (`#c82014`) and warning yellow (`#fbbc05`): Form/system states.

## Typography

### Font Family
- **Primary**: `SoDoSans, "Helvetica Neue", Helvetica, Arial, sans-serif`.
- **Rewards Serif**: `Lander Tall`, with Iowan Old Style / Georgia fallback.
- **Careers Script**: `Kalam`, used only for specific Careers/cup-name moments.

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|---|---|---:|---:|---:|---:|---|
| Display | SoDoSans | 80px | 400-600 | 1.2 | -0.16px | Rewards/large hero moments |
| Jumbo | SoDoSans | 58px | 400-600 | 1.2 | -0.16px | Secondary display |
| Hero | SoDoSans | 45px | 600 | 1.2 | -0.16px | Seasonal campaign headline |
| Heading | SoDoSans | 24px | 600 | 1.5 | -0.16px | Product/promo headings |
| Heading Regular | SoDoSans | 24px | 400 | 1.5 | -0.16px | Softer sections |
| Body Large | SoDoSans | 19px | 400 | 1.75 | -0.16px | Homepage promo copy |
| Body | SoDoSans | 16px | 400 | 1.5 | -0.01em | Standard copy |
| Button / Label | SoDoSans | 14-16px | 600 | 1.2 | -0.01em | Pill CTA labels |
| Caption | SoDoSans | 13px | 400 | 1.5 | -0.01em | Legal/footnotes |

### Principles
- Tight tracking is part of the voice.
- Use SoDoSans for shopping and homepage flows.
- Keep Rewards serif localized to Rewards surfaces.
- Do not use pure black body copy; use the warm opacity-based text tokens.

## Layout

### Spacing System
The system is rem-based with a 16px default rhythm: 4, 8, 16, 24, 32, 40, 48, 56, and 64px. Global gutters move from 16px to 24px to 40px as screens widen.

### Grid & Container
- Homepage modules alternate image/text bands.
- Nav height scales from 64/72px on small screens to 99px on desktop.
- Product imagery can sit beside text on desktop and stack on mobile.
- Footer columns expose Starbucks' broader business taxonomy and should collapse cleanly.

### Whitespace Philosophy
Whitespace should feel like a clean cafe table: generous but functional. Use cream space between promotional blocks instead of dividers.

## Elevation & Depth

Starbucks uses low-alpha layered shadows rather than heavy elevation.

### Rules
- Use the triple-layer nav shadow for the global top bar.
- Use whisper-soft card shadows for cards and gift-card tiles.
- Use the Frap/floating action shadow only for persistent order affordances.
- Avoid heavy SaaS shadows or glass effects.

### Surface Stack
1. Warm/white page bands.
2. White cards and product bands.
3. House Green deep feature bands.
4. Floating feedback/order affordances.

## Shapes

### Border Radius Scale
- **12px**: Cards, modal panels, gift-card tiles.
- **50px**: All buttons and pill CTAs.
- **50%**: Floating circular order/Frap button and icon buttons.
- **4px**: Inputs and select-style product customization rows.
- **12px 12px 0 0**: Fixed feedback tab.

### Geometry
The system is soft but not bubbly. Buttons are full pills; cards are modestly rounded; product images retain their photographic edges.

## Components

### Global Nav
White top bar with Starbucks logo, Menu, Rewards, Gift Cards, Find a store, Sign in, and Join now. Desktop uses inline links; mobile collapses into a drawer with account links such as Card management, My Rewards, History, Personal info, Payment methods, Privacy and data, Settings, and Sign out.

### Homepage Promo Bands
Current bands include "It's a great day for coffee", "It's Starbucks summer", Unicorn Cake Pop, Khloud Protein Popcorn, and Military Appreciation eGift. Use real product or campaign photography, a short headline, brief body copy, and a single pill CTA.

### Buttons
Primary actions use Green Accent filled pills; secondary actions use outlined green pills; account conversion uses black filled Join now and dark outlined Sign in. All should use 50px radius and `scale(0.95)` active feedback.

### Product Photography
Use bright, appetizing product imagery: layered drinks on sunlit surfaces, cake pops on plates, food/package photography, and photographed eGift cards. Avoid generic abstract illustrations for food/order modules.

### Gift Cards
Gift cards are treated as physical illustrated objects. The current homepage highlights Military Appreciation eGift cards and donation copy. Preserve legal/partner footnotes when relevant.

### Feedback Tab
Fixed "Provide feedback" tab uses green fill, white text, and top-rounded corners. It is a utility affordance, not a promotional CTA.

### Footer
Footer is large and link-heavy. Columns: About Us, Careers, Social Impact, For Business Partners, Order and Pick Up. Include social links and legal/privacy/accessibility links.

## Do's and Don'ts

### Do
- Use Green Accent for order/menu CTAs.
- Use warm neutral or white section bands.
- Keep all buttons pill-shaped.
- Use product photography as the primary visual signal.
- Keep seasonal copy short and direct.
- Preserve long legal/footnote copy for donations and promotions.
- Use the footer taxonomy; it is part of the current site structure.

### Don't
- Do not flatten all greens into one brand green.
- Do not use gold outside Rewards or star-cost contexts.
- Do not make buttons square.
- Do not replace real food/drink photography with abstract art.
- Do not introduce gradients or glassmorphism.
- Do not over-darken the homepage; dark green is a feature-band color, not the whole canvas.

## Responsive Behavior

### Breakpoints

| Breakpoint | Width | Behavior |
|---|---:|---|
| XS | `< 480px` | 64px nav, hamburger drawer, stacked promo bands |
| Mobile | `480px-767px` | 72px nav, single-column content, full-width CTAs where needed |
| Tablet | `768px-1023px` | 83px nav, split image/text modules begin |
| Desktop | `1024px-1439px` | 99px nav, full alternating promo layout |
| XL | `1440px+` | Content caps around 1440px with larger warm margins |

### Behavior Notes
- Stack hero image and text on mobile.
- Keep product imagery legible and uncropped around key items.
- Maintain 44px+ effective touch targets, even if visual pill height is smaller.
- Footer columns should collapse into accordions or stacked groups.
- Feedback tab remains available but should not cover primary CTAs.

## Iteration Guide

If a Starbucks screen feels generic, check the green mapping first: Starbucks Green for brand, Green Accent for CTAs, House Green for deep bands. Then verify SoDoSans-like tracking, 50px pill buttons, and warm surface color.

If a homepage module feels too heavy, return it to the current pattern: product image, short headline, short paragraph, one CTA. Starbucks seasonal pages work because they are clear retail signage, not dense editorial layouts.

## Known Gaps

- Homepage campaign content changes seasonally; this capture reflects the Starbucks summer / Military Appreciation homepage seen through Lightpanda.
- SoDoSans and Lander Tall are proprietary; public implementations need documented substitutes such as Inter/Manrope and Iowan Old Style/Lora.
- Logged-in account, order cart, and product customization states are deeper than the anonymous homepage capture.
- Menu/PDP nutrition details are not revalidated in this update, though the component tokens remain compatible with the broader Starbucks system.
