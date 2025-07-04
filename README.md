WRO Future Engineers – Autonomous Vehicle
Overview
This repository contains the engineering materials for our autonomous vehicle developed for the WRO Future Engineers Competition 2025. The vehicle is designed using 3D-printed structural components, LEGO gear and support systems, and is powered by an Arduino UNO microcontroller. It includes all necessary documentation, code, schematics, and media files to showcase the design, construction, and functionality of our self-driving robot.

📁 Repository Structure
t-photos/: Two photos of the team (one official and one fun group picture).

v-photos/: Six images of the vehicle (front, back, left, right, top, and bottom views).

video/: video.md file containing the link to our driving demo video.

schemes/: Electromechanical diagrams in JPG, PNG, or PDF showing how components are connected.

src/: Arduino code controlling the motors, sensors, and logic.

models/: 3D model files used to print the vehicle's structure and mounts.

other/: Additional files such as build photos, hardware specs, battery info, and connection instructions.

⚙️ Technical Introduction
The vehicle combines custom-designed 3D-printed parts with LEGO gear systems to form a functional and modular robotic platform. It features a drive system, a steering mechanism, onboard sensors, and a power system all managed by an Arduino UNO.

🔧 Modules
motor_control.ino: Controls a DC motor for propulsion and a servo motor for steering.

ultrasonic.ino: Handles distance measurements from ultrasonic sensors.

main.ino: Integrates all modules and controls behavior based on sensor input.

🔩 Electromechanical Design
Chassis: Fully 3D-printed, designed to house all components securely, including the electronics and internal battery pack.

Supports: LEGO elements are used as modular supports and for integrating gear mechanisms.

Gearing: A system of LEGO gears transmits torque from the DC motor to the drive wheels.

Steering: A servo motor turns the front axle using a 3D-printed linkage system.

Sensors: Two ultrasonic sensors detect obstacles and measure distances.

Power Supply: The robot is powered by a rechargeable battery pack mounted inside the chassis.

Controller: All logic is run by an Arduino UNO, connected to motors and sensors through the chassis.

🧪 Build & Execution Instructions
Open the .ino files in the Arduino IDE.

Connect your Arduino UNO via USB to your computer.

Under the Tools menu, select the correct board (Arduino UNO) and port.

Press Upload to flash the code.

Disconnect USB and power the vehicle via the internal battery to begin autonomous operation.

🎯 Project Objective
Our objective is to design a reliable, fully autonomous vehicle using a hybrid structure made of 3D-printed elements and LEGO mechanics, controlled by Arduino-based logic. This allows flexibility in design, rapid prototyping, and a clear demonstration of STEM learning.

🔍 Additional Notes
The combination of LEGO gears and custom-printed parts enhances mechanical precision.

The battery pack is safely integrated inside the chassis for optimal space usage.

All modules are modular and replaceable, promoting ease of maintenance and iteration.
