---
name: Modern Athletic Premium
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1b1c'
  on-surface-variant: '#424752'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#737783'
  outline-variant: '#c3c6d4'
  surface-tint: '#245cb2'
  primary: '#215aaf'
  on-primary: '#ffffff'
  primary-container: '#4173ca'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#944a00'
  on-secondary: '#ffffff'
  secondary-container: '#ff9742'
  on-secondary-container: '#6c3400'
  tertiary: '#575d61'
  on-tertiary: '#ffffff'
  tertiary-container: '#70757a'
  on-tertiary-container: '#fbfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#ffdcc5'
  secondary-fixed-dim: '#ffb783'
  on-secondary-fixed: '#301400'
  on-secondary-fixed-variant: '#713700'
  tertiary-fixed: '#dee3e8'
  tertiary-fixed-dim: '#c2c7cc'
  on-tertiary-fixed: '#171c20'
  on-tertiary-fixed-variant: '#42474c'
  background: '#fcf9f8'
  on-background: '#1b1b1c'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
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
  label-sm:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

The design system is engineered for a high-end fitness audience that values both aesthetic grace and athletic performance. The brand personality is "Feminine but Strong"—balancing the softness of luxury wellness with the high-energy precision of professional training. 

The visual style is **Corporate / Modern** with a **Tactile** edge. It avoids the coldness of standard tech by utilizing a warm base palette, while maintaining a cutting-edge feel through crisp typography and purposeful use of vibrant accent colors. The UI should evoke an emotional response of confidence, clarity, and elite motivation.

## Colors

The palette is anchored by **Athletic Blue**, used strategically for primary actions and brand presence to signify trust and energy. **Warm Cream** serves as the primary canvas, providing a sophisticated, human alternative to pure white. 

**Orange** is reserved strictly for highlights, progress indicators, and "New" badges to inject heat and urgency into the experience. **Soft Blue-Gray** provides a subtle secondary layer for grouping content without creating harsh visual breaks. Text hierarchy is maintained by the contrast between **Almost Black** headings and **Warm Gray** body copy, ensuring legibility while maintaining the "premium" warmth.

## Typography

This design system utilizes **Plus Jakarta Sans** for headlines to provide a friendly, optimistic, and modern geometric feel. Its soft curves complement the "feminine" aspect of the brand while its bold weights convey "strength." 

**Work Sans** is used for body and labels; its professional and grounded nature ensures high readability for workout instructions and data-heavy fitness metrics. Labels and small metadata should utilize the uppercase styling with slight letter-spacing to mimic premium athletic apparel branding.

## Layout & Spacing

The layout follows a **Fluid Grid** model with a focus on generous vertical breathing room to maintain a "premium" feel. 

- **Desktop:** 12-column grid with 64px side margins. 
- **Mobile:** 4-column grid with 20px side margins. 

Spacing follows an 8px rhythmic scale. Use `lg` (48px) and `xl` (80px) spacing to separate major content sections (e.g., Hero to Training Programs). Use `sm` (12px) and `md` (24px) for internal component spacing and grouping. Gutters are fixed at 24px to ensure content never feels crowded, even on smaller screens.

## Elevation & Depth

Depth is conveyed through **Tonal Layers** and **Ambient Shadows**. Surfaces should not feel "flat," but rather like physical layers of high-quality material.

- **Level 0 (Base):** Warm Cream (#FAF6F0).
- **Level 1 (Cards/Containers):** Soft Blue-Gray (#EEF3F8) or pure White with a very soft, diffused 10% opacity shadow (Athletic Blue tinted).
- **Level 2 (Modals/Popovers):** Higher elevation with a 15% opacity shadow, providing clear separation from the background.

Avoid heavy black shadows; instead, use shadows tinted with the Primary Brand color (#5F8FE8) to keep the UI looking fresh and vibrant.

## Shapes

The design system adopts a **Rounded** (Level 2) shape language. Standard UI elements like input fields and buttons utilize a 0.5rem (8px) corner radius. This "Round Eight" approach strikes the perfect balance between the approachability of a lifestyle brand and the precision of a fitness app. 

Large containers (Cards) should scale up to 1rem (16px) for a softer, more modern aesthetic. Buttons can optionally use a fully "pill-shaped" radius (999px) when used as floating action buttons (FABs) to emphasize their interactive nature.

## Components

### Buttons
- **Primary:** Athletic Blue (#5F8FE8) background with White text. Bold weight. 
- **Secondary:** Ghost style with Athletic Blue border and text. 
- **Accent:** Orange (#F28C38) background for high-conversion CTAs like "Join Now."

### Cards
Use the Soft Blue-Gray (#EEF3F8) for card backgrounds when placed on the Warm Cream base. Padding should be a minimum of 24px (`md`) to allow content to breathe.

### Inputs
Fields should have a Light Neutral (#E5DFD6) border that transitions to Athletic Blue on focus. Use Work Sans for placeholder text in Warm Gray (#6E6A64).

### Progress Bars
Utilize the Orange (#F28C38) for the progress fill against a Soft Blue-Gray track. This creates high visibility for workout completion and goal tracking.

### Chips/Tags
Small, low-profile capsules used for workout categories (e.g., "Strength," "HIIT"). Use the Label-sm typography with a 4px rounded corner.