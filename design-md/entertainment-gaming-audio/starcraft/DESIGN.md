---
version: alpha
name: StarCraft
description: "A tactical sci-fi marketing system built like a remastered RTS command interface: black space canvas, giant illustrated battlefield backgrounds, Eurostile Extended uppercase headlines, Source Sans Pro body copy, neon green primary CTAs, cyan secondary controls, armored media frames, scan-line button textures, and hard 13px section dividers with heavy black shadow. The page should feel like a Battle.net product page viewed through a Terran console: cinematic, metallic, glowing, and mission-ready."

colors:
  primary: "#7aff7a"
  primary-border: "#00ff00"
  primary-glow: "#00cc00"
  primary-dark: "#003301"
  primary-deep: "#008603"
  accent-cyan: "#4be8f2"
  accent-cyan-border: "#1e86b0"
  accent-cyan-dark: "#1a465e"
  accent-blue-text: "#cce1ff"
  success-price: "#00ff94"
  canvas: "#000000"
  surface-dark: "#151515"
  surface-overlay: "rgba(0,0,0,0.6)"
  surface-panel: "rgba(0,0,0,0.5)"
  media-outline: "rgba(242,255,242,0.5)"
  media-outline-hover: "rgba(242,255,242,0.75)"
  ink: "#f2fff2"
  body: "#b8bbcc"
  body-muted: "rgba(184,187,204,0.72)"
  on-primary: "#0a0f0a"
  on-dark: "#f2fff2"
  divider-shadow: "rgba(0,0,0,0.8)"
  card-shadow: "rgba(0,0,0,0.75)"
  inset-shadow: "rgba(0,0,0,0.7)"
  tab-green-border: "#286d28"
  tab-green-active: "#47b347"
  tab-cyan-border: "#28696d"
  tab-cyan-active: "#47a6b3"

typography:
  hero-display:
    fontFamily: "Eurostile Extd, Eurostile Extended, sans-serif"
    fontSize: 64px
    fontWeight: 700
    lineHeight: 0.95
    letterSpacing: 0
    textTransform: uppercase
  display-lg:
    fontFamily: "Eurostile Extd, Eurostile Extended, sans-serif"
    fontSize: 45px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: 0
    textTransform: uppercase
  display-md:
    fontFamily: "Eurostile Extd, Eurostile Extended, sans-serif"
    fontSize: 30px
    fontWeight: 700
    lineHeight: 1.08
    letterSpacing: 0
    textTransform: uppercase
  subheading:
    fontFamily: "Eurostile Extd, Eurostile Extended, sans-serif"
    fontSize: 18px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0
    textTransform: uppercase
  button:
    fontFamily: "Eurostile Extd, Eurostile Extended, sans-serif"
    fontSize: 18px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: 0
    textTransform: uppercase
  button-sm:
    fontFamily: "Eurostile Extd, Eurostile Extended, sans-serif"
    fontSize: 15px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: 0
    textTransform: uppercase
  body:
    fontFamily: "Source Sans Pro, system-ui, -apple-system, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-lg:
    fontFamily: "Source Sans Pro, system-ui, -apple-system, sans-serif"
    fontSize: 21px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-sm:
    fontFamily: "Source Sans Pro, system-ui, -apple-system, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  caption:
    fontFamily: "Source Sans Pro, system-ui, -apple-system, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0
  price:
    fontFamily: "Alegreya Sans, Source Sans Pro, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: 0
  nav-link:
    fontFamily: "Source Sans Pro, system-ui, -apple-system, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0

rounded:
  none: 0px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 20px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 48px
  xxl: 72px
  section: 96px
  masthead: 160px

