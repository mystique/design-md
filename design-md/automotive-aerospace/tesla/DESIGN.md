---
version: alpha
name: Tesla
description: |
  Tesla's public web system is a product-first digital showroom built from
  full-bleed vehicle and energy imagery, Universal Sans, a restrained
  monochrome palette, a single blue action color, and almost invisible UI
  chrome. The global navigation groups the business into Vehicles, Energy,
  Charging, Discover, and Shop, while sales and offer surfaces revolve around
  Model 3, Model Y, Cybertruck, Current Offers, Inventory, Full Self-Driving
  (Supervised), Superchargers, Solar Panels, Powerwall, Megapack, and Solar
  Roof. The current homepage verified through Lightpanda leads with Model 3
  and Model Y promotions, then turns into a modular product-and-energy grid.
  The design language is quiet, precise, and extremely flat: photography
  carries the emotion, while interface elements stay simple enough to
  disappear.

colors:
  primary: "#3e6ae1"
  primary-hover: "#3457b1"
  primary-pressed: "#2e4994"
  primary-on: "#ffffff"
  canvas: "#ffffff"
  canvas-alt: "#f4f4f4"
  surface: "#ffffff"
  surface-subtle: "#f7f7f7"
  surface-frosted: "rgba(255,255,255,0.75)"
  surface-overlay: "rgba(128,128,128,0.65)"
  ink: "#171a20"
  body: "#393c41"
  muted: "#5c5e62"
  placeholder: "#8e8e8e"
  border: "#d0d1d2"
  divider: "#eeeeee"
  dark-surface: "#171a20"
  dark-overlay: "rgba(0,0,0,0.35)"
  transparent: "rgba(0,0,0,0)"
  focus: "#3e6ae1"
  success: "#12bb00"
  warning: "#fbb01b"
  error: "#b74134"

typography:
  hero:
    fontFamily: Universal Sans Display
    fallback: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif
    fontSize: 40px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: 0
  page-title:
    fontFamily: Universal Sans Display
    fontSize: 48px
    fontWeight: 500
    lineHeight: 1.17
    letterSpacing: 0
  section-title:
    fontFamily: Universal Sans Display
    fontSize: 32px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: 0
  product-name:
    fontFamily: Universal Sans Text
    fontSize: 17px
    fontWeight: 500
    lineHeight: 1.18
    letterSpacing: 0
  nav:
    fontFamily: Universal Sans Text
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: 0
  button:
    fontFamily: Universal Sans Text
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: 0
  body:
    fontFamily: Universal Sans Text
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: 0
  body-lg:
    fontFamily: Universal Sans Text
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  caption:
    fontFamily: Universal Sans Text
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  promo:
    fontFamily: Universal Sans Text
    fontSize: 22px
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: 0

spacing:
  none: 0
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 40px
  section: 64px
  hero: 80px
  page-gutter-mobile: 24px
  page-gutter-desktop: 48px
  nav-height: 56px
  button-width: 200px
  button-height: 40px

rounded:
  none: 0
  control: 4px
  card: 12px
  pill: 9999px
  circle: 50%

elevation:
  none: none
  inset-focus: "rgba(0,0,0,0) 0 0 0 2px inset"
  frosted: "backdrop-filter blur(16px)"
  overlay: "rgba(128,128,128,0.65)"
  subtle: "0 1px 2px rgba(0,0,0,0.05)"

