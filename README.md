# Notes on Robotics

Notes on robotics, mainly (arm) manipulation robotics: kinematics, dynamics, trajectory generation, control. Additionaly robot vision topics are outlined.

I made these notes as a possible script for students.

Some of the used resources:

- [Youtube ThatsEngineering, Robotics Playlist](https://www.youtube.com/playlist?list=PLZaGkBteQK3HQFSWDM7-yRQWTd86DeDIY)
- [QUT Robot Academy, Peter Corke](https://robotacademy.net.au/)
- J. Craig, Introduction to Robotics, 3rd Ed.
- Lynch & Park, Modern Robotics. Book and Coursera Course.
- [CoppeliaSim Tutorial by Leopoldo Armesto](https://www.youtube.com/playlist?list=PLjzuoBhdtaXOYfcZOPS98uDTf4aAoDSRR)

Notes done using Notability for iPad.
Examples implemented in Python using Peter Corke's [Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python).

Index of topics:

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

3. Direct Kinematics (Videos 6, 7, 8, 9; Craig 3)
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

5. Jacobians (Craig 5)
6. Dynamics (Craig 6)
7. Trajectory Generation (Craig 7)

Now, start the CoppeliaSim tutorial.
10 hours, approx.

Coursera Courses:
8. Motion planning (Lynch 10)
9. Robot Control (Lynch 11)
10. Grasping and Manipulation (Lynch 12)
11. Wheeled Mobile Robots (Lynch 13)

12. Linear control of manipulators (Craig 9)
13. Nonlinear control of manipulators (Craig 10)
14. Force control of manipulators (Craig 11)
