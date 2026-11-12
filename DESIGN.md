---
name: Andean Electric Touring
colors:
  surface: '#0d1417'
  surface-dim: '#0d1417'
  surface-bright: '#333a3e'
  surface-container-lowest: '#080f12'
  surface-container-low: '#161d20'
  surface-container: '#1a2124'
  surface-container-high: '#242b2e'
  surface-container-highest: '#2f3639'
  on-surface: '#dce3e8'
  on-surface-variant: '#b9cbbd'
  inverse-surface: '#dce3e8'
  inverse-on-surface: '#2a3135'
  outline: '#849588'
  outline-variant: '#3b4a40'
  surface-tint: '#00e293'
  primary: '#cdffde'
  on-primary: '#003921'
  primary-container: '#00f5a0'
  on-primary-container: '#006b43'
  inverse-primary: '#006c44'
  secondary: '#95d3ba'
  on-secondary: '#003829'
  secondary-container: '#0b513d'
  on-secondary-container: '#83c2a9'
  tertiary: '#e9f5ff'
  on-tertiary: '#00354a'
  tertiary-container: '#a9deff'
  on-tertiary-container: '#006488'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#50ffaf'
  primary-fixed-dim: '#00e293'
  on-primary-fixed: '#002111'
  on-primary-fixed-variant: '#005232'
  secondary-fixed: '#b0f0d6'
  secondary-fixed-dim: '#95d3ba'
  on-secondary-fixed: '#002117'
  on-secondary-fixed-variant: '#0b513d'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#0d1417'
  on-background: '#dce3e8'
  surface-variant: '#2f3639'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: 0em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.04em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-lg: 2rem
  margin: 1rem
  margin-md: 2rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an automotive-grade digital cockpit crafted for long-range electric expeditioning across the varied topographies of Colombia—from coastal highways to high-altitude Andean mountain passes (*páramos*).

The aesthetic marries the high-precision restraint of modern luxury EV human-machine interfaces (Polestar, Porsche Taycan, Apple CarPlay) with tactile environmental immersion. The experience balances safety-critical legibility while operating at speed with the indulgence of a luxury grand tourer.

### Aesthetic Pillars
- **Atmospheric Glass & Slate:** Deep, non-reflective obsidian and slate foundations layered with satin-finished glass surfaces that capture subtle ambient backdrops without distracting glare.
- **Luminescent Telemetry:** Kinetic accents powered by high-contrast electric mint to command immediate focal attention for charging statuses, battery reserves, altitude gains, and waypoints.
- **Precision Tactility:** Razor-thin inner containment borders (0.5px–1px hairline borders with micro-refraction highlights) mimicking laser-etched automotive glass and machined aluminum bezel trims.
- **Quiet Dominance:** Restrained micro-typography, generous tap-target safety tolerances, and high-frequency real-time cartography that prioritizes essential telemetry under intense equatorial sun or pitch-black mountain fog.

## Colors

The palette is engineered for low luminance fatigue during nocturnal navigation while retaining maximum legibility under direct equatorial sunlight.

### Palette Architecture
- **Primary (`#00F5A0` - Electric Mint):** High-luminance signal green. Reserved for active charging states, critical state of charge (SoC) metrics, vehicle speed readouts, and active route trajectories.
- **Secondary (`#064E3B` - Deep Emerald):** Rich botanical undertone used for structural surfaces, active navigation banners, and gradient fades behind cartography overlays. Echoes Colombia’s cordilleras.
- **Tertiary (`#38BDF8` - Glacial Cyan):** Ancillary telemetry accent for regenerative braking curves, altitude differentials, temperature overlays, and ultra-fast DC charging station markers.
- **Neutral (`#0B1215` - Obsidian Slate):** Low-glare automotive canvas. Eliminates deep black OLED clipping while reducing visual noise and dashboard reflection against the windshield.

### Functional States
- **Critical / Low Range:** `#FF385C` (Luminous Crimson) for range deficits, charger outages, or sudden battery temp spikes.
- **Cautionary / High Gradient:** `#F59E0B` (Amber Beacon) for steep descent brake cooling notices and unpaved roadway transitions.
- **Surface Elevation Steps:** Base Canvas (`#0B1215`), Glass Panel Bed (`#111C20` at 70% opacity), Floating Overlay Bed (`#18262C` at 85% opacity).

## Typography

The typographic hierarchy pairs the technical, engineered geometry of **Space Grotesk** with the neutral, hyper-legible neo-grotesque contours of **Hanken Grotesk**.

### Typographic Principles
- **Glanceability:** Headings, speed, and critical range figures use Space Grotesk with tracked tabular figures, permitting instant absorption within a 200-millisecond cockpit glance.
- **Long-Form Telemetry:** Route logs, waypoint descriptions, and charging specs rely on Hanken Grotesk for fluid reading against dark backdrops without glyph collision.
- **Micro-Badges & Labels:** Sub-12px elements are rendered exclusively in uppercase Space Grotesk with increased letter-spacing (`0.06em` to `0.08em`) to maintain legibility over frosted glass under vibration.

## Layout & Spacing

The layout adapts between in-dash landscape touchscreens (center console/infotainment) and portrait mobile companion displays.