components:
  site-header:
    backgroundColor: transparent
    scrolledBackgroundColor: "{colors.surface-frosted}"
    textColor: "{colors.ink}"
    height: 56px
    logo: TESLA wordmark
    centerNav: Vehicles, Energy, Charging, Discover, Shop
    rightNav: Support, language, account
    rounded: "{rounded.none}"
    shadow: "{elevation.none}"
  nav-item:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    hoverBackgroundColor: "{colors.canvas-alt}"
    typography: "{typography.nav}"
    rounded: "{rounded.control}"
    padding: "4px 16px"
    minHeight: 32px
  primary-button:
    backgroundColor: "{colors.primary}"
    hoverBackgroundColor: "{colors.primary-hover}"
    textColor: "{colors.primary-on}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    minHeight: 40px
    width: 200px
    border: "3px solid transparent"
  secondary-button:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    minHeight: 40px
    width: 200px
    border: "3px solid transparent"
  hero-section:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    media: full-bleed responsive image or video
    height: "100vh"
    contentAlign: center top
    ctaLayout: centered pair
    rounded: "{rounded.none}"
  vehicle-card:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.product-name}"
    image: transparent vehicle render
    links: Learn, Order
    linkColor: "{colors.muted}"
    rounded: "{rounded.none}"
    shadow: "{elevation.none}"
  category-card:
    backgroundColor: full-bleed image
    textColor: "{colors.primary-on}"
    rounded: "{rounded.card}"
    overflow: hidden
    labelPosition: top-left
    shadow: "{elevation.none}"
  stat-panel:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.page-title}"
    metrics: 7x fewer collisions, miles driven counter
    ctaLayout: Schedule Demo, Learn More
    rounded: "{rounded.none}"
  current-offers-card:
    backgroundColor: full-bleed image
    textColor: "{colors.ink}"
    title: Current Offers
    cta: Learn More
    rounded: "{rounded.card}"
    shadow: "{elevation.none}"
  inventory-card:
    backgroundColor: full-bleed image
    textColor: "{colors.ink}"
    links: New, Pre-Owned
    rounded: "{rounded.card}"
    shadow: "{elevation.none}"
  charge-map-card:
    backgroundColor: map tile surface
    textColor: "{colors.ink}"
    title: Find Your Charge
    links: View Network, Learn More
    rounded: "{rounded.card}"
  energy-card:
    backgroundColor: full-bleed image
    textColor: "{colors.ink}"
    products: Solar Panels, Powerwall, Megapack, Solar Roof
    ctaLayout: Order Now, Learn More
    rounded: "{rounded.card}"
  form-field:
    backgroundColor: "{colors.surface-subtle}"
    textColor: "{colors.ink}"
    placeholderColor: "{colors.placeholder}"
    border: "1px solid {colors.border}"
    focusBorder: "1px solid {colors.focus}"
    rounded: "{rounded.control}"
    typography: "{typography.body}"
  chat-bar:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    border: "1px solid {colors.divider}"
    position: fixed bottom
    examples: Compare Model 3 and Model Y, What's Pet Mode?, What does the Tesla app do?
    secondaryCta: Schedule a Drive Today
    rounded: "{rounded.none}"
  offer-form:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    interestOptions: Model S, Model 3, Model X, Model Y, Cybertruck
    typography: "{typography.body}"
---

## Overview

Tesla's site remains one of the most restrained large-scale commerce systems on the web. Lightpanda successfully rendered the current homepage on May 17, 2026: the top nav exposes **Vehicles**, **Energy**, **Charging**, **Discover**, **Shop**, **Support**, region/language, and Account, then the page opens on **Model 3** with "One Year of Free Supercharging Included" and a Model Y promotion with **0% APR Available**. Both hero blocks use the same paired action pattern: **Order Now** and **Learn More**.

Below the opening vehicle promotions, the homepage shifts from full-screen showroom into a modular commercial grid: **Full Self-Driving (Supervised)** with 7x fewer collisions and a live miles-driven counter, vehicle cards for Model 3 / Model Y / Cybertruck, **Current Offers**, **Inventory**, a charging-network map, and energy cards for **Solar Panels**, **Powerwall**, **Megapack**, and **Solar Roof**. This is not only a hero carousel anymore; it is a product, offer, charging, and energy index.

The interface does not try to create brand drama through components. It uses photography and product renders as the emotional layer, then overlays a small set of precise controls: blue primary buttons, white secondary buttons, 14px navigation, image cards, product links, map tiles, forms, and a persistent **Tesla Assist** support/chat pattern with suggested prompts and "Schedule a Drive Today." Official Tesla pages still expose the larger mission structure: electric vehicles, solar, batteries, and scalable clean-energy systems.

