---
version: alpha
name: Runway
description: |
  A cinematic AI research and product interface where video, world-model output,
  and full-bleed imagery are the primary UI. The live homepage verified through
  Lightpanda leads with "Building AI to Simulate the World", promotes Runway
  Agent, Gen-4.5, GWM-1, GWM Worlds, GWM Robotics, and Runway Characters, and
  closes with a research/company recruiting message. The design is dark,
  editorial, minimal, and film-production-grade: the interface recedes so
  generated worlds, motion, and research artifacts can dominate.

colors:
  primary: "#ffffff"
  primary-focus: "#e9ecf2"
  primary-on-dark: "#ffffff"
  ink: "#000000"
  body: "#404040"
  body-on-dark: "#ffffff"
  body-muted: "#767d88"
  ink-muted-80: "#3f3f3f"
  ink-muted-48: "#7d848e"
  divider-soft: "#c9ccd1"
  hairline: "#27272a"
  canvas: "#000000"
  canvas-parchment: "#fefefe"
  surface-pearl: "#e9ecf2"
  surface-tile-1: "#030303"
  surface-tile-2: "#1a1a1a"
  surface-tile-3: "#0c0c0c"
  surface-black: "#000000"
  surface-chip-translucent: "rgba(255,255,255,0.12)"
  on-primary: "#000000"
  on-dark: "#ffffff"

typography:
  hero-display:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 48px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: -1.2px
  display-lg:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 40px
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: -1px
  display-md:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 36px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: -0.9px
  lead:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 24px
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: 0
  lead-airy:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: -0.2px
  tagline:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: 0.35px
    textTransform: uppercase
  body-strong:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: -0.16px
  body:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: -0.16px
  dense-link:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: 0.35px
  caption:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: -0.16px
  caption-strong:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0.35px
    textTransform: uppercase
  button-large:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: -0.16px
  button-utility:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0.35px
    textTransform: uppercase
  fine-print:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 11px
    fontWeight: 450
    lineHeight: 1.3
    letterSpacing: 0
  micro-legal:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 10px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: 0
  nav-link:
    fontFamily: "abcNormal, abcNormal Fallback, Inter, DM Sans, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.3
    letterSpacing: -0.16px

rounded:
  none: 0px
  xs: 4px
  sm: 6px
  md: 8px
  lg: 16px
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
  section: 78px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-large}"
    rounded: "{rounded.xs}"
    padding: 10px 16px
  button-primary-focus:
    backgroundColor: "{colors.primary-focus}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xs}"
  button-primary-active:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.xs}"
  button-secondary-pill:
    backgroundColor: "{colors.surface-chip-translucent}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button-large}"
    rounded: "{rounded.xs}"
    padding: 10px 16px
    border: "1px solid rgba(255,255,255,0.16)"
  button-dark-utility:
    backgroundColor: "{colors.surface-tile-2}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button-utility}"
    rounded: "{rounded.xs}"
    padding: 8px 12px
  button-pearl-capsule:
    backgroundColor: "{colors.canvas-parchment}"
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    rounded: "{rounded.md}"
    padding: 8px 14px
  button-store-hero:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.ink}"
    typography: "{typography.button-large}"
    rounded: "{rounded.xs}"
    padding: 12px 20px
  button-icon-circular:
    backgroundColor: "{colors.surface-chip-translucent}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.full}"
    size: 40px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body}"
  text-link-on-dark:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
  global-nav:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.nav-link}"
    height: 64px
  sub-nav-frosted:
    backgroundColor: "rgba(0,0,0,0.48)"
    textColor: "{colors.on-dark}"
    typography: "{typography.caption}"
    border: "1px solid rgba(255,255,255,0.12)"
  product-tile-light:
    backgroundColor: "{colors.canvas-parchment}"
    textColor: "{colors.ink}"
    typography: "{typography.display-lg}"
    rounded: "{rounded.md}"
    padding: 32px
  product-tile-parchment:
    backgroundColor: "{colors.surface-pearl}"
    textColor: "{colors.ink}"
    typography: "{typography.display-lg}"
    rounded: "{rounded.md}"
    padding: 32px
  product-tile-dark:
    backgroundColor: "{colors.surface-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-lg}"
    rounded: "{rounded.md}"
    padding: 32px
  cinematic-hero:
    backgroundColor: "{colors.surface-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    rounded: "{rounded.none}"
    media: "full-bleed video or image"
  research-card:
    backgroundColor: "{colors.surface-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.lead}"
    rounded: "{rounded.md}"
    border: "1px solid {colors.hairline}"
  footer:
    backgroundColor: "{colors.surface-black}"
    textColor: "{colors.body-muted}"
    typography: "{typography.caption}"
    padding: 64px 24px
