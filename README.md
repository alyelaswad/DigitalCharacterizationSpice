# DigitalCharacterizationSpice

## Overview
This repository contains the SPICE simulations and design files for the CSCE 3303 – Fundamental Microelectronics Fall 2024 project. The goal of the project is to characterize the performance parameters of digital circuits using SPICE simulations. The project is divided into two main parts:

- **Part A**: Characterization of a CMOS inverter using LTspice simulations, focusing on voltage transfer characteristics (VTC), propagation delay times, and power consumption.
- **Part B**: Design, simulation, and characterization of a **4-to-1 Multiplexer (MUX)** and **1-to-4 Demultiplexer (DEMUX)**.

The simulations are performed using **LTspice**, a free SPICE simulator. This project aims to investigate and analyze the performance of the specified circuits, including their propagation delay and average power consumption.

## Project Description

### Part A: CMOS Inverter Characterization

In Part A, the task is to perform a detailed characterization of a **CMOS inverter** using SPICE simulations. The objectives include:
1. **Voltage Transfer Characteristics (VTC)**: The VTC of the CMOS inverter will be computed at various input voltage values using **0.18-μm CMOS technology**.
2. **Propagation Delay**: The dynamic response of the inverter will be analyzed by applying a pulse at the input and measuring the propagation delay times (both high-to-low and low-to-high).
3. **Power Consumption**: The average power dissipation of the inverter will be calculated at different input conditions, considering the effects of rise and fall times.

The simulations will be conducted twice:
- **Matched Design**: Where the width of the NMOS and PMOS transistors are designed to account for the difference in mobility between electrons and holes, such that the current drive capabilities of both transistors are balanced. Specifically, the width of the PMOS transistor is scaled by the ratio \( \frac{\mu_n}{\mu_p} \) compared to the NMOS transistor.
- **Minimum Area**: Where the design aims to minimize the area by adjusting the transistor sizes.

### Part B: 4-to-1 Multiplexer (MUX) and 1-to-4 Demultiplexer (DEMUX)

In Part B, the focus shifts to the design and analysis of two digital circuits:
- **4-to-1 Multiplexer (MUX)**: A digital circuit that selects one of four inputs based on two control signals. 
- **1-to-4 Demultiplexer (DEMUX)**: A circuit that takes a single input and routes it to one of four outputs based on two control signals.

#### 4-to-1 Multiplexer (MUX)
1. Design the MUX circuit using **0.18-μm CMOS technology**.
2. Create a SPICE netlist for the MUX.
3. Simulate the MUX for various input combinations and analyze its functionality.
4. Measure propagation delay times and average power consumption.

#### 1-to-4 Demultiplexer (DEMUX)
1. Design the DEMUX circuit using **0.18-μm CMOS technology**.
2. Create a SPICE netlist for the DEMUX.
3. Simulate the DEMUX for various input combinations and analyze its functionality.
4. Measure propagation delay times and average power consumption.

### SPICE Simulations
For both Part A and Part B, the SPICE netlists will include the necessary components such as resistors, capacitors, voltage sources, and MOSFETs. Control statements will be used to perform the necessary analyses such as operating point, transient, and DC analysis. The results will be interpreted with respect to the propagation delay times and average power consumption.

### Simulation Files
- **Netlist Files**: SPICE netlists for each design (CMOS inverter, MUX, DEMUX).
- **Simulation Results**: Plots and graphs for voltage transfer characteristics, propagation delay, and power dissipation.

## Requirements

- **LTspice**: SPICE simulator used for all simulations. Available for free from Analog Devices [here](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html).
- **Transistor Models**: The simulations will use standard MOSFET models (Level 1) for **0.18-μm CMOS technology**.

## Team Members
- **Aly Elaswad**
- **Arwa Abdelkarim**
- **Kareem Elnaghy** 


