# Open Hardware Disclosure

This document captures the key open hardware disclosures for `seven-hardware`.

## Project

- Name: `seven-hardware`
- Repository: `https://github.com/<org-or-user>/seven-hardware`
- Current design source path: `kicad/`

## Open source hardware license

- Hardware design files are licensed under `CERN-OHL-W-2.0`.
- See `LICENSE.md` for full path-based license mapping.

## Source files provided

The complete editable source for this hardware project is in:

- `kicad/seven.kicad_sch`
- `kicad/seven.kicad_pcb`
- `kicad/seven.kicad_pro`
- `kicad/sym-lib/**`
- `kicad/fp-lib/**`
- `kicad/*-lib-table`

## Build/manufacturing outputs

CI or local generation may produce artifacts such as:

- ERC/DRC reports
- Gerbers and drill files
- Assembly/position files
- Schematic PDF
- PCB render images
- BOM exports

These are generated from the above source files and are intended to support fabrication and review.

## Dependencies and third-party content

This project may reference external libraries and models (for example KiCad system symbol libraries, footprint libraries, and 3D models).

- Third-party content is governed by its own upstream license.
- Where possible, references should resolve from project-local libraries committed in this repository.

## Modification and redistribution

Under `CERN-OHL-W-2.0`, recipients can study, modify, make, and distribute products based on this design, subject to the terms of that license.

## Maintainer checklist (recommended)

- Keep project library tables (`sym-lib-table`, `fp-lib-table`) committed.
- Keep design source and generated release artifacts traceable by version/tag.
- Document any required proprietary or external dependencies clearly.
- Keep `LICENSE.md` and this file up to date when repository structure changes.

