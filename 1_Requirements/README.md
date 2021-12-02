# M2_Embedded_waterlevelfinder 
# Introduction

The water and wastewater industry has many requirements for measuring the level of water in applications such as flumes, weirs, pipes, tanks, wells, basins, and cooling towers. Ultrasonic sensors are reliable, cost-effective instruments for these applications. In operation, the sensor is mounted over the water. To determine the distance to the water, it transmits a sound pulse that reflects from the surface of the water and measures the time it takes for the echo to return.
## Reasearch
In many conditions, the conventional liquid data monitoring based on an ultrasonic sensor
provides the unreliable readings due to the dynamically changed water level.
In addition, in some conditions, it needs not only measuring water level but also needs to measure the volume and control water surplus or deficiency. 
To solve these issues,an accurate non-contact water measurement system based on a microcontroller and an ultrasonic sensor to measure the level 
and volume of liquids in small tanks without any contact.
## Features and Cost and Timeline
1.	Used to measure the water.
2.	This system can be used in checking fuel in vechicles also with few changes in it .
## Defining Our System
Distance to fill yet is determined  using HC-SR04 and ATMEGA328p. In this project i have measured distance in centimeters, with the help of HC-SR04 Ultrasound sensor, ATMEGA328p micro-controller, LCD Display via I2C bus.
Principle:
Timer2 of ATMEGA328p is used to generate a Trigger pulse of 20uS, the ultrasonic module sends out a 8cycle burst of 40khz which hits the water and returns back to raise an echo pulse. The pulse-width of this pulse is proportional to the distance between the module and water.
Input capture module of the ATMEGA was used to capture the time between rising and falling edges of the echo pulse. The prescaler of this unit was chosen, such that the resolution of pulse-width is 16uS.
The display in use is LCD which has an integrated chip that converts serial data (via I2C bus) into parallel stream of bits for the LCD
##SWOT ANALYSIS
Strength:
1. Measure the distance which wil be easy to conﬁgure and handle.
2. Easy to use and reliable
3. cost
4. Technology advantages
Weaknesses:
1. They cannot tell you the exact distance or location of the obstacle.
2. Marketing deficiencies
Requirements:
s.no    description             status
HR01	Enable ICP Interrupt	  Implemented
HR02	Enable internal pullups Implemented
HR03	I2C and LCD	            Implemented
Opportunities:
1. New technology
3. New markets or services
Threats:
1. New or increased competition
2.  Economic slowdowns
4W's and 1'H
WHAT:
Distance yet to fill water is a numerical measurement of how far apart objects or points are.Ultrasonic sensor provides an easy way in  measurement of water level.
WHY:
Ultrasonic sensors are great tools to measure distance and detect objects without any actual contact with the physical world. 
WHERE:
Wherever having the tank can be used to find the water level yet to fill.
WHEN: The ultrasonic sensor emits a high-frequency sound pulse and calculates the distance depending upon the time taken by the echo signal to travel back after reflecting from the desired target. The speed of sound is 341 meters per second in air. After the distance is calculated, it will be displayed on the LCD display.
How:
In This project,the HC-SR04 Ultrasonic Sensor with ATMEGA328 is used  to determine the distance to fill water. The basic principle of ultrasonic distance measurement is based on ECHO.
