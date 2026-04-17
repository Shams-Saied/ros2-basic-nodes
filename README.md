# ROS 2 Basic Nodes (Timers & Logging)

## Overview

This project demonstrates basic usage of ROS 2 nodes using Python. It includes simple examples of node creation, timers, and logging functionality.

The goal of this project is to explore the fundamentals of ROS 2 node structure and periodic execution.

## Features

* Creation of ROS 2 nodes using Python
* Timer-based callbacks (executed every second)
* Logging messages using ROS 2 logging system
* Basic conditional logic within nodes
* Random data simulation

## Tech Stack

* Python
* ROS 2 (`rclpy`)

## How to Run

### 1. Start ROS 2

Make sure ROS 2 is installed and sourced:

```bash
source /opt/ros/<your_distro>/setup.bash
```

### 2. Run First Node (Parity Checker)

```bash
python3 first_node.py
```

* Enter a number when prompted
* The node will log whether the number is **even** or **odd** every second

### 3. Run Second Node (Sensor Simulation)

```bash
python3 second_node.py
```

* The node generates and logs random:

  * Temperature
  * Pressure
  * Humidity

## What I Learned

* Basics of ROS 2 node creation
* Using timers for periodic execution
* Logging data in ROS 2
* Structuring simple Python-based ROS nodes

## Notes

* This project is a simple introductory exercise and does not include inter-node communication (e.g., publishers/subscribers).
* Intended for learning and experimentation with ROS 2 fundamentals.
