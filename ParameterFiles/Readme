# Quadcopter UAV Build and Integration

Graduate quadcopter UAV build and integration project covering mechanical assembly, electrical wiring, ArduCopter flight-stack and flight-controller setup, ESC and brushless motor bring-up, ExpressLRS radio configuration, GPS integration, and final parameter tuning for stable, validated multirotor system operation.

---

## Overview

This project documents my end-to-end build, integration, configuration, and bring-up of a compact quadcopter UAV completed as part of a graduate drone systems project. The work focused on assembling the airframe, integrating the power and signal path across flight electronics, configuring the ArduCopter flight stack, bringing up the ESC/motor subsystem, setting up radio control and GPS, and validating the final configuration through bench-level setup and parameter tuning.

The project reflects hands-on work across embedded hardware integration, system configuration, signal/power wiring, flight-controller setup, and subsystem validation. It also demonstrates skills relevant to embedded systems, robotics, UAVs, hardware/software integration, bring-up, and test/validation engineering.

---

## What I Did

- Assembled and integrated a quadcopter UAV platform from component-level hardware
- Mounted and connected the frame, motors, ESCs, flight controller, battery, receiver, and GPS
- Performed electrical wiring and connector integration for power and signal paths
- Configured the ArduCopter flight stack and flight-controller parameters
- Set up and validated the ExpressLRS radio/controller link
- Integrated GPS hardware and verified final system-level setup
- Managed final configuration through a parameter file and bench bring-up workflow
- Captured final hardware images and preserved the final tuned configuration for documentation and reuse

---

## Project Highlights

- **Mechanical assembly:** frame-level integration of the multirotor platform and onboard components
- **Electrical integration:** battery, XT60 connector, ESC power path, signal routing, and onboard wiring management
- **Embedded configuration:** flight-controller setup and ArduCopter parameterization
- **Control-path bring-up:** ExpressLRS transmitter/receiver configuration and validation
- **Navigation subsystem integration:** GPS module mounting and connection
- **Validation workflow:** final parameter management, subsystem checks, wiring inspection, and integrated system bring-up

---

## System Architecture

The quadcopter system consists of the following major subsystems:

- **Airframe / mechanical structure**
- **4 brushless motors**
- **4 ESCs**
- **Flight controller running ArduCopter**
- **GPS module**
- **ExpressLRS receiver**
- **Handheld radio transmitter/controller**
- **LiPo battery and power connector**
- **Integrated onboard signal and power wiring**

At a high level:

- The **battery** supplies the main power path
- The **ESCs** drive the 4 brushless motors
- The **flight controller** coordinates motor outputs and vehicle behavior
- The **receiver** passes control inputs from the handheld transmitter
- The **GPS module** provides navigation/positioning data
- The overall system is configured and stabilized through **ArduCopter parameter setup**

---

## Hardware Used

This project involved integration of the following hardware categories:

- Carbon-fiber quadcopter frame
- 4 brushless motors
- 4 ESCs
- Flight controller
- GPS module
- ExpressLRS receiver
- RadioMaster transmitter/controller
- LiPo battery
- XT60 power connector
- Propellers
- Wiring, connectors, and mounting hardware

> Exact model details can be expanded further in `docs/hardware_bom.md`.

---

## Software / Firmware / Tools Used

This project used a UAV software and configuration stack centered around ArduCopter and associated setup tools.

### Core stack
- **ArduCopter / ArduPilot** — flight-stack and flight-controller configuration
- **ExpressLRS** — radio link setup
- **Mission Planner** — parameter configuration and system setup
- **ESC configuration ecosystem** — ESC setup / tuning workflow
- **Final ArduCopter parameter file** — preserved for final validated configuration

### Supporting workflow
- Bench-level bring-up and validation
- Configuration-driven integration across flight control, radio, power, and GPS subsystems
- Parameter management for repeatable final setup

---

## Mechanical Assembly

The multirotor platform was physically assembled by integrating the quadcopter frame, propulsion subsystem, battery mounting arrangement, GPS mast/module placement, and controller-linked receiver setup.

