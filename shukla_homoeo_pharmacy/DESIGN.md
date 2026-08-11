---
name: Shukla Homoeo Pharmacy
colors:
  surface: '#f7fbf1'
  surface-dim: '#d8dbd2'
  surface-bright: '#f7fbf1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f5ec'
  surface-container: '#ecefe6'
  surface-container-high: '#e6e9e0'
  surface-container-highest: '#e0e4db'
  on-surface: '#191d17'
  on-surface-variant: '#41493e'
  inverse-surface: '#2d322c'
  inverse-on-surface: '#eff2e9'
  outline: '#717a6d'
  outline-variant: '#c0c9bb'
  surface-tint: '#2a6b2c'
  primary: '#00450d'
  on-primary: '#ffffff'
  primary-container: '#1b5e20'
  on-primary-container: '#90d689'
  inverse-primary: '#91d78a'
  secondary: '#00629e'
  on-secondary: '#ffffff'
  secondary-container: '#62b4fe'
  on-secondary-container: '#004470'
  tertiary: '#6b1d3d'
  on-tertiary: '#ffffff'
  tertiary-container: '#883454'
  on-tertiary-container: '#ffaec6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#acf4a4'
  primary-fixed-dim: '#91d78a'
  on-primary-fixed: '#002203'
  on-primary-fixed-variant: '#0c5216'
  secondary-fixed: '#cfe5ff'
  secondary-fixed-dim: '#99cbff'
  on-secondary-fixed: '#001d34'
  on-secondary-fixed-variant: '#004a78'
  tertiary-fixed: '#ffd9e2'
  tertiary-fixed-dim: '#ffb1c8'
  on-tertiary-fixed: '#3e001d'
  on-tertiary-fixed-variant: '#7a2949'
  background: '#f7fbf1'
  on-background: '#191d17'
  surface-variant: '#e0e4db'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.5px
  price-tag:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style
The design system for this pharmacy store balances clinical expertise with a welcoming, local community feel. The narrative is centered on "Trustworthy Vitality"—combining the traditional stability of homeopathic medicine with a modern, efficient e-commerce experience.

The style is **Modern Corporate** with subtle **Tactile** influences. It prioritizes clarity and cleanliness to reduce cognitive load during a healthcare purchase. The interface uses generous white space, soft color transitions, and high-quality iconography to evoke a sense of professional care and reliability. The visual language is designed to feel approachable for all age groups while maintaining the precision expected of a medical institution.

## Colors
The palette is grounded in the psychological associations of health and trust. 

- **Primary Green (#1B5E20):** Used for branding, headers, and successful states. It represents nature and homeopathic tradition.
- **Secondary Medical Blue (#0277BD):** Reserved strictly for interactive elements, Primary CTAs, and links to ensure high discoverability.
- **Background Tints:** Light Green (#F1F8E9) is used for the main app canvas to keep the vibe organic. Light Blue (#E1F5FE) is used for specific informational callouts or "Pharmacy Choice" sections.
- **Status Colors:** Use standard semantic reds for "Out of Stock" or errors, and amber for "Low Stock" warnings.

## Typography
Inter is selected for its exceptional legibility and neutral, professional character. 

- **Hierarchical Contrast:** Use `Display LG` for pharmacy section titles and `Headline MD` for category names.
- **Product Details:** Medicine names should always use `Title LG` to ensure they are the first thing a user sees on a card.
- **Numerical Data:** Prices and dosage instructions use a slightly heavier weight (`700`) to stand out against descriptive body text.
- **Mobile Adaptation:** On smaller screens, `Display LG` scales down to 28px to prevent awkward text wrapping on long homeopathic remedy names.

## Layout & Spacing
The layout follows a **Fluid Grid** system with a focus on vertical rhythm. 

- **Grid:** Use a 4-column grid for mobile and a 12-column grid for desktop.
- **Product Grids:** Maintain a 16px gutter between product cards to allow the white space to act as a separator, preventing the medical catalog from feeling cluttered.
- **Vertical Spacing:** Use `lg (24px)` between major sections (e.g., between "Shop by Category" and "Best Sellers").
- **Safe Areas:** Medicine details pages should use increased margins (`xl`) to focus the user's attention on the product description and usage instructions.

## Elevation & Depth
This design system utilizes **Tonal Layers** and **Ambient Shadows** to create a structured hierarchy.

- **Level 0 (Surface):** The background (#F1F8E9).
- **Level 1 (Cards):** Pure white surfaces with a soft, 10% opacity shadow (0px 4px 12px) to distinguish medicine products from the background.
- **Level 2 (Interactive):** Floating Action Buttons (FABs) for "Cart" or "Chat with Pharmacist" use a more pronounced shadow (0px 8px 24px) to suggest clickability.
- **Overlays:** Modals for dosage instructions use a 40% dimmed backdrop with a white container to ensure zero distractions.

## Shapes
The shape language is "Friendly Professional." 

- **Standard Elements:** Use `rounded-lg` (12px) for product cards, medicine imagery, and category containers.
- **Action Elements:** Use `rounded-xl` (24px) for search bars, primary buttons, and chip filters. This pill-shape styling makes the app feel more modern and approachable.
- **Iconography:** Icons should be contained within circular or soft-square backgrounds to maintain the "medical stamp" aesthetic.

## Components

### Medicine Product Cards
- **Surface:** White background, 12px corner radius.
- **Content:** Product image at top, followed by `Title LG` for the name. 
- **Pricing:** Show "Current Price" in `Primary Green` and "Original Price" in `Text Muted` with a strikethrough. Add a small badge in the corner for "Save 15%".
- **Action:** A small "+" blue button at the bottom right for quick "Add to Cart."

### Search Bar
- **Style:** 24px corner radius, white background with a 1px border (#E0E0E0).
- **Iconography:** Left-aligned magnifying glass in `Secondary Blue`.
- **Placeholder:** "Search for medicines, dilutions, or brands..."

### Category Chips
- **Style:** Pill-shaped (24px), light grey stroke.
- **Active State:** Solid `Primary Green` background with white text.
- **Visuals:** Include a small 16px icon (e.g., a drop icon for Dilutions, a pill icon for Tablets).

### Buttons
- **Primary:** Medical Blue (#0277BD) background, white text, 24px radius, bold weight.
- **Secondary:** Outline button with `Primary Green` border for "View Details" or "Refill Prescription."

### Pharmacy-Specific Icons
- Icons must be "Line-Art" style with a 2px stroke width.
- Use specific metaphors: a mortar and pestle for "Ayurvedic/Homeo," a stethoscope for "Consultation," and a truck for "Express Delivery."