# Multi-mode Arduino Car
This involves building a car using an Arduino microcontroller. The car is equipped with ultrasonic sensors, a servo motor, and DC motors, controlled through Bluetooth (both remotely and via voice commands) or automatically. This is designed to navigate autonomously by detecting obstacles in its path and avoiding them by changing direction.
## Features
***

- [x] If an obstacle is detected within a specified distance (COLL_DIST), the car changes its path by moving backward and turning to avoid the obstacle..
- [x] Can be controlled remotely via Bluetooth using commands sent through a serial interface. 
- [x] Can also be controlled using voice commands, where commands such as forward ('f'), backward ('b'), right ('r'), left ('l'), around ('a'), and stop ('s') are recognized through Bluetooth.
- [x] Using the ultrasonic sensor, the car automatically changes direction when an obstacle is detected in front of it.
- [x] A servo motor is used to move the ultrasonic sensor to scan different directions.

## Technologies
***

- [x] Arduino Microcontroller
- [x] AFMotor Library
- [x] Servo Library
- [x] NewPing Library
- [x] Bluetooth Communication
- [x] Ultrasonic Sensor 

## Car Showcase
### Automatic mode
![auto](https://github.com/Rafia06/image/blob/main/WhatsApp%20Video%202025-01-20%20at%2002.04.20_d0c0da1a.mp4)

### Bluetooth control
![remote](https://github.com/Rafia06/image/blob/main/WhatsApp%20Video%202025-01-20%20at%2002.04.35_284df7bc.mp4)



