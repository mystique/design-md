---
version: alpha
name: Adobe
description: |
  A broad creative-and-document productivity system built from Spectrum pragmatism, black hero panels, Adobe red brand authority, bright blue action buttons, and a modular AEM masonry of product pods. The current homepage leads with Adobe Acrobat and PDF Spaces, positioning files, ideas, and AI Assistant as a guided document workflow, then fans out into Creative Cloud, Firefly, Photoshop, business, and news modules.

colors:
  primary: "#1473e6"
  primary-hover: "#0d66d0"
  primary-pressed: "#095aba"
  adobe-red: "#ff0000"
  adobe-red-deep: "#d31510"
  acrobat-red: "#ec1c24"
  firefly-purple: "#6e3aff"
  creative-cloud-pink: "#ff2bc2"
  photoshop-blue: "#31a8ff"
  express-purple: "#7d2cff"
  ink: "#000000"
  body: "#2c2c2c"
  body-muted: "#505050"
  body-subtle: "#6e6e6e"
  on-primary: "#ffffff"
  on-dark: "#ffffff"
  canvas: "#ffffff"
  canvas-soft: "#f5f5f5"
  surface-card: "#ffffff"
  surface-dark: "#000000"
  surface-graphite: "#1e1e1e"
  surface-neutral: "#f8f8f8"
  surface-blue-soft: "#e8f1ff"
  surface-red-soft: "#fff0f0"
  hairline: "#d5d5d5"
  hairline-soft: "#eeeeee"
  focus-ring: "#1473e6"
  overlay-dark: "rgba(0,0,0,0.45)"
  shadow-card: "0 2px 8px rgba(0,0,0,0.14)"

typography:
  hero-display:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 56px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: -0.02em
  display-lg:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 44px
    fontWeight: 700
    lineHeight: 1.12
    letterSpacing: -0.015em
  display-md:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.18
    letterSpacing: -0.01em
  headline:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0
  card-title:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 22px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0
  lead:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-strong:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.45
    letterSpacing: 0
  nav-link:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0
  button:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 15px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0
  eyebrow:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0.06em
    textTransform: uppercase
  caption:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0
  legal:
    fontFamily: "Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 8px
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
  section: 72px
  masonry: 24px

components:
  global-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 64px
    borderBottom: "1px solid {colors.hairline-soft}"
  adobe-logo:
    backgroundColor: transparent
    textColor: "{colors.adobe-red}"
    rounded: "{rounded.none}"
  nav-link:
    backgroundColor: transparent
    textColor: "{colors.body}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.none}"
    padding: 12px 10px
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 10px 18px
    height: 40px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.pill}"
  button-secondary:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    border: "2px solid {colors.primary}"
    padding: 8px 16px
    height: 40px
  button-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 10px 18px
    height: 40px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.body-strong}"
  hero-acrobat:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    minHeight: 640px
  hero-copy-panel:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.lead}"
    padding: 48px
  product-eyebrow:
    backgroundColor: transparent
    textColor: "{colors.on-dark}"
    typography: "{typography.eyebrow}"
  masonry-grid:
    backgroundColor: "{colors.canvas-soft}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    gap: 24px
  product-pod:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 28px
    shadow: "{colors.shadow-card}"
  product-pod-dark:
    backgroundColor: "{colors.surface-graphite}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 28px
  acrobat-pod:
    backgroundColor: "{colors.surface-red-soft}"
    textColor: "{colors.ink}"
    typography: "{typography.card-title}"
    rounded: "{rounded.lg}"
    padding: 28px
  firefly-pod:
    backgroundColor: "{colors.firefly-purple}"
    textColor: "{colors.on-dark}"
    typography: "{typography.card-title}"
    rounded: "{rounded.lg}"
    padding: 28px
  creative-cloud-pod:
    backgroundColor: "{colors.surface-blue-soft}"
    textColor: "{colors.ink}"
    typography: "{typography.card-title}"
    rounded: "{rounded.lg}"
    padding: 28px
  news-pod:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 24px
    border: "1px solid {colors.hairline-soft}"
  floating-business-button:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 12px 18px
    shadow: "{colors.shadow-card}"
  footer:
    backgroundColor: "{colors.canvas-soft}"
    textColor: "{colors.body}"
    typography: "{typography.caption}"
    padding: 56px 0px 32px
  footer-heading:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-strong}"
    rounded: "{rounded.none}"
---

## Overview

Adobe's current homepage is a broad platform storefront for creative work, document workflows, AI, business, and product news. The extracted page currently leads with **Adobe Acrobat** and the headline “Transform how you share information.” Supporting copy promotes **PDF Spaces**, bringing together files, ideas, and an **AI Assistant** into a guided experience. The primary CTA is “Free trial,” with “Learn more” as the secondary path.

The page is assembled from AEM “pods” and uses a masonry rhythm after the hero. The fragment references visible in the page point to Creative Cloud promo content, Firefly promo content, Creative Cloud links, Photoshop campaign content, business content, news, and a floating business/contact-style button. This makes the system feel less like a single-product landing page and more like a flexible product marketplace for Adobe's portfolio.

