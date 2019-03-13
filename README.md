# ArduinoRover
Arduino Rover and Joystick

# Parts:
- For the Rover:
- - Arduino Mega
- - Chassis with two motors
- - NRF24L01 antena
- - Ultrasonic Module HC-SR04
- - L298N H Bridge
- - Piezo Buzzer
- - Two SG90 Micro Servo Motors
- - Camera Mount Platform
- - Battery (from 3 to 12V)
- For the transmitter:
- - Arduino Uno
- - MB102 Breadboard
- - NRF24L01 antena
- - Two PS2 joysticks
- - Two 4-legged buttons
- - Two resistors (from 100 to 300 Ohms each)
- - Battery (from 3 to 12V)

# Connecting the parts:
- Rover:
- - Motors:
- - - Connect the two motors to the motor pins on the L298N H Bridge
- - - 
- - NRF24L01 antena:
- - - SCK to Arduino PIN 52
- - - M0 to Arduino PIN 51
- - - M1 to Arduino PIN 50
- - - CSN to Arduino PIN 8
- - - CE to Arduino PIN 7
- - Piezo Buzzer:
- - - Buzzer(+) to Arduino PIN 3
- - - Buzzer(-) to Arduino GND
- - 
