---
version: alpha
name: Microsoft
description: "A broad consumer-and-business storefront built from restrained product editorial: white canvas, Segoe UI typography, Microsoft Blue (#0067b8) as the primary action color, and modular image cards that move fluidly between Surface hardware, Microsoft 365, Xbox, Copilot, enterprise, and social-impact stories. The system is pragmatic and retail-oriented: square card modules, subtle gray surfaces, dense navigation, direct CTAs, and product photography doing most of the emotional work."

colors:
  primary: "#0067b8"
  primary-hover: "#005da6"
  primary-pressed: "#004e8c"
  primary-dark: "#004578"
  accent-copilot: "#0078d4"
  ink: "#1a1a1a"
  body: "#333333"
  body-muted: "#505050"
  body-subtle: "#616161"
  inverse-ink: "#ffffff"
  canvas: "#ffffff"
  canvas-soft: "#f2f2f2"
  surface-card: "#ffffff"
  surface-muted: "#f7f7f7"
  surface-footer: "#f2f2f2"
  surface-dark: "#000000"
  hairline: "#e6e6e6"
  hairline-strong: "#d2d2d2"
  focus: "#000000"
  microsoft-red: "#f25022"
  microsoft-green: "#7fba00"
  microsoft-blue: "#00a4ef"
  microsoft-yellow: "#ffb900"
  on-primary: "#ffffff"
  on-dark: "#ffffff"

typography:
  hero-display:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 46px
    fontWeight: 600
    lineHeight: 1.13
    letterSpacing: 0
  display-lg:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 37px
    fontWeight: 600
    lineHeight: 1.16
    letterSpacing: 0
  display-md:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 29px
    fontWeight: 600
    lineHeight: 1.21
    letterSpacing: 0
  headline:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 24px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0
  card-title:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 21px
    fontWeight: 600
    lineHeight: 1.29
    letterSpacing: 0
  lead:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.44
    letterSpacing: 0
  body:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-sm:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: 0
  body-sm-strong:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.43
    letterSpacing: 0
  nav-link:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.23
    letterSpacing: 0
  button:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0
  footer-heading:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 15px
    fontWeight: 600
    lineHeight: 1.33
    letterSpacing: 0
  footer-link:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0
  micro:
    fontFamily: "Segoe UI, SegoeUI, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.36
    letterSpacing: 0

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 6px
  lg: 8px
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
  container: 72px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 10px 20px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
  button-secondary:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 10px 0
  button-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 10px 20px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.body-sm-strong}"
    rounded: "{rounded.none}"
  global-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.none}"
    height: 54px
  utility-strip:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.none}"
    padding: 12px 24px
  hero-panel:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.hero-display}"
    rounded: "{rounded.none}"
    padding: 64px
  hero-panel-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    rounded: "{rounded.none}"
    padding: 64px
  content-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.body}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: 24px
  content-card-raised:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.body}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: 24px
    boxShadow: "0 2px 6px rgba(0, 0, 0, 0.16)"
  quick-link:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.primary}"
    typography: "{typography.body-sm-strong}"
    rounded: "{rounded.none}"
    padding: 16px 12px
  horizontal-story:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.headline}"
    rounded: "{rounded.none}"
    padding: 48px
  ai-assistant-panel:
    backgroundColor: "{colors.surface-muted}"
    textColor: "{colors.ink}"
    typography: "{typography.headline}"
    rounded: "{rounded.none}"
    padding: 32px
  carousel-dot:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 10px
  footer:
    backgroundColor: "{colors.surface-footer}"
    textColor: "{colors.body-muted}"
    typography: "{typography.footer-link}"
    rounded: "{rounded.none}"
    padding: 36px 72px
---

## Overview

Microsoft.com is not a single-product marketing page. It is a **federated storefront and editorial gateway** that must carry Surface hardware, Windows, Microsoft 365, Xbox, Copilot, business products, accessibility, sustainability, support, and investor-scale corporate information without changing visual languages between them.

The system is practical, modular, and retail-minded. A slim global navigation bar sits above large image-led hero placements, quick-link tiles, card grids, horizontal story bands, business sections, social links, and a dense footer. Almost every module is a rectangle on a white or light-gray field. Corners are square, typography is Segoe UI, CTAs are direct, and Microsoft Blue carries all action affordances.

