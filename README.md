# ESP32-UltraLED

This project demonstrates the integration of an ESP32 microcontroller with an ultrasonic sensor and three LED indicators.
For this project you will need: 
- **ESP32 Microcontroller**
- **HC-SR04 Ultrasonic Sensor**
- **Three LEDs** (Red, Yellow, Green)
- **Resistors** (220Ω for each LED)
- **Breadboard and Jumper Wires***

## Pin Map

| Component       | ESP32 Pin |
|------------------|-----------|
| Trig Pin         | 5         |
| Echo Pin         | 18        |
| Green LED        | 27        |
| Yellow LED       | 26        |
| Red LED          | 25        |
| Ground           | GND       |
| VCC (Ultrasonic) | 5V        |

The project utilizes an ultrasonic sensor to measure distances and provide real-time feedback. It employs three LED indicators—red, yellow, and green—to visually represent different distance ranges: the green LED lights up for distances between 20 cm and 30 cm, the yellow LED indicates distances from 10 cm to 20 cm, and the red LED activates for distances less than 10 cm. Additionally, the distance measurements are displayed on the Serial Monitor, facilitating easy monitoring and debugging.

This project lays the groundwork for numerous potential applications and enhancements. Future developments could include integrating additional sensors for more complex environmental awareness, implementing wireless communication for remote monitoring, or expanding the system into a full-fledged proximity alarm or automation tool.
