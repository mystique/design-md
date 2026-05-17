---
version: alpha
name: Rolls-Royce
description: A cinematic super-luxury interface built from full-bleed film, black-purple canvas, Riviera Nights typography, and restrained outlined controls. The system treats every page like a private viewing room: video or photography fills the viewport, content appears as uppercase, widely tracked type, and UI chrome is reduced to monogram navigation, hairlines, and thin stroked CTAs. Purple (#6d30a7) is the only true brand accent, used sparingly as a royal dash rather than a loud action color.

colors:
  primary: "#6d30a7"
  primary-deep: "#281432"
  primary-void: "#1b0d2e"
  primary-ink: "#110619"
  accent-gold: "#b59b6e"
  ink: "#000000"
  body: "#222222"
  body-muted: "#676776"
  muted: "#9b9b9b"
  muted-soft: "#727281"
  hairline: "#dddddd"
  hairline-dark: "#3b3b3b"
  canvas: "#ffffff"
  canvas-soft: "#f7f7f7"
  canvas-quiet: "#f2f2f2"
  surface-dark: "#222222"
  surface-black: "#000000"
  surface-ink: "#151515"
  surface-purple: "#281432"
  surface-purple-deep: "#1b0d2e"
  surface-purple-black: "#110619"
  on-primary: "#ffffff"
  on-dark: "#ffffff"
  on-photo: "#ffffff"
  focus: "#b4c7cb"
  error: "#f94564"
  success: "#24603d"

typography:
  hero-display:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 56px
    fontWeight: 300
    lineHeight: 1.18
    letterSpacing: 4px
    textTransform: uppercase
  display-xl:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 44px
    fontWeight: 300
    lineHeight: 1.22
    letterSpacing: 3.6px
    textTransform: uppercase
  display-lg:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 34px
    fontWeight: 300
    lineHeight: 1.29
    letterSpacing: 2.5px
    textTransform: uppercase
  display-md:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 22px
    fontWeight: 300
    lineHeight: 1.64
    letterSpacing: 2.5px
    textTransform: uppercase
  heading-sm:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 2.5px
    textTransform: uppercase
  eyebrow:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 12px
    fontWeight: 500
    lineHeight: 2
    letterSpacing: 2px
    textTransform: uppercase
  body-lg:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 16px
    fontWeight: 300
    lineHeight: 1.75
    letterSpacing: 0.8px
  body:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 14px
    fontWeight: 300
    lineHeight: 2
    letterSpacing: 0.5px
  body-strong:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 2
    letterSpacing: 0.5px
  caption:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 13px
    fontWeight: 300
    lineHeight: 1.92
    letterSpacing: 0.5px
  nav-link:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.67
    letterSpacing: 1.2px
    textTransform: uppercase
  button:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: 2px
    textTransform: uppercase
  fine-print:
    fontFamily: "Riviera Nights, Helvetica, Arial, -apple-system, sans-serif"
    fontSize: 11px
    fontWeight: 300
    lineHeight: 1.64
    letterSpacing: 0.6px

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  pill: 9999px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  xxl: 64px
  section: 96px
  cinematic: 128px

components:
  top-nav:
    backgroundColor: transparent
    textColor: "{colors.on-photo}"
    typography: "{typography.nav-link}"
    height: 72px
  monogram-nav:
    backgroundColor: transparent
    textColor: "{colors.on-photo}"
    typography: "{typography.nav-link}"
    height: 72px
  button-primary:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 15px 30px
    height: 48px
  button-primary-on-light:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 15px 30px
    height: 48px
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 15px 30px
    height: 48px
  button-icon-stroked:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    rounded: "{rounded.full}"
    size: 48px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button}"
  text-link-on-dark:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
  hero-video-band:
    backgroundColor: "{colors.surface-black}"
    textColor: "{colors.on-photo}"
    typography: "{typography.hero-display}"
    padding: 96px
  hero-photo-band:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-photo}"
    typography: "{typography.display-xl}"
    padding: 96px
  editorial-photo-tile:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-lg}"
    rounded: "{rounded.none}"
    padding: 64px
  model-photo-tile:
    backgroundColor: "{colors.surface-black}"
    textColor: "{colors.on-photo}"
    typography: "{typography.heading-sm}"
    rounded: "{rounded.none}"
  journey-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.heading-sm}"
    rounded: "{rounded.none}"
    padding: 32px
  menu-overlay:
    backgroundColor: "{colors.surface-purple-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-md}"
    padding: 64px
  form-overlay:
    backgroundColor: "{colors.surface-purple-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
    padding: 64px
  text-input:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: 12px 0
    height: 48px
  filter-chip:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.eyebrow}"
    rounded: "{rounded.none}"
    padding: 8px 0
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body-muted}"
    typography: "{typography.fine-print}"
    padding: 64px
