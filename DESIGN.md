---
name: Serene Growth
colors:
  surface: '#f8faf5'
  surface-dim: '#d9dbd5'
  surface-bright: '#f8faf5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4ef'
  surface-container: '#edeee9'
  surface-container-high: '#e7e9e3'
  surface-container-highest: '#e1e3de'
  on-surface: '#191c19'
  on-surface-variant: '#3e4a39'
  inverse-surface: '#2e312e'
  inverse-on-surface: '#f0f1ec'
  outline: '#6e7b67'
  outline-variant: '#becbb4'
  surface-tint: '#106e00'
  primary: '#106e00'
  on-primary: '#ffffff'
  primary-container: '#38b021'
  on-primary-container: '#053b00'
  inverse-primary: '#69e04e'
  secondary: '#3d6934'
  on-secondary: '#ffffff'
  secondary-container: '#bdf0ae'
  on-secondary-container: '#436f3a'
  tertiary: '#556250'
  on-tertiary: '#ffffff'
  tertiary-container: '#909d89'
  on-tertiary-container: '#293425'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#85fd67'
  primary-fixed-dim: '#69e04e'
  on-primary-fixed: '#022100'
  on-primary-fixed-variant: '#0a5300'
  secondary-fixed: '#bdf0ae'
  secondary-fixed-dim: '#a2d494'
  on-secondary-fixed: '#002201'
  on-secondary-fixed-variant: '#25501f'
  tertiary-fixed: '#d9e7d0'
  tertiary-fixed-dim: '#bdcbb5'
  on-tertiary-fixed: '#131e10'
  on-tertiary-fixed-variant: '#3e4a39'
  background: '#f8faf5'
  on-background: '#191c19'
  surface-variant: '#e1e3de'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 80px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style

This design system is built on a foundation of empathy, clarity, and personal development. The visual narrative utilizes a **Corporate / Modern** aesthetic with a soft, organic lean, ensuring the interface feels professional yet deeply approachable. 

The brand personality is characterized by "gentle authority"—providing expert guidance while maintaining a warm, accessible presence. The UI should evoke feelings of calmness, safety, and optimism, using generous negative space and a harmonious color palette to reduce cognitive load for users seeking counseling or personal growth services.

## Colors

The palette is rooted in nature-inspired greens to symbolize growth and renewal. 

- **Primary:** A vibrant, confident green used for primary actions and key emphasis.
- **Secondary:** A soft sage green used for hero backgrounds and secondary containers to soften the visual impact.
- **Tertiary:** A very light, tinted mint used for subtle section backgrounds and large surface areas.
- **Neutral:** A deep charcoal (not pure black) is used for typography to maintain high readability without the harshness of high-contrast black on white.
- **Base:** The primary background is a clean white to maintain a sense of clinical purity and organization.

## Typography

The design system utilizes **Plus Jakarta Sans** across all levels. This typeface offers a perfect balance between geometric modernism and friendly, rounded terminals that align with the brand’s approachable nature.

Headlines should be bold and impactful, using tighter letter-spacing to create a strong visual anchor. Body text prioritizes legibility with generous line heights (1.6) to ensure long-form content is easy to digest for users who may be in a stressed state of mind.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop to ensure a curated, editorial feel, transitioning to a fluid model for smaller breakpoints.

- **Desktop:** 12-column grid with a 1200px max-width, 24px gutters, and 64px side margins.
- **Mobile:** Single column with 20px side margins.
- **Rhythm:** Vertical rhythm follows an 8px base unit. Section spacing is intentionally generous (80px+) to maintain a "breathable" atmosphere, reflecting the mental clarity the service provides.

## Elevation & Depth

Visual hierarchy is established primarily through **Tonal Layers** and **Ambient Shadows**.

- **Surfaces:** Use white cards against the tertiary green background to create immediate focus.
- **Shadows:** Utilize "Large & Soft" shadows for cards. Shadows should be highly diffused (30-40px blur) with a very low opacity (5-8%) and a slight tint of the neutral charcoal color to avoid a "dirty" look.
- **Interaction:** On hover, cards should lift slightly (y-offset increase) and the shadow should expand, simulating a physical tactile response.

## Shapes

The shape language is consistently **Rounded**. Hard corners are avoided to maintain the "approachable" brand pillar.

- **Standard Elements:** 0.5rem (8px) for input fields and small buttons.
- **Cards & Containers:** 1.5rem (24px) for hero cards and service highlight containers to create a soft, friendly frame for content.
- **Images:** Should feature rounded corners or organic, blob-like masking to mirror the fluid nature of human emotions.

## Components

### Buttons
- **Primary:** Filled with the primary green, white text, 8px or pill-shaped roundedness. Bold typography.
- **Secondary:** Outlined with a 2px primary green border or a light green tonal fill with dark green text.

### Cards
Cards are the primary content vehicle. They must feature a white background, 24px corner radius, and the defined ambient shadow. Internal padding should be a minimum of 32px to ensure the content doesn't feel cramped.

### Input Fields
Fields should use a subtle light-gray border (or tertiary green border) that thickens and changes to primary green on focus. Labels should be placed above the field in the `label-md` style.

### Navigation
The navigation bar should be clean, using the secondary green as a background or a semi-transparent blur effect. Links should use `label-md` with a clear active state indicated by a weight change or a subtle underline.

### Chips/Tags
Used for service categories, these should use the tertiary green background with dark green text and fully rounded (pill) corners.