# Burglar-Alarm
This is a Burglar Alarm system programmed on Arduino IDE and Matlab.

The system runs on hardware that includes a buzzer, keypad, sensors, an actuator, and a camera. 
The code on Arduino runs the general program controlling the sensors and actuators however it communicates with Matlab which runs the other part of the code which prints instructions to the screen as well as runs face recognition.
All the details of the system along with flowchart diagrams are included in the "Burgular Alarm Project Details.pdf File.

It is important to note that the facial recognition algorithm included in the code is a development of a program written by Brett Shoelson.
The original facial recognition files and script written by Brett can be found on:
https://uk.mathworks.com/matlabcentral/fileexchange/49914-streaming-face-detection-training-recognition

How to run the program:
1- Assemble your hardware and connect it to the Arduino
2- Connect your Arduino to the computer
3- Open 'Simple_Full_Arduino_Code.ino' Arduino code found in the 'Arduino Code.zip' folder and upload the code onto your Arduino.
4- Open 'Matlab_arduino_communication.m' Matlab script found in the 'Matlab_Arduino Communication and Face Recognition Code.zip' folder and run that code

Notes: 
- You may need to alter the port your arduino is connected to in both 'Matlab_arduino_communication.m' and 'streamingFaceRecognition.m' Matlab script files found in the 'Matlab_Arduino Communication and Face Recognition Code.zip' folder in order for your code to run.
- Also make sure to check the notes written in the beginning of the 'streamingFaceRecognition.m' Matlab script to ensure you have all the relevant additional Matlab Packages installed and everything else is set up properly.


Lara Abouelnour
Created in May 2022
