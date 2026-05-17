---
version: alpha
name: Mastercard
description: A warm, rounded, editorial payments interface built from a putty-cream canvas, MarkForMC typography, ink-black CTAs, circular image portraits, giant stadium media frames, and orbital orange trajectory lines. The live US homepage verified through Lightpanda leads with "Powering economies and empowering people" and organizes the brand around For you, For business, For the world, For innovators, and News and trends.

colors:
  primary: "#141413"
  primary-focus: "#262627"
  primary-on-dark: "#F3F0EE"
  brand-red: "#EB001B"
  brand-yellow: "#F79E1B"
  signal-orange: "#CF4500"
  signal-orange-light: "#F37338"
  clay-brown: "#9A3A0A"
  link-blue: "#3860BE"
  ink: "#141413"
  body: "#141413"
  body-on-dark: "#ffffff"
  body-muted: "#696969"
  ink-muted-80: "#262627"
  ink-muted-48: "#696969"
  divider-soft: "#D1CDC7"
  hairline: "rgba(20,20,19,0.20)"
  canvas: "#F3F0EE"
  canvas-parchment: "#F3F0EE"
  surface-pearl: "#FCFBFA"
  surface-tile-1: "#FFFFFF"
  surface-tile-2: "#F4F4F4"
  surface-tile-3: "#E8E2DA"
  surface-black: "#141413"
  surface-chip-translucent: "rgba(255,255,255,0.88)"
  on-primary: "#F3F0EE"
  on-dark: "#ffffff"

typography:
  hero-display:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 64px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: -1.28px
  display-lg:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 44px
    fontWeight: 500
    lineHeight: 1.12
    letterSpacing: -0.88px
  display-md:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 36px
    fontWeight: 500
    lineHeight: 1.22
    letterSpacing: -0.72px
  lead:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 28px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: -0.56px
  lead-airy:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 24px
    fontWeight: 450
    lineHeight: 1.35
    letterSpacing: -0.24px
  tagline:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0.56px
    textTransform: uppercase
  body-strong:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.35
    letterSpacing: -0.32px
  body:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 450
    lineHeight: 1.4
    letterSpacing: 0
  dense-link:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: -0.48px
  caption:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 450
    lineHeight: 1.45
    letterSpacing: 0
  caption-strong:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0.56px
    textTransform: uppercase
  button-large:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: -0.32px
  button-utility:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0.13px
  fine-print:
    fontFamily: "MarkOffcForMC, MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 450
    lineHeight: 1.35
    letterSpacing: 0
  micro-legal:
    fontFamily: "MarkOffcForMC, MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.35
    letterSpacing: 0
  nav-link:
    fontFamily: "MarkForMC, SofiaSans, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: -0.48px

rounded:
  none: 0px
  xs: 8px
  sm: 20px
  md: 24px
  lg: 40px
  pill: 999px
  full: 1000px

spacing:
  xxs: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  xxl: 64px
  section: 96px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-large}"
    rounded: "{rounded.sm}"
    padding: 6px 24px
    border: "1.5px solid {colors.primary}"
  button-primary-focus:
    backgroundColor: "{colors.primary-focus}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
  button-primary-active:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
  button-secondary-pill:
    backgroundColor: "{colors.surface-tile-1}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.sm}"
    padding: 6px 24px
    border: "1.5px solid {colors.ink}"
  button-dark-utility:
    backgroundColor: "{colors.signal-orange}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button-utility}"
    rounded: "{rounded.md}"
    padding: 4px 30px
  button-pearl-capsule:
    backgroundColor: "{colors.surface-pearl}"
    textColor: "{colors.ink-muted-80}"
    typography: "{typography.caption}"
    rounded: "{rounded.pill}"
    padding: 8px 20px
  button-store-hero:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-large}"
    rounded: "{rounded.lg}"
    padding: 16px 40px
  button-icon-circular:
    backgroundColor: "{colors.surface-chip-translucent}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 56px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.link-blue}"
    typography: "{typography.body}"
  text-link-on-dark:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
  global-nav:
    backgroundColor: "{colors.surface-tile-1}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 72px
    rounded: "{rounded.pill}"
  sub-nav-frosted:
    backgroundColor: "{colors.surface-tile-1}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.pill}"
  product-tile-light:
    backgroundColor: "{colors.surface-tile-1}"
    textColor: "{colors.ink}"
    typography: "{typography.display-md}"
    rounded: "{rounded.lg}"
    padding: 48px
  product-tile-parchment:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-md}"
    rounded: "{rounded.lg}"
    padding: 48px
  product-tile-dark:
    backgroundColor: "{colors.surface-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-md}"
    rounded: "{rounded.lg}"
    padding: 48px
  hero-media-frame:
    backgroundColor: "{colors.surface-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    rounded: "{rounded.lg}"
    padding: 64px
  circular-portrait-card:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.lead}"
    rounded: "{rounded.full}"
  satellite-cta:
    backgroundColor: "{colors.surface-tile-1}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 56px
  footer:
    backgroundColor: "{colors.surface-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.caption}"
    padding: 100px 48px 148px
