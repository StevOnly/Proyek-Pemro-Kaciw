---
name: MugiTrack Operations
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#43474e'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#73777f'
  outline-variant: '#c3c6cf'
  surface-tint: '#3f608a'
  primary: '#002547'
  on-primary: '#ffffff'
  primary-container: '#163b63'
  on-primary-container: '#85a6d4'
  inverse-primary: '#a8c9f9'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#002934'
  on-tertiary: '#ffffff'
  tertiary-container: '#004050'
  on-tertiary-container: '#43b1d3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3e3ff'
  primary-fixed-dim: '#a8c9f9'
  on-primary-fixed: '#001c39'
  on-primary-fixed-variant: '#264871'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#b7eaff'
  tertiary-fixed-dim: '#6cd3f7'
  on-tertiary-fixed: '#001f28'
  on-tertiary-fixed-variant: '#004e61'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  container-max: 1440px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
---

## Brand & Style
The design system is engineered for industrial reliability and operational clarity. It serves a manufacturing environment where precision in production and distribution is paramount. The brand personality is **Corporate/Modern**, emphasizing structural integrity and systematic organization.

The UI evokes a sense of "Operational Trust"—it is dependable enough for a factory floor and sophisticated enough for executive reporting. The style utilizes a refined professional aesthetic: high-density information layouts, clear visual hierarchies, and a restrained use of color to highlight actionable data. The interface prioritizes utility and speed of comprehension, ensuring that CV. Mugi Jaya's manufacturing workflows remain fluid and error-free.

## Colors
This design system utilizes a high-contrast professional palette to distinguish between structural elements and active status indicators.

- **Primary Navy (#163B63):** Used for persistent navigation, sidebars, and primary branding elements to convey stability.
- **Secondary Blue (#2563EB):** The "Action Color" used for primary buttons, active states, and selection indicators.
- **Functional Colors:** Success (Green), Warning (Amber), and Danger (Red) are used strictly for status badges (e.g., *Selesai*, *Tertunda*, *Gagal*) and critical alerts.
- **Backgrounds:** The main canvas uses a cool slate white (#F8FAFC) to reduce eye strain, while the Light Blue Background (#EFF6FF) is reserved for subtle grouping or sectioning of related data.

## Typography
The system uses **Inter** for its exceptional legibility in data-heavy environments. The scale is optimized for high-density SaaS interfaces.

- **Headlines:** Use SemiBold (600) for page titles like *Daftar Produksi* or *Manajemen Distribusi*.
- **Body:** The standard 14px size ensures that large tables and lists remain readable without excessive scrolling.
- **Labels:** Small, all-caps bold labels are used for metadata and table headers to provide clear distinction from row data.
- **Language:** All typography must support Indonesian characters and accommodate longer word lengths common in Indonesian technical terms (e.g., *Pertanggungjawaban*).

## Layout & Spacing
The design system employs a **Fixed Grid** model for desktop to maintain structural consistency, transitioning to a fluid model for tablet and mobile.

- **Grid:** A 12-column grid system with 16px gutters.
- **Rhythm:** An 8px linear scale is used for most components, while a 4px "half-step" is permitted for tight density in data tables or compact forms.
- **Responsive Behavior:** 
  - **Desktop (1280px+):** Sidebar is persistent. Content is centered with a max-width of 1440px.
  - **Tablet (768px - 1279px):** Sidebar collapses to icons. Margins reduce to 24px.
  - **Mobile (<767px):** Single column layout. Sidebars move to a bottom sheet or "hamburger" overlay. Margins are 16px.

## Elevation & Depth
Depth is communicated through **Tonal Layers** and subtle **Ambient Shadows**. This creates a clear hierarchy without distracting the user from the manufacturing data.

- **Level 0 (Base):** Background (#F8FAFC).
- **Level 1 (Cards/Sheets):** White surface (#FFFFFF) with a very soft, diffused shadow (0px 2px 4px rgba(22, 59, 99, 0.05)).
- **Level 2 (Dropdowns/Modals):** White surface with a more pronounced shadow (0px 8px 24px rgba(22, 59, 99, 0.12)).
- **Interactions:** Hover states on interactive cards should slightly increase shadow spread to indicate "lift," while clicked states should flatten back to Level 1.

## Shapes
The shape language reflects the precision of glass and aluminum cutting. Corners are rounded enough to feel modern and accessible, but remain structured.

- **Standard Elements:** Buttons and input fields use a `0.5rem` (8px) radius.
- **Large Containers:** Cards and major sections use `rounded-lg` (16px) to create a distinct frame for production data.
- **Badges:** Status badges (e.g., *Dalam Proses*) use a full pill-shape (999px) to differentiate them from clickable rectangular buttons.

## Components
Consistent component behavior ensures CV. Mugi Jaya staff can operate the system with minimal training.

- **Cards:** White background, 16px border radius, subtle border (#E2E8F0), and Level 1 elevation. Used for grouping production batches or delivery details.
- **Tables:** Minimalist design with no vertical borders. Headers are #64748B (Neutral) in 12px Bold. Rows alternate with a subtle hover effect using #EFF6FF.
- **Status Badges:** Small font size (12px), bold weight, using a "light background + dark text" pattern (e.g., Success Green text on a 10% opacity Green background).
- **Primary Buttons:** Solid Secondary Blue (#2563EB) with white text. Height: 40px for desktop, 48px for touch-friendly mobile views.
- **Input Fields:** 1px border (#CBD5E1), 8px radius. Active state uses a 2px Secondary Blue ring. Labels always appear above the field in 12px Bold.
- **Data Visualization:** Use simple bar charts and progress rings. Use Secondary Blue for "In Progress" and Success Green for "Target Reached."