---

## Overview

Rolls-Royce Motor Cars' web presence is a **private cinema for super-luxury objects**. The homepage opens with video and full-bleed photography, not navigation density. Content is reduced to a slow sequence of title cards: "PROJECT NIGHTINGALE", "A COACHBUILD COLLECTION", "AN INTRODUCTION TO POSSIBILITY", and the recurring command "DISCOVER". The interface is theatrical but extremely controlled: black, white, deep aubergine, thin white strokes, and widely tracked Riviera Nights type.

Where Apple behaves like a product gallery and Bugatti behaves like a black-box museum, Rolls-Royce behaves like an invitation-only viewing room. The page is built from full-viewport cinematic slides, editorial image tiles, and an off-canvas menu that reveals the full model universe: Phantom, Phantom Extended, Spectre, Ghost, Ghost Extended, Cullinan, and Black Badge. Bespoke and Coachbuild are treated as first-class editorial categories, not secondary services.

The design system's signature tension is **soft luxury through hard geometry**. Buttons are not rounded pills; they are rectangular, stroked, and frequently paired with a circular stroked arrow icon. Text is light in weight but uppercase and letterspaced. Surfaces are either pure image/video, deep purple-black overlays, or plain white utility sections. There are almost no decorative flourishes because the material palette is already expressive: marble, desert, midnight paint, coachbuilt details, and the Spirit of Ecstasy.

**Key Characteristics:**

- Full-bleed video/photo first; UI appears as overlaid type and controls.
- Deep purple-black brand atmosphere (`{colors.primary-deep}` / `{colors.primary-ink}`), with purple `#6d30a7` used sparingly as a line, dash, or status accent.
- Riviera Nights is the entire voice: light weights, uppercase headings, wide letter-spacing, and unusually tall line-height for body copy.
- Primary CTAs are thin stroked rectangles with uppercase labels and arrow icons, not filled buttons.
- Monogram-centered navigation and menu overlays reinforce the private-club feeling.
- Responsive grid is unusually precise: desktop layouts use a 28-column rhythm with 16px gutters and 96px modules at wide screens.
- Hover/motion is cinematic: images dim or scale subtly (`opacity .4s`, `transform .4s`) rather than using color flashes.
- Forms, dealer finders, language selectors, and FAQs live in full-screen dark overlays, keeping utility flows inside the same ceremonial frame.

## Colors

> **Source page analyzed:** `https://www.rolls-roycemotorcars.com/en_GB/home.html` on May 16, 2026. Lightpanda extracted the live semantic page; the production CSS exposes Riviera Nights web fonts and recurring palette values including `#6d30a7`, `#281432`, `#1b0d2e`, `#110619`, `#222`, `#fff`, `#ddd`, `#676776`, and `#9b9b9b`.

