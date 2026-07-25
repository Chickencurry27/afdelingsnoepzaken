---
name: Sugar & Nostalgia
colors:
  surface: '#faf9f8'
  surface-dim: '#dadad9'
  surface-bright: '#faf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f2'
  surface-container: '#eeeeed'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e3e2e1'
  on-surface: '#1a1c1c'
  on-surface-variant: '#584141'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f0f0'
  outline: '#8c7071'
  outline-variant: '#e0bfbf'
  surface-tint: '#af2b3e'
  primary: '#570013'
  on-primary: '#ffffff'
  primary-container: '#800020'
  on-primary-container: '#ff828a'
  inverse-primary: '#ffb3b5'
  secondary: '#81515a'
  on-secondary: '#ffffff'
  secondary-container: '#fdbec9'
  on-secondary-container: '#7a4a54'
  tertiary: '#352325'
  on-tertiary: '#ffffff'
  tertiary-container: '#4d383b'
  on-tertiary-container: '#bea1a4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdada'
  primary-fixed-dim: '#ffb3b5'
  on-primary-fixed: '#40000b'
  on-primary-fixed-variant: '#8e0f28'
  secondary-fixed: '#ffd9df'
  secondary-fixed-dim: '#f4b6c1'
  on-secondary-fixed: '#330f19'
  on-secondary-fixed-variant: '#663a43'
  tertiary-fixed: '#fbdbde'
  tertiary-fixed-dim: '#debfc2'
  on-tertiary-fixed: '#281719'
  on-tertiary-fixed-variant: '#574144'
  background: '#faf9f8'
  on-background: '#1a1c1c'
  surface-variant: '#e3e2e1'
  candy-pink: '#F8C8DC'
  deep-burgundy: '#5E0B1F'
  cream-white: '#FFFAF0'
  accent-gold: '#D4AF37'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 64px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 36px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  title-lg:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 2rem
  section-padding: 6rem
  stack-sm: 0.5rem
  stack-md: 1.5rem
  stack-lg: 3rem
---

## Brand & Style

This design system reimagines a local landmark as a high-end, boutique destination. The personality is "Nostalgic Luxury"—blending the whimsical charm of a classic candy shop with the refined elegance of a modern lifestyle brand. The goal is to move beyond a transactional e-commerce interface toward an immersive, sensory invitation to visit the physical location in Middelburg.

The aesthetic follows a **Modern Heritage** style. It uses high-quality whitespace, sophisticated color transitions, and editorial-inspired layouts. By pairing classic serif typography with soft, tactile UI elements, the system creates a digital environment that feels as welcoming and hand-crafted as a box of artisanal chocolates.

- **Audience:** Local residents, tourists seeking "hotspots," and gift-seekers.
- **Emotional Response:** Delight, warmth, indulgence, and curiosity.
- **Style Direction:** A blend of Minimalism and Tactile design, utilizing soft shadows and elegant curves to evoke the physical presence of a boutique store.

## Colors

The palette is a sophisticated evolution of the brand’s signature tones. **Deep Burgundy** serves as the primary anchor, providing a sense of heritage and high-end quality. This is balanced by a spectrum of pinks: **Secondary Pink** for interactive elements and **Tertiary Pastel** for large surface areas and section backgrounds.

- **Primary (Burgundy):** Used for typography, primary buttons, and structural lines to ensure high contrast and readability.
- **Secondary/Tertiary (Pinks):** Used for soft backgrounds, decorative elements, and hover states to maintain the "sweet" brand identity.
- **Neutral (Cream/White):** Replaces harsh pure whites with a "paper" or "cream" tone to enhance the nostalgic, boutique feel.
- **Gold Accent:** Reserved for small decorative flourishes, iconography, or premium category highlights.

## Typography

The typographic strategy balances "The Playful" and "The Professional." 

**EB Garamond** is the voice of the brand. Its classical proportions and elegant serifs evoke the feeling of a historic storefront. Use it for all large headlines and quotes. On mobile, carefully scale display sizes to maintain readability while keeping the editorial impact.

**Hanken Grotesk** provides a clean, modern contrast. As a high-performance sans-serif, it handles all body copy, product descriptions, and utility labels. Its neutral but warm character ensures the interface remains functional and accessible without competing with the decorative serif.

## Layout & Spacing

The layout adopts a **Sophisticated Fixed Grid** approach. Content is centered within a generous max-width container, surrounded by ample whitespace to create a "gallery" effect for the products and store photography.

- **The One-Page Flow:** The layout should feel like a curated journey. Use vertical "chapters" separated by full-bleed color shifts (alternating between cream and pastel pink).
- **Rhythm:** Use a 12-column grid for desktop. Margins should be wide (minimum 64px) to emphasize the boutique nature—crowded layouts are for supermarkets; spacious layouts are for boutiques.
- **Mobile Adaptivity:** On mobile, margins reduce to 20px, and columns collapse to a single stack. Spacing between sections remains generous to preserve the airy feel.

## Elevation & Depth

To maintain a sophisticated and modern feel, this system avoids heavy shadows. Depth is achieved through **Tonal Layering** and **Soft Ambient Occlusion**.

- **Surface Tiers:** Use subtle shifts in background color (e.g., a cream card on a pastel pink section) to define depth without borders.
- **Shadows:** When necessary (such as for a floating navigation bar or primary "Visit Us" card), use highly diffused, low-opacity shadows tinted with the primary burgundy color (`rgba(94, 11, 31, 0.05)`).
- **Glassmorphism:** Apply a light backdrop blur to the header to allow candy colors to peek through as the user scrolls, creating a sense of transparency and lightness.

## Shapes

The shape language is "Rounded and Friendly." Sharp corners are avoided to mirror the organic shapes of confectionery. 

- **Cards & Containers:** Use `rounded-lg` (1rem) for product cards and informational blocks to keep them soft and inviting.
- **Interactive Elements:** Buttons should use a more pronounced curve (rounded-xl) to feel tactile and "pill-like," inviting the user to touch.
- **Imagery:** Photography should occasionally use circular or organic masking to break the rigidity of the digital grid, reinforcing the "hand-crafted" boutique vibe.

## Components

### Buttons
- **Primary:** Burgundy background with Cream text. Rounded-xl. High-end feel with a subtle gold border on hover.
- **Secondary:** Transparent with a Burgundy outline. Used for "Read More" or secondary actions.

### Cards (The "Sweet" Card)
Cards should not have visible borders. Instead, use a subtle color fill or a very soft shadow. Product cards should feature high-quality, "hero" style photography of the candy.

### Inputs & Fields
Use a soft cream background with a thin burgundy bottom-border. This mimics high-end stationery or boutique order forms.

### Sticky Navigation
A minimal, centered navigation bar that transitions from transparent to a frosted glass (glassmorphism) effect. It should prominently feature the "Visit Us" CTA or the store address.

### The "Atmosphere" Block
A specialized component for the one-page layout that combines an organic-shaped image of the Middelburg store with a floating text block. This is the "hero" of the pivot to physical retail.

### Lists & Menus
Use elegant, thin dividers and EB Garamond titles. Icons (like the location pin or phone) should be rendered in a thin-stroke gold or burgundy style.