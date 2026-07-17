# OpenPowerLab

OpenPowerLab is a modular hardware platform for developing, testing and validating digital control algorithms for power electronic converters.

The project is designed as a reusable development platform rather than a single converter, allowing experimentation with different power topologies, sensing techniques and control strategies.

## Objectives

- Modular hardware architecture
- Digital control using STM32 microcontrollers
- Separation between Control Board and Power Board
- Hardware protection independent of the control algorithm
- Easy debugging and laboratory experimentation

## Current Status

### Control Board
- [ ] Architecture definition
- [ ] Schematic
- [ ] PCB
- [ ] Firmware

### Power Board
- [x] System specification
- [ ] Schematic
- [ ] PCB
- [ ] Assembly
- [ ] Validation

## First Prototype

Synchronous Buck Converter

| Parameter | Value |
|-----------|-------|
| Input Voltage | 20–28 V |
| Output Voltage | 2–12 V |
| Output Current | 3 A |
| Switching Frequency | 60–100 kHz |
| Control | Digital (STM32) |
| Current Sensing | Shunt resistor + CSA |
| Protection | Hardware over-current protection |

## Planned Features

- Synchronous Buck
- Boost
- Buck-Boost
- DC/AC Inverter
- AC/DC PFC
- Current observers
- Sensorless current estimation
- Digital control algorithms
- Data acquisition and logging

## Repository Structure

```
/
├── docs/
├── hardware/
│   ├── control_board/
│   └── power_board/
├── firmware/
├── simulations/
└── README.md
```

