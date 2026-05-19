---
version: alpha
name: Arturia
description: |
  A sound-explorer product system built from black-and-white technical chrome, red-orange performance accents, large product/campaign hero panels, and modular news cards. Arturia's homepage mixes instrument launches, artist stories, preset packs, events, and support commerce in one pragmatic music-tech surface. Navigation has a distinctive terminal-like underscore prefix (_products, _sounds, _store, _community, _support), while the footer drops into a high-contrast black newsletter and support directory.

colors:
  primary: "#e84b2a"
  primary-deep: "#bf321c"
  primary-bright: "#ff6748"
  secondary: "#111111"
  ink: "#0b0b0b"
  body: "#242424"
  body-muted: "#6a6a6a"
  body-subtle: "#9a9a9a"
  on-primary: "#ffffff"
  on-dark: "#ffffff"
  canvas: "#ffffff"
  canvas-soft: "#f6f6f4"
  surface-card: "#ffffff"
  surface-hero: "#121212"
  surface-dark: "#000000"
  surface-graphite: "#191919"
  surface-silver: "#eeeeea"
  surface-warm-gray: "#e5e0d8"
  accent-persia: "#c33a29"
  accent-synth-blue: "#315fd6"
  accent-electric: "#f2d44d"
  hairline: "#d8d8d2"
  hairline-soft: "#ededed"
  focus-ring: "#e84b2a"
  overlay-dark: "rgba(0,0,0,0.48)"
  shadow-card: "0 16px 40px rgba(0,0,0,0.12)"

typography:
  hero-display:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 64px
    fontWeight: 700
    lineHeight: 1.02
    letterSpacing: -0.02em
  display-lg:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 44px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.015em
  display-md:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.18
    letterSpacing: -0.01em
  headline:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: -0.005em
  lead:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 21px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0
  body-lg:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-strong:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.45
    letterSpacing: 0
  nav-link:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0.02em
    textTransform: lowercase
  button:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 15px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0
  card-title:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 22px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: -0.005em
  label:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0.04em
    textTransform: uppercase
  caption:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0
  legal:
    fontFamily: "Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0

rounded:
  none: 0px
  xs: 2px
  sm: 6px
  md: 10px
  lg: 16px
  xl: 24px
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
  editorial: 112px

components:
  promo-strip:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.caption}"
    height: 40px
    padding: 8px 16px
  global-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 72px
    borderBottom: "1px solid {colors.hairline-soft}"
  nav-link-underscore:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.none}"
    padding: 12px 10px
  logo-lockup:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
  icon-button:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 44px
  hero-product:
    backgroundColor: "{colors.surface-hero}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    minHeight: 720px
  hero-overlay-copy:
    backgroundColor: "{colors.overlay-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-md}"
    padding: 40px
  campaign-tile-dark:
    backgroundColor: "{colors.surface-graphite}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-md}"
    rounded: "{rounded.none}"
    padding: 56px
  campaign-tile-light:
    backgroundColor: "{colors.canvas-soft}"
    textColor: "{colors.ink}"
    typography: "{typography.display-md}"
    rounded: "{rounded.none}"
    padding: 56px
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 14px 24px
    height: 46px
  button-primary-active:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.pill}"
  button-secondary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 14px 24px
    height: 46px
  text-link-arrow:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-strong}"
  news-grid:
    backgroundColor: "{colors.canvas-soft}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    gap: 24px
  news-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 28px
    shadow: "{colors.shadow-card}"
  news-card-label:
    backgroundColor: "{colors.surface-silver}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: 7px 12px
  product-category-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.card-title}"
    rounded: "{rounded.lg}"
    padding: 32px
    shadow: "{colors.shadow-card}"
  newsletter-footer:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
    padding: 64px 0px
  footer:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.caption}"
    padding: 64px 0px 32px
  footer-heading:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
  footer-link:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.caption}"
  email-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    border: "1px solid {colors.hairline}"
    padding: 14px 18px
    height: 48px
---

## Overview

Arturia's homepage presents the company as a practical but adventurous music-technology brand. It opens with a promo strip for **Augmented PERSIA**, then a compact white navigation bar with the brand's distinctive underscore-prefixed links: `_products`, `_sounds`, `_store`, `_community`, `_support`. The page then stacks product launch hero content, artist/story modules, preset-pack promotion, news cards, events, newsletter signup, and a support-heavy footer.

The visual language sits between instrument hardware, software UI, and modern creative commerce. It is more polished and dimensional than Ableton's flat manual-like system, but less maximal and color-saturated than Bitwig. Black and white form the chassis; red-orange acts as a performance accent; product imagery, synth interfaces, and campaign photography bring the color and energy.

The current homepage copy includes “Acoustic instruments reinvented,” “Instinct-led sound design with Pigments,” and “450 cutting-edge presets.” The language is direct, product-specific, and aimed at musicians who understand instruments, presets, controllers, sequencers, and sound design.

