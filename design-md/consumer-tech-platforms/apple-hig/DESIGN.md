---
version: alpha
name: Apple Human Interface Guidelines
description: A platform-native design system for Apple apps and games. It prioritizes clear hierarchy, harmony with device hardware and system surfaces, adaptive layouts, Dynamic Type, system colors, SF typography, SF Symbols, and restrained Liquid Glass control layers. The goal is not to decorate an interface with Apple-like styling, but to make software feel at home on iOS, iPadOS, macOS, tvOS, visionOS, and watchOS.

colors:
  accent-blue-light: "#0088ff"
  accent-blue-dark: "#0091ff"
  accent-blue-contrast-light: "#1e6ef4"
  accent-blue-contrast-dark: "#5cb8ff"
  system-red-light: "#ff383c"
  system-red-dark: "#ff4245"
  system-orange-light: "#ff8d28"
  system-orange-dark: "#ff9230"
  system-yellow-light: "#ffcc00"
  system-yellow-dark: "#ffd600"
  system-green-light: "#34c759"
  system-green-dark: "#30d158"
  system-mint-light: "#00c8b3"
  system-mint-dark: "#00dac3"
  system-teal-light: "#00c3d0"
  system-teal-dark: "#00d2e0"
  system-cyan-light: "#00c0e8"
  system-cyan-dark: "#3cd3fe"
  system-indigo-light: "#6155f5"
  system-indigo-dark: "#6d7cff"
  system-purple-light: "#cb30e0"
  system-purple-dark: "#db34f2"
  system-pink-light: "#ff2d55"
  system-pink-dark: "#ff375f"
  system-brown-light: "#ac7f5e"
  system-brown-dark: "#b78a66"
  label-primary-light: "#000000"
  label-primary-dark: "#ffffff"
  label-secondary-light: "#3c3c4399"
  label-secondary-dark: "#ebebf599"
  label-tertiary-light: "#3c3c434d"
  label-tertiary-dark: "#ebebf54d"
  separator-light: "#3c3c434a"
  separator-dark: "#54545899"
  fill-primary-light: "#78788033"
  fill-primary-dark: "#7878805c"
  fill-secondary-light: "#78788029"
  fill-secondary-dark: "#78788052"
  grouped-background-light: "#f2f2f7"
  grouped-background-dark: "#000000"
  surface-light: "#ffffff"
  surface-dark: "#1c1c1e"
  material-scrim-dark-35: "#00000059"
  destructive: "{colors.system-red-light}"
  success: "{colors.system-green-light}"
  warning: "{colors.system-orange-light}"
  focus: "{colors.accent-blue-light}"

typography:
  ios-large-title:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 34px
    fontWeight: 400
    lineHeight: 1.21
    letterSpacing: 0.40px
  ios-title-1:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 28px
    fontWeight: 400
    lineHeight: 1.21
    letterSpacing: 0.38px
  ios-title-2:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 22px
    fontWeight: 400
    lineHeight: 1.27
    letterSpacing: -0.26px
  ios-title-3:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: -0.45px
  ios-headline:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 17px
    fontWeight: 600
    lineHeight: 1.29
    letterSpacing: -0.43px
  ios-body:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.29
    letterSpacing: -0.43px
  ios-callout:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.31
    letterSpacing: -0.31px
  ios-subhead:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.33
    letterSpacing: -0.23px
  ios-footnote:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.38
    letterSpacing: -0.08px
  ios-caption-1:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.33
    letterSpacing: 0
  ios-caption-2:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.18
    letterSpacing: 0.06px
  macos-body:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.23
    letterSpacing: -0.08px
  tvos-body:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 29px
    fontWeight: 400
    lineHeight: 1.24
    letterSpacing: 0.40px
  visionos-body:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.29
    letterSpacing: -0.43px
  watchos-body:
    fontFamily: "SF Compact, SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.31
    letterSpacing: 0
  emphasis:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 17px
    fontWeight: 600
    lineHeight: 1.29
    letterSpacing: -0.43px
  symbol-label:
    fontFamily: "SF Pro, system-ui, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 15px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: -0.23px

