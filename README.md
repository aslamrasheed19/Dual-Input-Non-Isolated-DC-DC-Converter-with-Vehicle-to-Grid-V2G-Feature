# Dual-Input Non-Isolated DC-DC Converter with Vehicle-to-Grid Feature

A B.Tech Electrical & Electronics Engineering project implementing and documenting a **dual-input non-isolated DC-DC converter (DISOC)** for solar-PV/battery-powered electric-vehicle applications, with support for **vehicle-to-grid (V2G), vehicle-to-vehicle (V2V), solar charging, and regenerative-energy recovery**.

## Project Topic

**Power Electronics / Electric Vehicle Energy Management:** Dual-input single-output non-isolated DC-DC conversion for hybrid solar PV + battery EV systems with bidirectional power-flow capability.

## Short Description

The project studies a reconfigurable dual-input single-output converter that integrates two energy sources—solar PV and an EV battery—using a common converter structure. The documented design supports six operating types selected according to source availability, battery state of charge, and EV operating/parking condition. The project includes a MATLAB/Simulink model and a laboratory hardware prototype reported at 500 W.

The project report describes the motivation as reducing the need for multiple dedicated DC-DC converters, reducing system complexity, and enabling functions such as PV-to-battery charging, V2G/V2V power transfer, and regenerative braking through a common converter structure.

## Key Features

- Dual-input, single-output non-isolated DC-DC converter topology
- Solar PV and battery as the two input energy sources
- Six documented operating types:
  1. Combinational boost (C-boost)
  2. Solar PV-powered operation
  3. Battery-powered operation
  4. Battery charging from solar PV in parking mode
  5. V2G / V2V power transfer in parking mode
  6. Bidirectional rear-buck operation for regenerative energy recovery
- Simultaneous power transfer from PV and battery in C-boost operation
- V2G/V2V functionality through the converter and an appropriate inverter/interface
- MATLAB/Simulink simulation model
- Hardware prototype documentation
- BLDC motor/EV drive context and regenerative-braking study

## Repository Structure

```text
.
├── README.md
├── .gitignore
├── src/
│   └── dual_input_disoc_v2g.slx
├── assets/
│   ├── simulink-model.png
│   └── hardware-prototype.png
└── docs/
    ├── project-report.pdf
    └── project-presentation.pptx
```

## Software Requirements

- MATLAB / Simulink
- The supplied Simulink model was saved with **MATLAB R2020a**.
- The model uses blocks from the MATLAB/Simulink power-system/electric-drive environment; the report also identifies MATLAB/Simulink as the simulation platform.

> **Note:** The model may require the relevant Simscape Electrical / Specialized Power Systems and electric-drive libraries installed in your MATLAB release. Compatibility with newer MATLAB releases should be verified before simulation.

## How to Run the Simulation

1. Open MATLAB with the required Simulink/power-system libraries installed.
2. Open `src/dual_input_disoc_v2g.slx`.
3. Review the converter, PV, battery, control, measurement, and motor/load sections.
4. Run the model using the configured simulation settings.
5. Inspect the logged signals/scopes and compare the results with the project report in `docs/project-report.pdf`.

The supplied model is configured for a variable-step simulation and has a stop time of 7 s.

## Project Documentation

- **Project report:** `docs/project-report.pdf` — full B.Tech design report covering the problem, methodology, converter modes, component design, simulation, hardware implementation, cost, advantages, conclusion, and appendix.
- **Presentation:** `docs/project-presentation.pptx` — project presentation used for the academic project.

## Reference  

>G. G. Kumar and S. Kumaravel, "Dual-Input Non-isolated DC-DC Converter with Vehicle to Grid Feature," in IEEE Journal of Emerging and Selected Topics in Power Electronics, doi: 10.1109/JESTPE.2020.3042967.  

## Team

- Abhinand U D — PRN19EE002
- Muhammed Aslam A — PRN19EE030
- Sreehari T — PRN19EE043
- Thanveer Shahal — PRN19EE044

**Project Guide:** Mrs. Ajisha S, Assistant Professor, Department of Electrical & Electronics Engineering, College of Engineering Perumon.

## Academic Context

B.Tech, Electrical & Electronics Engineering, College of Engineering Perumon, under A P J Abdul Kalam Technological University, 2019–2023.

