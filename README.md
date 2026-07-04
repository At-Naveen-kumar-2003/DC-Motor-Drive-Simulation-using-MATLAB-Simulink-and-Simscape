# DC Motor Drive Simulation using MATLAB Simulink and Simscape

## Overview

This project demonstrates the modeling and simulation of a Permanent Magnet DC (PMDC) Motor using MATLAB Simulink and Simscape Electrical. The objective is to analyze the motor's electrical and mechanical behavior by measuring voltage, current, and rotational speed under different supply voltages.

The simulation is developed using MATLAB R2026a and follows a physical modeling approach with Simscape components.

---

## Objectives

- Model a Permanent Magnet DC Motor using Simscape.
- Measure armature voltage, current, and motor speed.
- Compare motor performance for 12 V and 24 V DC supply.
- Understand the effect of supply voltage on motor characteristics.

---

## Software Used

- MATLAB R2026a
- Simulink
- Simscape
- Simscape Electrical

---

## Components Used

- DC Voltage Source
- Current Sensor
- Voltage Sensor
- Permanent Magnet DC Motor
- Ideal Rotational Motion Sensor
- Inertia
- Mechanical Rotational Reference
- Electrical Reference
- Solver Configuration
- PS-Simulink Converter
- Mux
- Scope

---

## Model Description

The DC motor is supplied by a DC voltage source through a current sensor. A voltage sensor is connected across the motor terminals to monitor the applied voltage. The motor shaft is connected to an Ideal Rotational Motion Sensor and an Inertia block to observe the motor's rotational characteristics. Physical signals are converted into Simulink signals using PS-Simulink Converters and displayed using a Scope.

---

## Simulation Cases

### Case 1: 12 V Supply

- Supply Voltage: 12 V
- Measured Parameters:
  - Motor Voltage
  - Armature Current
  - Angular Speed

### Case 2: 24 V Supply

- Supply Voltage: 24 V
- Measured Parameters:
  - Motor Voltage
  - Armature Current
  - Angular Speed

---

## Results

The simulation shows that increasing the supply voltage from 12 V to 24 V increases:

- Motor speed
- Armature current
- Developed electromagnetic torque
- Mechanical output power

The motor reaches steady-state operation after a short transient period.

---

## Applications

- Industrial Automation
- Electric Vehicles
- Robotics
- Conveyor Systems
- Pumps
- Fans
- Home Appliances
- Mechatronic Systems

---

## Learning Outcomes

Through this project, I gained practical experience in:

- MATLAB Simulink modeling
- Simscape Electrical
- Permanent Magnet DC Motor modeling
- Electrical and mechanical system integration
- Voltage and current measurement
- Speed measurement using rotational sensors
- Physical signal conversion using PS-Simulink Converter
- Simulation and performance analysis of electromechanical systems

---