### Layout Philosophy
- **Automotive Ergonomics:** Driving interfaces anchor key interactive regions within the bottom and steering-wheel-adjacent zones. Map visualizers take full-bleed canvas space while controls rest on floating glass trays.
- **Grid Architecture:** 
  - **Mobile (Cockpit Companion):** 4-column fluid layout with a base 16px outer margin.
  - **In-Dash Screen / Tablet (Landscape):** 12-column asymmetric grid split into an 8-column cartographic canvas and a 4-column HUD telemetry dock.
- **Rhythm & Touch Buffers:** Minimum hit areas adhere to automotive ISO standards: no critical driving button or toggle is smaller than 48x48dp, with a mandatory `space-md` (16px) separation to prevent accidental taps across uneven road surfaces.

## Elevation & Depth

Visual hierarchy uses physical material metaphors: deep tinted glass panels, micro-refractions, and high-energy luminescent backlights.

### Elevation Levels

1. **Level 0 (Canvas Base):** Deep Obsidian Slate (`#0B1215`). Used for underlying base cartography, topographical relief shading, and raw instrument backgrounds.
2. **Level 1 (Sub-Panel / Cards):** Translucent Slate (`#111C20` at 70% opacity) accompanied by `backdrop-filter: blur(20px)` and an interior top-edge hairline border (`1px solid rgba(255, 255, 255, 0.08)`).
3. **Level 2 (Active Telemetry Floating Trays):** Frosted Emerald-Slate (`#18262C` at 85% opacity) with a diffused drop shadow: `0 12px 32px -4px rgba(0, 0, 0, 0.65), 0 0 0 1px rgba(0, 245, 160, 0.15)`.
4. **Level 3 (Overlays, Turn Indicators, Critical Alerts):** Elevated HUD layer with ambient back-glow. Uses directional soft shadows tinted with the primary hue: `0 8px 30px rgba(0, 245, 160, 0.25)`.

### Border Treatments
All floating components feature dual-layer borders:
- Outer: 1px continuous hairline (`rgba(255, 255, 255, 0.06)`).
- Top specular highlight: A linear gradient stroke running from left to right (`rgba(255, 255, 255, 0.2)` down to `transparent`), emulating an automotive chamfered bezel catching ambient daylight.

## Shapes

The shape system employs Level 2 (Rounded) geometry, balancing technical precision with modern, sculptural luxury automotive styling.

### Shape Hierarchy
- **Base Components (Cards, Panels, Sheets):** 16px (`rounded-lg`) corner radii for structured integration with glass surfaces.
- **Interactive Units (Buttons, Inputs, Toggles):** 8px (`0.5rem`) corner radii providing sharp, definite boundaries that signal clickability.
- **Badges, Telemetry Chips, and Range Pills:** Full pill treatment (`rounded-full` / 9999px) to convey modular, floating information pods.
- **Elevation Cross-Sections:** Continuous, mathematically smoothed Bezier curves for altitude and battery degradation graphs, avoiding harsh stepped lines.

## Components

### Buttons & Quick Controls
- **Primary Drive Action:** High-luminance Electric Mint (`#00F5A0`) fill with obsidian text (`#0B1215`), 8px rounded corners, and a subtle inner top highlight. Hover/active states project an electric halo (`box-shadow: 0 0 20px rgba(0, 245, 160, 0.4)`).
- **Secondary / HUD Button:** Translucent glass fill (`rgba(255, 255, 255, 0.05)`), 1px micro-border, white text. Transitions to 15% opacity on active press with tactile audio-haptic feedback.

### Micro-Badges & Waypoint Chips
- **Battery & Elevation Chips:** Compact pill containers with dual-toned interiors. Left quadrant contains an iconography slot (e.g., kW rate, gradient percentage, CCS2 plug icon) illuminated in Electric Mint or Glacial Cyan; right quadrant displays Space Grotesk tabular data.
- **Pass Status Badges:** Dynamic color-coded pill tags signaling Andean pass conditions (e.g., "ALTO DE LA LÍNEA: OPTIMAL - 3,260m").

### Input Fields & Search Bars
- **Waypoint Search:** Recessed glass bar with a dark translucent base (`#0E171A`), inset shadows to create depth, and an Electric Mint 1.5px focus boundary. Integrated voice-command trigger icon for hands-on-wheel operation.

### Elevation & Consumption Graphs
- **Topographical Profile View:** Dynamic SVG path combining an area gradient fill (Secondary Deep Emerald fading to `rgba(6, 78, 59, 0)`) with an Electric Mint stroke tracing the mountain crest.
- **Wayfinding Milestones:** Interactive vertical scrubber needles showing remaining SoC projected across upcoming elevation gains.

### Cartography Markers
- **EV Fast-Charger Nodes:** Circular dark glass pucks encased in a hairline mint ring with an internal charging bolt glyph. When selected, the marker emits a breathing radar pulse indicating real-time stall availability (e.g., "4/6 Free • 150 kW").

### Cards & Telemetry Displays
- **Trip Summary / Cockpit Card:** Floating glass container housing speed, distance to next charge, cabin climate, and regenerative power delivery. Segmented by ultra-subtle vertical dividers (`rgba(255, 255, 255, 0.08)`).