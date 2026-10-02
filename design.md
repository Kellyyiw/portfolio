---
name: Editorial Bento
colors:
  surface: '#fdf9f0'
  surface-dim: '#dedad1'
  surface-bright: '#fdf9f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ea'
  surface-container: '#f2ede4'
  surface-container-high: '#ece8df'
  surface-container-highest: '#e6e2d9'
  on-surface: '#1c1c16'
  on-surface-variant: '#444748'
  inverse-surface: '#32302a'
  inverse-on-surface: '#f5f0e7'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5e5e5b'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdb'
  on-secondary-container: '#63635f'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#410000'
  on-tertiary-container: '#ea4c3a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#e4e2dd'
  secondary-fixed-dim: '#c8c6c2'
  on-secondary-fixed: '#1b1c19'
  on-secondary-fixed-variant: '#474744'
  tertiary-fixed: '#ffdad4'
  tertiary-fixed-dim: '#ffb4a8'
  on-tertiary-fixed: '#410000'
  on-tertiary-fixed-variant: '#920703'
  background: '#fdf9f0'
  on-background: '#1c1c16'
  surface-variant: '#e6e2d9'
typography:
  display-2xl:
    fontFamily: Bodoni Moda
    fontSize: 120px
    fontWeight: '700'
    lineHeight: 110px
    letterSpacing: -0.04em
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 72px
    fontWeight: '600'
    lineHeight: 76px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  nav-link:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
spacing:
  unit: 8px
  grid-margin: 64px
  grid-gutter: 1px
  container-padding: 32px
  bento-gap: 24px
---

## Brand & Style
The design system is rooted in high-end editorial aesthetics, blending the structural rigidity of a bento-style grid with the fluid elegance of a fashion lookbook. It targets high-profile creators and luxury portfolios where white space is as functional as the content itself. 

The personality is **sophisticated, intentional, and unapologetically bold**. It avoids extraneous decoration, relying instead on "maximalist minimalism"—where few elements exist, but those that do are rendered with extreme scale and precision. The goal is to evoke a sense of timelessness and professional authority through stark contrast and architectural layout.

## Colors
The palette is restricted to three core tones to maintain editorial tension. 

- **Primary (Charcoal):** Used for all primary headlines, body copy, and heavy structural elements.
- **Secondary (Off-White):** The canvas. This warm, papery tone prevents the "digital fatigue" of pure white and provides a premium, tactile feel.
- **Tertiary (Deep Crimson):** A surgical accent. Used exclusively for primary calls to action, active states, or critical highlights. It should never exceed 5% of the screen real estate.
- **Neutral (Stone):** A subtle mid-tone used for the fine-line grid borders and secondary metadata.

## Typography
The typographic strategy relies on the friction between the neo-classical elegance of **Bodoni Moda** and the utilitarian precision of **Inter**.

- **Headlines:** Use Bodoni Moda. This typeface brings a scholarly, high-fashion authority to the design. For section headers, embrace "massive" sizing that occasionally overflows the grid container for artistic effect.
- **Body:** Inter provides a neutral, highly legible counterpoint. Use wider tracking for small labels and navigation to enhance the "luxury brand" feel.
- **Hierarchy:** Maintain a strict distinction. Serif is for "emotion and impact," while Sans-serif is for "utility and information."

## Layout & Spacing
This design system utilizes a **Bento Box Grid**—a modular system where content is housed in rectangular "cells" of varying sizes.

- **The Grid:** A 12-column foundation. However, visually, the layout is defined by 1px "fine-line" borders in the Neutral tone (#e5e1d8) that separate cells. 
- **Bento Cells:** Cells should vary in aspect ratio. Use a mix of 1x1, 2x1, and 2x2 blocks.
- **Padding:** Content inside a bento cell should have generous, uniform padding (32px minimum) to keep the layout feeling airy despite the rigid borders.
- **Responsive:** On mobile, the 12-column grid collapses to a single column, but the 1px dividers remain to maintain the modular look.

## Elevation & Depth
In line with the Modern Minimalism style, this system is **strictly flat**. 

- **Depth:** Achieved through layering and color blocking rather than shadows. 
- **Borders:** Use 1px solid lines for all containers. Avoid rounded corners; depth is implied by the structural overlap of these containers.
- **Interactions:** Use tonal shifts (e.g., a cell background changing from Off-White to a very light Grey) to indicate hover states. 
- **Glassmorphism:** Reserved exclusively for fixed navigation bars to ensure content remains visible beneath the UI as the user scrolls.

## Shapes
The shape language is **geometric and sharp**. 

- **Corners:** 0px radius for all primary containers, buttons, and images. This reinforces the architectural and editorial feel.
- **Images:** All photography should be cropped to hard rectangles.
- **Exceptions:** No exceptions. Even "pills" or "chips" should be rendered as rectangular boxes with small internal padding and uppercase labels.

## Components
- **Primary Button:** Solid Charcoal background with Off-White text. Rectangular, no radius. On hover, background shifts to Deep Crimson.
- **Bento Cards:** The foundational component. Each card has a 1px Stone border. Content can be an image (flush to edges) or text (with 32px padding).
- **Input Fields:** Bottom-border only (1px Charcoal). No background fill. Labels use the `label-caps` typography style.
- **Navigation:** A minimalist top bar. Links are uppercase with wide tracking. The active page is indicated by a Deep Crimson dot or a 1px underline.
- **Chips/Tags:** Small rectangular boxes with a 1px border. Use for categories or "Year" metadata in a portfolio.
- **Image Overlays:** When text appears over images, use a subtle Charcoal gradient (bottom-up) to ensure the high-contrast typography remains legible.