The visual language is Adobe Spectrum-adjacent: clean sans-serif typography, pill CTAs, blue interactive color, Adobe red as brand authority, and modular cards with product-specific colors. The hero can go stark black for Acrobat, while downstream pods become more colorful as Creative Cloud, Firefly, Photoshop, Express, or Business content takes over.

**Key Characteristics:**
- Adobe red as logo/brand authority, not the default CTA color.
- Bright Spectrum Blue for primary actions like Free trial and Learn more.
- Black Acrobat hero surfaces with white copy and document/product imagery.
- AEM masonry pods for cross-product promotion.
- Product-specific color accents: Acrobat red, Firefly purple, Photoshop blue, Creative Cloud pink/gradient energy.
- Rounded cards and pill CTAs, more SaaS/product-platform than luxury editorial.
- AI messaging woven into document and creative workflows.

## Colors

> **Source page analyzed:** https://www.adobe.com via lightpanda MCP on 2026-05-19. The page exposed Acrobat/PDF Spaces hero content and AEM fragment references for Creative Cloud, Firefly, Photoshop, Business, and News pods. Computed visual styles were mostly hidden by the rendered fragment state, so token choices align with Adobe's visible content and established Spectrum-style web grammar.

### Brand & Accent

- **Spectrum Blue** (`{colors.primary}` — #1473e6): Main interactive color for CTA buttons and text links.
- **Adobe Red** (`{colors.adobe-red}` — #ff0000): Brand mark color and high-level Adobe identity signal.
- **Acrobat Red** (`{colors.acrobat-red}` — #ec1c24): Product accent for Acrobat and PDF modules.
- **Firefly Purple** (`{colors.firefly-purple}` — #6e3aff): Generative AI and Firefly surfaces.
- **Photoshop Blue** (`{colors.photoshop-blue}` — #31a8ff): Photoshop product accent.
- **Creative Cloud Pink** (`{colors.creative-cloud-pink}` — #ff2bc2): Creative Cloud campaign accent.

### Surface

- **Canvas** (`{colors.canvas}` — #ffffff): Main navigation and product-pod surface.
- **Soft Canvas** (`{colors.canvas-soft}` — #f5f5f5): Masonry background and footer surface.
- **Dark Surface** (`{colors.surface-dark}` — #000000): Acrobat hero and high-impact campaign modules.
- **Graphite** (`{colors.surface-graphite}` — #1e1e1e): Dark cards where pure black would be too heavy.
- **Blue Soft** (`{colors.surface-blue-soft}` — #e8f1ff): Creative Cloud or productivity support panels.
- **Red Soft** (`{colors.surface-red-soft}` — #fff0f0): Acrobat support panels and document-card surfaces.

### Text

- **Ink** (`{colors.ink}` — #000000): High-emphasis headings.
- **Body** (`{colors.body}` — #2c2c2c): Default copy.
- **Body Muted** (`{colors.body-muted}` — #505050): Secondary descriptions.
- **Body Subtle** (`{colors.body-subtle}` — #6e6e6e): Legal, metadata, fine print.
- **On Dark** (`{colors.on-dark}` — #ffffff): Text over black hero and dark product pods.

### Borders & Effects

- **Hairline** (`{colors.hairline}` — #d5d5d5): Standard dividers, inputs, card outlines.
- **Hairline Soft** (`{colors.hairline-soft}` — #eeeeee): Navigation and low-emphasis card borders.
- **Card Shadow** (`{colors.shadow-card}`): Soft product-platform elevation for pods and floating buttons.

## Typography

### Font Family

- **Primary:** `Adobe Clean, adobe-clean, Helvetica Neue, Arial, sans-serif`. Adobe's product marketing surfaces should read like Spectrum/Spectrum-adjacent UI: clean, enterprise-ready, and highly legible.
- **Fallback:** Use `Helvetica Neue` or `Arial` when Adobe Clean is unavailable.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.hero-display}` | 56px | 700 | 1.05 | -0.02em | Homepage hero headline |
| `{typography.display-lg}` | 44px | 700 | 1.12 | -0.015em | Major product/campaign heading |
| `{typography.display-md}` | 32px | 700 | 1.18 | -0.01em | Pod and section headings |
| `{typography.headline}` | 24px | 700 | 1.25 | 0 | Compact section headline |
| `{typography.card-title}` | 22px | 700 | 1.25 | 0 | Masonry pod title |
| `{typography.lead}` | 20px | 400 | 1.5 | 0 | Hero support copy |
| `{typography.body}` | 16px | 400 | 1.5 | 0 | Default copy |
| `{typography.nav-link}` | 14px | 700 | 1.2 | 0 | Navigation |
| `{typography.button}` | 15px | 700 | 1 | 0 | CTA labels |
| `{typography.eyebrow}` | 13px | 700 | 1.25 | 0.06em | Product family labels like ADOBE ACROBAT |
| `{typography.caption}` | 13px | 400 | 1.45 | 0 | Captions and footer |

### Principles

- **Bold, not decorative.** Adobe marketing type is clear and product-platform oriented. Use weight 700 for hierarchy rather than expressive font choices.
- **Product labels use uppercase.** Eyebrows like “ADOBE ACROBAT” should be compact and strong.
- **Body copy stays practical.** Explain workflows, AI features, file sharing, and trial paths directly.
- **No luxury tracking.** Avoid wide letter spacing except for short product eyebrows.

## Layout

### Spacing System

- **Base unit:** 8px, with 24px masonry gutters and 72px section spacing.
- **Hero:** Large dark panel with left or centered copy and product imagery.
- **Masonry:** Flexible pod grid; cards can vary in size, image/media density, and product color.
- **Footer:** Soft gray utility area with product, support, account, and legal links.

### Grid & Container

- **Hero module:** Product eyebrow, large headline, body copy, primary CTA, secondary text link.
- **Masonry pods:** Multiple campaign fragments organized into a responsive grid. Pods can represent Creative Cloud, Firefly, Photoshop, Acrobat, business, or news.
- **Floating business CTA:** A bottom or edge floating contact/business button can overlay content.

### Whitespace Philosophy

Adobe balances enterprise clarity with creative energy. The hero should feel crisp and high-contrast, while the masonry below can be denser and more colorful. Do not use Apple-style empty product-gallery spacing; Adobe's homepage is a portfolio hub and needs visible breadth.

## Components

### Navigation

**`global-nav`** is a white Spectrum-style product navigation bar with Adobe logo, product family links, search/account utility, and no decorative background.

**`adobe-logo`** should use the Adobe red mark. Do not approximate it with text.

### Hero

**`hero-acrobat`** is the current lead pattern: black surface, Acrobat/document product imagery, uppercase product eyebrow, large white headline, support copy, blue primary CTA, and blue/white secondary link depending on contrast.

**`hero-copy-panel`** should remain readable and direct. Avoid marketing clutter; one primary action and one secondary action are enough.

### Buttons & Links

**`button-primary`** uses Spectrum Blue and a pill shape. This is Adobe's default action grammar.

**`button-secondary`** is a blue outline pill. Use beside primary CTAs when the action is equivalent but lower commitment.

**`button-dark`** is black with white text, useful on light product pods when the product brand calls for contrast.

**`text-link`** is blue and semibold. It should be used for Learn more and product-detail links.

### Product Pods

**`masonry-grid`** is the homepage's main content engine. It should support mixed-size cards and product-specific colors without losing the shared system.

**`product-pod`** is the default white rounded card with product title, copy, media, and CTA.

**`product-pod-dark`** is used for black or graphite creative campaign blocks.

**`acrobat-pod`**, **`firefly-pod`**, and **`creative-cloud-pod`** provide product-specific surfaces while retaining shared typography, radius, and CTA rules.

**`news-pod`** is quieter, usually white with border and compact copy.

### Footer

**`footer`** is a soft gray utility surface. It should organize product families, support, account, business, and legal links without competing with the hero.

## Do's and Don'ts

### Do

- Use Spectrum Blue for primary actions and links.
- Use Adobe Red for brand/logo identity, not as the universal button color.
- Allow product-specific accent colors inside pods.
- Use rounded cards and pill CTAs consistently.
- Make Acrobat, Creative Cloud, Firefly, Photoshop, Express, Business, and News feel like one portfolio system.
- Keep AI copy tied to workflows: documents, files, ideas, PDF Spaces, generative creation, business productivity.

### Don't

- Don't make every Adobe surface red.
- Don't flatten the homepage into a single-product landing page.
- Don't use stark square enterprise buttons when Spectrum-style pills are expected.
- Don't overuse gradients as generic decoration; reserve color intensity for product/campaign imagery.
- Don't hide cross-product breadth below the fold; Adobe's value is the portfolio.
- Don't use playful or handmade typography; the system is professional and product-led.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Small phone | ≤ 419px | Hero becomes stacked; CTAs wrap; masonry becomes single column |
| Phone | 420–767px | Navigation collapses; hero imagery moves below copy; pods stack |
| Tablet | 768–1023px | Two-column masonry; hero reduces to tablet crop |
| Desktop | 1024–1439px | Full hero and multi-column masonry |
| Large desktop | ≥ 1440px | Hero media and pod grid expand within max-width constraints |

### Behavior Notes

- Preserve CTA hierarchy on mobile: primary trial action first, secondary learn-more action second.
- Product pods should keep their brand colors even when stacked.
- Hero dark mode must maintain contrast for body copy and buttons.
- Floating business/contact buttons should not cover CTA clusters on small screens.

## Content Strategy

- Lead with the most strategic current product story, currently Acrobat and PDF Spaces.
- Pair AI features with concrete workflows rather than abstract AI claims.
- Use pods to expose the product portfolio: Creative Cloud, Firefly, Photoshop, Acrobat, Express, Business, News.
- Keep CTAs explicit: Free trial, Learn more, Start now, Contact sales.
- Let each product color appear, but maintain a shared Adobe Clean typography and Spectrum-style control system.

## Sources

- Homepage: https://www.adobe.com
- Extracted with lightpanda MCP on 2026-05-19.
