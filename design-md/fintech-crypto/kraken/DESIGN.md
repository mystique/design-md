---
version: alpha
name: Kraken
description: |
  A clean, trustworthy crypto and multi-asset exchange interface anchored by
  Kraken Purple, white surfaces, near-black text, product-card navigation, live
  market tables, proof metrics, and compliance-heavy footers. The live homepage
  verified through Lightpanda leads with "Financial freedom starts here" and
  also exposes the newer brand platform "Own the power of your money", covering
  Kraken Pro, Kraken consumer app, Krak, VIP, Institutional, Desktop, API, CLI,
  staking, markets, and education.

colors:
  primary: "#7132f5"
  primary-focus: "#5741d8"
  primary-on-dark: "#855bfb"
  purple-deep: "#5b1ecf"
  purple-subtle: "rgba(133,91,251,0.16)"
  ink: "#101114"
  body: "#101114"
  body-on-dark: "#ffffff"
  body-muted: "#9497a9"
  ink-muted-80: "#484b5e"
  ink-muted-48: "#686b82"
  divider-soft: "#dedee5"
  hairline: "rgba(104,107,130,0.24)"
  canvas: "#ffffff"
  canvas-parchment: "#f7f5ff"
  surface-pearl: "#f8f8fb"
  surface-tile-1: "#ffffff"
  surface-tile-2: "rgba(148,151,169,0.08)"
  surface-tile-3: "rgba(104,107,130,0.12)"
  surface-black: "#101114"
  surface-chip-translucent: "rgba(133,91,251,0.16)"
  success: "#149e61"
  success-dark: "#026b3f"
  success-soft: "rgba(20,158,97,0.16)"
  danger: "#d14343"
  warning: "#f5a524"
  on-primary: "#ffffff"
  on-dark: "#ffffff"

typography:
  hero-display:
    fontFamily: "Kraken-Brand, IBM Plex Sans, Helvetica, Arial, sans-serif"
    fontSize: 56px
    fontWeight: 700
    lineHeight: 1.12
    letterSpacing: -1px
  display-lg:
    fontFamily: "Kraken-Brand, IBM Plex Sans, Helvetica, Arial, sans-serif"
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.17
    letterSpacing: -1px
  display-md:
    fontFamily: "Kraken-Brand, IBM Plex Sans, Helvetica, Arial, sans-serif"
    fontSize: 36px
    fontWeight: 700
    lineHeight: 1.22
    letterSpacing: -0.5px
  lead:
    fontFamily: "Kraken-Brand, IBM Plex Sans, Helvetica, Arial, sans-serif"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 1.29
    letterSpacing: -0.5px
  lead-airy:
    fontFamily: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 22px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: 0
  tagline:
    fontFamily: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.43
    letterSpacing: 0
  body-strong:
    fontFamily: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.38
    letterSpacing: 0
  body:
    fontFamily: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.38
    letterSpacing: 0
  dense-link:
    fontFamily: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.38
    letterSpacing: 0
  caption:
    fontFamily: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: 0
  caption-strong:
    fontFamily: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.43
    letterSpacing: 0
  button-large:
    fontFamily: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.38
    letterSpacing: 0
  button-utility:
    fontFamily: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.43
    letterSpacing: 0
  fine-print:
    fontFamily: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.33
    letterSpacing: 0
  micro-legal:
    fontFamily: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0
  nav-link:
    fontFamily: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: 15px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0

