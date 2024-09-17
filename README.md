# 🚦Traffic-Light-Controller-Using-Verilog

# Introduction
The Traffic Light Controller project demonstrates the design and implementation of a traffic signal management system using Verilog HDL. This system is crucial for controlling traffic lights at intersections, ensuring safe and efficient traffic flow. The controller uses a Finite State Machine (FSM) to manage the timing and sequencing of traffic lights (Red, Yellow, Green) for different traffic directions. This project is suitable for FPGA implementations and digital system design practice.

# Overview
This repository contains a Verilog HDL implementation of a traffic light control system. The design is based on an FSM and supports configurations for two-way or four-way intersections. The project also includes a testbench for verifying the functionality through simulation.

# Features
FSM-Based Design: Implements traffic light control using a Finite State Machine for managing light states.

Two-Way and Four-Way Intersections: Configurable for both types of intersections.

Customizable Timing: Allows for adjustments in the duration of Red, Yellow, and Green lights.

Pedestrian Mode: Optional functionality for pedestrian crossings.

Simulation Testbench: Includes a testbench for verifying the design's behavior in a simulated environment.

# Setup and Simulation
𝗩𝗲𝗿𝗶𝗹𝗼𝗴 𝗧𝗼𝗼𝗹𝘀

1.Install a Verilog-compatible tool like ModelSim or Vivado.

2.Open the traffic_light_controller.v and fsm.v files in the tool.

3.Compile and simulate the design using the provided testbench (traffic_light_tb.v) to verify functionality.

𝗦𝗶𝗺𝘂𝗹𝗮𝘁𝗶𝗼𝗻

1.Load the testbench file in your Verilog simulation tool.

2.Run the simulation to observe the traffic light controller's behavior and verify that it meets the desired specifications.

# Customization

Adjust the timing parameters in the Verilog code to change the duration of each traffic light phase.

Modify the FSM logic to add or change functionality, such as additional traffic light sequences or pedestrian modes.
