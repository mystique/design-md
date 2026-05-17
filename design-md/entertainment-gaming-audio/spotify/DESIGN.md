---
version: alpha
name: Spotify
description: |
  Spotify's current web language splits into two connected modes: a bright,
  oversized Premium marketing site and the dark, dense Spotify Web Player at
  open.spotify.com. Premium is a campaign page for "The ultimate home for
  music, artists, fans, live events, videos" with a 2026 offer of 3 months for
  $0, plan cards, editorial image modules, and large stacked-word headlines.
  The Web Player is the familiar near-black content browser: Trending songs,
  Popular artists, albums, radio, charts, album artwork grids, sidebar
  navigation, and a Premium upsell banner. Both modes share Spotify's compact
  typography, pill/circle control language, global footer taxonomy, and green
  brand accent, but they use color and density very differently.

colors:
  spotify-green: "#1ed760"
  spotify-green-dark: "#1db954"
  black: "#000000"
  near-black: "#121212"
  app-surface: "#181818"
  app-surface-raised: "#1f1f1f"
  app-card: "#252525"
  app-card-hover: "#2a2a2a"
  app-border: "#4d4d4d"
  text-base: "#ffffff"
  text-subdued: "#b3b3b3"
  text-muted: "#a7a7a7"
  text-bright-secondary: "#cbcbcb"
  marketing-canvas: "#ffffff"
  marketing-ink: "#000000"
  marketing-green-surface: "#1ed760"
  marketing-lime: "#cff56a"
  marketing-pink: "#ffcdd2"
  marketing-blue: "#509bf5"
  marketing-purple: "#af2896"
  marketing-card: "#f4f4f4"
  plan-card: "#121212"
  plan-divider: "#ffffff33"
  negative: "#f3727f"
  warning: "#ffa42b"
  announcement: "#539df5"
  shadow-heavy: "rgba(0,0,0,0.5)"
  shadow-medium: "rgba(0,0,0,0.3)"

typography:
  hero-marketing:
    fontFamily: SpotifyMixUITitle
    fallback: CircularSp, Helvetica Neue, Helvetica, Arial, sans-serif
    fontSize: 72px
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: -1px
  display-marketing:
    fontFamily: SpotifyMixUITitle
    fontSize: 56px
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: -0.5px
  section-title:
    fontFamily: SpotifyMixUITitle
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: 0
  app-section-title:
    fontFamily: SpotifyMixUITitle
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0
  card-title:
    fontFamily: SpotifyMixUI
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.35
    letterSpacing: 0
  body:
    fontFamily: SpotifyMixUI
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-sm:
    fontFamily: SpotifyMixUI
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  label:
    fontFamily: SpotifyMixUI
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0
  button:
    fontFamily: SpotifyMixUI
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0
  uppercase-button:
    fontFamily: SpotifyMixUI
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: 1.4px
    textTransform: uppercase
  caption:
    fontFamily: SpotifyMixUI
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  micro:
    fontFamily: SpotifyMixUI
    fontSize: 10px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0

spacing:
  none: 0
  hairline: 1px
  xxs: 2px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 24px
  xxl: 32px
  section: 64px
  marketing-section: 96px
  app-sidebar: 280px
  player-bar: 90px
  card-gap: 16px
  page-gutter-mobile: 24px
  page-gutter-desktop: 40px

rounded:
  none: 0
  xs: 2px
  sm: 4px
  card: 8px
  panel: 12px
  pill: 500px
  full-pill: 9999px
  circle: 50%

elevation:
  none: none
  card-hover: "rgba(0,0,0,0.3) 0 8px 8px"
  dialog: "rgba(0,0,0,0.5) 0 8px 24px"
  input-inset: "rgb(18,18,18) 0 1px 0, rgb(124,124,124) 0 0 0 1px inset"
  marketing-soft: "0 8px 24px rgba(0,0,0,0.12)"

