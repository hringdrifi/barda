# Barða

Barða is a compact wireless keyboard design project by [hringdrifi](https://github.com/hringdrifi).

The design uses 42 Kailh Choc hot-swap switch positions and an FDK HY0020 Bluetooth Low Energy module based on the Nordic nRF52832.

## Project status

The PCB design files are published in this repository. Validate the design for your intended switches, battery, firmware, manufacturing process, and assembly before building hardware.

## Available files

- [`pcb/`](pcb/) — KiCad source files for the keyboard PCB and plates
  - [`barda.kicad_pcb`](pcb/barda.kicad_pcb) — main keyboard PCB
  - [`barda.kicad_sch`](pcb/barda.kicad_sch) — schematic
  - [`barda_plate.kicad_pcb`](pcb/barda_plate.kicad_pcb) — switch plate PCB
  - [`barda_bottom_plate.kicad_pcb`](pcb/barda_bottom_plate.kicad_pcb) — bottom plate PCB
  - [`smidr.pretty/`](pcb/smidr.pretty/) — custom footprints referenced by the design
  - [`3dmodels/`](pcb/3dmodels/) — STEP models for selected components
- [`pcb/README.md`](pcb/README.md) — Smiðr KiCad-export details

## License

The design data in `pcb/` is licensed under the [CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P-2.0)](LICENSE).

This license permits use, modification, manufacture, and sale of the design data and products made from it. Modified design data does not need to be published, but applicable notices must be retained and modifications must be documented. The design data and any resulting products are provided without warranty.

## Disclaimer

Verify dimensions, clearances, component compatibility, manufacturability, and safety for your own build before making any parts. Use of these files is at your own risk.
