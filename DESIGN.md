---
name: Luminescent Identity
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#d0bcff'
  on-secondary: '#3c0091'
  secondary-container: '#571bc1'
  on-secondary-container: '#c4abff'
  tertiary: '#7bd0ff'
  on-tertiary: '#00354a'
  tertiary-container: '#009bd1'
  on-tertiary-container: '#002d40'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '700'
    lineHeight: 4.25rem
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: 2.75rem
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Inter
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: 1.25rem
    letterSpacing: 0em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 1rem
    fontWeight: '500'
    lineHeight: 1.5rem
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.04em
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

This design system defines a high-assurance, premium authentication interface. It caters to modern developers, fintech users, and enterprise operators who expect rigorous security wrapped in effortless aesthetics. The atmosphere balances technical precision with high-end digital craftsmanship, cultivating trust, composure, and swift focus.

The visual direction merges **Minimalism** with restrained **Glassmorphism**:
- **Monolithic canvas**: Deep slate backgrounds eliminate eye strain and ground visual hierarchy.
- **Atmospheric luminosity**: Targeted electric indigo and violet accents emit directional light through frosted glassy layers, highlighting key focal points without gratuitous decoration.
- **Clarity over ornament**: Every pixel, divider, and token conveys functional clarity, reducing friction during critical verification and sign-in paths.

## Colors

The palette is engineered for high-contrast accessibility on a dark bedrock, satisfying WCAG AAA standards for all body copy and primary interaction points:

- **Primary (`#6366F1` - Electric Indigo)**: Anchors high-priority actions, focus rings, and primary auth submission states.
- **Secondary (`#8B5CF6` - Vivid Violet)**: Provides spectral depth via interactive gradients, micro-glows, badges, and MFA verification accents.
- **Tertiary (`#38BDF8` - Electric Cyan)**: Used surgically for status notifications, system health markers, and password strength indicators.
- **Neutral (`#0F172A` - Midnight Slate)**: Establishes deep surface hierarchy. Supporting neutrals scale from pure charcoal-slate substrates (`#0B0F19`) to high-contrast foreground whites (`#F8FAFC`) and muted labels (`#94A3B8`).

## Typography

The typographic hierarchy implements three distinct roles:
1. **Plus Jakarta Sans** for prominent titles, greetings, and structural headlines—providing geometric authority with subtle modern warmth.
2. **Inter** for descriptions, microcopy, error validation messages, and inline forms—ensuring crisp legibility across high-DPI and standard screens.
3. **JetBrains Mono** strictly reserved for OTP codes, recovery keys, passkey hashes, and terminal-style session metadata.

Keep letter spacing tight (`-0.025em` to `-0.015em`) on large display tiers to maintain density, shifting to tabular spacing on code and security tokens for immediate scanning.

## Layout & Spacing

The interface employs a centered single-axis layout for primary auth canvases, shifting to a dual-pane presentation on desktop:

- **Desktop (1024px+)**: A split presentation consisting of an atmospheric contextual brand panel (left) and a centered verification module (right) locked to a maximum width of `460px`.
- **Tablet (768px - 1023px)**: Single container centered with `margin: 2rem`, card width bounded at `440px`.
- **Mobile (320px - 767px)**: Fluid full-width container utilizing `margin-sm: 1rem` and compact vertical spacing (`space-lg`) to prevent essential action triggers from falling below the fold.

Vertical rhythm adheres strictly to an 8px baseline rhythm (`space-xs` = 4px, `space-sm` = 8px, `space-md` = 16px, `space-lg` = 24px, `space-xl` = 40px). Form clusters maintain `space-md` between inputs and `space-xl` prior to primary commit actions.

## Elevation & Depth

Visual depth is achieved through translucent surfaces, controlled light diffraction, and micro-borders rather than standard muddy drop shadows:

- **Base Canvas**: Solid obsidian slate (`#0B0F19`) layered with an ambient radial gradient in the top quadrant (`rgba(99, 102, 241, 0.12)` blurred at `120px`).
- **Glassmorphic Cards**: Surface fills render as `rgba(15, 23, 42, 0.65)` layered over a `16px` backdrop filter blur. Cards receive an ultra-fine border of `1px solid rgba(255, 255, 255, 0.08)`.
- **Elevated Modals & Popovers**: Background `rgba(30, 41, 59, 0.85)` with a `24px` backdrop blur, a light-facing inner highlight (`inset 0 1px 0 0 rgba(255, 255, 255, 0.15)`), and a directional shadow: `0 20px 40px -15px rgba(2, 6, 23, 0.7)`.
- **Active Focus**: Interactive elements emit an electric glow via `0 0 0 3px rgba(99, 102, 241, 0.35)` paired with a `1px` primary border.

## Shapes

The design system standardizes on **Rounded (Level 2)** geometry:
- Standard inputs, buttons, and badges utilize `0.5rem` (8px).
- Authentication card shells and nested boundary dialogs utilize `1rem` (16px).
- Modal backdrops, notifications, and floating banners employ `1.5rem` (24px).
- Biometric triggers and circular avatars preserve standard pill/circular configurations.

This curvature balances modern softness with structural precision, preserving straight internal grid lines across complex verification forms.

## Components

### Buttons
- **Primary Auth Button**: Filled with an indigo-to-violet linear gradient (`135deg, #6366F1, #8B5CF6`). Height: `48px`, font weight: `600`, label centered. Pressed states reduce brightness to `92%` and translate down `1px`.
- **Secondary / SSO Buttons**: Glass surface (`rgba(255, 255, 255, 0.03)`), `1px` border of `rgba(255, 255, 255, 0.1)`. Hover state activates `rgba(255, 255, 255, 0.07)` and border transitions to `rgba(99, 102, 241, 0.4)`.

### Input Fields
- **Container**: `48px` height with `0.5rem` radius. Surface uses `rgba(15, 23, 42, 0.6)`.
- **Borders**: Inactive state is `1px solid rgba(255, 255, 255, 0.1)`. Focus state shifts to `#6366F1` with an outer glow of `0 0 0 3px rgba(99, 102, 241, 0.25)`.
- **Typography**: Entered text renders at `#F8FAFC`, placeholder text in `#64748B`.

### Segmented OTP / Passcode Inputs
- Six discrete square cells (`48px x 56px`), centered text set in `JetBrains Mono` at `1.25rem`.
- Inactive cells carry standard input treatment; current focused cell gains violet halo and active cursor indicator.

### Checkboxes & Switches
- **Checkboxes**: `18px x 18px` box with `0.25rem` radius. Unchecked has a `1px solid rgba(255, 255, 255, 0.2)` border. Checked state transitions to full `#6366F1` fill with an animated white vector checkmark.
- **Labels**: Set in `Inter`, `body-sm`, color `#CBD5E1`.

### Chips & Security Badges
- Ultra-compact pills (`height: 24px`) displaying protocol statuses (e.g., "WebAuthn Enabled", "Passkey Ready"). Background `rgba(99, 102, 241, 0.12)`, text `#A5B4FC`, border `1px solid rgba(99, 102, 241, 0.3)`.

### Cards & Panels
- Structured with `space-xl` padding on desktop and `space-lg` on mobile. Surfaces leverage subtle frosted glass styling with hairline borders, strictly segregating auth header copy, interactive form groups, and footnote terms.