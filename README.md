# Design of an Electric Vehicle using MATLAB/Simulink

## Overview

This project focuses on the development of a complete Electric Vehicle (EV) model using MATLAB/Simulink. The model simulates the behavior of an electric vehicle powertrain and evaluates vehicle performance under different drive cycles. The simulation includes battery modeling, motor control, vehicle dynamics, transmission system, and state-of-charge (SOC) estimation.

## Objectives

- Develop a complete EV powertrain model in MATLAB/Simulink.
- Simulate vehicle performance using standard drive cycles.
- Calculate vehicle speed, distance traveled, and battery State of Charge (SOC).
- Analyze energy consumption and vehicle behavior under varying operating conditions.

## System Architecture

The EV model consists of the following major subsystems:

### Drive Cycle Source
Provides reference vehicle speed inputs using:
- FTP75 Drive Cycle
- Artemis Motorway 150 km/h Drive Cycle
- User-defined Signal Builder input

### Longitudinal Driver
Generates acceleration and braking commands by comparing reference speed and actual vehicle speed.

### Controller and Motor Drive
- PWM Controller
- H-Bridge Controller
- DC Motor (400 V)

### Transmission and Vehicle Body
- Simple Gear Transmission
- Rear Wheel Drive (RWD) Configuration
- Vehicle Dynamics Model

### Battery System
- 600 V Battery Model
- SOC Estimation using Coulomb Counting Method
- Current Monitoring and Energy Consumption Analysis

## Model Features

- EV longitudinal vehicle dynamics simulation
- Multiple drive cycle implementation
- Battery State of Charge estimation
- DC motor control using PWM and H-Bridge
- Vehicle speed tracking
- Distance calculation
- Energy consumption analysis

## Tools Used

- MATLAB
- Simulink
- Simscape
- Simscape Electrical
- Powertrain Blockset

## Results

Simulation results were obtained using the FTP75 drive cycle.

- Battery Voltage: 600 V
- Motor Voltage: 400 V
- Battery Capacity: 150 Ah
- Distance Travelled: 27 km
- Final State of Charge (SOC): 87.78%

The vehicle successfully followed the reference drive cycle while demonstrating realistic battery discharge characteristics and vehicle dynamics.

## Key Learnings

- Electric vehicle powertrain modeling
- Battery and SOC estimation techniques
- Drive cycle implementation
- Vehicle longitudinal dynamics
- Simulink system-level modeling
- EV energy consumption analysis

## Repository Contents

- Simulink Model (.slx)
- Project Documentation
- Simulation Results
- Drive Cycle Analysis

## Author

Rajesh R

MATLAB | Simulink | Electric Vehicle Design | Battery Systems | Vehicle Dynamics
