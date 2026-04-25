# Seven Hardware

Seven is a rapid‑prototyping platform for low‑cost, low‑power connected
IoT devices with integrated LTE cellular connectivity.

Designed for teams moving from concept to deployment, Seven bridges the gap
between traditional development boards and finalized products—making it ideal
for pilot projects, field trials, and early production runs.

Specification:

* Nordic Semiconductor nRF9151 SiP with integrated LTE-M/NB-IoT modem and GPS
  * 64 MHz Arm Cortex-M33
  * 256 KiB RAM
  * 1 MiB flash
* 6-36 V input voltage
* 2 x mikroBUS™ sockets for easy expansion with Click Boards
* RGB LED
* Passive buzzer
* Programming interface (SWD) via TAG connector
* Industrial temperature range (-40 to 85 Celsius)

The software stack is built on the Zephyr Project, providing a robust, secure,
and scalable RTOS foundation. It includes ready‑to‑use modules for over‑the‑air
(OTA) updates and cloud connectivity, with primary support for AWS IoT.

By adopting the widely used mikroBUS™ add‑on standard, Seven offers access to
thousands of off‑the‑shelf Click Boards. This makes it easy to extend the
platform with sensors (motion, proximity, temperature, etc.) or interfaces such
as RS‑232, RS‑485, CAN, and more—without custom hardware design.

Seven is open source and open hardware, giving developers complete transparency
and control to customize, manufacture, and evolve their products without vendor
lock‑in.

---

This repository contains the KiCad project, documentation, and manufacturing
files required to build the Seven hardware board.

<p align="center">
  <img src="assets/seven_nrf9151.jpg" alt="Seven nRF9151" width="50%" />
</p>

## License

Copyright 2026 ID8 Engineering AB

This source describes Open Hardware and is licensed under the CERN-OHL-P v2.

You may redistribute and modify this source and make products using it
under the terms of the CERN-OHL-P v2 (https://cern.ch/cern-ohl).

This source is distributed WITHOUT ANY EXPRESS OR IMPLIED
WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY
AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-P v2
for applicable conditions.

This source distribution includes the companion documents required by
the CERN-OHL-P v2 guide:

- [LICENSE](LICENSE)
- [CERN-OHL-P-v2-user-guide.md](CERN-OHL-P-v2-user-guide.md)
- [CHANGES.txt](CHANGES.txt)

---

## Report issues

If you run into problems, you can ask for help in our
[issue tracker](https://github.com/id8-engineering/seven-hardware/issues) on
GitHub.

## Maintainers

Maintained by [ID8 Engineering AB](https://github.com/id8-engineering/).
