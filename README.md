Reactive-Bot: LiDAR-Based Obstacle Avoidance in MuJoCo

Project Overview
This project is for the ST: Autonomous Mobile Robot course. The goal is to implement a fundamental reactive navigation system for a mobile robot within a 3D simulated environment. Using C++ and the MuJoCo physics engine, the robot will autonomously navigate and avoid static obstacles in real-time without the need for a pre-generated map.

Technical Stack
Simulator: MuJoCo (3D Physics) 

Programming Language: C++ 

Modeling Format: MJCF (XML) 

Logic Type: Reactive State Machine (Sense-Act) 

Key Features
Sensor Processing: Real-time distance data parsing from simulated LiDAR/Range-finder sensors.

C++ Control Loop: Implementation of a state machine to manage robot states: Forward, Turn, and Recovery.

High-Fidelity Physics: Utilization of MuJoCo’s engine to simulate realistic wheel friction and physical collisions.

Sim-to-Real Path: Designed for eventual porting to physical hardware (e.g., Raspberry Pi or Arduino) using ultrasonic/IR sensors.