rounded:
  none: 0px
  control-sm: 6px
  control-md: 10px
  control-lg: 14px
  card: 16px
  sheet: 20px
  capsule: 9999px
  circle: 9999px
  app-icon-ios: 22.37%
  app-icon-macos: 22.37%

spacing:
  hairline: 1px
  xxs: 2px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 20px
  xxl: 24px
  xxxl: 32px
  section: 44px
  control-padding-bezel: 12px
  control-padding-borderless: 24px
  safe-area-min: 16px
  visionos-control-center-distance: 60px

components:
  button-primary:
    backgroundColor: "{colors.accent-blue-light}"
    textColor: "{colors.label-primary-dark}"
    typography: "{typography.ios-headline}"
    rounded: "{rounded.capsule}"
    minSize: 44px 44px
    padding: 10px 18px
  button-secondary:
    backgroundColor: "{colors.fill-secondary-light}"
    textColor: "{colors.accent-blue-light}"
    typography: "{typography.ios-body}"
    rounded: "{rounded.capsule}"
    minSize: 44px 44px
    padding: 10px 18px
  button-destructive:
    backgroundColor: transparent
    textColor: "{colors.system-red-light}"
    typography: "{typography.ios-body}"
    rounded: "{rounded.capsule}"
    minSize: 44px 44px
  button-icon:
    backgroundColor: "{colors.fill-secondary-light}"
    textColor: "{colors.label-primary-light}"
    rounded: "{rounded.circle}"
    size: 44px
  button-visionos:
    backgroundColor: "thin material"
    textColor: "vibrant label"
    typography: "{typography.visionos-body}"
    rounded: "{rounded.capsule}"
    minSize: 60px 60px
  button-watchos-inline:
    backgroundColor: "Liquid Glass material"
    textColor: "vibrant label"
    typography: "{typography.watchos-body}"
    rounded: "{rounded.capsule}"
    minSize: 44px 44px
  navigation-bar:
    backgroundColor: "regular Liquid Glass"
    textColor: "{colors.label-primary-light}"
    typography: "{typography.ios-body}"
    height: 44px
  tab-bar:
    backgroundColor: "regular Liquid Glass"
    textColor: "{colors.label-secondary-light}"
    selectedTextColor: "{colors.accent-blue-light}"
    typography: "{typography.ios-caption-1}"
    minSize: 44px 44px
  sidebar:
    backgroundColor: "regular Liquid Glass"
    textColor: "{colors.label-primary-light}"
    typography: "{typography.ios-body}"
    rounded: "{rounded.none}"
  sheet:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.label-primary-light}"
    typography: "{typography.ios-body}"
    rounded: "{rounded.sheet}"
  alert:
    backgroundColor: "regular Liquid Glass"
    textColor: "{colors.label-primary-light}"
    typography: "{typography.ios-body}"
    rounded: "{rounded.sheet}"
  list-row:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.label-primary-light}"
    typography: "{typography.ios-body}"
    minSize: 44px
  grouped-list:
    backgroundColor: "{colors.grouped-background-light}"
    textColor: "{colors.label-primary-light}"
    typography: "{typography.ios-body}"
    rounded: "{rounded.card}"
  card-content:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.label-primary-light}"
    typography: "{typography.ios-body}"
    rounded: "{rounded.card}"
    padding: 16px
  search-field:
    backgroundColor: "{colors.fill-secondary-light}"
    textColor: "{colors.label-primary-light}"
    typography: "{typography.ios-body}"
    rounded: "{rounded.control-lg}"
    minSize: 44px
  text-field:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.label-primary-light}"
    typography: "{typography.ios-body}"
    rounded: "{rounded.control-md}"
    minSize: 44px
  segmented-control:
    backgroundColor: "{colors.fill-secondary-light}"
    textColor: "{colors.label-primary-light}"
    typography: "{typography.ios-subhead}"
    rounded: "{rounded.control-lg}"
    minSize: 44px
  toggle:
    backgroundColor: "{colors.fill-primary-light}"
    selectedBackgroundColor: "{colors.system-green-light}"
    rounded: "{rounded.capsule}"
    minSize: 44px
  symbol:
    textColor: "{colors.label-primary-light}"
    typography: "{typography.symbol-label}"
    renderingMode: hierarchical
  status-success:
    textColor: "{colors.system-green-light}"
    typography: "{typography.ios-footnote}"
  status-warning:
    textColor: "{colors.system-orange-light}"
    typography: "{typography.ios-footnote}"
  status-error:
    textColor: "{colors.system-red-light}"
    typography: "{typography.ios-footnote}"
