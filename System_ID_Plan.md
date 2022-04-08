---
title: System Identification Plan
---
Materials available:
1. Stiff Material: Wood (Innovation Hub)
1. Flexible Materials: Nylon(Class) or Polyester(Class)
1. Adhesive: Available in Innovation Hub
1. Actuators: Small servos and control systems(Team Member’s)

Parameters and Testing Methods:
* Actuator modeling
  * Simulate servo torque and speed inside System Dynamics.
* input signal specification
  * Test available servos and control system.
* Mass and inertia properties of system
  * Manufacture system and test motion with servos, measure motion, speed, and error to calculate mass and inertia.
* Link and/or joint stiffness
  * Manufacture simplified system and test deflection with known mass.
* Joint damping
  * Manufacture system and test damping through motion tests.

Prototyping Plan:
Andrew will be responsible for acquiring materials to generate a test system. This system will be simplified to focus on parameter testing. Andrew will also be responsible for manufacturing the prototype and conducting the above tests.

Testing Analysis:
Tracker, a free video analysis software, will be used to generate motion data from videos of the prototype tests. The goal is to extract a damping ratio from the tests to insert into the System Dynamics simulation. 

Simulation Update:
Currently, the damping ratio of the system is set to 0. Therefore, once a value is acquired, it can be added to the simulation and run. This will be done by Andrew Fechter.

Report:
The prototyping process, testing, and updated simulation will be contained in a single report. The system dynamics .ipynb file will be updated to include this information.
