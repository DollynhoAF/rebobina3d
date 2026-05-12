---
name: Rebobina 3D Cinematic Tech
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#ccc3d8'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#958da1'
  outline-variant: '#4a4455'
  surface-tint: '#d2bbff'
  primary: '#d2bbff'
  on-primary: '#3f008e'
  primary-container: '#7c3aed'
  on-primary-container: '#ede0ff'
  inverse-primary: '#732ee4'
  secondary: '#b4c5ff'
  on-secondary: '#002a78'
  secondary-container: '#0053db'
  on-secondary-container: '#cdd7ff'
  tertiary: '#ffb693'
  on-tertiary: '#561f00'
  tertiary-container: '#ae4700'
  on-tertiary-container: '#ffe0d3'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#eaddff'
  primary-fixed-dim: '#d2bbff'
  on-primary-fixed: '#25005a'
  on-primary-fixed-variant: '#5a00c6'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb693'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7a3000'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-tech:
    fontFamily: spaceGrotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
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
  section-gap: 80px
---

## Brand & Style

The brand identity of this design system is built on the intersection of additive manufacturing precision and futuristic digital interfaces. It targets a demographic of innovators, engineers, and creators who value both technical performance and aesthetic sophistication.

The visual style is a hybrid of **Minimalist High-Tech** and **Glassmorphism**. It prioritizes clarity and functional density while utilizing depth-based effects like translucent surfaces and neon luminescence to evoke a sense of "the laboratory of the future." The primary experience is immersive dark-mode, punctuated by high-contrast "Flash" sections—stark white layouts that reset the user's visual attention and emphasize premium hardware or finished 3D outputs.

## Colors

The palette is engineered to create a deep, cinematic environment. The primary background uses a **Deep Purple-Black** to provide infinite depth. Vibrant purples serve as the primary interactive signal, while the brand's legacy blue is used for secondary utilities and informational states.

### Contrast Strategy
- **Base State:** Dark background (#09090B) with Pure White text for maximum legibility and a "glowing" effect on OLED screens.
- **Highlight State:** A radical shift to a Pure White background with Dark Slate text. This is reserved for specific landing sections, product showcases, or "physical" documentation to create a tactile, paper-like contrast against the digital darkness.
- **Accents:** Neon Purple (#7C3AED) is used for primary actions. The orange (#FF6B00) is used sparingly for technical alerts, heat-related data, or critical status indicators.

## Typography

This design system utilizes **Geist** for its neutral, engineered precision. It provides the "tech-focused" feel requested while maintaining extreme legibility in both dark and light modes. 

**Space Grotesk** is introduced for labels and technical metadata to lean into the futuristic aesthetic, using wide letter spacing and uppercase styling to mimic instrument panels and blueprints. For display headings, tight tracking and heavy weights create a commanding presence, while body copy remains spacious to ensure the "clean and practical" requirement is met.

## Layout & Spacing

The layout philosophy follows a **Fixed-Grid System** within a maximum container width of 1280px, ensuring high-end editorial control over content positioning. 

- **Grid:** A 12-column grid is used for desktop, collapsing to 6 columns for tablet and 4 columns for mobile.
- **Rhythm:** An 8px base unit drives all padding and margin decisions. Component internal spacing (e.g., inside a card) follows a strict hierarchy of 16px, 24px, or 32px.
- **Negative Space:** Generous vertical section gaps (80px+) are used to separate "Highlight" (white) blocks from "Standard" (dark) blocks, preventing visual clutter and emphasizing the shift in context.

## Elevation & Depth

This design system rejects traditional shadows in favor of **Luminescent Depth** and **Glassmorphism**.

1.  **Surface Tiers:** Background is Level 0. Cards and containers are Level 1, using a slightly lighter purple-gray with a semi-transparent blur (Backdrop Filter: 12px).
2.  **Sleek Borders:** Borders are 1px thin, using a "White-to-Transparent" gradient at 10% opacity to create a subtle "rim light" effect on dark surfaces.
3.  **Glow Effects:** Primary buttons and active states utilize a soft, 15px outer glow (Drop Shadow) using the primary purple color at 30% opacity. This simulates an emissive light source, reinforcing the futuristic technological feel.

## Shapes

The shape language is **Refined Geometric**. A standard radius of 0.5rem (8px) is applied to all primary UI elements to keep the interface approachable but structured. 

Buttons and input fields maintain this consistent radius, while "Highlight" sections and full-width containers use 0px (sharp) edges to create a sense of architectural scale. Interaction indicators (like radio active states) use perfect circles to contrast against the predominantly rectangular grid.

## Components

### Buttons
- **Primary:** Solid Vibrant Purple background, white text, 8px radius. Features a subtle inner-top highlight (1px white at 10% opacity) and an outer purple glow on hover.
- **Secondary:** Transparent background with a 1px "Ice" border (white at 20% opacity). Text in pure white.
- **Tertiary/Ghost:** No border or background. Used for low-priority technical actions.

### Cards
Cards are the primary organizational unit. In dark mode, they use a "Glass" effect: semi-transparent dark backgrounds with a thin 1px border. In "Highlight" mode, cards use a subtle gray stroke (#E5E7EB) and no background blur.

### Form Inputs
Inputs use a "Terminal" style: dark background, 1px border that turns vibrant purple on focus, and a monospaced font (Space Grotesk) for the value input. Labels are placed above the field in uppercase technical styling.

### Chips & Status
Small, pill-shaped indicators for "3D Material Type" or "Print Status." These use high-saturation background colors at 15% opacity with high-saturation text to appear like illuminated LED indicators.

### 3D Viewport Frames
Specialized components for showcasing 3D models should feature "Corner Brackets"—small L-shaped accents at the four corners of the container—to reinforce the "technological scanner" aesthetic.