---
name: Studio Biometric Minimal
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
  on-surface-variant: '#45474b'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777b'
  outline-variant: '#c6c6cb'
  surface-tint: '#5b5e66'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#181c22'
  on-primary-container: '#80848c'
  inverse-primary: '#c3c6cf'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fe932c'
  on-secondary-container: '#663500'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#00174b'
  on-tertiary-container: '#497cff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dfe2eb'
  primary-fixed-dim: '#c3c6cf'
  on-primary-fixed: '#181c22'
  on-primary-fixed-variant: '#43474e'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Geist
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Geist
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 42px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Geist
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Geist
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-mono-lg:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.04em
  label-mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses optical precision, institutional authority, and studio craft. Built for a technical passport and visa studio, the aesthetic bridges strict regulatory compliance with an effortless, modern concierge experience. 

The visual personality hinges on:
- **Optical Precision:** Fine technical micro-labels, hairline bounding boxes, and dimensional specs (e.g., `2x2 in`, `35x45 mm`) evoke studio calibration marks and optical viewfinders.
- **Architectural Minimalism:** Extensive white space, disciplined vertical rhythms, and deep obsidian contrasting tones mirror physical photography studios—diffused soft-box lighting, neutral cycloramas, and black-anodized camera gear.
- **Institutional Trust & Clarity:** Uncompromising legibility ensures users feel entirely confident that their biometric submissions adhere to strict international government standards.

## Colors

The palette is engineered around high-contrast studio optics: pure light, deep light-absorbing carbon, and focused utilitarian signal colors.

- **Primary (`#0D1117` - Studio Obsidian):** Used for commanding headlines, primary buttons, structural frames, and definitive biometric status cues.
- **Secondary (`#D97706` - Precision Amber):** Calibrated to mimic physical camera sensor indicators and regulatory compliance markers. Applied intentionally to critical high-conversion actions ("Book Your Photo"), alert flags, and active viewfinder guides.
- **Tertiary (`#2563EB` - Optic Cobalt):** A secondary functional accent dedicated to verified biometric checkmarks, active document links, and country requirement tags.
- **Neutral Palette:**
  - `Canvas / Off-White` (`#FAF9F5`): A refined, archival photo-paper tint for background warmth without sterile glare.
  - `Surface Studio` (`#FFFFFF`): Pure crisp white for elevated cards, document previews, and spec sheets.
  - `Hairline Slate` (`#E2E8F0`): 1px structural framing.
  - `Muted Optic` (`#64748B`): Technical annotations, subtext, and dimensional scales.

## Typography

The typographic hierarchy juxtaposes human-centered editorial clarity with camera-body technical engraving:
- **Headings & Body (Geist):** Clean, neutral, high-legibility geometric sans with tight tracking on titles for modern restraint and effortless readability across administrative instructions.
- **Micro & Specification Badges (JetBrains Mono):** Monospaced numerals and metadata for all technical specs (`35x45 MM`, `ICAO 9303 COMPLIANT`, `DENVER, CO - 39.7392° N`). Monospace guarantees tabular precision when displaying dimensions, aspect ratios, and turnaround times.

## Layout & Spacing

This layout uses a balanced 12-column grid system built on an 8px base rhythm. Generous vertical breathing room establishes an editorial, high-end studio presence.

- **Desktop (1024px+):** Max-width canvas of 1280px, 12 columns, `1.5rem` gutters, and `2rem` minimum screen margins.
- **Tablet (768px - 1023px):** 8 columns, `1.25rem` gutters, and `1.5rem` margins. Side-by-side spec layouts collapse gracefully into two-column blocks.
- **Mobile (< 768px):** 4 columns, `1rem` gutters, and `1rem` outer canvas padding. Action bars (booking and location verification) lock into a persistent bottom sheet for quick one-handed access.

## Elevation & Depth

To reflect crisp photographic paper and studio backdrops, elevation relies on clean surface layering and razor-thin borders rather than heavy blur shadows.

- **Surface Levels:** 
  - `Base Floor`: Warm paper tone (`#FAF9F5`).
  - `Card Surface`: Optical white (`#FFFFFF`) with a permanent `1px solid #E2E8F0` frame.
  - `Overlays & Viewfinders`: Deep Obsidian (`#0D1117`) with 90% opacity and fine hairline guides.
- **Ambient Diffusion:** Floating interactive elements (sticky date pickers, biometric guidelines cards) use a single ultra-subtle drop shadow: `0 4px 20px -2px rgba(13, 17, 23, 0.05)`.
- **Viewfinder Guides:** Overlays use thin crosshairs, corner tick marks, and translucent reticle lines to emphasize camera focus and precision.

## Shapes

The design system maintains a refined, low-radius architectural form factor (Level 1 - Soft, with baseline 4px radii).

- **Cards & Enclosures:** Subtle `0.25rem` (4px) to `0.5rem` (8px) corners retain an engineered, mechanical feel akin to medium-format camera bodies and film slides.
- **Micro-Badges & Dimension Labels:** Crisp `2px` corners or strict right angles with inset corner brackets.
- **Interactive Buttons:** `0.375rem` (6px) rounded corners, striking a balance between approachable ergonomics and strict architectural geometry.

## Components

### Buttons
- **Primary ("Book Your Photo"):** Obsidian background (`#0D1117`), crisp white text, `6px` radius, accompanied by subtle hover states that transition into a razor-thin border of Precision Amber (`#D97706`).
- **Urgent / Express Action:** Precision Amber background (`#D97706`), deep black text, high-contrast, bold weight for walk-in alerts or same-day passport guarantees.
- **Secondary:** Surface white (`#FFFFFF`), `1px solid #E2E8F0`, Obsidian text, shifting to neutral gray fill (`#F1F5F9`) on hover.

### Dimension & Biometric Badges
- Compact inline pills utilizing `JetBrains Mono` at `11px`.
- High-contrast regulatory styling: Black or pure white fill with a solid `1px` border, framing specifications like `2×2 INCHES` or `ICAO BIOMETRIC CHECKED`.
- Country indicator flags accompanied by official government photo specification codes.

### Cards
- Pure white surfaces framed with `1px solid #E2E8F0`.
- Padding fixed to `space-lg` (`1.5rem`).
- Header areas feature viewfinder corner notches or technical crop markings to ground the photography studio identity.

### Input Fields & Selectors
- Background: Optic white (`#FFFFFF`).
- Resting border: `1px solid #CBD5E1`.
- Focus border: `1.5px solid #0D1117` with zero blur ring for a direct, precise focus state.
- Floating helper tags display standard requirement notices (e.g., "Glasses must be removed per US State Dept rules").

### Checkboxes & Radios
- Square-profile check indicators (`4px` radius) with high-contrast Obsidian fills and sharp white vector checkmarks.
- Radio buttons feature a precision target-dot pattern mimicking camera aperture rings.

### Studio-Specific Components
- **Biometric Compliance Previewer:** A photographic card overlay featuring camera viewfinder crop marks, chin/crown alignment rules, and pass/fail indicator badges.
- **Appointment Slot Matrix:** Time blocks structured like a technical shutter-speed dial, showing immediate real-time availability in Denver (Mountain Time).