components:
  premium-header:
    backgroundColor: "{colors.marketing-canvas}"
    textColor: "{colors.marketing-ink}"
    logo: Spotify wordmark
    nav: Premium plans, Support, Download, Sign up, Log in
    primaryCta: Try 3 months for $0
    rounded: "{rounded.none}"
  premium-hero:
    backgroundColor: "{colors.marketing-canvas}"
    textColor: "{colors.marketing-ink}"
    typography: "{typography.hero-marketing}"
    headlineFragments: music, artists, fans, live events, videos
    cta: Try 3 months for $0
    legalCopy: Premium Individual only, $12.99/month after, offer ends July 6 2026
  premium-feature-list:
    backgroundColor: "{colors.marketing-canvas}"
    textColor: "{colors.marketing-ink}"
    items: Ad-free music listening, Lossless music, Offline listening, Full control
    badge: Premium
  premium-plan-card:
    backgroundColor: "{colors.plan-card}"
    textColor: "{colors.text-base}"
    accentColor: "{colors.spotify-green}"
    rounded: "{rounded.panel}"
    plans: Individual, Student, Duo, Family, Audiobooks Access
    ctaStyle: pill
  web-player-shell:
    backgroundColor: "{colors.near-black}"
    textColor: "{colors.text-base}"
    layout: sidebar + main content + player bar
    nav: Home, Search, Your Library, Premium
    rounded: "{rounded.none}"
  premium-upsell-banner:
    backgroundColor: "{colors.app-surface-raised}"
    textColor: "{colors.text-base}"
    cta: Try 3 months for $0
    secondaryCta: View all plans
    rounded: "{rounded.card}"
  content-section:
    backgroundColor: "{colors.near-black}"
    textColor: "{colors.text-base}"
    titleTypography: "{typography.app-section-title}"
    sections: Trending songs, Popular artists, Popular albums and singles, Popular radio, Featured Charts
  media-card:
    backgroundColor: transparent
    hoverBackgroundColor: "{colors.app-card-hover}"
    textColor: "{colors.text-base}"
    subtitleColor: "{colors.text-subdued}"
    mediaRatio: "1 / 1"
    rounded: "{rounded.card}"
    shadow: "{elevation.none}"
  artist-card:
    backgroundColor: transparent
    imageShape: "{rounded.circle}"
    textColor: "{colors.text-base}"
  play-button:
    backgroundColor: "{colors.spotify-green}"
    textColor: "{colors.black}"
    rounded: "{rounded.circle}"
    shadow: "{elevation.card-hover}"
  pill-button:
    backgroundColor: "{colors.text-base}"
    textColor: "{colors.black}"
    rounded: "{rounded.full-pill}"
    typography: "{typography.button}"
    padding: "12px 32px"
  dark-pill:
    backgroundColor: "{colors.app-surface-raised}"
    textColor: "{colors.text-base}"
    rounded: "{rounded.full-pill}"
    padding: "8px 16px"
  search-input:
    backgroundColor: "{colors.app-surface-raised}"
    textColor: "{colors.text-base}"
    placeholderColor: "{colors.text-subdued}"
    rounded: "{rounded.pill}"
    padding: "12px 96px 12px 48px"
    shadow: "{elevation.input-inset}"
  footer:
    backgroundColor: "{colors.black}"
    textColor: "{colors.text-subdued}"
    linkColor: "{colors.text-base}"
    columns: Company, Communities, Useful links, Spotify Plans
---

## Overview

Spotify currently needs to be modeled as two related surfaces, not one. The Premium page at `spotify.com/us/premium/` is a bright marketing experience with oversized stacked-word headlines, a hero offer of **3 months for $0**, plan cards, cultural/event imagery, and a long footer. The Web Player at `open.spotify.com` is the dense dark app: trending songs, popular artists, albums, radio, charts, album art grids, sidebar navigation, a Premium upsell, and language selection.

The old file described only the dark player. That is still essential, but it misses the current Premium campaign language: "The ultimate home for music, artists, fans, live events, videos"; "Take us with you anywhere"; "With music that never stops"; "Fresh ways to discover music"; "The best place to listen with your crew"; and plan cards for Individual, Student, Duo, Family, and Audiobooks Access.

The shared identity comes from Spotify's compact sans typography, pill buttons, circular play controls, green action color, global footer taxonomy, and content-first color strategy. The difference is polarity: Premium uses white/green/campaign imagery and big expressive headlines; Open uses near-black surfaces and lets album art provide color.

**Key Characteristics:**
- Two modes: bright Premium marketing, dark Web Player app.
- Spotify Green (`#1ed760`) remains the functional brand accent.
- Premium hero offer: **Try 3 months for $0**, then **$12.99/month**, ending **July 6, 2026**.
- Premium feature themes: ad-free listening, lossless up to 24-bit/44.1 kHz, offline listening, full playback control, DJ, Wrapped, daylist, Jam, Blend.
- Web Player sections: Trending songs, Popular artists, Popular albums and singles, Popular radio, Featured Charts.
- Pill/circle geometry is mandatory: CTAs, search, nav pills, play controls.
- Album/artist art is the Web Player's main color source.
- Footer taxonomy is consistent across both: Company, Communities, Useful links, Spotify Plans.

## Colors

### Brand & Action
- **Spotify Green** (`#1ed760`): Brand accent, play controls, active states, and Premium CTAs.
- **Green Dark** (`#1db954`): Legacy/secondary green accent and border variant.
- **Black** (`#000000`): Footer, app contrasts, icon color on green controls.

