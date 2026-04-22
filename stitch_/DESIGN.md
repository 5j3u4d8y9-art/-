---
name: Wufeng Chaoyang Design System
colors:
  surface: '#fff8f5'
  surface-dim: '#e1d8d4'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ed'
  surface-container: '#f5ece7'
  surface-container-high: '#efe6e2'
  surface-container-highest: '#e9e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#58413a'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#8c7169'
  outline-variant: '#e0c0b6'
  surface-tint: '#a93705'
  primary: '#a93705'
  on-primary: '#ffffff'
  primary-container: '#f26b3a'
  on-primary-container: '#571700'
  inverse-primary: '#ffb59c'
  secondary: '#7b5800'
  on-secondary: '#ffffff'
  secondary-container: '#fdc656'
  on-secondary-container: '#735200'
  tertiary: '#496640'
  on-tertiary: '#ffffff'
  tertiary-container: '#7e9d72'
  on-tertiary-container: '#193313'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59c'
  on-primary-fixed: '#390c00'
  on-primary-fixed-variant: '#832700'
  secondary-fixed: '#ffdea4'
  secondary-fixed-dim: '#f4be4e'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4200'
  tertiary-fixed: '#caecbc'
  tertiary-fixed-dim: '#afd0a1'
  on-tertiary-fixed: '#062104'
  on-tertiary-fixed-variant: '#324e2a'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

The brand personality of this design system is **Radiant, Rooted, and Professional**. It captures the essence of a "New Morning" (Chaoyang) in the Wufeng district, blending the energy of a rising sun with the grounded stability of a cultural community. 

The design style follows a **Modern Corporate** aesthetic infused with **Minimalism**. It prioritizes clarity and structure to ensure event information is easily digestible, while using vibrant color accents to evoke optimism. The UI should feel airy and expansive, mirroring the openness of a landscape at dawn. Visual elements should avoid clutter, favoring purposeful whitespace and high-quality photography of the Wufeng area to build an emotional connection with the audience.

## Colors

The palette is inspired by the transition of light during a Wufeng sunrise. 

- **Primary (Sunrise Orange):** An active, energetic hue used for primary calls-to-action and key brand moments.
- **Secondary (Soft Morning Gold):** Used for highlights, accents, and secondary buttons to provide warmth without overwhelming the user.
- **Tertiary (Earthy Forest Green):** Represents the lush topography of Wufeng. Use this for environmental cues, success states, or grounding elements in long-form content.
- **Neutral (Charcoal & Cream):** The background is a soft "Paper" cream (#FCFAF7) rather than pure white to reduce eye strain and feel more organic. Text uses a deep charcoal for high legibility and professional contrast.

## Typography

This design system utilizes **Plus Jakarta Sans** for headlines to convey a friendly, contemporary, and optimistic tone. The geometric yet soft nature of the font echoes the "vibrant" requirement of the event. 

For body text and functional labels, **Work Sans** is employed. Its optimized apertures and clean construction ensure maximum readability for event schedules, descriptions, and registration forms. 

- Use **Display-XL** sparingly for hero sections.
- Use **Label-MD** in all-caps for overlines or small categories to add a structured, professional rhythm to the layout.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop and a **Fluid Grid** for mobile devices. 

- **Desktop:** A 12-column grid with a maximum container width of 1200px. Gutters are set to 24px to allow the content to breathe.
- **Rhythm:** An 8px linear scale governs all spatial relationships. Vertical section spacing should lean towards **LG (48px)** or **XL (80px)** to maintain the minimalist, airy aesthetic.
- **Alignment:** Content should be primarily left-aligned for readability, with hero sections and call-to-action blocks optionally center-aligned to create visual anchors.

## Elevation & Depth

To maintain a professional and structured feel, this design system uses **Tonal Layers** and **Ambient Shadows**. 

Depth is achieved not through heavy gradients, but through subtle shifts in surface color. 
- **Surface Level 0:** The Cream background (#FCFAF7).
- **Surface Level 1:** Pure White (#FFFFFF) cards with a very soft, diffused shadow (15% opacity of the Primary color mixed with Grey).
- **Interactive Depth:** Buttons should use a slight lift on hover (increase shadow spread) rather than a color darken, maintaining the "vibrancy" of the sunrise palette.
- **Glassmorphism:** Use a subtle backdrop blur (12px) for sticky navigation bars to simulate morning mist, allowing the vibrant colors of the page to peek through as the user scrolls.

## Shapes

The shape language is **Rounded (Level 2)**. 

Standard components like buttons and input fields use a 0.5rem (8px) corner radius. This strikes a balance between the "professional" structure and "welcoming" community vibe. Large containers or featured event cards should utilize `rounded-xl` (1.5rem / 24px) to create a distinct, modern look that feels approachable and soft.

## Components

### Buttons
- **Primary:** Solid Sunrise Orange with white text. High-contrast, rounded-md.
- **Secondary:** Outlined in Tertiary Green or solid Soft Morning Gold for less urgent actions.

### Cards
- Event cards should feature a large image top-area with a 24px padding for the text content below. Use a white background to pop against the cream page surface.

### Input Fields
- Subtle 1px borders in a mid-tone grey. Focus states should transition the border to Sunrise Orange with a soft outer glow.

### Chips / Tags
- Use for "Event Categories" or "Status." These should be semi-transparent versions of the Primary or Tertiary colors with bold Label-MD text.

### Additional Components
- **Timeline/Schedule:** A vertical structured list using Tertiary Green for the connector line and Soft Morning Gold for time-indicators.
- **Speaker Profile:** Circular avatars with a 4px Sunrise Orange border to emphasize the "radiant" theme.