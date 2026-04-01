# Quadcopter UAV Build and Integration

Graduate quadcopter UAV build and integration project covering mechanical assembly, electrical wiring, ArduCopter flight-controller setup, ESC and brushless motor bring-up, ExpressLRS radio configuration, GPS integration, optional ESP32-based Wi-Fi telemetry, and final parameter tuning for stable, validated multirotor system operation.

---

## Project At-a-Glance

**Focus areas:** embedded hardware integration, UAV bring-up, wiring and power-path integration, ArduCopter configuration, radio/receiver setup, Mission Planner validation, telemetry integration, and final configuration preservation.

**Key technologies:** ArduCopter, Mission Planner, ExpressLRS, EdgeTX, BLHeli_S, DroneBridge ESP32, UART-based subsystem integration.

**Repository highlights:**
- Build and integration guides
- Wiring and architecture diagrams
- Final build evidence images
- Saved final parameter file
- Repeatable setup and validation path

---

## Overview

This repository documents my end-to-end build, integration, configuration, and bring-up of a compact quadcopter UAV completed as part of a graduate drone systems project. The work focused on assembling the airframe, integrating the power and signal path across flight electronics, configuring the ArduCopter flight stack, bringing up the ESC and motor subsystem, setting up the radio control link and GPS, and validating the final configuration through bench-level setup and parameter tuning.

The project reflects hands-on work across embedded hardware integration, system configuration, signal and power wiring, flight-controller setup, subsystem validation, and reproducible final configuration capture. It is especially relevant to embedded systems, robotics, UAV, hardware/software integration, bring-up, validation, and manufacturing test-oriented engineering roles.

---

## For Recruiters and Hiring Teams

This project demonstrates practical experience across:

- embedded hardware bring-up
- flight-controller and firmware configuration
- electrical wiring and subsystem integration
- UART-based receiver and telemetry integration
- radio setup and control-link validation
- GPS and navigation-related system integration
- bench-level test and verification workflows
- documentation of final build evidence and configuration artifacts

It is a hands-on build and validation project rather than a simulation-only exercise, and the repository is structured to show both the final integrated hardware and the repeatable setup path used to reach the validated system state.

---

## Key Skills Demonstrated

- Quadcopter mechanical assembly and electronics packaging
- Battery, XT60, ESC, and propulsion-path wiring
- Flight-controller setup and ArduCopter configuration
- ExpressLRS transmitter/receiver integration
- GPS installation and serial-interface integration
- Optional ESP32-based Wi-Fi telemetry setup
- Mission Planner-based validation and parameter verification
- Final `.param` configuration preservation for reuse and rebuilds
- Technical documentation for reproducible system bring-up

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
