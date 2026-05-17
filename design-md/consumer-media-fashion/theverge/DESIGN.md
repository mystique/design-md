---
version: alpha
name: The Verge
description: A loud, dark, magazine-meets-feed interface for technology journalism. The Verge homepage uses a near-black canvas, giant Manuka-style masthead typography, PolySans editorial headlines, mono-uppercase labels, acid mint and ultraviolet accents, rounded story cards, dense image-led feeds, and ranking modules. The live site verified through Lightpanda presents Tech, Reviews, Science, Entertainment, AI, and Policy as top-level channels, with Top Stories, Latest, Quick Posts, themed editorial packages, Most Popular, Most Discussed, and a long rolling news feed.

colors:
  primary: "#3cffd0"
  primary-focus: "#1eaedb"
  primary-on-dark: "#3cffd0"
  secondary: "#5200ff"
  secondary-dark: "#3d00bf"
  hover-link: "#3860be"
  ink: "#ffffff"
  body: "#ffffff"
  body-on-dark: "#ffffff"
  body-muted: "#949494"
  body-soft: "#e9e9e9"
  ink-on-accent: "#000000"
  ink-on-light: "#131313"
  divider-soft: "#313131"
  hairline: "#ffffff"
  canvas: "#131313"
  canvas-deep: "#000000"
  surface-slate: "#2d2d2d"
  surface-chip-translucent: "rgba(255,255,255,0.20)"
  surface-pressed: "rgba(140,140,140,0.87)"
  surface-yellow: "#ffe500"
  surface-pink: "#ff4ecd"
  surface-orange: "#ff7a00"
  surface-blue: "#3860be"
  surface-white: "#ffffff"
  overlay-black: "rgba(0,0,0,0.33)"
  on-primary: "#000000"
  on-dark: "#ffffff"

