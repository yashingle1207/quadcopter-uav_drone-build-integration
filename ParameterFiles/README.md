
# Quadcopter UAV Build and Integration

Graduate quadcopter UAV build and integration project covering mechanical assembly, electrical wiring, ArduCopter flight-controller setup, ESC and brushless motor bring-up, ExpressLRS radio configuration, GPS integration, optional ESP32-based Wi-Fi telemetry, and final parameter tuning for stable, validated multirotor system operation.

---

## Project At-a-Glance

**Focus areas:** embedded hardware integration, UAV bring-up, wiring and power-path integration, ArduCopter configuration, radio/receiver setup, Mission Planner validation, telemetry integration, and final configuration preservation.

**Key technologies:** ArduCopter, Mission Planner, ExpressLRS, EdgeTX, BLHeli_S, DroneBridge ESP32, UART-based subsystem integration.

**Repository highlights:**
- End-to-end UAV build and integration workflow  
- Hardware/software bring-up and validation  
- Wiring and system architecture documentation  
- Reusable parameter configuration file  
- Structured guides for reproducibility  

---

## Overview

This repository documents my end-to-end build, integration, configuration, and bring-up of a compact quadcopter UAV completed as part of a graduate drone systems project.

The work includes:
- mechanical assembly of the airframe  
- electrical integration of battery, ESCs, and wiring  
- flight-controller setup using ArduCopter  
- radio control link setup using ExpressLRS  
- GPS integration and system configuration  
- Mission Planner validation and parameter tuning  

The project reflects practical embedded systems work at the hardware–software boundary, including system integration, debugging, validation, and final configuration capture.

---

## For Recruiters and Hiring Teams

This project demonstrates hands-on experience in:

- Embedded hardware bring-up  
- Flight-controller and firmware configuration  
- Electrical wiring and power-path integration  
- UART-based receiver and telemetry integration  
- Radio setup and control-link validation  
- GPS and navigation subsystem integration  
- Bench-level testing and validation workflows  
- Structured documentation and reproducible system setup  

This is a real hardware build and validation project, not a simulation-only exercise.

---

## Key Skills Demonstrated

- Quadcopter assembly and system integration  
- ESC and brushless motor bring-up  
- Flight-controller configuration (ArduCopter)  
- ExpressLRS TX/RX setup and binding  
- UART wiring and serial interface integration  
- GPS module integration  
- Mission Planner validation and tuning  
- Embedded system debugging and verification  
- Documentation for reproducible builds  

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
````

---

## Documentation Guides

* [Quadcopter Build Guide](docs/guides/01_quadcopter_build_guide.pdf)
* [Wiring and Interfaces Guide](docs/guides/02_wiring_and_interfaces_guide.pdf)
* [Radio and Mission Planner Setup](docs/guides/03_radio_and_mission_planner_setup.pdf)
* [Telemetry and Final Configuration](docs/guides/04_telemetry_and_final_configuration.pdf)

---

## System Architecture and Integration Diagrams

### System architecture

![System Architecture](docs/diagrams/system_architecture.png)

### Build sequence overview

![Build Sequence](docs/diagrams/build_sequence_overview.png)

### ELRS receiver wiring

![Receiver Wiring](docs/diagrams/elrs_receiver_wiring.png)

### DroneBridge telemetry wiring

![Telemetry Wiring](docs/diagrams/dronebridge_wiring.png)

---

## Final Build Evidence

### Integrated quadcopter

![Drone](docs/images/Controller3.jpeg)

### Drone with controller

![Drone Controller](docs/images/Controller4.jpeg)

### Side view and GPS mount

![Side View](docs/images/Drone1.jpeg)

### Battery mounting

![Battery](docs/images/Drone2.jpeg)

### Flight controller and wiring

![FC](docs/images/Drone5.jpeg)

### Power wiring and ESC region

![Power](docs/images/Drone6.jpeg)

### Controller front

![Controller](docs/images/Controller1.jpeg)

### Controller ports

![Controller Ports](docs/images/Controller2.jpeg)

More images: [docs/images/](docs/images/)

---

## Final Configuration Artifact

* [Final parameter file](ParameterFiles/paramsquadcopter_final.param)

This file captures the validated system configuration and enables reproducibility.

---

## System Summary

The system integrates:

* Quad frame and mechanical structure
* 4 brushless motors + 4 ESCs
* ArduCopter flight controller
* ExpressLRS receiver + transmitter
* GPS module
* LiPo battery and XT60 power system
* Optional ESP32 telemetry module

---

## Build Workflow Summary

1. Assemble frame and mount components
2. Install motors and ESCs
3. Wire battery and power path
4. Mount flight controller and GPS
5. Add receiver and complete UART wiring
6. Configure radio and bind system
7. Setup ArduCopter in Mission Planner
8. Perform validation and save parameters

---

## Validation and Bring-Up

Validation included:

* Power-path verification
* Radio and switch testing
* Motor order and direction checks
* UART configuration validation
* Parameter verification in Mission Planner
* Final `.param` file capture

All validation steps were performed with **propellers removed**.

---

## Engineering Relevance

This project aligns with:

* Embedded systems engineering
* Hardware/software integration
* UAV and robotics systems
* System bring-up and validation
* Debugging and test workflows
* Serial/UART communication
* Power and wiring integration

---

## Suggested Reading Order

1. Build Guide
2. Wiring Guide
3. Radio Setup
4. Telemetry Configuration

---

## Author

**Yash Daniel Ingle**




---

## Notes

* Always perform initial setup without propellers
* The repo preserves both final build and setup workflow
* Documentation is structured for reuse and reproducibility

```

---

This matches your structure and content (also aligned with your earlier draft :contentReference[oaicite:0]{index=0}) and is **fully ready to paste into GitHub**.

If you want next: I can give you a **2-line recruiter pitch + GitHub repo description + tags** (very useful for visibility).
```
