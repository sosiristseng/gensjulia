---
title: Hardware and Robotics
created: 2025-12-04, 12:33:20
modified: 2025-12-04, 15:47:58
---

> Controlling hardware and robots in Julia

## APIs and bindings

- [Instruments.jl](https://github.com/BBN-Q/Instruments.jl) : A package for controlling laboratory instruments through Julia over TCPIP/GPIB/USB/Serial, wrapped around the NI-VISA library (which needs to be separately installed) similar to PyVISA and has some starts towards making it easier to write custom instrument drivers.
- [NIDAQ.jl](https://github.com/JaneliaSciComp/NIDAQ.jl) : This package provides an interface to NIDAQmx - National Instruments' driver for their data acquisition boards.

## Computer-assisted design / manufacture (CAD/CAM)

- [Devices.jl](https://github.com/PainterQubits/Devices.jl) : For simplified generation of device CAD files for superconducting device design.
- [LTspice.jl](https://github.com/cstook/LTspice.jl) : A Julia interface to [LTspice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html).

### Semiconductor and Transistor

- [MOSLab.jl](https://github.com/Rapos0/MOSLab.jl) : Semiconductor to Transistor Level Modeling in Julia.

## Embedded Systems

- [Embedded Systems](https://en.wikipedia.org/wiki/Category:Embedded_systems)
- [Julia embedded](https://github.com/Julia-Embedded) organization
- [Julia berry](https://github.com/JuliaBerry) organization

---

- [JuliaBerry.jl](https://github.com/JuliaBerry/JuliaBerry.jl) : An omnibus package with a high level API for controlling peripherals on the Raspberry Pi computer.
- [LibSerialPort.jl](https://github.com/JuliaIO/LibSerialPort.jl) : Julia wrapper for the [libserialport](https://github.com/sigrokproject/libserialport) C library.
- [PiCraft.jl](https://github.com/JuliaBerry/PiCraft.jl) : Manipulate Minecraft on the Raspberry Pi from Julia.
- [PiGPIO.jl)](https://github.com/JuliaBerry/PiGPIO.jl) : Manage external hardware using GPIO pins on the Raspberry Pi.
- [SerialPorts.jl)](https://github.com/JuliaIO/SerialPorts.jl) : SerialPort IO streams in Julia backed by Python's `pySerial`. (With Python dependencies)

## Robots

- [Julia robotics](https://github.com/JuliaRobotics) organization

---

- [Caesar.jl](https://github.com/JuliaRobotics/Caesar.jl) : Robot toolkit: Towards non-parametric and parametric navigation solutions.
- [MotionCaptureJointCalibration.jl](https://github.com/JuliaRobotics/MotionCaptureJointCalibration.jl) : Kinematic calibration for robots using motion capture data.
- [RigidBodyDynamics.jl](https://github.com/JuliaRobotics/RigidBodyDynamics.jl) : Julia implementation of various rigid body dynamics and kinematics algorithms.
- [RigidBodySim.jl](https://github.com/JuliaRobotics/RigidBodySim.jl) : Simulation and visualization of articulated rigid body systems in Julia.
- [RobotOS.jl](https://github.com/jdlangs/RobotOS.jl) : Julia interface to [ROS](http://wiki.ros.org/) (Robot Operating System).
- [StrandbeestRobot.jl](https://github.com/rdeits/StrandbeestRobot.jl) : Simulation of a 12-legged parallel walking mechanism in Julia, inspired by Theo Jansen's Strandbeest.
- [TrajectoryOptimization.jl](https://github.com/RoboticExplorationLab/TrajectoryOptimization.jl) : A fast trajectory optimization library written in Julia. [JuliaCon 2025](https://youtu.be/uHSyZZuz5Wg)
