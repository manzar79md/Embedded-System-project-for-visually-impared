Wrist-Worn Multimodal Obstacle Detection System
Abstract
The Wrist-Worn Multimodal Obstacle Detection System is an embedded system designed to assist visually impaired individuals in navigating their surroundings safely and independently. The device integrates multiple components, including an HC-SR04 ultrasonic sensor, a vibration motor, and a buzzer, to provide tactile and auditory feedback. Designed as a compact, wearable device resembling a wristwatch, it prioritizes user accessibility, reliability, and customization.

Features
Obstacle Detection: Uses an HC-SR04 ultrasonic sensor to detect nearby obstacles.
Feedback Mechanisms:
Tactile Feedback: Vibration motor alerts users through physical vibrations.
Auditory Feedback: Buzzer provides sound-based alerts.
Compact and Wearable Design: Built as a wrist-worn device for portability and convenience.
User-Friendly Interface: Simple on/off switch for ease of use.
Rechargeable Battery: Provides extended usage without frequent replacements.
Customizable Settings: Adaptable to user preferences and environmental conditions.
Fail-Safe Mechanisms: Reduces false alarms for a smoother and more reliable experience.
Components
HC-SR04 Ultrasonic Sensor: Detects obstacles by measuring distance using ultrasonic waves.
Vibration Motor: Provides tactile feedback when obstacles are detected.
Buzzer: Emits sound alerts as an auditory indication of nearby obstacles.
Rechargeable Battery: Powers the device and supports recharging for long-term use.
Microcontroller (e.g., ESP32/Arduino): Serves as the processing unit for sensor data and control mechanisms.
Switch: Powers the device on/off for easy operation.
How It Works
Obstacle Detection:
The HC-SR04 ultrasonic sensor continuously scans for obstacles within a predefined range.
Feedback:
When an obstacle is detected, the system triggers both the vibration motor and the buzzer.
The intensity and frequency of feedback can vary based on the proximity of the obstacle.
Power Management:
The device is powered by a rechargeable battery, ensuring usability on the go.
Users can turn the device on or off using a switch for efficient power usage.
Applications
Navigation aid for visually impaired individuals.
Mobility support in crowded or unfamiliar environments.
Enhancing safety during outdoor and indoor movement.
Setup Instructions
Hardware Assembly:
Connect the HC-SR04 sensor, vibration motor, buzzer, switch, and rechargeable battery to the microcontroller.
Secure all components within a compact, wearable enclosure resembling a wristwatch.
Software Configuration:
Upload the obstacle detection and feedback code to the microcontroller using the Arduino IDE or a similar platform.
Adjust sensor range and feedback thresholds as per user requirements.
Power Up:
Ensure the battery is charged, and switch on the device to start operation.
Usage
Wear the device on your wrist.
Turn it on using the power switch.
The device automatically detects obstacles and provides tactile and auditory feedback to help you navigate.
Safety and Reliability
The device includes fail-safe mechanisms to minimize false alarms.
Feedback intensity is optimized to ensure comfort and effectiveness.
Future Enhancements
Integration of advanced sensors for improved accuracy.
Addition of wireless connectivity for real-time monitoring.
Compatibility with smart devices for extended functionalities.
for the virtual view click on this link https://wokwi.com/projects/406034869275608065
License
This project is open-source and can be freely used and modified for non-commercial purposes. For commercial use, please contact the author.

Acknowledgments
Thanks to all mentors, peers, and resources that contributed to the success of this project.