---

## Overview

Runway is an AI research and creative tooling site that behaves more like a cinematic reel than a SaaS homepage. The current live page verified through Lightpanda opens with the announcement **"Meet Runway Agent - your new creative partner"**, then leads into the hero statement **"Building AI to Simulate the World"** with a direct Get Started action.

The current navigation is minimal and editorial: **Research**, **Product**, **Resources**, **Solutions**, and **Company**, with Enterprise Sales, Log in, and Try Runway actions. The homepage links immediately to Runway Characters, Media and Entertainment, Robotics and Autonomy, and General World Models.

The current content structure highlights Runway's research frontier: **Gen-4.5: A New Frontier for Generative Video**, **GWM Robotics**, **GWM Worlds**, **Runway Characters**, **GWM-1**, **General World Models**, and a research statement about building foundational General World Models that can simulate possible worlds and experiences. It also features partnerships and customer stories, including NVIDIA, Lionsgate, UCLA Film/TV, and KPF architecture workflows.

The visual language should feel like film production, not product management. Full-bleed video and cinematic AI imagery do the work that icons, gradients, and diagrams would do elsewhere. UI chrome should stay nearly invisible.

## Colors

### Brand & Accent

- **White** (`{colors.primary}` - #ffffff): The main action/text color on dark cinematic surfaces.
- **Black** (`{colors.canvas}` - #000000): Primary page environment and the default film-screen base.
- **Deep Black** (`{colors.surface-tile-1}` - #030303): Subtle dark-layer variant.
- **Dark Surface** (`{colors.surface-tile-2}` - #1a1a1a): Cards, overlays, alert-like containers, and dark panels.

### Surface

- **Canvas Black** (`{colors.canvas}`): Default background for hero, research, product, and footer areas.
- **Near White** (`{colors.canvas-parchment}` - #fefefe): Light editorial sections.
- **Cool Cloud** (`{colors.surface-pearl}` - #e9ecf2): Cool light-gray sections and contrast panels.
- **Border Dark** (`{colors.hairline}` - #27272a): The single dark hairline used for minimal containment.

### Text

- **On Dark** (`{colors.on-dark}` - #ffffff): Primary copy on cinematic backgrounds.
- **Charcoal** (`{colors.body}` - #404040): Body text on light surfaces.
- **Cool Slate** (`{colors.body-muted}` - #767d88): Secondary text, descriptions, metadata, and muted footer links.
- **Mid Slate** (`{colors.ink-muted-48}` - #7d848e): Tertiary text and lower-priority labels.
- **Muted Gray** (`#a7a7a7`, implied): De-emphasized captions and timestamps.

### Hairlines & Borders

- Use `#27272a` for dark-mode containment, but only when needed.
- Use `#c9ccd1` or `#d0d4d4` for light-section dividers.
- Avoid strong outlines. Runway's interface should feel like a projection surface with minimal chrome.

### Brand Gradient

Runway does not need decorative UI gradients. Color and gradient should come from generated video, cinematic images, and research visuals. Do not add generic AI-gradient backgrounds.

## Typography

### Font Family

Runway uses **abcNormal** as a one-typeface system. The same family handles display, body, buttons, navigation, captions, and micro labels. The fallback should be Inter or DM Sans when abcNormal is unavailable.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---:|---:|---:|---:|---|
| `{typography.hero-display}` | 48px | 400 | 1 | -1.2px | Hero and film-title statements |
| `{typography.display-lg}` | 40px | 400 | 1.05 | -1px | Section headings |
| `{typography.display-md}` | 36px | 400 | 1 | -0.9px | Secondary section markers |
| `{typography.lead}` | 24px | 400 | 1.1 | 0 | Research card titles |
| `{typography.lead-airy}` | 20px | 400 | 1.3 | -0.2px | Descriptive section copy |
| `{typography.body}` | 16px | 400 | 1.45 | -0.16px | Body and product copy |
| `{typography.caption}` | 13px | 400 | 1.3 | -0.16px | Metadata and card descriptions |
| `{typography.caption-strong}` | 14px | 600 | 1.25 | 0.35px | Uppercase labels |
| `{typography.fine-print}` | 11px | 450 | 1.3 | 0 | Micro labels |

### Principles

Use one typeface for everything. Variety comes from scale, weight, case, and spacing. Display text is tight and cinematic; body text is still compact compared with conventional marketing pages.

Use uppercase labels sparingly to structure navigation and modules. Keep weights in the 400-600 range, with 450 as a precision detail for micro labels.

### Note on Font Substitutes

abcNormal is custom. Use Inter or DM Sans if needed, but preserve the tight display line-height and slight negative tracking. Avoid adding a second decorative display typeface.

## Layout

### Spacing System

- **Base unit:** 8px.
- **Small values:** 4px, 6px, 8px, and 12px for labels and compact UI.
- **Component gaps:** 16px to 24px.
- **Section spacing:** 48px to 78px.
- **Cinema width:** use very wide containers, up to about 1600px, when imagery is the content.

### Grid & Container

The homepage uses a full-bleed hero, link clusters for major research/product areas, large cinematic sections for Gen-4.5 and GWM, research cards, latest product cards, partnership/customer cards, and a dense footer.

Image grids should be asymmetric and magazine-like. Full-bleed media should be allowed to dominate. Research cards can be structured, but still image-led.

### Whitespace Philosophy

Whitespace behaves like a scene transition. Large dark gaps and full-bleed visuals create a feeling of moving between film frames. Do not make the page feel like a feature checklist.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow, no border | Most of the interface |
| Hairline | `1px solid #27272a` | Rare containers and alerts |
| Dark section | Black / near-black with light type | Hero, research, footer |
| Light section | White or cool cloud with dark type | Editorial contrast areas |
| Media depth | Video, lighting, focus, motion | Primary depth system |

Runway uses zero shadows. Depth comes from cinematography: light, motion, foreground/background, and image composition.

### Decorative Depth

Decorative depth is the media itself. Use film-grade stills, generated worlds, video thumbnails, model outputs, and research visuals. Interface decoration should be minimal.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---:|---|
| `{rounded.none}` | 0px | Full-bleed media and hero |
| `{rounded.xs}` | 4px | Buttons and utility controls |
| `{rounded.sm}` | 6px | Small cards and links |
| `{rounded.md}` | 8px | Standard image cards and product screenshots |
| `{rounded.lg}` | 16px | Alert-style containers and featured cards |
| `{rounded.pill}` | 9999px | Rare chips only |
| `{rounded.full}` | 9999px | Icon buttons if needed |

### Photography Geometry

Images and videos should be large, clean, and cinematic. Preserve aspect ratios. Use full-bleed hero media, wide research videos, and mixed editorial grids. Do not over-round imagery; Runway's geometry is subtle, not pill-shaped.

## Components

### Top Navigation

**`global-nav`** - Transparent or dark nav over cinematic content. Left wordmark, center links for Research, Product, Resources, Solutions, Company, and right actions for Enterprise Sales, Log in, Try Runway.

### Buttons

**`button-primary`** - White or near-white button on dark media with black text. Compact radius and minimal chrome.

**`button-secondary-pill`** - Subtle translucent dark button for secondary actions. Use sparingly.

**`button-dark-utility`** - Dark utility button for labels, filters, or research cards.

### Cards & Containers

**`cinematic-hero`** - Full-bleed video/image with tight hero headline and direct CTA. Current hero: "Building AI to Simulate the World."

**Research feature cards** - Gen-4.5, GWM Robotics, GWM Worlds, Runway Characters, GWM-1, and General World Models. Use media first, title second, description third.

**Latest product cards** - Runway Characters, Introducing GWM-1, Gen-4.5. These should feel like research/product releases, not blog cards.

**Partner/customer cards** - NVIDIA, Lionsgate, UCLA, KPF. Use image thumbnail, title, short proof sentence, and Learn more.

### Inputs & Forms

Forms are not central to the homepage. Login, app, enterprise contact, and pricing flows can use minimal fields with dark or light neutral surfaces and 4px to 8px radii.

### Footer

Footer is dense and dark. Current columns are Product, Initiatives, Company, Get Started, and Connect, with links for Explore Examples, Characters, GWM-1, General World Models, Robotics, Gen-4.5, API, AI Summit 2026, Studios, AI Festival, Academy, Careers, Safety, Enterprise, Education, Pricing, Data Security, Changelog, social links, Terms, Privacy, California Notices, Code of Conduct, and System Status.

## Do's and Don'ts

### Do

- Use cinematic images and videos as the main design material.
- Keep UI chrome minimal and quiet.
- Use abcNormal for every text role.
- Keep display text tight and film-title-like.
- Use cool gray text for secondary copy.
- Preserve current research/product naming: Gen-4.5, GWM-1, GWM Worlds, GWM Robotics, Runway Characters.
- Use zero shadows.

### Don't

- Don't add generic AI gradients.
- Don't use colorful UI accents that compete with media.
- Don't create icon-heavy feature grids.
- Don't use pill-shaped geometry as a default.
- Don't introduce a second font.
- Don't make the page feel like a dashboard or SaaS pricing site.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---:|---|
| Mobile | < 640px | Single-column sections, reduced hero type, stacked media |
| Tablet | 640-768px | Two-column grids begin |
| Small Desktop | 768-1024px | Standard section layout |
| Desktop | 1024-1280px | Full cinematic layout |
| Large Desktop | 1280-1600px | Max-width cinematic containers |

### Touch Targets

Article/research cards should act as large tap targets. Buttons should preserve enough padding while remaining visually restrained.

### Collapsing Strategy

Navigation collapses to a compact menu. Hero remains full-bleed. Image grids reduce columns rather than shrinking images too far. Research cards stack with media first.

### Image Behavior

Preserve cinematic composition on all breakpoints. Use alternate crops where necessary. Avoid small thumbnails that obscure the model output.

## Iteration Guide

1. Start with media, then add only enough typography and UI to orient the user.
2. Use black, white, and cool gray before adding any other interface color.
3. Treat every major section as a scene.
4. Keep type tight, single-family, and restrained.
5. Show real model output or partner/customer imagery instead of abstract graphics.
6. Verify mobile crops early.
7. Keep the footer dense but minimal.

## Known Gaps

- Source capture was performed with Lightpanda against `https://runwayml.com/` on 2026-05-17. It exposed current navigation, announcement, hero, research/product modules, partnership cards, recruiting copy, and footer links.
- Computed CSS values were not fully extracted, so the low-level tokens combine current homepage content with the existing Runway design analysis.
- Video upload/player fallback text appeared in the static capture; visual QA is needed to verify live video motion, overlays, and first-frame crops.
