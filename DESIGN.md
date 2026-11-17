---
name: Precision Engineering & Marketplace Trust
colors:
  surface: '#f9f9ff'
  surface-dim: '#d8d9e4'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3fe'
  surface-container: '#ecedf8'
  surface-container-high: '#e6e7f2'
  surface-container-highest: '#e1e2ec'
  on-surface: '#191b23'
  on-surface-variant: '#434656'
  inverse-surface: '#2d3038'
  inverse-on-surface: '#eff0fb'
  outline: '#737688'
  outline-variant: '#c3c5d9'
  surface-tint: '#004af1'
  primary: '#003dcb'
  on-primary: '#ffffff'
  primary-container: '#0f52ff'
  on-primary-container: '#e1e4ff'
  inverse-primary: '#b8c4ff'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#3c4e74'
  on-tertiary: '#ffffff'
  tertiary-container: '#54668e'
  on-tertiary-container: '#dce5ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#0037b9'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#b4c6f3'
  on-tertiary-fixed: '#051a3e'
  on-tertiary-fixed-variant: '#35466c'
  background: '#f9f9ff'
  on-background: '#191b23'
  surface-variant: '#e1e2ec'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-badge:
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
    letterSpacing: 0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 2rem
  margin-mobile: 1.25rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system is tailored for an elite digital services platform and high-end web developer portfolio. The brand persona blends the meticulous reliability of an enterprise services marketplace with the sharp, innovative edge of a premier software engineer. It targets engineering directors, product founders, and enterprise clients seeking immediate technical credibility, transparency, and execution speed.

The visual style is **Contemporary Technical Precision**—a synthesis of high-contrast modernism and functional utility:
- **Atmosphere**: Confident, structural, and meticulously curated.
- **Hierarchy**: Content-first framing with generous negative space, crisp micro-borders, and high-legibility typographic hierarchies.
- **Emotional Target**: Immediate authority, engineering rigor, operational trust, and frictionless navigation.

## Colors

The palette establishes an immediate sensation of reliability, clarity, and precision:
- **Primary (`#0F52FF`)**: An electric cobalt blue driving interactive affordances, core CTA anchors, active link states, and verified metric highlights.
- **Secondary (`#10B981`)**: An emerald green signaling deployment health, client satisfaction, operational uptime, project success indicators, and live availability status.
- **Tertiary (`#091E42`)**: Deep architectural navy serving as anchor surface tones, strong headline ink, and deep container backdrops.
- **Neutral (`#0A0D14`)**: A high-density carbon black governing primary typography, bordered structures, and dark-theme baseplates.

### Palette Application
- **Surfaces**: Canvas defaults to an ultra-clean off-white `#F9FAFB` in light mode, with `#FFFFFF` reserved for elevated cards and input fields.
- **Borders & Dividers**: Subdued slate-neutral lines (`#E4E7EC` light, `#1F2430` dark) ensure layout definition without visual noise.
- **Feedback & States**: Neutral cool slates (`#475467`) support secondary body copy and meta-information.

## Typography

The type system pairs **Inter** for all display, structural, and narrative needs with **JetBrains Mono** for technical labels, syntax tags, architectural specs, and metrics.

- **Inter**: Provides neutral, geometric clarity with fine-tuned tabular features (`cv02`, `cv03`, `cv04`, `cv11`). Tighter tracking across display tiers delivers a cohesive, editorial layout.
- **JetBrains Mono**: Infuses the interface with an authentic engineering DNA. Applied strictly to technology stack badges, SLA readouts, version numbers, and inline command tokens.

## Layout & Spacing

The layout is built upon a rigid, fluid 12-column grid anchored by an 8pt architectural rhythm:
- **Desktop (>= 1280px)**: 12 columns, max content container width of 1240px, 32px gutters, and 48px outer margins.
- **Tablet (768px - 1279px)**: 8 columns, 24px gutters, and 32px outer canvas margins. Elements reflow to 4-column spans for 2-up service matrices.
- **Mobile (< 768px)**: 4 columns, 16px gutters, and 20px outer canvas margins. Complex tables and tech stacks convert into vertically stacked modular cards or horizontal scroll ribbons.

