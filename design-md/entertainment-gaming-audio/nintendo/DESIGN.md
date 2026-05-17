---
version: alpha
name: Nintendo
description: A modular entertainment portal built from bright white surfaces, Nintendo Red (#e60012), dotted gray dividers, and image-led game cards. The system feels playful without becoming noisy: the red accent is used as a precise interaction rail, section titles are underlined with a red rule, cards stay flat and photographic, and horizontal scrollers create the sense of browsing a game shelf.

colors:
  primary: "#e60012"
  primary-deep: "#b40000"
  primary-alt-3ds: "#ce181e"
  accent-orange: "#f57900"
  accent-saturday: "#30a6d9"
  ink: "#3c3c3c"
  body: "#3c3c3c"
  body-muted: "#8c8c8c"
  body-subtle: "#b4b4b4"
  canvas: "#ffffff"
  surface-soft: "#f2f2f2"
  surface-nav: "#ededed"
  surface-overlay: "rgba(255,255,255,0.7)"
  surface-overlay-mobile: "rgba(255,255,255,0.95)"
  hairline: "#e6e6e6"
  hairline-mid: "#d9d9d9"
  divider-dotted: "#b4b4b4"
  on-primary: "#ffffff"

typography:
  body:
    fontFamily: "YakuHanJPs, Roboto, Hiragino Kaku Gothic ProN, nc3Jp, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 2
    letterSpacing: 0
  section-title:
    fontFamily: "YakuHanJPs, Roboto, Hiragino Kaku Gothic ProN, nc3Jp, Arial, sans-serif"
    fontSize: 21px
    fontWeight: 700
    lineHeight: 32px
    letterSpacing: 0
  section-title-mobile:
    fontFamily: "YakuHanJPs, Roboto, Hiragino Kaku Gothic ProN, nc3Jp, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 32px
    letterSpacing: 0
  section-label:
    fontFamily: "YakuHanJPs, Roboto, Hiragino Kaku Gothic ProN, nc3Jp, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0
  card-title:
    fontFamily: "YakuHanJPs, Roboto, Hiragino Kaku Gothic ProN, nc3Jp, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.43
    letterSpacing: 0
  card-title-mobile:
    fontFamily: "YakuHanJPs, Roboto, Hiragino Kaku Gothic ProN, nc3Jp, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.58
    letterSpacing: 0
  small:
    fontFamily: "YakuHanJPs, Roboto, Hiragino Kaku Gothic ProN, nc3Jp, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  small-strong:
    fontFamily: "YakuHanJPs, Roboto, Hiragino Kaku Gothic ProN, nc3Jp, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: 0
  micro:
    fontFamily: "YakuHanJPs, Roboto, Hiragino Kaku Gothic ProN, nc3Jp, Arial, sans-serif"
    fontSize: 10px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0
  number-display:
    fontFamily: "Roboto, YakuHanJPs, Arial, sans-serif"
    fontSize: 30px
    fontWeight: 900
    lineHeight: 0.9
    letterSpacing: 0
  number-date:
    fontFamily: "Roboto, YakuHanJPs, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 20px
    letterSpacing: 0
  nav-thumb-label:
    fontFamily: "YakuHanJPs, Roboto, Hiragino Kaku Gothic ProN, nc3Jp, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: 0

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 6px
  lg: 8px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 14px
  md: 20px
  lg: 28px
  xl: 40px
  xxl: 56px
  section: 72px
  section-mobile: 50px

components:
  global-header:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.small-strong}"
    height: 74px
  hero-carousel:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    aspectRatioDesktop: "1440 / 520"
    aspectRatioMobile: "1 / 1"
  hero-nav-strip:
    backgroundColor: "{colors.surface-nav}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-thumb-label}"
    heightDesktop: 74px
    heightMobile: 63px
  hero-nav-item-active:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.primary}"
    borderTop: "4px solid {colors.primary}"
  section-header:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.section-title}"
    borderBottom: "2px solid {colors.hairline}"
    activeRule: "2px solid {colors.primary}"
  topic-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.card-title}"
    rounded: "{rounded.none}"
    borderBottom: "2px solid {colors.hairline}"
  software-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.card-title}"
    rounded: "{rounded.none}"
    borderBottom: "2px solid {colors.hairline}"
  hardware-tab:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.card-title}"
    rounded: "{rounded.none}"
    border: "1px solid {colors.hairline}"
  button-switch:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.small-strong}"
    rounded: "{rounded.xs}"
    padding: 14px 24px
  button-outline-gray:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body-muted}"
    typography: "{typography.small-strong}"
    rounded: "{rounded.xs}"
    border: "2px solid {colors.hairline}"
    padding: 12px 20px
  arrow-round-red:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.full}"
    size: 18px
  scroller-controller:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body-muted}"
    rounded: "{rounded.xs}"
    border: "2px solid {colors.hairline}"
    size: 42px
  scroller-knob:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.small-strong}"
    height: 22px
  news-row:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.small}"
    borderTop: "1px dotted {colors.divider-dotted}"
  badge-muted:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.body-muted}"
    typography: "{typography.micro}"
    rounded: "{rounded.none}"
    padding: 5px
  announcement:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body-muted}"
    typography: "{typography.small}"
    borderTop: "1px solid {colors.hairline}"
    padding: 22px 0
  footer:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.body-muted}"
    typography: "{typography.small}"
    borderTop: "1px solid {colors.hairline}"
