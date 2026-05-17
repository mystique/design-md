---
version: alpha
name: Bitwig
description: "A music-production interface language built from DAW screenshots, modular routing diagrams, and festival-poster color. Bitwig pairs Montserrat geometry with cream editorial panels, deep purple content bands, turquoise outlines (#00d0b9), neon green gradients, and sudden orange hover states. The brand should feel like pro audio software made visible: technical, modular, colorful, and performance-ready, with curved section masks and real product UI imagery carrying most of the visual drama."

colors:
  primary: "#00d0b9"
  primary-dark: "#07b78c"
  primary-bright: "#17b5fe"
  accent-orange: "#ff5a00"
  accent-purple: "#62089e"
  accent-deep-purple: "#2a094d"
  accent-violet: "#520b86"
  canvas: "#ffffff"
  canvas-warm: "#f7e1ba"
  canvas-cream: "#f4f3ec"
  ink: "#000000"
  body: "#212529"
  body-muted: "#666666"
  body-soft: "#00000066"
  on-dark: "#ffffff"
  on-muted-dark: "#ececec"
  surface-dark-purple: "#1f0234"
  surface-news-purple: "#39065e"
  surface-violet: "#520b86"
  surface-connect: "#343434"
  surface-connect-gray: "#818884"
  surface-rose-dark: "#4f1f2b"
  hairline: "#dddddd"
  focus-ring: "#00d0b9"
  overlay-warm: "#f7e1ba44"

typography:
  hero-display:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 64px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: 0
  display-lg:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.12
    letterSpacing: 0
  display-md:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 36px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0
  headline:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 1.28
    letterSpacing: 0
  lead:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 22px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0
  body-lg:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-strong:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.45
    letterSpacing: 0
  card-title:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 20px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 0
  quote:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 32px
    fontWeight: 300
    lineHeight: 1.5
    letterSpacing: 0
    fontStyle: italic
  nav-link:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: 0
  button:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0
  caption:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0
  label:
    fontFamily: "Montserrat, system-ui, -apple-system, sans-serif"
    fontSize: 13px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 8px
  lg: 14px
  xl: 24px
  curve-section: 33vw
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
  section: 80px
  section-lg: 112px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    padding: 12px 22px
  button-light:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    padding: 12px 22px
  button-light-hover:
    backgroundColor: "{colors.accent-orange}"
    textColor: "{colors.on-muted-dark}"
    rounded: "{rounded.sm}"
  button-outline:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    padding: 11px 21px
  button-video:
    backgroundColor: "rgba(255, 255, 255, 0.18)"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    size: 140px
  global-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 63px
  search-input:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: 8px 12px
  intro-hero:
    backgroundColor: "{colors.accent-purple}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    rounded: "{rounded.none}"
    padding: 96px 0
  curved-photo-panel:
    backgroundColor: "{colors.primary-dark}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.curve-section} 0 {rounded.curve-section} 0"
    padding: 0
  feature-panel-warm:
    backgroundColor: "{colors.canvas-warm}"
    textColor: "{colors.ink}"
    typography: "{typography.body-lg}"
    rounded: "0 {rounded.curve-section} {rounded.curve-section} 0"
    padding: 80px 0
  screenshot-zoom-box:
    backgroundColor: "{colors.canvas-warm}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: 0
  article-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: 0
  article-tag:
    backgroundColor: transparent
    textColor: "{colors.primary-dark}"
    typography: "{typography.label}"
  artist-band:
    backgroundColor: "{colors.surface-dark-purple}"
    textColor: "{colors.on-dark}"
    rounded: "0 {rounded.curve-section} 0 0"
    padding: 80px 0
  news-band:
    backgroundColor: "{colors.surface-news-purple}"
    textColor: "{colors.on-dark}"
    padding: 80px 0
  in-focus-band:
    backgroundColor: "{colors.surface-violet}"
    textColor: "{colors.on-dark}"
    padding: 80px 0
  trial-band:
    backgroundColor: "{colors.canvas-cream}"
    textColor: "{colors.ink}"
    typography: "{typography.lead}"
    padding: 72px 0
  connect-band:
    backgroundColor: "{colors.surface-connect}"
    textColor: "{colors.on-muted-dark}"
    typography: "{typography.body-lg}"
    padding: 96px 0
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    padding: 48px 0
---

