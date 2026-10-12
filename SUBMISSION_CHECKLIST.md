# Submission checklist

The organisers' deadline wording is **midnight on 19 October 2026**. Complete the Microsoft Form linked from the [official challenge repository](https://github.com/Fleming-Society/PCB-Challenge-2026) before the deadline.

## Design setup

- [ ] Open the project in KiCad 10
- [ ] Configure a four-layer stack on 1.6 mm FR4
- [ ] Choose inner-layer roles that provide a continuous reference plane for the differential pair
- [x] Set global minimum track width and clearance to 0.15 mm
- [x] Set minimum copper-to-edge clearance to 0.3 mm
- [x] Set minimum via diameter/drill to 0.6 mm / 0.3 mm
- [x] Set minimum via annular ring to 0.15 mm

## Layout completion

- [ ] Draw one contiguous board outline
- [ ] Place all components without courtyard overlap
- [ ] Keep traces and vias out of every IC courtyard
- [ ] Route every connection manually; auto-routing does not count
- [ ] Keep vias out of pads
- [ ] Keep the high-speed differential pair over a continuous reference plane
- [ ] Add sensible ground fill and stitching where appropriate
- [ ] Minimise the board's bounding-box area
- [ ] Record final width, height, area, and via count in `README.md`

## Verification

- [ ] Refill all copper zones
- [ ] Confirm zero unrouted connections
- [ ] Run KiCad DRC and resolve every error
- [ ] Review and minimise warnings
- [ ] Confirm footprints still match their libraries
- [ ] Re-open the project from a clean checkout to catch missing files

## GitHub and form

- [ ] Commit the final KiCad source files
- [ ] Push to a public GitHub repository
- [ ] Confirm the repository opens without signing in
- [ ] Use `https://github.com/S-n-a-z/PCB-Challenge-2026-Submission` as the form link once the repository exists
- [ ] Prepare the logic deduction and reasoning for the form (do not add it to this public repository unless intentional)
- [ ] Enter full name
- [ ] Enter university email address, not a personal address
- [ ] Enter team name and full member names, or `N/A`
- [ ] Select year of study
- [ ] Select university
- [ ] Add challenge rating and optional comments
- [ ] Submit the form
