# taifoon-design-system

> *Mathematics rendered in light.*
>
> Tokens, fonts, and UI kit for the Taifoon visual language.

[taifoon.io](https://taifoon.io) reads as a research-grade physics instrument: black space, silver intelligence, blue field energy, teal anomaly signal, Volt for charged events. This repo is the canonical reference for everything that makes that read.

**License:** CC-BY-4.0 — use freely with attribution. Adapter integrations and partner products are encouraged to pick up these tokens and ship cohesive visuals across the ecosystem.

---

## Index

- [`colors_and_type.css`](./colors_and_type.css) — CSS variable tokens (`--tf-*`, opacity scale, motion ease, type scale)
- [`preview/`](./preview/) — HTML swatch gallery rendering the token system
- `fonts/` — Inter Variable + JetBrains Mono Variable woff2s *(coming in v1.1)*
- `assets/` — logos, hero imagery, chain icons *(coming in v1.1)*

## Brand truths

- Black-dominant (85–90%) universe. Silver, Blue, Teal, Violet are accents. Volt is the high-energy signal.
- `border-radius: 0` everywhere. Never round corners.
- **Inter** (sans) + **JetBrains Mono** (mono). Mono is used liberally for labels, captions, stats, buttons, addresses, hashes, chain names.
- Hover: blue `::after` sweep shimmer + `cubic-bezier(0.16, 1, 0.3, 1)` easing. Always. No bounces. No elastic.
- Atmospheric depth from three layered effects only: coordinate grids, singularity glows, orbital traces.
- Voice: protocol documentation. Calm, declarative, never selling. The brand speaks like a law of physics, not a startup.

## Color distribution

```
Black 85–90%   ← #000000 background
Silver 8–12%   ← #E6F0F7 text, lines, grids
Blue 2–4%      ← #3DA5FF interaction, CTAs, labels
Teal 0.5–1.5%  ← #00B5B8 anomaly signal — live indicators, claimed states, score ≥ 80
Volt           ← #B8F500 charged events / TSUL sash / "live now" pulse
Violet         ← #6A5CFF refunded states, trading ICP only
```

## Type

```
--font-sans: 'Inter', ui-sans-serif, system-ui, sans-serif
--font-mono: 'JetBrains Mono', ui-monospace, SFMono-Regular, Menlo, monospace
```

Light weights (200/300) for headlines. 400 for body. 600 for CTAs. **No 900.**
Tracking: 0.02em baseline, 0.15–0.25em on labels and buttons.

## Motion

- Easing: **always** `cubic-bezier(0.16, 1, 0.3, 1)`
- Durations: 150ms (state), 300ms (transition), 600–700ms (reveal), 8–20s (ambient)
- Reduced-motion: ambient + reveal cut to 10ms (`@media (prefers-reduced-motion: reduce)`)

## Use it

```html
<link rel="stylesheet" href="https://taifoon-design-system.pages.dev/colors_and_type.css" />
```

Or copy `colors_and_type.css` into your own bundle. Load Inter Variable and JetBrains Mono Variable from [Fontsource](https://fontsource.org/fonts/inter) or Google Fonts.

## Get involved

License or commercial questions: **taifooon@proton.me**.

Part of the Taifoon OS — [taifoon.io](https://taifoon.io).
