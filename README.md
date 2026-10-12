# PCB Challenge 2026 submission

Submission workspace for the [Fleming Society PCB Challenge 2026](https://github.com/Fleming-Society/PCB-Challenge-2026).

The design starts from the organisers' KiCad 10 source files at commit [`aa78e2f`](https://github.com/Fleming-Society/PCB-Challenge-2026/commit/aa78e2f7600de122057406a5ad188f318c097d1f). The PCB must be fully routed on one contiguous four-layer board and pass KiCad's Design Rule Checker with zero unresolved errors.

## Submission files

- `pcb_challenge_final.kicad_pro` — KiCad 10 project and design-rule settings
- `pcb_challenge_final.kicad_sch` — supplied schematic
- `pcb_challenge_final.kicad_pcb` — PCB layout to be completed

The logic deduction is submitted in the event form rather than published here.

## Final result

| Check | Result |
| --- | --- |
| Board dimensions | _Pending_ |
| Bounding-box area | _Pending_ |
| Copper layers | _Pending: configure four layers_ |
| Unrouted connections | _Pending_ |
| DRC errors | _Pending_ |
| DRC warnings | _Pending_ |

## Required constraints

- Four copper layers on 1.6 mm FR4
- Minimum track width and clearance: 0.15 mm
- Minimum copper-to-board-edge clearance: 0.3 mm
- Minimum via drill: 0.3 mm
- Minimum via diameter: 0.6 mm (0.15 mm annular ring)
- No vias in pads
- No traces or vias beneath IC courtyards
- No overlapping component courtyards
- Default KiCad or organiser-supplied footprints only; footprints must not be modified
- ESP32 antenna keep-out may extend beyond the board edge
- Continuous reference plane for the high-speed differential pair
- Zero unresolved DRC errors

See [`SUBMISSION_CHECKLIST.md`](SUBMISSION_CHECKLIST.md) before publishing the final entry.
