---
version: alpha
name: Ableton
description: |
  Ableton's current public site is a music-maker editorial system built from
  stark black text, Futura PT, white and dolphin-gray surfaces, vivid flat
  campaign color, and large artist/product imagery. The homepage leads with
  Live 12.4 news, then drops into magazine-like grids for latest posts,
  tutorial videos, free downloads, learning resources, newsletter signup, and
  a dense footer. The design is direct, square-edged, instructional, and
  recognizably Berlin: software and hardware are presented with the clarity of
  a manual, while high-saturation color and big media keep the system musical.

colors:
  ink: "#000000"
  primary: "#0000ff"
  primary-on: "#ffffff"
  body: "#000000"
  body-muted: "#666666"
  body-subtle: "#999999"
  canvas: "#ffffff"
  page: "#f3f3f3"
  dolphin: "#eeeeee"
  separator: "#eeeeee"
  field: "#ffffff"
  focus-shadow: "rgba(0,0,255,0.5)"
  overlay: "rgba(0,0,0,0.6)"
  overlay-button: "rgba(0,0,0,0.5)"
  cobalt: "#4200ff"
  salmon: "#ff8389"
  lemonade: "#fbffa7"
  lemon: "#fbfa61"
  lilac: "#c176fd"
  lilac-light: "#dbd2f0"
  sherbet: "#ffc2ca"
  antarctica: "#6dcbff"
  lavender: "#d5b3ff"
  periwinkle: "#b1c5ff"
  indigo: "#7600e2"
  goldfish: "#fed134"
  tangerine: "#ff7000"
  teal: "#00a2b0"
  sapphire: "#6682ff"
  flamingo: "#ff00c2"
  malachite: "#00ffaf"
  sunshine: "#fdf900"
  turquoise: "#00ffff"
  coral: "#fe5948"
  razzmatazz: "#ff0956"
  watermelon: "#ff5157"
  desert: "#d34312"
  tiffany: "#00d2be"
  aquamarine: "#54bdcc"
  spearmint: "#b6ffc0"
  intro: "#047259"
  standard: "#0799d6"
  suite: "#3b3845"
  push: "#c7c8ca"
  loop-aquamarine: "#99e5ed"
  loop-primary: "#ff2b49"
  note-chartreuse: "#d6ff00"
  acid-yellow: "#e1ff8a"
  live12-release: "#f19ef9"
  live12-sand-light: "#ebf0dc"
  live12-coral-lighter: "#ffc3a5"
  error: "#ed0000"

typography:
  display-xxxxl:
    fontFamily: Futura PT
    fallback: Avenir, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Helvetica, Arial, sans-serif
    fontSize: 110px
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: 0
  display-xxxl:
    fontFamily: Futura PT
    fallback: Avenir, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Helvetica, Arial, sans-serif
    fontSize: 90px
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: 0
  display-xxl:
    fontFamily: Futura PT
    fontSize: 60px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: 0
  display-xl:
    fontFamily: Futura PT
    fontSize: 40px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0
  heading-lg:
    fontFamily: Futura PT
    fontSize: 30px
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: 0
  heading-md:
    fontFamily: Futura PT
    fontSize: 20px
    fontWeight: 700
    lineHeight: 1.5
    letterSpacing: 0
  body-lg:
    fontFamily: Futura PT
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-md:
    fontFamily: Futura PT
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-sm:
    fontFamily: Futura PT
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  label:
    fontFamily: Futura PT
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.5
    letterSpacing: 0
  utility:
    fontFamily: Futura PT
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.5
    letterSpacing: 0

spacing:
  xxxs: 4px
  xxs: 8px
  xs: 12px
  sm: 16px
  md: 20px
  lg: 30px
  xl: 40px
  xxl: 60px
  xxxl: 90px
  super: 120px
  page-gutter-mobile: 20px
  page-gutter-tablet: 40px
  page-gutter-desktop: 60px
  max-width: 1600px

rounded:
  none: 0
  media: 0
  control: 0
  modal: 0
  circle: 9999px

elevation:
  none: none
  focus: "0 0 3px rgba(0,0,255,0.5)"
  overlay: "0 0 0 9999px rgba(0,0,0,0.6)"
  media: none

