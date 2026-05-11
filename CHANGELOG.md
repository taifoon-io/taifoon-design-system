# Changelog

## [Unreleased]

- React component library (Button, Badge, Card, Modal) consuming --tf-* tokens
- Storybook story suite
- npm package: `@taifoon/design-system`
- Figma token export pipeline

## [1.0.0] — 2026-05-10

Initial token system release. CSS custom properties for the full Taifoon visual language.

### Added

- **`colors_and_type.css`** — 60+ CSS custom properties (`--tf-*`)
  - Core palette: `--tf-void` (near-black), `--tf-silver` (primary text), `--tf-blue` (field energy), `--tf-teal` (anomaly), `--tf-volt` (events)
  - Functional: `--tf-ok`, `--tf-warn`, `--tf-alert`
  - ICP category accents: finance / trading / infra / messaging / rollups / enterprise
  - Typography: `--tf-font-sans` (Inter Variable), `--tf-font-mono` (JetBrains Mono)
  - Type scale: 11 steps from xs (0.75rem) to 7xl (4.5rem)
  - Spacing, shadows, glows, motion (3 easings, 3 durations)
  - Borders (3 opacities), radius (sm → full), z-index scale (0–400)
- **`preview/index.html`** — visual swatch gallery for all tokens
- **CI** — CSS token count validation (`>= 40 --tf-* variables`) + gitleaks
- **License**: CC-BY-4.0 — attribution required; framework-agnostic, open usage
