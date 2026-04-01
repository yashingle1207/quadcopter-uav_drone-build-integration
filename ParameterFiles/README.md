# Quadcopter UAV Build and Integration

Graduate quadcopter UAV build and integration project covering mechanical assembly, electrical wiring, ArduCopter flight-stack and flight-controller setup, ESC and brushless motor bring-up, ExpressLRS radio configuration, GPS integration, optional Wi-Fi telemetry, and final parameter tuning for stable, validated multirotor system operation.

---

## Overview

This repository documents my end-to-end build, integration, configuration, and bring-up of a compact quadcopter UAV completed as part of a graduate drone systems project. The work focused on assembling the airframe, integrating the power and signal path across flight electronics, configuring the ArduCopter flight stack, bringing up the ESC and motor subsystem, setting up the radio control link and GPS, and validating the final configuration through bench-level setup and parameter tuning.

The project reflects hands-on work across embedded hardware integration, system configuration, signal and power wiring, flight-controller setup, subsystem validation, and reproducible final configuration capture. It is relevant to embedded systems, robotics, UAV, hardware/software integration, bring-up, and test/validation engineering roles.

---

## What This Project Demonstrates

- Quadcopter mechanical assembly and subsystem integration
- Battery, ESC, and propulsion-path wiring
- Flight-controller setup and ArduCopter configuration
- ExpressLRS radio and receiver integration
- GPS installation and serial-interface integration
- Optional ESP32-based Wi-Fi telemetry setup
- Mission Planner-based validation and parameter verification
- Documentation of final build evidence and saved configuration artifacts

---

## Technical Scope

### Mechanical integration
- Airframe assembly
- Electronics packaging
- GPS mast placement
- Battery mounting and retention
- Wiring layout for serviceability and safe routing

### Electrical and interface integration
- XT60 and main battery power-path wiring
- ESC and motor integration
- Receiver-to-flight-controller UART wiring
- GPS and telemetry serial connections
- Power and ground distribution across the flight stack

### Embedded configuration
- ArduCopter flight-controller setup
- Mission Planner parameter configuration
- ELRS radio binding and control-link setup
- Flight-mode and arm/disarm channel mapping
- Final parameter-file preservation for reproducibility

### Validation and bring-up
- Bench validation with props removed
- Radio-bar and switch verification in Mission Planner
- Serial/UART configuration checks
- Motor-order, motor-direction, and arming-logic validation
- Final documented configuration baseline

---

## System Architecture

The completed system integrates the following major subsystems:

- Carbon-fiber mini quad airframe
- 4 brushless motors
- 4 ESCs
- ArduCopter-based flight controller
- GPS module
- ExpressLRS receiver
- RadioMaster Pocket transmitter
- LiPo battery and XT60 power connection
- Optional DroneBridge ESP32 telemetry module

At a high level:

- The **battery and power path** supply the flight electronics and propulsion chain
- The **flight controller** coordinates stabilization, control, serial integration, and motor outputs
- The **receiver** carries pilot commands from the radio transmitter
- The **GPS module** provides position and navigation input
- The **optional ESP32 telemetry bridge** supports Wi-Fi telemetry to a ground station
- The overall system is configured and validated through **Mission Planner**

---

## Repository Structure

```text
quadcopter-uav_drone-build-integration/
├── README.md
├── docs/
│   ├── diagrams/
│   │   ├── build_sequence_overview.png
│   │   ├── dronebridge_wiring.png
│   │   ├── elrs_receiver_wiring.png
│   │   └── system_architecture.png
│   ├── guides/
│   │   ├── 01_quadcopter_build_guide.pdf
│   │   ├── 02_wiring_and_interfaces_guide.pdf
│   │   ├── 03_radio_and_mission_planner_setup.pdf
│   │   └── 04_telemetry_and_final_configuration.pdf
│   └── images/
│       ├── Controller1.jpeg
│       ├── Controller2.jpeg
│       ├── Controller3.jpeg
│       ├── Controller4.jpeg
│       ├── Drone1.jpeg
│       ├── Drone2.jpeg
│       ├── Drone3.jpeg
│       ├── Drone4.jpeg
│       ├── Drone5.jpeg
│       └── Drone6.jpeg
├── ParameterFiles/
│   └── paramsquadcopter_final.param
└── refs/
    └── external_tools_and_links.md
