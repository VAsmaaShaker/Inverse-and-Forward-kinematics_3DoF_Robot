# Inverse-and-Forward-kinematics_3DoF_Robot
Calculate inverse and forward kinematics for a robot with 3 degrees of freedom.

## What is Inverse and Forward kinematics?
Forward kinematics uses the joint parameters to compute the configuration of the chain, and inverse kinematics reverses this calculation to determine the joint parameters that achieve a desired configuration.
![1](https://github.com/user-attachments/assets/978ad3dc-bf15-4aae-af69-98cfaf4a2930)
![7](https://github.com/user-attachments/assets/f8c6a79d-90c5-4dac-8108-ee2e13489242)



---------------------------------------------------------------------------------------------
## To calculate it, I followed these steps:
### Forward kinematics
Forward movement involves determining the final position of the end effector.
![image](https://github.com/user-attachments/assets/a345d304-7825-4ed0-adb6-f6c82506665f)

To calculate the forward kinematics,

1- determine the position of the end effector sequentially along the x-axis for each of link 1, link 2, and link 3. Then, I will sum these positions together. 

![image](https://github.com/user-attachments/assets/d7e44134-cddf-411c-8d42-1ea23854b145)


2- I will repeat these steps for the y-axis.

![image](https://github.com/user-attachments/assets/caad1141-13ba-445f-a835-62255e2057cb)

### Inverse kinematics
Inverse kinematics is used to find the angles for link 1, link 2, and link 3.

![image](https://github.com/user-attachments/assets/cfd4f6ce-c12a-4460-9275-aa2b7a8071a1)

To calculate the Inverse kinematics,
1. calculated the positions of link 1 and link 2 using the 2DoF  in the X and Y axes.
![image](https://github.com/user-attachments/assets/1e74afdf-6416-46e7-90e0-affc55a08722)

![image](https://github.com/user-attachments/assets/f5d27a02-1f49-4a0a-903e-50400f58f305)

2. Calculated the final angle for link 3 by  ( angle1 - angle2 ) from the total angle.

![image](https://github.com/user-attachments/assets/7a035995-3ab1-4e5f-92b3-fb1bed00df7f)


---------------------------------------------------------------------------------------------
## Ref
1. https://www.youtube.com/live/HcEVUetq_sg?feature=shared
2. https://youtu.be/b1arysUSlzo
3. https://www.schoolofmotion.com/blog/character-rigging-tools-after-effects
4. https://en.wikipedia.org/wiki/Inverse_kinematics
5. https://youtu.be/xdP49Mo4sOE
