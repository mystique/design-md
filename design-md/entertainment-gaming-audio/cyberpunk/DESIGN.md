---
version: alpha
name: Cyberpunk 2077
description: A hyper-commercial dystopian marketing system rendered in acid yellow, black chrome, scanner cyan, and brutal promo typography. The page behaves like a game launcher crossed with a city billboard: oversized franchise logos, sharp rectangular buttons, stacked news cards, black-to-yellow surface inversion, platform icon strips, and dense sub-navigation for games, shows, community, and updates. It is loud by design, but disciplined loudness: every visual attack is channeled through a tiny palette, hard-edged geometry, and a repeated contrast grammar of yellow-on-black, black-on-yellow, and cyan utility accents.

colors:
  primary: "#fcee0a"
  primary-deep: "#d7c800"
  primary-soft: "#fff25c"
  primary-ink: "#000000"
  accent-cyan: "#00f0ff"
  accent-cyan-deep: "#00b7c3"
  accent-red: "#ff394a"
  accent-pink: "#ff4fd8"
  accent-toxic: "#8bff3d"
  canvas: "#000000"
  canvas-alt: "#090909"
  surface-panel: "#111111"
  surface-card: "#151515"
  surface-overlay: "rgba(0,0,0,0.66)"
  surface-glass: "rgba(10,10,10,0.82)"
  surface-yellow: "#fcee0a"
  surface-cyan: "#00f0ff"
  ink: "#000000"
  on-dark: "#ffffff"
  body-dark: "rgba(255,255,255,0.82)"
  body-muted: "rgba(255,255,255,0.56)"
  body-subtle: "rgba(255,255,255,0.34)"
  divider: "#2b2b2b"
  divider-bright: "#4a4a4a"
  stroke-yellow: "#fcee0a"
  stroke-cyan: "#00f0ff"
  focus-ring: "#00f0ff"
  shadow-hard: "0 12px 24px rgba(0,0,0,0.45)"

typography:
  hero-display:
    fontFamily: '"Rajdhani, Arial Narrow, Helvetica Neue, sans-serif"'
    fontSize: 72px
    fontWeight: 700
    lineHeight: 0.92
    letterSpacing: 0.01em
    textTransform: uppercase
  display-lg:
    fontFamily: '"Rajdhani, Arial Narrow, Helvetica Neue, sans-serif"'
    fontSize: 48px
    fontWeight: 700
    lineHeight: 0.98
    letterSpacing: 0.01em
    textTransform: uppercase
  display-md:
    fontFamily: '"Rajdhani, Arial Narrow, Helvetica Neue, sans-serif"'
    fontSize: 34px
    fontWeight: 700
    lineHeight: 1.02
    letterSpacing: 0.02em
    textTransform: uppercase
  title:
    fontFamily: '"Rajdhani, Arial Narrow, Helvetica Neue, sans-serif"'
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.08
    letterSpacing: 0.015em
    textTransform: uppercase
  nav-link:
    fontFamily: '"Rajdhani, Arial Narrow, Helvetica Neue, sans-serif"'
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: 0.06em
  utility:
    fontFamily: '"Rajdhani, Arial Narrow, Helvetica Neue, sans-serif"'
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: 0.08em
    textTransform: uppercase
  body-lg:
    fontFamily: '"Inter, Helvetica Neue, Arial, sans-serif"'
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  body:
    fontFamily: '"Inter, Helvetica Neue, Arial, sans-serif"'
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  body-strong:
    fontFamily: '"Inter, Helvetica Neue, Arial, sans-serif"'
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0.01em
  caption:
    fontFamily: '"Rajdhani, Arial Narrow, Helvetica Neue, sans-serif"'
    fontSize: 13px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: 0.08em
    textTransform: uppercase
  micro:
    fontFamily: '"Inter, Helvetica Neue, Arial, sans-serif"'
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0.01em
  button:
    fontFamily: '"Rajdhani, Arial Narrow, Helvetica Neue, sans-serif"'
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0.08em
    textTransform: uppercase

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 8px
  lg: 14px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 96px
  hero: 144px

