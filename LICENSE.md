# Licensing

This repository uses a split-license model:

- Hardware design source files are licensed under `CERN-OHL-W-2.0`.
- Software/scripts are licensed under `Apache-2.0`.
- Documentation is licensed under `CC-BY-4.0`.

## Scope by path

### Hardware design (`CERN-OHL-W-2.0`)

Applies to:

- `kicad/**/*.kicad_sch`
- `kicad/**/*.kicad_pcb`
- `kicad/**/*.kicad_pro`
- `kicad/**/*.kicad_sym`
- `kicad/**/*.kicad_mod`
- `kicad/**/*-lib-table`
- Other KiCad source assets in `kicad/` (templates, custom libraries, project assets)

### Software and automation (`Apache-2.0`)

Applies to:

- `.github/workflows/**`
- `tests/**`
- Shell scripts and tooling scripts added in this repository

### Documentation (`CC-BY-4.0`)

Applies to:

- `README.md`
- `docs/**`
- `OPEN_HARDWARE.md`
- Markdown/text documentation files not listed above

## Notes

- Generated output files (for example Gerbers, PDFs, images, reports) inherit the license of their corresponding source inputs unless otherwise stated.
- Third-party libraries/components/models remain under their respective upstream licenses.
- Add canonical license texts under a `LICENSES/` directory:
  - `LICENSES/CERN-OHL-W-2.0.txt`
  - `LICENSES/Apache-2.0.txt`
  - `LICENSES/CC-BY-4.0.txt`

