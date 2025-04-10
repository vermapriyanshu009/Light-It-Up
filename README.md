# Light-It-Up
Developed a real-time system to control LED states via hand gestures, integrating computer vision and hardware control (Arduino Uno).

# 🤖 Hand Gesture Controlled LED System

A real-time system to control LED states using hand gestures, combining computer vision with embedded hardware (Arduino Uno). This project showcases human-computer interaction through intuitive hand movements—no physical switches required.

## 🚀 Features
- Real-time gesture detection and classification
- Dynamic LED control using hand gestures
- Seamless integration of software (Python) and hardware (Arduino)
- Recognized for innovation and shortlisted for a college science exhibition

## 🧠 Technologies Used
- **Python**
  - **Mediapipe**: Real-time hand landmark detection
  - **OpenCV**: Video capture and gesture visualization
  - **TensorFlow**: Custom gesture classification and model training
  - **PyFirmata**: Serial communication with Arduino
- **Arduino Uno**: Controlled via StandardFirmata firmware
- **Hardware Setup**: LEDs, breadboard, jumper wires

## 🛠️ Setup Instructions

### Hardware Requirements
- Arduino Uno
- LEDs (1–3 recommended)
- Breadboard & jumper wires
- USB cable for Arduino

### Software Requirements
- Python 3.x
- Required libraries:
  ```bash
  pip install mediapipe opencv-python tensorflow pyfirmata

### Arduino Setup:
Open Arduino IDE.
Upload the StandardFirmata sketch from:
File → Examples → Firmata → StandardFirmata

Connect the Arduino via USB.

### Make sure the correct serial port is configured in the script (e.g., COM3 on Windows or /dev/ttyUSB0 on Linux).

### VSCode: 
Step 1 --> Run the controller.py file.

Step 2 --> Run the new.py file.

For more help, refer youtube channel --> https://www.youtube.com/watch?v=hKbtfto9trw&t=130s&ab_channel=RoboTechZone