The page uses polished photography and product renders for warmth rather than decorative UI. Surface devices, controllers, app-icon constellations, AI story photography, and soft abstract sustainability imagery provide the brand range. The interface around those assets stays neutral so the site can switch from college bundle commerce to enterprise Copilot to social impact without feeling like separate properties.

**Key Characteristics:**
- Segoe UI everywhere: readable, utilitarian, native to Windows, with no display/body family split.
- Microsoft Blue (`{colors.primary}` #0067b8) is the universal CTA and text-link color.
- Modular rectangular cards with image-first composition; light shadow appears on retail cards but corners stay square.
- Dense universal navigation and mega-menu taxonomy, followed by consumer-facing hero modules.
- White and pale gray dominate surfaces; color enters through imagery and the four Microsoft logo tiles, not through broad UI backgrounds.
- Direct commerce language: "Shop now", "See offer", "Join now", "Learn more", "Register for free".
- Page rhythm: nav -> utility strip -> hero carousel -> assistant prompt -> quick links -> consumer card grid -> horizontal story -> business card grid -> AI/editorial card grid -> impact banners -> social links -> dense footer.

## Colors

> Source analyzed: live Microsoft homepage at `https://www.microsoft.com/en-us/` on May 17, 2026. The page initially redirects by locale, so the US homepage was used as the stable source page.

### Brand & Accent

- **Microsoft Blue** (`{colors.primary}`): Primary buttons, text CTAs, link arrows, and commerce action states. It is saturated enough to survive on white cards and still recognizable as Microsoft.
- **Primary Hover / Pressed** (`{colors.primary-hover}`, `{colors.primary-pressed}`): Darker blue states for mouse and active interactions. These should feel like a compressed version of the same color, not a new accent.
- **Copilot / Fluent Blue** (`{colors.accent-copilot}`): A brighter system blue used when referencing Copilot, Fluent, or Windows-adjacent UI moments.
- **Four-square Logo Colors** (`{colors.microsoft-red}`, `{colors.microsoft-green}`, `{colors.microsoft-blue}`, `{colors.microsoft-yellow}`): Reserved for the Microsoft mark or tiny brand references. Do not expand them into section backgrounds or decorative confetti.

### Surface

- **Canvas** (`{colors.canvas}`): Default page background and card fill.
- **Soft Canvas** (`{colors.canvas-soft}`): The footer, page-level utility strips, and broad gray bands.
- **Muted Surface** (`{colors.surface-muted}`): Assistant prompts, AI panels, and subtle alternate modules.
- **Dark Surface** (`{colors.surface-dark}`): Rare, mostly for media overlays or dark retail imagery; not a common site-wide section color.
- **Hairlines** (`{colors.hairline}`, `{colors.hairline-strong}`): Borders, card separation, footer rules, and menu dividers.

### Text

- **Ink** (`{colors.ink}`): Headlines and high-emphasis navigation.
- **Body** (`{colors.body}`): Default paragraph copy. Microsoft avoids near-black severity in normal body type.
- **Muted / Subtle Body** (`{colors.body-muted}`, `{colors.body-subtle}`): Footer links, captions, secondary module text, and legal notes.
- **Inverse Ink** (`{colors.inverse-ink}`): White copy on dark image panels.

### Color Philosophy

Microsoft's interface color system is restrained because the product portfolio is already visually busy. The four-color brand mark appears in the logo, app icon imagery, and product screenshots; broad UI surfaces should remain white, black, gray, or blue. Avoid rainbow gradients, heavy color blocking, or making every product area use its own accent.

## Typography

### Font Family

The system uses **Segoe UI / SegoeUI** across display, body, navigation, buttons, and footer. This is the Windows-native brand voice: calm, practical, and highly readable. Fallbacks should be `Helvetica Neue, Helvetica, Arial, sans-serif`.

Unlike Apple or IBM, Microsoft does not signal premium tone through unusual weight or tracking. Hierarchy comes from size, weight 600, and placement. Letter-spacing remains `0` throughout.

### Hierarchy

| Token | Size | Weight | Line Height | Use |
|---|---:|---:|---:|---|
| `{typography.hero-display}` | 46px | 600 | 1.13 | Homepage hero title |
| `{typography.display-lg}` | 37px | 600 | 1.16 | Large horizontal story headings |
| `{typography.display-md}` | 29px | 600 | 1.21 | Section headings |
| `{typography.headline}` | 24px | 600 | 1.25 | Story module headings |
| `{typography.card-title}` | 21px | 600 | 1.29 | Product card title |
| `{typography.lead}` | 18px | 400 | 1.44 | Hero supporting copy |
| `{typography.body}` | 16px | 400 | 1.50 | Paragraph copy |
| `{typography.body-sm}` | 14px | 400 | 1.43 | Card body, helper copy |
| `{typography.body-sm-strong}` | 14px | 600 | 1.43 | Link labels, quick links |
| `{typography.nav-link}` | 13px | 400 | 1.23 | Universal nav |
| `{typography.footer-link}` | 11px | 400 | 1.45 | Footer link columns |

### Principles

- **Weight 600 is the headline voice.** Use 600 for hero, section, and card headings. Do not use 700 unless a local product surface already does.
- **Body copy stays plain.** Keep body at 16px/400, line-height 1.5. Microsoft pages optimize for fast comprehension across many modules.
- **No negative tracking.** Segoe UI should breathe naturally; tight Apple-like tracking makes Microsoft look wrong.
- **Small type is important.** Navigation and footer use 13px and 11px respectively, because information architecture density is part of the brand.
- **Sentence case wins.** CTAs, nav, headings, and footer labels use normal sentence/title casing, not all-caps editorial treatment.

## Layout

### Spacing System

- **Base unit:** 4px, expressed mostly as 8 / 12 / 16 / 24 / 32 / 48 / 64.
- **Container padding:** Desktop pages commonly hold a centered max-width content area with 60-72px side padding.
- **Section padding:** `{spacing.section}` 64px on large bands; card groups can be tighter at 48px.
- **Card padding:** 24px inside rectangular content cards.
- **Button padding:** 10px vertical by 20px horizontal for primary CTAs.

### Grid & Container

- Desktop retail cards use a 4-up grid for consumer products, then a separate 4-up grid for business modules.
- Editorial and impact stories often switch to horizontal split modules: image on one side, copy on the other, both rectangular.
- Quick links form an icon-and-label row: Surface, Microsoft 365, Xbox, PC finder, accessories, business.
- Footer uses six dense columns and a corporate-link baseline, all on `{colors.surface-footer}`.

### Page Rhythm

Microsoft uses sequence rather than drama. The homepage is a stack of functional modules: hero carousel, assistant prompt, quick links, cards, business cards, AI stories, impact banners, social follow row, footer. There is little empty theatrical space. Each module answers "where should this visitor go next?"

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow, no border | Nav, hero image panels, broad story bands |
| Hairline | 1px `{colors.hairline}` | Footer dividers, mega-menu boundaries, subtle card separation |
| Retail card | `0 2px 6px rgba(0, 0, 0, 0.16)` | Product cards sitting on a white/light-gray background |
| Image depth | Native product photography shadows | Surface hardware, controllers, app icon compositions |

Depth is functional, not atmospheric. The card shadow separates a retail module from the background; it is not used to create glossy SaaS panels. Most emotional depth comes from the photography: floating Surface devices, close-up controller texture, Copilot screenshots, and editorial story images.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---:|---|
| `{rounded.none}` | 0px | Default for buttons, cards, nav, hero modules |
| `{rounded.xs}` | 2px | Fine focus/indicator details |
| `{rounded.sm}` | 4px | Product UI screenshots or embedded Fluent controls |
| `{rounded.md}` | 6px | Rare product-surface panels |
| `{rounded.lg}` | 8px | Rare Fluent-adjacent app surfaces, not homepage cards |
| `{rounded.pill}` | 9999px | Search chips or assistant prompts only when explicitly chip-like |

Microsoft.com homepage modules are mostly square. Rounded Fluent controls exist inside screenshots and product surfaces, but the marketing shell itself stays rectangular.

## Components

### Universal Navigation

`{components.global-nav}` is a 54px white navigation bar with the Microsoft logo, product links, "All Microsoft", search, cart, and sign-in. It is intentionally dense and text-first. Dropdowns become mega menus organized by product category: Software, PCs & Devices, Entertainment, Business, Developer & IT, Other.

### Hero Carousel

`{components.hero-panel}` pairs a large product image with a 46px/600 headline, 16-18px supporting copy, and one blue primary CTA. The hero can use copy-over-image or copy-adjacent-image depending on asset composition. Controls are minimal: carousel dots and play/pause.

### Assistant Prompt

`{components.ai-assistant-panel}` is a short guidance module: "Hi there. How can we help?" with prompt chips such as "Ask me a question", "Which PC is right for me?", "Sign in to my account", and "How can AI help my business?" It should feel utility-oriented, not like a chatbot splash screen.

### Quick Links

`{components.quick-link}` combines a small product icon/render with a bold blue label. These links are compact shortcuts to major store journeys. Keep labels short and concrete.

### Content Cards

`{components.content-card}` and `{components.content-card-raised}` are the primary homepage module. Each card begins with an image, then title, body copy, and a link or button. Cards may cover Surface, Microsoft 365, Xbox, business trade-in, Copilot, events, or editorial AI stories without changing component structure.

### Horizontal Story Bands

`{components.horizontal-story}` supports larger narrative modules such as accessories, Project C.U.R.E., or sustainability. These use wide imagery and a larger heading, but remain simple rectangles with a direct CTA.

### Footer

`{components.footer}` is dense and utilitarian: six columns, small 11px links, gray background, and a corporate baseline for language, privacy, legal, recycling, ads, and copyright. Do not simplify it into a sparse marketing footer; the density is part of Microsoft.com.

## Imagery

Microsoft's image language is product-led and inclusive:

- **Surface hardware**: clean device renders, often floating or arranged in product families.
- **App ecosystems**: Microsoft 365 and Copilot shown as icon clusters, UI screenshots, or app-grid compositions.
- **Xbox**: tactile controller photography and game art grids.
- **Business**: device families, Copilot UI, accessibility/event graphics.
- **Editorial/social impact**: documentary photography and soft abstract sustainability scenes.

Images should be crisp, bright, and literal. Avoid dark atmospheric stock photography unless the story itself calls for it. The site benefits from immediate product recognition, not mystery.

## Motion & Interaction

- Hero carousel supports play/pause and dot navigation.
- Links use a small arrow/chevron convention and darken on hover.
- Primary buttons darken on hover and pressed states.
- Mega-menu opens from the universal nav with dense category columns.
- "Back to top" appears after long scroll.
- Focus states should be highly visible, usually black or blue outlines; Microsoft prioritizes accessibility over subtlety.

## Responsive Behavior

- Global nav collapses into a hamburger/search pattern on small screens.
- Hero imagery stacks above text on mobile; text remains left-aligned and CTA stays full-width or near-full-width when needed.
- 4-up card grids collapse to 2-up at tablet and 1-up at mobile.
- Quick links wrap into a compact grid rather than horizontal overflow.
- Footer columns stack into accordions or grouped vertical lists on mobile.
- Image crops should preserve product identity: do not crop away the Surface screen, Xbox controller controls, or app-icon clusters.

## Accessibility

Accessibility is visible in Microsoft.com's design posture:

- Keep contrast high: blue links on white, white text on dark image panels, charcoal body copy on light surfaces.
- Use real text for headings and CTAs; do not bake critical copy into images.
- Provide descriptive alt text for product and editorial imagery.
- Preserve keyboard-visible focus outlines.
- Keep carousel controls explicit and include play/pause.
- Avoid relying solely on color for product category distinctions.

## Implementation Guardrails

- Do use Segoe UI and Microsoft Blue before reaching for any decorative palette.
- Do keep cards rectangular and image-first.
- Do use the four Microsoft logo colors only for the logo or literal Microsoft/app ecosystem references.
- Do maintain footer and navigation density; oversimplification makes the page feel unlike Microsoft.com.
- Do let product photography and screenshots carry visual richness.
- Do not make broad rainbow gradients from the logo colors.
- Do not use Apple-like negative tracking, oversized whitespace, or pill-shaped CTAs as the default.
- Do not make the homepage look like a single-product SaaS landing page; it is a multi-audience navigation and commerce surface.
- Do not round every card. Fluent UI may use radius inside product screenshots, but the Microsoft.com marketing shell is mostly square.
