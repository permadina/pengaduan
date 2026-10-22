---
name: Civic Horizon
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f3'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e7ff'
  surface-container-highest: '#dbe2fb'
  on-surface: '#131b2e'
  on-surface-variant: '#454650'
  inverse-surface: '#283043'
  inverse-on-surface: '#eef0ff'
  outline: '#767681'
  outline-variant: '#c6c5d1'
  surface-tint: '#4d5b96'
  primary: '#00041f'
  on-primary: '#ffffff'
  primary-container: '#071952'
  on-primary-container: '#7583c1'
  inverse-primary: '#b7c4ff'
  secondary: '#006877'
  on-secondary: '#ffffff'
  secondary-container: '#8debff'
  on-secondary-container: '#006b7a'
  tertiary: '#000706'
  on-tertiary: '#ffffff'
  tertiary-container: '#002322'
  on-tertiary-container: '#219592'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#03154f'
  on-primary-fixed-variant: '#35437c'
  secondary-fixed: '#a3eeff'
  secondary-fixed-dim: '#76d4e7'
  on-secondary-fixed: '#001f25'
  on-secondary-fixed-variant: '#004e5a'
  tertiary-fixed: '#8ef3f0'
  tertiary-fixed-dim: '#71d7d3'
  on-tertiary-fixed: '#00201f'
  on-tertiary-fixed-variant: '#00504e'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dbe2fb'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  caption:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system blends **Corporate Modernism** with an inviting, civic-first ethos. Public governance platforms frequently stumble into sterile bureaucracy or archaic clutter. This system rejects both extremes by uniting the unquestioned authority of local government with the human-centered warmth of modern digital products.

### Brand Personality & Emotional Impact
- **Authoritative yet Approachable:** The deep navy foundation conveys institutional integrity and security, while warm cream surfaces dissipate citizen intimidation.
- **Transparent & Accountable:** High visual clarity, unmistakable operational statuses, and clean data hierarchies instill trust in municipal problem-solving.
- **Efficient & Decisive:** Administrative views empower civil servants with dense, actionable data arrangements, while citizen interfaces prioritize rapid, low-friction reporting.

### Design Language
The aesthetic relies on structured whitespace, subtle tonal borders, crisp typography, and restrained tactile feedback. It avoids excessive decorative clutter, allowing functional clarity and status visibility to guide every user flow.

## Colors

The color architecture enforces strict institutional legibility and semantic consistency across citizen and administrative touchpoints.

### Base Roles
- **Primary (`#071952`):** Reserved for primary actions, navigational headers, active step indicators, and top-tier branding elements. Expresses civic gravitas.
- **Secondary (`#088395`):** Serves operational controls, secondary interactive accents, and administrative filter bars.
- **Tertiary / Interactive Accent (`#35A29F`):** Used sparingly for interactive highlights, active tabs, progress bars, and focus outlines.
- **Neutral Core (`#0B1325`):** Primary text and icon color, calibrated for maximum contrast against light surfaces.
- **Neutral Secondary (`#4A5568`):** Applied to metadata, captions, label descriptions, and helper strings.
- **Surface Canvas (`#FEF3E2`):** Warm cream canvas that reduces harsh eye strain and softens the formal tone of government interaction.
- **Surface Elevation (`#FFFFFF`):** High-priority card containers, table backgrounds, and modal dialog sheets.

### Status & Feedback Semantics
Status tokens remain consistent across badges, timeline nodes, and alerts:
- **Pending (`#D97706` / BG `#FEF3C7`):** Citizen report submitted, awaiting triage.
- **In Progress (`#088395` / BG `#E0F2FE`):** Assigned to relevant department or field officer.
- **Resolved (`#059669` / BG `#D1FAE5`):** Verified completion with public evidence attachment.
- **Rejected (`#DC2626` / BG `#FEE2E2`):** Invalid report, spam, or out-of-jurisdiction dismissal.

## Typography

The typographic hierarchy balances display authority with dense data utility.

### Type Pairings
- **Headings (Plus Jakarta Sans):** Crafted with balanced geometric proportions and high x-height, providing institutional stature without feeling distant or archaic. Used across page titles, stat callouts, modal banners, and section markers.
- **Body & Data (Inter):** Neutral, robust, and precision-engineered for screen legibility. It anchors high-density citizen reports, complex complaint timelines, form inputs, and administrative tabular records without visual fatigue.

### Scaling and Implementation
- Responsive headline sizes automatically degrade to mobile-safe scales below `768px` to prevent awkward word wraps in administrative banners.
- Numbers in tabular contexts, tracking codes, and dates must utilize tabular figures (`tnum`) for exact vertical alignment across rows.

## Layout & Spacing

The structural layout relies on an 8pt spatial grid configured as a 12-column adaptive system.

### Grid & Breakpoints
- **Desktop (1200px+):** 12-column grid, `margin: 2rem`, `gutter: 1.5rem`. Container max-width capped at `1360px` for optimal reading spans, expanding to full-width dynamic layouts strictly within the admin management portal.
- **Tablet (768px - 1199px):** 8-column layout, `margin: 1.5rem`, `gutter: 1rem`. Multi-step citizen reporting forms compress into a single vertical column with sticky progression indicators.
- **Mobile (&lt; 768px):** 4-column layout, `margin: 1rem`, `gutter: 1rem`. Administrative tables convert to card-based complaint streams with collapsible detail views.