components:
  button-primary:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.xs}"
    padding: 16px 32px
  button-primary-hover:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.primary}"
    rounded: "{rounded.xs}"
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.accent-cyan}"
    typography: "{typography.button}"
    rounded: "{rounded.xs}"
    padding: 16px 32px
  button-secondary-hover:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.accent-cyan}"
    rounded: "{rounded.xs}"
  media-frame:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.lg}"
    padding: 0
  media-frame-hover:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.lg}"
  section-divider:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.none}"
    height: 13px
  masthead:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    rounded: "{rounded.none}"
    padding: 160px 40px 96px
  content-section:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: 96px 40px
  game-feature-card:
    backgroundColor: "{colors.surface-overlay}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: 48px 32px
  cross-sell-tile:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.none}"
    padding: 0
  tab-orb:
    backgroundColor: "radial-gradient(50% 50% at 50% 50%, rgba(3,14,3,0.65) 0%, rgba(21,79,22,0.52) 100%)"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.full}"
    size: 72px
  tab-orb-active:
    backgroundColor: "radial-gradient(50% 50% at 50% 50%, #002800 0%, #47b347 100%)"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.full}"
    size: 72px
  social-icon:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 40px
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    typography: "{typography.caption}"
    rounded: "{rounded.none}"
    padding: 72px 40px
---

## Overview

StarCraft: Remastered's site is a **cinematic RTS command interface**. The whole page sits on black, then each section paints over it with battlefield art, grid panels, race/faction imagery, and star-field social footer backgrounds. Unlike clean console-store marketing, this system wants visible machinery: scan lines, glowing borders, four-corner media brackets, smoky black shadows, and uppercase sci-fi typography.

The front matter should be read as a battle-station UI kit. Headlines are Eurostile Extended Bold and always uppercase; body text is Source Sans Pro in cool gray-blue. Buttons are not flat brand pills. The primary CTA is a black, scan-lined rectangle with lime text, lime border, an outer dark frame, and glow. Secondary CTAs swap the lime system for cyan, but keep the same 4px industrial rectangle and scan-line texture.