### Web Player Dark System
- **Near Black** (`#121212`): Main app background.
- **App Surface** (`#181818`): Sidebar, panels, and cards.
- **Raised Surface** (`#1f1f1f`): Search inputs, controls, and raised interactive surfaces.
- **Card Hover** (`#2a2a2a`): Hover state for media cards.
- **Primary Text** (`#ffffff`): Titles and active navigation.
- **Subdued Text** (`#b3b3b3`): Metadata, inactive nav, captions.

### Premium Marketing System
- **Marketing Canvas** (`#ffffff`): Premium page base.
- **Marketing Ink** (`#000000`): Premium heading/body text.
- **Green Surface** (`#1ed760`): Offer and action emphasis.
- **Campaign Tints**: Lime, pink, blue, and purple can appear in marketing imagery and campaign surfaces, but should not override the green brand accent.
- **Plan Card Dark** (`#121212`): Premium plan cards are dark islands within the bright page.

### Semantic
- **Negative Red** (`#f3727f`), **Warning Orange** (`#ffa42b`), and **Announcement Blue** (`#539df5`) are reserved for app/system messaging.

## Typography

### Font Family
- **Title**: `SpotifyMixUITitle`, with CircularSp/global script fallbacks.
- **UI / Body**: `SpotifyMixUI`, with Arabic, Hebrew, Cyrillic, Greek, Devanagari, CJK, Helvetica Neue, Helvetica, and Arial fallbacks.
- **Global support** matters: Open Spotify exposes a large language selector, so text styles must handle many scripts without breaking density.

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|---|---|---:|---:|---:|---:|---|
| Premium Hero | SpotifyMixUITitle | 72px | 800 | 0.95 | -1px | Big stacked campaign words |
| Premium Display | SpotifyMixUITitle | 56px | 800 | 0.95 | -0.5px | Large marketing sections |
| Marketing Section | SpotifyMixUITitle | 32px | 700 | 1.1 | 0 | Plan and feature headings |
| App Section | SpotifyMixUITitle | 24px | 700 | 1.2 | 0 | Trending songs, Popular artists |
| Card Title | SpotifyMixUI | 16px | 700 | 1.35 | 0 | Track, album, artist labels |
| Body | SpotifyMixUI | 16px | 400 | 1.5 | 0 | Marketing prose |
| App Body | SpotifyMixUI | 14px | 400 | 1.5 | 0 | Metadata, nav, captions |
| Button | SpotifyMixUI | 14px | 700 | 1.2 | 0 | Modern pill CTAs |
| Uppercase Button | SpotifyMixUI | 14px | 700 | 1.0 | 1.4px | Legacy/system label style |
| Caption | SpotifyMixUI | 12px | 400 | 1.5 | 0 | Legal and fine print |

### Principles
- Premium can use giant stacked words and dense line breaks.
- Web Player stays compact: 12-24px dominates.
- Use bold/regular contrast more than color for text hierarchy.
- Button text is strong but not decorative; keep it direct.

## Layout

### Spacing System
Spotify's app mode is dense and 8px-based; Premium mode is more editorial, using broad 64-96px section rhythms. Keep the two rhythms separate.

### Grid & Container
- Web Player: sidebar + main scroll area + optional bottom player bar.
- Web Player content: horizontal rows or responsive grids of square media cards.
- Premium: stacked long-scroll sections, full-width campaign imagery, plan-card grid, and footer columns.
- Premium plan cards: dark cards inside a bright page, grouped by Individual, Student, Duo, Family, Audiobooks Access.

### Whitespace Philosophy
The app compresses content because discovery requires density. Premium breathes more because it is selling value and culture. Do not apply the Web Player's density to Premium hero sections, and do not apply Premium's oversized type to app grids.

## Elevation & Depth

Spotify is one of the few dark systems where heavier shadows are correct. Dialogs and menus need visible darkness-on-dark depth.

### Rules
- Use `rgba(0,0,0,0.5) 0 8px 24px` for dialogs and menus.
- Use `rgba(0,0,0,0.3) 0 8px 8px` for hover/elevated app cards.
- Use inset shadows for search/input borders on dark backgrounds.
- Premium marketing should use softer, lighter shadows only when card separation needs it.

### Surface Stack
1. Web app base `#121212`.
2. Panels/cards `#181818`.
3. Raised controls `#1f1f1f`.
4. Hover cards `#2a2a2a`.
5. Dialog/menu shadows at 0.5 opacity.

## Shapes

### Border Radius Scale
- **2px-4px**: Tiny badges and utility states.
- **8px**: App cards and media tiles.
- **12px**: Premium plan cards and larger panels.
- **500px / 9999px**: Pill CTAs, search, nav pills.
- **50%**: Play buttons, artist images, avatars.

