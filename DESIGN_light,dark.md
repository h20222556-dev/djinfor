---
name: Warm Minimalist Portfolio
colors:
  # --- Light Mode ---
  surface: '#fdf8f8'
  surface-dim: '#ddd9d8'
  surface-bright: '#fdf8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3f2'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e6'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#444748'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#1a1a1a'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#655d51'
  on-secondary: '#ffffff'
  secondary-container: '#e9decf'
  on-secondary-container: '#696255'
  tertiary: '#48473f'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c1c17'
  on-tertiary-container: '#86847e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#ece1d2'
  secondary-fixed-dim: '#cfc5b6'
  on-secondary-fixed: '#201b12'
  on-secondary-fixed-variant: '#4c463b'
  tertiary-fixed: '#e6e2db'
  tertiary-fixed-dim: '#cac6bf'
  on-tertiary-fixed: '#1c1c17'
  on-tertiary-fixed-variant: '#484742'
  background: '#fdf8f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'

  # --- Dark Mode (dark: prefix) ---
  dark-surface: '#1a1918'
  dark-surface-dim: '#141312'
  dark-surface-bright: '#3a3836'
  dark-surface-container-lowest: '#0f0e0d'
  dark-surface-container-low: '#1c1b1b'
  dark-surface-container: '#232120'
  dark-surface-container-high: '#2d2b2a'
  dark-surface-container-highest: '#383534'
  dark-on-surface: '#e8e3e2'
  dark-on-surface-variant: '#c8c5c4'
  dark-inverse-surface: '#e5e2e1'
  dark-inverse-on-surface: '#313030'
  dark-outline: '#928f8e'
  dark-outline-variant: '#474746'
  dark-primary: '#e8e3e2'
  dark-on-primary: '#1a1a1a'
  dark-secondary: '#cfc5b6'
  dark-on-secondary: '#362f24'
  dark-secondary-container: '#4c463b'
  dark-on-secondary-container: '#ece1d2'
  dark-background: '#1a1918'
  dark-on-background: '#e8e3e2'
  dark-surface-variant: '#474746'

typography:
  display-lg:
    fontFamily: "'Pretendard', 'Inter', sans-serif"
    fontSize: 72px
    fontWeight: '200'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: "'Pretendard', 'Inter', sans-serif"
    fontSize: 44px
    fontWeight: '200'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: "'Pretendard', 'Inter', sans-serif"
    fontSize: 48px
    fontWeight: '300'
    lineHeight: '1.2'
    letterSpacing: -0.03em
  headline-md:
    fontFamily: "'Pretendard', 'Inter', sans-serif"
    fontSize: 32px
    fontWeight: '300'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: "'Pretendard', 'Inter', sans-serif"
    fontSize: 22px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: "'Pretendard', 'Inter', sans-serif"
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.8'
    letterSpacing: -0.01em
  body-md:
    fontFamily: "'Pretendard', 'Inter', sans-serif"
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.7'
    letterSpacing: 0em
  body-sm:
    fontFamily: "'Pretendard', 'Inter', sans-serif"
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  label-sm:
    fontFamily: "'Pretendard', 'Inter', sans-serif"
    fontSize: 13px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.05em

rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px

spacing:
  container-max: 1440px
  gutter: 24px
  gutter-mobile: 16px
  margin-desktop: 80px
  margin-mobile: 20px
  section-gap: 160px
  section-gap-mobile: 96px
  stack-gap: 32px
  card-gap: 24px

motion:
  default: '0.3s ease-in-out'
  lift: '0.5s cubic-bezier(0.4, 0, 0.2, 1)'
  scale: '0.4s cubic-bezier(0.4, 0, 0.2, 1)'
  fade: '0.6s cubic-bezier(0.4, 0, 0.2, 1)'
  scroll-reveal: '0.7s cubic-bezier(0.16, 1, 0.3, 1)'
  stagger-delay: '80ms'
  cursor-follow: '0.12s linear'
---

## Brand & Style

This design system is built on a foundation of **Warm Minimalism**, blending the precision of high-end consumer technology interfaces with the tactile, emotional comfort of editorial design. It is tailored for a multi-disciplinary creative professional who balances technical development, UX/UI design, strategic planning, and creative direction.

