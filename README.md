# Close-Loop Stepper Motor Driver Controller Project

This repository contains the source code for a close-loop stepper motor driver controller project. The project uses Simulink and Simscape for simulation and an MKS Servo 42D board as the real-world hardware driver.

## Software Components

- Simulink model: [Plant Model](Sim.slx)

## Hardware Components

- MKS Servo 42D board
- Usongshine  17HS4401S Step Motor

## Controller Overview
The field-oriented control (FOC) scheme will be implemented to precise control of torque and other parameters.

### Implementation Details

The implementation details of the driver board are provided in the attached Simulink and Simscape models. These models demonstrate the simulation and real-time operation of the controller on the MKS Servo 42D board.