### Vertical Rhythm
Section spacing retains consistent intervals: `space-xl` separates high-level modules (e.g., metric cards from complaint feeds), `space-md` organizes intra-component flows (e.g., label-to-input, title-to-description), and `space-xs` groups micro-indicators (e.g., icons next to timestamp labels).

## Elevation & Depth

To match modern governance platforms, depth is generated via low-opacity, atmospheric drop shadows grounded by ultra-fine hairline boundaries.

### Layer Architecture
- **Flat Ground (`#FEF3E2`):** Base canvas level. Houses navigation chrome and structural gutters.
- **Level 1 (`#FFFFFF` + Hairline):** Core content cards, KPI summary containers, and table sheets. Elevated with `0px 1px 3px rgba(7, 25, 82, 0.05)` and framed by a crisp border `1px solid rgba(7, 25, 82, 0.08)`.
- **Level 2 (Floating & Interactive):** Dropdown menus, quick-action citizen drawers, and active hover states. Rendered with `0px 4px 12px rgba(7, 25, 82, 0.08)` and border `1px solid rgba(7, 25, 82, 0.12)`.
- **Level 3 (Modal & Critical Overlays):** Citizen confirmation dialogs, admin dispatch modals, and large evidence lightboxes. Rendered with `0px 16px 32px rgba(7, 25, 82, 0.16)` over a scrim backdrop `rgba(11, 19, 37, 0.6)` with a `4px` blur.

## Shapes

The geometric framework balances friendly civic accessibility with strict administrative discipline.

### Radius Assignments
- **Base Components (`rounded` / 0.5rem):** Form inputs, dropdown selectors, alert banners, and table action triggers.
- **Structural Containers (`rounded-lg` / 1rem):** Dashboard summary KPI cards, report cards, modal shells, and multi-file upload zones.
- **Full Radius (`rounded-full` / Pill):** Status indicators, report category tags, avatar clusters, and quick filter chips.

## Components

### Buttons
- **Primary:** Solid `#071952` background, `#FFFFFF` text, `rounded-lg` (8px), padding `10px 20px`. Subtle hover elevation shift to `#088395` with `transform: translateY(-1px)` and a transition duration of `150ms ease`.
- **Secondary:** Transparent fill, `1.5px solid #071952`, text `#071952`. Hover activates background `rgba(7, 25, 82, 0.04)`.
- **Destructive:** Solid `#DC2626` background, `#FFFFFF` text, utilized for dispatch rejection or report cancellation modals.

### Status Badges
- Strict pill architecture (`rounded-full`, padding `4px 12px`, typography `label-sm`).
- **Menunggu (Pending):** Text `#92400E`, background `#FEF3C7`, border `1px solid #FDE68A`.
- **Diproses (In Progress):** Text `#075985`, background `#E0F2FE`, border `1px solid #BAE6FD`.
- **Selesai (Resolved):** Text `#065F46`, background `#D1FAE5`, border `1px solid #A7F3D0`.
- **Ditolak (Rejected):** Text `#991B1B`, background `#FEE2E2`, border `1px solid #FECACA`.

### Administrative Data Tables
- White card canvas framed by `1px solid rgba(7, 25, 82, 0.08)`.
- **Header:** Background `#F8FAFC`, uppercase `caption` typography, text `#4A5568`, padding `12px 16px`.
- **Rows:** Alternating subtle zebra striping (odd rows white, even rows `#FCFDFE`), padding `14px 16px`, bottom border `1px solid rgba(7, 25, 82, 0.04)`. Hover initiates background `rgba(8, 131, 149, 0.03)`.
- **Tracking ID:** Formatted with `Inter Medium` using tabular numerals, color `#088395`.

### Input Fields & Forms
- Input canvas `#FFFFFF`, border `1.5px solid #CBD5E1`, border-radius `0.5rem`.
- Labels positioned above using `label-md` in `#0B1325`, accompanied by mandatory asterisks in `#DC2626`.
- **Focus State:** Border changes to `#35A29F`, backed by an outer ring `0 0 0 3px rgba(53, 162, 159, 0.2)`. Transition duration `120ms`.
- Helper captions in `body-sm` (`#4A5568`) placed `4px` beneath input boxes.

### KPI Summary Cards
- White background, `rounded-lg`, internal padding `20px`.
- Layout: Top row showcases the category title (`label-md`, `#4A5568`) paired with an icon enclosed in a `36x36px` tinted circular container (`10%` opacity of theme color).
- Bottom row displays metric figures (`headline-lg`, `#071952`) flanked by a delta tag (e.g., `+12% minggu ini`).

### Citizen Complaint Feed Cards
- Composed on white surface with a distinct left-edge vertical status bar (`4px` width matching semantic status color).
- Houses complainant anonymization toggle, ticket hash code, category tag chip, submission timestamp, and expandable multi-attachment gallery preview.