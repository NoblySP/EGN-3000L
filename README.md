# EGN-3000L
Code &amp; README text for Arduino Follower Robot

## Brief description of code
The code starts off with initializing all the variables that will be used in the project. Then, under the setup() function, pinMode() is used to configure the specified pins to behave either as an output or as an input. The loop() function contains the main logic of the robot. If the distance between the user’s hand and the ultrasonic sensor is between a certain amount, then the corresponding code within the if block activates. The code within the if block will control the 2 motors. By using the digitalWrite() function, certain pins can be given either a HIGH value or a LOW value depending on the movement that the robot needs to make.

## How Sparky works
As soon as Sparky is powered on, it plays a sound effect through the speaker. Then, the ultrasonic sensor starts measuring the distances. 
If the distance between the sensor and the user's hand is less than or equal to 10 cm, Sparky will move backwards. 
If the disatnce between the sensor and the user's hand is between 10 cm and 35 cm, Sparky will move forwards. 
If the distance between the sensor and the user's hand is more than 35 cm, Sparky will keep turning left. 

## TO-DO
Image of Sparky from Clash Royale (as source of inspiration)
Images of Sparky design prototype
Fabrication video
Images of assembled Sparky