components:
  nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    height: 68px
    border: none
    rounded: "{rounded.none}"
    links: Live, Push, Move, Note, Link, Shop, Packs, Help, More
    utilityLinks: Try Live 12 for free, Log in or register
  more-menu:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    sectionHeading: "{typography.body-sm}"
    cardTypography: "{typography.heading-md}"
    border: none
    rounded: "{rounded.none}"
    content: Blog, Classroom, Certified Training, About, Jobs, Loop, Learning Music, Learning Synths, Making Music
  hero-teaser:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.antarctica}"
    typography: "{typography.display-xxl}"
    media: full-bleed responsive image
    rounded: "{rounded.none}"
    minHeight: "calc(100vh - 68px)"
    cta: underlined arrow link
  blog-teaser:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    categoryColor: "{colors.primary}"
    typography: "{typography.heading-md}"
    mediaRatio: "600 / 340"
    rounded: "{rounded.none}"
    shadow: "{elevation.none}"
  category-strip:
    backgroundColor: "{colors.dolphin}"
    textColor: "{colors.ink}"
    linkColor: "{colors.primary}"
    typography: "{typography.body-md}"
    gap: "{spacing.md}"
    rounded: "{rounded.none}"
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-on}"
    typography: "{typography.label}"
    border: "2px solid {colors.primary}"
    rounded: "{rounded.none}"
    padding: "8px 18px"
    minHeight: 44px
    hoverBackgroundColor: "{colors.ink}"
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    border: "2px solid {colors.ink}"
    rounded: "{rounded.none}"
    padding: "8px 18px"
    minHeight: 44px
  link-arrow:
    textColor: "{colors.primary}"
    typography: "{typography.label}"
    decoration: underline
    affordance: small angled arrow after label
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    placeholderColor: "{colors.body-muted}"
    border: "2px solid {colors.ink}"
    focusBorder: "2px solid {colors.primary}"
    focusShadow: "{elevation.focus}"
    rounded: "{rounded.none}"
    padding: "8px 13px"
  select:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    border: "2px solid {colors.ink}"
    rounded: "{rounded.none}"
    padding: "8px 45px 8px 13px"
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    wordmarkScale: oversized
    newsletter: inline email input plus black/blue submit
    rounded: "{rounded.none}"
    padding: "60px 40px"
---

## Overview

Ableton's current site is less "music app landing page" than a working editorial index for music makers. The homepage opens with a full-bleed Live 12.4 takeover image and a huge Futura PT headline in pale blue, then moves into dense, useful rows: latest posts, tutorial videos, free downloads, category links, newsletter signup, education, community, language/location controls, and the "Made in Berlin" signature.

The interface is built around strong defaults: black text, white panels, dolphin-gray separators, blue links, square controls, large rectangular media, and almost no elevation. The brand personality comes from rhythm rather than ornament. Grids are practical and modular; arrows and underlines make links feel active; category labels turn blog content into a browsable magazine system.

The product ecosystem is explicit in navigation: Live, Push, Move, Note, Link, Shop, Packs, and Help all sit in the primary nav, while More exposes Blog, classroom material, training, company pages, and external learning properties. That breadth matters. Ableton is not only selling software; it is maintaining a learning and community surface for musicians.

**Key Characteristics:**
- Futura PT as the whole-site voice, using book and medium weights rather than a decorative display family.
- Hard black/white structure with `{colors.page}` as the outer surround and `{colors.canvas}` as the content surface.
- Ableton blue (`#0000ff`) for links, focus states, selection, and high-trust actions.
- Campaign color utilities spanning cobalt, antarctica, lavender, tangerine, coral, chartreuse, Live 12 pink, and many more.
- Square everything: controls, fields, cards, image frames, and section blocks.
- Homepage content grid mixing hero news, blog teasers, tutorials, downloads, and category strips.
- Interaction grammar based on underlined text and small arrow marks, not glossy buttons.

## Colors

### Brand & Core
- **Black** (`{colors.ink}` / `#000000`): Primary text, logo, borders, button fills, and modal overlays. Ableton uses real black, not softened charcoal.
- **Ableton Blue** (`{colors.primary}` / `#0000ff`): The main interaction color. It appears on links, focus rings, active accents, and some CTA surfaces.
- **White** (`{colors.canvas}` / `#ffffff`): Main page content background and footer surface.
- **Page Gray** (`{colors.page}` / `#f3f3f3`): Browser/body surround behind the white page.
- **Dolphin** (`{colors.dolphin}` / `#eeeeee`): Light category strips, separators, and quiet utility panels.

### Campaign Spectrum
Ableton keeps a large flat-color utility palette rather than one dominant accent family. Current CSS exposes vivid classes for cobalt, antarctica, lavender, indigo, goldfish, tangerine, malachite, turquoise, coral, razzmatazz, watermelon, tiffany, aquamarine, spearmint, note chartreuse, acid yellow, Live 12 release pink, and Live 12 sand. These colors should behave as **actual layout surfaces or text colors**, not as soft decorative glows.