typography:
  hero-display:
    fontFamily: "Manuka, Impact, Helvetica, Arial, sans-serif"
    fontSize: 107px
    fontWeight: 900
    lineHeight: 0.8
    letterSpacing: 1.07px
  display-lg:
    fontFamily: "Manuka, Impact, Helvetica, Arial, sans-serif"
    fontSize: 90px
    fontWeight: 900
    lineHeight: 0.8
    letterSpacing: 0
  display-md:
    fontFamily: "Manuka, Impact, Helvetica, Arial, sans-serif"
    fontSize: 60px
    fontWeight: 900
    lineHeight: 0.8
    letterSpacing: 0
  lead:
    fontFamily: "PolySans, Helvetica, Arial, sans-serif"
    fontSize: 34px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0
  lead-airy:
    fontFamily: "PolySans, Helvetica, Arial, sans-serif"
    fontSize: 32px
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: 0.32px
  tagline:
    fontFamily: "PolySans, Helvetica, Arial, sans-serif"
    fontSize: 19px
    fontWeight: 300
    lineHeight: 1.2
    letterSpacing: 1.9px
  body-strong:
    fontFamily: "PolySans, Helvetica, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0
  body:
    fontFamily: "PolySans, Helvetica, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.6
    letterSpacing: 0
  dense-link:
    fontFamily: "PolySans, Helvetica, Arial, sans-serif"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0.15px
  caption:
    fontFamily: "PolySans, Helvetica, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  caption-strong:
    fontFamily: "PolySans, Helvetica, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: 1.8px
    textTransform: uppercase
  button-large:
    fontFamily: "PolySans, Helvetica, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0
  button-utility:
    fontFamily: "PolySans Mono, Courier New, Courier, monospace"
    fontSize: 12px
    fontWeight: 600
    lineHeight: 2
    letterSpacing: 1.5px
    textTransform: uppercase
  fine-print:
    fontFamily: "PolySans Mono, Courier New, Courier, monospace"
    fontSize: 11px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: 1.1px
    textTransform: uppercase
  micro-legal:
    fontFamily: "PolySans, Helvetica, Arial, sans-serif"
    fontSize: 10px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 1.5px
    textTransform: uppercase
  nav-link:
    fontFamily: "PolySans Mono, Courier New, Courier, monospace"
    fontSize: 12px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: 1.5px
    textTransform: uppercase
  serif-body:
    fontFamily: "FK Roman Standard, Georgia, serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: -0.16px

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 20px
  lg: 24px
  xl: 30px
  pill: 40px
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
  feed-gap: 16px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-large}"
    rounded: "{rounded.lg}"
    padding: 10px 24px
  button-primary-focus:
    backgroundColor: "{colors.primary-focus}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.lg}"
    border: "1px solid {colors.secondary}"
  button-primary-active:
    backgroundColor: "{colors.surface-pressed}"
    textColor: "{colors.ink-on-accent}"
    rounded: "{rounded.lg}"
  button-secondary-pill:
    backgroundColor: "{colors.surface-slate}"
    textColor: "{colors.body-soft}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 10px 24px
  button-dark-utility:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.primary}"
    typography: "{typography.button-utility}"
    rounded: "{rounded.pill}"
    padding: 10px 20px
    border: "1px solid {colors.primary}"
  button-pearl-capsule:
    backgroundColor: "{colors.surface-white}"
    textColor: "{colors.ink-on-light}"
    typography: "{typography.caption-strong}"
    rounded: "{rounded.md}"
    padding: 6px 12px
  button-store-hero:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button-utility}"
    rounded: "{rounded.xl}"
    padding: 12px 24px
  button-icon-circular:
    backgroundColor: "{colors.surface-chip-translucent}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 44px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body}"
  text-link-on-dark:
    backgroundColor: transparent
    textColor: "{colors.primary-on-dark}"
    typography: "{typography.body}"
  global-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 56px
  sub-nav-frosted:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    borderBottom: "1px solid {colors.divider-soft}"
  product-tile-light:
    backgroundColor: "{colors.surface-white}"
    textColor: "{colors.ink-on-light}"
    typography: "{typography.lead}"
    rounded: "{rounded.md}"
    padding: 24px
  product-tile-parchment:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.ink-on-accent}"
    typography: "{typography.lead}"
    rounded: "{rounded.md}"
    padding: 24px
  product-tile-dark:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.lead}"
    rounded: "{rounded.md}"
    padding: 24px
    border: "1px solid {colors.hairline}"
  story-card-accent:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.ink-on-accent}"
    typography: "{typography.lead}"
    rounded: "{rounded.md}"
    padding: 24px
  story-card-slate:
    backgroundColor: "{colors.surface-slate}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 24px
  story-image:
    backgroundColor: "{colors.divider-soft}"
    rounded: "{rounded.sm}"
    border: "1px solid {colors.divider-soft}"
  ranked-list:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    border: "1px solid {colors.hairline}"
  timeline-item:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    borderLeft: "1px solid {colors.secondary-dark}"
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body-muted}"
    typography: "{typography.caption}"
    padding: 48px 24px
---

## Overview

The Verge is a dark, loud, image-first technology publication. Its metadata describes the site as covering technology and how it makes us feel, from breaking news and reviews to features, investigations, video, and podcasts. The current homepage verified through Lightpanda is organized around top-level channels: **Tech**, **Reviews**, **Science**, **Entertainment**, **AI**, and **Policy**, with subscription and sign-in actions in the global header.

The current homepage content structure is feed-native. It opens with tabs for **Top Stories**, **Latest**, and **Following**, then leads with image-heavy story cards. Current top stories include "Mixtape is a musical portrait of teenage life", "NPR's Manoush Zomorodi talks about living with too much tech", "The app you need to clean up your computer", laptop recommendations, and a Trump Mobile story. Below that, the page moves through **The latest Quick Posts**, themed editorial packages like **Weekend reads**, **The personal software revolution**, **AI-era hacking**, and **Healthcare hoax?**, plus **Most Popular**, **Most Discussed**, and a long Latest feed.

