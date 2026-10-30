# Hardware Design

This directory contains the hardware design documentation and implementation files of the Multi-Range Voltage-Controlled Current Sink (VCCS).

The hardware design was developed using Altium Designer and consists of the complete circuit schematic and a two-layer printed circuit board (PCB).

## 1. Circuit Schematic

The schematic design covers the main functional blocks of the VCCS, including:

- Continuous linear current-sink circuit based on an operational amplifier and MOSFET.
- Boost-converter-based high-current regulation stage.
- Current-sensing and feedback circuitry.
- Microcontroller-based control and reference generation.
- Current-range selection and switching circuitry.
- Power supply and signal conditioning sections.

## 2. PCB Design

The PCB was designed as a two-layer board with 35 µm copper thickness.

The layout separates the main power sections to support the different operating requirements of the circuit:

- The boost-converter power stage is implemented on the top layer.
- The continuous current-sink section is implemented on the bottom layer.
- Wide copper traces and polygon pours are used in high-current paths.
- Ground polygons are implemented on both layers and interconnected through stitching vias.

## Design Files

This directory is organized into two sections:

- `Schematic/` – Circuit schematic files and their corresponding documentation.
- `PCB/` – PCB layout files and related design outputs.

The included files provide the circuit-level and physical-layout documentation of the proposed VCCS architecture.
