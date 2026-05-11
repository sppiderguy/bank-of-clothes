---
name: Bank of Clothes PMU Platform
colors:
  surface: '#fbf9fb'
  surface-dim: '#dbd9dc'
  surface-bright: '#fbf9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f5'
  surface-container: '#efedef'
  surface-container-high: '#e9e7ea'
  surface-container-highest: '#e4e2e4'
  on-surface: '#1b1c1d'
  on-surface-variant: '#44474d'
  inverse-surface: '#303032'
  inverse-on-surface: '#f2f0f2'
  outline: '#74777d'
  outline-variant: '#c4c6cd'
  surface-tint: '#4d6079'
  primary: '#000917'
  on-primary: '#ffffff'
  primary-container: '#0d2137'
  on-primary-container: '#7689a4'
  inverse-primary: '#b5c8e5'
  secondary: '#006876'
  on-secondary: '#ffffff'
  secondary-container: '#92edff'
  on-secondary-container: '#006d7b'
  tertiary: '#000c07'
  on-tertiary: '#ffffff'
  tertiary-container: '#00261c'
  on-tertiary-container: '#009a79'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#b5c8e5'
  on-primary-fixed: '#081c32'
  on-primary-fixed-variant: '#364860'
  secondary-fixed: '#9eefff'
  secondary-fixed-dim: '#77d4e5'
  on-secondary-fixed: '#001f24'
  on-secondary-fixed-variant: '#004e59'
  tertiary-fixed: '#65fbcf'
  tertiary-fixed-dim: '#40deb3'
  on-tertiary-fixed: '#002117'
  on-tertiary-fixed-variant: '#00513e'
  background: '#fbf9fb'
  on-background: '#1b1c1d'
  surface-variant: '#e4e2e4'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-desktop: 64px
  margin-tablet: 32px
  margin-mobile: 16px
  max-width: 1280px
---

## Brand & Style
The design system is built upon the principles of **Community Utility** and **Institutional Trust**. It serves a platform that manages resources for a "Bank of Clothes," requiring a UI that feels as reliable as a financial institution but as accessible as a local community center. 

The aesthetic style is **Corporate / Modern**, characterized by a rigorous commitment to organization and clarity. It avoids excessive ornamentation in favor of a clean, light-filled environment where content takes center stage. The mood is professional yet optimistic, achieved through the high-contrast pairing of deep navy with vibrant mint accents.

## Colors
The palette is structured to drive focus and signify action:
- **Primary (Navy - #0D2137):** Used for structural elements, navigation headers, and primary typography to establish authority and groundedness.
- **Secondary (Teal - #028090):** The functional color. Used for secondary actions, links, and highlighting active states.
- **Tertiary (Mint Green - #02C39A):** The "success" and "community" accent. Used for positive status indicators, growth metrics, and high-visibility calls to action.
- **Neutral/Background:** A clean light grey (#F8FAFC) is used for the canvas to reduce eye strain, while pure white (#FFFFFF) is reserved for cards and interactive containers to provide "lift."

## Typography
This design system utilizes **Inter** to achieve a modern, systematic feel. The typography is optimized for legibility in data-heavy environments.
- **Hierarchy:** Headlines use a semi-bold or bold weight with tighter letter spacing to feel impactful.
- **Readability:** Body text utilizes a generous line height (1.5x) to ensure large blocks of community information or clothing descriptions remain scannable.
- **Utility:** Labels use a slightly heavier weight and increased letter spacing to clearly differentiate metadata from body content.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop to maintain a professional, dashboard-like structure, transitioning to a fluid model for mobile devices.
- **Grid:** A 12-column system is used for desktop. Components should snap to these columns to maintain vertical rhythm.
- **Spacial Scale:** An 8px base unit (0.5rem) governs all padding and margins. 
- **White Space:** Generous gutters (24px) are utilized between cards to prevent the UI from feeling cluttered, reinforcing the "organized" brand pillar.

## Elevation & Depth
Depth is communicated through **Ambient Shadows** and tonal layering rather than heavy borders.
- **Level 1 (Cards/Inputs):** A subtle, diffused shadow (Y: 2px, Blur: 8px, 4% Black) is applied to white containers against the light grey background.
- **Level 2 (Hover/Modals):** Increased shadow depth (Y: 8px, Blur: 20px, 8% Navy) suggests interactivity and brings elements to the foreground.
- **Borders:** Low-contrast outlines (1px solid #E2E8F0) are used sparingly for input fields and list item separators to provide structure without adding visual noise.

## Shapes
The shape language is consistently **Rounded**, striking a balance between industrial precision and community warmth.
- **Standard Elements:** Buttons, input fields, and standard cards utilize a 0.5rem (8px) radius.
- **Large Containers:** Hero sections or main dashboard panels use "rounded-lg" (1rem / 16px) to soften the overall appearance of the platform.
- **Tags/Status:** Pill-shaped rounding is reserved for status badges (e.g., "In Stock," "Donated") to distinguish them from actionable buttons.

## Components
- **Buttons:** Primary buttons are Navy (#0D2137) with white text. Secondary buttons use the Teal (#028090) as an outline or ghost style. Interaction states should involve a slight darkening of the hex code.
- **Cards:** Pure white background with 0.5rem rounded corners and Level 1 shadows. Content within cards should have a consistent 24px internal padding.
- **Inputs:** Fields use a 1px #E2E8F0 border that transitions to a 2px Teal (#028090) border upon focus.
- **Chips & Badges:** Used for clothing categories (e.g., "Outerwear," "Children's"). These should use the Mint Green (#02C39A) with a low-opacity background tint for high readability.
- **Icons:** Use a consistent line-weight (2px). Icons should be monochromatic (Navy or Teal) to maintain a professional, streamlined aesthetic.
- **Progress Bars:** Use Mint Green (#02C39A) to track donation goals or inventory levels, symbolizing growth and positive community impact.