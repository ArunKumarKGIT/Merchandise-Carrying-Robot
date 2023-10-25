# Merchandise-Carrying-Robot

##  INTRODUCTION:
As technology becomes increasingly important in today's world, it is inevitable to not only learn how to use technology but also to innovate new ideas. Nowadays, automation of tasks can be seen implemented everywhere, but still, some places lack its implementation like rice mills where food grain are carried in gunny bags by manpower. There are many disadvantages of this kind of transportation, because it is time-consuming, labor-intensive, economical, and also, using of hooks/manual handling makes gunny bags prone to leakage & pilferage. The record keeping/gunny counting is also done manually. Automation of these transportation task has the advantage of :
1. Quick turn-around time for loading/unloading operation.
2. Exact counting of bags handled.
3. Cost-effective. 
4. Less pilferage & saving of grains.
5. Long-life of gunny

##  PROBLEM STATEMENT DESCRIPTION:

The main task is to implement a robot than can load goods, carry them in a pre-defined route, and then de-load them.
It can also record the number of gunny bags transported, detect defective bags(wet ones) and isolate them.
This project has two main aspects, weight endurance and route following efficiency, in which we created a prototype of a basic route follower and tried to increase its efficiency(velocity of the robot, angle of curvature).

##  HARDWARE REQUIREMENTS:

Arduino UNO
IR sensors
L298N 2A Motor Driver Module with PWM Control
TT-4 DC BO Motor Dual shaft
Vehicular frame
7.4V Lithium ion Rechargeable Battery (2600mah)

WORKING:

This robot is designed such that it follows a pre-defined route autonomously and stops when there is an obstacle or hindrance and continues to move forward when the path is clear until it reaches the destination.
The vehicle is made with two IR sensors( separated by a distance equal to that of the width of the black line ) placed at the front of the vehicle facing downwards(towards the ground) and another IR sensor facing the forward direction ( to detect the obstacle ).
The Arduino UNO , L298N Driver Module are mounted on the vehicular frame along with the two motors connected to the wheel .The required connections are made between the components .Here, the IR sensors play an important role in guiding the robot along the Black Line(pre-defined path).
![p1](https://github.com/ArunKumarKGIT/Merchandise-Carrying-Robot/assets/77446060/3ce30155-c5c3-4bb2-861a-9d5bb27c46f1)

##  IR SENSOR:
The IR sensor consist of an IR transmitter and an IR receiver. The IR transmitter radiates the IR light. If the light encounters an object, the light gets reflected back. The reflected IR light is received by the IR receiver. If there is no object, then IR light does not get reflected and hence, IR receiver will not detect any light. The same case is obtained when the IR light encounters a black object. Since black object absorbs all light that falls on it, the IR light will not get reflected.

Based on this working of IR sensor, the robot is made. When any one of the two IR sensors(placed each at the left and right side, at the front portion of the vehicle) encounters a black colour, the wheel of that particular side is made to rotate in reverse direction, while the other wheel moves in the forward direction. This makes the robot to turn left or right, based on the IR sensor which meets with the black line. 

If the right sensor encounters with the line, then the robot turns toward the right direction( left wheel moves in forward direction and right wheel moves in reverse direction). Similarly,  when the left sensor encounters with the line, then the robot turns toward the left direction( right wheel moves in forward direction and left wheel moves in reverse direction).

![n4](https://github.com/ArunKumarKGIT/Merchandise-Carrying-Robot/assets/77446060/0ad4e07f-244b-4a6f-ae22-6dbf406a41ea)

APPLICATIONS:
In the medical field, a line follower can be used for automated stretchers that carry patients or as a tool for optimizing the patient reception system. Another utility in this domain is bringing food and drinks to patients in infectious disease wards, where medical staff aren’t able to safely interact with patients.

There are many applications for the line follower in our world today. It is used especially in industrial environment, performing tasks such as transportation, manipulation of different objects and as a replacement for conveyer belts. They are also well suited for domestic applications, such as floor cleaning or as service robots that follow you. In the future, the concept of the line follower is expected to be applied in several markets, including medical, transportation and construction.

![prototype](https://github.com/ArunKumarKGIT/Merchandise-Carrying-Robot/assets/77446060/354f84ff-ee8b-45b1-9abe-76d4ba89e044)

![prototype1](https://github.com/ArunKumarKGIT/Merchandise-Carrying-Robot/assets/77446060/8198edfe-b487-4742-960b-ad4a14916352)







