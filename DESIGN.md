---
name: Precision Industrial System
colors:
  surface: '#f7f9fc'
  surface-dim: '#d8dadd'
  surface-bright: '#f7f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f7'
  surface-container: '#eceef1'
  surface-container-high: '#e6e8eb'
  surface-container-highest: '#e0e3e6'
  on-surface: '#191c1e'
  on-surface-variant: '#5c4037'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f4'
  outline: '#907066'
  outline-variant: '#e5beb2'
  surface-tint: '#ac3400'
  primary: '#a83300'
  on-primary: '#ffffff'
  primary-container: '#d24200'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb59d'
  secondary: '#5257a3'
  on-secondary: '#ffffff'
  secondary-container: '#a7acff'
  on-secondary-container: '#383d88'
  tertiary: '#585b6e'
  on-tertiary: '#ffffff'
  tertiary-container: '#717388'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59d'
  on-primary-fixed: '#390b00'
  on-primary-fixed-variant: '#832600'
  secondary-fixed: '#e0e0ff'
  secondary-fixed-dim: '#bfc2ff'
  on-secondary-fixed: '#090c5e'
  on-secondary-fixed-variant: '#3a3f8a'
  tertiary-fixed: '#e0e1f8'
  tertiary-fixed-dim: '#c3c5dc'
  on-tertiary-fixed: '#181b2b'
  on-tertiary-fixed-variant: '#434658'
  background: '#f7f9fc'
  on-background: '#191c1e'
  surface-variant: '#e0e3e6'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: '0'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-technical:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system embodies high-precision industrial manufacturing and CNC machining. The aesthetic combines clean, modern engineering rigor with dynamic technical energy.

- **Brand Personality:** Methodical, high-tolerance, authoritative, and forward-looking.
- **Target Audience:** Industrial procurement directors, mechanical engineers, aerospace contractors, automotive project managers, and tier-1 tooling suppliers.
- **Emotional Response:** Inspires confidence in dimensional accuracy, operational safety, cutting-edge machinery, and dependable delivery cycles.
- **Visual Style:** Industrial Precision Minimalist with technical blueprint undertones. Layouts prioritize clean visual structure, high legibility, micro-grid accents, crisp technical tags, and authoritative contrast between dark structural elements and high-visibility safety orange cues.

## Colors

The color palette is engineered around high functional contrast, reflecting industrial machining standards and technical clarity:

- **Primary (`#F84F00`):** High-visibility dynamic orange reserved for high-priority calls to action, active machine states, measurement highlights, and focal interactive elements.
- **Secondary (`#03045A`):** Deep institutional blueprint blue representing structural durability, technical certainty, and heavy machinery integrity. Used for key headlines, primary navigational framing, and emphasized borders.
- **Tertiary (`#0B0E1E`):** Dark slate/carbide black applied to high-density technical footers, contextual terminal-style telemetry displays, and code/specification panels.
- **Neutral Surface (`#F5F7FA`):** Low-strain technical light gray for canvas backdrops, data tables, secondary cards, and structural containment layers.
- **Pure White (`#FFFFFF`):** High-clarity foreground surface dedicated to interactive form inputs, primary cards, modals, and content containers.
- **Subtle Blueprint Grid Line:** `rgba(3, 4, 90, 0.06)` against `#F5F7FA` surfaces for micro-grid technical details without clutter.

## Typography

Typography prioritizes geometric precision and rapid technical scanning across large format displays and factory-floor mobile devices:

- **Display & Headlines:** Set in `Space Grotesk`. Its mechanical terminals and modern geometric balance convey precision manufacturing, tooling power, and architectural balance.
- **Body:** Set in `Hanken Grotesk`. A clean, highly balanced contemporary sans-serif offering neutral, effortless reading across technical specifications and service overviews.
- **Data, Callouts & Blueprint Metrics:** Set in `JetBrains Mono`. Dedicated to dimensional readouts, CNC axis notation (e.g., `X: 420.05mm`), serial tags, tolerances, and parameter labels.
- **Hierarchy Notes:** Headlines use tight negative letter-spacing to express machine-calibrated tightness. Technical labels default to uppercase tracking for rapid identification.

## Layout & Spacing

The layout is built upon an 8-point technical modular grid, reflecting industrial CAD/CAM software structures:

