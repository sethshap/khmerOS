---
name: Heritage Editorial
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede8'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#4e453e'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#80756d'
  outline-variant: '#d2c4bb'
  surface-tint: '#705a49'
  primary: '#322214'
  on-primary: '#ffffff'
  primary-container: '#4a3728'
  on-primary-container: '#bba08c'
  inverse-primary: '#dec1ac'
  secondary: '#715a3e'
  on-secondary: '#ffffff'
  secondary-container: '#fdddb9'
  on-secondary-container: '#786044'
  tertiary: '#2f2317'
  on-tertiary: '#ffffff'
  tertiary-container: '#46392b'
  on-tertiary-container: '#b5a290'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fbddc7'
  primary-fixed-dim: '#dec1ac'
  on-primary-fixed: '#28180b'
  on-primary-fixed-variant: '#574333'
  secondary-fixed: '#fdddb9'
  secondary-fixed-dim: '#e0c29f'
  on-secondary-fixed: '#281803'
  on-secondary-fixed-variant: '#584329'
  tertiary-fixed: '#f4dfcb'
  tertiary-fixed-dim: '#d7c3b0'
  on-tertiary-fixed: '#241a0e'
  on-tertiary-fixed-variant: '#524436'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-sm:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Source Sans Three
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Source Sans Three
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Source Sans Three
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1120px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The design system embodies a sophisticated editorial aesthetic that prioritizes content clarity and timeless elegance. The brand personality is intellectual, authoritative, and warm, moving away from cold minimalism toward a "New Heritage" feel. 

The design style is **Minimalist Editorial** with an emphasis on high-quality typography and a restricted, natural palette. It utilizes generous white space (represented here by soft sand and beige) to allow long-form content to breathe. The emotional response should be one of calm focus, reminiscent of reading a high-end physical journal or a curated gallery guide.

## Colors
The palette transition shifts from botanical greens to an earth-centric "Brown & Beige" theme. 

- **Primary (#4A3728):** A deep espresso brown used for headlines, primary actions, and high-contrast text. It provides the "ink" for the editorial experience.
- **Secondary (#8C7355):** A warm walnut tone used for sub-navigation, icons, and secondary accents.
- **Tertiary (#D9C5B2):** A muted sand tone used for borders, subtle dividers, and inactive states.
- **Neutral (#F5F2ED):** A soft, warm beige that serves as the canvas for the entire UI, reducing eye strain compared to pure white.

## Typography
The typography system relies on the interplay between a classic serif and a functional sans-serif. 

**Libre Caslon Text** is used for all headlines and display elements to reinforce the literary tone. It should be set with slightly tighter letter-spacing for large titles. 

**Source Sans Three** provides a clean, unobtrusive contrast for body copy and UI labels, ensuring high legibility in dense information environments. "Label-caps" should be used sparingly for category tags or overlines to add a touch of modern structure to the traditional serif layout.

## Layout & Spacing
This design system utilizes a **Fixed Grid** philosophy for desktop to maintain the "page" feel of a magazine, while transitioning to a fluid model for mobile.

- **Desktop:** 12-column grid centered within a 1120px container. Large 64px external margins create a frame around the content.
- **Tablet:** 8-column grid with 32px margins.
- **Mobile:** 4-column fluid grid with 20px margins.

Spacing follows a strict 8px base unit. Use generous padding (often 2x the standard) between sections to maintain the airy, premium editorial feel.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows. 

The background is the base Neutral (Beige). Elements that need to appear "raised" or separated use a slightly lighter off-white or a subtle 1px border in the Tertiary (Sand) color. 

Avoid drop shadows. If elevation is strictly necessary for a floating component (like a modal), use an extremely diffused, low-opacity shadow (#4A3728 at 5% opacity) with a large blur radius to mimic natural ambient light.

## Shapes
The shape language is understated and **Soft**. 

A minimal corner radius (0.25rem) is applied to buttons and input fields to take the "edge" off the layout without making it appear overly "app-like" or bubbly. This maintains the structural integrity of a grid-based editorial layout. Cards and larger containers may use a larger radius (0.5rem) to signify grouping, but should never reach pill-shaped or fully rounded territory.

## Components
- **Buttons:** Primary buttons are solid Espresso (#4A3728) with Sand (#D9C5B2) text. Secondary buttons are outlined in Sand with Espresso text.
- **Input Fields:** Use a 1px border in Sand (#D9C5B2) on the Beige (#F5F2ED) background. Labels use the "label-caps" typography style.
- **Chips/Tags:** Small, rectangular shapes with 2px radius. Use a Tertiary background with Espresso text.
- **Lists:** Editorial lists should use hairline dividers (0.5px) in the Sand color.
- **Cards:** Cards should not have shadows. Use a subtle fill color change (slightly lighter than the background) or a 1px Sand border to define the boundary.
- **Pull Quotes:** A signature component. Use large Libre Caslon Text, italicized, with a thick 4px Espresso left-border accent.