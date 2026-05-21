# Trajectory Planning and Obstacle Avoidance for MyCobot280

## Overview

This project focuses on trajectory planning and obstacle avoidance for the MyCobot280 robotic manipulator using Random Search and A* algorithms in a PyBullet simulation environment.

Different trajectories were generated and compared based on:

- Time Optimization
- Energy Optimization
- Motion Smoothness

The robot end-effector moves from the start position to the goal position while safely avoiding static obstacles placed in the workspace.

---

# Features

- MyCobot280 robotic manipulator simulation
- PyBullet-based workspace environment
- Static obstacle avoidance
- Random Search trajectory generation
- A* trajectory planning
- Time-optimized trajectories
- Energy-efficient trajectories
- Smooth trajectory generation
- Joint-space waypoint planning
- Inverse kinematics-based robot motion
- Trajectory comparison and analysis

---

# Algorithms Used

## Random Search
Random waypoint-based trajectory generation with collision avoidance constraints.

## A* Algorithm
Graph-based optimal path planning using heuristic cost evaluation.

---

# Optimization Objectives

## Time Optimization
Generates shorter and faster trajectories with reduced travel distance.

## Energy Optimization
Reduces excessive joint movement and actuator effort.

## Smoothness Optimization
Minimizes abrupt directional changes and improves motion continuity.

---

# Simulation Environment

- PyBullet Physics Engine
- MyCobot280 URDF Model
- Custom workspace with obstacles
- Real-time trajectory visualization

---

# Workspace Setup

The environment contains:

- Start Position
- Goal Position
- Red Obstacle
- Green Obstacle
- Blue Obstacle

All generated trajectories safely avoid collisions while navigating through the constrained workspace.

---

# Results

The project compares Random Search and A* trajectories using:

- Path Length
- Energy Cost
- Smoothness Cost

The A* algorithm demonstrated:

- Better trajectory consistency
- Lower energy cost
- Improved smoothness
- More structured path planning

---

# Technologies Used

- Python
- PyBullet
- NumPy
- Matplotlib

---

# Project Structure

```text
├── trajectories/
├── images/
├── graphs/
├── pybullet_simulations/
├── results/
├── README.md
└── requirements.txt
```

---

# Installation

```bash
pip install pybullet numpy matplotlib
```

---

# Run Simulation

```bash
python simulation.py
```

---

# Output

The simulation generates:

- Robot trajectory execution
- Obstacle avoidance visualization
- Joint-space trajectory motion
- Performance comparison graphs

---

# Future Scope

- Dynamic obstacle avoidance
- Real-time trajectory replanning
- AI-based trajectory optimization
- Reinforcement learning integration
- ROS2 integration
- Physical robot implementation

---

# Author

Kaushal Pandya

M.Tech Robotics and Automation
