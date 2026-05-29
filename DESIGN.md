---
name: RingForge Identity
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e4bebc'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ab8987'
  outline-variant: '#5b403f'
  surface-tint: '#ffb3b1'
  primary: '#ffb3b1'
  on-primary: '#680011'
  primary-container: '#ff535b'
  on-primary-container: '#5b000e'
  inverse-primary: '#bb152c'
  secondary: '#ffb4a8'
  on-secondary: '#690000'
  secondary-container: '#920703'
  on-secondary-container: '#ff9a8a'
  tertiary: '#c7c6c6'
  on-tertiary: '#2f3131'
  tertiary-container: '#909191'
  on-tertiary-container: '#282a2a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b1'
  on-primary-fixed: '#410007'
  on-primary-fixed-variant: '#92001c'
  secondary-fixed: '#ffdad4'
  secondary-fixed-dim: '#ffb4a8'
  on-secondary-fixed: '#410000'
  on-secondary-fixed-variant: '#920703'
  tertiary-fixed: '#e3e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  headline-xl:
    fontFamily: Bebas Neue
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Bebas Neue
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Bebas Neue
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Bebas Neue
    fontSize: 32px
    fontWeight: '700'
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
  label-lg:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 20px
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
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
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1440px
---

## Brand & Style

The design system is built on the philosophy of "The Forge"—where grit meets precision. It targets a demographic that values intensity, discipline, and premium athletic experiences. The aesthetic is **Aggressive Modernism**, blending high-impact typography with a sophisticated dark-mode atmosphere.

To evoke an energetic and powerful response, the system utilizes:
- **Dark Premium Foundation:** Deep blacks and grays provide a high-contrast canvas that allows the red accents to "bleed" through the interface.
- **Glassmorphism:** Subsurface scattering and frosted textures on containers mimic the look of high-end gym equipment and modern architectural elements.
- **Neon Kineticism:** Subtle outer glows and lighting effects on interactive elements simulate the buzzing energy of a late-night boxing gym.
- **Cinematic Depth:** Use of aggressive shadows and layered translucency to create a sense of three-dimensional space.

## Colors

The palette is anchored in a deep **Primary Black (#0D0D0D)** to establish a prestigious, "after-hours" elite club feel. 

- **Primary Red (#E63946):** Used for "Action" states, calls to action, and critical feedback. It represents heat and kinetic energy.
- **Deep Red (#8B0000):** Used for gradients, hover states, and secondary visual interest to add depth to the primary red.
- **Secondary Silver (#B0B0B0):** Utilized for metadata, borders, and secondary text to provide a technical, industrial contrast.
- **Pure White (#FFFFFF):** Reserved strictly for high-readability body text and essential icons to ensure maximum contrast against the dark background.

## Typography

Typography in this design system is a tool for impact. 

- **Headlines (Bebas Neue Bold):** These should be treated as graphic elements. They are all-caps by default, designed to "punch" through the layout. Use tight line heights to maintain a blocky, structural feel.
- **Body (Inter Regular):** Provides a clean, neutral balance to the aggressive headlines. It ensures that workout descriptions, schedules, and technical data remain highly legible.
- **Interaction (Montserrat SemiBold):** Used for buttons, navigation links, and micro-copy. The geometric nature of Montserrat adds a modern, architectural finish to the UI's functional areas.

## Layout & Spacing

The layout follows a **Fixed-Fluid Hybrid** model. Content is contained within a max-width of 1440px for desktop clarity but stretches fluidly on smaller viewports.

- **Grid:** Use a 12-column grid for desktop and a 4-column grid for mobile.
- **Rhythm:** A 4px baseline grid governs all vertical rhythm. Spacing between major sections should be aggressive (80px–120px) to emphasize a premium, airy feel despite the dark palette.
- **Gaps:** Gutters are set at 24px to ensure distinct separation between high-intensity visual cards.

## Elevation & Depth

This design system eschews traditional shadows for **Luminous Depth**. 

- **Tiers:** Level 0 is the Deep Black background. Level 1 is the Dark Gray (#1A1A1A) surface container.
- **Glassmorphism:** Surface containers (Level 1) use a 10px backdrop-blur with a 10% white border-stroke to create a "glass" effect over moving backgrounds or glowing orbs.
- **Neon Accents:** Instead of drop shadows, active elements use a `0px 0px 15px rgba(230, 57, 70, 0.4)` outer glow. This creates an "energy leak" effect, suggesting the power contained within the component.

## Shapes

The shape language is **Refined-Rugged**. While the boxing world is often associated with sharp edges, this design system uses `rounded-md` (0.5rem) and `rounded-lg` (1rem) corners to provide a modern, "tech-wear" finish. 

- **Standard Elements:** Use a 0.5rem radius (Buttons, Input fields).
- **Featured Cards:** Use a 1rem radius to soften the high-contrast imagery within.
- **Pill Shapes:** Reserved exclusively for status indicators (e.g., "Live Now," "Class Full") to distinguish them from actionable buttons.

## Components

### Buttons
- **Primary:** Solid Accent Red (#E63946) with White Montserrat SemiBold text. On hover, apply a 20px red outer glow and scale up by 2%.
- **Secondary:** Transparent background with a 2px Silver border. Text is Silver. On hover, background fills with Silver and text becomes Black.

### Cards
- **Glow Cards:** Dark Gray (#1A1A1A) background with a subtle red top-border. When hovered, the entire card gains a soft red inner-glow and the backdrop-blur increases.
- **Media Cards:** Full-bleed imagery with a bottom-up black gradient overlay to house white Bebas Neue typography.

### Input Fields
- **Dark Inputs:** Deep Black background, 1px Gray border. On focus, the border transitions to Accent Red with a subtle red "shadow" glow.

### Tables
- **Dark Matrix:** Rows are separated by a 1px Dark Gray line. Header row uses Montserrat Label-sm in Silver. Alternate row striping is not used; instead, use a hover-state highlight that turns the row background to a semi-transparent Deep Red.

### Navigation
- **Header:** Sticky glassmorphic bar with 20px backdrop-blur. Links use Montserrat SemiBold with a red underline animation that expands from the center on hover.