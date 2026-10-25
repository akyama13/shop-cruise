---
name: Retail Copilot System
colors:
  surface: '#f8faf8'
  surface-dim: '#d8dad9'
  surface-bright: '#f8faf8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f2'
  surface-container: '#eceeec'
  surface-container-high: '#e6e9e7'
  surface-container-highest: '#e1e3e1'
  on-surface: '#191c1b'
  on-surface-variant: '#3f4944'
  inverse-surface: '#2e3130'
  inverse-on-surface: '#eff1ef'
  outline: '#6f7974'
  outline-variant: '#bec9c2'
  surface-tint: '#176b52'
  primary: '#00513c'
  on-primary: '#ffffff'
  primary-container: '#176b52'
  on-primary-container: '#9be9c9'
  inverse-primary: '#89d6b7'
  secondary: '#2d6954'
  on-secondary: '#ffffff'
  secondary-container: '#b2f0d5'
  on-secondary-container: '#346f5a'
  tertiary: '#00514a'
  on-tertiary: '#ffffff'
  tertiary-container: '#006b62'
  on-tertiary-container: '#7fecde'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a4f2d2'
  primary-fixed-dim: '#89d6b7'
  on-primary-fixed: '#002116'
  on-primary-fixed-variant: '#00513c'
  secondary-fixed: '#b2f0d5'
  secondary-fixed-dim: '#96d3ba'
  on-secondary-fixed: '#002117'
  on-secondary-fixed-variant: '#0f503d'
  tertiary-fixed: '#89f5e7'
  tertiary-fixed-dim: '#6bd8cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#005049'
  background: '#f8faf8'
  on-background: '#191c1b'
  surface-variant: '#e1e3e1'
typography:
  display-lg:
    fontFamily: DM Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: DM Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: DM Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: DM Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: DM Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
  metric-num:
    fontFamily: DM Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system is engineered for high-velocity Kirana operations, wholesale stockrooms, and modern Indian retail trade. Kirana merchants and floor managers operate in chaotic, high-turnover environments under varied lighting, demanding immediate legibility, zero-latency workflows, and unyielding cognitive clarity. 

The aesthetic blends **Modern Utilitarian SaaS** with **Pragmatic Retail Ergonomics**. It delivers:
- **Calm Authority**: Built around a deep banyan forest green that evokes trust, stability, and mercantile prosperity.
- **Immediate Legibility**: Compact, high-information-density metric tiles and tabular records engineered for quick scanning across stock tallies and rupee transactions.
- **Physical Reliability**: Tactical, clean surfaces with structured borders and mild elevation that mimic clear ledger sheets rather than transient, abstract interfaces.

## Colors

The palette balances mercantile authority with rapid operational feedback:

- **Primary (`#176B52`)**: Forest Green anchors the primary brand presence, key navigation rails, primary action triggers, and validated ledger summaries.
- **Secondary (`#10513E`)**: Deep Hunter Green provides active press states, focused states, and high-contrast table headers.
- **Tertiary (`#0D9488`)**: Emerald/Teal directs positive inventory flow, incoming supplier shipments, and healthy margin deltas.
- **Surface & Background (`#F6F8F6` / `#FFFFFF`)**: The canvas employs a soft pale tint to neutralize glare under fluorescent shop lighting, while cards retain pure `#FFFFFF` for clear layer separation.
- **Container Tints (`#E8F4ED`)**: Used for contextual item tags, AI assistant dialog bubbles, and active inventory filters.
- **Critical & Warning Feedback**:
  - Expiry/Aging Stock: Amber (`#F59E0B`) with soft amber backdrop (`#FEF3C7`).
  - Stockout Depletion / Overdue Credit: Rose (`#E11D48`) on rose tint (`#FFE4E6`).
  - Subtle Dividing Line: Neutral borders rendered in `#E5E9E6` to maintain architectural structure without visual noise.

## Typography

DM Sans is applied uniformly across display, body, and label roles to maintain structural consistency across desktop monitors, POS terminals, and mobile devices.

- **Tabular Numerics**: Set `font-variant-numeric: tabular-nums lining-nums` across all pricing tables, inventory counts, and currency listings (`₹`). This keeps column decimals vertically aligned for rapid balance sheet checks.
- **Hierarchy & Case**: Micro-labels (such as SKU tags, supplier categories, and batch states) use uppercase styling with positive tracking (`letter-spacing: 0.04em`) to ensure legibility down to 11px.
- **Financial Metrics**: Dedicated `metric-num` style ensures rapid reading of daily revenue, expiring SKUs, and projected stockout days without crowding dense dashboard tiles.