The older Tesla read focused on full-screen automotive heroes and the "invisible interface" idea. That still holds, but the current system should also account for more transactional surfaces: current offers forms, product interest checkboxes, shop categories, sign-up/contact fields, and account/support navigation. The result is a quiet system that must work as both showroom and conversion funnel.

**Key Characteristics:**
- Universal Sans Display for hero/product titles and Universal Sans Text for UI.
- Global nav: Vehicles, Energy, Charging, Discover, Shop.
- Current homepage lead: Model 3 free Supercharging offer and Model Y 0% APR offer.
- Homepage product set: Model 3, Model Y, Cybertruck, FSD (Supervised), Current Offers, Inventory, charging map, Solar Panels, Powerwall, Megapack, Solar Roof.
- Single primary chromatic color: Tesla blue (`#3e6ae1`).
- Full-bleed photography and product renders carry most brand expression.
- Buttons use a restrained 4px radius and 40px height.
- Dropdown vehicle cards use transparent product renders, centered names, and plain Learn / Order links.
- Forms and offers are utilitarian, low-chrome, and built around clear fields and consent copy.
- Footer remains terse: Tesla © 2026, Privacy & Legal, Recalls, Contact, News, Updates, Locations, Learn.

## Colors

### Brand & Action
- **Tesla Blue** (`{colors.primary}` / `#3e6ae1`): Primary CTA fill, focus color, and the only dominant interaction color. Use for actions such as Order Now, Submit, or Schedule.
- **Blue Hover** (`#3457b1`): Slightly deeper hover state for blue actions.
- **White** (`#ffffff`): Main surface, secondary button fill, dropdown panel background, and product-card canvas.

### Surface
- **Canvas** (`#ffffff`): Default page surface and nav/dropdown background.
- **Light Ash** (`#f4f4f4`): Alternate surface for subtle section breaks and hover backgrounds.
- **Subtle Surface** (`#f7f7f7`): Form fields and quiet utility panels.
- **Frosted Surface** (`rgba(255,255,255,0.75)`): Header treatment over content when a translucent layer is needed.
- **Dark Surface** (`#171a20`): Hero text context, dark overlays, and rare dark-mode surfaces.

### Text
- **Carbon Dark** (`#171a20`): Product names, headings, nav labels, and high-priority copy.
- **Graphite** (`#393c41`): Body text and secondary UI content.
- **Pewter** (`#5c5e62`): Tertiary links such as Learn, Order, and supporting labels.
- **Silver Fog** (`#8e8e8e`): Placeholder and disabled-adjacent text.
- **Cloud Gray** (`#eeeeee`) and **Pale Silver** (`#d0d1d2`): Dividers, borders, and form outlines.

### Semantic
Tesla marketing pages rarely show heavy semantic colors. Use green, warning yellow, and red only for form/system states, not for brand decoration. Blue remains the main interaction signal.

## Typography

### Font Family
- **Display**: `Universal Sans Display`, fallback to system sans. Use for hero titles, product names at large scale, and major section headings.
- **Text/UI**: `Universal Sans Text`, fallback to system sans. Use for navigation, CTAs, forms, body copy, and product metadata.
- **No decorative typography**: no italics, no expressive serif, no uppercase transformation as a default voice.

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|---|---|---:|---:|---:|---:|---|
| Page Title | Universal Sans Display | 48px | 500 | 1.17 | 0 | Larger product/mission pages |
| Hero Title | Universal Sans Display | 40px | 500 | 1.20 | 0 | Full-bleed model sections |
| Section Title | Universal Sans Display | 32px | 500 | 1.25 | 0 | Offer/product group headings |
| Product Name | Universal Sans Text | 17px | 500 | 1.18 | 0 | Dropdown cards and compact product labels |
| Nav Item | Universal Sans Text | 14px | 500 | 1.20 | 0 | Vehicles, Energy, Charging, Discover, Shop |
| Button | Universal Sans Text | 14px | 500 | 1.20 | 0 | Primary and secondary CTAs |
| Body | Universal Sans Text | 14px | 400 | 1.43 | 0 | Paragraphs, form copy, consent |
| Caption | Universal Sans Text | 12px | 400 | 1.50 | 0 | Legal and supporting metadata |

