Home Security System using Raspberry Pi and PIR Sensor  

Project Overview  
This project implements a cost-effective Home Security System using a Raspberry Pi and a PIR (Passive Infrared) sensor. It detects intruders by sensing motion and sends real-time push notifications to the user’s smartphone using Pushbullet.  

Features  
Motion detection using PIR sensor  
Real-time alerts via Pushbullet notifications  
Wi-Fi-enabled security system using Raspberry Pi  
Affordable and easy-to-implement IoT solution  

Components Required  
Raspberry Pi (with Raspbian OS installed)  
PIR Sensor  
Jumper Wires  

How It Works  
1. Motion Detection: The PIR sensor detects movement and sends a signal to the Raspberry Pi.  
2. Trigger Alert: The Raspberry Pi processes the signal and sends a push notification using Pushbullet API.  
3. Real-time Notification: The user receives an alert on their smartphone.  

Circuit Diagram  
![Screenshot (219)](https://github.com/user-attachments/assets/4802bd68-38e0-413d-a5d9-7954c8cec4ce)

Installation and Setup  
1. Set up the Raspberry Pi  
   Install Raspbian OS  
   Enable GPIO access  
2. Install Dependencies  
   ```bash
 sudo apt update
 sudo apt install python3-pip
 pip install pushbullet.py RPi.GPIO
