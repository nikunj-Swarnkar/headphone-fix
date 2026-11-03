<p align="center">
  <img src="assets/banner.jpg" alt="Headphone Fix — 3D printed repair for Noise Airwave Max 4" width="100%" />
</p>

# Headphone Fix

**A set of 3D-printable replacement parts that brought my Noise Airwave Max 4 headphones back to life.**

![Status](https://img.shields.io/badge/status-fixed-brightgreen)
![Parts](https://img.shields.io/badge/parts%20printed-3-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## What is this project?

My Noise Airwave Max 4 headphones snapped at the headband, and the company doesn't sell spare parts for it. Instead of throwing away a pair of headphones that still worked perfectly, I measured the broken pieces, remodelled them in CAD, and 3D printed replacements.

This repo contains everything needed to repeat the repair:

| Part | What it replaces |
| --- | --- |
| **Hinge** | The pivot that connects the headband arm to the ear cup |
| **Headrest band** | The curved top band that cracked under stress |
| **Snap tabs** | The small clips that hold the headrest cover in place |

All models are included as `.step` (editable), `.stl` (any slicer) and `.3mf` (print-ready).

## Why I made this

- **The headband cracked** right where the slider meets the ear cup.
- **No spare parts.** I couldn't find replacement headband or hinge parts for sale, so an official repair wasn't an option.
- **The electronics were fine.** Only the plastic shell failed, so replacing the whole pair felt like a waste.
- **I wanted it to be repairable.** Anyone with the same headphones and access to a 3D printer can now fix theirs instead of buying new ones.

## Tech stack

| Area | Tools / materials |
| --- | --- |
| **CAD** | Fusion 360 (`.f3d` source files included) |
| **Model formats** | STEP, STL, 3MF |
| **Fabrication** | FDM 3D printing |
| **Material** | PLA filament |
| **Measuring** | Digital calipers + test-fit prints |

## How I fixed it

1. **Teardown** — Opened the headband assembly and separated the cracked hinge from the ear cup.
2. **Measurement** — Measured every mating surface and mounting point with calipers, then sketched the profiles.
3. **Modelling** — Rebuilt the hinge and headrest band in Fusion 360, matching the original snap-fit geometry so no glue is needed.
4. **Prototyping** — Printed rough versions to check fit, then iterated on wall thickness and tolerances until the parts clicked in place.
5. **Final print** — Printed the final set, reassembled the headphones and adjusted one part to compensate for a small piece that was lost during teardown.

## Files in this repo

```
3d models/
├── headrest/   head rest fix.f3d | .step | .stl | .3mf
└── hinge/      hinge.f3d         | .step | .stl | .3mf
Bom headrest.csv
```

- **`.3mf`** — ready to slice, no setup needed.
- **`.stl`** — use this if you slice with something other than the bundled 3MF.
- **`.step` / `.f3d`** — edit the geometry if your model or printer needs different tolerances.

## Bill of materials

| Item | Qty | Cost (USD) |
| --- | --- | --- |
| PLA filament (1 kg spool) | 1 | ~$6.32 |

Total cost of the repair was under **$7** — the printer and calipers I already owned.

## License

Released under the [MIT License](LICENSE). Print it, remix it, sell it — a credit is appreciated.

---

## Gallery

### Before

<p align="center">
  <img src="assets/before-1.jpg" alt="Cracked headband" width="44%" />
  <img src="assets/before-2.jpg" alt="Broken hinge area" width="44%" />
</p>

### Teardown & measurements

<p align="center">
  <img src="assets/measure-1.jpg" alt="Measuring the hinge mount" width="44%" />
  <img src="assets/measure-2.jpg" alt="Measuring the headband profile" width="44%" />
</p>
<p align="center">
  <img src="assets/measure-3.jpg" alt="Close-up of the original hinge" width="44%" />
  <img src="assets/measure-4.jpg" alt="Snap-fit details on the headrest" width="44%" />
</p>

### CAD

<p align="center">
  <img src="assets/cad-headrest.jpg" alt="Headrest band model" width="52%" />
  <img src="assets/cad-hinge.jpg" alt="Hinge model" width="34%" />
</p>

### Printed parts

<p align="center">
  <img src="assets/print-1.jpg" alt="Headband back on the headphones" width="44%" />
  <img src="assets/print-2.jpg" alt="Printed parts fitted" width="44%" />
</p>
<p align="center">
  <img src="assets/print-3.jpg" alt="Headphones after the repair" width="40%" />
</p>

### Fitting & adjustments

<p align="center">
  <img src="assets/lost-part.jpg" alt="Original part lost during teardown" width="44%" />
  <img src="assets/adjust.jpg" alt="Adjustment made to replace the lost part" width="44%" />
</p>

### Prototypes

<p align="center">
  <img src="assets/proto-1.jpg" alt="Early prototype" width="32%" />
  <img src="assets/proto-2.jpg" alt="Test fit prototype" width="32%" />
  <img src="assets/proto-3.jpg" alt="Iteration on the hinge" width="32%" />
</p>
<p align="center">
  <img src="assets/proto-4.jpg" alt="Failed test print" width="43%" />
  <img src="assets/proto-5.jpg" alt="Final prototype set" width="43%" />
</p>
