# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
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
```
1.Open the roboanalyzer software.
2.Select the robot and the degrees of freedom.
3.Change the values with the link length wherever necessary.
4.Simulate the model for forward kinematics.
5.Plot the graph between the link and the joints.
6.Update the DH parameters of the link configuration and end effector configuration
```



### SIMULATION 

![Screenshot (236)](https://user-images.githubusercontent.com/94508142/174304065-3857360b-672c-4d7b-9388-f8e96a8dbba2.png)
![Screenshot (240)](https://user-images.githubusercontent.com/94508142/174304088-278d40c7-fc75-47e7-8c37-24cc232affa4.png)



 
 
 
 
 
 
 ### PLOT 

![Screenshot (235)](https://user-images.githubusercontent.com/94508142/174299867-f4bb2db2-3780-41db-b885-352243d93565.png)
![Screenshot (241)](https://user-images.githubusercontent.com/94508142/174304169-81f831da-ab46-461a-bea1-8456fca58c4d.png)

### EE Configuration
![Screenshot (237)](https://user-images.githubusercontent.com/94508142/174304379-95bbefc0-1364-4cca-a57f-f1dbc53167aa.png)
![Screenshot (242)](https://user-images.githubusercontent.com/94508142/174304412-a4259cb1-30a6-4f5c-b2be-fe16beedddff.png)




### RESULTS :  
Forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles is analysed succesfully

