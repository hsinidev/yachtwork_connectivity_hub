---
name: Yacht-Work Executive Interface
colors:
  surface: '#0e131e'
  surface-dim: '#0e131e'
  surface-bright: '#343946'
  surface-container-lowest: '#090e19'
  surface-container-low: '#171b27'
  surface-container: '#1b1f2b'
  surface-container-high: '#252a36'
  surface-container-highest: '#303541'
  on-surface: '#dee2f2'
  on-surface-variant: '#c5c6d2'
  inverse-surface: '#dee2f2'
  inverse-on-surface: '#2b303c'
  outline: '#8e909c'
  outline-variant: '#444650'
  surface-tint: '#b3c5ff'
  primary: '#b3c5ff'
  on-primary: '#0d2c6e'
  primary-container: '#002366'
  on-primary-container: '#758dd5'
  inverse-primary: '#435b9f'
  secondary: '#c6c6c6'
  on-secondary: '#2f3131'
  secondary-container: '#484949'
  on-secondary-container: '#b8b8b8'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#272929'
  on-tertiary-container: '#8f9090'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#00174a'
  on-primary-fixed-variant: '#2a4386'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#0e131e'
  on-background: '#dee2f2'
  surface-variant: '#303541'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
  data-mono:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin: 32px
  container-max: 1440px
  bento-gap: 16px
---

## Brand & Style

This design system embodies the precision and prestige of maritime engineering. The aesthetic is **Executive & Sleek**, designed to instill a sense of absolute command and control for luxury yacht fleet management. It targets high-net-worth individuals and elite yacht engineers who require high-density data presented with aesthetic clarity.

The visual narrative combines **Glassmorphism** for data overlays with a **Corporate Modern** structural foundation. The "Bento-box" layout provides a modular, high-tech organization of complex network metrics, while subtle metallic textures and linear gradients evoke the brushed steel and chrome hardware found in a modern bridge. The result is an authoritative interface that feels both cutting-edge and timelessly premium.

## Colors

The palette is anchored by **Deep Royal Blue (#002366)**, serving as the primary brand identifier and the foundation for deep-space backgrounds. **Crisp White** is utilized strictly for high-contrast typography and essential iconography to ensure legibility against dark surfaces.

**Brushed Steel (#C0C0C0)** serves as the primary accent color, used for structural borders, interactive states, and metallic finishes. A "Steel Gradient" is employed for primary call-to-action elements to simulate a physical, tactile button. The color mode is strictly dark to reduce glare on maritime bridges and maintain an "executive dashboard" atmosphere.

## Typography

The typography utilizes **Inter** to maintain a neutral, systematic, and highly legible appearance across technical data sets. The hierarchy is structured to prioritize quick scanning of network statuses.

**Headline-LG** is reserved for yacht names or high-level system statuses. **Label-Caps** is used for category headers within bento-box modules to provide a structured, architectural feel. For numerical data and IP addresses, a tighter tracking and medium weight are applied to ensure data density doesn't compromise clarity.

## Layout & Spacing

This design system utilizes a **Fixed Grid** layout for desktop, centered within a 1440px container to maintain an executive feel on ultra-wide displays. A **12-column grid** forms the basis of the bento-box architecture, where components typically span 3, 4, 6, or 12 columns.

Spacing is strictly derived from a **4px base unit**. The "Bento-gap" of 16px is consistent across all dashboard views to create a tight, engineered aesthetic. On mobile devices, the grid collapses to a single column with 16px side margins, while maintaining the same bento-box module spacing to preserve the modular identity.

## Elevation & Depth

Hierarchy is achieved through **Glassmorphism** and tonal layering rather than traditional drop shadows.
1.  **Base Layer:** The Deep Royal Blue (#002366) background, often with a subtle radial gradient toward the center.
2.  **Bento Layer:** Semi-transparent "containers" using a backdrop-blur (20px to 40px) and a 1px solid Brushed Steel (#C0C0C0) border at 20% opacity.
3.  **Active Layer:** Elements requiring immediate attention use a high-opacity metallic finish or a "glow" effect using the primary blue to simulate illuminated hardware.

Shadows, when used, are low-spread and high-opacity, mimicking the look of an inset physical panel rather than a floating element.

## Shapes

The shape language is defined by **Medium Roundedness (0.5rem)**. This provides a balance between the hard-edged precision of maritime instruments and the approachability of modern software. 

Data cards and bento-box modules use `rounded-lg` (1rem) to create clear visual separation, while buttons and input fields utilize `rounded-md` (0.5rem) to maintain a crisp, professional profile. Circular elements are reserved strictly for status indicators (e.g., Online/Offline pings).

## Components

### Buttons
Primary buttons feature a **linear metallic gradient** (Brushed Steel) with dark navy text. Hover states introduce a subtle inner glow. Secondary buttons use a "Ghost" style with a 1px silver border and no fill.

### Data Cards (Bento Boxes)
These are the core of the system. Each card features a **20px backdrop-blur**, a subtle 1px border, and a title section in **Label-Caps**. Cards should be used to group related telemetry (e.g., Starlink signal, local Wi-Fi, internal server health).

### Inputs & Controls
Input fields use a dark, semi-transparent fill (`rgba(0,0,0,0.2)`) with silver bottom-borders only, creating a sleek, minimal appearance. Sliders for bandwidth control feature a metallic "thumb" and a royal blue progress track.

### Status Indicators
High-tech "Pings" use radial glows to signify connectivity status: Emerald for active, Amber for throttled, and Crimson for disconnected. These should be paired with the **Data-Mono** font for real-time latency values.

### Navigation
The sidebar is a high-blur glass panel that runs the full height of the viewport, using silver iconography and a vertical "active" indicator line in white.