**Key Characteristics:**
- White technical nav with underscore-prefixed lowercase labels.
- Red-orange accent for launches, offers, and primary actions.
- Large product/campaign hero sections for instruments, sounds, and artist stories.
- Rounded pill CTAs paired with modular cards.
- News/event cards that mix product updates, events, dates, and long descriptive copy.
- Black footer with newsletter, product categories, support links, company links, and social icons.
- Brand position: sound exploration, synthesis, hybrid hardware/software workflows.

## Colors

> **Source page analyzed:** https://www.arturia.com/ via lightpanda MCP on 2026-05-19. The extracted page included the Augmented PERSIA promo, primary navigation, hero links, Jenys story, Explorations Vol. 6, IMSTA FESTA London event, KeyStep 37 mk2 news, Arturia World Tour news, newsletter, and footer taxonomy.

### Brand & Accent

- **Performance Orange** (`{colors.primary}` — #e84b2a): Main brand action and promotional accent. Use for offer strips, primary CTAs, launch badges, and focus states.
- **Deep Orange** (`{colors.primary-deep}` — #bf321c): Active state for primary actions.
- **Bright Orange** (`{colors.primary-bright}` — #ff6748): High-energy highlights on dark media.
- **Synth Blue** (`{colors.accent-synth-blue}` — #315fd6): Secondary campaign accent when referencing software instruments, Pigments, or digital synthesis.
- **Electric Yellow** (`{colors.accent-electric}` — #f2d44d): Sparing highlight for presets, knobs, and sound-pack energy.

### Surface

- **Canvas** (`{colors.canvas}` — #ffffff): Primary nav and content surface.
- **Soft Canvas** (`{colors.canvas-soft}` — #f6f6f4): News grids, product browsing, and neutral page bands.
- **Hero Surface** (`{colors.surface-hero}` — #121212): Dark fallback for product/campaign hero modules.
- **Graphite** (`{colors.surface-graphite}` — #191919): Dark cards or story modules that should feel technical rather than pure void.
- **Black** (`{colors.surface-dark}` — #000000): Footer and high-contrast brand anchor.
- **Silver** (`{colors.surface-silver}` — #eeeeea): Labels, tag chips, and utility backgrounds.

### Text

- **Ink** (`{colors.ink}` — #0b0b0b): Primary headings and nav.
- **Body** (`{colors.body}` — #242424): Default copy.
- **Body Muted** (`{colors.body-muted}` — #6a6a6a): Secondary descriptions, dates, legal copy.
- **On Dark** (`{colors.on-dark}` — #ffffff): Footer, hero overlays, dark campaign tiles.

### Borders & Effects

- **Hairline** (`{colors.hairline}` — #d8d8d2): Inputs, card separators, quiet dividers.
- **Hairline Soft** (`{colors.hairline-soft}` — #ededed): Nav border and low-emphasis rules.
- **Card Shadow** (`{colors.shadow-card}`): `0 16px 40px rgba(0,0,0,0.12)` for modular cards. Arturia allows more elevation than Ableton.

## Typography

### Font Family

- **Primary:** `Inter, Helvetica Neue, Arial, sans-serif`. The DOM exposed `inter` classes on key promotional and nav elements. Use Inter as the practical approximation: modern, readable, and technical.
- **Logo:** The Arturia wordmark is an SVG asset and should not be rebuilt with live type.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.hero-display}` | 64px | 700 | 1.02 | -0.02em | Product launch hero |
| `{typography.display-lg}` | 44px | 700 | 1.10 | -0.015em | Major campaign heading |
| `{typography.display-md}` | 32px | 700 | 1.18 | -0.01em | Story and preset-pack headings |
| `{typography.headline}` | 24px | 700 | 1.25 | -0.005em | News/card headings |
| `{typography.lead}` | 21px | 400 | 1.45 | 0 | Hero tagline |
| `{typography.body}` | 16px | 400 | 1.55 | 0 | Default copy |
| `{typography.nav-link}` | 14px | 700 | 1.0 | 0.02em | `_products`, `_sounds`, `_store` nav labels |
| `{typography.button}` | 15px | 700 | 1.0 | 0 | CTAs |
| `{typography.label}` | 13px | 700 | 1.25 | 0.04em | News/Event tags and footer headings |
| `{typography.caption}` | 13px | 400 | 1.45 | 0 | Footer links and metadata |

### Principles

- **Technical but approachable.** Use clean sans-serif with high legibility; avoid experimental display faces that distract from product names.
- **Bold product names matter.** Instrument names such as Augmented PERSIA, Pigments, KeyStep, and Explorations should be prominent.
- **Lowercase underscore nav is a brand cue.** Preserve the `_products` pattern; do not normalize it into generic title-case navigation.
- **Copy can be descriptive.** News cards tolerate longer explanatory text than a pure consumer ecommerce site.

## Layout

### Spacing System

- **Base unit:** 8px, with 24/32/48/80 as recurring layout intervals.
- **Promo strip:** A narrow top strip, roughly 40px tall, carrying one offer and one arrow link.
- **Navigation:** 72px white bar with logo, underscore links, locale, and cart.
- **Hero modules:** 720px+ dark or image-led panels with large product names and a single CTA.
- **News grid:** Modular card grid with 24px gutters.
- **Footer:** Deep black, high contrast, content-rich.

### Grid & Container

- **Homepage stack:** promo → nav → product hero → story tile → preset promo → news/event grid → newsletter/footer.
- **News cards:** 3-up or responsive grid; cards include a label, title, summary, optional date, and link.
- **Footer columns:** Products, Store and Services, About us, Social Networks.

### Whitespace Philosophy

Arturia alternates between large immersive launch panels and dense utility sections. The page should feel like a musician's product ecosystem: enough whitespace to make instruments desirable, enough density to expose software, sounds, support, education, events, and community.

## Components

### Navigation

**`promo-strip`** announces a current offer, such as the Augmented PERSIA intro price. It should be compact, high-contrast, and link with an arrow affordance.

**`global-nav`** is a white technical bar with Arturia logo, underscore-prefixed product links, locale, and cart.

**`nav-link-underscore`** is the signature nav label. Keep the underscore and lowercase text: `_products`, `_sounds`, `_store`, `_community`, `_support`.

### Hero & Campaign Modules

**`hero-product`** is the primary launch surface. It pairs a large product name with a short tagline like “Acoustic instruments reinvented” and a single `Discover` CTA.

**`campaign-tile-dark`** is used for artist stories and software-led campaign modules, where photography or UI imagery sits over a dark technical surface.

**`campaign-tile-light`** supports preset packs, secondary launches, and lighter product stories.

### Buttons & Links

**`button-primary`** is a red-orange pill. It should feel energetic but not toy-like.

**`button-secondary`** is a black pill for neutral actions on light surfaces.

**`text-link-arrow`** is used for short inline CTAs such as “→ Check the offer,” “Read the story,” and “See more news.”

### Cards

**`news-grid`** lays out events and news. It should support mixed content lengths without collapsing into equal-height blandness.

**`news-card`** is a white modular surface with label, headline, summary, and optional date. Shadows are acceptable and help cards separate from soft backgrounds.

**`news-card-label`** distinguishes Event vs News. It should be compact and uppercase.

**`product-category-card`** can represent hardware synthesizers, controllers, audio interfaces, software instruments, effects, and other product families.

### Footer

**`newsletter-footer`** is a black high-contrast signup area. It includes a newsletter prompt and privacy copy.

**`footer`** is a utility directory with product categories, store/support links, company links, and social icons. It is dense and practical, not decorative.

## Do's and Don'ts

### Do

- Preserve underscore-prefixed nav labels.
- Use red-orange as the primary launch/action accent.
- Let product names and instrument categories remain explicit and technical.
- Mix product, artist, preset, event, and support content in the same system.
- Use black footer surfaces for newsletter and directory content.
- Use real product imagery, synth UI screenshots, hardware closeups, and musician story photography.

### Don't

- Don't flatten Arturia into Ableton-style pure square minimalism.
- Don't overuse neon gradients; Arturia's color should mostly come from products and campaigns.
- Don't remove support/store/community pathways from the main experience.
- Don't make every CTA black; orange is the energy cue.
- Don't normalize `_products` into “Products” in the main nav.
- Don't make cards too precious; this is practical music-tech communication.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Small phone | ≤ 419px | Promo text wraps; nav becomes hamburger; hero type drops to 34px |
| Phone | 420–767px | Single-column campaign tiles and news cards; footer columns stack |
| Tablet | 768–1023px | Two-column card grids; compact nav with reduced link count |
| Desktop | 1024–1439px | Full nav, large hero, 3-up news grid |
| Large desktop | ≥ 1440px | Hero imagery expands; content max-width prevents cards from over-stretching |

### Behavior Notes

- Keep the promo strip visible unless it consumes too much mobile height.
- The underscore nav pattern should survive in mobile menus.
- Hero modules should art-direct imagery; do not simply center-crop product hardware if it removes controls or UI context.
- Footer content should remain complete on mobile through stacked groups.

## Content Strategy

- Lead with the current product launch or offer.
- Follow with creative proof: artist story, sound design story, preset pack, or event.
- Keep copy concrete: instrument name, workflow, sound-design promise, event date.
- Balance inspiration with support. Arturia users need downloads, manuals, support, FAQ, distributors, education, and environmental/company info.

## Sources

- Homepage: https://www.arturia.com/
- Extracted with lightpanda MCP on 2026-05-19.
