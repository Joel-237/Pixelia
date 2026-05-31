---
name: Pixelya Design System
colors:
  surface: '#e8ffee'
  surface-dim: '#c9e0cf'
  surface-bright: '#e8ffee'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#e2f9e9'
  surface-container: '#ddf4e3'
  surface-container-high: '#d7eedd'
  surface-container-highest: '#d1e8d8'
  on-surface: '#0c1f15'
  on-surface-variant: '#3d4943'
  inverse-surface: '#21342a'
  inverse-on-surface: '#dff6e6'
  outline: '#6d7a73'
  outline-variant: '#bccac1'
  surface-tint: '#006c4e'
  primary: '#00694c'
  on-primary: '#ffffff'
  primary-container: '#008560'
  on-primary-container: '#f5fff7'
  inverse-primary: '#68dbae'
  secondary: '#086b53'
  on-secondary: '#ffffff'
  secondary-container: '#a0f3d4'
  on-secondary-container: '#167159'
  tertiary: '#246755'
  on-tertiary: '#ffffff'
  tertiary-container: '#40806d'
  on-tertiary-container: '#f5fff9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#86f8c9'
  primary-fixed-dim: '#68dbae'
  on-primary-fixed: '#002115'
  on-primary-fixed-variant: '#00513a'
  secondary-fixed: '#a0f3d4'
  secondary-fixed-dim: '#84d6b9'
  on-secondary-fixed: '#002117'
  on-secondary-fixed-variant: '#00513e'
  tertiary-fixed: '#adf0da'
  tertiary-fixed-dim: '#92d4be'
  on-tertiary-fixed: '#002018'
  on-tertiary-fixed-variant: '#025140'
  background: '#e8ffee'
  on-background: '#0c1f15'
  surface-variant: '#d1e8d8'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.03em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '800'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-md:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 0.5rem
  sm: 1rem
  md: 1.5rem
  lg: 2.5rem
  xl: 4rem
  gutter: 16px
  margin-mobile: 20px
  margin-desktop: 80px
---

## Brand & Style
The design system for Pixelya is anchored in "African Modernism"—a fusion of high-precision technology and vibrant, rhythmic geometry. It avoids the ethereal trends of glassmorphism and gradients in favor of structural clarity and flat, confident color blocks. The aesthetic is "Tech-forward yet Human," utilizing bold shapes and deliberate whitespace to convey reliability and local expertise within the Yaoundé tech ecosystem. The visual language is defined by sharp geometric junctions, high-contrast intersections, and a mobile-first philosophy that prioritizes immediate legibility and tactile ease.

## Colors
The palette uses a tiered green structure to evoke growth and digital vitality. 
- **Primary Teal (#1D9E75)** is the core action color.
- **Dark Forest (#0F6E56)** and **Deep Noir (#0F2218)** provide the structural "ink" and grounding for the brand.
- **Light Mint (#9FE1CB)** acts as a soft transitional canvas for secondary sections.
- **Navy (#0C447C)** is reserved for subtle technical accents or links to ensure a sophisticated "Tech" feel.
Color application follows a "block-stacking" logic: White for primary content, Mint for supporting features, and Dark Forest for impactful footers or call-to-action sections.

## Typography
The typography strategy relies on the tension between the heavy, geometric **Plus Jakarta Sans** for headings and the understated, functional **DM Sans** for body text. 
- **Headings:** Must be set in ExtraBold (800) with tight letter spacing to create a rhythmic, block-like appearance.
- **Body:** DM Sans ensures high readability across mobile devices, using a generous line height (1.6) to provide breathing room within the dense color blocks.
- **Hierarchy:** Maintain clear distinction by using Deep Noir for primary headings and Dark Forest for sub-headings to create a subtle tonal depth.

## Layout & Spacing
The layout follows a "Mobile-First Fluid Grid" model. Elements are arranged in vertical stacks on mobile, expanding to a 12-column grid on desktop. 
- **Section Separation:** Transition between content phases using full-bleed color blocks (White to Mint to Dark Green).
- **Whitespace:** Use "generous" vertical padding (at least `xl` spacing) between sections to prevent the flat color blocks from feeling cramped.
- **Alignment:** Strict adherence to a 4px baseline grid ensures the "precise geometry" requested. Avoid offset or staggered layouts; stick to clean, horizontal alignment.

## Elevation & Depth
In alignment with the "no-gradient" and "flat" philosophy, depth is achieved through **Tonal Layering** and **Subtle Outlines** rather than shadows.
- **Layers:** Use contrasting background colors to signify hierarchy. For example, a White card sitting on a Light Mint section.
- **Borders:** Cards and containers use a 1px solid border in a slightly darker shade of the background (e.g., Mint borders on Mint backgrounds) to define edges without adding visual weight.
- **Interaction:** On hover or active states, elements do not "lift" with shadows. Instead, they shift color (e.g., Primary Teal to Dark Forest) or increase border thickness to maintain the flat, geometric integrity.

## Shapes
This design system uses a dual-radius strategy to balance friendliness and structure:
- **Small Components:** Buttons and Input fields use a **rounded-lg (0.5rem)** radius for a modern, approachable feel.
- **Large Containers:** Cards and section containers use a **rounded-xl (1.5rem)** radius to soften the high-contrast color blocks.
- **Icons:** Should be geometric and use consistent stroke weights that mirror the weight of the DM Sans body text.

## Components
- **Buttons:** Minimum height of 48px for mobile accessibility. Primary buttons are solid Teal with White text. Secondary buttons are Dark Forest with White text. No shadows.
- **Cards:** Pure White background with a 1px border (#9FE1CB or #0F6E56 at low opacity). Use `rounded-xl` corners. Padding should be generous (`md` or `lg`).
- **Input Fields:** 48px height, `rounded-lg` corners, 1px border in Light Mint, turning Primary Teal on focus. 
- **Chips/Tags:** Small `rounded-lg` pills using Navy (#0C447C) with White text for technical categories or Mint with Dark Forest text for general categories.
- **Lists:** Horizontal dividers should be thin (1px) and use the Dark Forest color at 10% opacity to maintain the clean, "African modern" aesthetic.
- **Section Blocks:** Full-width containers that utilize the primary palette to separate the narrative flow of the page.