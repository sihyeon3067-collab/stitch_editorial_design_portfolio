---
name: Radical Editorial
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#594048'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#8d6f78'
  outline-variant: '#e0bec7'
  surface-tint: '#b90066'
  primary: '#b40064'
  on-primary: '#ffffff'
  primary-container: '#da227d'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb0ca'
  secondary: '#5e5f5b'
  on-secondary: '#ffffff'
  secondary-container: '#e3e3de'
  on-secondary-container: '#646561'
  tertiary: '#5d5c5b'
  on-tertiary: '#ffffff'
  tertiary-container: '#767474'
  on-tertiary-container: '#f7feff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e3'
  primary-fixed-dim: '#ffb0ca'
  on-primary-fixed: '#3e001f'
  on-primary-fixed-variant: '#8d004d'
  secondary-fixed: '#e3e3de'
  secondary-fixed-dim: '#c7c7c2'
  on-secondary-fixed: '#1b1c19'
  on-secondary-fixed-variant: '#464744'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c9c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-xl:
    fontFamily: Hanken Grotesk
    fontSize: 120px
    fontWeight: '800'
    lineHeight: 110px
    letterSpacing: -0.04em
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 80px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  meta-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 54px
    letterSpacing: -0.04em
spacing:
  margin-desktop: 64px
  margin-mobile: 20px
  gutter: 24px
  section-gap: 160px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

This design system is built for a high-end personal design portfolio that prioritizes communication design as an art form. It draws heavily from **Minimalism** and **Modernism**, with an experimental edge that mimics the layout of avant-garde print magazines.

The brand personality is confident, precise, and intellectually curious. The interface acts as a silent gallery frame—highly structured yet invisible—allowing the creative work to take center stage. By removing traditional UI decorations like borders, shadows, and gradients, the system relies on radical scale, extreme negative space, and rigid typographic alignment to communicate hierarchy and sophistication.

## Colors

The palette is limited to three core players to maintain high-impact editorial clarity:
- **Primary (Vibrant Pink):** Used sparingly as a "highlighter" for active states, calls to action, and signature branding elements. It should feel electric against the muted base.
- **Secondary (Warm Off-White):** The canvas. A soft, paper-like background that feels more premium and less sterile than pure white.
- **Tertiary (Deep Black):** Reserved for the "Ink"—all primary typography and structural lines.
- **Neutral (Slate Gray):** Used for low-priority metadata and placeholder states.

Color is never used for decoration; it is used for navigation and emphasis. Surfaces should remain flat with no depth effects.

## Typography

The typography system is the primary driver of the visual identity. It uses two Sans-Serif faces to create a hierarchy of "Impact" vs "Information."

- **Display & Headlines:** Use **Hanken Grotesk**. For large-scale display text (project titles, numbers), the tracking should be set to -4% to create a tight, architectural block of text.
- **Body & Metadata:** Use **Inter**. This provides a neutral, utilitarian counterpoint to the aggressive display type. Body text should be set in medium-length columns to ensure readability.
- **Uppercase Labels:** Used for section headers or small navigation items to create a rhythmic "break" in the reading experience.

Avoid italics. Use weight and scale to differentiate meaning.

## Layout & Spacing

This system utilizes a **12-column asymmetric fluid grid**. Unlike standard web layouts, content should purposefully skip columns to create "white-space pockets," mimicking a print magazine spread.

- **Asymmetry:** Key project descriptions might occupy columns 1-4, while the imagery sits in columns 6-12.
- **Vertical Rhythm:** Use massive vertical gaps (`section-gap`) to separate distinct projects or chapters. This forces the user to focus on one piece of work at a time.
- **Alignment:** Use hard-edge alignment. Text should often be top-aligned with the top edge of adjacent imagery to create a strong horizontal datum line.
- **Mobile:** Transition to a 4-column grid. Prioritize the massive display type, allowing it to bleed or break across lines to maintain its "loud" personality.

## Elevation & Depth

This design system is **strictly flat**. Depth is achieved solely through **Layering and Scale**, never through lighting effects.

1.  **Spatial Layering:** Elements may overlap (e.g., large background typography sitting behind a project image).
2.  **No Shadows:** Do not use box-shadows or drop-shadows. Hierarchy is established by the size of the element and its proximity to other elements.
3.  **Tonal Planes:** Use the Primary Pink color to create "flat planes" of color that sit behind text or images to highlight specific modules.
4.  **Zero Borders:** Container edges are defined by the end of the content or the background color change, not by stroke lines.

## Shapes

The shape language is **Sharp (0px)**. 

All image containers, buttons, and UI modules must have 90-degree corners. This reinforces the "architectural" and "editorial" feel of the system. The only exception to this rule is the typography itself or specific organic brand assets. All functional UI elements must remain strictly rectangular.

## Components

**Buttons**
Buttons are large, rectangular blocks of Primary Pink or Deep Black. Text inside is always `label-caps`. Hover states should involve a simple color inversion (e.g., Pink background with Black text flips to Black background with Pink text). No transition easing; the change should be instant and digital.

**Project Cards**
Images are full-bleed within their grid columns. Titles are placed using `display-lg` typography, often overlapping the image slightly or placed in the gutter to create an experimental look. Metadata (Year, Category) is set in `meta-sm` and right-aligned to the container.

**Input Fields**
Simple bottom-border only (1px solid Black). Label sits above in `label-caps`. Focus state changes the bottom border to Primary Pink.

**Navigation**
A persistent header that is purely typographic. Links are set in `label-caps`. The active page is indicated by a Primary Pink strike-through or a simple color change.

**Project Numbers**
Use `display-xl` typography for index numbers (e.g., 01, 02). These can be used as watermark-style background elements or as large anchors for section starts.