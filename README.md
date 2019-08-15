# Density_based_Traffic_control_system

Objectives:
1.	To control the traffic lights based on the density of the vehicles to reduce traffic congestion.
2.	To develop coding and to implement it in hardware of density based traffic light control system using arduino.

Introduction:
Due to the heavy traffic in the road many people are suffering. Even though there is traffic signal available at various places it is not easy to control the crowd. In order to avoid traffic problem heavily on the road, we designed and developed a system so called as density based traffic light control system.

Circuit Operation:
It operates in two modes :
•	   Normal mode 
•	   Density mode
NORMAL MODE: 
In this mode of operation green , yellow and red lights change after a fixed time period like a typical traffic signal. Here ,light from IR transmitter LED reach IR receiver without any interruption. IR sensor senses amount of cars passing through the road .By using Arduino , we can observe the voltage of IR sensor. When light from IR transmitter does not interrupted by vehicles ,value of voltage is low (about 800) .When voltage value is below 800,this mode is operated . 
DENSITY MODE:
When amount of cars increases ,light of IR transmitter intersect by cars to reach the receiver .Then the voltage of IR sensor increases (about above 850) .When voltage is below threshold value , normal mode is on; but above threshold values then the red signal becomes automatically green.

Flow Chart:


Advantages:
•	Avoids wastage of time due to the traffic
•	Fully automatic
•	Low power consumption
•	It provides the easy access in the traffic light
•	Low cost to design the circuit, maintenance of the circuit is good
•	By using this Arduino Uno we can create many more control to the appliances
•	Easy convenience to handle.

Limitations:
•	IR sensors sometimes may absorb normal light also. As a result, traffic system works in improper way.
•	IR sensors work only for fewer distances.
•	We have to arrange IR sensors in accurate manner otherwise they may not detect the traffic density.

APPLICATIONS:
•	The project is mainly used in the traffic signals in metropolitan cities to provide uniform distribution of traffic.

Conclusion:
The project may be very well used in where the traffic signals is kept and in many other places where we need to full fill the need of the automation. In this project we have studied the optimization of traffic light controller in a City using IR sensors and Arduino . By using this system configuration we tries to reduce the possibilities of traffic jams, caused by traffic lights, to an extent and we have successfully gets the results.

Future Work:
•	We will implement this system for traffic controlling in a 4 lane junction.
•	We will update this system with when a pedestrian try to cross the road during green signal it will turn on an alarm and warn the pedestrian and traffic police.
•	We will update this system with when a vehicle try to move even during red signal it will turn on an alarm to warn the driver of the vehicle and the traffic
