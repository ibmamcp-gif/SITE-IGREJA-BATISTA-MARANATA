---
name: Maranata Institutional Identity
colors:
  surface: '#f9f9fe'
  surface-dim: '#dad9df'
  surface-bright: '#f9f9fe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f8'
  surface-container: '#eeedf3'
  surface-container-high: '#e8e7ed'
  surface-container-highest: '#e2e2e7'
  on-surface: '#1a1c1f'
  on-surface-variant: '#434750'
  inverse-surface: '#2f3035'
  inverse-on-surface: '#f1f0f6'
  outline: '#737781'
  outline-variant: '#c3c6d1'
  surface-tint: '#395e98'
  primary: '#002551'
  on-primary: '#ffffff'
  primary-container: '#0d3b73'
  on-primary-container: '#83a7e6'
  inverse-primary: '#aac7ff'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#421b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#632c00'
  on-tertiary-container: '#e4935f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#aac7ff'
  on-primary-fixed: '#001b3e'
  on-primary-fixed-variant: '#1e467f'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#ffdbc8'
  tertiary-fixed-dim: '#ffb68a'
  on-tertiary-fixed: '#321300'
  on-tertiary-fixed-variant: '#713709'
  background: '#f9f9fe'
  on-background: '#1a1c1f'
  surface-variant: '#e2e2e7'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.01em
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
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  button:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  gutter: 24px
  container-max-width: 1200px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style

The design system is anchored in a philosophy of **Sacred Minimalism**. It balances the weight of institutional tradition with the clarity of modern digital craftsmanship. The aesthetic is sophisticated and professional, drawing inspiration from high-end technology brands like Apple and Linear to evoke a sense of trust, serenity, and premium quality.

The target audience ranges from long-standing church members to modern seekers looking for a welcoming, organized, and contemporary spiritual home. The emotional response should be one of "Peaceful Authority"—the UI feels established yet breathable, utilizing expansive whitespace to allow content to "breathe" and create a meditative user experience.

## Colors

This design system utilizes a refined, low-vibrancy palette to maintain an air of sophistication.

- **Deep Institutional Blue (#0D3B73):** Used for primary actions, branding elements, and core navigation to convey stability and depth.
- **Subtle Gold (#C5A059):** Applied sparingly as an accent for highlights, active states, or special call-to-actions to suggest quality and sacredness.
- **Grayscale Hierarchy:** High-contrast black is avoided for long-form text; instead, a very deep gray is used for primary body copy to reduce eye strain, while lighter grays handle secondary metadata and decorative borders.

## Typography

The typography strategy pairs **Plus Jakarta Sans** for headlines to provide a friendly yet modern geometric character, with **Inter** for body text to ensure maximum legibility and a systematic, clean appearance.

Large display titles should use tighter letter-spacing and bold weights to command attention. Body text should maintain a generous line height (at least 1.5x) to support the "premium" feel of the design. Labels and small metadata should occasionally use all-caps with light tracking to distinguish them from prose.

## Layout & Spacing

This design system follows a **Fixed-Fluid Hybrid** model. Content is housed within a maximum width container of 1200px for desktop to ensure optimal line lengths, while margins remain fluid on smaller viewports.

The defining characteristic is **Generous Negative Space**. Vertical gaps between major sections should be significant (120px on desktop) to separate different thematic areas of the church's message. Internal component spacing follows a 4px/8px baseline grid to maintain mathematical harmony. 

**Breakpoints:**
- Mobile: < 768px (4 columns, 16px margins)
- Tablet: 768px - 1024px (8 columns, 24px margins)
- Desktop: > 1024px (12 columns, adaptive margins)

## Elevation & Depth

To achieve a "Stripe-like" aesthetic, elevation is handled through **Ambient Shadows** and tonal layering rather than heavy borders.

- **Base Layer:** Pure White (#FFFFFF).
- **Surface Layer:** Light Gray (#F9FAFB) used to differentiate background sections.
- **Elevated Cards:** Use an extremely soft, multi-layered shadow (0px 4px 20px rgba(0,0,0,0.04)) and a subtle 1px border (#EAECF0) to define edges against the white background.
- **Interactions:** On hover, cards should lift slightly using a more pronounced shadow and a 2px vertical translation (Y-axis) for a tactile feel.

## Shapes

The shape language is defined by **Soft Geometric Precision**. 

A standard radius of **12px** is used for buttons and small components, while larger containers and cards utilize **16px** to appear friendlier and more contemporary. Circular "pill" shapes are reserved exclusively for tags/badges and specific decorative elements to avoid clashing with the sophisticated structural grid.

## Components

### Navigation
The header is fixed to the top of the viewport. It begins as **transparent** (with white text) when over hero images, transitioning to a **solid white background** with a subtle bottom border and blue text upon scrolling. A `backdrop-filter: blur(8px)` is applied for a glassmorphism effect during transition.

### Buttons
- **Primary:** Deep Blue background, white text. No border. High contrast.
- **Secondary/Ghost:** Transparent background with a 1px border (#EAECF0). Subtle hover state changes background to #F9FAFB.
- **Tertiary:** Text-only with an underline that appears on hover, used for "Read More" links.

### Cards
Cards are the primary content vessel. They feature 16px padding, a 1px subtle border, and a soft shadow. Imagery within cards should always have the top corners rounded to match the container.

### Forms
Input fields are tall (48px) with a background color of #F9FAFB and a subtle border. Focus states transition the border color to Deep Blue and add a 2px outer glow in a semi-transparent blue. Labels are always positioned above the field in `label-sm` style.

### Chips & Badges
Small, rounded-full elements used for categories (e.g., "Sermons", "Events"). These use the Subtle Gold (#C5A059) at 10% opacity for the background and 100% opacity for the text.