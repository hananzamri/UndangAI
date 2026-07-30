---
name: Institutional Minimalist
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#261900'
  on-tertiary-container: '#a17f3b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffdea5'
  tertiary-fixed-dim: '#e9c176'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4201'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Source Serif 4
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Source Serif 4
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Source Serif 4
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Source Serif 4
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  headline-sm:
    fontFamily: Source Serif 4
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
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
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  xxl: 64px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style
The design system is engineered to project absolute reliability and modern legal authority. It targets legal professionals, corporate entities, and government bodies within the ASEAN region. The aesthetic balances the heritage of the legal profession with the efficiency of a high-tech infrastructure platform.

The design style is **Minimalist-Professional**. It utilizes expansive whitespace to reduce cognitive load during complex legal tasks, paired with precise, thin-stroke iconography and structured layouts. The emotional response is one of "calm confidence"—a high-trust environment where data is organized and navigation is intuitive. Avoid all decorative elements that do not serve a functional purpose.

## Colors
The palette is rooted in **Deep Midnight Navy**, signifying depth, stability, and institutional trust. **Champagne Gold** is used sparingly as a prestige accent for primary actions and brand-defining moments, ensuring it feels like an mark of quality rather than a decorative flourish.

**Soft Slate Grey** provides the foundation for secondary information and borders, maintaining a lower visual hierarchy than the primary navy text. The background strategy relies on a crisp **Off-white** to prevent screen glare during long reading sessions, with pure white reserved for elevated cards and document surfaces. Status colors are slightly desaturated to remain professional while providing clear utility.

## Typography
The typographic strategy employs a high-contrast pairing:
- **Headlines:** Use *Source Serif 4*. This serif provides the traditional "weight" expected in legal contexts, echoing the authority of printed law and academic journals.
- **Body & Interface:** Use *Inter*. This provides maximum legibility for dense legal text and complex data tables. Its neutral, systematic nature ensures the interface stays out of the user's way.

Ensure that for long-form legal documents, `body-lg` is used with a maximum line length of 70 characters to optimize reading speed and comprehension.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop to maintain structural integrity and professional alignment, switching to a fluid model for mobile devices. 

- **Desktop (1280px+):** 12-column grid, 24px gutters, and 40px external margins.
- **Tablet (768px - 1279px):** 8-column grid, 24px gutters, 24px margins.
- **Mobile (< 767px):** 4-column grid, 16px gutters, 16px margins.

The spacing rhythm is based on a 4px baseline. Use `xl` (40px) and `xxl` (64px) for section vertical spacing to maintain the minimalist, airy feel. Content should be grouped logically using negative space rather than heavy dividers wherever possible.

## Elevation & Depth
Elevation is expressed through **Tonal Layering** and **Ambient Shadows**. This design system avoids heavy shadows to maintain a "flat" professional profile.

1.  **Level 0 (Base):** Off-white (`#F8FAFC`). For the main background.
2.  **Level 1 (Surface):** White (`#FFFFFF`). Used for cards, document panels, and input areas. Defined by a subtle 1px border in `Soft Slate Grey` at 10% opacity.
3.  **Level 2 (Navigation/Floating):** White with a soft, diffused shadow. Shadow: `0 4px 12px rgba(15, 23, 42, 0.05)`.
4.  **Level 3 (Modals):** White with a deeper, multi-layered shadow. Shadow: `0 12px 32px rgba(15, 23, 42, 0.1)`.

Depth is also communicated through the use of side-by-side "panes" for document comparison, where the active pane may have a 2px Champagne Gold top-border.

## Shapes
The shape language is **Soft**. Sharp 0px corners are too aggressive for a modern platform, while highly rounded "pill" shapes feel too casual.

- **Standard (Buttons, Inputs, Cards):** 4px (`0.25rem`) corner radius. This creates a precise, architectural feel.
- **Large (Modals, Featured Containers):** 8px (`0.5rem`) corner radius.
- **Document Previews:** Maintain a strict 0px or 2px radius to mimic the feel of physical paper.

## Components
- **Buttons:** 
  - *Primary:* Deep Midnight Navy with White text. 4px radius. High-contrast.
  - *Secondary:* Transparent with Deep Midnight Navy border (1px).
  - *Action:* Champagne Gold is reserved for "Finalize," "Sign," or "Upgrade" actions only.
- **Legal Documents:** Displayed on a white "sheet" container with a Level 1 elevation. Line numbers should be visible in the left margin in `Soft Slate Grey`.
- **Side-by-Side Comparison:** Two synchronized scrolling panes. The "Difference" between texts should be highlighted using a pale version of the Success (addition) and Error (deletion) colors.
- **Search Results:** Clean list items with a `headline-sm` title. Metadata (Date, Court, Jurisdiction) should use `label-sm` in `Soft Slate Grey`.
- **Inputs:** Simple 1px borders. On focus, the border transitions to Deep Midnight Navy. Use `body-md` for input text.
- **Chips:** Used for legal tags (e.g., "Civil Law," "Precedent"). Solid `Soft Slate Grey` at 10% opacity with Navy text, 2px radius.