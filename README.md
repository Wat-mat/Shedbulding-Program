# Shed Designer

A browser-based design tool for wood-framed sheds. Enter a size and a few options, and it builds a full 3D framing model and generates the shopping list and cut list to build it.

> This is a showcase repository: screenshots and a feature overview only. The application source is kept private.

![Gable shed framing in 3D](docs/screenshots/gable-3d-framing.png)

## What it does

- **Live 3D framing model.** Every stud, plate, joist, header and rafter is modeled and color-coded by role. Orbit, zoom, and toggle layers on and off.
- **Three roof styles.** Gable, lean-to, and barn (gambrel), each with adjustable pitch, overhangs and (for gambrel) break position.
- **Three roof framing options.** Cut rafters, build your own trusses, or buy pre-made trusses.
- **Doors and windows.** Placed openings automatically get headers and framing.
- **Materials list.** Lumber, sheathing, siding and roofing totals by board size, with a CSV export.
- **Cut list.** Every piece grouped by stock and length, so you can cut efficiently at the saw.
- **Roof cut details.** Angles and dimensions for rafter and truss cuts.
- **Flags.** Warnings when a choice needs attention.
- **Light and dark themes.**

## Screenshots

| Barn (gambrel) roof | Lean-to roof |
|---|---|
| ![Gambrel](docs/screenshots/barn-gambrel.png) | ![Lean-to](docs/screenshots/lean-to.png) |

| Built trusses | Materials list |
|---|---|
| ![Trusses](docs/screenshots/built-trusses.png) | ![Materials](docs/screenshots/materials-list.png) |

![Dark theme](docs/screenshots/dark-theme.png)

## Tech

TypeScript, Vite, three.js for rendering, and Vitest. The project has an automated test suite of more than 300 tests covering the framing, counting and list-generation logic.

## Status

In active development. Core framing, roofing, trusses, and material and cut lists work today; more features are planned.

## Contact

Built by Carson Honaker (University of Nebraska Omaha, cybersecurity). Interested in the project? Reach out through my GitHub profile.
