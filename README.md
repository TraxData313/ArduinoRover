# ArduinoRover
Arduino Rover and Joystick

# Parts:
- For the Rover:
- - Arduino Mega
- - Chassis with two motors
- - L298N H Bridge
- - NRF24L01 antena
- - Ultrasonic Module HC-SR04
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
- - Motors to H-Bridge:
- - - Connect the two motors to the motor pins on the L298N H Bridge
- - - Check the picture for reference: https://github.com/TraxData313/ArduinoRover/blob/master/MotorsConnections.PNG
- - L298N H Bridge to Arduino:
- - - L298N 5+ Pin to Arduino 5V
- - - L298N 12+ Pin to Battery(+)
- - - L298N GND Pin to Arduino GND
- - - NOTE: Connect each L298N MCU pin to 5V briefly, and write down what motion it induces.
- - - NOTE: For example, if when you touch MCU pin 1, the left wheel moves back, write down MCU1=LeftBack
- - - NOTE: Once you have that reference, connect the MCU pins this way:
- - - L298N MCU Pin leftForward to Arduino PIN 9
- - - L298N MCU Pin leftBack to Arduino PIN 6
- - - L298N MCU Pin rightForward to Arduino PIN 5
- - - L298N MCU Pin rightBack to Arduino PIN 4
- - NRF24L01 antena:
- - - SCK to Arduino PIN 52
- - - M0 to Arduino PIN 51
- - - M1 to Arduino PIN 50
- - - CSN to Arduino PIN 8
- - - CE to Arduino PIN 7
- - Piezo Buzzer:
- - - Buzzer(+) to Arduino PIN 3
- - - Buzzer(-) to Arduino GND
- - Ultrasonic Module HC-SR04:
- - - Module TrigPin to Arduino PIN 40
- - - Module EchoPin to Arduino PIN 38
- - - Module VCC Pin to Arduino 5V
- - - Module GND Pin to Arduino GND
- - L298N H Bridge to Arduino
