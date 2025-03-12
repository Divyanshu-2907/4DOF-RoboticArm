# 4-DOF Robotic Arm Control System

## Overview
This project is a web-based control system for a 4-DOF robotic arm, allowing real-time remote operation with precise movement control. The system is built using an ESP32 microcontroller and features an intuitive HTML-based user interface.

## Features
- **ESP32-Based Control System**: Designed and implemented a responsive control mechanism using ESP32 and Embedded C.
- **Web-Based Interface**: Developed an intuitive HTML-based user interface for seamless robotic manipulation.
- **Real-Time Remote Operation**: Enables precise control of the robotic arm from a web browser.

## Technologies Used
- **ESP32**: Microcontroller for handling the robotic arm’s movements.
- **Embedded C**: Programming language for controlling the ESP32.
- **HTML, CSS, JavaScript**: Frontend technologies for the web-based interface.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/4dof-robotic-arm.git
   cd 4dof-robotic-arm
   ```
2. Install the necessary libraries for ESP32 in the Arduino IDE:
   - WiFi.h
   - WebSocketsServer.h
   - Servo.h
3. Flash the ESP32 with the provided Embedded C code.
4. Open the web interface in a browser and connect to the ESP32.

## Usage
- Access the web interface from your browser.
- Use the control buttons to move the robotic arm in desired directions.
- Monitor real-time movements and adjust as needed.

## Future Enhancements
- Adding gesture or voice control.
- Implementing machine learning for automated movements.
- Expanding support for additional robotic peripherals.

## Contributing
Feel free to contribute by submitting pull requests or opening issues.

## License
This project is licensed under the MIT License.
