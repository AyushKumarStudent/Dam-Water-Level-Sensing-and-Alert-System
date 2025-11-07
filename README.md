# Dam Water Level Sensing and Alert System

##  Project Overview
This project monitors water levels in a dam using an Ultrasonic Sensor (HC-SR04) and an Arduino Uno.  
It provides visual alerts using LEDs and an audible buzzer alarm when the water level approaches danger levels.

##  Objective
- Measure real-time water level using an ultrasonic sensor.
- Display water level status through LEDs.
- Trigger a buzzer when the water level becomes dangerously high.

##  Components Used
- Arduino UNO  
- Ultrasonic Sensor (HC-SR04)  
- Buzzer  
- LEDs (Red, Yellow, Green)  
- 220Ω Resistors  
- Breadboard and Jumper Wires  

## 🔌 Circuit Diagram
[View Circuit Diagram](Circuit_Diagram/schematic.png)

📄 [View full schematic (PDF)](Circuit_Diagram/schematic.pdf)

##  Arduino Code
The code for this project is located in [Arduino_Code/water_level_alert.ino](Arduino_Code/water_level_alert.ino)

##  Working Principle
The ultrasonic sensor measures the distance between the sensor and the water surface.  
As the water level rises, the distance decreases.  
Based on distance thresholds:
- Green LED → Safe level  
- Yellow LED → Warning level  
- Red LED + Buzzer → Danger (possible overflow)

##  Demo Video
(You will add your YouTube/Drive video link here after recording your demo.)

## Simulation Screenshots

- [Safe Level](Simulation_screenshots/safe_level.png)
- [Warning Level](Simulation_screenshots/warning_level.png)
- [Danger (Possible Overflow)](Simulation_screenshots/Danger_.png)
##  Author
*Ayush kumar*  

