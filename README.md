#Aim of the project
the aim of the project is to generate a start and end point for the robot to move towards. In order to move the robot, a curved path is generated thst the robot will follow avoiding the wallls and obstacles encountered.

##how the robot works
Firstly, the user will have 3 choices for the journey of the robot, each choice has its own start and end coordinates. Furthermore, the polyfit function generates the curve, which is the path that the robot will follow. In addition, sensors were utilised to know the difference between the current location of the vehicle and the landmarks, which resembles the obstacles. A specified tolerance of 0.3 in distance that stops the vehicle from hitting the walls or the obstacles.

