---
name: Clinical Clarity
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
  on-surface-variant: '#3d4946'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6d7a76'
  outline-variant: '#bdc9c4'
  surface-tint: '#006b5b'
  primary: '#006859'
  on-primary: '#ffffff'
  primary-container: '#008471'
  on-primary-container: '#f4fffa'
  inverse-primary: '#71d8c2'
  secondary: '#49607c'
  on-secondary: '#ffffff'
  secondary-container: '#c7dfff'
  on-secondary-container: '#4b637e'
  tertiary: '#006857'
  on-tertiary: '#ffffff'
  tertiary-container: '#00846e'
  on-tertiary-container: '#f4fffa'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#8ef5de'
  primary-fixed-dim: '#71d8c2'
  on-primary-fixed: '#00201a'
  on-primary-fixed-variant: '#005144'
  secondary-fixed: '#d1e4ff'
  secondary-fixed-dim: '#b0c9e8'
  on-secondary-fixed: '#011d35'
  on-secondary-fixed-variant: '#314863'
  tertiary-fixed: '#7cf8da'
  tertiary-fixed-dim: '#5ddbbe'
  on-tertiary-fixed: '#00201a'
  on-tertiary-fixed-variant: '#005143'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-tablet: 1.5rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system establishes an empathetic, highly dependable digital healthcare environment designed for mobile patient journeys. The visual aesthetic fuses Scandinavian clinical minimalism with modern biometric warmth: precision without sterility, empathy without infantilization. 

The experience targets diverse patient cohorts and busy healthcare providers. Interface patterns must instantly reduce stress, communicate critical diagnostic or scheduling data without ambiguity, and project institutional authority alongside personal attentiveness.

Key stylistic principles:
- **Visual Calmness**: Soft, oxygenated background surfaces prevent cognitive fatigue and ease clinical anxiety.
- **Immediate Legibility**: Elevated contrast and distinct optical hierarchies prioritize actionable health metrics, appointment slots, and prescription instructions.
- **Physical Softness**: High corner radiuses, gentle depth separation, and generous touch footprints replace intimidating medical rigidity with friendly, accessible interactions.

## Colors

The palette leverages restorative marine and teal tones supported by deep navigational blues and crisp slate neutrals.

### Palette Architecture
- **Primary (`#008774`) & Primary Accent (`#00A389`)**: Signifies restorative care and clinical expertise. Used for primary actions, active navigational states, and high-priority interactive widgets.
- **Secondary / Deep Navy (`#0F2942`)**: Imparts structural weight, confidence, and authority. Anchors primary typography, critical headings, and top-level navigation headers.
- **Surface Canvas (`#F4FBF9`)**: A soft, mint-tinted atmosphere that replaces harsh sterile whites while avoiding muddy grays.
- **Elevated Surfaces (`#FFFFFF`)**: Pure white reserved for cards, bottom sheets, inputs, and modular overlays to establish clear separation from the background canvas.
- **Neutrals**:
  - `Text Primary`: `#1E293B` (Deep slate for body text, guaranteeing AAA compliance against white).
  - `Text Secondary / Neutral`: `#64748B` (Muted slate for labels, helper strings, and inactive icons).
  - `Border / Divider`: `#E2E8F0` (Hairline structural boundary).
- **Clinical Functional Tokens**:
  - `Status Confirmed / Normal`: `#059669` (Emerald) with `#ECFDF5` background.
  - `Status Pending / Caution`: `#D97706` (Amber) with `#FFFBEB` background.
  - `Status Critical / Cancelled`: `#E11D48` (Rose) with `#FFF1F2` background.
  - `Information / Lab Alert`: `#0284C7` (Sky) with `#F0F9FF` background.

## Typography

Plus Jakarta Sans provides high legibility in mobile health contexts. Its open aperture design, generous x-height, and soft geometric curves balance technological precision with human approachability.

### Rules of Engagement
- **Tabular Figures**: Always enable `tnum` (tabular numbers) in medical charts, dosage schedules, biometric reads, and appointment times to avoid layout jitter during real-time updates.
- **Headline Scannability**: Use `headline-md` and `headline-sm` in Secondary (`#0F2942`) for section headers to quickly ground patients scanning through dense medical records.
- **Secondary Tone Restraint**: Restrict `label-sm` strictly to tags, biometric category badges, and contextual metadata. Do not set instructional or legal microcopy below `12px` (`body-sm`).

## Layout & Spacing

The layout is built around a mobile-first, single-column fluid card hierarchy anchored by safe touch margins and structural vertical stacks.

### Responsive Breakpoints & Margins
- **Mobile (< 640px)**: 4-column layout; screen margins fixed at `1rem` (16px); inter-card gap set to `1rem`. Critical interactive zones must respect a 48px minimum vertical touch dimension.
- **Tablet (640px – 1024px)**: 8-column layout; screen margins expand to `2rem`; gutters widen to `1.5rem`. Dashboard panels transition into split clinical summaries (e.g., patient vital card on the left, appointment chronology on the right).
- **Desktop (> 1024px)**: 12-column layout capped at an inner maximum container of `1200px` centered, utilizing `3rem` margins to ensure doctor portal readability.