Content groupings strictly use internal modular paddings (`space-md` for standard density, `space-lg` to `space-xl` for project showcases) to preserve breathing room and visual autonomy.

## Elevation & Depth

Visual hierarchy is communicated via **layered crispness**: combining razor-sharp micro-borders with low-opacity, wide-radius ambient shadows.

- **Border Strategy**: Surfaces rely on a 1px border rendered in `rgba(15, 23, 42, 0.08)` (light mode) or `rgba(255, 255, 255, 0.1)` (dark mode) to enforce clean geometric boundaries without heavy outlines.
- **Ambient Shadow Levels**:
  - *Level 0 (Flat)*: Flat flush panels with border-only separation (tables, sub-containers, inline filters).
  - *Level 1 (Resting Cards)*: `0px 2px 4px rgba(10, 13, 20, 0.04), 0px 6px 16px rgba(10, 13, 20, 0.03)` with a 1px structural border.
  - *Level 2 (Interactive Hover / Floating Nav)*: `0px 4px 8px rgba(10, 13, 20, 0.04), 0px 16px 32px rgba(15, 82, 255, 0.08)`. A faint primary blue tint bleeds into the ambient glow during hover transitions.
  - *Level 3 (Modals / Overlays)*: `0px 24px 48px -12px rgba(9, 30, 66, 0.18)` over a blurred backdrop (`backdrop-filter: blur(8px); background: rgba(10, 13, 20, 0.4)`).

## Shapes

The shape system adopts a **Soft Precision (`1`)** geometry. 
- Elements maintain clean 4px (`rounded`) to 8px (`rounded-lg`) corners, evoking modern enterprise software rather than consumer-toy plasticity.
- Interactive tags, pills, and status chips apply a deliberate `rounded-full` exception to clearly differentiate contextual metadata from clickable operational modules and functional card enclosures.

## Components

### Buttons
- **Primary**: Solid Cobalt Blue (`#0F52FF`) fill, pure white text, 8px border-radius, `space-sm` vertical by `space-lg` horizontal padding. Hover state shifts to `#0A42D1` with a `Level 2` elevated blue-tinted drop glow.
- **Secondary**: Clear background, 1px solid border (`#D0D5DD`), neutral text (`#0A0D14`). Hover state applies `#F4F5F7` background fill.
- **Success / Booking Action**: Emerald Green (`#10B981`) solid fill with white text, paired with a subtle ping or dot pulse for live project availability.

### Tag Badges & Service Chips
- **Tech Stack Tags**: Rendered with `label-code` in JetBrains Mono. Translucent slate background (`rgba(15, 23, 42, 0.04)`), 1px solid border (`rgba(15, 23, 42, 0.08)`), and slate-gray ink.
- **Availability / Verification Badges**: Full pill shape (`rounded-full`) containing an active emerald pulsing dot (`#10B981`), `label-badge` font, light green background (`#ECFDF5`), and emerald text (`#065F46`).

### Cards & Service Offerings
- Clean white backdrop (`#FFFFFF`), 8px border-radius, 1px border (`#E4E7EC`), resting at `Level 1` elevation.
- Includes a dedicated header section with categorical tags, monospace pricing or delivery turnaround metrics, an integrated bulleted scope list, and a direct engagement action trigger.
- Hover states initiate a subtle vertical translation (`-2px`) and upgrade shadow depth to `Level 2`.

### Form Fields & Inputs
- Height of 44px with 8px radius. Neutral light fill (`#FFFFFF`), bordered by `#D0D5DD`.
- Active focus displays a dual-layer treatment: 1px active blue border (`#0F52FF`) coupled with a 3px outer glow ring (`rgba(15, 82, 255, 0.15)`).

### Selection Controls (Checkboxes & Radios)
- Precise 18px dimensions with 4px corner radius for checkboxes, circular for radios.
- Unselected state uses a 1.5px slate border (`#D0D5DD`). Checked state shifts to solid `#0F52FF` with a crisp white internal check or center radio pip.

### Interactive Code / Metric Snippets
- Dedicated container using high-contrast dark navy `#091E42` surfaces, 8px radius, populated with JetBrains Mono syntax tags, micro-copy buttons ("Copy Config"), and live status telemetry indicators.