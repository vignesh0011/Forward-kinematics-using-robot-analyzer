# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles.

### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
1. open the roboanalyzer software.
2. select the robot and its degrees of freedom.
3. change the values with the link lenght wherever necessary.
4. simulate the model for forward kinematics.
5. plot the graph between the link and the joints.
6. update the DH parameters of the link configuration and end effector configuration.

### SIMULATION 
 
#### 6 DOF

##### Video



https://user-images.githubusercontent.com/53014593/170322586-84e1ec29-e832-4f57-94b9-d125fc9babb6.mp4



#### Screenshot
![6dof](https://user-images.githubusercontent.com/53014593/170322988-3be1c9a5-490d-4140-a557-ea9c5f635602.png)


![6dof-ee](https://user-images.githubusercontent.com/53014593/170322494-182e77aa-3622-4904-bc49-72141c301a1d.png)


#### 4 DOF

##### Video

https://user-images.githubusercontent.com/70213227/170174635-804432ee-87a5-4573-a9ab-0882b537c72b.mp4

#### Screenshot
![4dof](https://user-images.githubusercontent.com/53014593/170322962-b070efd5-d39a-4468-a9be-96cd2a7c43c7.png)


![4dof-ee](https://user-images.githubusercontent.com/53014593/170322390-b003bb56-534d-4c67-8c01-9e32b174aca2.png)



 
### PLOT 
 
#### 6 DOF

![6dof](https://user-images.githubusercontent.com/53014593/170322472-b63362f1-d743-40b4-b1ce-4530a2acf8d9.png)

#### 4 DOF


![4dof](https://user-images.githubusercontent.com/53014593/170322351-2d1af58f-fda6-4248-bafc-fb221386c60e.png)









### RESULTS : 
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
