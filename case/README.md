# Barða case models

This directory contains the STEP models for the Barða case. The models are supplied as separate parts so they can be inspected, modified, or incorporated into a manufacturing workflow.

| File | Role |
| --- | --- |
| [`barda_switch_plate.step`](barda_switch_plate.step) | Switch plate for the case assembly. |
| [`barda_bumper.step`](barda_bumper.step) | Bumper layer between the plate and bottom plate. |
| [`barda_bottom_plate.step`](barda_bottom_plate.step) | Bottom plate for the case assembly. |

## Use

Import all three STEP files into the same CAD assembly and align them by their native coordinates. The models are design data rather than a production-ready manufacturing package: confirm dimensions, fit with the PCB and components, material selection, tolerances, and manufacturing constraints before fabrication.

The case models are licensed under the [CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P-2.0)](../LICENSE).
