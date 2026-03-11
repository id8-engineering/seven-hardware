# Seven Hardware

Hardware design files for the **Seven platform**.

This repository contains the KiCad project, documentation, and manufacturing files required to build the Seven hardware board.

---

## Overview

Seven is a hardware platform designed for fast prototyping IoT projects.

The board provides:

- Main microcontroller 
- Power management 
- Connectivity interfaces 
- 2 MikroBUS sockets
- Debug and programming interface

The hardware is designed using **KiCad**.

---

## Hardware Features

- MCU: nRF9151
- Supply voltage: 7-40V (3-40V but Seven needs 5V)
- Onboard regulation: 3.3V regulator
- Debug and programming interface: UART & SWD

---

## Requirements

To open or modify the design files you need:

- **KiCad 8.x** (recommended)

Download:  
https://www.kicad.org/

---

## Images

Coming soon...

---

## Manufacturing **COMING SOON** (PLACEHOLDER)

```
Manufacturing outputs are located in:

production/gerbers

These include:

- Gerber files
- Drill files
- Pick-and-place files
- Bill of materials

You can upload the Gerbers directly to a PCB manufacturer.
```

---

## Development Workflow **COMING SOON** (PLACEHOLDER)
```
1. Edit schematic in KiCad
2. Run electric rule check (ERC)
3. Update PCB layout
4. Run design rule check (DRC)
5. Generate manufacturing files
6. Commit changes
```

---

## Hardware Revision

Current revision: Coming soon...

Revision history is documented in:

docs/revisions.md

---

## Contributing

Coming soon...

---

## License

Coming soon

---

## Maintainers

Maintained by **ID8 Engineering**.