The navigation drawer is part of the core system. It exposes deep taxonomies: Amazon, Apple, Facebook, Google, Microsoft, Samsung, Business; Smart Home Reviews, Phone Reviews, Tablet Reviews, Headphone Reviews; Space, Energy, Environment, Health; TV, Movies, Audio; OpenAI and Anthropic; Antitrust, Politics, Law, Security; Gadgets, Shopping, Gaming, Streaming, Transportation, Features, Verge Video, Podcasts, Newsletters, Archives, Store, and Product Updates.

The visual language is "tech tabloid meets club flyer": a near-black canvas, white headlines, acid mint, ultraviolet, saturated story blocks, rounded tile geometry, mono-uppercase labels, high-contrast imagery, and flat hairline borders. It should feel paced, noisy, and editorially opinionated rather than neutral or app-like.

## Colors

### Brand & Accent

- **Jelly Mint** (`{colors.primary}` - #3cffd0): The signature high-voltage accent. Use it for Subscribe CTAs, active rails, link emphasis, and major accent story tiles. It should read like hazard paint, not a soft success green.
- **Ultraviolet** (`{colors.secondary}` - #5200ff): The secondary brand shock color. Use for promo outlines, alternate story fills, rails, and high-energy section accents.
- **Deep Link Blue** (`{colors.hover-link}` - #3860be): Link hover color. It is the one calmer blue in the system and should be used for interaction feedback.
- **Focus Cyan** (`{colors.primary-focus}` - #1eaedb): Keyboard focus only. Avoid using it as a general brand accent.

### Surface

- **Canvas** (`{colors.canvas}` - #131313): The default homepage surface. The site does not feel like it has a light mode; dark is the publication identity.
- **Canvas Deep** (`{colors.canvas-deep}` - #000000): Text on mint/yellow/white tiles and maximum-depth overlays.
- **Surface Slate** (`{colors.surface-slate}` - #2d2d2d): Secondary cards, muted modules, and dark pill buttons.
- **Surface White** (`{colors.surface-white}` - #ffffff): High-contrast spotlight cards and inverted story tiles.
- **Accent story fills** (`{colors.surface-yellow}`, `{colors.surface-pink}`, `{colors.surface-orange}`, `{colors.surface-blue}`): Used as full-block story surfaces. These should be solid color fields, not gradients.

### Text

- **Ink / Body** (`{colors.ink}` / `{colors.body}` - #ffffff): Primary headlines and story text on dark surfaces.
- **Body Muted** (`{colors.body-muted}` - #949494): Bylines, dates, timestamps, comment counts, and metadata.
- **Body Soft** (`{colors.body-soft}` - #e9e9e9): Secondary button and dark-card copy.
- **Ink on Accent** (`{colors.ink-on-accent}` - #000000): Text on mint, yellow, and white surfaces.
- **Ink on Light** (`{colors.ink-on-light}` - #131313): Text on white cards that should retain a Verge dark-canvas relationship.

### Hairlines & Borders

- **Hairline** (`{colors.hairline}` - #ffffff): Story card outlines, ranked-list borders, and dark-card separation.
- **Divider Soft** (`{colors.divider-soft}` - #313131): Image frames and quiet internal dividers.
- **Secondary Dark** (`{colors.secondary-dark}` - #3d00bf): StoryStream/timeline rail and ultraviolet border variant.
- **Overlay Black** (`{colors.overlay-black}`): Subtle ring/shadow alternative where saturated cards need contained edges.

### Brand Gradient

The Verge should not use decorative gradients. Color is applied as solid blocks: mint, ultraviolet, yellow, pink, orange, blue, white, slate, or near-black. Gradients weaken the cut-paper, timeline, and club-flyer identity.

## Typography

### Font Family

The Verge uses a three-voice system:

- **Manuka** for the masthead and giant feature display. It is a shout, never normal UI.
- **PolySans** for story headlines, body, decks, navigation support, and most editorial UI.
- **PolySans Mono** for uppercase labels, timestamps, category tags, button labels, and timeline metadata.
- **FK Roman Standard** appears sparingly for magazine-like body or pull-quote moments.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---:|---:|---:|---:|---|
| `{typography.hero-display}` | 107px | 900 | 0.8 | 1.07px | Masthead / biggest feature display |
| `{typography.display-lg}` | 90px | 900 | 0.8 | 0 | Large display feature headlines |
| `{typography.display-md}` | 60px | 900 | 0.8 | 0 | Inline feature callouts |
| `{typography.lead}` | 34px | 700 | 1 | 0 | Section and module headlines |
| `{typography.lead-airy}` | 32px | 400 | 1.1 | 0.32px | Secondary feature headings |
| `{typography.tagline}` | 19px | 300 | 1.2 | 1.9px | Thin capitalized editorial labels |
| `{typography.body-strong}` | 16px | 700 | 1 | 0 | Emphasis and tight story text |
| `{typography.body}` | 16px | 500 | 1.6 | 0 | Story decks and reading copy |
| `{typography.dense-link}` | 15px | 400 | 1.2 | 0.15px | UI labels and compact headlines |
| `{typography.caption}` | 13px | 400 | 1.6 | 0 | Captions and secondary copy |
| `{typography.caption-strong}` | 12px | 400 | 1.3 | 1.8px | Uppercase kickers |
| `{typography.button-utility}` | 12px | 600 | 2 | 1.5px | Mono uppercase button labels |
| `{typography.fine-print}` | 11px | 500 | 1.2 | 1.1px | Mono timestamps |
| `{typography.micro-legal}` | 10px | 500 | 1.4 | 1.5px | Ranking metadata and legal microtext |
| `{typography.serif-body}` | 16px | 400 | 1.3 | -0.16px | Rare print-voice excerpts |

### Principles

Manuka is the identity layer. Use it only at large sizes and with extremely tight line-height. If Manuka appears below 60px, the page starts to feel like a poster system instead of The Verge.

PolySans carries the feed. Headlines are tight, direct, and often bold. Body and decks can breathe at 1.6 line-height because the surrounding layout is visually loud.

Mono-uppercase labels are essential. Timestamps, buttons, category names, rail labels, and tabs should feel like system readouts or broadcast graphics. Lowercase mono should be avoided.

### Note on Font Substitutes

Manuka, PolySans, PolySans Mono, and FK Roman Standard are proprietary or brand-specific choices. If unavailable, substitute Manuka with Anton, Bebas Neue, Oswald, or Archivo Black, but loosen line-height from 0.8 to about 0.95. Use Space Grotesk, DM Sans, or Hanken Grotesk for PolySans; Space Mono or JetBrains Mono for PolySans Mono; Newsreader or Literata for FK Roman Standard.

## Layout

### Spacing System

- **Base unit:** 8px.
- **Micro tokens:** 4px and 8px for label stacks, icon gaps, and metadata.
- **Feed tokens:** 12px to 16px between stacked story units.
- **Card padding:** 20px to 32px for story cards; 40px to 48px for major feature cards.
- **Section spacing:** 32px to 64px between editorial packages.
- **Outer margins:** about 24px on mobile and 48px on desktop.

### Grid & Container

The homepage is not a quiet card grid. It combines a masthead/nav layer, a top-story module, repeated story cards, ranked lists, themed packages, and a latest-feed column. Use a 12-column underlying grid but allow editorial modules to span irregular widths.

Current content modules to support:
- Top Stories / Latest / Following tabs.
- Hero/top-story image cards.
- Quick Posts.
- Themed packages such as Weekend reads, Personal software revolution, AI-era hacking, and Healthcare hoax.
- Most Popular and Most Discussed ranked lists.
- Latest feed with author avatars, embeds, block quotes, image galleries, and source links.
- Follow-topic onboarding chips.

### Whitespace Philosophy

Whitespace is a pacing device, not a luxury surface. The dark canvas creates silence between saturated blocks, image stacks, and ranking modules. Keep the page dense enough to feel like a newsroom, but give each package a clear reset before the next editorial beat.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat canvas | `#131313`, no shadow | Homepage background, footer, nav |
| Hairline card | 1px white or slate border | Dark story cards, ranked lists |
| Accent tile | Solid mint, ultraviolet, yellow, pink, orange, blue, or white | High-emphasis stories and promo blocks |
| Image frame | 1px `#313131` / white border | Article thumbnails and feature images |
| Rail item | Left border or timeline rule | StoryStream-style entries |
| Focus | Cyan fill/border treatment | Keyboard focus only |

The system is intentionally flat. Do not use Material-style shadows or soft floating elevation. Borders, solid color fills, and the contrast between imagery and dark canvas create all necessary depth.

### Decorative Depth

Decorative depth comes from editorial collage: image crops, saturated story fills, ranking numbers, timeline rails, comment counts, and dense metadata. The page should feel assembled from loud editorial objects rather than rendered from a generic component library.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---:|---|
| `{rounded.none}` | 0px | Masthead bands, rules, some full-bleed media |
| `{rounded.xs}` | 2px | Inputs and tight form fields |
| `{rounded.sm}` | 4px | Nested images and small media frames |
| `{rounded.md}` | 20px | Standard story cards and tags |
| `{rounded.lg}` | 24px | Primary buttons and feature cards |
| `{rounded.xl}` | 30px | Promotional outline pills |
| `{rounded.pill}` | 40px | Large outlined CTAs |
| `{rounded.full}` | 9999px | Circular icon buttons and avatars |

### Photography Geometry

The Verge uses aggressive editorial crops. Current homepage images are served with multiple crops for desktop/mobile, often 16:9, square, or vertical story-card variants. Preserve image impact: do not add soft overlays, zoom-on-hover, or decorative frames beyond the hairline border.

Images inside story cards should clip to the card geometry or use small internal radii. Author avatars are circular and small, usually 96px source crops rendered much smaller in the feed.

## Components

### Top Navigation

**`global-nav`** — Dark header with Subscribe, Sign In, wordmark, and top-level channel links: Tech, Reviews, Science, Entertainment, AI, Policy. Links use mono-uppercase or compact PolySans styling and shift toward deep link blue on hover. Subscribe should remain a mint or high-emphasis CTA.

**Navigation drawer** — Full taxonomy menu with Login / Sign Up, Search, channel groups, social links, and Subscribe. It should be dense and structured, not a minimal mobile menu. Use stacked groups with mono-uppercase headings and nested links.

### Buttons

**`button-primary`** — Jelly mint pill. Black text, 10px x 24px padding, 24px radius. Use for Subscribe and primary conversion actions.

**`button-secondary-pill`** — Dark slate pill with off-white text. Use for secondary actions on the dark canvas.

**`button-dark-utility`** — Outlined mint utility button with mono-uppercase label. Use for promotional secondary CTAs and editorial utility controls.

**`button-store-hero`** — Ultraviolet promotional pill. Use for store/subscription/promo modules when the page needs a second shock color.

**`button-icon-circular`** — Translucent circular icon button for search, menu, close, carousel, or notification controls.

### Cards & Containers

**`product-tile-dark` / dark story card** — Near-black card with white text, 20px radius, and a 1px white or slate border. Use for standard story entries that need dark continuity.

**`story-card-accent`** — Solid mint, yellow, pink, orange, ultraviolet, white, or blue card. Text flips to black or white depending on contrast. Use to interrupt the feed and create magazine-like rhythm.

**`story-card-slate`** — Slate card for secondary feed modules where a full hazard color would overpower the page.

**`ranked-list`** — Dark module for Most Popular and Most Discussed. Use large numbers, tight story headlines, author/date metadata, and clear dividers.

**`timeline-item`** — StoryStream-style feed item with a left rail, mono timestamp, rounded story body, kicker, headline, deck, and optional media. The rail should feel like a newsroom ticker.

### Inputs & Forms

Search and sign-in forms use dark fields, white text, muted placeholders, and tight 2px to 4px radii. Focus should use mint or cyan border treatment, not a glow. Error/alert states may use ultraviolet instead of a generic red.

Newsletter, account, topic-follow, and notification modules should feel like editorial utility: compact controls, dense text, and high-contrast buttons.

### Footer

The footer is dark and utility-heavy. Current footer includes social links, Contact, Tip Us, Community Guidelines, Archives, About, Ethics Statement, How We Rate and Review Products, Cookie Settings, Terms of Use, Privacy Notice, Cookie Policy, Licensing FAQ, Accessibility, Platform Status, and Vox Media copyright. Keep it dense and straightforward.

## Do's and Don'ts

### Do

- Use the near-black canvas as the dominant page surface.
- Keep Subscribe and primary CTAs in jelly mint.
- Use ultraviolet and saturated fills as hard editorial interruptions.
- Use Manuka only for masthead and large feature display.
- Use mono-uppercase for navigation labels, timestamps, buttons, and rankings.
- Preserve image-led story cards and aggressive crops.
- Build ranked lists and feed modules as first-class components.
- Let story packages have strong titles and subtitles, such as "Weekend reads / Catch up on our favorite stories of the week."
- Use flat borders instead of shadows.

### Don't

- Don't make the page light, airy, or minimal.
- Don't replace saturated story tiles with gray SaaS cards.
- Don't use decorative gradients.
- Don't animate images with zoom or parallax on hover.
- Don't use Manuka for small labels or buttons.
- Don't remove metadata; authors, dates, comment counts, and source labels are part of the system.
- Don't make the navigation drawer sparse. The depth of the taxonomy matters.
- Don't soften the brand with rounded beige cards or pastel tints.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---:|---|
| Mobile | < 768px | Header compresses, drawer carries taxonomy, story cards stack, ranked modules become single-column |
| Tablet | 768-1024px | Top tabs remain visible, packages can use 2-column layouts, nav reduces visible channels |
| Desktop | 1024-1300px | Full top nav, multi-card top story layout, ranked modules alongside feed |
| Wide | > 1300px | Preserve max feed width; do not stretch story cards into unreadable lines |

### Touch Targets

Subscribe, menu, search, close, auth, and topic chips should be at least 40px tall where possible. Story cards can be full-card links, but author/source links must remain separately tappable.

### Collapsing Strategy

Story packages collapse from mixed editorial grids into stacked cards. Top Stories / Latest / Following tabs remain near the top. Large display type and masthead scale down aggressively while preserving the compressed, loud character.

Most Popular and Most Discussed become vertical ranked modules. Latest feed entries preserve author avatar, timestamp, headline, and media order.

### Image Behavior

Use alternate crops instead of simply shrinking desktop images. Maintain meaningful subjects in story thumbnails. Square and vertical crops are acceptable on mobile; wide cinematic crops work better in top-story and package modules.

## Iteration Guide

1. Start with the dark canvas, white text, and mono-uppercase nav.
2. Add one high-voltage accent at a time: mint first, ultraviolet second, other solids only for story cards.
3. Choose the story module type: top story, quick post, package card, ranked item, timeline/latest item, or follow-topic chip.
4. Preserve editorial metadata: author, date/time, comment count, source, and deck.
5. Keep image crops strong and static.
6. Use borders and solid fills for depth; avoid shadows.
7. Check mobile density early so the drawer, ranked lists, and latest feed remain scannable.
8. Use the current channel taxonomy when building menus or footer areas.

## Known Gaps

- Source capture was performed with Lightpanda against `https://www.theverge.com/` on 2026-05-17. The capture exposed current navigation, drawer taxonomy, homepage modules, story titles, authors, comments, package headings, topic-follow prompts, notifications drawer, and footer links.
- Computed CSS values were not fully extracted, so typography/color tokens combine the existing The Verge design analysis with the current homepage content and structure.
- The live homepage is news-driven and changes frequently. Article titles and package order should be treated as date-specific examples, not permanent content.
- Visual details such as exact masthead SVG geometry, hover transitions, ad placements, and authenticated Following/Notifications states require browser visual QA if pixel-level reproduction is needed.
