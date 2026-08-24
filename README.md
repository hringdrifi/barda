# Barða

Barða is a compact wireless keyboard design project by [hringdrifi](https://github.com/hringdrifi).

![Barða, top view](assets/barda-top-view.png)

![Barða, side view](assets/barda-side-view.png)

The design uses 42 Kailh Choc hot-swap switch positions and an FDK HY0020 Bluetooth Low Energy module based on the Nordic nRF52832.

## Supported components

The design supports the following keyboard components:

- Kailh Choc V2 switches
- Kailh low-profile sockets
- [Chosfox Cross-Core Low-Profile Stabilizers](https://chosfox.com/products/chosfox-cross-core-satellite-switch-for-low-profile-keyboards)

Confirm the exact part variants and mechanical fit before ordering or manufacturing.

## Connectivity and firmware

Barða has no USB connection and supports Bluetooth Low Energy (BLE) only. It is powered by a CR1632 lithium coin cell. A USB-to-serial adapter is required to flash firmware to the keyboard.

## Project status

The PCB and case design files are published in this repository. Validate the design for your intended switches, battery, firmware, manufacturing process, and assembly before building hardware.

## Available files

- [`pcb/`](pcb/) — KiCad source files for the keyboard PCB and plates
  - [`barda.kicad_pcb`](pcb/barda.kicad_pcb) — main keyboard PCB
  - [`barda.kicad_sch`](pcb/barda.kicad_sch) — schematic
  - [`barda_plate.kicad_pcb`](pcb/barda_plate.kicad_pcb) — switch plate PCB
  - [`barda_bottom_plate.kicad_pcb`](pcb/barda_bottom_plate.kicad_pcb) — bottom plate PCB
  - [`smidr.pretty/`](pcb/smidr.pretty/) — custom footprints referenced by the design
  - [`3dmodels/`](pcb/3dmodels/) — STEP models for selected components
- [`case/`](case/) — STEP models for the case assembly
  - [`barda_switch_plate.step`](case/barda_switch_plate.step) — case switch plate
  - [`barda_bumper.step`](case/barda_bumper.step) — bumper layer
  - [`barda_bottom_plate.step`](case/barda_bottom_plate.step) — case bottom plate
- [`pcb/README.md`](pcb/README.md) — Smiðr KiCad-export details
- [`case/README.md`](case/README.md) — case-model notes and file roles

## License

The design data in `pcb/` and `case/` is licensed under the [CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P-2.0)](LICENSE).

This license permits use, modification, manufacture, and sale of the design data and products made from it. Modified design data does not need to be published, but applicable notices must be retained and modifications must be documented. The design data and any resulting products are provided without warranty.

## Disclaimer

Verify dimensions, clearances, component compatibility, manufacturability, and safety for your own build before making any parts. Use of these files is at your own risk.