### Spatial Rhythm
- Apply `space-xs` (4px) exclusively for icon-to-text labels and tag insets.
- Apply `space-sm` (8px) for tightly coupled form elements (e.g., input label to field box).
- Apply `space-md` (16px) for interior card padding, row separations, and button content insets.
- Apply `space-lg` (24px) for distinct content grouping within the same functional view.
- Apply `space-xl` (32px) for primary layout section boundaries.

## Elevation & Depth

To prevent visual clutter, this design system minimizes heavy dropshadows in favor of surface layering, crisp 1px borders, and soft ambient light casting.

### Layering Hierarchy
1. **Canvas Layer (`#F4FBF9`)**: Base background that sits beneath all interface modules.
2. **Resting Cards & Modules (`#FFFFFF`)**: Defined by a hairline border (`1px solid #E2E8F0`) combined with an ambient, colored tint shadow: `0 4px 20px -2px rgba(15, 41, 66, 0.04)`. This creates a tactile, floating paper aesthetic without dark, muddy edges.
3. **Interactive & Hover/Press Cards**: Slightly lifted using `0 8px 24px -4px rgba(0, 135, 116, 0.08)` and border tint shift to `#CBD5E1`.
4. **Floating Action Elements & Navigation Bars**: Uses `0 12px 32px -4px rgba(15, 41, 66, 0.10)` combined with subtle backdrop blur (`backdrop-filter: blur(12px)`) when semi-transparent glass treatments overlay patient schedules.
5. **Modals & Critical Action Sheets**: Dim background with an ambient scrim of `#0F2942` at 40% opacity; sheet body raised with `0 20px 40px -8px rgba(15, 41, 66, 0.20)`.

## Shapes

The shape system leverages organic, friendly geometry to soften the clinical context while keeping structure orderly.

- **Primary Cards & Modals**: Implemented with `rounded-2xl` (1rem / 16px to 1.5rem / 24px on large surfaces) to yield friendly, cradled surfaces that feel approachable on handheld glass devices.
- **Controls, Buttons & Form Inputs**: Standardized on `rounded-xl` (0.75rem / 12px) to ensure touch targets feel distinct, bounded, and ergonomic.
- **Pill Elements (Status Badges, Category Chips, Segmented Filter Tabs)**: Utilize fully rounded, pill-shaped contours (`rounded-full` / 9999px) to clearly differentiate metadata and filter chips from clickable operational cards.

## Components

### Buttons
- **Primary Button**: Background `#008774`, foreground `#FFFFFF`, border-radius `12px` (`rounded-xl`), minimum height `48px`. Active state transitions to `#00A389`. Text set to `label-lg`.
- **Secondary Button**: Background `#FFFFFF`, foreground `#0F2942`, border `1.5px solid #E2E8F0`. On press, background becomes `#F4FBF9`.
- **Destructive Button**: Background `#FFF1F2`, text `#E11D48`, border `1px solid rgba(225, 29, 72, 0.2)`.

### Form Inputs
- **Base Input**: Height `52px`, background `#FFFFFF`, border `1px solid #E2E8F0`, corner radius `12px`. Text style `body-md` in `#1E293B`.
- **Focused State**: Border shifts to `#008774` with an ambient glow ring: `0 0 0 3px rgba(0, 135, 116, 0.15)`.
- **Input Labels**: Set in `label-md` (`#0F2942`) positioned `8px` above the field container with optional helper text in `#64748B`.

### Medical Status Chips
- Pill geometry (`rounded-full`), padding `4px 12px`, text style `label-sm`.
- **Confirmed**: Text `#059669`, background `#ECFDF5`, dot indicator `#10B981`.
- **Pending**: Text `#D97706`, background `#FFFBEB`, dot indicator `#F59E0B`.
- **Cancelled**: Text `#E11D48`, background `#FFF1F2`, dot indicator `#F43F5E`.

### Cards & Appointment Modules
- Background `#FFFFFF`, corner radius `16px` (`rounded-2xl`), padding `16px`, structural border `1px solid #E2E8F0`, soft resting shadow.
- Visual hierarchy within appointment cards:
  - Top row: Doctor name (`headline-sm`, `#0F2942`) and specialty badge.
  - Middle: Date and time ribbon with soft `#F4FBF9` pill container featuring `#008774` calendar icon.
  - Bottom row: Action buttons (Reschedule/Confirm) separated by top divider or unified button group.

### Checkboxes & Radios
- Size `22px x 22px`. Inactive has a 1.5px solid `#CBD5E1` border.
- Selected state fills with `#008774`, displaying a pure white checkmark or inner dot. Transitions should execute with a brisk 150ms ease-out curve.

### Medical Record List Items
- Divided by hairline borders (`#E2E8F0`); row height `64px`.
- Left-aligned leading icon within a `40px` circular container tinted at 10% opacity of the associated status color.
- Trailing accessory indicator (chevron) in `#64748B`.