components:
  masthead:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.utility}"
    height: 88px
  nav-link:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.none}"
    padding: 10px 0px
  nav-link-highlight:
    backgroundColor: "{colors.surface-yellow}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 14px 24px
    height: 44px
  hero-billboard:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    minHeight: 880px
  hero-copy:
    backgroundColor: "{colors.surface-overlay}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-lg}"
    padding: 40px
  button-primary-yellow:
    backgroundColor: "{colors.surface-yellow}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 16px 28px
    height: 48px
  button-primary-black:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.surface-yellow}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    border: "1px solid {colors.stroke-yellow}"
    padding: 16px 28px
    height: 48px
  button-secondary-cyan:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.accent-cyan}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    border: "1px solid {colors.stroke-cyan}"
    padding: 16px 28px
    height: 48px
  platform-strip:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    rounded: "{rounded.none}"
    gap: 16px
  news-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: 0px
    shadow: "{colors.shadow-hard}"
  news-highlight:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.on-dark}"
    typography: "{typography.title}"
    rounded: "{rounded.none}"
  section-break:
    backgroundColor: "{colors.surface-yellow}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    height: 8px
  product-universe-panel:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.none}"
    padding: 96px 0px
  franchise-tile:
    backgroundColor: "{colors.surface-panel}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: 0px
  newsletter-panel:
    backgroundColor: "{colors.canvas-alt}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: 96px 0px
  text-input-dark:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    border: "1px solid {colors.divider-bright}"
    padding: 16px 18px
    height: 56px
  checkbox-line:
    backgroundColor: transparent
    textColor: "{colors.body-muted}"
    typography: "{typography.micro}"
    rounded: "{rounded.none}"
  social-icon:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    rounded: "{rounded.none}"
    size: 40px
  partner-strip:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body-subtle}"
    rounded: "{rounded.none}"
    padding: 32px 0px
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body-muted}"
    typography: "{typography.micro}"
    rounded: "{rounded.none}"
    padding: 64px 0px

---

## Overview

Cyberpunk 2077's homepage is a **franchise billboard system**. It is not subtle, not restrained, and not trying to be premium in the quiet-luxury sense. Instead it weaponizes contrast: acid yellow against black, black buttons outlined in yellow, cyan utility actions, giant promo headlines, and game-launcher density spread across cinematic hero art, live news, franchise tiles, and community funnels.

The interface feels like an extension of Night City itself: aggressive, crowded, branded, and electrified. But beneath that chaos is a consistent discipline. Surfaces are mostly hard-edged black panels; every section snaps to rectangular frames; the accent vocabulary is tiny; and the same CTA grammar repeats across hero, news, and product modules. The page reads like a media network for one fictional universe rather than a single-game landing page.

The overall rhythm is: franchise header and deep nav, giant sales hero, current-news stack, universe/product gallery, newsletter capture, social/community strip, then corporate footer. It blends campaign urgency with evergreen fandom infrastructure.

**Key Characteristics:**
- Acid yellow and black inversion as the core brand contrast.
- Cyan as a secondary utility/action accent, never the main sales color.
- Hard-edged rectangles everywhere; almost no soft UI.
- Condensed uppercase promo typography for display, paired with cleaner sans body copy.
- Heavy use of logo art, platform badges, module labels, and media crops.
- Hero CTA duplication in both yellow-on-black and black-on-yellow variants.
- Footer and nav designed as franchise infrastructure, not minimal chrome.

## Colors

> **Source pages analyzed:** Cyberpunk 2077 US English homepage, including hero, news module, product-universe section, newsletter, and footer. The canonical color grammar is highly explicit in the brand art and CTA classes surfaced on the page.

