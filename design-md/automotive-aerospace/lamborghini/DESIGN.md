---
version: alpha
name: Lamborghini
description: |
  Lamborghini's current public site is a theatrical performance system built
  on the official Lamborghini Design Tokens v1.5.0: LamboType Variable,
  absolute black and near-black surfaces, white navigation, sharp-edged
  controls, hexagonal action motifs, and a gold accent reserved for decisive
  actions. The homepage is no longer only a dark video stage; it mixes
  full-bleed hero banners, model discovery, news cards, light content surfaces,
  emissions/disclaimer modules, and an accessibility-aware header. The voice is
  aggressive, uppercase, engineered, and cinematic, with the product line
  anchored by Fenomeno Roadster, Revuelto, Temerario, Urus, and limited-series
  content.

colors:
  black: "#000000"
  white: "#ffffff"
  lamborghini-gold: "#ffc000"
  gold-hover: "#997300"
  gold-pressed: "#cc9a00"
  gold-light-theme: "#917300"
  gold-light-hover: "#423500"
  surface-dark: "#181818"
  surface-dark-2: "#313131"
  surface-dark-3: "#494949"
  surface-light: "#f5f5f5"
  surface-light-2: "#dcdcdc"
  surface-light-3: "#c4c4c4"
  text-dark-primary: "#f5f5f5"
  text-dark-secondary: "#dcdcdc"
  text-dark-tertiary: "#c4c4c4"
  text-dark-muted: "#ababab"
  text-dark-disabled: "#969696"
  text-light-primary: "#181818"
  text-light-secondary: "#313131"
  text-light-tertiary: "#494949"
  text-light-muted: "#626262"
  text-light-disabled: "#7d7d7d"
  stroke-dark-1: "#7d7d7d"
  stroke-dark-2: "#626262"
  stroke-dark-3: "#494949"
  stroke-dark-4: "#313131"
  stroke-light-1: "#969696"
  stroke-light-2: "#ababab"
  stroke-light-3: "#c4c4c4"
  stroke-light-4: "#dcdcdc"
  focus-blue: "#1e90ff"
  signal-alert-dark: "#e62d37"
  signal-warning-dark: "#ff822d"
  signal-info-dark: "#2d73d7"
  signal-success-dark: "#37d200"
  signal-alert-light: "#dc1e28"
  signal-warning-light: "#f5a500"
  signal-info-light: "#2328ff"
  signal-success-light: "#23a046"
  gradient-dark-bottom: "linear-gradient(180deg, #00000000 0%, #000000 100%)"
  gradient-dark-surface: "linear-gradient(180deg, #18181833 0%, #181818 100%)"
  gradient-light-bottom: "linear-gradient(180deg, #00000000 0%, #f5f5f5 100%)"
  gradient-header: "linear-gradient(180deg, #f5f5f5 0%, #18181800 100%)"

typography:
  display-max:
    fontFamily: LamboType
    fontSize: 136px
    fontWeight: 700
    fontVariation: '"wdth" 50, "wght" 700'
    lineHeight: 1.0
    letterSpacing: 0
    textTransform: uppercase
  hero:
    fontFamily: LamboType
    fontSize: 120px
    fontWeight: 700
    fontVariation: '"wdth" 50, "wght" 700'
    lineHeight: 1.05
    letterSpacing: 0
    textTransform: uppercase
  display-xl:
    fontFamily: LamboType
    fontSize: 90px
    fontWeight: 700
    fontVariation: '"wdth" 50, "wght" 700'
    lineHeight: 1.0
    letterSpacing: 0
    textTransform: uppercase
  display-lg:
    fontFamily: LamboType
    fontSize: 80px
    fontWeight: 700
    fontVariation: '"wdth" 50, "wght" 700'
    lineHeight: 1.0
    letterSpacing: 0
    textTransform: uppercase
  heading-xl:
    fontFamily: LamboType
    fontSize: 60px
    fontWeight: 700
    fontVariation: '"wdth" 50, "wght" 700'
    lineHeight: 1.0
    letterSpacing: 0
    textTransform: uppercase
  heading-lg:
    fontFamily: LamboType
    fontSize: 54px
    fontWeight: 700
    fontVariation: '"wdth" 50, "wght" 700'
    lineHeight: 1.11
    letterSpacing: 0
    textTransform: uppercase
  heading-md:
    fontFamily: LamboType
    fontSize: 40px
    fontWeight: 700
    fontVariation: '"wdth" 50, "wght" 700'
    lineHeight: 1.25
    letterSpacing: 0
    textTransform: uppercase
  heading-sm:
    fontFamily: LamboType
    fontSize: 27px
    fontWeight: 700
    fontVariation: '"wdth" 50, "wght" 700'
    lineHeight: 1.41
    letterSpacing: 0
    textTransform: uppercase
  body-lg:
    fontFamily: LamboType
    fontSize: 18px
    fontWeight: 400
    fontVariation: '"wdth" 100, "wght" 400'
    lineHeight: 1.56
    letterSpacing: 0
  body-md:
    fontFamily: LamboType
    fontSize: 16px
    fontWeight: 400
    fontVariation: '"wdth" 100, "wght" 400'
    lineHeight: 1.625
    letterSpacing: 0
  label:
    fontFamily: LamboType
    fontSize: 18px
    fontWeight: 700
    fontVariation: '"wdth" 50, "wght" 700'
    lineHeight: 1.56
    letterSpacing: 0
    textTransform: uppercase
  micro:
    fontFamily: LamboType
    fontSize: 10px
    fontWeight: 400
    fontVariation: '"wdth" 50, "wght" 400'
    lineHeight: 1.25
    letterSpacing: 0.36px
    textTransform: uppercase
  fallback-prose:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: 300
    lineHeight: 1.5

