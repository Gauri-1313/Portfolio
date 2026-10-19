---
name: Kinetic Obsidian
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353943'
  surface-container-lowest: '#0a0e17'
  surface-container-low: '#181b25'
  surface-container: '#1c1f29'
  surface-container-high: '#262a34'
  surface-container-highest: '#31353f'
  on-surface: '#dfe2ef'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dfe2ef'
  inverse-on-surface: '#2c303a'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#b8c4ff'
  on-secondary: '#1a2b6a'
  secondary-container: '#334282'
  on-secondary-container: '#a2b1f9'
  tertiary: '#bdc2ff'
  on-tertiary: '#131e8c'
  tertiary-container: '#7c87f3'
  on-tertiary-container: '#081486'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#dde1ff'
  secondary-fixed-dim: '#b8c4ff'
  on-secondary-fixed: '#001354'
  on-secondary-fixed-variant: '#334282'
  tertiary-fixed: '#e0e0ff'
  tertiary-fixed-dim: '#bdc2ff'
  on-tertiary-fixed: '#000767'
  on-tertiary-fixed-variant: '#2f3aa3'
  background: '#0f131c'
  on-background: '#dfe2ef'
  surface-variant: '#31353f'
typography:
  display-hero:
    fontFamily: Hanken Grotesk
    fontSize: 3.5rem
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 2rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 1.125rem
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Geist
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0.01em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.08em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-desktop: 3.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system expresses high-assurance digital security wrapped in architectural luxury. Tailored for enterprise developers, fintech platforms, and elite SaaS ecosystems, the aesthetic communicates cryptographic precision, quiet confidence, and zero-friction interaction.

The style fuses **Modern Minimalist Utility** with **Subtle Frosted Glass Elements**. 

- **Voice & Tone:** Discreet, deliberate, uncompromisingly stable. Copy is sparse, instructional, and devoid of colloquialisms.
- **Visual Personality:** Deep monolithic slate foundations paired with sharp light-refracting boundaries and an electric indigo focal point.
- **Interaction Ethos:** Immediate responsiveness, micro-transitions governed by sharp cubic-beziers, and tactical visual feedback that transforms rote identity verification into an executive tactile experience.

## Colors

The palette leverages high-order contrast between an abyssal dark slate architecture and a luminous electric indigo engine.

- **Primary (`#6366F1`):** The operational core. Used strictly for prime calls-to-action, active focus indicators, and critical progression states.
- **Secondary (`#A5B4FC`):** Soft luminous lilac. Reserved for subtle hover glows, secondary interactive icons, and low-priority active indicators.
- **Tertiary (`#818CF8`):** Mid-tone violet. Serves as a transitional gradient step and active border accent.
- **Neutral (`#090D16`):** The foundational obsidian canvas.

### Atmospheric Tones
- **Canvas Base:** `#090D16` (Deep Obsidian Slate)
- **Surface Elevation 1 (Split Panel / Cards):** `#0E131F`
- **Surface Elevation 2 (Input Wells / Inner Containers):** `#161C2E`
- **Surface Elevation 3 (Floating Menus / Modals):** `#1E263D`
- **Subtle Rim Border:** `rgba(255, 255, 255, 0.08)`
- **Active Focus Rim:** `rgba(99, 102, 241, 0.45)`

### Foreground Scale
- **Text Primary (Warm Platinum):** `#F8FAFC`
- **Text Secondary (Slate Fog):** `#94A3B8`
- **Text Muted (Charcoal Haze):** `#64748B`

### State Semantics
- **Success:** `#10B981` (Emerald verification)
- **Destructive/Error:** `#F43F5E` (Precise crimson flag)
- **Warning:** `#F59E0B` (Amber session expiry warning)

## Typography

The typographic hierarchy couples the clean structural geometry of **Hanken Grotesk** with the razor-sharp legibility of **Geist**, anchored by **JetBrains Mono** for low-level metadata, tokens, and verification codes.

- **Headlines:** Use `Hanken Grotesk` with tight, intentional tracking (`-0.02em` to `-0.03em`) to deliver modern authority.
- **Body & Inputs:** Handled entirely by `Geist` to maintain extreme legibility even under low illumination.
- **Labels, Tokens, and Badges:** Standardized with `JetBrains Mono` in uppercase tracking (`0.08em`) to enforce technical precision and clarity across MFA tokens, IP addresses, and state badges.

## Layout & Spacing

The layout is engineered around an asymmetric **50/50 Desktop Split-Screen Canvas**.

### Split Layout Archetype
- **Left Architecture (The Brand Anchor):** Displays context, brand visuals, security status animations, and ambient glow fields. Fixed to viewport height, non-scrolling.
- **Right Architecture (The Interaction Engine):** A clean vertical-stacking viewport holding authentication forms, SSO bridges, and recovery workflows. Constrained to a max content width of `440px` centered within its 50vw panel.