### Principles
- Use medium weight, not bold, for emphasis.
- Keep letter spacing at `0`; the typeface should do the work.
- Keep most interface text at 14px for engineered consistency.
- Avoid uppercase labels unless the source content requires it.

## Layout

### Spacing System
Tesla's rhythm is compact in the UI and spacious in the page. Buttons and nav items use 4px/8px/16px internal spacing; page sections often occupy full viewport height; forms and offer surfaces use 16px-32px spacing with clear vertical grouping.

### Grid & Container
- Use full-bleed hero media with centered headline and CTA pair.
- Use dropdown panels with product-card grids and a side rail of plain links.
- Use offer and signup forms as centered, narrow content columns.
- Use shop/category pages as image-led card grids.
- Keep nav and content separation subtle; avoid visible heavy borders.

### Whitespace Philosophy
Tesla whitespace is a luxury and clarity signal. Each screen should have one message: one model, one offer, one form, one product group. Do not fill blank space with decoration.

## Elevation & Depth

Tesla's default elevation is flat. Depth comes from photography, z-index, and occasional translucent surfaces.

### Rules
- Do not add drop shadows to default cards, panels, or buttons.
- Use frosted/transparent header layering where content requires it.
- Use modal overlays only for focused tasks.
- Use borders sparingly, mostly for forms and focus states.

### Surface Stack
1. Full-bleed image or white canvas.
2. Transparent/frosted header.
3. Dropdown panels and forms on white.
4. Modal overlays for region, account, consent, or support tasks.

## Shapes

### Border Radius Scale
- **0px**: Hero sections, dropdown panels, major surfaces.
- **4px**: Buttons, nav hover states, inputs, focused controls.
- **12px**: Large photographic category cards only.
- **Circle**: Carousel dots and icon-only indicators.

### Geometry
Tesla geometry is precise and understated. Use low-radius rectangles and plain grids. Avoid pills, expressive blobs, chamfered luxury shapes, and decorative frames.

## Components

### Header & Navigation
The desktop header uses the TESLA wordmark, center category nav, and right-side support/language/account icons. Dropdowns should feel like white product trays: transparent vehicle renders, model names, Learn / Order links, and side lists for supporting products or categories.

### Hero Sections
Hero sections use full-viewport product imagery or video. The current homepage starts with Model 3 over `Homepage-Promo-Model-3-Desktop-US-CA-MX.jpg`, then Model Y over `Homepage-Promo-Meet-Model-Y-Desktop.jpg`. Text is centered and quiet: one product name, one offer line, then paired actions. CTA pairs sit below the headline: blue primary action and white secondary action.

### Buttons
Primary buttons are blue with white text; secondary buttons are white with graphite text. Both are 40px tall, 4px radius, and visually calm. State changes should be color and border changes, not scale or motion tricks.

### Vehicle Cards
Homepage vehicle cards are large image tiles, not only dropdown renders. Current cards include **Model 3** as Sport Sedan, **Model Y** as Midsize SUV, and **Cybertruck** as Utility Truck, each with a lease/offer line and Order Now / Learn More actions. Navigation product cards can remain transparent renders on white; homepage product cards use full-bleed photography.

### FSD / Metrics
The current FSD block is text and metrics driven: "Full Self-Driving (Supervised)", a subscription line, **7x Fewer Collisions**, a large miles-driven counter, and Schedule Demo / Learn More actions. Treat this as a sober stats panel, not an infographic-heavy dashboard.

