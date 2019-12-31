# Radar 📡

 Radar is a simple simulator of radar technologies that scan a small area and draw the detected objects as points in a GUI.
 
## How it works 🤔
 
 This radar is built using an Arduino uno, servo motor and an utlrasonic sensor.
 
 The arduino order the servo motor to start rotating, and the ultrasonic sensor is places on the servo that it will rotate too, then the arduino start to calculate the distance from the data collected by the ultrasonic sensor.
 
 The arduino send this data, the angle and the distance, to the computer, that will be received by a python program that represent this informations as a point on the screen using the graphical interface library "pygame".

## Run the Radar

 All we need to do to run the radar is connect the arduino and check the port associated to it, then set the correct port in the python file so it will be able to communicate with the arduino.
 
## Prerequisites
 
 This project requires that you install python ( python 3 is used in this project), arduino ide, pygame library and pyserial library.
 
 ```
  python -m pip install pyserial
 ```
 
 ## Built With 🏗️
 
 * [Python3](https://www.python.org/) - python
 * [Pygame](https://www.pygame.org/) - pygame library
 * [Pyserial](https://pypi.org/project/pyserial/) - pyserial
 * [Arduino](https://www.arduino.cc/) - Arduino
 
 ## Note
 
  This project is published in [hackaday](https://hackaday.io/project/21228-radar) with more descriptions and photos.
  
 ## Authors ✍

* **Said Mohamad Ammar** - *Student in Lille University* 
