Smart Electricity Meter System Using Arduino

A Smart Electricity Meter System developed using Arduino to monitor and calculate real-time electricity consumption. This project was presented at the International Telecommunication Conference (ITC 2023) and focuses on improving energy monitoring efficiency through embedded systems and sensor integration.

Overview

The system measures voltage and current values using sensors connected to an Arduino UNO board. The collected data is processed to calculate power consumption, energy usage, and estimated electricity cost in real time. The results are displayed on an LCD screen, providing continuous live monitoring of electricity consumption.

This project demonstrates practical applications of embedded systems, electronics, real-time monitoring, and Arduino programming.

Features
Real-time electricity monitoring
Power consumption calculation
Energy usage estimation
LCD display integration
Sensor-based monitoring system
Continuous live updates
Low-cost embedded solution
Components Used
Arduino UNO
LCD 16x2 Display
ACS712 Current Sensor
Voltage Sensor Module
Breadboard
Jumper Wires
Potentiometer
External Power Supply
Technologies & Tools
Arduino IDE
Embedded C
Proteus Simulation
Electronics & Circuit Design
System Workflow
Voltage and current sensors collect electrical readings.
Arduino processes the sensor values.
The system calculates power consumption.
Results are displayed on the LCD screen.
Energy usage updates continuously in real time.
Formula Used
Power (W) = Voltage × Current
Energy (kWh) = Power × Time
Example Arduino Code
float voltage = analogRead(A1);
float current = analogRead(A0);
float power = voltage * current;

lcd.setCursor(0,0);
lcd.print("Power: ");
lcd.print(power);
Skills Gained
Embedded Systems
Arduino Programming
Circuit Design
Sensor Integration
Hardware Troubleshooting
Problem Solving
Real-Time Data Processing
Team Members
Omar Attia Farag Elmahdy
Mohamed Ebrahim Hafez
Mohamed Ashraf Ali Eldeen
Eslam Hamdy Mohamed
Supervisor

Mohamed Bastawisy

Organization

Dakahlia STEM School

Conference Participation

Presented at the International Telecommunication Conference (ITC 2023) held at the Arab Academy for Science, Technology & Maritime Transport (AASTMT), Alexandria, Egypt.

Future Improvements
Wi-Fi connectivity
Mobile application integration
Cloud monitoring dashboard
Smart home integration
Automatic electricity cut-off system
License

This project is for educational and learning purposes.
