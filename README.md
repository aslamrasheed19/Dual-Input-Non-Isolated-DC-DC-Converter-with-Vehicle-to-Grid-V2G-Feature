# Dual-Input Non-Isolated DC-DC Converter with V2G

A MATLAB/Simulink based B.Tech project on a **Dual-Input Non-Isolated DC-DC Converter with Vehicle-to-Grid (V2G) Feature** for solar PV and battery-powered electric vehicle applications.

## Overview

This project studies a dual-input single-output DC-DC converter that integrates two energy sources:

- Solar photovoltaic (PV) source
- Electric vehicle battery

The converter is designed to support multiple power-flow modes, including vehicle propulsion, solar-powered operation, battery-powered operation, solar PV battery charging, Vehicle-to-Grid (V2G), Vehicle-to-Vehicle (V2V), and regenerative braking.

## Features

- Dual-input power conversion
- Solar PV and battery integration
- Non-isolated DC-DC conversion
- Six operating modes
- Simultaneous utilization of available input sources
- Solar PV based battery charging
- Vehicle-to-Grid (V2G) operation
- Vehicle-to-Vehicle (V2V) power transfer
- Regenerative braking energy recovery
- MATLAB/Simulink based modelling and simulation

## Project Structure

```text
dual-input-disoc-v2g/
├── src/
│   └── dual_input_disoc_v2g.slx
├── docs/
│   ├── project-report.pdf
│   ├── project-presentation.pptx
│   └── research-paper.pdf
├── assets/
│   ├── simulink-model.png
│   └── hardware-prototype.png
├── README.md
├── REFERENCES.md
├── CITATION.cff
├── PROJECT_INFO.txt
└── .gitignore
```

## Simulation

The converter model is developed and simulated using **MATLAB/Simulink**.

The simulation covers the converter's different operating conditions and evaluates the corresponding power-flow behaviour and output response.

## Operating Modes

### 1. C-Boost Operation

Both input sources can contribute power to the load. This mode is used when higher output power is required.

### 2. Solar PV-Powered Operation

The solar PV source supplies power to the load while the battery is not used as the primary source.

### 3. Battery-Powered Operation

The battery supplies power to the load when solar PV power is unavailable or insufficient.

### 4. Solar PV Battery Charging

During parking, solar PV energy can be directed to charge the vehicle battery.

### 5. V2G / V2V Operation

During parking, available energy can be transferred:

- From the vehicle to the utility grid (V2G)
- From one electric vehicle to another electric vehicle (V2V)

### 6. Regenerative Braking

Energy recovered during regenerative braking can be transferred back to the vehicle battery.

## Applications

- Electric vehicles
- Hybrid renewable-energy systems
- Solar-powered EV charging
- Vehicle-to-Grid systems
- Vehicle-to-Vehicle energy transfer
- Battery energy management
- Regenerative braking systems
- Smart-grid connected electric vehicles

## Requirements

- MATLAB
- Simulink
- Required Simscape / electrical power-system libraries compatible with the model

Open the Simulink model from:

```text
src/dual_input_disoc_v2g.slx
```

## Reference

The project is based on the following technical work:

> **Dual Input Non-Isolated DC-DC Converter with Vehicle to Grid Feature**

The project documentation and research material included in this repository provide the detailed converter topology, operating modes, analysis, simulation, and hardware implementation.

## Author

**Muhammed Aslam A**  
B.Tech Project  
Department of Electrical Engineering

