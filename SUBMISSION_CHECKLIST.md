# Submission checklist

The challenge closes at the end of 19 October 2026. The entry needs a public repository link and a completed [submission form](https://forms.cloud.microsoft/Pages/ResponsePage.aspx?id=_oivH5ipW0yTySEKEdmlwtUrHdFLQS5OlbEozvc0DnlUMzJQWkFZVDhVRjZNVTlCQjhHQ0hDSUxSQi4u).

## Project and placement

- [x] Start from the organisers' corrected source files.
- [x] Set up four copper layers and a 1.6 mm stack.
- [x] Set the current minimum track width and clearance to 0.15 mm and 0.12 mm.
- [x] Set copper-to-edge clearance to 0.3 mm.
- [x] Set minimum via diameter, drill and annular ring to 0.6 mm, 0.3 mm and 0.15 mm.
- [x] Include the supplied custom footprint libraries with the project.
- [x] Place all 164 components on one contiguous board without overlapping courtyards.
- [x] Keep the antenna exclusion area off the board.

## Routing and checks

- [x] Route the USB pair and check the ground fill beneath its main traces.
- [x] Route the supply, clock and reset networks.
- [x] Route the mux-to-register links, two-stage synchroniser links and comparator gate links.
- [x] Check for vias in SMD pads and vias overlapping IC courtyards.
- [ ] Move the two existing `b2` and `b3` vias out of U10's courtyard; `b2` is also in a pad.
- [ ] Finish the 18 remaining unconnected items in [the routing list](REMAINING_CONNECTIONS.md).
- [ ] Review traces against the same-layer IC courtyard restriction.
- [ ] Resolve or account for the symbol and footprint mismatches in the parity report.
- [ ] Refill all copper zones and run DRC with zero unresolved errors.
- [ ] Review the remaining warnings.
- [ ] Check the layer stack and USB geometry for the chosen manufacturer.
- [ ] Reopen the project from a fresh checkout and repeat the checks.
- [ ] Record the final dimensions and area after routing is complete.

## GitHub and form

- [ ] Put the finished, checked layout on the repository's main branch.
- [ ] Confirm the public link opens without signing in.
- [ ] Add the logic deduction and supporting reasoning to the form.
- [ ] Complete the participant and team details.
- [ ] Submit the form before the deadline.

The current layout is a working version. Publishing this branch does not submit an entry to the challenge.
