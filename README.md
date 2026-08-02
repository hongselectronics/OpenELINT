# OpenELINT Lab — Electronic Warfare & Radar Simulation

An open, single-file, browser-based teaching simulator for **radar** and
**electronic warfare**. No install, no build step, no dependencies, and no
network calls — everything (logic, styling, images) is inlined in one
self-contained `index.html`.

> **Illustrative / notional · generic parameters.** Every system in the roster
> is a *generic, class-representative* model (by frequency band and role) — not
> any specific fielded system. Nothing here reflects real-system performance or
> any classified capability. For instruction and relative comparison only; not
> for operational use.

## Run it
Open `index.html` in any modern browser — that's it.

## Host on GitHub Pages
Put `index.html` (and the included `.nojekyll`) at the repository root (or in
`/docs`), then enable **Settings → Pages**. The `.nojekyll` file ensures the
site is served as-is.

## What's inside (tabs)
- **RADAR Fundamentals** — Fundamentals primer, Range Equation, Null Steering,
  Sidelobe Canceler, Scan Loss
- **Detection & Engagement** — Engagement (J/S · SINR · burn-through),
  Radar Scopes (PPI / A / B / Range-Doppler), Range-Height coverage,
  Receiver Chain, Signal Processing, Multipath, Detection (Swerling / ROC /
  Monte Carlo), Dynamic Range, Link Budget, Burn-through Monte Carlo
- **Countermeasures & EP** — Deception (DRFM), RWR, Decoys & Chaff
- **SIGINT / ES** — ELINT / ESM (de-interleaving, emitter ID, geolocation)
- **Special & Reference** — LO / Stealth, Order of Battle, Systems / Data
  editor (add/edit systems, CSV import/export), References

## Methods & references
The models are re-implementations of standard, published radar/EW formulas
(array factor, radar range equation, jammer-to-signal / burn-through,
Marcum-Q and Shnidman detection, CFAR, CRLB/GDOP, pattern-propagation factor,
ITU-R attenuation, etc.). Full citations are on the in-app **References** tab.

## License
Released under the **MIT License** (see `LICENSE`). Free to use, modify, and
share. Update the copyright holder in `LICENSE` to your name/org if you fork it.
