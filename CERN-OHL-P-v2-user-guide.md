# Guide to the CERN-OHL-P v2

This document contains guidelines on how to apply the CERN-OHL-P v2 to a given
hardware design, and on the use of hardware designs licensed under the CERN-
OHL-P v2.

## How to apply the CERN-OHL-P v2 to a hardware design

Pre-requisite:

Authorship/ownership of the design must be clear and undisputed. Only the legal
owner of the rights in the hardware design may decide under what conditions to
make it available. If ownership is vested in more than one person/entity, there must
be an agreement among the owners (or a chain of compatible licences from each of
them) to release the hardware design as open hardware, and under the CERN-OHL-
P v2 in particular.

## The hardware design Source package

Pack all your hardware design Source files (e.g. for a Printed Circuit Board
schematics, layout, documentation...) as well as the documents listed below in an
archive file. This will ensure the licensee downloads everything in one go. It is best
to archive the files using a format everybody can open. Schematics and layouts
should be included in both source form and, should the design tool be proprietary, a
format readable by everybody, such as pdf.

The following documents must be distributed together with the hardware design
sources:

- Document containing the CERN-OHL-P v2
- This Guide
- A text file (plain ASCII file), where information can be added to but not removed
  from, noting that the design has been changed, and providing a date and
  information about the changes made by Licensee (see section 3.3.b of
  CERN-OHL-P v2) (e.g. CHANGES.TXT). A detailed list of changes would be
  helpful, as would a diff, but a description of the changes (e.g. "AC/DC power
  converter circuit removed as AC input no longer necessary") is fine.

## What to do with the hardware design Sources

Include in the hardware design Sources, for instance as a header, the following
elements:

- A copyright notice reflecting actual ownership
- A notice that the hardware design source is licensed under the CERN-OHL-P v2,
  possibly with a link to https://cern.ch/cern-ohl. Example notices: "Licensed
  under CERN-OHL-P v2 or later" or "Licensed under CERN-OHL-P v2"
- A disclaimer of warranties
- A source location, where others can find your design, if you wish to specify one

The following is an example of header if CERN is the Licensor:

```text
Copyright CERN 2020.

This source describes Open Hardware and is licensed under the CERN-OHL-P v2

You may redistribute and modify this documentation and make products using it
under the terms of the CERN-OHL-P v2 (https:/cern.ch/cern-ohl).
This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY,
INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A
PARTICULAR PURPOSE. Please see the CERN-OHL-P v2 for applicable conditions
```

Include in a part of the Source corresponding to a visible part of the Product (e.g.
silkscreen or top copper for a Printed Circuit Board):

- The licence notice: "Licensed under CERN-OHL-P v2"
- Do not include the CERN logo or the copyright notice
- The source location if you wish it to appear on the Product, its packaging or
  documentation

## How to deal with hardware designs licensed under the CERN-OHL-P v2

Generally speaking, you must always comply with any obligations applying to a
particular design (detailed in a contract or accompanying licence). If you receive
hardware designs licensed under the CERN-OHL-P v2, the obligations are to:

- Keep intact all the copyright and trademark notices that are on the hardware
  design Sources
- Keep intact the references to the CERN-OHL-P v2
- Keep intact the disclaimer of warranties

If you modify hardware design that you received from someone else that is licensed
under the CERN-OHL-P v2, you must

- Keep intact all the notices referred to above, although you may remove notices
  that are no longer relevant to your design
- Include notices that you have modified the hardware designs, giving a date and
  information about the modifications you have made (e.g. in a CHANGES.TXT file)
- Add the appropriate copyright notice to the modifications that were made
