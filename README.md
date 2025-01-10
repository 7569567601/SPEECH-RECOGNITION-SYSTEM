# SPEECH-RECOGNITION-SYSTEM
Name: Modala Naresh Sagar
Company: CodTech IT Solutions Pvt. Ltd
Intern ID: CT12EFC
Domain: Embedded Systems
Duration: December 17, 2024, to February 17, 2025
Project Overview
Project Title: Build a Basic Speech Recognition System for Command-Based Control of Devices Using an Embedded Board
Objective
To develop a system that uses speech recognition to control electrical devices such as lights and fans through an embedded board and relay modules.
Components Required
Embedded Board: Arduino Uno, ESP32, or Raspberry Pi to process commands.
Speech Recognition Module: Elechouse V3 Voice Recognition Module or similar to recognize commands.
Relay Module: To control high-power devices.
Electrical Appliances: Example devices like LED or fan.
Power Supply: To power the circuit.
Jumper Wires: For making circuit connections.
How It Works
1. Speech Recognition Module
Pre-trained to recognize specific voice commands (e.g., "Turn on light", "Turn off fan").
Sends command IDs to the embedded board via serial communication.
2. Embedded Board
Receives command IDs from the speech recognition module.
Decodes the commands and controls the relay module to switch devices on/off.
3. Relay Module
Acts as an electronic switch to control high-power appliances based on the board's signals.
Circuit Diagram
Connections
1. Speech Recognition Module:
VCC → 5V (Arduino or ESP32)
GND → GND
RX → TX (Arduino Pin 2)
TX → RX (Arduino Pin 3)
2. Relay Module:
IN1 → Pin 8 (Arduino or ESP32)
IN2 → Pin 9
VCC → 5V
GND → GND
3. Devices:
Connect the positive terminal of the device to the relay's NO (Normally Open) terminal.
Connect the COM (Common) terminal to the power source.
Training Voice Commands
Using Elechouse Voice Recognition Module V3
Train the module with the following voice commands:
"Turn on light"
"Turn off light"
"Turn on fan"
"Turn off fan"
![task 4](https://github.com/user-attachments/assets/30300e58-f8a3-49cd-b7a3-4f5d422d1626)
