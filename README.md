# Line_following_Robo
A typical line follower robot has two sets of motors, let's call them left
motor and right motor. Both motors rotate on the basis of the signal
received from the left and the right sensors respectively. The robot
needs to perform 4 sets of motion which includes moving forward,
turning left, turning right and coming to a halt. The description about
the cases are given below.<br>
## Moving Forward: <br>
In this case, when both the sensors are on a white surface and the line
is between the two sensors, the robot should move forward, i.e., both
the motors should rotate such that the robot moves in forward
direction (actually both the motors should rotate in the opposite
direction due to the placement of motors in our setup. But for the sake
of simplicity, we will call the motors rotating forward.<br>
![https://drive.google.com/file/d/1__psURYtoMt6hzfxMDZMZDNKuU6QFbfY/view?usp=drive_link]<br>
## Turning LEFT: <br>
In this case, the left sensor is on top of the dark line, whereas the right
sensor is on the white part, hence the left sensor detects the black line
and gives a signal to the microcontroller. Since, signal comes from the
left sensor, the robot should turn in the left direction. Therefore, the left
motor rotates backwards and the right motor rotates in forward
direction. Thus, the robot turns towards the left side.