- **Desktop (1200px+):** 12-column fluid grid, max-width 1360px centered, 24px (`1.5rem`) gutters, 48px (`3rem`) horizontal canvas margins.
- **Tablet (768px - 1199px):** 8-column grid with 20px gutters and 32px margins. Multi-column metric dashboards collapse from 4 columns to 2x2.
- **Mobile (under 768px):** 4-column grid with 16px (`1rem`) gutters and 20px (`1.25rem`) horizontal margins. Complex CNC machinery specs switch from table rows to modular key-value cards.
- **Vertical Spacing Rhythm:** Dense 8px/16px gaps between related parameters, 24px/40px separation between functional groups, and 64px/80px separating top-level service and equipment sections.

## Elevation & Depth

Elevation eschews soft, decorative shadows in favor of crisp structural boundaries and functional depth:

- **Layer 0 (Canvas):** `#F5F7FA` with an optional subtle CSS blueprint micro-grid pattern (`16px x 16px` with `#03045A0F` lines).
- **Layer 1 (Card & Module Surfaces):** Solid `#FFFFFF` enclosed with a precision 1px border `rgba(3, 4, 90, 0.12)`.
- **Layer 2 (Hovered & Active Machine Cards):** Border transitions to `rgba(248, 79, 0, 0.40)` with an ultra-crisp directional drop shadow: `0 4px 12px rgba(3, 4, 90, 0.08)`.
- **Layer 3 (Technical Drawers & Overlays):** `#FFFFFF` or `#0B0E1E` panels with `0 16px 36px rgba(11, 14, 30, 0.18)` and a 1px solid separator.
- **Industrial Contrast Accents:** Critical machine status panels and technical footers adopt `#0B0E1E` solid surfaces with inverted white and orange typography for maximum contrast.

## Shapes

To mirror precision-milled aluminum, steel tooling, and CAD workpieces, the shape language uses controlled, restrained radii:

- **Standard Elements (Buttons, Inputs, Metric Badges):** 4px (`0.25rem` / `rounded-md`), representing smooth chamfered edges rather than pillowy or casual rounded forms.
- **Structural Containers (Cards, Modals, Machine Galleries):** 8px (`0.5rem` / `rounded-lg`), providing enough curvature to feel modern while maintaining structural firmness.
- **Interactive Toggles & Checkmarks:** Crisp squared-soft elements (2px to 4px border radius).
- **No Pill Radii:** Fully round or pill-shaped buttons are explicitly prohibited to prevent consumer-app dilution and preserve industrial authority.

## Components

### Buttons
- **Primary Action (CTA):** Solid `#F84F00` background, `#FFFFFF` text, `Space Grotesk` medium weight, 4px radius, 12px 24px padding. Active state darkens to `#DE4600`. Hover delivers subtle scale stability without bouncing.
- **Secondary (Technical/Solid):** Solid `#03045A` background, `#FFFFFF` text. Used for drawing downloads, technical spec sheets, and catalog browsing.
- **Ghost/Outline:** 1.5px solid border `#03045A` with `#03045A` text on transparent background; on hover, fills with `rgba(3, 4, 90, 0.05)`.

### Technical Chips & Tolerance Badges
- **Specification Chip:** Monospace font (`JetBrains Mono`), 2px radius, background `#F5F7FA`, border `1px solid rgba(3, 4, 90, 0.15)`, text `#03045A`.
- **Machine Status Indicators:** Flex container with an 8px pulse dot (`#F84F00` for active/setup, `#10B981` for calibrated/ready) alongside bold monospace coordinates.

### Data Lists & Specification Tables
- **Grid Layout:** Alternating row hover states with `rgba(3, 4, 90, 0.02)`.
- **Headers:** `#0B0E1E` text in uppercase `JetBrains Mono` with bottom border `2px solid #03045A`.
- **Numbers & Units:** Tabular numbers aligned right; units (mm, µm, RPM) displayed in lower contrast gray text.

### Input Fields & RFQ (Request for Quote) Forms
- **Field Anatomy:** `#FFFFFF` background, 1.5px border `rgba(3, 4, 90, 0.20)`, 4px radius, 12px 16px padding.
- **Focus State:** Border shifts to `#F84F00` accompanied by a sharp `0 0 0 1px #F84F00` ring. Labels positioned above in `Hanken Grotesk` medium with uppercase technical hints.
- **CAD File Drag-and-Drop Area:** Dashed 2px border `#03045A` with technical grid background watermark and upload indicator.

### Machine & Capability Cards
- Enclosed in 8px radius container with `#FFFFFF` background and `1px solid rgba(3, 4, 90, 0.10)`.
- Header bar includes machine series (e.g., *5-Axis Machining Center*) in monospace label styling, followed by high-resolution tooling imagery and parameter bullet points separated by technical hair lines.