spacing:
  none: 0
  xxs: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 40px
  xxl: 48px
  xxxl: 56px
  section: 64px
  block: 72px
  page: 80px
  grid: 60px
  mobile-gutter: 24px
  header-desktop: 104px
  header-mobile: 80px

rounded:
  none: 0
  focus: 3px
  sm: 4px
  md: 8px
  lg: 16px
  hexagon: polygonal

elevation:
  none: none
  focus-dark: "0 0 0 2px #1e90ff"
  dark-overlay: "{colors.gradient-dark-bottom}"
  dark-surface-gradient: "{colors.gradient-dark-surface}"
  light-surface-gradient: "{colors.gradient-light-bottom}"
  header-gradient: "{colors.gradient-header}"

components:
  header:
    backgroundColor: transparent
    fullBackgroundColor: "{colors.surface-dark}"
    textColor: "{colors.white}"
    logo: centered Lamborghini shield
    heightDesktop: 104px
    heightMobile: 80px
    layout: menu button left, logo center, search and utility icons right
    motion: hides upward on scroll, returns with full background state
  menu-button:
    icon: hamburger
    label: Menu
    textColor: "{colors.white}"
    hoverColor: "{colors.text-dark-tertiary}"
    typography: "{typography.label}"
    padding: "{spacing.xs}"
    minWidth: 80px
  hero-banner:
    backgroundColor: "{colors.black}"
    textColor: "{colors.text-dark-primary}"
    media: full-bleed image or video
    overlay: "{colors.gradient-dark-bottom}"
    typography: "{typography.hero}"
    ctaStyle: hexagon media center or primary
    minHeight: "calc(100vh - 104px)"
  button-primary:
    backgroundColor: "{colors.lamborghini-gold}"
    hoverBackgroundColor: "{colors.gold-hover}"
    pressedBackgroundColor: "{colors.gold-pressed}"
    textColor: "{colors.black}"
    typography: "{typography.label}"
    border: none
    rounded: "{rounded.none}"
    padding: "16px 24px"
  button-secondary-dark:
    backgroundColor: transparent
    textColor: "{colors.white}"
    hoverColor: "{colors.text-dark-tertiary}"
    border: "1px solid {colors.white}"
    rounded: "{rounded.none}"
    padding: "12px 16px"
    typography: "{typography.label}"
  icon-button:
    backgroundColor: transparent
    textColor: "{colors.white}"
    hoverBackgroundColor: "rgba(255,255,255,0.08)"
    focusBorder: "2px solid {colors.focus-blue}"
    rounded: "{rounded.none}"
    size: 40px
  hexagon-cta:
    shape: hexagon
    backgroundColor: "{colors.lamborghini-gold}"
    textColor: "{colors.black}"
    hoverBackgroundColor: "{colors.gold-hover}"
    typography: "{typography.label}"
  news-card:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.text-light-primary}"
    labelColor: "{colors.gold-light-theme}"
    mediaRatio: "16 / 9"
    rounded: "{rounded.none}"
    shadow: "{elevation.none}"
  light-section:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.text-light-primary}"
    accentColor: "{colors.gold-light-theme}"
  dark-section:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.text-dark-primary}"
    accentColor: "{colors.lamborghini-gold}"
  footer:
    backgroundColor: "{colors.black}"
    textColor: "{colors.text-dark-secondary}"
    linkColor: "{colors.text-dark-primary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.none}"