## Overview

Bitwig's current web presence is a **music-production product page crossed with a modular synth poster**. It is not minimal in the Apple sense and not austere like a developer tool. The page sells professional DAW software through real interface screenshots, zoomed UI crops, hardware photography, tutorial cards, musician imagery, and saturated color fields that feel electronic rather than decorative.

The visual system is built around three tensions: clean white navigation and article cards; deep purple and violet editorial bands; and warm cream product surfaces where the Bitwig Studio UI is magnified with turquoise technical outlines. The strongest brand gesture is the curved mask: large panels use `33vw` corner geometry (`33vw 0 33vw 0`, `0 33vw 33vw 0`, `0 33vw 0 0`) so the page feels like signal flow, not stacked rectangles.

**Key Characteristics:**
- Montserrat everywhere: geometric, friendly, and technical enough for music software.
- Bright turquoise (`{colors.primary}` / #00d0b9) as the core technical accent: outlines, search icons, focus, and highlight boxes.
- Orange (`{colors.accent-orange}` / #ff5a00) as a sharp hover/action surprise, especially on light buttons in colorful hero sections.
- Purple-to-green gradient hero backgrounds anchored by real DAW imagery.
- Large real screenshots of Bitwig Studio, with crop-box zooms and rectangular cyan highlights.
- Curved section masks at enormous radii; cards and controls stay mostly square.
- Mixed surface rhythm: white nav -> saturated intro gradient -> curved photo -> cream feature analysis -> white awards/discover -> dark purple editorial -> cream trial -> gray hardware section -> white footer.

## Colors

> **Source pages analyzed:** Bitwig homepage, including the Bitwig Studio 6 intro, feature zoom sections, artist/news/story cards, trial CTA, Bitwig Connect hardware band, global navigation, and footer.

### Brand & Accent

- **Bitwig Turquoise** (`{colors.primary}` - #00d0b9): The precise technical accent. Use for screenshot crop borders, highlight rectangles, focus states, small icons, and primary action emphasis. It reads as "modulation / signal / selected parameter."
- **Deep Green Turquoise** (`{colors.primary-dark}` - #07b78c): The gradient endpoint in the hero and photo-band surfaces. Use as a large brand color field, not just a small control color.
- **Electric Blue** (`{colors.primary-bright}` - #17b5fe): Appears inside the hero's radial gradient atmosphere. Use sparingly as glow inside saturated gradient compositions.
- **Bitwig Orange** (`{colors.accent-orange}` - #ff5a00): The active hover and attention color. It should arrive suddenly on hover or on high-energy campaign labels, not replace turquoise as the main brand color.
- **Brand Purple** (`{colors.accent-purple}` - #62089e): The left side of the main gradient field and a major identity surface.
- **Deep Purple Wedge** (`{colors.accent-deep-purple}` - #2a094d): Used as angular hero corners and dark gradient depth.
- **Violet Band** (`{colors.accent-violet}` - #520b86): Used for "In Focus" and deeper content bands.

### Surface

- **White Canvas** (`{colors.canvas}` - #ffffff): Navigation, article cards, footer, award/discover sections.
- **Warm Cream** (`{colors.canvas-warm}` - #f7e1ba): The Bitwig Studio 6 feature-analysis surface. It gives the DAW screenshots a warm studio-paper context.
- **Trial Cream** (`{colors.canvas-cream}` - #f4f3ec): Softer off-white used for the trial / download CTA band.
- **Dark Purple** (`{colors.surface-dark-purple}` - #1f0234): Artist/editorial hero surface.
- **News Purple** (`{colors.surface-news-purple}` - #39065e): News/story region.
- **Connect Gray** (`{colors.surface-connect}` - #343434) and **Connect Hardware Gray** (`{colors.surface-connect-gray}` - #818884): Hardware marketing surfaces for Bitwig Connect.

### Text

- **Black Ink** (`{colors.ink}` - #000000): Headlines, nav links, strong card titles, footer text.
- **Body** (`{colors.body}` - #212529): Bootstrap-derived default body tone.
- **Muted Body** (`{colors.body-muted}` - #666666): Secondary descriptions and metadata.
- **Soft Black** (`{colors.body-soft}` - #00000066): Award years and low-priority labels.
- **On Dark** (`{colors.on-dark}` - #ffffff): Text over saturated purple/green backgrounds.
- **Muted On Dark** (`{colors.on-muted-dark}` - #ececec): Hardware section copy and light button hover text.

### Gradients

Bitwig gradients are not soft SaaS atmosphere. They are **synthetic, directional, and geometric**:

```css
background:
  linear-gradient(315deg, transparent 0% 77%, #2a094d),
  linear-gradient(135deg, transparent 0% 77%, #2a094d),
  radial-gradient(closest-side at 62% 82%, #17b5fecc 5% 8%, transparent 81% 100%),
  linear-gradient(90deg, #62089e, #07b78c);
```

Use gradients as real section backgrounds. Avoid vague purple-blue blobs; Bitwig's gradient has angular deep-purple corners and a green directional sweep.

## Typography

### Font Family

Bitwig preloads **Montserrat regular** and **Montserrat 700**. The site relies on those two weights for almost everything, with rare light/italic moments in quote sections.

```css
--font-sans: "Montserrat", system-ui, -apple-system, BlinkMacSystemFont,
             "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
```

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---:|---:|---:|---:|---|
| `{typography.hero-display}` | 64px | 700 | 1.05 | 0 | Product hero statements and campaign titles |
| `{typography.display-lg}` | 48px | 700 | 1.12 | 0 | Major section headings |
| `{typography.display-md}` | 36px | 700 | 1.20 | 0 | Feature blocks and CTA titles |
| `{typography.headline}` | 28px | 700 | 1.28 | 0 | Card group headings and product subheads |
| `{typography.lead}` | 22px | 400 | 1.45 | 0 | Centered intro paragraphs and trial copy |
| `{typography.body-lg}` | 18px | 400 | 1.55 | 0 | Feature descriptions |
| `{typography.body}` | 16px | 400 | 1.50 | 0 | Default paragraph and article card text |
| `{typography.body-strong}` | 16px | 700 | 1.45 | 0 | Strong inline emphasis |
| `{typography.card-title}` | 20px | 700 | 1.30 | 0 | Article/tutorial card titles |
| `{typography.quote}` | 32px | 300 | 1.50 | 0 | Award/review pull quotes |
| `{typography.nav-link}` | 14px | 700 | 1.00 | 0 | Top navigation labels |
| `{typography.button}` | 16px | 700 | 1.20 | 0 | Button labels |
| `{typography.caption}` | 14px | 400 | 1.45 | 0 | Metadata and footer copy |
| `{typography.label}` | 13px | 700 | 1.20 | 0 | Tags and compact labels |

### Principles

- **No negative tracking.** Montserrat is allowed to keep its geometric spacing. Do not tighten it into a luxury tech voice.
- **Weight contrast is binary.** Most type is either 400 or 700. This keeps the page clear and instructional.
- **Large type stays readable.** Bitwig headlines are bold but not compressed; line-height remains practical.
- **Quotes are the exception.** The award/review quote language can use 300 italic at larger sizes to feel human against the technical product surfaces.
- **Text is secondary to product imagery.** Headlines announce the idea; screenshots prove it.

## Layout

### Spacing System

- **Base unit:** 8px, with Bootstrap-like 15px container gutters visible in the implementation.
- **Section padding:** 72-112px depending on campaign density.
- **Card gutters:** 24px between article/tutorial cards.
- **Feature panels:** generous vertical rhythm with screenshots and zoom boxes treated as primary content, not decorations.

### Grid & Container

- **Max content width:** approximately 1140px, matching Bootstrap's `.container-xl` behavior.
- **Hero media:** centered, wide DAW screenshots with a large soft shadow-image layer behind them.
- **Feature analysis rows:** alternating screenshot backgrounds, crop boxes, and text blocks. The page often uses left/right rhythm rather than uniform card grids.
- **Article lists:** 3-column desktop card grids, 2-column tablet, 1-column phone.
- **Footer:** centered horizontal link rows with separators, not a tall dense enterprise directory.

### Curved Section Geometry

Bitwig's most distinctive layout move is the oversized curved mask:

- `33vw 0 33vw 0` for photo containers.
- `0 33vw 33vw 0` for the warm feature panel.
- `0 33vw 0 0` for the artist band.

Use these on full-width bands and large media containers. Do not apply giant radii to small cards or buttons.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow, clean surface color | Nav, footer, cream feature panels |
| Hairline | 1px neutral border or turquoise technical border | Inputs, screenshot highlights, crop boxes |
| Backdrop blur | 3-6px blur on translucent play button | Video play control over hero media |
| Product/image depth | Layered DAW screenshot plus shadow image | Hero interface presentation |

Bitwig does not rely on card shadows. Depth comes from real product screenshots, masked photos, gradient fields, and the zoom/crop mechanism. The crop box (`360px x 360px`, `3px #00d0b9 solid`) is more important than any conventional elevation token.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---:|---|
| `{rounded.none}` | 0px | Screenshot boxes, article cards, section edges |
| `{rounded.xs}` | 2px | Fine UI controls |
| `{rounded.sm}` | 4px | Buttons and form controls |
| `{rounded.md}` | 8px | Small utility panels |
| `{rounded.lg}` | 14px | Rare media cards |
| `{rounded.xl}` | 24px | Large contained promotional surfaces if needed |
| `{rounded.curve-section}` | 33vw | Full-width curved masks and photo panels |
| `{rounded.pill}` | 9999px | Video play button and rare capsule controls |

### Image Geometry

- DAW screenshots are rectangular and technical. Keep their edges crisp.
- Photo sections may be heavily masked with the large `33vw` curve.
- Article card images are standard responsive rectangles, usually 680x450-ish crops.
- Hardware images for Bitwig Connect sit on gray/photographic backgrounds, not on abstract cards.

## Components

### Navigation

**`global-nav`** - Fixed top white navigation, approximately 63px tall. Left: Bitwig logo at about 90px wide. Center: product links ("Bitwig Studio", "Bitwig Connect", "Discover", "Learn", "Support", "Try", "Buy"). Right: search input, account/cart icons. Nav text uses `{typography.nav-link}` and black ink. The search icon is turquoise.

### Buttons

**`button-primary`** - Turquoise action button. Background `{colors.primary}`, black text, Montserrat 700, 4px radius. Use for product actions when the surrounding surface is light or neutral.

**`button-light`** - White button used on saturated hero fields. Black text, 4px radius. On hover, it flips to `{colors.accent-orange}` with `{colors.on-muted-dark}` text. This white-to-orange hover is a core Bitwig interaction cue.

**`button-outline`** - Transparent button with turquoise text and border. Use for secondary actions near screenshots or cream panels.

**`button-video`** - Large translucent pill/capsule over video or hero media. Width around 120-140px, `backdrop-filter: blur(3px)` at rest, `blur(6px)` and `transform: scale(0.95)` on hover.

### Product & Feature Panels

**`intro-hero`** - Saturated purple-to-green gradient section with angular deep-purple corners and an electric-blue radial glow. Centered white text and a large Bitwig Studio interface image. CTAs use `{component.button-light}` so they pop against the gradient.

**`curved-photo-panel`** - A full-width photo/media panel with a diagonal turquoise/green surface and `33vw` alternating corner radius. Use for musician/product imagery, not for generic decoration.

**`feature-panel-warm`** - Cream Bitwig Studio 6 analysis section. Background `{colors.canvas-warm}` with a radial product graphic or screenshot layer. Large right-side curve (`0 33vw 33vw 0`). Use black text, turquoise borders, and real DAW screenshots.

**`screenshot-zoom-box`** - Technical zoom component. A 360px square crop box with `3px solid {colors.primary}`. Paired with a smaller turquoise highlight rectangle on the full screenshot. This is the signature "show the DAW detail" component.

### Cards & Editorial

**`article-card`** - White rectangular card with top image, tag, bold title, and body description. No decorative shadow. Used for Explore More, Learn, Discover, and story grids.

**`article-tag`** - Compact metadata label in turquoise/green, Montserrat 700, small size. Keeps cards scannable without turning them into badges.

**`artist-band`** - Deep purple band with an enormous top-right curve. Supports artist photography, interview links, and community content.

**`news-band`** and **`in-focus-band`** - Dark purple/violet editorial sections. Use white text and white article cards or media modules with clear contrast.

**`trial-band`** - Warm off-white CTA band. Centered copy and straightforward buttons. This is the calmer conversion surface after the high-energy editorial sections.

**`connect-band`** - Gray hardware/product section for Bitwig Connect. Uses real hardware photography as a background, gray overlays, and `{colors.on-muted-dark}` text. It should feel physical and utilitarian, not neon.

### Forms & Inputs

**`search-input`** - Transparent input in the nav with black text and turquoise search icon. Minimal border language. On focus, use a turquoise ring or underline.

Login popovers and account forms use conventional white surfaces, black labels, and outlined buttons. Keep forms practical; this is not where the brand gets expressive.

### Footer

**`footer`** - White footer with newsletter CTA, social icons, centered horizontal navigation, legal links, language selector, and copyright. The footer returns the site to a clean utility mode after the saturated page body.

## Do's and Don'ts

### Do

- Use Montserrat regular and 700 as the main type system.
- Use real Bitwig Studio UI screenshots, hardware photos, musician photos, and tutorial imagery.
- Use `{colors.primary}` (#00d0b9) for technical emphasis: highlight boxes, focus states, icons, and outlines.
- Build large section masks with `{rounded.curve-section}` (33vw) on full-width panels.
- Use saturated purple/green gradients as actual hero backgrounds, including angular deep-purple corners.
- Keep article cards rectangular and content-driven.
- Use orange hover states on light hero buttons where the original site does.
- Let screenshots and crop boxes explain product capability.

### Don't

- Do not turn Bitwig into generic dark-mode music software; the site alternates white, cream, purple, and gray surfaces.
- Do not use pill buttons everywhere. Pills are for video/play controls, not the primary CTA grammar.
- Do not apply huge `33vw` radii to small cards, buttons, or inputs.
- Do not use delicate serif typography, negative tracking, or luxury editorial spacing.
- Do not replace DAW screenshots with abstract waveform art.
- Do not overuse shadows. Technical borders and image layers carry depth.
- Do not make turquoise the only color; Bitwig needs purple, green, cream, gray, and orange in the system.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---:|---|
| Phone | < 576px | Nav collapses to hamburger; hero type drops to ~34px; cards become 1-column; large crop boxes scale down |
| Tablet | 576-991px | Content container uses 540-960px widths; article grids become 2-column; hero media stacks below text |
| Desktop | 992-1199px | Full nav appears; 3-column story grids; feature rows alternate screenshot and text |
| Wide desktop | >= 1200px | Container maxes near 1140px; hero and background media gain more lateral breathing room |

### Mobile Rules

- Preserve the curved section identity, but reduce vertical padding before reducing image size.
- Keep DAW screenshots legible; if the full screenshot becomes too small, prefer a cropped product detail.
- Convert 3-up article rows to single column quickly rather than squeezing text.
- Keep the fixed nav compact and clear; do not hide primary "Try" and "Buy" paths too deeply.
- Avoid viewport-width font scaling. Use discrete type steps.