rounded:
  none: 0px
  xs: 3px
  sm: 6px
  md: 8px
  lg: 12px
  pill: 9999px
  full: 50%

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 96px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-large}"
    rounded: "{rounded.lg}"
    padding: 13px 16px
  button-primary-focus:
    backgroundColor: "{colors.primary-focus}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.lg}"
  button-primary-active:
    backgroundColor: "{colors.purple-deep}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.lg}"
  button-secondary-pill:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.primary-focus}"
    typography: "{typography.button-large}"
    rounded: "{rounded.lg}"
    padding: 13px 16px
    border: "1px solid {colors.primary-focus}"
  button-dark-utility:
    backgroundColor: "{colors.surface-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button-utility}"
    rounded: "{rounded.md}"
    padding: 10px 14px
  button-pearl-capsule:
    backgroundColor: "{colors.purple-subtle}"
    textColor: "{colors.primary}"
    typography: "{typography.button-utility}"
    rounded: "{rounded.lg}"
    padding: 8px 12px
  button-store-hero:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-large}"
    rounded: "{rounded.lg}"
    padding: 14px 20px
  button-icon-circular:
    backgroundColor: "{colors.surface-tile-2}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 40px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.body}"
  text-link-on-dark:
    backgroundColor: transparent
    textColor: "{colors.primary-on-dark}"
    typography: "{typography.body}"
  global-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 72px
  sub-nav-frosted:
    backgroundColor: "{colors.surface-tile-1}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    border: "1px solid {colors.hairline}"
  product-tile-light:
    backgroundColor: "{colors.surface-tile-1}"
    textColor: "{colors.ink}"
    typography: "{typography.display-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  product-tile-parchment:
    backgroundColor: "{colors.canvas-parchment}"
    textColor: "{colors.ink}"
    typography: "{typography.display-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  product-tile-dark:
    backgroundColor: "{colors.surface-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  market-row:
    backgroundColor: "{colors.surface-tile-1}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    border: "1px solid {colors.divider-soft}"
  success-badge:
    backgroundColor: "{colors.success-soft}"
    textColor: "{colors.success-dark}"
    typography: "{typography.caption-strong}"
    rounded: "{rounded.sm}"
    padding: 4px 8px
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body-muted}"
    typography: "{typography.caption}"
    padding: 64px 24px
---

## Overview

Kraken is a crypto exchange and trading platform with a clean, trust-first visual system. The current live homepage verified through Lightpanda opens with **"Financial freedom starts here"**, a claim that millions of crypto investors trust Kraken as the best crypto platform, and a Sign up action. It also exposes a newer brand platform lower on the page: **"Own the power of your money"** with the promise "Crypto, stocks, futures, and more - trusted by millions worldwide."

The current navigation is organized around **Individuals**, **Businesses**, **VIP**, **Affiliates**, **Markets**, and **About**, with a large product mega-menu. Product lines include **Kraken Pro** ("Your all-in command center for trading"), **Kraken** ("Smart investing made easy"), **Krak** ("Send, spend, grow"), **Kraken Desktop**, **Kraken API**, **Kraken CLI**, **Kraken Institutional**, and related institutional services.

The homepage is dense with proof and market data: 666 crypto assets, 190+ countries supported, $2T+ total platform transaction volume, a Build your crypto portfolio asset carousel, staking rewards with "$800M+ in rewards earned by clients", a Kraken Pro trading interface section, "Start your crypto journey", "The command center for active traders", Kraken consumer app, Kraken VIP, Kraken Institutional, Krak global money app, Kraken CLI, spot margin, partnerships, Explore every market tables, and footer education/legal links.

The design should feel safe, modern, and product-rich. Purple is the core brand command color; white and very light surfaces keep the exchange trustworthy; compact cards, market rows, and proof metrics carry the financial product density.

## Colors

### Brand & Accent

