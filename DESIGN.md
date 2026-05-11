---
name: Aetheric Intelligence
colors:
  surface: '#141313'
  surface-dim: '#141313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2b2a2a'
  surface-container-highest: '#353434'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#050505'
  on-primary-container: '#797777'
  inverse-primary: '#5f5e5e'
  secondary: '#c3c6d7'
  on-secondary: '#2c303d'
  secondary-container: '#454957'
  on-secondary-container: '#b5b8c9'
  tertiary: '#c9c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#050505'
  on-tertiary-container: '#797777'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#dfe2f3'
  secondary-fixed-dim: '#c3c6d7'
  on-secondary-fixed: '#171b28'
  on-secondary-fixed-variant: '#434654'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c9c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#141313'
  on-background: '#e5e2e1'
  surface-variant: '#353434'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Montserrat
    fontSize: 30px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
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
  container-max: 1440px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
---

## Brand & Style
The design system centers on a "Cinematic Tech-Luxury" aesthetic, positioning the agency as a high-tier orchestrator of digital talent and solutions. The brand personality is authoritative yet visionary, evoking the feeling of a premium command center or an advanced AI interface.

The visual style leans heavily into **Glassmorphism** and **Atmospheric Depth**. Surfaces are treated as semi-translucent crystalline layers that float over a deep, infinite void. Movement is fluid and intentional, utilizing soft glows and mesh gradients to guide the user’s eye toward high-conversion actions. This creates an immersive experience that feels more like an elite digital environment than a traditional website.

## Colors
The palette is built on a "Deep Space" foundation. The **Deep Midnight Black** serves as the primary canvas, providing infinite depth, while **Dark Navy Blue** is used for structural layering and surface differentiation.

Accents are used strategically to signify energy and interactivity. **Neon Purple** represents intelligence and luxury, used for primary calls-to-action and highlights. **Electric Cyan** represents technology and speed, used for secondary accents, data visualizations, and active states. All interactive elements should leverage these two colors in gradients to simulate light emission.

## Typography
Typography is architectural and high-contrast. Headlines utilize **Montserrat** in bold weights to convey strength and permanence. For maximum impact, large display text should utilize a subtle vertical gradient from White to a slightly muted Silver.

Body text uses **Inter** for its neutral, highly legible characteristics, ensuring complex service descriptions remain readable. A specialized **Space Grotesk** label style is used for technical data, eyebrow headlines, and small UI metadata to reinforce the futuristic, high-tech atmosphere.

## Layout & Spacing
The system utilizes a **12-column fixed grid** for desktop, transitioning to a **4-column fluid grid** for mobile. Spacing follows a strict 8px base unit to maintain mathematical harmony.

Layouts should feel expansive, with generous "breathable" margins to evoke a luxury feel. Components should be grouped in "Dashboard Cells"—modular units that suggest a high-tech interface. Avoid cluttered layouts; instead, use staggered heights and floating arrangements to create a sense of three-dimensional space within the 2D screen.

## Elevation & Depth
Depth is achieved through **Backdrop Blurs (Glassmorphism)** and **Photorealistic Lighting**. Rather than standard grey shadows, this system uses "Glow Shadows"—low-opacity dropshadows tinted with the accent colors (Purple/Cyan) to simulate light reflecting off a surface.

1.  **Level 0 (Base):** Midnight Black with subtle mesh gradients.
2.  **Level 1 (Cards):** Semi-transparent Navy Blue (15-30% opacity) with a 20px backdrop blur and a 1px "Inner Glow" border.
3.  **Level 2 (Modals/Overlays):** Higher opacity glass with more pronounced neon border gradients.
4.  **Level 3 (Interactive):** Elements that appear to "lift" on hover, increasing the intensity of the glow beneath them.

## Shapes
The shape language is "Precision Geometric." While surfaces are rounded for a modern SaaS feel, the radii are kept tight to maintain a professional, high-tech edge. 

- **Primary Containers:** 1rem (16px) corner radius for a balanced, sophisticated look.
- **Buttons & Chips:** 0.5rem (8px) for a tighter, more utilitarian appearance.
- **Accents:** Sharp 90-degree angles are used only for decorative data-lines or "bracket" style ornaments that frame section titles.

## Components
### Buttons
Buttons are high-impact interactive elements. The "Primary Action" button features a linear gradient from Neon Purple to Electric Cyan with a persistent outer glow. On hover, the glow expands and the button slightly scales up (1.02x).

### Service Cards
Cards use the glassmorphic style with a "Pulse" border. A 1px gradient border should animate or "trace" the perimeter of the card when the user scrolls into view. Inside, use high-quality 3D icons or abstract tech-motifs.

### Input Fields
Inputs are minimal: a bottom-only border or a very subtle dark-filled container. Upon focus, the border transitions into a Cyan glow, and the label floats upward using the Space Grotesk label style.

### Dashboard Stats
For the staffing agency's metrics, use "Liquid Gauges" and sleek line charts that utilize the Electric Cyan color against the dark background. Data should appear to be "projected" onto the glass surfaces.

### Interactive Chips
Used for skills or service tags, these feature a Dark Navy background with a Purple border. They should have a subtle "hover-light" effect where the background brightens slightly.