---

## Overview

Mastercard's US homepage is a warm institutional brand magazine for a global payments technology company. Its metadata states the core promise directly: Mastercard connects and powers a digital economy that benefits people, businesses, and governments worldwide by making transactions safe, simple, and accessible. The current live homepage verified through Lightpanda leads with **"Powering economies and empowering people"** and the supporting line **"Unlocking potential for people, businesses and governments, all around the world."**

The current top navigation is organized by audience and intent: **For you**, **For business**, **For the world**, **For innovators**, and **News and trends**. The menu depth is substantial. For you includes Find a card, Ways to pay, Protecting you, Get support, and Experience Mastercard. For business includes Consumer payments, Commercial payments, Money movement, Open finance, Advisors & transformation, Cybersecurity & fraud prevention, Consumer acquisition & engagement, Insights & intelligence, and AI. For the world covers corporate impact, people, prosperity, planet, and about Mastercard. For innovators covers developers, digital labs, Start Path, Engage, Product Express, research, and experience centers.

The homepage content combines hero video, featured content, editorial story pills, business/government solution portraits, cards and benefits, Priceless experiences, company news, and a dark footer. Current featured content includes the Mastercard Partner Advantage Program, the State of Open Finance 2026 report, and a cyber-fraud report. Current story cards include Smarter subscriptions, Wiring the world, Travel influencers, New travel equation, Emerging tech, and repeated "Mastercard Agent pay" carousel entries.

The visual system is defined by a warm cream canvas, pill navigation, oversized rounded media frames, circular portraits, satellite CTAs, black primary buttons, burnt-orange utility/consent actions, and orbital orange arcs. It should feel premium and human, but still infrastructural: a payments network rendered as an ecosystem of connected services.

## Colors

### Brand & Accent

