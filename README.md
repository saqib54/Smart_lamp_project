# Smart_lamp_project
this project is andriod development based and iot based project having physical and app design
he Smart Lamp is a system designed to control LED lights through voice. The voice control is facilitated by a mobile application utilizing the 'PocketSphinx' library, which includes wake word detection for initiating voice recognition. 'PocketSphinx' is an open-source speech recognition toolkit created by CMUSphinx (https://cmusphinx.github.io/). The current voice recognition model in the application has limited accuracy, as it relies on the default CMUSphinx model. I encourage you that use this system to build your own model and train it for better accuracy. To use the system, simply say 'hey phoenix,' followed by 'commands' to issue voice commands. These commands are then sent via HTTP requests, managed by the 'Volley' library, to the ESP32. When the request is successful, you'll observe the LED turning on in your circuit. There are also additional features to control LED such as set timer to LED for it to be turned off and change LED colour. You can also see data analysis where it monitor current in the circuit using ACS712 sensor. This feature used to monitor if there is a problem to the circuit then you will see the current dropping or no current flow by using the graph shown in the feature. Moreover, you can control manually if you do not prefer control using your voice.
 
Video Tutorial
https://youtu.be/qMK6ij1JYLE
Software Requirements
Software	Version
Arduino IDE	
Version 2.2.1 Recommended

CLI Version 0.34.0 Recommended

Android Studio	
Version Hedgehog 2023.1.1 Recommended

Graddle Version 8.3 Recommended

SDK Version 34 Recommended

JDK Version 21 Recommended

Hardware Requirements
Hardware	Specification
	ESP32 WROOM-32
	GL-12 Breadboard
	RGB LED
	ACS712 5A Module
	220Ω Resistor
	Jumper Wires
	KF301 2-Pin Terminal Block Connector
	3.7V LiPo Battery
Wiring Diagram
Circuit-Diagram

Basic Flow of The System
How-It-Works-Image

Mobile Application Interface
Potrait View
       

Landscape View
    