### Brand & Accent
- **Royal Purple** (`{colors.primary}` — #6d30a7): The only vivid brand accent in the CSS. It appears as a thin dash/status color and should be used with restraint. It is not a generic button fill.
- **Deep Purple** (`{colors.primary-deep}` — #281432): Browser theme color and core brand atmosphere. It reads as Rolls-Royce's digital equivalent of lacquered aubergine.
- **Purple Void** (`{colors.primary-void}` — #1b0d2e): Dark overlay layer used when the interface needs more color than black but less visibility than a card.
- **Purple Ink** (`{colors.primary-ink}` — #110619): The deepest menu/form overlay tone. This is the default full-screen overlay background.
- **Accent Gold** (`{colors.accent-gold}` — #b59b6e): Rare heritage-metal accent. Use only for premium badges, Bespoke/Coachbuild highlights, or fine ornamentation. It should never become the main CTA color.

### Surface
- **White Canvas** (`{colors.canvas}` — #ffffff): Footer, accessory grids, utility overlays in light mode, and editorial card backgrounds.
- **Quiet Canvas** (`{colors.canvas-quiet}` — #f2f2f2): Subtle light section background and neutral product-card floor.
- **Soft Canvas** (`{colors.canvas-soft}` — #f7f7f7): Slightly warmer utility surface for dense grids.
- **Dark Surface** (`{colors.surface-dark}` — #222222): The default fallback behind video/photo bands and dark editorial blocks.
- **Black** (`{colors.surface-black}` — #000000): True void for video, full-screen image frames, and high-contrast overlays.
- **Ink Surface** (`{colors.surface-ink}` — #151515): Deep card or image-adjacent surface where pure black would be too severe.
- **Purple Surfaces** (`{colors.surface-purple}`, `{colors.surface-purple-deep}`, `{colors.surface-purple-black}`): Full-screen menus, form flows, language picker, and enquiry overlays.

### Text
- **Ink** (`{colors.ink}` — #000000): Primary text on white utility surfaces.
- **Body** (`{colors.body}` — #222222): Default long-form text on light surfaces.
- **Body Muted** (`{colors.body-muted}` — #676776): Footer links, subdued metadata, model descriptors.
- **Muted** (`{colors.muted}` — #9b9b9b): Secondary overlay text and disabled labels.
- **Muted Soft** (`{colors.muted-soft}` — #727281): Tertiary labels on light controls.
- **On Dark / On Photo** (`{colors.on-dark}` / `{colors.on-photo}` — #ffffff): All text over photography, video, and purple-black overlays.

### Hairlines & Feedback
- **Hairline** (`{colors.hairline}` — #dddddd): Light surface dividers, footer rules, accessory grid separators.
- **Hairline Dark** (`{colors.hairline-dark}` — #3b3b3b): Dividers inside dark overlays and dark input underlines.
- **Focus Blue-Grey** (`{colors.focus}` — #b4c7cb): Accessible focus or active outline where white would disappear.
- **Error** (`{colors.error}` — #f94564): Form validation only.
- **Success** (`{colors.success}` — #24603d): Confirmation states only.

### Brand Gradient
No CSS gradient is required for brand expression. Rolls-Royce uses **photographic atmosphere** and video lighting instead. If a text legibility overlay is needed on photography, use a transparent black scrim, not a decorative gradient.

## Typography

### Font Family
The production site preloads five Riviera Nights weights: Regular, Light, Medium, Ultralight, and Bold. In practice, the UI heavily favors **Light (300)** and **Regular/Medium (400/500)**. Bold exists in the font files but is not part of the core luxury voice.

- **Primary**: `Riviera Nights, Helvetica, Arial, -apple-system, sans-serif`.
- **CJK fallbacks**: the site swaps in `Noto Sans JP`, `Noto Sans KR`, or `Noto Sans SC` after Riviera Nights for localized markets.
- **No serif layer**: Unlike old-world luxury templates, the site stays all-sans. The luxury signal comes from weight, tracking, spacing, and photography.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.hero-display}` | 56px | 300 | 1.18 | 4px | Full-screen hero title cards and model-name moments |
| `{typography.display-xl}` | 44px | 300 | 1.22 | 3.6px | Large editorial page headings |
| `{typography.display-lg}` | 34px | 300 | 1.29 | 2.5px | Tout/title modules; CSS exposes 34px / 300 / 0.0735em |
| `{typography.display-md}` | 22px | 300 | 1.64 | 2.5px | Overlay menu section titles and secondary editorial headings |
| `{typography.heading-sm}` | 20px | 400 | 1.5 | 2.5px | Card titles and model tile labels |
| `{typography.eyebrow}` | 12px | 500 | 2.0 | 2px | Category labels ("PROJECT", "AN INTRODUCTION TO POSSIBILITY") |
| `{typography.body-lg}` | 16px | 300 | 1.75 | 0.8px | Lead copy on editorial pages |
| `{typography.body}` | 14px | 300 | 2.0 | 0.5px | Default paragraph; CSS commonly exposes 14px / 300 / 2 |
| `{typography.body-strong}` | 14px | 400 | 2.0 | 0.5px | Slightly firmer body copy |
| `{typography.caption}` | 13px | 300 | 1.92 | 0.5px | Descriptions, forms, helper copy |
| `{typography.nav-link}` | 12px | 400 | 1.67 | 1.2px | Main navigation labels |
| `{typography.button}` | 12px | 500 | 1.0 | 2px | CTA labels, always uppercase |
| `{typography.fine-print}` | 11px | 300 | 1.64 | 0.6px | Footer legal and microcopy |

### Principles

- **Uppercase is ceremonial.** Headings, labels, CTAs, navigation, and filter titles are uppercase with 0.1-0.18em tracking. Sentence case appears in descriptive copy and forms.
- **Light weight carries luxury.** Display titles are usually 300; body is 300; 500 is reserved for small labels that need structure.
- **Line-height is tall.** Body copy at 14px uses roughly `line-height: 2`. The prose should feel slow and spacious, not dense.
- **Letter-spacing replaces boldness.** Do not solve hierarchy by making text heavy. Increase tracking and scale first.
- **Text sits over image carefully.** On photography, copy stays short and high-contrast; long paragraphs move to split editorial blocks or overlays.

### Note on Font Substitutes
If Riviera Nights is unavailable:
- Use **Raleway** or **Jost** as the closest open-source substitute. The production CSS itself lists `Jost` and `Raleway` fallbacks in some localized contexts.
- Keep weights light (300/400/500), and increase letter-spacing for headings by `0.08em-0.16em`.
- Do not substitute a serif face; the current Rolls-Royce digital system is Riviera Nights-led, not heritage-serif-led.

## Layout

### Spacing System
- **Base unit:** 8px, with 16px as the dominant gutter.
- **Tokens:** `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 16px · `{spacing.md}` 24px · `{spacing.lg}` 32px · `{spacing.xl}` 48px · `{spacing.xxl}` 64px · `{spacing.section}` 96px · `{spacing.cinematic}` 128px.
- **Hero padding:** 96px+ vertical with content usually pinned to the lower third or centered over video.
- **Editorial blocks:** 64-96px interior padding, with image and text split across the grid.
- **Overlay padding:** 64px desktop, 24-32px mobile.

### Grid & Container
- **Desktop/wide grid:** Production CSS shows a wide-grid rhythm of 96px columns with 16px gutters and a 28-column layout family. Many components place content with spans like `grid-column: 4 / span 23`, `6 / span 7`, or `16 / span 14`.
- **Tablet grid:** 12-column family with 16px gutters.
- **Mobile grid:** 9-column family with 16px outside margins; most image/text pairs collapse with image first, copy second.
- **Max visual width:** Roughly 1328px on carousel and accessory surfaces.

### Whitespace Philosophy
Whitespace is not empty space; it is exclusivity. The homepage shows only a handful of messages across large photographic canvases. Dense content exists, but it is moved into overlays (FAQs, forms, dealer finder, language selector) or the footer. Never squeeze multiple marketing messages into a single hero. One frame, one thought, one CTA.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow, no border | Video hero, photo bands, main navigation |
| Hairline | 1px `{colors.hairline}` / `{colors.hairline-dark}` | Footer rules, form underlines, grid dividers |
| Stroked control | 1px white/black outline | Primary CTA rectangles and icon circles |
| Overlay | Full-screen purple-black surface | Menu, enquiry forms, language picker, FAQ |
| Photographic depth | Full-bleed video/photo, object-fit cover | Hero slides, model tiles, Bespoke editorial |

Rolls-Royce does not use card shadows as a hierarchy device. Depth comes from cinematic image lighting and from the switch between photograph and full-screen purple-black overlay.

### Motion Depth
- Image hover: `opacity .4s` and `transform .4s`, often scaling image media to `1.05`.
- Overlay transitions should feel slow and deliberate, not snappy.
- Carousel/slide navigation uses small numbered or icon controls, allowing motion to be part of the ceremony.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.none}` | 0px | Almost every layout surface: cards, images, buttons, inputs |
| `{rounded.xs}` | 2px | Rare scrollbar/thumb details only |
| `{rounded.sm}` | 4px | Technical UI fallback, not core marketing |
| `{rounded.pill}` | 9999px | Rare filter/status chips where production requires capsule hit areas |
| `{rounded.full}` | 9999px / 50% | Circular icon buttons and arrow controls |

The core radius grammar is **rectangular surfaces + circular icons**. Rounded cards or soft SaaS-style controls break the brand.

### Photography Geometry
- Hero media is full-bleed, usually `object-fit: cover`, with desktop crops favoring wide cinematic framing.
- Editorial image tiles can be square or portrait, but corners remain square.
- Model menu imagery uses dramatic partial vehicle crops, not catalog-style transparent renders.
- The homepage includes video modules and stills for Nightingale, Coachbuild Collection, Bespoke, and model entries.

## Components

### Navigation

**`top-nav`** — Transparent navigation over the hero. Height approximately 72px. Left side exposes "MENU"; center carries the Rolls-Royce monogram/brand mark; right side contains utility actions such as enquiry/dealer entry depending on surface. Text uses `{typography.nav-link}`, white over media, with minimal iconography.

**`monogram-nav`** — The centered brand anchor. It is the only persistent brand object and must remain visually quiet. Do not place it in a filled bar unless the page has scrolled into a utility section that requires a light nav mode.

**`menu-overlay`** — Full-screen purple-black overlay opened from MENU. Contains model imagery and primary sections: Inspiring Greatness, Models, Bespoke, Ownership, Provenance, Boutique, Muse Arts Programme. Model submenu lists Phantom, Phantom Extended, Spectre, Ghost, Ghost Extended, Cullinan, Black Badge, Configure, plus "View all". Typography scales from `{typography.display-md}` for category headings down to `{typography.nav-link}` for list items.

### Buttons

**`button-primary`** — Primary CTA on dark/photo surfaces. Transparent fill, white 1px stroke, uppercase `{typography.button}`, square corners, height 48px, padding 15px x 30px. Often paired with a separate stroked circular arrow icon. Labels: "DISCOVER MORE", "DISCOVER NOW", "DISCOVER".

**`button-primary-on-light`** — Same structure on white surfaces: transparent fill, black 1px stroke, black text. Used in footer/utility modules.

**`button-secondary`** — Filled white utility action used inside forms or dealer finder surfaces when a stronger action is needed. Same uppercase button type and square corners.

**`button-icon-stroked`** — Circular 48px arrow/close/back button. Transparent fill, 1px white stroke on dark overlays, black stroke on light surfaces. Used for overlay close, back, carousel controls, and CTA arrow companions.

**`text-link` / `text-link-on-dark`** — Uppercase text-only links. Use for footer links, menu links, and "View all" actions. Avoid underlines unless in legal or FAQ prose.

### Hero & Editorial Modules

**`hero-video-band`** — Full-viewport video slide. Background fallback `{colors.surface-black}`. Copy overlays in the lower or center band: eyebrow (`PROJECT`), headline (`Nightingale`), subheading (`A COACHBUILD COLLECTION`), then `{component.button-primary}`. Keep text short and never place it in a card.

**`hero-photo-band`** — Static full-bleed image version for model or Bespoke pages. Same typography and overlay rules as video. Use a transparent black scrim only when legibility requires it.

**`editorial-photo-tile`** — Used for "The world of bespoke" and Coachbuild editorial content. Full or split image surface, square corners, dark fallback. Heading in `{typography.display-lg}`, eyebrow in `{typography.eyebrow}`, body in `{typography.body}` if needed.

**`model-photo-tile`** — Vehicle tile inside menu/model showroom. Image dominates; title and "DISCOVER" link are minimal. Current homepage/menu models include Phantom, Phantom Extended, Spectre, Ghost, Ghost Extended, Cullinan, and Black Badge.

**`journey-card`** — "Explore Further / Continue Your Journey" card. Light surface, square corners, image at top or left, heading in `{typography.heading-sm}`, description in `{typography.caption}`. Examples include The History of Coachbuild, Rolls-Royce Arcadia Droptail, and Inspiring Greatness.

### Forms & Overlays

**`form-overlay`** — Full-screen dark overlay for Keep me informed, Request Information, Contact a Specialist, Request Callback, Request Viewing, Join Event, Request Brochure, Find a Dealer, Request Accessories, Whispers Request, Subscribe, Place Deposit, Purchase Enquiry, and General Enquiry. All these flows retain the same cinematic shell: Back button, close icon, uppercase form title, then understated underlined fields.

**`text-input`** — Transparent input with bottom hairline only. Height 48px, padding 12px 0, text in `{typography.body}`, label in `{typography.caption}` or `{typography.eyebrow}`. Focus should brighten the underline to white or `{colors.focus}` depending on contrast.

**`filter-chip`** — Used in accessory and model filters. It is typographic first: uppercase label, no filled pill unless mobile hit-target constraints require it. Active indicators can use a small purple dash.

### Footer

**`footer`** — White footer with quiet grey links. It contains Pre-owned, Cookies, Pressclub, Legal, Complaints, Find a dealer, EU tyre labels, Battery Regulation, FAQs, Contact, Privacy, Careers, Site Map, Whispers, Sustainability, Language, and social links. It is denser than the marketing surface but still uses wide letter-spacing and ample row spacing.

## Do's and Don'ts

### Do
- Use full-bleed video or photography as the primary layout material.
- Set headings and CTAs in Riviera Nights uppercase with wide letter-spacing.
- Keep primary CTAs transparent, rectangular, and stroked; pair them with circular stroked arrow icons where appropriate.
- Use `{colors.primary-deep}`, `{colors.primary-void}`, and `{colors.primary-ink}` for overlays and ceremony.
- Use `{colors.primary}` (#6d30a7) sparingly as a dash, indicator, or high-value brand accent.
- Keep forms and utility flows in full-screen overlays so they feel like part of the Rolls-Royce world.
- Let one editorial message own each frame: "Project Nightingale", "Coachbuild Collection", or "The world of bespoke".

### Don't
- Don't use rounded cards, pill CTAs, or soft SaaS-style surfaces for core marketing.
- Don't fill every primary button purple. Purple is an accent, not a bulk action fill.
- Don't introduce decorative gradients, shadows, or glass panels over the photography.
- Don't bold display type. Use 300/400 weights, scale, and letter-spacing.
- Don't crowd a hero with feature lists, specs, or multiple CTAs.
- Don't use catalog-style car renders when dramatic photography or video is available.
- Don't make the footer or forms playful; utility content remains formal and restrained.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 768px | 9-column grid, 16px margins, hero type drops to 28-34px, split image/text modules stack, menu becomes a vertical full-screen list |
| Tablet | 768-1023px | 12-column grid, image/text modules retain generous gutters, model tiles become 2-up where space allows |
| Desktop | 1024-1439px | Full overlay navigation, split editorial grids, model/showroom tiles 3-up or carousel |
| Wide | >= 1440px | 96px module grid with 16px gutters, content spans tighten around 1328px, photography remains full-bleed |

### Touch Targets
- CTA rectangles should be at least 48px high.
- Circular icon buttons should be 48 x 48px.
- Form inputs should be 48px high with generous vertical rhythm.
- Menu rows should have at least 44px effective tap height.

### Collapsing Strategy
- Hero media remains full-bleed at every breakpoint; crop shifts rather than boxing the image.
- Overlay menus retain the monogram/top action bar, then stack categories vertically.
- Journey cards move from horizontal grid to single-column.
- Footer link groups collapse into a vertical list or accordion-style sections.

### Image Behavior
- Use `object-fit: cover` for hero and tile media.
- Allow mobile crops to become portrait; keep subject centered or slightly offset for text placement.
- Hover scale is desktop-only; mobile uses static imagery and clear tap targets.

## Iteration Guide

1. Start with the media frame. If the image/video is not strong, the component will not feel Rolls-Royce.
2. Use `{token.refs}` for all color and typography choices.
3. Default new components to `{rounded.none}` and no shadow.
4. Use `{typography.eyebrow}` + `{typography.display-lg}` + one CTA as the default editorial stack.
5. Keep the purple accent rare. If more than one purple element appears in a small region, remove one.
6. For utility flows, prefer a full-screen `{component.form-overlay}` over inline page forms.
7. When in doubt, reduce copy and increase photographic breathing room.

## Known Gaps

- The homepage relies heavily on Brightcove video and lazy-loaded imagery; static extraction captures page text and many image URLs but not every rendered video frame.
- Computed styles from Lightpanda were limited for some late-loaded elements, so typography values are taken primarily from the production CSS.
- The live page analyzed was the `en_GB` homepage; model detail pages and configurator flows may introduce additional controls not represented here.
- The exact Rolls-Royce monogram SVG geometry is not documented as a token; treat it as a brand asset, not a reconstructable UI shape.
- Animation easing curves and durations beyond common `.4s` image opacity/transform transitions were not fully extracted.