### Geometry
Spotify identity depends on pill and circular forms. Square buttons or sharp search fields are wrong unless reproducing an embedded third-party surface.

## Components

### Premium Header
Use a white marketing header with Spotify logo, Premium plans menu, Support, Download, Sign up, Log in, and a direct Premium CTA. The Premium plans menu should expose Individual, Duo, Family, and Student.

### Premium Hero
The current hero is a bright campaign statement: "The ultimate home for music, artists, fans, live events, videos" plus `Try 3 months for $0`. Use large stacked type, one strong pill CTA, and clear legal copy.

### Premium Feature Sections
Feature modules include device ubiquity, ad-free music, lossless audio, offline listening, playback control, DJ, Wrapped, daylist, Jam, Blend, live events, video/countdown culture, and import-your-music. Use editorial imagery and short feature copy rather than app chrome.

### Premium Plan Cards
Plan cards are dark, high-contrast conversion units inside the bright marketing page. Current plans: Individual, Student, Duo, Family, and Audiobooks Access. Include pricing, account count, audiobook hours where relevant, cancellation language, and a pill CTA.

### Web Player Shell
The app shell uses dark surfaces with Home, Search, Your Library, and Premium. Preserve the left-nav mental model even when responsive layouts hide or compress it.

### Content Rows
Rows include Trending songs, Popular artists, Popular albums and singles, Popular radio, and Featured Charts. Media cards should show square album art, circular artist imagery where appropriate, title text, and subdued metadata. Keep card chrome minimal.

### Upsell Banner
Open Spotify currently displays a Premium Individual banner: `$0 for 3 months`, Try 3 months for $0, View all plans, plus legal copy. Treat it as a compact conversion strip, not a hero.

### Search & Controls
Search is a pill on dark, with icon-aware padding. Play buttons are green circles with black icons. Secondary app buttons are dark or white pills depending on context.

### Footer
Both surfaces share a broad Spotify footer: Company, Communities, Useful links, Spotify Plans, social links, region, legal/privacy/accessibility links, and copyright.

## Do's and Don'ts

### Do
- Separate Premium marketing mode from Web Player app mode.
- Use Spotify Green for play, active, and CTA functions.
- Use dark dense grids for open.spotify.com content.
- Use bright oversized campaign sections for Premium.
- Let album art and artist photography supply color in the app.
- Use pill CTAs and circular play/artist forms.
- Keep plan cards dark and conversion-focused.
- Include legal offer copy for Premium pricing and expiration.

### Don't
- Do not make the Premium page look like the Web Player app.
- Do not make the Web Player bright or airy.
- Do not use green as random background decoration.
- Do not square off CTAs, search, play controls, or plan buttons.
- Do not relax app density into a marketing layout.
- Do not invent extra brand accent colors beyond campaign imagery.
- Do not omit footer taxonomy; Spotify relies on broad ecosystem links.

## Responsive Behavior

### Breakpoints

| Breakpoint | Width | Behavior |
|---|---:|---|
| Mobile Small | `< 425px` | Single-column Premium sections; app rows become horizontal scroll or single-column lists |
| Mobile | `425px-575px` | Header collapses to menu; large hero type steps down |
| Tablet | `576px-767px` | Premium feature grids begin; app cards 2-column or scroll rows |
| Tablet Large | `768px-895px` | Sidebar may collapse; plan cards 2-column |
| Desktop Small | `896px-1023px` | Sidebar visible; app rows expand |
| Desktop | `1024px-1279px` | Full Premium nav and multi-column card grids |
| Large Desktop | `1280px+` | Expanded media rows and plan grids |

### Behavior Notes
- Keep Premium CTAs prominent and full-width or near-full-width on mobile.
- Preserve app bottom/player controls where relevant.
- Artist imagery should remain circular at all sizes.
- Album/playlist cards should preserve square artwork.
- Legal copy must remain readable after wrapping.

## Iteration Guide

If the screen is Premium-facing, start with white/green campaign energy, large copy, and plan/feature storytelling. If the screen is app-facing, start with `#121212`, dense media rows, subdued metadata, and green playback controls.

When a Spotify design feels wrong, check the polarity first. Most mistakes come from mixing marketing and app modes: giant Premium typography inside the player, or dark app cards inside a Premium offer section.

## Known Gaps

- Premium offer copy and expiration are time-sensitive; current Lightpanda capture shows the 2026 Q2 offer ending July 6, 2026.
- open.spotify.com content rows are personalized/region-sensitive; trending songs and artist lists can change frequently.
- Exact SpotifyMix font loading details vary by subdomain and runtime bundle.
- The Web Player's authenticated state, full playback bar, library behavior, and account menus are not fully captured from a logged-out Lightpanda session.
