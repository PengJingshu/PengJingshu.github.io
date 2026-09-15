---
version: alpha
name: "Jingshu Peng Portfolio"
description: "An industrial signal-path portfolio for a robotics software engineer, connecting perception, decision, and motion."
colors:
  ink: "#151B23"
  steel: "#596675"
  paper: "#F7F9FA"
  white: "#FFFFFF"
  blueprint: "#0A5C8E"
  signal: "#F05A28"
  line: "#C9D2D9"
typography:
  display:
    fontFamily: "Arial Narrow, Helvetica Neue, Arial, sans-serif"
  body:
    fontFamily: "Aptos, Segoe UI, Helvetica Neue, Arial, sans-serif"
  mono:
    fontFamily: "SFMono-Regular, Consolas, Liberation Mono, monospace"
rounded:
  DEFAULT: "0rem"
  sm: "0rem"
  md: "0rem"
  lg: "0rem"
spacing:
  section-gap: "7rem"
  page-max: "74rem"
components:
  button: {}
  capability-strip: {}
  project: {}
  navigation: {}
---

# Jingshu Peng Portfolio Design System

## Overview

### Creative North Star

A robotics commissioning notebook crossed with a clean industrial control schematic: precise, calm, and evidence-led. The page should feel like the person who can trace a signal from sensor input through software to physical motion.

### Product context and register

- **Audience and primary job:** Robotics hiring managers and engineers assessing Jingshu for robotics software roles.
- **Target market and evidence:** English-language US recruiting, based on the current resume and Pittsburgh-based education and experience.
- **Locale and language policy:** English-only portfolio; technical acronyms remain unexpanded when standard in robotics.
- **Usage scene:** Fast first-pass desktop review with complete mobile support; deeper project reading follows the first scan.
- **Register:** Brand portfolio with restrained technical detail.
- **Memorable signature:** A custom JP motion-path mark uses two precise letter strokes and one safety-orange robot-joint node; the same mark serves as the navigation identity and favicon.
- **Restraint:** No dashboard cards, decorative gradients, invented charts, unnecessary animation, or cryptic metadata labels.
- **Anti-references:** Generic blue SaaS landing pages, academic CV sites, and neon hacker portfolios.
- **Token ownership/runtime mapping:** `DESIGN.md` mirrors the canonical CSS custom properties in `main.css`; every color and type role maps directly by semantic name.

## Colors

Paper and white provide quiet working surfaces. Ink and steel create hierarchy. Blueprint blue marks navigation and technical structure; signal orange is reserved for the signal path, focus, and the strongest measured outcomes. Color never carries meaning alone.

## Typography

Condensed system sans is reserved for display statements at a restrained editorial scale: the hero caps at 6rem, section headings at 4.15rem, and project headings at 2.75rem. Aptos/Segoe UI carries readable body copy. Monospace is used for system labels, dates, technologies, and measured values. Body copy remains at least 16px with controlled line length.

## Layout

The desktop page uses one centered 64rem evidence column for every major content section, with responsive page gutters applied exactly once. Section widths remain aligned across Experience, Projects, Technical Skills, Publications, and Education. The portrait carries a compact two-line education block: institution first, degree and graduation year second, without camera labels or decorative system annotations. At 760px the layout becomes a single column. Images reserve their aspect ratio to prevent layout shift.

## Elevation & Depth

Hierarchy comes from alternating paper/white surfaces and strong typographic scale. Major section headings stand without underline rules; each section's content begins with its own top divider and continues with dividers between entries. The portrait caption sits directly below the framed image without an additional rule. Static content has no drop shadow. The sticky navigation uses an opaque paper surface and bottom rule.

## Shapes

Edges are square and mechanically precise. Pills are limited to compact technology labels. Circular nodes appear only on the signal path, where they encode a connection point.

## Components

### Foundational visual states

Links and controls have visible hover, active, and orange focus-visible states. Disabled and busy states are not used in this static site. Reduced motion removes transforms and smooth scrolling.

### Buttons and actions

Primary actions use ink fill; secondary actions use a transparent surface and visible border. Labels state their destination. Geometry remains stable on hover.

### Navigation and data display

Navigation is text-first and uses the explicit labels Experience, Projects, Toolkit, and Research. Main section headings use Experience, Selected Projects, Technical Skills, and Publications & Patent. Project metadata uses a consistent two-line block with the institution above the full month-and-year range. Every project includes a stack line whose ink `STACK` label is slightly larger and heavier than the technical list, supported by a short orange keyline. The capability strip names four core technical strengths; measured outcomes stay with the experience or project that produced them. Parallel project proof points share one neutral visual treatment; orange is reserved for genuinely prioritized evidence rather than distinguishing equivalent facts. Small technical labels appear only when they provide real context such as role, domain, date, or stack.

### Forms and overlays

This site contains no forms or overlays.

### Iconography

No icon library is used. The custom JP identity mark is a square-free SVG with consistent 4-unit strokes and a single signal-orange joint. It is decorative inside the explicitly labelled home link; all other navigation remains text-first.

### Motion

Only small hover translations are permitted. The design remains complete without motion and respects reduced-motion preferences.

### Content and data visualization

Copy is direct, technical, and evidence-led. Percentages, frequency, and throughput use concise engineering notation; claims are supported by resume facts.

## Do's and Don'ts

- **Do:** Make the perception-to-motion systems story visible within the first viewport.
- **Do:** Use signal orange only for focus and high-value evidence.
- **Do:** Prefer one clear heading over an eyebrow, title, and subtitle that repeat the same idea.
- **Don't:** turn projects into interchangeable rounded cards.
- **Don't:** use cryptic labels such as “SYSTEMS / SELECTED” or “TOOLKIT / CURRENT.”
- **Don't:** annotate the portrait with decorative camera or signal-path terminology.
- **Don't:** add decorative metrics, timelines, or diagrams without factual meaning.
