---
name: Financial Professionalism Modernized
colors:
  surface: '#f7fafd'
  surface-dim: '#d7dadd'
  surface-bright: '#f7fafd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f7'
  surface-container: '#ebeef1'
  surface-container-high: '#e5e8eb'
  surface-container-highest: '#e0e3e6'
  on-surface: '#181c1e'
  on-surface-variant: '#43474e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eef1f4'
  outline: '#73777f'
  outline-variant: '#c3c6cf'
  surface-tint: '#436084'
  primary: '#002444'
  on-primary: '#ffffff'
  primary-container: '#1a3a5c'
  on-primary-container: '#87a4cc'
  inverse-primary: '#abc9f2'
  secondary: '#755b05'
  on-secondary: '#ffffff'
  secondary-container: '#fed97c'
  on-secondary-container: '#785d08'
  tertiary: '#002542'
  on-tertiary: '#ffffff'
  tertiary-container: '#003b65'
  on-tertiary-container: '#7ca6d6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#abc9f2'
  on-primary-fixed: '#001c37'
  on-primary-fixed-variant: '#2a486b'
  secondary-fixed: '#ffdf94'
  secondary-fixed-dim: '#e6c269'
  on-secondary-fixed: '#251a00'
  on-secondary-fixed-variant: '#594400'
  tertiary-fixed: '#d1e4ff'
  tertiary-fixed-dim: '#a0cafc'
  on-tertiary-fixed: '#001d35'
  on-tertiary-fixed-variant: '#184974'
  background: '#f7fafd'
  on-background: '#181c1e'
  surface-variant: '#e0e3e6'
  surface-white: '#FFFFFF'
  status-success: '#2D6A4F'
  status-error: '#D90429'
  text-primary: '#1A3A5C'
  text-muted: '#64748B'
typography:
  display-lg:
    fontFamily: IBM Plex Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  headline-sm:
    fontFamily: IBM Plex Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.02em
  data-mono:
    fontFamily: jetbrainsMono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.4'
  headline-lg-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The brand personality is rooted in **institutional trust, precision, and modern efficiency**. This design system balances the authoritative weight of traditional finance with the streamlined usability of contemporary SaaS. It targets financial analysts, auditors, and administrators who require high data density without cognitive overload.

The visual style is a hybrid of **Minimalism and Corporate Modern**. It utilizes a "light-first" approach with expansive whites and subtle grays to ensure legibility, while using deep navy and gold to anchor the interface in a sense of prestige and value. The design avoids unnecessary flourish, focusing instead on structural clarity and functional hierarchy.

## Colors
The palette is led by **Deep Navy (#1A3A5C)**, representing stability and expertise. This is used for primary actions, navigation backgrounds, and high-level headings. **Gold (#E8C46A)** is used sparingly as a high-intent accent color, specifically for primary call-to-actions, currency-related highlights, and critical "Golden Path" interactions.

**Tertiary Blue (#1F4E79)** provides a softer alternative for secondary actions and active states in navigation. The **Neutral Gray (#EEF1F4)** is the foundation for the UI, used for background fills and card grouping to create a soft separation from the pure white surfaces of active data containers.

## Typography
For English, **IBM Plex Sans** is selected for its systematic, corporate appearance that remains highly legible in dense environments. Its technical DNA perfectly matches the "Financial Professionalism" narrative. For Arabic, a matching Naskh-style sans-serif must be used to maintain the vertical rhythm and baseline alignment.

A dedicated **Data Mono (JetBrains Mono)** role is included for UIDs, currency values, and audit logs to ensure tabular alignment and numerical clarity. Headline levels scale down for mobile devices to prevent excessive line-breaking in complex financial labels.

## Layout & Spacing
This design system utilizes a **Fixed Grid** model on desktop (1280px max-width) to mimic the structured nature of financial reports, and a **Fluid Grid** on mobile for adaptability. 

- **Desktop (1200px+):** 12-column grid, 24px gutters, 40px side margins.
- **Tablet (768px - 1199px):** 8-column grid, 16px gutters, 24px side margins.
- **Mobile (Up to 767px):** 4-column grid, 12px gutters, 16px side margins.

A strict **4px baseline grid** governs all internal component spacing (padding/margins). Information-dense areas like data tables should use a "Compact" 8px vertical padding, while dashboard cards use a "Standard" 24px padding to provide breathing room.

## Elevation & Depth
To maintain professional clarity and print-friendliness, depth is primarily conveyed through **Tonal Layers** rather than heavy shadows.

1.  **Level 0 (Base):** Neutral Gray background (#EEF1F4).
2.  **Level 1 (Cards/Containers):** Pure White surface (#FFFFFF) with a 1px border (#E2E8F0). No shadow.
3.  **Level 2 (Modals/Popovers):** Pure White surface with a "Precision Shadow": 0px 4px 12px rgba(26, 58, 92, 0.08). This shadow is tinted with the primary navy color to keep it integrated with the palette.
4.  **Level 3 (Primary Actions):** Primary Navy surfaces used for buttons or active tabs.

Interactive states utilize a 10% opacity overlay of the primary color on hover, rather than changing the elevation height.

## Shapes
The shape language is **Soft (0.25rem)**. This subtle rounding provides a modern feel without sacrificing the "serious" architectural structure required for financial software. 

- **Standard Inputs/Buttons:** 4px (0.25rem) radius.
- **Cards & Data Containers:** 8px (0.5rem) radius.
- **Status Chips:** Full pill-shaped (rounded-full) to distinguish them from interactive buttons.
- **Selection Indicators:** Sharp vertical bars (0px radius) on the left side of active sidebar items to indicate focus.

## Components

### Buttons
- **Primary:** Navy background, white text. No shadow, flat design.
- **Secondary:** Transparent background, 1px Navy border.
- **Accent:** Gold background, Navy text (reserved for high-conversion or "Save" actions).

### Cards & Stats
Dashboard cards must feature a "Gold Accent Bar" (2px top border) when displaying critical financial metrics. Use `data-mono` for the primary numerical value to ensure it stands out from descriptive labels.

### Data Tables
Tables are the heart of this design system.
- **Header:** Light gray background (#F8FAFC), Navy semi-bold text.
- **Rows:** White background with 1px bottom border. Hover state should use a #F1F5F9 fill.
- **Alignment:** Financial values should always be right-aligned; text should be left-aligned (or right-aligned for Arabic RTL).

### Input Fields
Inputs use a white background with a 1px gray border. On focus, the border transitions to Primary Navy with a 2px "Soft Ring" (0.15 opacity navy). Labels should always be visible above the field in `label-md`.

### Navigation
Sidebar navigation uses a dark mode-inspired theme (Navy background) even in the light mode system to create a strong structural anchor. Icons are gold when active and muted white when inactive.