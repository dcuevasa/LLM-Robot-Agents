# Pepper Notes

I already have a lot of experience working with Pepper, so it is the least of my problems; I already set up the Simulation in Gazebo (though, it's missing integration with the full SinfonIA Stack):
- [robot info for simulation](https://github.com/dcuevasa/pepper_robot_noetic)
- [simulation](https://github.com/dcuevasa/pepper_virtual_noetic)

So far only issue is the robot trembles like crazy and it doesn't work properly with MoveIt! However the most relevant stuff is the perception (cameras) and navigation, which are both working fine
![image](https://github.com/user-attachments/assets/57d8b6ca-a5b3-4f63-b2dc-b517498d081b)
My current worries are in working with more than one robot.

# Technical Requirements for LAA Integration on Pepper
As of the moment  writing this (And for the forseable future), our Pepper cannot manipulate and grab objects by themselves, so the robot is going to ask for the object to be handed to them instead of taking it.
Another note is that the implementation is going to rely heavily in abstractions for Navigation (Go from place A to B) which implies A fully mapped environment with predefined places and routes to navigate which the robot has to be familiar with. 

## Related links:
