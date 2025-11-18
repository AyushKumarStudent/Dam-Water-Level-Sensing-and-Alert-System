# Dam Water Level Sensing and Alert System

## i) Problem Statement / Aim
Problem Statement

To design and develop a prototype Dam Water-Level Sensing and Alert System using Arduino that detects water levels through an ultrasonic sensor and provides alerts using LEDs and a buzzer.

## Aim

To monitor dam water levels in real time and indicate safe, warning, and danger conditions using a low-cost electronic sensing system.

## ii) Scope of the Solution

Prevents dam overflow and flooding by early warning.

Real-time level monitoring using LEDs.

Provides audible alert using a 5V active buzzer.

Uses low-cost and easily available hardware.

Can be expanded for tanks, reservoirs, and industrial use cases.

Easy to operate and beginner-friendly.

## iii) Required Components to Develop the Solution
Hardware Components

Arduino UNO (DIP version)

Ultrasonic Sensor HC-SR04

LEDs (Green, Yellow, Red – 10mm)

Resistors (330Ω)

5V Active Buzzer

Breadboard (400-point)

Jumper Wires (M-M, M-F, F-F)

USB Type-B Cable (for power & programming)

9V Battery + Battery Clip

Software Requirements

Arduino IDE

Tinkercad for simulation

 
 ##🔌Simulated Circuit Diagram
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
[Project File](https://drive.google.com/file/d/1zXSYuDkDcyQtV6uIjHPVyFieDW5EFXOH/view?usp=drive_link)


## Simulation Screenshots

- [Safe Level](Simulation_screenshots/safe_level.png)
- [Warning Level](Simulation_screenshots/warning_level.png)
- [Danger (Possible Overflow)](Simulation_screenshots/Danger_.png)
##  Author
Ayush kumar
Arpan Das 
Dhairya Verma 

