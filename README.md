# Notes on Robotics

Notes on robotics, mainly (arm) manipulation robotics: kinematics, dynamics, trajectory generation, control. I made these notes as a possible script for my students.

Some of the used resources:

- [Youtube ThatsEngineering, Robotics Playlist](https://www.youtube.com/playlist?list=PLZaGkBteQK3HQFSWDM7-yRQWTd86DeDIY).
- [QUT Robot Academy, Peter Corke](https://robotacademy.net.au/).
- J. Craig, Introduction to Robotics, 3rd Ed.
- Lynch & Park, Modern Robotics. Book and Coursera Course.
- [CoppeliaSim Tutorial by Leopoldo Armesto](https://www.youtube.com/playlist?list=PLjzuoBhdtaXOYfcZOPS98uDTf4aAoDSRR).
- Robotics, Coursera Course by the University of Pennsilvania.

The notes were done using Notability for iPad.

<!--
Examples implemented in Python using Peter Corke's [Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python).
-->

Each topic has its own PDF:

1. Spatial Descriptions and Transformation Matrices for Robotic Manipulators (Videos 1, 2, 3; Craig 2)
    - Position vector
    - Orientation/Rotation matrix
    - Frames = Coordinate Systems
    - Transformations
    - Rotation Matrices
    - Compositions of transformations
    - Inverse Transformation matrix
    - Example: Compositions
    
2. Rotation: Euler Angles & Co. (Videos 4, 5; Craig 2)
    - Fixed Angle representation
    - Euler Angle representation (moving)
    - Comparing rotation representations
    - Example: Find Euler angles
    - Angle-axis representation
    - Unit Quaternions = Euler parameters
    - Rodrigues' Formula
    - Exponential Representation of Rotations

3. Direct (Forward) Kinematics (Videos 6, 7, 8, 9; Craig 3)
    - Links and joints
    - Conventions for fixing frames to joints
    - Denavit-Hartenberg (DH) representation for describing direct kinematics
    - DH Parameters example
    - Frames with standard names
    - DH parameters of the URe-s

4. Inverse Kinematics (Craig 4)
    - Solvability issues
    - Example with a planar manipulator
    - Repeatability and Accuracy

5. Jacobians (Videos 10, 11, 12, 13; Craig 5)
    - Linear and angular velocities: time-varying position and orientation
    - Velocity of Rigid Bodies
    - Notes on the Angular Velocity
    - Velocity Propagation from Link to Link
    - The Jacobian Matrix
    - The Frame of the Jacobian
    - Singularities
    - Calculating the Jacobian
        - Partial differentiation method
        - Velocity propagation method
    - Static Forces in Manipulators
    - Computation of forces and torques necessary at the joints to support a force at the endeffector using the Jacobian
    - Cartesian Transformation of Velocities and STatic Forces

6. Dynamics (Craig 6)
    - Acceleration of a Rigid Body
    - Mass Distribution
    - Newton-Euler Equations of Motion
    - Iterative Newton-Euler Dynamic Formulation: Obtain Joint Torques Necessary for Joint Motion (Inverse Dynamics)
    - An Example of Closed-Form Dynamic Equations
    - The Structure of a Manipulator's Dynamic Equations
        - The State-Space Equation
        - The Configuration-Space Equation
    - Lagrangian Formulation for Manipulator Dynamics
    - Manipulator Dynamics in Cartesian Space
    - Inclusion of Other Effects
    - Dynamics Simulation: Forward Dynamics

7. Trajectory Generation (Craig 7)
    - Path Generation with Joint Schemes
        - Cubic Polynomials of Joint Values with Via Points
        - Linear Functions with Parabolic Blends
    - Path Generation with Cartesian Schemes
        - Cartesian Straight-Line Motion
        - Problems with Cartesian Paths
    - Path Generation at Run-Time

8. Mechanism Design (Craig 8)
    - Basing the Design on Task Requirements
    - Kinematic Configuration
    - Quantitative Measures of Workspace Attributes
    - Actuation Schemes
    - Stiffness and Deflections
    - Actuators and Sensors

9. Linear control of manipulators (Craig 9)
    - Feedback and Closed-Loop Control
    - Second-Order Linear Systems
        - Laplace
        - Solving the second-order linear system
    - Control of Second-Order Systems
        - Position Regulation Control
    - Control-Law Partitioning
    - Trajectory-Following Control
    - Disturbance Rejection
        - Steady State Error
        - PID Control
    - Continuous vs. Discrete Time Control
    - Modeling and Control of a Single Joint
    - Architecture of an Industrial-Robot Controller

10. Nonlinear control of manipulators (Craig 10, TBD.)
11. Force control of manipulators (Craig 11, TBD.)

Mikel Sagardia, 2021.  
No guarantees.