---

## Overview

Lamborghini's current site is a dark cinematic brand system with a real token foundation. The page ships `/tokens.css` labeled **Lamborghini Design Tokens Version 1.5.0 - 13/02/2025**, and that file defines the visual grammar: dark and light themes, LamboType Variable, black/white inversion, gold active states, 4px-80px spacing, 0/4/8/16px radius tokens, blue focus outlines, and a large type scale from 10px to 136px.

The homepage at `https://www.lamborghini.com/en-en` currently presents the brand as a high-drama editorial feed rather than a single black hero. The content model includes full-bleed hero banners, model entries, latest news, multilingual metadata, emissions data, and media-center CTAs. The live content references **Fenomeno Roadster**, **Lamborghini Arena 2026**, **Automobili Lamborghini turns 63**, and the current model ecosystem: Revuelto, Temerario, Urus SE, plus legacy and limited-series entries.

The 2024 Lamborghini identity is still the core: centered shield logo, left-side Menu button, right-side icon controls, LamboType Variable with condensed uppercase settings, sharp controls, and a gold accent that should feel rare. What changed from the older pure-Markdown read is that the system is now more explicitly tokenized and more theme-aware: dark hero surfaces coexist with light news/product sections, and accessibility/focus states are first-class.

**Key Characteristics:**
- Official LamboType Variable loaded from `/fonts/2024/lambotype-web-variable/`.
- Dark theme uses `#000000` and `#181818`; light theme uses `#ffffff` and `#f5f5f5`.
- Lamborghini Gold (`#ffc000`) is the dark-theme active/accent color; light theme darkens active gold to `#917300`.
- Header is fixed, transparent over media, with a full-background state on scroll.
- Menu button uses uppercase condensed variable settings: `"wdth" 50, "wght" 700`.
- Hexagonal CTA style remains a signature action shape, especially around media/news CTAs.
- Focus states use blue (`#1e90ff`) outlines, not gold.
- Current site includes an explicit skip-to-content link and visible accessibility behavior.

## Colors

### Dark Theme
- **Surface 0 / Abyss** (`#000000`): Full-bleed hero, deepest page layer, footer, and dark editorial stage.
- **Surface 1** (`#181818`): Header full-background state, cookie banner, dark panels, and primary dark surface.
- **Surface 2** (`#313131`) and **Surface 3** (`#494949`): Stepped dark elevation, dividers, secondary panels.
- **Text 1** (`#f5f5f5`): Primary dark-theme text.
- **Text 2** (`#dcdcdc`): Secondary dark-theme links and copy.
- **Text 5** (`#969696`): Disabled and low-priority dark-theme text.

### Light Theme
- **Surface 0** (`#ffffff`): Light content base.
- **Surface 1** (`#f5f5f5`): News and editorial light sections.
- **Surface 2** (`#dcdcdc`) and **Surface 3** (`#c4c4c4`): Light separators and subdued panels.
- **Text 1** (`#181818`): Primary light-theme text.
- **Text 2** (`#313131`): Secondary light-theme text.
- **Text 5** (`#7d7d7d`): Muted/disabled light text.

### Accent & Interaction
- **Lamborghini Gold** (`#ffc000`): Dark-theme primary accent and active CTA.
- **Gold Hover** (`#997300`) and **Gold Pressed** (`#cc9a00`): Interaction states on dark surfaces.
- **Light Theme Gold** (`#917300`): Accessible accent on light surfaces.
- **Focus Blue** (`#1e90ff`): Keyboard focus border. Do not substitute gold for focus.
- **Semantic Signals**: alert red (`#e62d37` dark / `#dc1e28` light), warning orange, info blue, and success green.

### Gradients
Gradients are structural overlays, not decorative color blends. Use dark-bottom gradients to keep white type readable over video and photography, dark-surface gradients to transition into `#181818`, and light-bottom gradients for light editorial modules.

## Typography

