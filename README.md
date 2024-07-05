# Vehicle Interface Packages

This repository contains all the ROS packages related to vehicle interface and control.

## Repository Structure

```
vehicle_interface_packages
├── ros2_socketcan
└── SD-VehicleInterface
```

## Objective

The purpose of this repository is to house the packages related to the vehicle interface and control for StreetDrone vehicles. These packages facilitate seamless communication between the vehicles and ROS2-based self-driving software stacks, enabling effective vehicle management and control in both real and simulated environments.

### ros2_socketcan

The `ros2_socketcan` package is designed to handle the communication over CAN bus in ROS2. It includes:
- Implementation of ROS2 nodes for interfacing with CAN bus.
- Message definitions and utilities for CAN communication.
- Support for SocketCAN protocol to facilitate vehicle-to-computer communication.

### SD-VehicleInterface

The `SD-VehicleInterface` package is responsible for the interface between the StreetDrone vehicles and the ROS2 software stack. It includes:
- Configuration and setup scripts for integrating the StreetDrone Xenos Control Unit (XCU).
- Nodes and utilities for controlling vehicle dynamics and monitoring vehicle state.
- Support for various sensors and actuators used in StreetDrone vehicles.
- Simulation support for testing and development in Gazebo.

## Submodules

The packages in this repository are included as submodules. Ensure you initialize and update the submodules when you clone this repository:

```sh
git submodule init
git submodule update
```

## Compatibility

These packages are designed to work seamlessly both in real vehicle environments and in simulated settings, ensuring flexibility and robustness in various testing and operational scenarios.

---
