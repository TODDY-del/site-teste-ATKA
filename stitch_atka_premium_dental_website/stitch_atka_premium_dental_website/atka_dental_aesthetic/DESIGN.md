---
name: Atka Dental Aesthetic
colors:
  surface: '#14130f'
  surface-dim: '#14130f'
  surface-bright: '#3a3934'
  surface-container-lowest: '#0f0e0a'
  surface-container-low: '#1c1c17'
  surface-container: '#20201b'
  surface-container-high: '#2b2a25'
  surface-container-highest: '#36352f'
  on-surface: '#e6e2da'
  on-surface-variant: '#c1c7c9'
  inverse-surface: '#e6e2da'
  inverse-on-surface: '#31302b'
  outline: '#8c9294'
  outline-variant: '#42484a'
  surface-tint: '#afcbd3'
  primary: '#afcbd3'
  on-primary: '#19343a'
  primary-container: '#0e2a30'
  on-primary-container: '#779299'
  inverse-primary: '#486369'
  secondary: '#a3ced7'
  on-secondary: '#05363e'
  secondary-container: '#254f57'
  on-secondary-container: '#96bfc9'
  tertiary: '#f7ba8c'
  on-tertiary: '#4c2705'
  tertiary-container: '#3f1d00'
  on-tertiary-container: '#b78158'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#cbe7ef'
  primary-fixed-dim: '#afcbd3'
  on-primary-fixed: '#021f25'
  on-primary-fixed-variant: '#304b51'
  secondary-fixed: '#bfeaf4'
  secondary-fixed-dim: '#a3ced7'
  on-secondary-fixed: '#001f25'
  on-secondary-fixed-variant: '#234c55'
  tertiary-fixed: '#ffdcc4'
  tertiary-fixed-dim: '#f7ba8c'
  on-tertiary-fixed: '#2f1400'
  on-tertiary-fixed-variant: '#673d19'
  background: '#14130f'
  on-background: '#e6e2da'
  surface-variant: '#36352f'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '200'
    lineHeight: '1.1'
    letterSpacing: 0.1em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '300'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '300'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  title-md:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '300'
    lineHeight: '1.6'
    letterSpacing: 0px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0px
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.15em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  section-gap: 120px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The brand identity is built upon the concept of "Serene Precision." It targets a high-end demographic seeking both clinical excellence and a spa-like aesthetic experience. The UI must evoke feelings of calm, reliability, and modern luxury.

The design system utilizes a **Minimalist** approach with **High-Contrast** accents. It rejects the clinical sterility of traditional medical platforms in favor of a sophisticated "dark mode" sanctuary. Visuals are characterized by generous whitespace (represented here by deep petrol voids), thin geometric lines, and a deliberate, slow-paced rhythm.

## Colors

The palette is anchored by **Deep Petrol (#0E2A30)**, providing a grounding, high-end foundation that reduces eye strain and implies exclusivity. 

- **Primary Background**: #0E2A30 (Deep Petrol). Used for all main page surfaces.
- **Surface Secondary**: #6E97A0 (Muted Sage-Teal). Used for subtle grouping and secondary containers to provide depth without breaking the dark aesthetic.
- **Accent**: #C0895F (Copper). Reserved for interactive highlights, call-to-action elements, and decorative structural lines.
- **Typography (Primary)**: #E9E5DD (Cream). Provides a soft, readable contrast against the dark background, avoiding the harshness of pure white.
- **Typography (Secondary)**: #A9C3C8 (Soft Light-Blue). Used for metadata, captions, and de-emphasized information.

## Typography

The typography system relies on the contrast between the airy, architectural qualities of **Hanken Grotesk** and the functional clarity of **Inter**.

- **Headlines**: Set in Hanken Grotesk with light weights (200-300). Display styles must use wide letter spacing and, for the logo and primary section headers, uppercase styling to emphasize the geometric nature of the characters.
- **Body**: Set in Inter for maximum legibility in clinical descriptions and service lists. A light weight (300) is preferred for larger body text to maintain the "premium" feel.
- **Copper Accents**: Every major section headline should be followed by a thin (1px) horizontal line in Copper (#C0895F), extending either 40px or to the edge of the container.

## Layout & Spacing

This design system employs a **Fixed Grid** on desktop and a **Fluid Grid** on mobile. The spacing philosophy is "Luxurious Expansion"—using oversized margins and gaps to create a sense of breathing room.

- **Grid**: 12-column grid for desktop with 24px gutters.
- **Section Gaps**: Use a generous 120px vertical gap between major content blocks to signify a transition in the user's journey.
- **Horizontal Alignment**: Content should be centered within a 1280px max-width container. 
- **Mobile Adaptivity**: At the 768px breakpoint, margins reduce to 20px, and section gaps shrink to 64px. Elements should reflow to a single-column stack.

## Elevation & Depth

To maintain the minimalist aesthetic, the system avoids traditional drop shadows. Depth is communicated through **Tonal Layering** and **Subtle Outlines**.

- **Surface Tiers**: The base layer is #0E2A30. Cards or floating panels use #6E97A0 at low opacity (10-15%) or a slightly lighter tint of the primary background to create a "recessed" or "elevated" look without shadows.
- **Photography**: Images must use a 30-40% dark petrol overlay to ensure text legibility and visual cohesion.
- **Borders**: Instead of shadows, use 1px solid borders in #A9C3C8 (at 20% opacity) to define component boundaries.

## Shapes

The shape language is dominated by **Pill-shaped (Full Radius)** elements for interactive components and **Sharp** corners for structural layout elements (like section containers and image frames). This juxtaposition creates a balance between clinical precision and organic comfort.

- **Interactive Elements**: Buttons and chips always use a full pill radius.
- **Structural Elements**: Photography and large containers use 0px radius to maintain an architectural, "gallery" feel.

## Components

- **Buttons**: Pill-shaped with a 1px border. Primary buttons use #C0895F (Copper) for the border and text. Secondary buttons use #A9C3C8. Hover states should include a subtle background fill of the border color at 10% opacity.
- **Input Fields**: Minimalist style. Only a bottom border (1px) in #A9C3C8. Labels sit above the line in `label-sm` typography.
- **Cards**: No background fill by default. Defined by a 1px border of #6E97A0 (20% opacity) or simply by white space and alignment.
- **Chips/Badges**: Small pill-shaped tags used for service categories (e.g., "Aesthetic," "Surgical"). Use `label-sm` typography.
- **List Items**: Separated by thin 1px horizontal lines in #6E97A0 (15% opacity), creating a clean, ledger-like appearance.
- **Copper Accents**: A signature element where a 1px Copper line follows a heading, providing a high-end editorial feel to the layout.