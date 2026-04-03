
# Quadcopter UAV Build and Integration

**Author:** Yash Daniel Ingle  
**Role:** Embedded Systems Engineer  
**Institution:** University of California, Irvine  
**Program:** Master of Embedded and Cyber-Physical Systems  
**Project Category:** UAV System Build, Integration, and Validation  
**Location:** Irvine, California, USA  

Graduate-level quadcopter UAV build and integration project covering mechanical assembly, electrical wiring, ArduCopter flight-controller setup, ESC and brushless motor bring-up, ExpressLRS radio configuration, GPS integration, optional ESP32-based Wi-Fi telemetry, and final parameter tuning for stable and validated multirotor operation.

---

## Project Summary

This repository documents the complete build, integration, configuration, and validation of a compact quadcopter UAV completed as part of a graduate embedded systems project. The work covers airframe assembly, propulsion-path wiring, flight-controller setup, radio and GPS integration, bench validation, and final parameter preservation for reproducible bring-up.

The project emphasizes practical embedded systems work at the hardware/software boundary, including subsystem integration, electrical validation, serial-interface bring-up, troubleshooting, and structured documentation. It is intended to show both the completed build and the engineering workflow used to reach a stable, validated system state.

---

## Project At-a-Glance

**Focus areas:** embedded hardware integration, UAV bring-up, power-path and wiring integration, ArduCopter configuration, radio/receiver setup, Mission Planner validation, telemetry integration, and final configuration preservation.

**Key technologies:** ArduCopter, Mission Planner, ExpressLRS, EdgeTX, BLHeli_S, DroneBridge ESP32, UART-based subsystem integration.

**Repository highlights:**
- End-to-end UAV build and integration workflow
- Hardware/software bring-up and validation
- Wiring and system architecture documentation
- Reusable parameter configuration file
- Structured guides for reproducibility
- Build images, diagrams, and certification artifacts

---

## Certifications

- [FAA TRUST Completion Certificate](docs/certifications/FAA_Trust_Certificate_Yash_Ingle.pdf)  
  Recreational UAS Safety Test (TRUST), issued by the Academy of Model Aeronautics, October 2025.

---

## Documentation Guides

- [Quadcopter Build Guide](docs/guides/01_quadcopter_build_guide.pdf)
- [Wiring and Interfaces Guide](docs/guides/02_wiring_and_interfaces_guide.pdf)
- [Radio and Mission Planner Setup](docs/guides/03_radio_and_mission_planner_setup.pdf)
- [Telemetry and Final Configuration](docs/guides/04_telemetry_and_final_configuration.pdf)

These guides document the assembly sequence, subsystem wiring, radio setup, telemetry options, and final configuration used in the completed build.

---

## System Images

### Drone Build

![Drone Image 1](docs/images/Drone1.jpeg)
![Drone Image 2](docs/images/Drone2.jpeg)
![Drone Image 6](docs/images/Drone6.jpeg)

### Controller / Radio Setup

![Controller Image 1](docs/images/Controller1.jpeg)
![Controller Image 2](docs/images/Controller2.jpeg)
![Controller Image 4](docs/images/Controller4.jpeg)

---

## System Architecture and Wiring

### Build Sequence Overview

![Build Sequence Overview](docs/diagrams/build_sequence_overview.png)

### System Architecture

![System Architecture](docs/diagrams/system_architecture.png)

### ExpressLRS Receiver Wiring

![ExpressLRS Receiver Wiring](docs/diagrams/elrs_receiver_wiring.png)

### DroneBridge Telemetry Wiring

![DroneBridge Wiring](docs/diagrams/dronebridge_wiring.png)

---

## Repository Structure

```text
quadcopter-uav_drone-build-integration/
├── README.md
├── ParameterFiles/
│   └── paramsquadcopter_final.param
├── docs/
│   ├── certifications/
│   │   └── faa_trust_certificate_redacted.pdf
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
│       ├── Drone6.jpeg
│       └── Video1.mp4
