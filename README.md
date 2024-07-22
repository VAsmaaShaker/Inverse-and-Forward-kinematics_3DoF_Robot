# Inverse-and-Forward-kinematics_3DoF_Robot
Calculate inverse and forward kinematics for a robot with 3 degrees of freedom.

## What is Inverse and Forward kinematics?
Forward kinematics uses the joint parameters to compute the configuration of the chain, and inverse kinematics reverses this calculation to determine the joint parameters that achieve a desired configuration.
![1](https://github.com/user-attachments/assets/e005d428-f755-4d70-9a3d-36eef965158b)
![7](https://github.com/user-attachments/assets/5f6bf01e-a7f9-4cbc-b0b1-42b25c8a7fb5)

---------------------------------------------------------------------------------------------
## To calculate it, I followed these steps:
### Forward kinematics
Forward movement involves determining the final position of the end effector.
![image](https://github.com/user-attachments/assets/a208378e-59ae-4eca-8c68-c1f92ebbe9c7)
To calculate the forward kinematics,

1- determine the position of the end effector sequentially along the x-axis for each of link 1, link 2, and link 3. Then, I will sum these positions together. 

![image](https://github.com/user-attachments/assets/cbc1de66-1e4f-4c1c-81a2-a25f46b8aaea)


2- I will repeat these steps for the y-axis.

![image](https://github.com/user-attachments/assets/49800b6c-3253-496e-bd20-e04c97a831a7)

### Inverse kinematics
Inverse kinematics is used to find the angles for link 1, link 2, and link 3.

![image](https://github.com/user-attachments/assets/6ee13277-341b-4412-9730-b2052359ebb8)

To calculate the Inverse kinematics,
1. calculated the positions of link 1 and link 2 using the 2DoF  in the X and Y axes.
![image](https://github.com/user-attachments/assets/452055b9-a08e-4a29-9f9a-c3a16edd324c)

![image](https://github.com/user-attachments/assets/16396486-051a-42d8-8f08-3aba108906ae)

2. Calculated the final angle for link 3 by  ( angle1 - angle2 ) from the total angle.

![image](https://github.com/user-attachments/assets/c7994228-8f26-4a78-90a5-b3ead667f15a)


---------------------------------------------------------------------------------------------
## Ref
1. https://www.youtube.com/live/HcEVUetq_sg?feature=shared
2. https://youtu.be/b1arysUSlzo
3. https://www.schoolofmotion.com/blog/character-rigging-tools-after-effects
4. https://en.wikipedia.org/wiki/Inverse_kinematics
5. https://youtu.be/xdP49Mo4sOE
