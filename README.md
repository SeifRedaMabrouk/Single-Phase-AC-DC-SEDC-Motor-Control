# Single-Phase AC-DC Converter for SEDC Motor Speed Control

This repository contains a MATLAB/Simulink simulation model for controlling the speed of a Separately Excited DC (SEDC) Motor using a thyristor-based single-phase full-wave converter>

## Overview
The system models a fully-controlled bridge rectifier integrated with zero-crossing detection and custom firing pulse logic to regulate the armature voltage and control motor speed.

## Main Features
- **AC Power Source**: Input AC voltage supply.
- **Zero Cross Detector & Firing Logic**: Synchronizes pulse generation with grid frequency based on the adjustable firing angle.
- **AC/DC Rectifier**: Fully-controlled thyristor bridge delivering variable DC voltae.
- **SEDC Motor**: Simulates speed response in both `rad/s` and `RPM`.

## Requirements
- MATLAB / Simulink
- Simscape Electrical (Specialized Power Systems)

## How to Run
1. Open MATLAB and set the directory to this project folder.
2. Open `sedc_motor_control.slx` in Simulink.
3. Run the simulation and adjust the **Firing Angle** knob to control the motor speed.
