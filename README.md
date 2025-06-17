# Flood-Detection-and-Alert-System-Using-Arduino-
Designed and implemented a real-time flood detection system using an Arduino  board and IoT sensors to monitor water levels and send early warning alerts.  Technologies Used: Arduino, Ultrasonic/Water Level Sensors, GSM Module, IOT , C/C++.
Components:
Arduino UNO/Nano
HC-SR04 Ultrasonic Sensor
SIM800L GSM Module
16×2 LCD Display (I2C)
Buzzer
Jumper Wires and Breadboard

Connections:
HC-SR04 Ultrasonic Sensor:
VCC → 5V (Arduino)
GND → GND (Arduino)
Trig → Pin 9 (Arduino)
Echo → Pin 10 (Arduino)
SIM800L GSM Module:
VCC → 5V (Arduino)
GND → GND (Arduino)
TXD → Pin 7 (Arduino)
RXD → Pin 8 (Arduino)
16×2 LCD Display (I2C):
VCC → 5V (Arduino)
GND → GND (Arduino)
SDA → A4 (Arduino)
SCL → A5 (Arduino)

Buzzer:
Positive leg → Pin 11 (Arduino)
Negative leg → GND (Arduino)

# circuit diagram
![Screenshot 2025-06-17 203030](https://github.com/user-attachments/assets/4e7022fb-c541-4839-a6c1-0ad07299679f)


# Normal Condition
LCD Display:

Distance: 50 cm
Water Level: Safe
Buzzer: Silent
GSM Module: No SMS sent
# Flood Condition
LCD Display:

Distance: 10 cm
Flood Detected!
Buzzer: Continuous tone
GSM Module: Sends SMS: Flood Alert: Water level is critical!


