---
title: Dynamics I
---

In order to understand the solution devopled for the project, a simulation must be made that contains critical information. First, the linkages and their lengths are defined as shown below. Each link has a mass and inertia that plays a role in the simulation. The links are 37.5mm and 75mm.

{
lbase = Constant(.075,'lbase',system)

lA = Constant(.0375,'lA',system)

lC = Constant(.0375,'lC',system)

lend = Constant(.075,'lend',system)

lD = Constant(.0375,'lD',system)

lB = Constant(.0375,'lB',system)
}

More defining values are added such as initial conditions and frames with their respective references. Springs were added to the system to provide motion, for the final device only servos will be used. After defining contraints to keep the linkage even, an animation can be created, shown below.

[Dynamics Animation](https://youtu.be/sr3vjlnPuzs)