### Text
- **Primary Text** (`#000000`): Body, headings, category names, navigation, footer.
- **Muted Text** (`#666666`): Metadata, placeholders, secondary explanatory copy.
- **Subtle Text** (`#999999`): Placeholder and disabled-adjacent states.
- **On Blue / On Black** (`#ffffff`): Button labels and overlays.

### Semantic
- **Focus** (`#0000ff` + `rgba(0,0,255,0.5)`): Form focus and keyboard emphasis.
- **Error** (`#ed0000`): Form validation errors.
- **Overlay** (`rgba(0,0,0,0.6)`): Modal scrim and fullscreen media backdrop.

## Typography

### Font Family
- **Primary**: `Futura PT` (`futura-pt` in CSS), with fallbacks to Avenir, system UI, Segoe UI, Roboto, Helvetica Neue, Helvetica, Arial, sans-serif.
- **Loaded Weights**: Book normal, Book Oblique, and Medium/Bold. The site does not need a separate expressive display font because Futura PT carries both product clarity and editorial confidence.
- **Mono Substitute**: Use SF Mono / Menlo / Monaco / Consolas only when rendering code-like utility fragments; the public marketing site is overwhelmingly sans.

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|---|---|---:|---:|---:|---:|---|
| Maximum Display | Futura PT | 110px | 700 | 1.0 | 0 | Campaign-scale type; use sparingly |
| Hero Display | Futura PT | 90px | 700 | 1.0 | 0 | Homepage takeover / product launch headline |
| Page Title | Futura PT | 60px | 700 | 1.1 | 0 | Large editorial pages |
| Section Title | Futura PT | 40px | 700 | 1.2 | 0 | Blog panels and section headers |
| Feature Title | Futura PT | 30px | 700 | 1.4 | 0 | Teaser and content-card headlines |
| Body Large | Futura PT | 20px | 400 | 1.5 | 0 | Intro copy and form text on larger screens |
| Body | Futura PT | 16px | 400 | 1.5 | 0 | Standard UI and paragraph copy |
| Small | Futura PT | 14px | 400 | 1.5 | 0 | Utility labels, metadata, captions |
| Link / Label | Futura PT | 16px | 700 | 1.5 | 0 | Nav, arrow links, categories, buttons |

### Principles
- Keep letter spacing at `0`; Ableton does not use luxury-style tracking.
- Use bold weight as structure, not as decoration. Headings, links, nav labels, and categories can be bold.
- Preserve readable copy rhythm with 1.5 line-height for body and 1.0-1.2 for display.
- Let underlines and arrows give links motion instead of relying on elaborate hover effects.

## Layout

### Spacing System
The spacing rhythm is grid-like and practical: 20px and 30px for components, 40px and 60px for sections, 90px and 120px for large editorial breaks. The homepage grid uses large rectangular cells, while footer and category areas use dense link columns.

### Grid & Container
- Use a white `.page` surface over a gray outer body.
- Keep a persistent product nav at desktop widths; collapse to a direct "Menu" affordance on mobile.
- Use large image-led cells with copy directly below or overlaid, not floating card chrome.
- Build content rows in 3-up or full-width grids, then collapse to single-column mobile stacks.
- Let the footer be dense and functional, with the Ableton wordmark as a large anchor.

### Whitespace Philosophy
Whitespace should feel like musical timing: deliberate, aligned, and useful. Ableton pages can have broad pauses around hero and product content, but the site is not sparse. Learning links, category lists, footer utilities, and newsletter signup remain visible and practical.

## Elevation & Depth

Ableton is almost completely flat. Visual depth comes from media scale, black/white contrast, gray section bands, and vivid color blocks. Avoid cards floating with shadows.

### Rules
- Use `none` for default shadows.
- Use `0 0 3px rgba(0,0,255,0.5)` only for focus states.
- Use black overlays for modal/video contexts.
- If a media edge needs separation, prefer a flat color field or strong crop over a shadow.

### Surface Stack
1. `{colors.page}` outer body.
2. `{colors.canvas}` main page.
3. `{colors.dolphin}` utility strips and separators.
4. Campaign-color blocks for featured states.
5. `{colors.overlay}` for modal/video states.

## Shapes

### Border Radius Scale
- **None** (`0`): Buttons, inputs, nav, teaser cards, category strips, media frames.
- **Circle** (`9999px`): Only when the element is inherently circular, such as a play button or icon control.

