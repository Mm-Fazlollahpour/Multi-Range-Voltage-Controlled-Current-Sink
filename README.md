# Multi-Range Voltage-Controlled Current Sink (VCCS)

<p align="center">
  <img src="Images/Front-PCB.png" alt="VCCS PCB - Front View" width="48%">
  <img src="Images/Rear-PCB.png" alt="VCCS PCB - Rear View" width="48%">
</p>

<p align="center">
  <em>Two-layer PCB design – Front and Rear views</em>
</p>

## Project Overview

This project focuses on the design and simulation of a multi-range Voltage-Controlled Current Sink (VCCS), intended to operate as a programmable active load for the electrical characterization and testing of integrated circuits and electronic devices.

The proposed architecture combines a precision linear current-sink stage for low and intermediate current ranges with a boost-converter-based current regulation stage for high-current operation.

The system incorporates analog feedback control, selectable current-sensing networks, PWM-based regulation, and an STM32F103RCT6 microcontroller for programmable reference generation and range management.

## Key Features

- Multi-range programmable current-sink architecture
- Operational amplifier and MOSFET-based linear current regulation
- Boost-converter-based high-current regulation
- Differential current-sensing and feedback circuitry
- PWM-based control with a 100 kHz switching frequency
- STM32F103RCT6-based digital control
- LTspice circuit modeling and simulation
- Two-layer PCB design using Altium Designer

## System Architecture

The design consists of two complementary current-regulation paths:

**1. Linear Current-Sink Stage**

An operational amplifier and MOSFET-based feedback circuit regulate the current through selectable current-sense resistors. This stage is intended for low and intermediate current ranges.

**2. Boost-Based Current-Sink Stage**

A boost-converter power stage is used for the high-current operating range. Inductor-current sensing, an integrator-based