- **Kraken Purple** (`{colors.primary}` - #7132f5): Primary CTA, brand accent, links, active states, and app/product highlights.
- **Purple Dark** (`{colors.primary-focus}` - #5741d8): Button hover/focus and outlined button text.
- **Purple Deep** (`{colors.purple-deep}` - #5b1ecf): Pressed/active and high-emphasis purple.
- **Purple Subtle** (`{colors.purple-subtle}`): Low-emphasis chip and secondary purple surface.

### Surface

- **White Canvas** (`{colors.canvas}` - #ffffff): Default marketing surface.
- **Parchment Purple Tint** (`{colors.canvas-parchment}` - #f7f5ff): Soft brand-tinted section background.
- **Pearl** (`{colors.surface-pearl}` - #f8f8fb): Cards and large content blocks.
- **Gray Soft** (`{colors.surface-tile-2}`): Secondary buttons, utility cards, and low-emphasis modules.
- **Near Black** (`{colors.surface-black}` - #101114): Dark product or hero surfaces when needed.

### Text

- **Near Black** (`{colors.ink}` - #101114): Primary headings and body text.
- **Cool Gray** (`{colors.ink-muted-48}` - #686b82): Primary neutral and borders at opacity.
- **Silver Blue** (`{colors.body-muted}` - #9497a9): Secondary text, muted elements, descriptions.
- **White** (`{colors.on-dark}`): Text on dark or purple surfaces.

### Hairlines & Borders

- **Border Gray** (`{colors.divider-soft}` - #dedee5): Dividers, table rows, card outlines.
- **Hairline** (`{colors.hairline}`): Subtle cool-gray border at 24% opacity.
- Use borders more than shadows for financial data density.

### Brand Gradient

Kraken uses purple gradients and abstract glass/ink visuals in some promotional modules, especially Kraken CLI and VIP/institutional imagery. Treat gradients as brand imagery, not as default UI surfaces. Core controls stay flat purple, white, or subtle gray.

## Typography

### Font Family

Kraken uses a dual font system: **Kraken-Brand** for display headings and **Kraken-Product** for UI, body, buttons, tables, and legal copy. Fallbacks are IBM Plex Sans, Helvetica Neue, Helvetica, and Arial.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---:|---:|---:|---:|---|
| `{typography.hero-display}` | 56px | 700 | 1.12 | -1px | Major hero statements |
| `{typography.display-lg}` | 48px | 700 | 1.17 | -1px | Homepage hero / major product sections |
| `{typography.display-md}` | 36px | 700 | 1.22 | -0.5px | Section headings |
| `{typography.lead}` | 28px | 700 | 1.29 | -0.5px | Subheads |
| `{typography.lead-airy}` | 22px | 600 | 1.2 | 0 | Feature titles |
| `{typography.body}` | 16px | 400 | 1.38 | 0 | Standard body text |
| `{typography.body-strong}` | 16px | 600 | 1.38 | 0 | Strong labels and card titles |
| `{typography.caption}` | 14px | 400 | 1.43 | 0 | Metadata and descriptions |
| `{typography.caption-strong}` | 14px | 700 | 1.43 | 0 | Badges and table emphasis |
| `{typography.fine-print}` | 12px | 400 | 1.33 | 0 | Disclosures |

### Principles

Use Kraken-Brand for headlines and Kraken-Product for everything functional. The brand display face should feel confident and sturdy; the product face should stay readable in tables, legal copy, and market rows.

Purple creates recognition; typography creates trust. Keep heading tracking tight but not dramatic. Avoid playful display treatments in regulatory or risk-heavy contexts.

### Note on Font Substitutes

If Kraken-Brand or Kraken-Product is unavailable, use IBM Plex Sans for both display and UI. Inter is acceptable for UI but loses some Kraken specificity. Preserve 700 display weight and 12px button radius.

## Layout

### Spacing System

- **Micro values:** 1px, 2px, 3px, 4px, 5px, 6px for dense market/table UI.
- **Base values:** 8px, 10px, 12px, 13px, 15px, 16px.
- **Layout values:** 20px, 24px, 25px, 32px, 48px, and 96px section spacing.
- Crypto market rows can be denser than marketing cards; hero and proof sections need more space.

### Grid & Container

The homepage combines a navigation mega-menu, centered hero, proof metrics, token carousel, staking/rewards tables, product showcase cards, product family modules, market tables, and a very large footer.

Use card grids for product families: Kraken Pro, Kraken, Krak, Desktop, VIP, Institutional, CLI. Use table/list rows for assets, prices, staking APYs, and market data.

### Whitespace Philosophy

Kraken should not feel sparse like a luxury brand. It needs enough density to communicate trading capability, but enough whitespace and consistent radii to remain trustworthy. Data tables, metrics, and legal copy are part of the brand's credibility.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat white | White canvas | Core marketing pages |
| Soft card | White/pearl with border | Product cards, asset rows |
| Whisper shadow | `rgba(0,0,0,0.03) 0 4px 24px` | Raised buttons/cards |
| Micro shadow | `rgba(16,24,40,0.04) 0 1px 4px` | Utility surfaces |
| Dark product | Near-black/purple imagery | CLI, Pro, institutional modules |

Kraken uses very subtle shadows. Use borders and white cards first; shadow should be nearly invisible.

### Decorative Depth

Decorative depth comes from product screenshots, app UI, icon grids, purple abstract forms, market tables, and exchange product imagery. Avoid fake 3D coin clutter.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---:|---|
| `{rounded.none}` | 0px | Tables and dividers |
| `{rounded.xs}` | 3px | Tiny labels |
| `{rounded.sm}` | 6px | Badges |
| `{rounded.md}` | 8px | Neutral cards |
| `{rounded.lg}` | 12px | Buttons and primary cards |
| `{rounded.pill}` | 9999px | Rare chips and tabs |
| `{rounded.full}` | 50% | Asset icons |

### Photography Geometry

Kraken relies more on product screenshots, token icons, abstract brand art, and interface panels than lifestyle photography. Asset icons are circular. Product UI screenshots should use 12px to 16px radii and remain legible.

## Components

### Top Navigation

**`global-nav`** - White nav with Individuals, Businesses, VIP, Affiliates, Markets, About, search, and language selector. Mega-menu cards expose Kraken Pro, Kraken, Krak, Desktop, API, CLI, Institutional, and related actions.

### Buttons

**`button-primary`** - Purple 12px-radius CTA. Use for Sign up, Try Kraken, Get Kraken, Get started, Start earning today.

**`button-secondary-pill`** - White outlined purple button. Use for paired secondary actions.

**`button-pearl-capsule`** - Purple-subtle chip used for category tabs, product tags, and lower-priority actions.

### Cards & Containers

**Hero card** - White or soft-purple section with Kraken-Brand display headline, Sign up CTA, app download prompt, and proof note.

**Proof metrics** - Current values include 666 crypto assets, 190+ countries supported, and $2T+ total platform transaction volume.

**Market carousel/table** - Asset rows with token icon, symbol, name, price, 24h movement, and link. Categories include Popular, Rewards, Stablecoins, Newly listed, Crypto, Spot/Margin, Futures, and Stocks.

**Rewards/staking module** - APY rows, reward disclaimers, and "$800M+ in rewards earned by clients".

**Product family cards** - Kraken Pro, Kraken consumer app, Kraken VIP, Kraken Institutional, Krak, Kraken CLI, Kraken Desktop. Each card should include logo, headline, product promise, and CTA.

**Compliance/legal blocks** - Margin, derivatives, staking, geographic restrictions, Forbes award notes, and risk disclosures are part of the page structure and need readable fine print.

### Inputs & Forms

Search and signup forms use white or pearl fields, near-black text, gray borders, and 8px to 12px radius. Social/third-party signup buttons should align to the same radius scale.

### Footer

Footer is large and link-dense. Current groups include product icons (Pro, Kraken, Krak, Desktop), Features, Company, Browse Prices, Popular Markets, Buying Guides, Crypto Education, Wallet, legal links, social links, and extensive disclaimers. Keep legal text readable and visibly separate from marketing content.

## Do's and Don'ts

### Do

- Use Kraken Purple as the primary action and link color.
- Keep buttons at 12px radius.
- Use Kraken-Brand for headings and Kraken-Product for UI/body.
- Show market data, asset rows, APYs, and platform metrics as trust proof.
- Include legal/risk disclosures where trading, staking, margin, or futures are mentioned.
- Use subtle shadows only.
- Preserve product family distinctions: Kraken Pro, Kraken, Krak, Desktop, CLI, Institutional.

### Don't

- Don't use pill buttons as the default; 12px is the main CTA radius.
- Don't introduce unrelated purple shades outside the defined scale.
- Don't make crypto visuals feel casino-like.
- Don't hide risk/legal copy.
- Don't overuse dark mode; white trust surfaces are core.
- Don't make market tables too airy; density communicates exchange utility.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---:|---|
| Mobile Small | 375px | Single-column hero and cards, compact asset rows |
| Mobile | 425-640px | Stacked product modules, horizontal scroll for markets |
| Tablet | 640-1024px | 2-column cards, compact nav |
| Desktop | 1024-1280px | Full product grids and market tables |
| Wide | 1280-1536px | Expanded containers and dense footer |

### Touch Targets

Primary buttons need at least 44px effective height. Asset rows and product cards should be tappable. Market table tabs need clear spacing.

### Collapsing Strategy

Mega-menu becomes stacked. Product grids become single-column or 2-column. Market tables scroll horizontally or simplify columns. Legal blocks remain visible below related modules.

### Image Behavior

Product screenshots should remain legible on mobile. Token icons remain circular and compact. Abstract purple visuals can crop more aggressively as long as key product messaging remains clear.

## Iteration Guide

1. Start from white canvas, near-black text, and Kraken Purple CTA.
2. Decide if the section is marketing, market data, product family, rewards, or legal.
3. Use cards for products and rows/tables for prices.
4. Keep CTAs 12px radius.
5. Add proof metrics near major conversion points.
6. Keep legal disclosures close to risk-bearing products.
7. Verify mobile market rows and footer density.

## Known Gaps

- Source capture was performed with Lightpanda against `https://www.kraken.com/` on 2026-05-17. It exposed navigation, product mega-menu, hero text, metrics, token rows, rewards/staking content, Pro/consumer/VIP/institutional/Krak/CLI modules, market tables, footer links, and legal disclaimers.
- The page includes live prices and APYs, which are time-sensitive and should not be treated as static design content.
- Computed CSS values were not fully extracted, so low-level tokens combine current homepage structure with the existing Kraken design analysis.
- Authenticated signup, app download, market sorting/filtering, and live table interactions need visual QA if pixel fidelity is required.