---

# Apple Human Interface Guidelines DESIGN.md

This document describes Apple HIG as an implementable design system. It is based on the current Apple Human Interface Guidelines pages for [Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines), [Color](https://developer.apple.com/design/human-interface-guidelines/color), [Typography](https://developer.apple.com/design/human-interface-guidelines/typography), [Layout](https://developer.apple.com/design/human-interface-guidelines/layout), [Materials](https://developer.apple.com/design/human-interface-guidelines/materials), [Buttons](https://developer.apple.com/design/human-interface-guidelines/buttons), [SF Symbols](https://developer.apple.com/design/human-interface-guidelines/sf-symbols), [Components](https://developer.apple.com/design/human-interface-guidelines/components), and [Accessibility](https://developer.apple.com/design/human-interface-guidelines/accessibility), accessed on 2026-05-17.

## Overview

Apple HIG is a platform-native interaction language, not a visual skin. Its default answer is to use system frameworks and system components so the interface automatically adapts to appearance, contrast, text size, input method, display size, device posture, and platform conventions.

The system has three high-level principles:

- **Hierarchy:** Controls and navigation sit above content, but they should clarify the content rather than compete with it.
- **Harmony:** Interface shapes, materials, motion, and spacing should coordinate with the device and operating system. Rounded controls, concentric geometry, safe areas, and glass materials are part of this hardware-software fit.
- **Consistency:** Apps should adopt familiar platform behaviors and adapt continuously across window sizes and displays.

The strongest HIG implementation uses native SwiftUI, UIKit, AppKit, WatchKit, tvOS, and visionOS components wherever possible. Custom UI is appropriate only when it serves the app's purpose without breaking platform expectations.

## Design Vocabulary

HIG organizes the design language into six major areas:

| Area | Purpose |
|---|---|
| Getting started | Make an app or game feel at home on every supported Apple platform. |
| Foundations | Core visual and interaction ingredients: color, typography, layout, materials, accessibility, icons, SF Symbols, motion, privacy, writing, and localization direction. |
| Patterns | Common user tasks and flows such as onboarding, multitasking, drag and drop, search, sharing, loading, and settings. |
| Components | System-defined building blocks for content, navigation, menus, actions, presentation, selection, input, status, and system experiences. |
| Inputs | Touch, keyboard, pointer, remote, game controller, eyes, hands, Digital Crown, Apple Pencil, and other control methods. |
| Technologies | Apple capabilities such as Apple Intelligence, App Intents, Game Center, Live Activities, widgets, SharePlay, spatial computing, and platform services. |

## Design Principles

### Hierarchy

Create a clear path of attention. Primary content should be immediately visible, with controls grouped and layered according to importance. Use placement, size, weight, material, alignment, and progressive disclosure before adding extra decoration.

Controls must remain distinct from content. In modern iOS, iPadOS, macOS, tvOS, and watchOS surfaces, Liquid Glass provides the functional control layer. Content sits beneath it and can scroll behind it. Do not use the same material treatment for content and navigation, because it weakens the hierarchy.

### Harmony

Align UI geometry with the device. Use rounded controls, capsules, circles, safe-area-aware layouts, and system materials so the interface feels connected to Apple hardware. On visionOS, prefer translucent glass windows and comfortable center-weighted layouts. On watchOS, let content extend edge to edge because the bezel already creates visual padding.

Harmony also applies to input. A control that works well with a fingertip might not be comfortable with eyes, a remote, a pointer, or a Digital Crown. Treat target size and spacing as part of the visual design.

### Consistency

Adopt system components, system gestures, SF Symbols, Dynamic Type, semantic colors, and platform-standard navigation. People should not have to relearn basic interactions inside each app. If a custom pattern is necessary, it should preserve system expectations for roles, focus, accessibility labels, keyboard behavior, and state feedback.

## Colors

Apple colors are semantic and adaptive. Prefer system colors over hard-coded values because system colors automatically adjust for light mode, dark mode, increased contrast, vibrancy, and platform-specific material behavior.

### System Accent And Status Colors

The HIG system color set includes red, orange, yellow, green, mint, teal, cyan, blue, indigo, purple, pink, brown, and gray families. Each color has different light, dark, and increased-contrast variants. Use color names semantically:

- **Blue:** primary actions, links, focus, selected states, navigation emphasis.
- **Red:** destructive actions, errors, severe warnings.
- **Orange / Yellow:** warnings, attention, temporary caution.
- **Green:** success, confirmation, positive status.
- **Gray:** secondary structure, fills, separators, disabled states.

Do not use the same color to mean different things. If blue means interactive in one part of the app, do not use the same blue for decorative noninteractive text nearby.

### Light, Dark, Increased Contrast

Every custom color needs four variants: light, dark, increased-contrast light, and increased-contrast dark. This is required even for apps that appear to support one appearance mode, because Liquid Glass, accessibility settings, and platform surfaces can change the effective background context.

Use system colors for text, fills, separators, and backgrounds whenever possible:

- Labels: primary, secondary, tertiary, quaternary.
- Fills: primary, secondary, tertiary.
- Separators: semantic separator values instead of hand-tuned borders.
- Backgrounds: standard, secondary, tertiary, grouped, and elevated grouped variants.

### Color On Materials

Color on glass and materials is affected by content behind it. Use vibrant colors on top of standard materials so the system can maintain foreground contrast. Avoid choosing a material because it appears to create a specific color; choose it by semantic role and opacity need.

For clear Liquid Glass over bright media, add a dark dimming layer around 35% opacity when needed for legibility. If the background is already dark or a system media control provides its own dimming, avoid adding a redundant scrim.

### Inclusive Color

Never rely on color alone. Pair color with labels, icons, shape, position, haptics, sound, or text. Test color under bright outdoor light, dim light, True Tone, P3 and sRGB displays, dark appearance, increased contrast, and visionOS environmental lighting.

## Typography

Typography in Apple interfaces is legible first, expressive second. Use the San Francisco family unless a custom typeface is necessary for brand identity. For most apps, custom fonts should be limited and should support Dynamic Type.

### System Families

- **SF Pro:** default system UI typeface for iOS, iPadOS, macOS, tvOS, and visionOS.
- **SF Compact:** optimized for watchOS.
- **SF Pro Rounded / SF Compact Rounded:** coordinate with rounded UI elements or provide a softer voice.
- **SF Mono:** code, technical readouts, fixed-width data, and developer-facing text.
- **New York:** serif family for editorial or reading-focused experiences, often paired with SF.

The system fonts are variable fonts and support optical sizing. Let the system choose optical sizing instead of manually switching between Text and Display variants unless your design tool requires it.

### Minimum Legible Sizes

Use platform default sizes as the baseline for custom text:

| Platform | Default text size | Minimum text size |
|---|---:|---:|
| iOS / iPadOS | 17 pt | 11 pt |
| macOS | 13 pt | 10 pt |
| tvOS | 29 pt | 23 pt |
| visionOS | 17 pt | 12 pt |
| watchOS | 16 pt | 12 pt |

Avoid ultralight, thin, and light weights for small text. If a custom font uses a thin weight, increase size and contrast.

### Dynamic Type

Dynamic Type is required for resilient Apple UI. Text should scale according to the user's selected size, while layout preserves hierarchy. Do not blindly scale every label equally. Prioritize important readable content; utility labels, tab titles, dense metadata, and transient HUD text may scale within tighter bounds when appropriate.

When text grows:

- Reflow instead of clipping.
- Allow multiline labels where meaning matters.
- Keep controls tappable.
- Preserve reading order.
- Hide or defer secondary information before shrinking primary content.

### Tracking

SF Pro tracking varies by point size. In the common iOS range, 17 pt body text uses negative tracking, while very large display sizes gradually return toward neutral or slightly positive tracking. Do not apply a single global letter-spacing rule. Use system text styles whenever possible so tracking follows platform defaults.

## Layout

Layout should make content easy to find, keep controls distinct from content, and adapt to device, window, orientation, size class, safe area, and input method.

### Structure

Group related items with negative space, background shapes, materials, or separators. Avoid crowding important content with secondary details. Put the most important elements near the top and leading side in the current reading direction, and mirror correctly for right-to-left languages.

Extend backgrounds and full-screen artwork to screen or window edges. Scrollable content should continue to the bottom and sides of the device screen. Navigation and controls often float above content, so the content layer may need background extension beneath sidebars, inspectors, tab bars, or toolbars.

### Alignment

Alignment communicates organization. Use consistent leading edges, baselines, list indentation, and grid spacing so people can scan while scrolling. Avoid arbitrary offsets that make hierarchy look accidental.

### Progressive Disclosure

When the full set of content or controls cannot fit, reveal complexity gradually. Show partial content, disclosure controls, search, filters, overflow menus, inspectors, or sheets. Do not create a dense permanent control surface just to avoid hiding secondary controls.

### Safe Areas

Respect safe areas by default. Content can extend behind control layers when the system provides blur, glass, or scroll edge effects, but tappable content should not be hidden under bars, hardware cutouts, rounded display corners, home indicators, window controls, or visionOS window controls.

### Platform Adaptation

| Platform | Layout behavior |
|---|---|
| iOS | Compact-width, touch-first layouts. Use navigation stacks, tab bars, sheets, lists, and 44 pt targets. |
| iPadOS | Support split views, sidebars, multitasking, resizable windows, keyboard, pointer, and regular size classes. |
| macOS | Windowed, menu-driven, keyboard-friendly layouts. Use toolbars, sidebars, inspectors, menu bar commands, and smaller 28 pt default controls. |
| tvOS | Large text, focus-driven navigation, generous spacing, media-first content, and visible partially offscreen grids. |
| visionOS | Center important content, keep controls comfortable to look at, maintain window bounds, and use ornaments for controls outside windows. |
| watchOS | Edge-to-edge content, minimal padding, full-width primary buttons, and no more than two text buttons or three glyph buttons side by side. |

## Materials And Depth

Apple platforms use two material concepts: Liquid Glass and standard materials.

### Liquid Glass

Liquid Glass is a functional layer for controls and navigation. It floats above content and helps people understand that bars, sidebars, tab bars, ornaments, and control groups are interactive system-level surfaces.

Use Liquid Glass for:

- Navigation bars.
- Tab bars.
- Sidebars.
- Toolbars.
- Ornaments.
- Control clusters floating above content.
- Transient interactive elements such as active sliders or toggles.

Do not use Liquid Glass as a decorative card surface inside the content layer. Overuse makes the hierarchy noisy and weakens the distinction between content and controls.

Liquid Glass variants:

- **Regular:** default for text-heavy or control-heavy surfaces where legibility matters.
- **Clear:** highly translucent; use over rich media when preserving the underlying image or video is the priority.

### Standard Materials

Standard materials create structure inside the content layer. They can separate grouped content, table backgrounds, side sections, or overlay views without implying that the whole region is a top-level control layer.

On iOS and iPadOS, standard material thicknesses include ultra-thin, thin, regular, and thick. Thicker materials provide more contrast; thinner materials preserve more background context.

### visionOS Glass

visionOS windows use an adaptive glass material that changes with physical surroundings and virtual content. Avoid opaque windows unless truly necessary. Keep foreground content vibrant and legible, and avoid large solid-color blocks that block spatial awareness.

## Components

### Buttons

A button initiates an immediate action. It communicates through style, content, and role.

Roles:

- **Normal:** no special semantic meaning.
- **Primary:** most likely or default action.
- **Cancel:** cancels the current task.
- **Destructive:** can destroy data or cause a serious irreversible change.

Rules:

- Use a visually prominent style for the primary action, but keep prominent buttons to one or two per view.
- Use style, not size, to distinguish the preferred action from peer options.
- Give every custom button a visible press state.
- Use familiar SF Symbols for familiar actions.
- Use short verb-led text labels when text is clearer than an icon.
- Append an ellipsis to macOS push buttons that open another window, view, or app for more input.

Minimum hit regions:

| Platform | Default control size | Minimum control size |
|---|---:|---:|
| iOS / iPadOS | 44 x 44 pt | 28 x 28 pt |
| macOS | 28 x 28 pt | 20 x 20 pt |
| tvOS | 66 x 66 pt | 56 x 56 pt |
| visionOS | 60 x 60 pt | 28 x 28 pt |
| watchOS | 44 x 44 pt | 28 x 28 pt |

### Navigation

Use platform-native navigation:

- iOS: navigation stacks and tab bars.
- iPadOS: split views, sidebars, tabs, inspectors, resizable windows.
- macOS: sidebars, toolbars, menu bar, inspectors, settings windows.
- tvOS: focusable shelves, top navigation, media-centered layouts.
- visionOS: windows, ornaments, tab bars as ornaments, spatially comfortable control placement.
- watchOS: hierarchical navigation, full-screen flows, toolbar corner buttons, Digital Crown-friendly scrolling.

Navigation should preserve orientation. People should understand where they are, what they can do next, and how to return.

### Lists And Tables

Use lists and tables when information needs scanning, comparison, selection, or editing. Preserve row height, alignment, separators, selection states, swipe actions where appropriate, keyboard navigation, VoiceOver order, and context menus.

Grouped lists use grouped backgrounds and rounded group containers. Plain lists use stronger edge-to-edge scanning and are better for large data sets.

### Search Fields

Search fields should be immediately recognizable, with a search symbol, placeholder text, clear button when populated, and keyboard focus behavior. On large surfaces, search can live in a toolbar. On compact surfaces, it can be prominent in content or appear through navigation.

### Menus And Actions

Use menus for secondary or contextual actions, not primary workflows. Group related actions and separate destructive actions. Use system roles so destructive actions receive appropriate treatment and assistive technologies can communicate meaning.

### Sheets, Popovers, Alerts

Use:

- **Sheet:** focused task, editing flow, or modal decision that can be dismissed.
- **Popover:** contextual transient content near its source.
- **Alert:** urgent, short decision or information requiring attention.

Alerts should be rare. Use clear button roles and avoid long explanatory text. Destructive actions need explicit labels and confirmation.

### Status

Communicate status with text, color, icons, progress, and accessibility labels. Do not use color alone. For loading, prefer skeletons, progress indicators, or partial content over blocking spinners when useful information can appear incrementally.

## SF Symbols And Icons

Use SF Symbols wherever possible. Symbols integrate with the San Francisco font, align with text, support weights and scales, and adapt to rendering modes.

Rendering modes:

- **Monochrome:** one color across the symbol.
- **Hierarchical:** one color with opacity levels for visual hierarchy.
- **Palette:** multiple semantic colors across layers.
- **Multicolor:** system-defined multicolor rendering.

Use hierarchical mode for most app chrome. Use palette and multicolor only when the color carries meaning and remains legible in light, dark, increased contrast, and material contexts.

Custom symbols must match SF Symbols in simplicity, optical weight, alignment, perspective, and recognizability. Provide accessibility descriptions. Do not create custom replicas of Apple products or customize restricted Apple product symbols.

Symbol animations should be purposeful. Use replace, bounce, pulse, variable color, breathe, rotate, wiggle, draw, appear, and disappear only when they clarify state, progress, or feedback. Avoid stacking multiple symbol animations in one area.

## Motion And Feedback

Motion should explain state changes, reinforce direct manipulation, and provide feedback. It should not be ornamental or disorienting.

Use:

- Press states for custom controls.
- Smooth transitions for navigation and presentation.
- Gesture-tracked movement where possible.
- Haptics and sound when the platform supports them and the feedback adds meaning.

Respect Reduce Motion:

- Reduce automatic and repetitive animations.
- Tighten springs and avoid exaggerated bounce.
- Replace large x/y/z transitions with fades.
- Avoid animated depth changes.
- Avoid animating into and out of blur.
- Avoid fast blinking and intense peripheral motion.

## Inputs

Design for every input method a platform supports.

### Touch

Touch targets need enough visible size and enough spacing. Use familiar gestures for common tasks. Provide onscreen alternatives for gestures such as swipe-to-delete, drag, multi-finger actions, or long press.

### Pointer And Keyboard

Support pointer hover, keyboard navigation, focus rings, standard keyboard shortcuts, and Full Keyboard Access. Avoid overriding system-defined shortcuts.

### tvOS Remote

Focus is the primary interaction model. Focused elements need clear scale, material, or movement feedback. Grids should reveal partial offscreen content symmetrically to indicate more items.

### visionOS Eyes And Hands

Keep controls easy to look at. Place button centers at least 60 pt apart where possible. Avoid small controls stacked densely. Do not require large repetitive gestures. Avoid anchoring content to the wearer's head.

### watchOS Digital Crown

Use the Digital Crown for scrolling, precise adjustment, and value changes. Keep controls sparse and easy to activate in short sessions.

## Accessibility

Accessibility is part of the core system, not an audit phase. An accessible interface is intuitive, perceivable, and adaptable.

### Vision

Support larger text sizes. Ideally allow text enlargement up to 200%, or 140% on watchOS. Maintain WCAG Level AA contrast guidance:

| Text | Minimum contrast |
|---|---:|
| Up to 17 pt, any weight | 4.5:1 |
| 18 pt and larger | 3:1 |
| Bold text, any size | 3:1 |

Support VoiceOver, labels, traits, values, hints, and meaningful reading order. Images need useful descriptions unless decorative.

### Hearing

Do not rely only on sound. Pair audio cues with visible indicators, haptics, captions, transcripts, or controls. Let people control audio and video playback.

### Mobility

Offer sufficiently sized controls and spacing. Add about 12 pt padding around controls with a bezel and about 24 pt around borderless visible elements. Support simple gestures and alternatives to gesture-only actions. Support Voice Control, Switch Control, AssistiveTouch, pointer control, and keyboard control.

### Speech

Keyboard-only navigation and Switch Control support are essential. Integrate App Intents, Siri, and Shortcuts for repeated or important tasks where voice-only operation would help.

### Cognitive

Reduce complexity. Use familiar interactions, avoid unnecessary timed dismissal, provide explicit controls for media, allow opt-out of autoplay, respond to Dim Flashing Lights, and simplify workflows for Assistive Access. For hard-to-recover actions, ask for confirmation twice in Assistive Access contexts.

## Platform Notes

### iOS

Design compact, touch-first views. Use 17 pt body text, 44 pt controls, navigation stacks, tab bars, sheets, and system colors. Respect safe areas and Dynamic Type. Avoid desktop-style density.

### iPadOS

Support multitasking, resizable windows, regular size classes, sidebars, keyboard shortcuts, pointer, drag and drop, and content layouts that remain useful from compact split views to full-screen canvas.

### macOS

Use the menu bar, window toolbars, sidebars, inspectors, settings windows, keyboard shortcuts, pointer affordances, and smaller control metrics. Avoid importing iOS tab-heavy navigation where macOS users expect windows and commands.

### tvOS

Design for distance. Use large text, strong focus states, generous spacing, media-forward backgrounds, and remote-friendly interaction. Minimum text size is much larger than phone UI.

### visionOS

Use glass, depth, ornaments, spatial layout, and comfortable field-of-view placement. Keep important content near the center of windows. Avoid opaque surfaces and high-contrast bright objects against very dark immersive surroundings unless the surrounding context is also bright.

### watchOS

Prioritize glanceable content. Keep flows short, use full-width primary buttons, avoid too many side-by-side controls, and use toolbar corner buttons where appropriate. The bezel supplies visual padding, so content can extend edge to edge.

## Implementation Rules

1. Use native system components before custom components.
2. Use semantic system colors before hard-coded colors.
3. Support light, dark, and increased contrast.
4. Use Dynamic Type and preserve layout at large accessibility sizes.
5. Keep primary actions visually prominent but limited.
6. Keep Liquid Glass in control/navigation layers, not decorative content cards.
7. Use SF Symbols for interface icons.
8. Provide press, selected, disabled, loading, focus, and accessibility states for every custom control.
9. Respect safe areas, size classes, and platform input methods.
10. Test with VoiceOver, Full Keyboard Access, Increase Contrast, Reduce Motion, larger text, and different appearance modes.

## Do's And Don'ts

### Do

- Use system frameworks and controls so adaptation comes for free.
- Create a clear distinction between content and controls.
- Let color carry semantic meaning consistently.
- Use SF Pro, SF Compact, SF Mono, New York, and SF Symbols as intended.
- Preserve minimum text sizes and control sizes by platform.
- Use progressive disclosure for complexity.
- Provide alternatives for gestures.
- Test with accessibility settings, real devices, and multiple lighting conditions.
- Use platform-specific layouts instead of forcing one layout across all devices.

### Don't

- Don't treat Apple HIG as a set of decorative visual effects.
- Don't use Liquid Glass everywhere.
- Don't make content and controls look like the same layer.
- Don't rely on color alone for state or meaning.
- Don't use tiny text because it fits a mockup.
- Don't override familiar system gestures or keyboard shortcuts without a strong reason.
- Don't create custom icons when SF Symbols already provides a recognizable symbol.
- Don't use many prominent buttons in one view.
- Don't force complex gestures for common repeated actions.
- Don't ignore dark mode, increased contrast, Reduce Motion, or larger text.

## Responsive And Adaptive Checklist

Use this checklist before considering an Apple-platform UI complete:

- Light mode works.
- Dark mode works.
- Increased contrast works.
- Reduce Transparency works.
- Reduce Motion works.
- Dynamic Type works through accessibility sizes.
- VoiceOver reads content in the right order.
- Buttons and controls expose labels, traits, values, and hints.
- Keyboard-only navigation works where applicable.
- Pointer hover and focus states work where applicable.
- Touch targets meet platform minimums.
- Layout respects safe areas and system controls.
- Content extends appropriately behind control layers without hiding essential information.
- Right-to-left layout mirrors correctly.
- Destructive actions are clearly labeled and confirm when necessary.
- Color is not the only indicator of state.

## Known Gaps

This document summarizes Apple HIG into an implementable design reference. It does not replace Apple's official documentation, platform SDK docs, or design resource templates. Device dimensions, color values, SF Symbols availability, Liquid Glass behavior, and component APIs can change with new OS releases, so verify against Apple's current pages when implementing production UI.

