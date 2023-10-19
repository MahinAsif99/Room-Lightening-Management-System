# Room-Lightening-Management-System
Design and Implementation of Room Lightening Management System  
1 Introduction:
Automatic Room Lighting System is a microcontroller based project that automatically turn on or off the lights in a room. Electricity, being one of the most important resources, must be utilized carefully. We often forget to switch off lights or fans when we leave a room. By using this system, we can intentionally forget about the lights as the system will automatically take care of them. The digital World we are living in allows us to use different technologies to automatically perform certain tasks. Such automation is very useful in certain areas like energy consumption, reducing human efforts, improving standard of living etc. The project implemented here is one such project where the microcontroller based system automatically controls the room lights. 

![image](https://github.com/MahinAsif99/Room-Lightening-Management-System/assets/148430248/57af9e33-20e4-4bb0-9d01-65360fc1da70)

1.1	Objectives
The aim of this project is to automatically turn on or off the lights in a room by detecting the human movement. We implemented this project using PIC18 Microcontroller and an Infrared (IR) sensor.
![image](https://github.com/MahinAsif99/Room-Lightening-Management-System/assets/148430248/57840b22-79f3-469c-8a2f-f4e5253ccbf0)

1.2	Features
•	Entrance and exit of a person.
•	IR sensors used so to indicate entrance and exit of a person.
LED turned ON and OFF when a person enters and exits.

1.3	Circuit Components
•	PIC18F452 Microcontroller. 
•	Bread Board.
•	Infrared Sensor.
•	16 x 2 LCD Display.
•	Lamp.
•	Connecting Wires.
•	Power Supply.

1.4 Circuit Diagram
![image](https://github.com/MahinAsif99/Room-Lightening-Management-System/assets/148430248/08c9d4bd-252b-4e06-9801-d905cf88606e)


1.5 Proposed Methadology
In this project, an automatic room lighting system is developed using PIC18F452 microcontroller. The main component of the project is IR Sensor. The placement of the sensor is important as it will determine the functioning of the project.
Practically speaking, the sensor must be placed on the either side of the door or entrance of the room. When a person tries to enter the room, the sensor detects the person first then the light will turn on. And vice versa when the person is leaving the room.
When a person tries to leave the room, the sensor again detects the person. This process will make the microcontroller to understand that a person is trying to leave the room and hence, the exit of the visitor. The microcontroller will not turn off the light until the last person has left the room.
When a person tries to enter the room, the sensor detects the person first. This action will indicate the PIC18F452 Microcontroller that the person is entering the room. Hence, the microcontroller will turn on the light and which indicates “system-detect”. 
As the visitors start leaves, the light will turn off which indicates “system-not-detect”. During this point, the microcontroller understands that there is nobody in the room and turns OFF the light.


1.6	Simulation Results
The lights in the room automatically turns ON detecting a human motion and is ON until unless the person has left. Initially, when there is no human movement, the IR Sensor doesn’t detect any person. As the person exits the room, the change in infrared radiation in the room is detected by the IR Sensor. This will turn OFF the Light. The light stays turned off as long as there is no movement in front of the sensor. 

1.7Hardware/software simulation results
Results:
When a person enter the room the IR sensor immediately detects through its IR radiations. The light is on until unless the person leaves the room. As soon as the person exits the room the sensor detects it and notifies the microcontroller.
•	Software Stimulation results:
The software implementation was done through assembly language coding on MPLAB IDE and circuit implementation on PROTEUS.
 
![image](https://github.com/MahinAsif99/Room-Lightening-Management-System/assets/148430248/6e01e0c7-463e-4015-ae85-a14f96472254)
![image](https://github.com/MahinAsif99/Room-Lightening-Management-System/assets/148430248/ec2f4618-4e2d-4905-8282-ac913b6a7a59)

•	Hardware Result:
If a person enters a room the sensor immediately detects it and indicates the controller, which in turn the LED is turned ON and the sensor displays it. Same is the case when the person exits.
![image](https://github.com/MahinAsif99/Room-Lightening-Management-System/assets/148430248/5c90e5fa-0564-4ecc-851b-d9d05ab0ed6c)

4.2	Design / simulation parameters
The design and stimulation parameters of the project are that we can implement this project in college’s classroom. We can apply a bidirectional counter and count the number of people entering in a room and as per set time it send the person count on mobile number of head to inform about, how many are presented? It also control the lights or fans of a room.

4.3	Discussions etc…
When project is turned ON, It automatically initializes I/O pins. After that it checks sensor’s output. If the sensor 1 detects, the microcontroller will detect it and display it on the LCD display. The LED will light up.

5	Conclusions
This project gives us an idea to detect the motion. This project can be used anywhere either at home or offices. It is very much cost efficient and can be used easily and efficiently. This system is designed using various devices like IR sensor, Pic18 microcontroller, proteus, power supply and various electronic components. The proposed system avoid unnecessary energy consumption and helps in energy saving.