## Layout & Spacing

The layout utilizes a flexible 12-column responsive grid on desktop screens, transitioning to an 8-column layout on store tablets and a 4-column layout on handheld mobile devices.

- **Desktop (1280px+)**: 12-column layout with fixed 240px collapsible side navigation, 1.5rem canvas margins, and 1rem column gutters. Optimized for dual-pane inventory matching and purchase order reconciliation.
- **Tablet (768px - 1279px)**: 8-column layout with off-canvas slideover navigation, 1rem margins, and 1rem gutters for counter-top tablets.
- **Mobile (< 768px)**: 4-column layout prioritizing single-column stackable metric modules and full-width barcode scanner surfaces.
- **Rhythm**: All internal padding, component heights, and card boundaries conform to a 4px/8px modular scale to ensure predictable vertical balance when displaying massive product lists.

## Elevation & Depth

Visual hierarchy uses flat structural containment backed by subtle, tinted shadows rather than dramatic blur layers, ensuring performance on low-spec hardware:

- **Base Layer (Flat)**: Background sits at `#F6F8F6`. Content containers rest at `#FFFFFF` with a crisp 1px structural outline (`#E5E9E6`).
- **Resting Cards**: `box-shadow: 0 1px 3px 0 rgba(16, 81, 62, 0.04), 0 1px 2px -1px rgba(16, 81, 62, 0.02);` subtle green-tinted ambient shadow.
- **Interactive / Hover Surface**: Lifted cards use `box-shadow: 0 4px 6px -1px rgba(16, 81, 62, 0.07), 0 2px 4px -2px rgba(16, 81, 62, 0.05);` with border transition to `#CBD5E1`.
- **Floating Overlays & Quick-Action Bars**: Bottom-docked bulk action drawers and barcode quick-entry triggers use `box-shadow: 0 10px 15px -3px rgba(16, 81, 62, 0.12), 0 4px 6px -4px rgba(16, 81, 62, 0.06);`.

## Shapes

The system implements balanced corner rounding:
- **Standard (`0.5rem` / 8px)**: Base shape for operational cards, data tables, metric tiles, modal containers, and text input boxes.
- **Pill / Circular (9999px)**: Reserved strictly for transient statuses (e.g., "In Stock", "Critical Expiring"), batch identifiers, and compact action triggers (e.g., Quick Add buttons, counter increments).
- **Sub-components (`0.25rem` / 4px)**: Nested elements within dense tables, including checkboxes, barcode pills, and tabular tooltips.

## Components

### Buttons
- **Primary**: Solid `#176B52` background, white label, 8px radius, height 40px (desktop) / 44px (touch/countertop). Hover state transitions to `#10513E`.
- **Secondary**: Crisp 1px border `#176B52` with text `#176B52`, background transparent. Hover state applies `#E8F4ED`.
- **Destructive**: Rose `#E11D48` background with crisp white label for permanent item archiving or inventory write-offs.
- **Quick Action Icon Button**: 36x36px square with 8px radius, centered 18px Lucide icon, subtle `#E5E9E6` border.

### Chips & Badges
- **Status Pills**: Pill-shaped (`rounded-full`), height 24px, 10px horizontal padding, `label-sm` typography.
  - *Healthy Stock*: `#E8F4ED` surface, `#10513E` text, green dot indicator.
  - *Expiring Batch*: `#FEF3C7` surface, `#B45309` text, amber warning icon.
  - *Out of Stock*: `#FFE4E6` surface, `#E11D48` text, rose alert dot.
  - *AI Recommendation*: `#F0FDFA` surface, `#0D9488` text, sparkling indicator icon.

### Form Inputs & Barcode Pickers
- **Text & Numeric Inputs**: White background, 1px border `#E5E9E6`, 8px radius, padding 10px 14px. Focus state shifts border to 1.5px `#176B52` with zero offset outline.
- **Currency Entry**: Built-in fixed `₹` prefix, right-aligned tabular numerals for immediate wholesale price reconciliation.

### Data Tables & Stock Rows
- **Headers**: Light background `#F6F8F6`, uppercase `label-sm` text `#4B5563`, 1px bottom border `#E5E9E6`.
- **Row Anatomy**: Height 52px, alternating row hover highlight `#F8FAF9`, inline SKU badge, dynamic quantity adjustment counter (+ / - stepper buttons).

### Floating Quick-Action Bar
- Fixed to bottom center viewport on mobile/tablet interfaces. Dark green backdrop (`#10513E`), 12px padding, pill-rounded container holding barcode scan shortcut, voice entry, and fast reconciliation commit.