### Brand & Accent
- **Cyberpunk Yellow** (`{colors.primary}` — #fcee0a): The defining franchise color. Used in logos, main CTA backgrounds, dividers, and emphasis surfaces. This is the page's dominant attention mechanic.
- **Cyberpunk Yellow Deep** (`{colors.primary-deep}` — #d7c800): Press/hover state and slightly dirtier yellow variant.
- **Cyberpunk Yellow Soft** (`{colors.primary-soft}` — #fff25c): Highlight or glow-adjacent pale yellow.
- **Scanner Cyan** (`{colors.accent-cyan}` — #00f0ff): Secondary action color used for "More news" and utility signals. Feels technical and HUD-like.
- **Scanner Cyan Deep** (`{colors.accent-cyan-deep}` — #00b7c3): Hover/active state or deeper utility border.
- **Alert Red** (`{colors.accent-red}` — #ff394a): Reserved for rare warning/error/promo moments.
- **Signal Pink** (`{colors.accent-pink}` — #ff4fd8): Optional editorial neon note, useful in universe-themed collateral.
- **Toxic Green** (`{colors.accent-toxic}` — #8bff3d): Rare tertiary tech-accent for status or speculative module treatments.

### Surface
- **Main Canvas** (`{colors.canvas}` — #000000): The foundational background. Almost everything sits on black or a black-adjacent panel.
- **Alt Canvas** (`{colors.canvas-alt}` — #090909): Slightly lifted black for lower sections.
- **Panel** (`{colors.surface-panel}` — #111111): Standard dark module panel.
- **Card Surface** (`{colors.surface-card}` — #151515): News cards and framed content tiles.
- **Overlay** (`{colors.surface-overlay}` — rgba(0,0,0,0.66)): Used over cinematic hero backgrounds so the type still punches through.
- **Glass Surface** (`{colors.surface-glass}` — rgba(10,10,10,0.82)): Useful for sticky headers or modal overlays.
- **Yellow Surface** (`{colors.surface-yellow}` — #fcee0a): Full inversion state for highlighted controls or stripe dividers.
- **Cyan Surface** (`{colors.surface-cyan}` — #00f0ff): Rare inversion state for utility emphasis.

### Text
- **Ink** (`{colors.ink}` — #000000): Text on yellow surfaces.
- **On Dark** (`{colors.on-dark}` — #ffffff): Main text on black surfaces.
- **Body Dark** (`{colors.body-dark}` — rgba(255,255,255,0.82)): Default paragraph tone.
- **Body Muted** (`{colors.body-muted}` — rgba(255,255,255,0.56)): Supporting copy and metadata.
- **Body Subtle** (`{colors.body-subtle}` — rgba(255,255,255,0.34)): Partner strip, footer utility, passive text.

### Borders & Effects
- **Divider** (`{colors.divider}` — #2b2b2b): Standard hard-line separators.
- **Divider Bright** (`{colors.divider-bright}` — #4a4a4a): More visible input and panel outlines.
- **Stroke Yellow** (`{colors.stroke-yellow}` — #fcee0a): Border for black/yellow outlined buttons.
- **Stroke Cyan** (`{colors.stroke-cyan}` — #00f0ff): Border for cyan utility CTAs.
- **Focus Ring** (`{colors.focus-ring}` — #00f0ff): Keyboard focus and accessibility highlight.
- **Hard Shadow** (`{colors.shadow-hard}`): `0 12px 24px rgba(0,0,0,0.45)` for stacked media/news depth.

## Typography

### Font Family
- **Display / Promo**: `Rajdhani, Arial Narrow, Helvetica Neue, sans-serif` or a similar condensed futuristic face. The site uses a sharp, engineered uppercase voice rather than painterly or military sci-fi type.
- **Body / Utility**: `Inter, Helvetica Neue, Arial, sans-serif`. Cleaner, neutral, and legible under dense franchise content.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.hero-display}` | 72px | 700 | 0.92 | 0.01em | Main billboard hero |
| `{typography.display-lg}` | 48px | 700 | 0.98 | 0.01em | Section hero or major campaign lockup |
| `{typography.display-md}` | 34px | 700 | 1.02 | 0.02em | Big section headers |
| `{typography.title}` | 24px | 700 | 1.08 | 0.015em | News and product titles |
| `{typography.nav-link}` | 16px | 600 | 1.1 | 0.06em | Main navigation |
| `{typography.utility}` | 14px | 600 | 1.1 | 0.08em | Small labels and metadata |
| `{typography.body-lg}` | 20px | 400 | 1.6 | 0 | Lead paragraphs |
| `{typography.body}` | 16px | 400 | 1.6 | 0 | Default body copy |
| `{typography.body-strong}` | 16px | 600 | 1.5 | 0.01em | Important body emphasis |
| `{typography.caption}` | 13px | 600 | 1.2 | 0.08em | Module labels such as `NEWS_` |
| `{typography.micro}` | 12px | 400 | 1.45 | 0.01em | Legal and consent copy |
| `{typography.button}` | 16px | 700 | 1 | 0.08em | CTA labels |

### Principles

- **Display type is engineered, not elegant.** The page wants billboard urgency and future-industrial energy.
- **Uppercase is everywhere.** Navigation, buttons, tags, and many section titles use uppercase or near-uppercase treatment.
- **Body copy is simple and readable.** The density comes from layout and branding, not overly stylized paragraph text.
- **Boldness replaces decoration.** Weight, contrast, and framing do the work that gradients and rounded chrome would do elsewhere.

## Spacing & Layout

- The layout is built from **large black chapters** with strong horizontal stacking rather than soft editorial breathing room.
- Hero and product areas rely on **wide gutters plus stacked call-to-action clusters**.
- News is displayed as a **dense media rail / grid**, with one highlighted card followed by tighter secondary cards.
- The product-universe section becomes a **franchise catalog**, each tile behaving like a sub-brand.
- Newsletter and footer shift from flashy campaign energy into **dark infrastructure mode** without leaving the brand palette.

## Components

### Header & Navigation

**`masthead`** is a large franchise header with nested menu structure: Games, Shows, News, Community, More, locale selection, and a highlighted Buy Now entry. It behaves more like a game-network shell than a simple site nav.

**`nav-link`** uses condensed semi-bold uppercase text on transparent black. The links are content-dense but visually unified by consistent spacing and casing.

**`nav-link-highlight`** is the primary commerce trigger. Yellow background, black text, hard edges, and strong uppercase label. The shape reads like a sticker slapped on a cyberpunk poster.

### Hero

**`hero-billboard`** is the signature opening section: giant logo-driven key art, one oversized headline, social-proof quotes, CTA pair, and platform strip. It should feel like a storefront takeover.

**`hero-copy`** sits over the image using a dark overlay so the message remains legible while still feeling embedded in the key art.

### Buttons

**`button-primary-yellow`** is the canonical action. High-contrast yellow fill, black text, no rounding, confident padding.

**`button-primary-black`** inverts the same grammar: black background with yellow text/border. It preserves the same silhouette so both can coexist in hero modules.

**`button-secondary-cyan`** marks utility or secondary exploration actions. Cyan is deliberately cooler and more technical than the sales yellow.

### Content Modules

**`news-card`** is a hard-edged media card with image-first layout and loud headline treatment. Cards should look like stacked tiles on a launcher homepage.

**`news-highlight`** is the lead version, often larger and paired with more visual hierarchy.

**`section-break`** is a thin but unmistakable yellow divider stripe. It acts like a voltage pulse between chapters.

**`product-universe-panel`** introduces the broader Cyberpunk universe and explains the ecosystem across game, expansion, anime, and community extensions.

**`franchise-tile`** is a full-media brand card for Cyberpunk 2077, Phantom Liberty, Edgerunners, and Edgerunners 2. Each tile includes key art, franchise logo, platform/service badges, and a Learn More action.

### Newsletter & Footer

**`newsletter-panel`** is a lead-gen section dressed in franchise styling rather than generic CRM UI. The form stays rectangular, dark, and sharp-edged.

**`text-input-dark`** is a black transparent input with visible outline and white text. It should feel like a terminal field, not a friendly consumer input.

**`checkbox-line`** carries long consent text in muted small copy without trying to beautify the legal complexity.

**`social-icon`** links are icon-only and sit in a compact network row.

**`partner-strip`** holds sponsor/partner logos like NVIDIA, Alienware, and AMD in subdued monochrome.

**`footer`** remains dense and infrastructural: legal links, language switcher, CD Projekt ecosystem links, and brand network exits.

## Do's and Don'ts

### Do
- Use `{colors.primary}` aggressively for top-level attention and purchase-driving actions.
- Keep surfaces rectilinear, sharp, and black-first.
- Let logos, key art, and platform badges take up real visual space.
- Use `{colors.accent-cyan}` for utility exploration, not primary sales actions.
- Lean into uppercase promo typography for section labels, buttons, and franchise headings.
- Maintain a sense of industrial UI density without turning the layout into clutter.

### Don't
- Don't soften the system with pills, pastel gradients, or delicate luxury spacing.
- Don't introduce many extra colors; the impact comes from yellow/black with limited neon companions.
- Don't use muted gray primary buttons. Cyberpunk actions should feel electrically obvious.
- Don't turn news or product modules into minimalist white cards. The franchise lives on dark surfaces.
- Don't make the footer too sparse; world-building and community infrastructure are part of the product.
- Don't rely on subtlety. This design language needs deliberate visual force.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Small phone | ≤ 419px | Stack hero CTAs vertically; reduce logo scale; news cards become single-column feed |
| Phone | 420–767px | Menu collapses fully; platform strip wraps; newsletter form becomes one-column |
| Tablet | 768–1023px | Hero stays cinematic but copy narrows; franchise tiles may become 2-up grid |
| Desktop | 1024–1439px | Full navigation, horizontal module rhythm, larger billboard hero |
| Large desktop | ≥ 1440px | Max hero scale, broad news rail spacing, stronger franchise-gallery presentation |

### Behavior Notes

- Mobile still needs to preserve the **yellow/black contrast violence**; scaling down should not make it polite.
- Navigation depth is high, so collapse patterns must prioritize Buy Now, core games/shows, and locale.
- Franchise logos often matter more than plain text headings and should remain legible across breakpoints.

## Content Strategy

- The homepage balances **sales urgency**, **ongoing live-service/news cadence**, and **franchise universe expansion**.
- Copy should sound punchy, promotional, and world-aware, not institutional or neutral.
- Repetition is acceptable if it reinforces campaign momentum: hero CTA, module CTA, franchise CTA.

## Sources

- Homepage: https://www.cyberpunk.net/us/en/
- Canonical page: https://www.cyberpunk.net/us/en/