Mechanical work included:
- frame assembly
- mounting onboard electronics
- securing the battery and power connector path
- mounting GPS hardware
- arranging onboard wiring and electronics to support compact multirotor integration

The final images in this repo document the fully assembled system and subsystem placement.

---

## Electrical Wiring and Integration

A major part of the project involved hands-on electrical integration of the UAV hardware stack.

This included:
- routing battery power through the main connector path
- integrating ESCs with the propulsion subsystem
- connecting the flight controller to onboard hardware
- wiring the receiver and GPS interfaces
- organizing and securing the signal and power wiring around the compact frame
- visually validating connector orientation, power path consistency, and integration quality

This work required careful attention to:
- power routing
- connector polarity
- wiring integrity
- signal path stability
- clean mechanical/electrical packaging in a constrained embedded system form factor

---

## Flight Controller and Flight-Stack Setup

The drone was configured around an **ArduCopter-based flight-control workflow**.

Configuration work included:
- setting up the flight controller
- managing final flight parameters
- integrating the control stack with the receiver and GPS
- preparing the platform for stable multirotor operation
- preserving the final parameterized configuration for reproducibility

The included parameter file captures the final tuned system setup used for the completed build.

---

## ESC and Brushless Motor Bring-Up

The propulsion subsystem required integration of:
- ESCs
- brushless motors
- motor output path from the flight controller
- battery-powered motor drive path

The bring-up process focused on ensuring the propulsion chain was correctly assembled and ready for controlled multirotor operation.

This included:
- ESC/motor integration
- final propulsion hardware assembly
- system-level validation of the assembled motor subsystem
- readiness of the flight stack to drive the propulsion path under the configured setup

---

## Radio / Receiver Integration

The project also involved setup of the **ExpressLRS radio link** and integration with the onboard flight system.

This included:
- configuring the radio/controller setup
- linking the handheld transmitter/controller to the onboard receiver
- ensuring the control path was integrated into the flight-controller workflow
- documenting the controller used as part of the final system

The controller images included in the repo document the handheld radio used for the project.

---

## GPS Integration

A GPS module was integrated into the multirotor platform and mounted above the main airframe using a raised mast configuration.

This supported:
- clear subsystem organization
- clean placement relative to the flight stack
- final navigation-oriented system setup as part of the UAV build

The repo images document the GPS mounting and integration in the final assembled platform.

---

## Validation and Bring-Up

This repository reflects not just assembly, but also **system-level validation and bring-up work**.

Validation-oriented work included:
- physical inspection of integrated hardware
- configuration of the flight stack and final parameters
- confirmation of controller and onboard subsystem setup
- integration of power, control, and GPS subsystems into a unified platform
- final documentation of the stable build state

This is relevant to roles involving:
- hardware/software integration
- embedded system bring-up
- UAV system validation
- system configuration
- bench-level validation
- test and verification support

---

## Repository Contents

### Images
The `images/` folder contains final project images documenting:
- the handheld radio/controller
- the fully assembled drone
- drone/controller system context
- battery mounting
- flight electronics close-ups
- wiring and packaging details

### Parameters
The `ParameterFiles/` folder contains the final saved ArduCopter parameter file used for the configured build.

### Recommended additional docs
This repo can also be expanded with:
- `docs/system_overview.md`
- `docs/hardware_bom.md`
- `docs/wiring_notes.md`
- `docs/bringup_checklist.md`
- `docs/calibration_and_validation.md`
- `refs/external_tools_and_links.md`

---

## Current Repository Structure

```text
quadcopter-uav_drone-build-integration/
├── images/
│   ├── Controller1.jpeg
│   ├── Controller2.jpeg
│   ├── Controller3.jpeg
│   ├── Controller4.jpeg
│   ├── Drone1.jpeg
│   ├── Drone2.jpeg
│   ├── Drone3.jpeg
│   ├── Drone4.jpeg
│   ├── Drone5.jpeg
│   ├── Drone6.jpeg
│   └── Video1.mp4
└── ParameterFiles/
    └── paramsquadcopter_final.param