**Key Characteristics:**
- Black canvas from top to bottom; no light page mode.
- Huge responsive artwork backgrounds: masthead battlefield, grid overview, feature scenes, repeating grid cross-sell, fixed social footer.
- Eurostile Extd Bold uppercase display type paired with Source Sans Pro body copy.
- Primary action color is glowing Terran-console green (`{colors.primary}` / #7aff7a), not Blizzard blue.
- Secondary/default chrome is cyan (`{colors.accent-cyan}` / #4be8f2) with blue border.
- Media frames use 20px radius, 2px pale outline, heavy black shadow, inset darkness, and decorative armored corner images.
- Section breaks are real assets: 13px dividers with `0 3px 15px 6px rgba(0,0,0,0.8)` shadow.
- Hover states brighten and glow rather than changing geometry.
- Platform/social icons use pale green-white and drop-shadow glow over dark imagery.

## Colors

> **Source pages analyzed:** `https://starcraft.blizzard.com/en-us/` StarCraft: Remastered homepage, including masthead, overview video, game features, cross-sell, social footer, Blizzard nav/footer shell, and page CSS.

### Brand & Accent

- **Console Green** (`{colors.primary}` - #7aff7a): The primary CTA text color. Use for "Buy Now" and any top-priority mission action.
- **Lime Border** (`{colors.primary-border}` - #00ff00): The hard 1px border around primary buttons and the bright core of comparison slider controls.
- **Green Glow** (`{colors.primary-glow}` - #00cc00): Hover glow and icon aura, usually applied as a soft `box-shadow` or `drop-shadow`.
- **Dark Console Green** (`{colors.primary-dark}` - #003301) and **Deep Console Green** (`{colors.primary-deep}` - #008603): The lower stops inside primary button gradients.
- **Cyan Action** (`{colors.accent-cyan}` - #4be8f2): Default/secondary CTA text, media gallery CTA text, and blue-tech interface accent.
- **Cyan Border** (`{colors.accent-cyan-border}` - #1e86b0): Secondary button border.
- **Cyan Frame Dark** (`{colors.accent-cyan-dark}` - #1a465e): Outer frame for secondary/default buttons.
- **Subheading Blue** (`{colors.accent-blue-text}` - #cce1ff): Label and subheading text, such as "REAL-TIME STRATEGY."
- **Success Price Green** (`{colors.success-price}` - #00ff94): Product price/discount accent used in commerce tables and highlights.

### Surface

- **Black Canvas** (`{colors.canvas}` - #000000): Body background, section base, game tiles, footer foundation.
- **Button Black** (`{colors.surface-dark}` - #151515): Primary button fill, a slightly raised black that allows scan lines and green gradient to read.
- **Dark Overlay** (`{colors.surface-overlay}` - rgba(0,0,0,0.6)): Applied over feature backgrounds to keep text legible.
- **Panel Overlay** (`{colors.surface-panel}` - rgba(0,0,0,0.5)): Button backing plate and dark interface plate behind framed controls.
- **Media Outline** (`{colors.media-outline}` - rgba(242,255,242,0.5)): The pale green-white outline around screenshots and video thumbnails.
- **Media Outline Hover** (`{colors.media-outline-hover}` - rgba(242,255,242,0.75)): Brighter outline on interactive media hover.

### Text

- **Pale Tactical White** (`{colors.ink}` - #f2fff2): Primary text/icon color over black and photography.
- **Body Gray-Blue** (`{colors.body}` - #b8bbcc): Default description text. It is cooler than neutral gray and keeps the site in sci-fi mode.
- **Muted Body** (`{colors.body-muted}` - rgba(184,187,204,0.72)): Secondary paragraphs and low-priority copy.
- **On Primary** (`{colors.on-primary}` - #0a0f0a): Rare dark text on light green surfaces, mostly reserved for special states.
- **On Dark** (`{colors.on-dark}` - #f2fff2): Foreground text over every dark section.

### Effects

- **Divider Shadow** (`{colors.divider-shadow}` - rgba(0,0,0,0.8)): Section divider and navigation depth.
- **Card Shadow** (`{colors.card-shadow}` - rgba(0,0,0,0.75)): Media frame drop shadow: `0 4px 20px 0`.
- **Inset Shadow** (`{colors.inset-shadow}` - rgba(0,0,0,0.7)): Inner darkness on media frames, roughly `0 0 40px 15px inset`.
- **Tab Green / Cyan Borders** (`{colors.tab-green-border}`, `{colors.tab-cyan-border}`): Circular icon tabs and race controls.

## Typography

### Font Family

StarCraft loads two core fonts:

```css
--font-display: "Eurostile Extd", "Eurostile Extended", sans-serif;
--font-body: "Source Sans Pro", system-ui, -apple-system, sans-serif;
```

Eurostile Extd is used for `[slot=heading]`, `[slot=subheading]`, buttons, and tab controls, with `text-transform: uppercase`. Source Sans Pro is used for descriptions, content slots, platform labels, lightbox counts, and smaller media content blocks.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---:|---:|---:|---:|---|
| `{typography.hero-display}` | 64px | 700 | 0.95 | 0 | Masthead headline / big campaign copy |
| `{typography.display-lg}` | 45px | 700 | 1.05 | 0 | Section headings on desktop |
| `{typography.display-md}` | 30px | 700 | 1.08 | 0 | Section headings on mobile and compact panels |
| `{typography.subheading}` | 18px | 700 | 1.20 | 0 | Genre labels and small command labels |
| `{typography.button}` | 18px | 700 | 1.10 | 0 | Desktop CTA labels |
| `{typography.button-sm}` | 15px | 700 | 1.10 | 0 | Mobile CTA labels |
| `{typography.body-lg}` | 21px | 400 | 1.55 | 0 | Larger intro copy |
| `{typography.body}` | 18px | 400 | 1.55 | 0 | Default descriptions |
| `{typography.body-sm}` | 16px | 400 | 1.50 | 0 | Cards and smaller descriptions |
| `{typography.caption}` | 14px | 400 | 1.40 | 0 | Footer/legal/supporting text |
| `{typography.price}` | 18px | 400 | 1.30 | 0 | Price/discount labels |
| `{typography.nav-link}` | 16px | 400 | 1.20 | 0 | Blizzard shell navigation |

### Principles

- **Display copy is uppercase by default.** Mixed case belongs to body text and footer/legal copy.
- **No delicate tracking.** Eurostile's extended width is already the brand signal. Avoid negative letter-spacing.
- **Body text is cool and readable.** Source Sans Pro at 18px with 1.55 line-height keeps lore and feature descriptions legible over dark imagery.
- **Headings compress vertically.** Hero and section titles use tight line-height so two-line statements feel like a game logo lockup.
- **Use color for hierarchy.** Subheadings lean blue (`#cce1ff`), body is gray-blue (`#b8bbcc`), and CTAs glow green or cyan.

## Layout

### Spacing System

- **Base unit:** 8px, with Blizzard Evergreen sections using 40px content gutters and 24px button-group gaps.
- **CTA group gap:** 24px.
- **Media gallery gap:** 40px.
- **Section rhythm:** 96px vertical padding for standard content sections; masthead gets a taller 160px top stage.
- **Section dividers:** 13px tall full-width image strips, not simple borders.

### Grid & Container

- **Page max width:** 2600px; the body centers a `.main-content` wrapper at full width with `max-width: 2600px`.
- **Masthead:** minimum 900px on desktop, with logo and heading centered over a bottom-positioned battlefield background. On mobile, min-height grows by viewport width (`max(220vw, 850px)` style behavior) to preserve the vertical key art.
- **Overview media:** 16:9 video thumbnail in a framed media shell, centered, max around 960px.
- **Feature cards:** carousel/card sections use horizontal overflow on smaller screens; first and last cards get 40px side margins.
- **Cross-sell:** four game tiles at desktop, horizontal scroll below 1200px.
- **Social/footer:** fixed-attachment background art with a black fade at the top and bottom.

### Whitespace Philosophy

Whitespace is not clean editorial air; it is battlefield staging. Empty space should feel like darkness, smoke, or distance between UI panels. Copy sits in tight centered or tactical blocks while the background art does most of the atmospheric work.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat black | `{colors.canvas}` with background art | Section base and footer |
| Divider depth | 13px image strip + `0 3px 15px 6px rgba(0,0,0,0.8)` | Between major sections |
| Button plate | Outer `-3px` frame, dark backing, scan-line texture | Primary and secondary CTAs |
| Media frame | 2px pale outline, 20px radius, armored corner images, black drop shadow | Video thumbnails, screenshots, cards |
| Glow active | Green/cyan `0 0 8px 2px` glow and brightness filter | Hover/active media and buttons |

### Decorative Depth

StarCraft's depth is deliberately theatrical:

- **Scan-line buttons** use a repeated texture plus vertical green/cyan gradients.
- **Armored media corners** are separate images anchored to top-left, top-right, bottom-right, and bottom-left.
- **Inset black frame** darkens the inside edge of video and image containers.
- **Starfield animations** and comet motion appear in error/background contexts; use sparingly as ambient space detail.
- **Drop shadows are heavy.** This is not soft SaaS elevation; it is game UI contrast over dark illustration.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---:|---|
| `{rounded.none}` | 0px | Structural sections, game tiles, dividers |
| `{rounded.xs}` | 4px | Buttons, comparison-slider handlebar |
| `{rounded.sm}` | 8px | Small interface panels |
| `{rounded.md}` | 12px | Gallery thumbnails / tab thumbnails |
| `{rounded.lg}` | 20px | Media frames and video thumbnails |
| `{rounded.full}` | 9999px | Circular race/social/icon controls |

### Media Geometry

- **Media frame radius:** 20px on videos, screenshots, gallery slides, and cross-sell media.
- **Decorative frame overscan:** frame corner images sit at `-6px` around the media container.
- **Corner art size:** 50px background-size at each corner.
- **Primary media aspect:** 16:9.
- **Game tiles:** rectangular art, no card radius on the outer tile; framed media inside carries the radius.

## Components

### Masthead

**`masthead`** - Full-bleed black/art hero. Uses responsive battlefield backgrounds: mobile, 1600px, and 2600px variants with `background-position: bottom`. The logo receives multiple black drop-shadows (`2px 0 20px`, `0 0 40px`, `0 0 50px`) so it reads over illustration. Header layout is centered. Platform icons sit below, with pale text shadowed by black.

### Buttons

**`button-primary`** - The StarCraft "Buy Now" button. Fill `{colors.surface-dark}` with scan-line texture and green vertical gradient. Text `{colors.primary}` in uppercase Eurostile. Border `1px solid {colors.primary-border}`. Outer plate is 3px larger with `{colors.primary-dark}` border, dark backing, and black shadow. Radius 4px. Hover brightens the overlay and adds green glow.

**`button-secondary`** - Default/cyan button for secondary actions such as gallery CTAs. Same industrial rectangle, but text `{colors.accent-cyan}`, border `{colors.accent-cyan-border}`, outer frame `{colors.accent-cyan-dark}`, and cyan gradient wash.

**`button-primary-hover`** and **`button-secondary-hover`** - Do not change layout. Increase brightness and show glow: primary uses `rgba(0,204,0,0.25)`, secondary uses a cool blue-violet glow.

### Media

**`media-frame`** - Used for YouTube thumbnails, videos, screenshots, comparison sliders, carousel media, lightbox slides, and card media. Base treatment:

```css
outline: 2px solid rgba(242,255,242,0.5);
border-radius: 20px;
box-shadow: 0 4px 20px 0 rgba(0,0,0,0.75);
```

It also gets a pseudo-element with four decorative corner images positioned at each corner and a second pseudo-element with a strong inset black shadow.

**`media-frame-hover`** - Outline brightens to `rgba(242,255,242,0.75)`, glow becomes `0 0 8px 2px rgba(0,204,0,0.6)`, and media brightens to `filter: brightness(1.1)`.

### Sections

**`section-divider`** - A 13px image strip with center/cover sizing and heavy black shadow. Use between major chapters. Do not substitute a CSS border.

**`content-section`** - Generic dark section with image/art background, overlay gradients where needed, centered header, body in Source Sans Pro, and framed media/card content.

**`game-feature-card`** - Feature carousel card surface over battlefield art. Uses black overlay logic, uppercase title, gray-blue description, and framed media when imagery is present.

**`cross-sell-tile`** - Blizzard game recommendation tile. Outer tile has no radius; media area gets StarCraft frame treatment. Gallery gap is 40px, and desktop expects four items.

### Tabs & Icons

**`tab-orb`** - Circular race/class icon control. Radial dark-green background, 1px green border, 4px/8px black shadow, full radius. Hover brightens.

**`tab-orb-active`** - Active state turns into a brighter radial green core (`#002800` to `#47b347`). Race variants can swap to cyan (`#002628` to `#47a6b3`) with `{colors.tab-cyan-border}`.

**`social-icon`** - Pale green-white icon over dark fixed background, with black drop-shadow. Hover adds green glow and brightness.

### Footer

**`footer`** - Dark social/footer band over fixed background art with black gradient fade at top and bottom. "Stay Connected" uses the small centered header style. Social links are X/Twitter, Facebook, YouTube, and Twitch. Blizzard legal footer sits below in the platform shell.

## Do's and Don'ts

### Do

- Use Eurostile Extd Bold uppercase for all headings, subheadings, buttons, and tabs.
- Use Source Sans Pro for body copy and longer descriptions.
- Keep the page black and image-led; every section should feel like game art or a command console.
- Use green for primary mission actions and cyan for secondary/default actions.
- Add scan-line textures to buttons.
- Frame important media with 20px radius, pale outline, armored corners, black shadow, and inset darkness.
- Use 13px image dividers between major sections.
- Let hover states glow and brighten.

### Don't

- Do not turn CTAs into modern pills; StarCraft buttons are squared 4px industrial plates.
- Do not use white cards or light page sections.
- Do not set headlines in a generic sans; Eurostile Extended is the core voice.
- Do not remove media borders or corner armor.
- Do not use soft pastel gradients or SaaS mesh backgrounds.
- Do not make section breaks invisible; the chunky divider is part of the brand.
- Do not use neutral gray body text when the cool gray-blue `{colors.body}` is available.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---:|---|
| Small phone | < 480px | Masthead uses mobile background, very tall art-first composition, CTA font 15px |
| Phone | 480-719px | Masthead remains art-led; media scales to viewport; cross-sell scrolls horizontally |
| Tablet | 720-959px | Section headings stay around 30px; thumbnails and icon tabs enlarge; media frame remains 20px |
| Desktop | 960-1199px | Nav offset becomes 72px; headings increase to 45px; masthead min-height ~900px |
| Wide desktop | >= 1200px | Cross-sell gallery stops scrolling; four game tiles sit in one row |
| Max art | >= 1600px | Backgrounds switch to 2600px / 3840px image assets |

### Mobile Rules

- Preserve background key art by increasing section height rather than cropping aggressively.
- Keep CTAs uppercase and framed even at small sizes.
- Do not remove the media frame on mobile; scale it down intact.
- Allow horizontal scrolling for cross-sell and feature carousels rather than compressing four cards into cramped columns.
- Keep text blocks short and centered unless paired with a specific feature panel.

