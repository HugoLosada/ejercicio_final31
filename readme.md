 Celestial Bodies Motion Simulation in Space with Verlet Integration

Project Description:
This project implements a simulation of the motion of various celestial bodies in space, including Earth, Mars, the Sun, and a spacecraft. The simulation is carried out using the Verlet integration method to calculate the positions and velocities of celestial bodies over time.

Technologies Used:
VPython (vpython): Used for three-dimensional visualization of objects and scenarios.
Tkinter: Used to create a simple graphical interface for user input.
Python: Main programming language.

How to Run the Simulation:
Make sure you have Python installed on your system.
Install the required libraries by running the following command in your terminal:
pip install vpython
Run the provided script (https://github.com/HugoLosada/ejercicio_final31.git).
The simulation will start, and you can observe the interaction between Earth, Mars, the Sun, and the spacecraft.

User Input:
During execution, the user needs to provide information about the spacecraft, including the spacecraft's radius (rship), velocity (vship), and time step (dt). This information is entered through a simple graphical interface created with Tkinter.

Recommended User Input:
Spacecraft Radius (rship): Recommended value: 3
Spacecraft Velocity (vship): Recommended value: 2
Time Step (dt): Recommended value: 2.73785078e-4

Initial Parameters:
Gravitational Constant (G): 39.4784176
Initial Angle (ANG): Calculated based on Mars' angular velocity and the spacecraft's orbital period.
Minimum Mars Influence Radius (Rmin): Calculated based on Mars' radius and mass.

Simulation Output:
The simulation will generate real-time visualizations of the Earth, Mars, and spacecraft positions in relation to the Sun. Additionally, information will be recorded in a text file (positions.txt) containing the current positions of Earth, Mars, and the spacecraft at each time step.

Spacecraft Trajectory Adjustment:
When the spacecraft approaches Mars, the code performs special trajectory adjustments to ensure proper behavior.

Author:
Hugo Losada Quintáns
