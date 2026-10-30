# Circuit Simulation

This directory contains the LTspice simulation files developed for the analysis and evaluation of the Multi-Range Voltage-Controlled Current Sink (VCCS).

The simulations were performed to investigate the electrical behavior of the proposed current-control circuits, examine feedback operation, and evaluate the transient response of the system.

## 1. Linear Current-Sink Simulation

The continuous current-sink stage was modeled and simulated in LTspice.

The simulation focuses on:

- Operational amplifier and MOSFET-based current regulation.
- Current-sense resistor configurations.
- Programmable reference voltage.
- Current response under different operating conditions.

## 2. Boost Converter Simulation

The high-current section was modeled using a boost-converter topology.

The simulation examines:

- Boost-converter switching behavior.
- Inductor current characteristics.
- Current-sensing and feedback circuitry.
- Interaction between the power stage and control loop.

## 3. Closed-Loop Current Control

A feedback control structure was developed to regulate the inductor current.

The control architecture includes:

- Differential current-sensing amplifier.
- Integrator-based error processing.
- Triangular carrier waveform generation.
- PWM signal generation.
- MOSFET gate-driving stage.

A switching frequency of 100 kHz was considered in the PWM generation stage.

## 4. Transient Response Analysis

Transient simulations were performed to investigate the response of the current-control loop to changes in the reference command.

The documented simulation results illustrate current transitions between approximately 10 A and 1 A.

The compensation network was also investigated to improve the transient response and reduce overshoot.

## Simulation Files

The `LTspice/` directory contains the circuit simulation projects, supporting files, and relevant simulation results.

These files provide a basis for reviewing the circuit behavior and control strategy.

**Note:** The presented results are based on circuit simulations and should be distinguished from experimental measurements or hardware validation.