- **Brand Red** (`{colors.brand-red}` - #EB001B): The left circle of the Mastercard mark. Use only in the logo or sanctioned brand marks, not as a general UI color.
- **Brand Yellow** (`{colors.brand-yellow}` - #F79E1B): The right circle of the Mastercard mark. Use only in the logo or official brand contexts.
- **Ink Black** (`{colors.primary}` / `{colors.ink}` - #141413): Primary text, body CTAs, dark footer, and high-contrast surfaces. It is warm and slightly softened against the cream canvas.
- **Signal Orange** (`{colors.signal-orange}` - #CF4500): Legal/consent and small attention actions. Use sparingly; it is not the main marketing CTA color.
- **Light Signal Orange** (`{colors.signal-orange-light}` - #F37338): Orbital arcs, active carousel indicators, and small decorative motion cues.
- **Link Blue** (`{colors.link-blue}` - #3860BE): Inline links and informational references where a recognizable web link is needed.

### Surface

- **Canvas Cream** (`{colors.canvas}` - #F3F0EE): Default page background. It should never be replaced with sterile white in main editorial sections.
- **Surface Pearl** (`{colors.surface-pearl}` - #FCFBFA): Raised cream-white panels, light cards, and paper-on-paper hierarchy.
- **White** (`{colors.surface-tile-1}` - #FFFFFF): Floating navigation pill, satellite CTAs, secondary button fills, and modal/card surfaces.
- **Soft Bone** (`{colors.surface-tile-2}` - #F4F4F4): Cool-light subregions, form backgrounds, and low-emphasis panel fills.
- **Cream Watermark** (`{colors.surface-tile-3}` - #E8E2DA): Ghost headline text and very soft background lettering behind circular portraits.
- **Surface Black** (`{colors.surface-black}` - #141413): Footer and dark media surfaces.

### Text

- **Ink** (`{colors.ink}` - #141413): Primary headline and body text on cream.
- **Charcoal** (`{colors.ink-muted-80}` - #262627): Alternate dark text for body copy and secondary emphasis.
- **Slate Gray** (`{colors.body-muted}` - #696969): Muted labels, disabled states, bottom-row privacy text, and secondary metadata.
- **Dust Taupe** (`{colors.divider-soft}` - #D1CDC7): Whisper text, low-contrast placeholders, and soft dividers.
- **On Primary** (`{colors.on-primary}` - #F3F0EE): Text on ink-black CTAs.
- **On Dark** (`{colors.on-dark}` - #ffffff): Footer text and text over dark video/media.

### Hairlines & Borders

- **Hairline** (`{colors.hairline}`): Soft ink border for buttons, cards, search fields, and light panels.
- **Divider Soft** (`{colors.divider-soft}`): Footer dividers, disabled text, and paper-like separations.
- **White-at-opacity borders** should be used on dark footer selectors and language/country controls.

### Brand Gradient

Mastercard's core UI does not rely on programmatic gradients. The sense of warmth and motion comes from photography, circular masks, cream-on-cream watermark text, soft shadows, and orange orbital lines. Do not use red-to-yellow Mastercard logo gradients as section backgrounds.

## Typography

### Font Family

Mastercard uses **MarkForMC** across the marketing system: headlines, body copy, nav links, CTAs, cards, and footer. **MarkOffcForMC** appears in legal or official text contexts. The fallback stack should be `SofiaSans, Arial, sans-serif`, with Sofia Sans preferred because it preserves the soft geometric feel.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---:|---:|---:|---:|---|
| `{typography.hero-display}` | 64px | 500 | 1 | -1.28px | Homepage hero headline |
| `{typography.display-lg}` | 44px | 500 | 1.12 | -0.88px | Major section heads |
| `{typography.display-md}` | 36px | 500 | 1.22 | -0.72px | Section titles and ghost headings |
| `{typography.lead}` | 28px | 500 | 1.2 | -0.56px | Card lead titles |
| `{typography.lead-airy}` | 24px | 450 | 1.35 | -0.24px | Large body statements |
| `{typography.tagline}` | 14px | 700 | 1 | 0.56px | Uppercase eyebrow labels |
| `{typography.body-strong}` | 16px | 500 | 1.35 | -0.32px | Strong body and button-adjacent copy |
| `{typography.body}` | 16px | 450 | 1.4 | 0 | Default body copy |
| `{typography.dense-link}` | 16px | 500 | 1 | -0.48px | Navigation and compact link labels |
| `{typography.caption}` | 14px | 450 | 1.45 | 0 | Footer links and card metadata |
| `{typography.caption-strong}` | 14px | 700 | 1 | 0.56px | Footer column headers and labels |
| `{typography.button-large}` | 16px | 500 | 1 | -0.32px | Primary and secondary CTAs |
| `{typography.button-utility}` | 13px | 400 | 1.2 | 0.13px | Consent and legal utility buttons |
| `{typography.fine-print}` | 12px | 450 | 1.35 | 0 | Footer privacy text |
| `{typography.micro-legal}` | 11px | 400 | 1.35 | 0 | Legal microcopy |

### Principles

Weight 450 is important. It creates the slightly soft, institutional reading texture that separates Mastercard from generic corporate sans typography. Use 500 for headlines and navigation, 450 for body and footer links, 700 only for uppercase eyebrow labels.

Headlines use tight negative tracking around -2%. Body copy does not need negative tracking. Uppercase tracking is reserved for eyebrow labels and footer headers, often paired with a tiny orange dot.

Do not add a second display face. The brand's contrast comes from radius, imagery, circular composition, and weight/spacing, not from typeface mixing.

### Note on Font Substitutes

MarkForMC is proprietary. If unavailable, use **Sofia Sans** first, then Inter, Geist, or Neue Haas Grotesk. Preserve the 450-like body tone where possible through variable font weights. If a substitute cannot render 450, use 400 for body and keep headline letter-spacing tight.

## Layout

### Spacing System

- **Base unit:** 8px.
- **Small tokens:** 4px and 8px for icon/label spacing.
- **Component tokens:** 16px, 24px, 32px, and 48px for buttons, cards, and media interiors.
- **Section tokens:** 96px for major section rhythm; 64px for mobile/compact sections.
- **Hero/media gutters:** large rounded media should sit in from viewport edges with generous 24px to 48px margins.

### Grid & Container

Mastercard uses centered, editorial containers rather than dense dashboards. The homepage currently combines a floating audience nav, hero video, featured content links, horizontal pill story carousel, business/government solution orbit cards, cards-and-benefits blocks, Priceless video, company news, and a large footer.

Business solution cards should be arranged as connected circular portraits rather than a standard grid. Footer content uses a large headline above a multi-column link layout: Need help, Company, Legal & Privacy, and Mastercard Sites.

### Whitespace Philosophy

Whitespace should feel like premium report paper. The warm cream canvas carries large empty areas comfortably, especially around circular portraits and orbital lines. Avoid crowded fintech dashboard density. Mastercard should read as calm infrastructure, not a transactional app screen.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Canvas | Warm cream, no shadow | Main page background |
| Paper lift | Pearl/white surface with soft shadow | Floating nav, cards, satellite CTAs |
| Stadium media | Large rounded video/image frame, no heavy border | Hero and media sections |
| Circular portrait | Cropped image circle, optional soft shadow | Solution/service cards |
| Dark footer | Warm black surface | Footer and dark brand blocks |
| Consent/modal | White card with orange utility action | Cookie and legal flows |

Depth is soft and sparse. Use `rgba(0,0,0,0.04) 0 4px 24px` for floating nav or light cards, and stronger `rgba(0,0,0,0.08) 0 24px 48px` only under large pill/circular media when needed. Do not use harsh card shadows.

### Decorative Depth

The most distinctive decorative depth is orbital: thin orange lines arc between circular portraits, and white satellite CTAs dock onto image circles. Cream-on-cream ghost headings may sit behind foreground portraits. These should imply trajectory and connected services, not decoration for its own sake.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---:|---|
| `{rounded.none}` | 0px | Rare utility dividers |
| `{rounded.xs}` | 8px | Small inputs and compact panels |
| `{rounded.sm}` | 20px | Standard ink and outline CTAs |
| `{rounded.md}` | 24px | Orange consent pills and medium cards |
| `{rounded.lg}` | 40px | Hero media frames and large stadium cards |
| `{rounded.pill}` | 999px | Floating nav, chips, search fields |
| `{rounded.full}` | 1000px / 50% | Circular portraits, satellite CTAs, icon buttons |

### Photography Geometry

Mastercard uses photography through strong masks. Hero video/image frames should use wide stadium corners. Business/service imagery should be circular or pill-shaped. Current business solution examples include Insights & Intelligence, Consumer and Commercial Payments, Money Movement, Cybersecurity & Fraud Prevention, Consumer Acquisition & Engagement, and Open Finance.

Square or sharp-cornered service imagery should be avoided. If a source image is rectangular, crop it into a circle or pill and preserve meaningful subject placement.

## Components

### Top Navigation

**`global-nav`** — Floating white pill navigation with Mastercard symbol at left, audience links in the center, and menu/search controls. Current primary links are For you, For business, For the world, For innovators, and News and trends. The nav should feel docked above the cream canvas rather than pinned as a flat bar.

**Mega menu** — Audience-based, deep, link-heavy overlay. Preserve the current structure: personal card/payment/support links, business solution links, impact/about links, innovator/developer links, and newsroom/investor links. Search suggestions include Find a card, AI, Cybersecurity & Fraud Prevention, Insights & Intelligence, Personalization, Money Movement, Commercial Payments, Open Finance, and Digital Assets.

### Buttons

**`button-primary`** — Ink-black pill. Use for marketing CTAs such as Learn more, Explore, Discover, Register now, Start, and body-level actions. Text should be cream, not stark white.

**`button-secondary-pill`** — White pill with ink border. Use for secondary actions paired with a primary.

**`button-dark-utility`** — Signal-orange pill for cookie, privacy, consent, and legal confirmation flows. Do not use it as the main marketing CTA.

**`button-icon-circular` / `satellite-cta`** — White circular arrow button attached to circular portraits or used for carousel/media controls. Keep it perfectly round and visually docked to another circular/pill element.

### Cards & Containers

**`hero-media-frame`** — Wide, dark, rounded video/image frame with 40px corners. Current hero contains a video player fallback and the headline "Powering economies and empowering people."

**Featured content card/list** — Compact editorial links for current featured content: Mastercard Partner Advantage Program, the State of Open Finance 2026 report, and a cyber-fraud integration report.

**Horizontal pill story card** — Rounded story tiles for Smarter subscriptions, Wiring the world, Travel influencers, New travel equation, Emerging tech, and Mastercard Agent pay. Use full-bleed imagery and small Story/Report labels.

**`circular-portrait-card`** — Business solution module with circular imagery, eyebrow label, title, and satellite CTA. Pair with light orange orbit lines.

**Benefits cards** — Cards and benefits section includes "Benefits and services that support your ambitions", "Find a card that's right for you", and "Pay your way". These should remain warm, rounded, and consumer-facing.

**Priceless video block** — Passion/experience module with video poster and functional-cookie fallback. Maintain premium media treatment and clear external link to priceless.com.

### Inputs & Forms

Search starts as a circular icon control and expands into a rounded pill input. Use a white field, ink text, soft ink border, and 999px radius. Footer country/language controls use dark surface, white text, white-at-opacity border, and pill shape.

Consent and privacy flows may use third-party-looking controls, but the primary action should use signal orange and the legal UI should remain visibly distinct from marketing CTAs.

### Footer

**`footer`** — Dark warm-black footer headed by "We're always here when you need us." Link groups are Need help, Company, Legal & Privacy, and Mastercard Sites. Current footer includes Get support, Report a lost or stolen card, Find ATM, FAQs, About, Careers, Newsroom, Investor Relations, Privacy & Data Responsibility, trademarks, BCRs, California Privacy Notice, Modern Slavery Statement, Priceless.com, Mastercard Business Intelligence, Mastercard Developers, Mastercard Marketing Center, and Center for Inclusive Growth. Bottom row includes copyright, Privacy, Terms, Manage cookies, Your Privacy Choices, and social links for LinkedIn, Facebook, X, and YouTube.

## Do's and Don'ts

### Do

- Use the warm cream canvas as the foundation.
- Use the Mastercard red/yellow circles only in the logo or official brand mark.
- Use black/ink CTAs for marketing actions.
- Reserve signal orange for consent, small attention cues, and orbital decoration.
- Use generous rounded corners: 20px, 24px, 40px, and full circles.
- Crop service/solution imagery into circles or pills.
- Attach satellite CTAs to circular portraits where appropriate.
- Preserve the audience-based nav taxonomy.
- Use MarkForMC/Sofia Sans with 450 body weight and tight headline tracking.

### Don't

- Don't turn brand red and yellow into generic UI button colors.
- Don't replace the cream canvas with pure white.
- Don't make service cards square.
- Don't use sharp-cornered media frames in hero sections.
- Don't overuse orange as a CTA color.
- Don't introduce fintech dashboard density.
- Don't add hard shadows or glassmorphism.
- Don't use a second display font for contrast.
- Don't remove footer utility links; support and legal access are part of the product surface.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---:|---|
| Mobile | < 768px | Floating nav collapses to logo/menu/search, hero type shrinks, circular cards stack |
| Tablet | 768-1024px | Pill nav tightens, carousel remains horizontal, solution cards become 2-up |
| Desktop | 1024-1440px | Full floating nav, large hero frame, connected portrait/orbit layouts |
| Wide | > 1440px | Keep max container width; allow orbital lines and cream whitespace to expand |

### Touch Targets

Buttons and nav controls should be at least 40px high. Circular icon/satellite controls should be 48px to 60px. Carousel controls, video play, search, menu, and footer selectors need clear touch hit areas.

### Collapsing Strategy

Hero media remains rounded but reduces from 40px corners if needed on small screens. Circular portrait cards stack vertically and may drop orbital lines if they become confusing. The mega-menu becomes a full-screen stacked audience menu. Footer columns stack under the large support headline.

### Image Behavior

Use alternate crops rather than shrinking circles until subjects are illegible. Hero video/image should preserve the stadium feel. Portrait cards should remain circular at all breakpoints, with satellite CTAs either docked or moved directly below if space is too tight.

## Iteration Guide

1. Start with cream canvas, ink text, and a floating white pill nav.
2. Use audience-first navigation: For you, For business, For the world, For innovators, News and trends.
3. Use black CTAs for marketing actions; keep orange for legal/consent and orbit cues.
4. Build media from stadiums, circles, and pills before considering rectangles.
5. Pair service circles with satellite CTAs and orange arcs when the layout supports it.
6. Preserve current content modules: hero, featured content, story carousel, business solutions, cards/benefits, Priceless, company news, footer.
7. Check mobile early; circles, satellite buttons, and orbit lines can crowd quickly.
8. Keep footer support/legal links visible and structured.

## Known Gaps

- Source capture was performed with Lightpanda against `https://www.mastercard.com/` on 2026-05-17. The site redirected to the US English homepage and exposed current navigation, mega-menu links, hero content, featured content, story cards, business solution modules, cards/benefits, Priceless section, company news, and footer.
- Computed CSS values were not fully extracted, so low-level typography, radius, and color tokens combine current page content with the existing Mastercard design analysis.
- Video playback, carousel motion, orbit-line geometry, cookie-modal styling, and expanded search behavior require visual browser QA for pixel-level fidelity.