### Offers, Inventory & Charging
Current Offers and Inventory appear as practical grid cards. Inventory uses New / Pre-Owned links. Find Your Charge uses a map tile surface with View Network and Learn More actions. These modules are functional wayfinding, so keep typography and controls quiet.

### Energy Cards
Solar Panels, Powerwall, Megapack, and Solar Roof use the same image-led tile grammar as vehicles. Solar Panels, Powerwall, and Solar Roof include Order Now / Learn More; Megapack is Learn More only. Do not restyle the energy business as a separate green brand.

### Forms & Offers
Offer/signup forms should use direct field labels, subdued gray inputs, clear validation, and plain consent copy. Current offer flows include product interests such as Model S, Model 3, Model X, Model Y, and Cybertruck.

### Shop / Category Cards
Shop and accessory surfaces use image-led category tiles: Model Y Accessories, Model 3 Accessories, Model S Accessories, Model X Accessories, Cybertruck Accessories, Charging, Apparel, and Lifestyle. These should be more grid-like than hero-like.

### Chat / Support Bar
A bottom support or "Ask a Question" pattern can be fixed to the viewport. Current Tesla Assist suggestions include "Compare Model 3 and Model Y", "What's Pet Mode?", "What does the Tesla app do?", and "Where can I drive the Model 3?", paired with "Schedule a Drive Today." Keep it white, narrow, and functional.

## Do's and Don'ts

### Do
- Let product imagery dominate.
- Use Tesla blue only for primary actions and focus.
- Keep UI type mostly at 14px and weight 400-500.
- Use 4px radius on controls.
- Use full-viewport hero sections for major product pages.
- Keep dropdown vehicle cards borderless and white.
- Make forms clear, quiet, and legally complete.
- Preserve the global business taxonomy: Vehicles, Energy, Charging, Discover, Shop.

### Don't
- Do not introduce additional brand accent colors.
- Do not add decorative gradients, shadows, or patterns.
- Do not use heavy outlines around cards.
- Do not use large hero-scale typography beyond the restrained Tesla range.
- Do not turn nav labels or CTAs into uppercase shouting.
- Do not make buttons pill-shaped.
- Do not clutter a hero with more than two primary actions.
- Do not make the UI feel more expressive than the vehicle or energy product imagery.

## Responsive Behavior

### Breakpoints

| Breakpoint | Width | Behavior |
|---|---:|---|
| Mobile | `< 768px` | Hamburger/drawer nav, stacked CTAs, single-column forms and cards |
| Tablet | `768px-1023px` | Reduced nav/dropdown grid, full hero remains, wider form columns |
| Desktop | `1024px-1439px` | Full header categories, dropdown product grid, side-by-side CTAs |
| Large Desktop | `1440px+` | Centered content, full-bleed media, restrained max widths for forms |

### Behavior Notes
- Maintain full-bleed hero imagery across breakpoints.
- Stack CTA pairs vertically on narrow screens.
- Keep controls at least 40px high, preferably 44px+ in touch-heavy contexts.
- Preserve image legibility; crop with `object-fit: cover` rather than shrinking.
- Keep long consent copy readable in forms.

## Iteration Guide

If a Tesla-inspired surface feels underdesigned, first improve the photography, product render, or spacing. Do not compensate with decorative UI. If it feels too generic, enforce the blue/white/gray palette, Universal Sans sizing, 4px control radius, and two-action CTA rhythm.

For commerce or offer flows, prioritize clarity over showroom drama. Use narrow forms, clean labels, subdued input surfaces, and explicit product-interest choices. For product pages, return to full-screen media and one-message-per-viewport rhythm.

## Known Gaps

- Direct `curl` access is blocked by Tesla's Akamai layer in this environment, but Lightpanda MCP successfully rendered the homepage and supplied current module content.
- Tesla's homepage campaigns, offers, incentives, and model ordering labels change frequently by market.
- The public site uses Tesla Design System classes (`tds-*`) and dynamic app rendering; exact runtime CSS may vary by page.
- This file captures the global Tesla web language, not every configurator, account, service, or in-vehicle UI state.
