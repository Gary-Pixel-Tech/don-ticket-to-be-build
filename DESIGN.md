---
name: Gentleman Auditor
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#37393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c4c7c8'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c6c6c7'
  primary: '#ffffff'
  on-primary: '#2f3131'
  primary-container: '#e2e2e2'
  on-primary-container: '#636565'
  inverse-primary: '#5d5f5f'
  secondary: '#a0caff'
  on-secondary: '#003259'
  secondary-container: '#0063aa'
  on-secondary-container: '#c7deff'
  tertiary: '#ffffff'
  on-tertiary: '#452a16'
  tertiary-container: '#ffdcc6'
  on-tertiary-container: '#805d45'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#d2e4ff'
  secondary-fixed-dim: '#a0caff'
  on-secondary-fixed: '#001c37'
  on-secondary-fixed-variant: '#00497e'
  tertiary-fixed: '#ffdcc6'
  tertiary-fixed-dim: '#eabda0'
  on-tertiary-fixed: '#2d1604'
  on-tertiary-fixed-variant: '#5f402a'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  h1-desktop:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  h1-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
  h2:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  h3:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  data-mono:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  max-width: 1440px
---

## Brand & Style

The design system is built upon a juxtaposition of mid-century sartorial elegance and modern data engineering. It targets the Mexican financial landscape, where traditional professional standards meet the demand for high-speed digital auditing. 

The visual style is **Sophisticated Minimalism** with **Corporate** undertones. It rejects decorative softness in favor of geometric precision, mirroring the sharp creases of a tailored suit and the rigid structure of accounting ledgers. The atmosphere is one of absolute authority, reliability, and "gentlemanly" discretion, ensuring that the automated processing of sensitive fiscal data (RFCs, tax IDs, and amounts) feels both secure and premium.

## Colors

This design system utilizes a high-contrast dark mode strategy to emphasize data density and visual hierarchy.

- **Primary (Stark White):** The foundational color (#F3F3F3) for key interactive elements, primary typography, and prominent UI nodes, ensuring high visibility against the dark core backgrounds.
- **Secondary (Vibrant Fedora Blue):** Used for interaction states, data highlights, and action-oriented nodes.
- **Tertiary (Fedora Brown):** A distinction color reserved for secondary actions, subtle branding accents, and specialized status indicators.
- **Contrast (Pure White):** Reserved for high-level emphasis and the "paper" surfaces of digital ticket representations.
- **Muted Tones:** Carbon Grey provides depth for nested UI elements, while soft dark tones are used for containers to maintain a high-density professional atmosphere.

## Typography

Typography is used to distinguish between brand presence and functional utility.

- **Headlines:** Montserrat provides a bold, commanding presence. H1 elements must always be uppercase to evoke the authoritative feel of classic newsprint and legal documents.
- **Body & Data:** Inter is the workhorse for all fiscal information. It is specifically chosen for its legibility in high-density tables, ensuring that Mexican RFCs (tax IDs) and complex currency strings are unambiguous. 
- **Numerical Data:** For financial tables, use `data-mono` (Inter with appropriate tracking) to ensure vertical alignment of digits.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to maintain the structural integrity of complex data tables, transitioning to a fluid single-column model on mobile.

- **Grid:** A 12-column system with a 16px gutter.
- **Rhythm:** All spacing must be multiples of 4px. Use generous 32px margins for data-heavy views to prevent visual fatigue.
- **Accounting Layouts:** When presenting ticket totals and tax breakdowns, use a two-column distribution within the container where labels are left-aligned and amounts are strictly right-aligned to follow traditional accounting standards.

## Elevation & Depth

This design system uses **Bold Borders** and **Tonal Layers** rather than shadows to define depth, maintaining a flat, geometric aesthetic.

- **Surface Levels:** The base level is a deep, foundational dark tone. Secondary containers use tonal layering to create a subtle lift.
- **The "Ticket" Surface:** Digital representations of purchase tickets use a Pure White (#FFFFFF) background with zero elevation/shadow, defined instead by a crisp 1px border.
- **Interactive States:** Depth is communicated through color shifts (e.g., #F3F3F3 transitioning to Blue highlights) rather than physical displacement or shadows.

## Shapes

The shape language is strictly **Geometric (Sharp)**. 

Every element—including buttons, input fields, cards, and dropdowns—must have a 0px border radius. This lack of rounding reinforces the "unrefined" but precise nature of the brand, echoing the sharp edges of a physical paper ticket and the rigidity of financial law.

## Components

### Buttons
- **Primary:** Solid #F3F3F3 background with dark uppercase Montserrat text. 0px radius.
- **Secondary:** Solid #6F4E37 background. Used for "Distinction" actions (e.g., Export, Finalize).
- **Ghost:** White border (1px) with no fill, used for secondary navigation.

### Data Tables
- **Header:** Dark container background with white `label-caps` text.
- **Cells:** Clear Inter typography. Numerical columns (Total, VAT, IEPS) must be right-aligned.
- **Dividers:** 1px solid lines using sharp contrast borders for both dark and light surfaces.

### Dropzones
- **Style:** 2px dashed border using #1D70B8. 
- **Content:** Central icon representing the "Fedora" brand mark or a document upload symbol, accompanied by uppercase Montserrat instructional text.

### Input Fields
- **Default:** Transparent background with 1px #F3F3F3 border.
- **Focus:** Border color shifts to #1D70B8 with a subtle inner glow (no blur).

### Cards / Ticket Views
- Rectangular white containers for data extraction results. Use 1px borders. No shadows. Ensure vertical rhythm is maintained with 8px or 16px internal padding.