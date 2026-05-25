---
name: Dragon's Ledger
colors:
  surface: '#fff8f0'
  surface-dim: '#e9d9b1'
  surface-bright: '#fff8f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff3d7'
  surface-container: '#fdedc4'
  surface-container-high: '#f7e7bf'
  surface-container-highest: '#f1e1b9'
  on-surface: '#221b03'
  on-surface-variant: '#5a403c'
  inverse-surface: '#383014'
  inverse-on-surface: '#fff0ca'
  outline: '#8e706b'
  outline-variant: '#e3beb8'
  surface-tint: '#b52619'
  primary: '#610000'
  on-primary: '#ffffff'
  primary-container: '#8b0000'
  on-primary-container: '#ff907f'
  inverse-primary: '#ffb4a8'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#003503'
  on-tertiary: '#ffffff'
  tertiary-container: '#004e06'
  on-tertiary-container: '#5fc454'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a8'
  on-primary-fixed: '#410000'
  on-primary-fixed-variant: '#920703'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#92fa83'
  tertiary-fixed-dim: '#77dd6a'
  on-tertiary-fixed: '#002201'
  on-tertiary-fixed-variant: '#005307'
  background: '#fff8f0'
  on-background: '#221b03'
  surface-variant: '#f1e1b9'
typography:
  headline-xl:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: EB Garamond
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: EB Garamond
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: EB Garamond
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
spacing:
  margin-page: 2rem
  gutter: 1.5rem
  stack-sm: 0.5rem
  stack-md: 1rem
  stack-lg: 2rem
---

## Brand & Style
The design system evokes the atmosphere of a medieval scriptorium and high-fantasy court. It targets players seeking an immersive, lore-heavy experience where every interaction feels like a deliberate action within a physical world. The aesthetic blends **Tactile Skeuomorphism** with **Editorial Elegance**. 

The UI should feel weighty and ancient. Surfaces are not mere colors but textures: aged parchment, hammered iron, and carved stone. Interactions should mimic physical sensations—the heavy thud of a stone slab moving or the soft press of a wax seal. The goal is to transform a digital interface into a "living artifact."

## Colors
The palette is grounded in historical pigments and natural materials. 
- **Aged Parchment (#f4e4bc):** Serves as the primary canvas for all information, providing a warm, organic base.
- **Deep Crimson (#8b0000):** Used for critical actions, health bars, and high-status markers. It represents the "Blood of the Dragon."
- **Gold (#d4af37):** Reserved for highlights, borders, and rare interactive states. It should often be applied with a metallic sheen or gradient.
- **Forest Green (#228b22):** Utilized for positive growth, stamina, or nature-based UI elements.
- **Slate Grey (#708090):** The color of cold stone and forged iron, used for structural frames and secondary background depth.

## Typography
Typography follows the logic of a royal decree. While true blackletter is used for decorative "Illuminated" initials (drop caps), the primary headlines use **Libre Caslon Text** for its authoritative, historical weight and sharp serifs. 

**EB Garamond** is used for all body text to ensure high legibility while maintaining the "bookish" feel of a manuscript. All labels should be set in small caps with generous letter spacing to mimic stone engravings. Important headers should feature an "Illuminated Manuscript" treatment: a large, decorative first letter set in Deep Crimson with Gold filigree.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy, resembling the structured margins of a medieval codex. 
- **Desktop:** A centered 12-column grid with wide 48px margins. Content is contained within "Stone Frames."
- **Mobile:** A single column layout with 16px margins, where borders are simplified into "iron trim" at the top and bottom of the screen.
- **Rhythm:** Spacing should be generous. Elements are never crowded; they are given room to breathe like text on a holy relic. Use vertical stacking for inventory lists and horizontal sprawling for skill trees.

## Elevation & Depth
Depth is achieved through **Tonal Layers** and **Physical Textures** rather than modern shadows.
- **Base Level:** The Slate Grey "Stone" background.
- **Mid Level:** Aged Parchment sheets layered on top of the stone. These have rough, deckled edges and a very faint, hard-edged inner shadow to suggest they are sitting *inside* a frame.
- **High Level:** Wax seals and Gold-plated buttons that sit "on top" of the parchment.
- **Overlays:** Full-screen stone slabs that slide into view to block the background, creating a sense of total immersion in a sub-menu.

## Shapes
This design system utilizes **Sharp (0)** roundedness for structural elements to mimic cut stone and forged metal. However, specific interactive elements like "Wax Seals" (buttons) are naturally circular but should have irregular, "melted" perimeters rather than perfect geometric radii. Use "Iron-wrought" corners—decorative L-shaped brackets in Slate Grey—to anchor the corners of rectangular containers.

## Components
### The Serpent (Snake)
The protagonist is a **Scaled Serpent**. Its body consists of interlocking, diamond-shaped scales in Forest Green with a Gold underbelly. The head is dragon-like, featuring small horns and glowing embers for eyes.

### Food Items
- **Royal Crown:** High-value item, glistening gold with crimson velvet.
- **Chalice:** Mid-value, silver or pewter texture with wine-colored liquid.
- **Meat Leg:** Common item, a rustic brown roasted turkey/boar leg.

### UI Elements
- **Buttons (Wax Seals):** Circular, Deep Crimson, with an embossed dragon icon in the center. They "crack" slightly when pressed.
- **Containers (Stone Slabs):** Slate Grey with inner beveled edges. The "content area" inside is always Aged Parchment.
- **Borders (Iron-wrought):** 2px solid Slate Grey lines, punctuated by rivets at the intersections.
- **Input Fields:** Styled as "Scrolls"—horizontal parchment rolls that expand when focused.
- **Checkboxes:** Small iron latches that flip from an "open" to "locked" position.