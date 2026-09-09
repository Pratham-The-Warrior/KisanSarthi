---
name: KisanSarthi
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#414844'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#5b6300'
  on-secondary: '#ffffff'
  secondary-container: '#dfec60'
  on-secondary-container: '#616a00'
  tertiary: '#002d1c'
  on-tertiary: '#ffffff'
  tertiary-container: '#00452e'
  on-tertiary-container: '#75b393'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#dfec60'
  secondary-fixed-dim: '#c2cf47'
  on-secondary-fixed: '#1a1d00'
  on-secondary-fixed-variant: '#444b00'
  tertiary-fixed: '#b1f0ce'
  tertiary-fixed-dim: '#95d4b3'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#0e5138'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  section-gap: 80px
---

## Brand & Style

The brand identity bridges the gap between high-tech data science and grounded agricultural practice. It is designed to evoke a sense of "Precision Growth"—professional, reliable, and technologically advanced. The target audience includes modern farm owners, agronomists, and institutional stakeholders who require clarity in data and premium quality in execution.

The design style is **Modern Premium**. It utilizes a "Clean Slate" approach with a pure white foundation to symbolize transparency and freshness. This is contrasted with sophisticated layers of green that represent life and prosperity. The aesthetic borrows from **Minimalism** (expansive whitespace and crisp typography) and **Glassmorphism** (translucent data overlays) to create a UI that feels light yet deeply informative. Subtle geometric patterns, inspired by topographies and geofencing coordinates, provide a secondary layer of texture that reinforces the agricultural tech narrative.

## Colors

The palette is rooted in the "Forest to Field" spectrum. 

- **Primary (Forest Green):** A deep, authoritative green used for navigation, primary headings, and grounding elements. It establishes trust and stability.
- **Secondary (Vibrant Lime):** A high-energy, high-contrast accent used exclusively for primary calls to action and critical status indicators. It represents growth and innovation.
- **Tertiary (Emerald):** A mid-tone green used for data visualization, secondary buttons, and success states.
- **Neutral/Background:** A foundation of pure white (#FFFFFF) is used for the primary canvas, while a very light gray (#F8F9FA) defines "Land DNA" surface containers. 

Text should primarily be set in a dark charcoal or the primary forest green to ensure legibility and a premium feel.

## Typography

This design system uses a dual-font strategy to balance professional impact with technical readability.

- **Headlines:** Montserrat provides a strong, geometric, and modern presence. It should be used for all major section headers and hero titles.
- **Body & Data:** Inter is used for its exceptional legibility and neutral tone, making it ideal for dense agricultural data, reports, and administrative tasks.
- **Hierarchy:** Use tight letter spacing for large headlines to maintain a "premium editorial" feel. Labels and small metadata should use uppercase Inter with increased letter spacing for a technical, "data-mapped" appearance.

## Layout & Spacing

The layout philosophy centers on **Spacious Data Visualization**. It utilizes a 12-column fluid grid for desktop and a single-column flow for mobile.

- **Margins & Gutters:** Generous 24px gutters ensure that complex data cards never feel cluttered. Desktop margins are expansive (48px) to push content toward the center, creating a focused, high-end experience.
- **Rhythm:** Spacing follows an 8px incremental scale. Use larger gaps (section-gap) between distinct data modules to allow the UI to "breathe."
- **Content Blocks:** Information should be grouped into logical "Plots" (cards), mimicking the organized structure of an efficiently managed farm.

## Elevation & Depth

Hierarchy is achieved through a combination of tonal layering and soft, ambient shadows.

- **Surface Layers:** The base is pure white. Secondary containers use a subtle "off-white" or light gray background to create a tiered look without heavy borders.
- **Shadows:** Use extremely soft, diffused shadows (Blur: 20px-40px, Opacity: 4-6%) with a slight primary-color tint. This makes cards appear as if they are floating gently over the "DNA" patterned background.
- **Glassmorphism:** For overlays, modals, and navigation bars, use a backdrop-blur (12px) with a 70% white tint. This creates a high-tech, sophisticated "lens" effect over map data or complex charts.

## Shapes

The shape language is "Organic Geometric." 

Standard elements use a 12px radius (`rounded`) to feel approachable and modern. Larger containers like main dashboard cards should use a 16px to 24px radius (`rounded-xl`) to emphasize the premium, friendly nature of the brand. Avoid sharp corners entirely to distinguish the product from legacy industrial software.

## Components

- **Buttons:** Primary buttons use the Secondary Lime Green with dark text for maximum visibility. Secondary buttons should be ghost-styled with a Forest Green border or solid Forest Green with white text.
- **Cards:** White backgrounds, 16px corner radius, and soft ambient shadows. Include a subtle 1px border (#E9ECEF) to define edges against the white canvas.
- **Input Fields:** Clean, minimal styling. Use a 1px Forest Green border on focus. Labels should be small, uppercase, and positioned above the field for clarity.
- **Chips & Tags:** Use for status (e.g., "Harvest Ready", "Low Moisture"). These should have semi-transparent background tints of their respective status colors (Emerald for success, Amber for warning).
- **Data Visualization:** Line charts and geofencing maps should use vibrant greens and teals. Grid lines should be faint, and interactive points should have a subtle glow effect.
- **Progress Bars:** Use thick, rounded bars with the Emerald-to-Lime gradient to signify growth and completion.