### Responsive Reflow Rules
- **Desktop (1024px+):** Strict 50/50 split canvas. Left panel retains visual dominance; right panel isolates form components with `margin-desktop` gutters.
- **Tablet (768px - 1023px):** Collapses into a centered single-column card layout (`600px` max-width). The brand anchor simplifies into a minimal sticky header band.
- **Mobile (< 768px):** Single-column edge-to-edge flow using `margin` of `1.25rem`. The branding pane compresses to an inline brandmark and dynamic security badge at top.

## Elevation & Depth

Visual hierarchy does not use high-opacity Drop Shadows. It utilizes stacked surface luminance, frosted glass overlays, and delicate perimeter backlights.

### Surface System
- **Layer 0 (Canvas):** Solid `#090D16`.
- **Layer 1 (Card Panes & Glass Plates):** Background `rgba(14, 19, 31, 0.75)` overlaid with a `backdrop-filter: blur(16px)` and perimeter border `1px solid rgba(255, 255, 255, 0.08)`.
- **Layer 2 (Inputs & Well Panes):** Background `#161C2E`, inset with a `box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.4)`.
- **Layer 3 (Modals & MFA Dropdowns):** Background `rgba(30, 38, 61, 0.95)`, `backdrop-filter: blur(24px)`, edged with `1px solid rgba(255, 255, 255, 0.12)`.

### Lighting & Ambient Glows
- **Focused State Glow:** Interactive elements focus-lit with `0 0 0 1px #6366F1, 0 0 20px -3px rgba(99, 102, 241, 0.35)`.
- **Panel Separation:** The 50/50 division on desktop uses a vertical hairline border `1px solid rgba(255, 255, 255, 0.06)`, accentuated with a gradient that fades at top and bottom viewports.

## Shapes

The interface adopts a **Soft, Precision-Engineered Form Language** (Level 1). Forms emphasize architectural rigor over pillowy casualness.

- **Standard Elements (Inputs, Buttons, Badges):** `0.375rem` (6px) border radius for crisp geometry.
- **Cards, Panels, and Dialogs:** `rounded-lg` (`0.5rem` / 8px).
- **Tooltips and Inline Chips:** `0.25rem` (4px).
- **Exceptions:** User profile avatars and biometric touch prompts maintain pure circular geometry (`rounded-full`).

## Components

### 1. Form Inputs
- **Base State:** Background `#161C2E`, border `1px solid rgba(255, 255, 255, 0.1)`, text `body-md` in `#F8FAFC`, height `48px`, horizontal padding `space-md`.
- **Placeholder:** `#64748B`.
- **Focus State:** Border color shifts to `#6366F1` with an indigo ambient aura (`0 0 0 1px #6366F1, 0 0 16px rgba(99, 102, 241, 0.25)`).
- **Password Mask Toggle:** Monospaced icon button positioned inline-right, tinted `#94A3B8`, switching to `#F8FAFC` on hover.

### 2. Buttons
- **Primary Action (Log In, Continue):** Solid `#6366F1` with white high-contrast text (`Geist`, weight 500). Hover produces a subtle brightness lift to `#818CF8` and a concentrated `0 4px 14px rgba(99, 102, 241, 0.4)` glow. Height `48px`.
- **Secondary (SSO Provider Buttons):** Background `rgba(255, 255, 255, 0.03)`, border `1px solid rgba(255, 255, 255, 0.1)`, text `#F8FAFC`. Hover brings background to `rgba(255, 255, 255, 0.07)` and border to `rgba(255, 255, 255, 0.2)`.
- **Ghost/Tertiary (Forgot Password, Terms):** Zero border, zero surface fill. Text `#94A3B8`, transforming to `#F8FAFC` on hover with a delayed underline effect.

### 3. Checkboxes & Radio Controls
- **Box Architecture:** `18px × 18px`, `roundedness: 1` (4px radius), border `1px solid rgba(255, 255, 255, 0.2)`, background `#161C2E`.
- **Checked State:** Background `#6366F1` displaying an SVG micro-check icon in pure white `#FFFFFF`. Outer aura matches the indigo focus glow.

### 4. MFA & OTP Verification Cells
- 6-slot segregated input fields. Each block is `48px × 56px`, center-aligned text in `label_font` (`JetBrains Mono`, 20px).
- Inactive cells feature a bottom baseline border; on focus, the cell activates with a full `#6366F1` luminous border and subtle background brightening.

### 5. Split-Screen Hero Canvas (Left Panel Accent)
- Houses a frosted glass credential card overlay: `rgba(22, 28, 46, 0.6)` backdrop with `blur(20px)`, embedded with dynamic encryption telemetry, system health status dots (`#10B981`), and subtle watermarked cryptographic keys rendered in `code-sm`.