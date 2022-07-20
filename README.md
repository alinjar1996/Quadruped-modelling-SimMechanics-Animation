# Quadruped-modelling-SimMechanics-Animation
This repository contains animation for simulation of a quadruped under external disturbance.  The Quadruped is modelled in Matlab-SimMechanics. The control methodology that ensures stable movement of the quadruped is novel and currently under preparation for a manuscript.
The quadruped model is of 24 Degrees of Freedom (DoF). Each hip joint has 3 DoF, knee joint has 1 DoF, and ankle joint has 2 DoF.
Dynamic parameters of the quadruped are critical for stability. Mass of the quadruped is 4.5 Kg. A force of 10N has been applied on the quadruped along +ve X direction (forward direction) for 0.2 second. 
The applied optimal control law takes care of the friction force, reaction force, Centre of Mass (CoM) displacement and Torso rotation. 