### Font Family
- **Primary**: `LamboType`, loaded as a variable font. Use it for navigation, heroes, labels, model names, CTAs, and most prose.
- **Icon Font**: `Lambo-icons`, used for search, social, geolocation, tool, checkmark, and social symbols.
- **Fallback Prose**: `Open Sans` appears in rich text/table content and legacy editorial blocks.

### Hierarchy

| Role | Font | Size | Weight / Variation | Line Height | Case | Notes |
|---|---|---:|---|---:|---|---|
| Maximum Display | LamboType | 136px | `"wdth" 50, "wght" 700` | 1.0 | Uppercase | Extreme campaign type |
| Hero | LamboType | 120px | `"wdth" 50, "wght" 700` | 1.05 | Uppercase | Model / hero statements |
| Display XL | LamboType | 90px | `"wdth" 50, "wght" 700` | 1.0 | Uppercase | Major feature sections |
| Display LG | LamboType | 80px | `"wdth" 50, "wght" 700` | 1.0 | Uppercase | Desktop section title |
| Heading XL | LamboType | 60px | `"wdth" 50, "wght" 700` | 1.0 | Uppercase | Editorial split sections |
| Heading LG | LamboType | 54px | `"wdth" 50, "wght" 700` | 1.11 | Uppercase | Large card/news titles |
| Heading MD | LamboType | 40px | `"wdth" 50, "wght" 700` | 1.25 | Uppercase | Compact hero/mobile |
| Heading SM | LamboType | 27px | `"wdth" 50, "wght" 700` | 1.41 | Uppercase | News/card titles |
| Body LG | LamboType | 18px | `"wdth" 100, "wght" 400` | 1.56 | Mixed | Body and paragraph |
| Body MD | LamboType | 16px | `"wdth" 100, "wght" 400` | 1.625 | Mixed | Standard UI copy |
| Micro | LamboType | 10px | `"wdth" 50, "wght" 400` | 1.25 | Uppercase | Badges and tiny labels |

### Principles
- Use uppercase and condensed width for navigational, display, and CTA language.
- Use variable font settings instead of faking condensation with negative letter spacing.
- Keep letter spacing mostly `0`; the token file exposes only `0`, `0`, and `0.36px`.
- Reserve Open Sans for embedded rich text tables or legacy content, not brand headlines.

## Layout

### Spacing System
The official scale is rem-based: 4, 8, 16, 24, 32, 40, 48, 56, 64, 72, 80, 88px, plus a 60px grid token. Mobile containers use 24px side padding. Header height is 104px on desktop and 80px on mobile.

### Grid & Container
- Use full-width hero/media modules.
- Use centered `.container` layouts for navigation and content groups.
- Keep a fixed header above content; reserve `scroll-margin-top` around 104px / 80px for anchor targets.
- Light sections can use `#f5f5f5` surfaces for news and informational lists.
- Dark sections should use black or `#181818`, not generic slate.

### Whitespace Philosophy
Lamborghini uses darkness as space and scale as hierarchy. A single title over a vehicle image should feel more powerful than a cluster of small cards. Let sections breathe, but keep transitions cinematic through media and gradient overlays.

## Elevation & Depth

Depth comes from surface tokens and media overlays, not shadows.

### Surface Levels
- **Level 0**: `#000000`, the deepest black.
- **Level 1**: `#181818`, standard dark panel/header surface.
- **Level 2**: `#313131`, raised dark panel.
- **Level 3**: `#494949`, high-contrast dark separation.
- **Light Level 1**: `#f5f5f5`, light editorial surface.

### Rules
- Do not add drop shadows to dark cards.
- Use official gradients for photo legibility.
- Use `#1e90ff` focus outlines for accessibility.
- Use surface changes and image contrast for perceived depth.

## Shapes

### Border Radius Scale
- **0px**: Default for buttons, cards, sections, images, forms, and nav surfaces.
- **4px / 8px / 16px**: Available token values but should be rare; use mainly for system/focus/accessibility affordances where the live site already does.
- **3px**: Focus pseudo-element radius from current header accessibility style.
- **Hexagon**: Signature CTA/icon geometry. Use for media-center CTAs, video controls, and special action buttons.

### Geometry
The dominant geometry is angular and mechanical. Rectangles, hard cuts, horizontal bars, and hexagons fit the brand; rounded SaaS cards do not.

## Components