---

## Overview

Nintendo Japan's homepage is a **newsstand for games**: a red brand shell at the top, a large media carousel, then a sequence of flat modules for topics, pickup items, software releases, updates, and customer notices. The page is not minimal. It is dense, useful, and highly structured, but it stays readable because every module uses the same grammar: white canvas, gray rules, bold Japanese labels, red arrows, and thumbnail-led cards.

The system's personality comes from rhythm rather than decoration. Section headers have a red underline sitting on a gray rule. Cards avoid shadows and rounded corners. Separators are often dotted gray lines, giving the interface a printed schedule/catalog feeling. Nintendo Red (`{colors.primary}`) is the unmistakable brand signal, but it is used surgically: active states, arrows, button fills, section rules, loading spinners, Sunday markers, and link hover states.

**Key Characteristics:**
- Nintendo Red (`{colors.primary}` — #e60012) is the single dominant interaction and brand color.
- White canvas with soft gray infrastructure: `{colors.hairline}` borders, `{colors.divider-dotted}` dotted dividers, `{colors.surface-soft}` UI panels.
- Image-first cards: thumbnails carry the entertainment energy; UI chrome remains flat.
- Section labels pair Japanese titles with small uppercase English subtitles (`トピックス` + `TOPICS`).
- Horizontal browsing is central: hero carousel, pickup rail on mobile, and software release scroller.
- Typography uses Japanese-first YakuHanJPs / Hiragino / nc3Jp with Roboto reserved for dates and numbers.
- No decorative gradients; movement, thumbnails, and red state changes provide the liveliness.

## Colors

> **Source page analyzed:** `https://www.nintendo.com/jp/` homepage and its shared/reset/local CSS assets.

### Brand & Accent
- **Nintendo Red** (`{colors.primary}` — #e60012): The primary brand color. Used for active carousel state, button fills, red section title rule, arrow icons, loader stroke, hover text, selected tabs, software theme markers, and Sunday/date accents.
- **Deep Red** (`{colors.primary-deep}` — #b40000): A pressed/active underline shadow used beneath selected red tab buttons.
- **3DS Red** (`{colors.primary-alt-3ds}` — #ce181e): A legacy hardware theme color for 3DS-labeled software surfaces.
- **Schedule Orange** (`{colors.accent-orange}` — #f57900): Used in the release schedule scroller when the active section is not the current-week red state.
- **Saturday Blue** (`{colors.accent-saturday}` — #30a6d9): A functional calendar accent for Saturday day markers.

### Surface
- **Canvas** (`{colors.canvas}` — #ffffff): The default page background and card surface.
- **Soft Panel** (`{colors.surface-soft}` — #f2f2f2): Badges, dropdown surfaces, tab resting states, search overlays, and utility panels.
- **Carousel Rail Gray** (`{colors.surface-nav}` — #ededed): The hero thumbnail navigation strip and inactive carousel tab ground.
- **Desktop Search Overlay** (`{colors.surface-overlay}` — rgba(255,255,255,0.7)): The dimmed white overlay behind active search suggestions on desktop.
- **Mobile Search Overlay** (`{colors.surface-overlay-mobile}` — rgba(255,255,255,0.95)): Stronger mobile overlay to preserve legibility.

### Text
- **Ink** (`{colors.ink}` — #3c3c3c): Default body and heading color. Softer than black and consistent across homepage cards and lists.
- **Body Muted** (`{colors.body-muted}` — #8c8c8c): Dates, announcement labels, badges, scroller dates, and secondary metadata.
- **Body Subtle** (`{colors.body-subtle}` — #b4b4b4): English subtitles and dotted divider material.
- **On Primary** (`{colors.on-primary}` — #ffffff): Text and icons on red buttons, active tabs, and red scroller controls.

### Hairlines & Dividers
- **Hairline** (`{colors.hairline}` — #e6e6e6): The core border color. Used for section rules, card bottoms, announcement top border, controller borders, table rules, and utility dividers.
- **Hairline Mid** (`{colors.hairline-mid}` — #d9d9d9): Slightly stronger mobile tag/list border.
- **Dotted Divider** (`{colors.divider-dotted}` — #b4b4b4): Repeating 1px dot/dash separators used between news rows, carousel cells, glance nav items, and local button separators.

### Brand Gradient
**No gradient token.** Nintendo's visual energy comes from game artwork and red state changes, not decorative CSS gradients. Repeating linear-gradients are used only to draw dotted/dashed dividers; treat them as borders, not atmospheric backgrounds.

## Typography

### Font Family
- **Japanese UI / body:** `YakuHanJPs, Roboto, Hiragino Kaku Gothic ProN, nc3Jp, Arial, sans-serif`. `YakuHanJPs` controls Japanese punctuation spacing; `nc3Jp` is Nintendo's bundled Noto Sans JP face.
- **Numbers / dates:** `Roboto, sans-serif` appears on date stamps, release schedule numerals, and numeric UI.
- **Weights:** Normal and bold are the main states. Roboto reaches 900 for oversized schedule date markers.

### Hierarchy

| Token | Size | Weight | Line Height | Use |
|---|---|---|---|---|
| `{typography.body}` | 16px | 400 | 2.0 | Default page copy |
| `{typography.section-title}` | 21px | 700 | 32px | Japanese section titles |
| `{typography.section-title-mobile}` | 16px | 700 | 32px | Mobile section titles |
| `{typography.section-label}` | 12px | 700 | 1.0 | English section subtitles (`TOPICS`, `PICKUP`) |
| `{typography.card-title}` | 14px | 700 | 1.43 | Topic/software card titles |
| `{typography.card-title-mobile}` | 12px | 700 | 1.58 | Mobile card titles |
| `{typography.small}` | 12px | 400 | 1.6 | News row copy, announcement links |
| `{typography.small-strong}` | 12px | 700 | 1.4 | Buttons, small labels, carousel nav text |
| `{typography.micro}` | 10px | 700 | 1.0 | Badges and compact metadata |
| `{typography.number-display}` | 30px | 900 | 0.9 | Release schedule date markers |
| `{typography.number-date}` | 14px | 700 | 20px | What's New date column |
| `{typography.nav-thumb-label}` | 12px | 700 | 1.4 | Hero thumbnail navigation labels |

### Principles

- **Bold labels do the hierarchy work.** Nintendo uses strong weight instead of large type. Section titles are only 21px on desktop.
- **Japanese title + English subtitle.** The Japanese label is primary; the English subtitle is small, gray, and secondary.
- **Long body leading.** The base body line-height is `2`, which gives dense Japanese copy enough breathing room.
- **Roboto is functional, not decorative.** Use it for dates, counters, prices, and release schedule markers.
- **No negative tracking.** The system avoids Apple-style tight display typography. Keep letter-spacing at `0` unless a specific logo asset dictates otherwise.

## Layout

### Spacing System
- **Base rhythm:** 4px and 8px increments, with many Nintendo-specific constants: 14, 20, 22, 24, 28, 40, 56, 72.
- **Section top padding:** `{spacing.section}` (72px) on desktop/tablet, `{spacing.section-mobile}` (50px) on phone.
- **Headline-to-grid gap:** 49px desktop, 41px tablet, 26px phone for the main content sections.
- **Grid gutters:** 28px desktop for 3-column pickup, 24px tablet, and horizontal scrolling cards on phone.
- **Scroller card size:** 275px desktop software cards, 205px phone software cards.

### Grid & Container
- **Inner content width:** `nc3-l-innerWidth` centers page modules; software scroller clips around ~1120px on desktop.
- **Hero carousel:** full-width media area with a desktop aspect ratio of roughly 1440:520 (`36.11%` padding-bottom). Phone changes to a square 1:1 hero.
- **Topics grid:** 4 columns desktop, 3 tablet, 2 phone pattern via shared `nc3-l-grid--4-3-2`.
- **Pickup grid:** 3 columns desktop/tablet; mobile becomes a horizontal rail with `64vw` cards.
- **Software scroller:** horizontal release shelf with sticky date headers and controller bar on desktop.

### Whitespace Philosophy
The page uses generous vertical gaps between modules but compact interiors inside each module. Nintendo leaves air before every section title, then switches to dense browsing once the card grid begins. This creates a reliable rhythm: breathe, browse, act.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow | Page canvas, cards, buttons, nav strips |
| Rule | 1–2px solid gray border | Section headers, card bottoms, controllers, announcement |
| Dotted rule | Repeating 1px gray dash pattern | News rows, carousel dividers, small nav separators |
| Image zoom | Thumbnail background-size 100% → 104.5% | Hover feedback on cards |
| White veil | `rgba(255,255,255,0.3)` overlay | Desktop card hover highlight |

**Shadow philosophy.** Do not add drop shadows to Nintendo homepage components. Depth is communicated through borders, dotted dividers, thumbnail scale, and red state changes. Cards should feel like printed catalog tiles rather than floating panels.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.none}` | 0px | Cards, hero, headers, rails, images |
| `{rounded.xs}` | 2px | Buttons, pagers, tab clusters |
| `{rounded.sm}` | 4px | Small indicator details and compact UI |
| `{rounded.md}` | 6px | Rare utility controls |
| `{rounded.lg}` | 8px | Reserved for non-homepage promotional assets if needed |
| `{rounded.full}` | 9999px | Circular arrow icons and day markers |

### Image Geometry
- **Hero imagery:** desktop wide crop; mobile square crop. Always full-bleed inside the carousel frame.
- **Topic cards:** thumbnail first, text below, flat bottom rule. Image corners remain square.
- **Pickup cards:** wide banner-like thumbnails, roughly 38% aspect-ratio height (`padding-bottom: 38.028%`).
- **Software cards:** product thumbnail + hardware tag + title + company/CERO metadata; rigid card width in horizontal scroller.
- **Banner modules:** centered image banners with a thin `{colors.hairline}` border on desktop.

## Components

### Navigation & Hero

**`global-header`** — Nintendo's generated global shell. Red is the dominant brand bar color, with white logo/action text. Keep the header visually heavier than the section chrome below it.

**`hero-carousel`** — Full-width key visual switcher. Desktop aspect ratio is approximately 1440 × 520; mobile becomes square. Content is image/video-led with no card frame and no text overlay requirement. Loading state uses a 24px circular spinner with a 2px `{colors.primary}` stroke and transparent bottom segment.

**`hero-nav-strip`** — Five-item thumbnail rail below the hero. Desktop height 74px, mobile height 63px. Inactive cells sit on `{colors.surface-nav}` with white internal thumbnail boxes and dotted vertical separators. Active state exposes `{colors.primary}` through the timer/rule and text color.

### Section Headers

**`section-header`** — The homepage's most repeatable structure. A Japanese bold title floats left at 21px/700, the English subtitle sits beside it in 12px gray bold, and a full-width 2px gray rule runs underneath. The Japanese title segment owns a 2px red underline, turning section headings into a functional tab-like marker.

### Cards

**`topic-card`** — Flat article card. Thumbnail on top, bold 14px title below, date/metadata in muted gray, small red circular arrow at the lower right, and 2px `{colors.hairline}` bottom rule. Hover shifts title/arrow emphasis to red and may apply a light white overlay on the thumbnail.

**`software-card`** — Game release card used in the horizontal schedule scroller. Thumbnail, hardware label, title, CERO/company metadata, and red arrow. The content area ends with a 2px gray bottom rule. Hardware theme markers use red for Switch, `#ce181e` for 3DS, and `#0096c8` for Wii U surfaces where present.

**`hardware-tab`** — Large utility links for `Nintendo Switch 2`, `Nintendo Switch`, and smartphone apps. These are not rounded cards; they are bordered rectangular tabs with bold text and red arrow affordances.

### Buttons & Controls

**`button-switch`** — Primary list/action button. Red background, white text, small rounded 2px corners, bold 12px label, and leading red/white arrow icon depending on context. Used for "もっと見る" and article-list navigation.

**`button-outline-gray`** — Secondary navigation button. White background, gray text, 2px gray border, small 2px radius. On mobile, these often collapse into text-like cells and drop the border.

**`arrow-round-red`** — The core affordance glyph: a red circular arrow, generally 10–18px depending on context. It appears inside article cards, news rows, buttons, and "more" blocks.

**`scroller-controller`** — Desktop-only left/right controls for horizontal rails. 42 × 42px, 2px `{colors.hairline}` border, 2px radius, gray chevron. Hover/disabled states use `{colors.surface-soft}` and lighter gray glyphs.

**`scroller-knob`** — Red draggable schedule indicator. Includes small top marker and triangular pointer. Uses `{colors.primary}` for current-week sections and `{colors.accent-orange}` for alternate schedule sections.

### Lists & Notices

**`news-row`** — The `WHAT'S NEW` row. Desktop uses table-like columns: date (Roboto 14px/700), badge wrapper, then link text with red arrow on the right. Rows are separated by dotted gray top rules and a solid gray bottom rule on the list.

**`badge-muted`** — Compact label inside update rows. Gray text on `{colors.surface-soft}`, bold 10px, 5px padding, square corners. It should read like metadata, not a CTA.

**`announcement`** — Customer notice strip at the bottom of the homepage content. White background, top hairline, muted gray headline, optional left border between label and text on desktop. Links use small text with a red arrow icon.

**`footer`** — Generated global footer. Gray/white utility surface with dense links and low visual weight compared with the red header.

## Do's and Don'ts

### Do
- Use `{colors.primary}` (#e60012) for active states, arrows, loaders, selected tabs, primary buttons, and section-title rules.
- Keep cards flat: square image crops, no shadow, no floating card treatments.
- Use gray rules and dotted dividers as the main structural separators.
- Pair Japanese section names with small uppercase English subtitles.
- Use Roboto for dates and numeric schedule markers; use the Japanese UI stack for everything else.
- Preserve horizontal browsing patterns for game/software content.
- Use image thumbnails as the visual energy source; the UI frame should stay restrained.

### Don't
- Don't introduce decorative gradients; repeating gradients are only for dotted rule patterns.
- Don't add Apple-style pill CTAs or large rounded card corners. Nintendo's homepage grammar is rectangular.
- Don't use black as the default text color; use `{colors.ink}` (#3c3c3c).
- Don't replace red arrows with generic text links. The red circular arrow is a core navigation cue.
- Don't use shadows to create hierarchy. Use red state, border thickness, and image scale.
- Don't make section headings oversized. The homepage relies on compact bold headings, not hero typography.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Small phone | ≤ 374px | Hero nav collapses to icon-only 20% cells; active text hidden |
| Phone | ≤ 759.98px | Hero becomes square; section padding 50px; pickup becomes horizontal `64vw` rail; software cards 205px |
| Tablet | 760–979.98px | Section padding remains 72px; topics grid reduces; many scrollers become native horizontal scroll |
| Desktop | ≥ 980px | Full carousel rail; desktop scroller controllers; software clip max around 1120px |
| Wide desktop | ≥ 1200px | Carousel nav labels use 12px; content gutters stabilize |

The structural breakpoints that matter for agents: 980px, 760px, 375px.

### Touch Targets
- Carousel nav cells are large horizontal targets: 20% width on desktop, overlapping 46% panels on tablet/phone except very small phones.
- Scroller buttons are 42 × 42px, close to the modern 44px touch target.
- Circular day markers are 18 × 18px desktop and 15 × 15px phone, but they are informational rather than primary touch targets.

### Collapsing Strategy
- **Hero carousel:** wide media panel → square mobile panel; thumbnail text hides on inactive mobile cells.
- **Topics grid:** 4 → 3 → 2 column behavior through shared grid classes.
- **Pickup:** 3-column desktop/tablet → horizontal scroll rail on phone.
- **Software schedule:** controller-driven desktop rail → native horizontal scroll on touch/tablet; phone cards narrow to 205px.
- **Button nav:** bordered buttons on desktop → lighter divided text cells on mobile/tablet.

### Image Behavior
- Images are responsive through `data-pc`, `data-tab`, and `data-sp` attributes on Nintendo's image loader.
- Above-fold hero images switch art direction between desktop/tablet and phone.
- Card images use lazy loading where possible.
- Hover zoom on desktop should be subtle: background-size from 100% to about 104.5%, with a 130–150ms transition.

## Iteration Guide

1. Focus on one module at a time: `{component.hero-carousel}`, `{component.section-header}`, `{component.topic-card}`, or `{component.software-card}`.
2. Use `{token.refs}` everywhere; keep raw red values out of component descriptions unless documenting a source value.
3. Default to square corners. Only use `{rounded.xs}` for controls that are visibly button-like.
4. Never document hover as the only state. Default and active/selected states define the system; hover is secondary desktop polish.
5. Preserve the red-under-gray section header treatment. It is the homepage's strongest structural signature.
6. Use dotted dividers before adding borders when separating dense list items.
7. When in doubt about visual energy, add/choose better game artwork rather than adding UI decoration.

## Known Gaps

- The generated global header/footer are produced by Nintendo's `NC3.shell` scripts; this document describes their visual role but not every internal menu state.
- Search, account login, and suggestion overlays are present in shared CSS but not fully surfaced on the homepage's static HTML.
- Card content is populated dynamically by JavaScript and remote feeds; component specs describe the layout shell rather than a fixed content set.
- Some legacy hardware theme colors are present in shared CSS (`3DS`, `Wii U`) even when the homepage emphasizes Switch and Switch 2.
- Exact logo geometry is asset-based and should be treated as brand artwork, not recreated from text tokens.