### Geometry
Ableton should feel rectangular and modular. Keep cards square, images square-edged, forms boxed, and buttons hard-cornered. Rounded SaaS pills or soft app-store cards dilute the brand.

## Components

### Header & Navigation
The top nav is a white horizontal bar with a compact Ableton mark and direct product links: Live, Push, Move, Note, Link, Shop, Packs, Help. The "More" menu expands into site/company links and learning properties. Utility links for trying Live and account login sit in the same nav system rather than in a separate marketing CTA band.

### Hero Teaser
The homepage hero is image-first and news-driven. The current lead promotes Live 12.4 with a full-bleed takeover image, huge pale-blue headline text, and an underlined arrow CTA. Treat the hero as editorial news, not as a generic centered app hero.

### Blog / Content Teasers
Teasers pair 600x340-style media crops with category labels and bold headlines. Categories such as Downloads and Tutorials are visible and useful. Cards should be flat, white, and grid-aligned; avoid nested card surfaces.

### Category Links
Category strips use blue text links and simple spacing: All posts, Artists, News, Downloads, Tutorials, Videos, Loop, One Thing. These are navigation controls, not tags for decoration.

### Forms
Inputs and selects are square, black-bordered, and direct. Focus switches the border to blue and adds a small blue glow. Footer newsletter signup uses this language in a compact inline group.

### Buttons & Links
Primary buttons can be blue or black with white text, but Ableton often prefers bold underlined text links with a small angled arrow. Use buttons for explicit forms, trials, shopping, or account actions; use arrow links for editorial discovery.

### Footer
The footer is not minimal. It includes a large Ableton wordmark, newsletter signup, register/about/jobs links, social icons, education links, community links, language and location selectors, legal links, and the "Made in Berlin" hallmark.

## Do's and Don'ts

### Do
- Use Futura PT-style geometric typography.
- Keep the base UI black, white, and dolphin-gray.
- Use Ableton blue for links, focus, and strong actions.
- Use vivid flat campaign colors as real panels or text colors.
- Show real software, hardware, artists, tutorials, and downloads.
- Keep cards, controls, and media square-edged.
- Use underlined arrow links for editorial navigation.
- Make footer and category areas dense but highly scannable.

### Don't
- Do not use glassmorphism, glossy gradients, or atmospheric SaaS blur.
- Do not round cards and buttons into pills.
- Do not turn the brand into a dark DAW interface unless the specific product page requires it.
- Do not replace the product ecosystem with vague "features" navigation.
- Do not make typography thin, widely tracked, or luxury-coded.
- Do not hide desktop navigation behind icon-only controls.
- Do not use campaign colors as tiny decorative flecks when they should be confident surfaces.

## Responsive Behavior

### Breakpoints

| Breakpoint | Width | Behavior |
|---|---:|---|
| Small Mobile | `< 480px` | Single-column content, menu trigger, reduced display type |
| Mobile / Small Tablet | `480px-767px` | Stacked teasers, touch-sized controls, large readable images |
| Tablet | `768px-1023px` | Two-column rows begin; footer groups remain readable |
| Desktop | `1024px+` | Persistent product navigation, full editorial grid |
| Wide Desktop | `1440px+` | Larger gutters and campaign-scale media; cap at broad readable widths |

### Behavior Notes
- Collapse grids by stacking, not by squeezing content until media becomes illegible.
- Preserve large image crops for tutorials, downloads, product UI, and artist content.
- Keep form controls at least 44px tall.
- Reduce display sizes in fixed steps; do not scale text continuously with viewport width.
- Maintain the blue focus style and square geometry across all breakpoints.

## Iteration Guide

When designing Ableton-inspired UI, start with the content role. Product launch and homepage surfaces can use massive media and campaign color; blog and learning surfaces should become clean teaser grids; account, checkout, or support flows should stay utilitarian with boxed forms and direct labels.

If the result feels too generic, increase the Futura PT boldness, add stronger arrow-link language, and make one campaign color occupy real layout space. If it feels too loud, return the canvas to white, use black text, and let only links/categories carry blue.

## Known Gaps

- The exact Live 12.4 campaign image palette can change with homepage promotions, so campaign-specific colors should be verified against the current page before generating a launch hero.
- The CSS exposes many legacy and product-specific color utilities; not every token should appear in one interface.
- Product pages for Live, Push, Move, and Note may introduce their own sub-brand color rhythms beyond the homepage.
- This file captures the public homepage and global system, not checkout, account, or full documentation states.