### Header & Navigation
The header is fixed, transparent over the hero, and can switch to a full `#181818` background. Structure: Menu button on the left, centered Lamborghini shield logo, search/utility controls on the right. The Menu button includes a hamburger icon and uppercase "Menu" label on larger screens. Nav actions are icon buttons with hover and focus states.

### Hero Banner
Use full-bleed image/video modules with dark gradients and uppercase model or news titles. Current homepage content includes Fenomeno Roadster and news-oriented hero/media modules. Keep CTAs sparse: one hexagonal/media CTA or one primary gold action is enough.

### Model Modules
Model surfaces should foreground names such as Revuelto, Temerario, Urus SE, and Few-Off/Fenomeno with large uppercase type over car imagery. Emissions or disclaimer text may appear as supporting legal metadata and should stay visually secondary.

### CTAs
Primary dark-theme actions use `#ffc000` with black label text and hover to `#997300`. Secondary actions use transparent or black/white treatments with sharp corners. Hexagon CTAs are the strongest Lamborghini-specific control form.

### News Cards
News cards can live on light surfaces. They use large 16:9 imagery, uppercase labels like NEWS, dates/tags, and bold LamboType titles. Recent live examples include Lamborghini Arena 2026, Fenomeno Roadster, and Automobili Lamborghini turns 63.

### Accessibility & Focus
Preserve the skip-to-main-content link, `:focus-visible` outlines, and blue focus border. The current site uses a white translucent focus background plus a white/blue outline depending on component state.

### Cookie / Consent
Cookie controls inherit the dark system: `#181818` panel, uppercase LamboType labels, transparent or `#202020` buttons, white borders, and hard corners.

## Do's and Don'ts

### Do
- Use the official LamboType variable family and condensed uppercase settings.
- Treat `#000000` and `#181818` as distinct surfaces.
- Use Lamborghini Gold only for decisive actions and active accents.
- Use `#917300` rather than bright gold on light surfaces.
- Keep CTAs sharp or hexagonal.
- Preserve the fixed header pattern: menu left, shield center, icons right.
- Use full-bleed vehicle/media imagery with dark gradients.
- Keep blue focus outlines visible.
- Include legal/emissions/disclaimer space when showing current models.

### Don't
- Do not use generic dark blue/slate palettes.
- Do not make every section black; the current system includes light surfaces.
- Do not use soft cards, heavy shadows, or rounded SaaS buttons.
- Do not use gold as decoration or ambient glow.
- Do not replace LamboType condensation with arbitrary negative tracking.
- Do not hide accessibility focus states to preserve a cinematic look.
- Do not overload hero sections with multiple competing CTAs.

## Responsive Behavior

### Breakpoints

| Breakpoint | Width | Behavior |
|---|---:|---|
| Mobile Small | `< 576px` | 24px container gutters, 80px header, compact hero type |
| Mobile / Tablet | `576px-767px` | Single-column content, large media, reduced spacing |
| Tablet | `768px-991px` | Desktop/mobile visibility classes switch; two-column content may begin |
| Desktop | `992px-1199px` | Menu label appears, full header spacing, stronger grid |
| Large Desktop | `1200px+` | 104px header, 130px top compensation when no hero/breadcrumb |
| Wide | `1440px+` | Center content, keep hero full-bleed |

### Behavior Notes
- Keep hero media full-bleed and crop with `object-fit: cover`.
- Scale display type by discrete token sizes, not viewport-width font sizing.
- Collapse button groups vertically on mobile.
- Maintain 24px mobile container padding.
- Keep header controls touch-friendly; icon buttons need at least a 40px hit area.

## Iteration Guide

If a Lamborghini screen feels generic, first check whether LamboType variable settings are present. The brand loses much of its identity if headings are merely bold sans-serif. Next, enforce black/white/gold discipline, sharpen the controls, and increase media scale.

If a screen feels too theatrical for a utility task, move it onto `#f5f5f5` or `#ffffff`, use light-theme text tokens, and keep gold at `#917300`. The current site allows light surfaces for news, data, and informational modules; not every view needs the hero treatment.

## Known Gaps

- Homepage hero/news content changes frequently; model names and current campaign imagery should be rechecked before generating page-specific layouts.
- The site loads large generated Emotion CSS, so some component styles are runtime class-based rather than simple static selectors.
- LamboType internals are captured as practical variable settings, not a complete typographic specimen.
- Product configurator, dealer search, shop, and motorsport pages may add more specialized components beyond the homepage/global system.