The visual narrative avoids the clinical coldness of pure "Tech Minimalism" by using a soft, ivory-based palette and generous whitespace. The goal is to evoke a sense of quiet confidence, clarity, and intentionality. The user experience should feel breathable and unhurried, utilizing subtle transitions that mimic organic motion rather than mechanical snaps.

Both Light and Dark modes are first-class experiences. The dark theme uses warm-tinted darks (not pure black) to maintain the emotional warmth of the brand at night.

## Colors

The palette is anchored by **Warm Ivory (#FDF8F8)**, which serves as the primary canvas to reduce eye strain and provide a more premium, "paper-like" feel than pure white.

- **Primary:** Soft Black (#1A1A1A) is used for all high-emphasis text and iconography to ensure deep contrast without the harshness of hex #000.
- **Secondary:** Deep Beige (#655D51) acts as a sophisticated accent for metadata, labels, and secondary actions.
- **Tertiary:** Warm Olive (#48473F) is reserved for subtle categorization and tag elements.
- **Surface:** Pure White (#FFFFFF) is used sparingly for floating elements like cards or navigation bars to create a subtle layered effect against the ivory background.

**Dark Mode:** The dark background is Warm Charcoal (#1A1918) — a brownish-tinted dark that preserves the brand's warmth. Text uses Soft Cream (#E8E3E2) instead of pure white to reduce glare.

## Typography

The typographic system prioritizes legibility and editorial rhythm. All tokens use **Pretendard** as the primary font (covering Korean characters with a unified neo-grotesque aesthetic), with **Inter** as a fallback for environments where Pretendard is unavailable.

Font loading: `@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');`

Headlines should be set with light weights (200–300) and tight letter-spacing to create a "designed" feel. Body text utilizes a generous line-height (1.7–1.8) to ensure maximum readability and to contribute to the overall sense of openness. Use **label-sm** for metadata and small tags, applying a slight tracking increase for clarity.

A new **headline-sm** token is added for section sub-headers and case study titles within modals. A **body-sm** token is added for caption text and card metadata.

## Layout & Spacing

The layout utilizes a **12-column fluid grid**, but content is intentionally constrained to the center **8 or 10 columns** for long-form text and project descriptions to maintain optimal line lengths.

- **Desktop:** 80px side margins with 24px gutters.
- **Mobile:** 20px side margins with 16px gutters.
- **Vertical Rhythm:** Large "Section Gaps" (160px on desktop, 96px on mobile) are used between major content blocks to emphasize the minimalist aesthetic.

Alignment should be primarily left-aligned for clarity, with the exception of the Hero section which can experiment with centered or asymmetrical compositions.

## Elevation & Depth

This design system avoids heavy shadows, instead using **Tonal Layers** and **Low-Contrast Outlines** to define hierarchy.

- **Level 0 (Base):** Warm Ivory (#FDF8F8) / Dark: Warm Charcoal (#1A1918).
- **Level 1 (Cards/Nav):** Pure White (#FFFFFF) with a 1px border of Warm Gray (#E5E1DA) or a very soft, diffused shadow (`0px 4px 20px rgba(0,0,0,0.04)`). Dark: Surface container (#232120) with outline-variant border.
- **Level 2 (Modals/Overlays):** White with `0px 8px 40px rgba(0,0,0,0.08)`. Dark: `#2d2b2a` with `rgba(0,0,0,0.4)` backdrop.
- **Interactions:** On hover, elements lift using the `lift` motion token, increasing border opacity rather than shadow depth.

## Motion

All transitions should feel **organic and unhurried**. Never use linear easing for UI elements — always prefer ease-in-out or custom cubic-bezier curves.

- **default (0.3s):** Buttons, links, color transitions.
- **lift (0.5s):** Card hover elevation, nav state changes.
- **scale (0.4s):** Image zoom on hover (project cards).
- **fade (0.6s):** Section transitions, modal open/close.
- **scroll-reveal (0.7s):** Elements entering viewport — use `transform: translateY(24px) → 0` combined with `opacity: 0 → 1`.
- **stagger-delay (80ms):** Apply sequentially to lists of cards or skill items so they animate in with a natural cascade effect.
- **cursor-follow (0.12s):** Custom cursor tracking speed — fast enough to feel responsive, slow enough to feel weighted.

Respect `prefers-reduced-motion`: all scroll-triggered and decorative animations should be disabled when this media query is active.

## Shapes

The shape language is refined and soft. A standard **0.5rem (8px)** radius is used for small components like input fields and buttons, while larger containers and project image cards use **1rem (16px)** to emphasize a modern, friendly feel.

Filter tags and category chips may use **full (9999px)** pill shape as an exception, as their small size makes it appropriate. Standard buttons should never be fully pill-shaped.

## Components

### Navigation
A fixed top navigation with `backdrop-filter: blur(16px)` and `background: rgba(253,248,248,0.85)` (dark: `rgba(26,25,24,0.85)`). Includes: logo/name on the left, nav links center or right, and a dark mode toggle icon on the far right. Link items have a soft underline `scaleX` transition on hover. On scroll past 80px, add a subtle `1px solid outline-variant` bottom border.

### Hero Section
Large-scale typography is the primary visual. Use **display-lg** for the main statement and **body-lg** for the subtext. Below the subtext, include a row of discipline tags (e.g., `Development`, `Design`, `Planning`, `Creative`) using the **label-sm** token and pill-shaped chips. Ensure at least 120px of padding at the top.

Interactive enhancement: on cursor hover anywhere in the hero, a large radial gradient (warm, low-opacity) follows the cursor to add depth without distraction. Disable on mobile.

### Project Filter Tabs
A horizontally scrollable tab row beneath the section title, containing: `All`, `Development`, `Design`, `Planning`, `Creative`. Active tab uses **primary** background with **on-primary** text. Inactive tabs use a 1px border with transparent fill. Filtering triggers a fade + slight vertical shift animation on the card grid using the **fade** motion token. On mobile, the tab row scrolls horizontally with no visible scrollbar.

### Project Cards
Cards feature edge-to-edge imagery with a **1rem (16px)** border radius. Below the image: discipline tag (label-sm, secondary color), project title (headline-sm), and a one-line description (body-sm, on-surface-variant). On hover: image scales to 1.02x using the **scale** motion token, and a thin primary-colored bottom border appears on the card. Cards animate into view on scroll using **scroll-reveal** with **stagger-delay** applied per card.

### Case Study Modal
Triggered on project card click. Opens as a full-height right-side drawer (desktop) or bottom sheet (mobile) with a semi-transparent backdrop. Structure inside the modal:
1. **Header:** Project title (headline-md) + discipline tag + close button.
2. **Problem:** "What problem were we solving?" — body-md, italic.
3. **Process:** Key steps with optional inline images — body-md with headline-sm sub-headers.
4. **Outcome:** Measurable results or takeaways — body-lg, slightly larger for emphasis.
5. **Footer:** Links to live project or GitHub.

Modal opens with a `translateX(100%) → 0` (desktop) or `translateY(100%) → 0` (mobile) using the **fade** motion token.

### Dark Mode Toggle
An icon button (sun/moon) in the top-right of the navigation. On click, toggles a `data-theme="dark"` attribute on the `<html>` element. All color tokens switch via CSS custom properties. The toggle itself animates with a 0.4s rotation + opacity crossfade between icons. Persist preference in `localStorage`.

### Custom Cursor
Replace the default cursor with a small circle (12px, `primary` color, 60% opacity). On hover over interactive elements (links, buttons, cards), the circle expands to 32px and reduces opacity to 30%, creating a "halo" effect. Uses the **cursor-follow** motion token for tracking. Hide on touch devices.

### Scroll Reveal
All major content blocks (section titles, card grids, skill lists, about text) enter the viewport with a `translateY(24px) → 0` + `opacity: 0 → 1` animation using **scroll-reveal**. Use `IntersectionObserver` with a `0.15` threshold. Apply **stagger-delay** to any group of 2+ sibling elements.

### Buttons
Primary buttons: **primary** background (#1A1A1A) with **on-primary** text. Secondary buttons: 1px border (`outline-variant`) with no fill. All buttons feature the **default** motion transition on `background-color` and `border-color`. Minimum touch target: 44px height on mobile.

### Skill Lists
Presented as a clean grid or a series of horizontal rows with subtle dividers (`outline-variant`). Category titles use **label-sm** in **secondary** color. Items animate in on scroll with **stagger-delay**. On hover, each skill item's background transitions to `surface-container-low`.

### Footer
Minimal single-row footer: name on the left, social links (GitHub, LinkedIn, email) on the right as icon buttons. Separated from content by a single `outline-variant` divider. Uses **body-sm** for copyright text.
