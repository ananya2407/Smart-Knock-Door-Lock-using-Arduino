# Smart-Knock-Door-Lock-using-Arduino

Security is one of the major concerns of today and digital security solutions have become an important part of daily households. To improve the security of households, the objective is to create a smart lock that will unlock using a specific knocking pattern.The smart knock door lock is an affordable security solution for households, implemented as a personal locking system and can be programmed to recognise different knocking patterns.

The lock is developed using Arduino Uno connected to a Piezo sensor and a motor for knock detection and door unlocking. The lock has features like, pattern detection, intensity detection and is also easily reprogrammable to a new knocking pattern. The simplicity of the lock adds to its features. The motivation was to provide an efficient security solution.


The device is designed using the following components – 
•	Arduino Uno
•	1 Piezo speaker (30mm)
•	1 SPST momentary Push Button
•	Motor
•	Resistors (1 M, 10k, 2.2k, 560 ohms)
•	1 NPN Transistor P2N2222A 
•	1 Rectifier Diode (1N4001 or similar)
•	Power – 9V battery
•	Buzzer
•	LEDs
•	Connecting wires
•	Box for setup

The Arduino Uno is programmed to recognize and distinguish between number of knocks, intensity of each knock and the tempo of the knock. The Piezo speaker is the knock sensor that listens for the knocks.

The Push button is used to reset the knocking pattern of the lock. The blue and green LEDs act as indicators for the knocks detected and blue LED glows thrice if an incorrect knock is detected. A buzzer alarms us in case of such a situation.

The green LED blinks if the knock detected matches to the pattern saved in the lock. The transistor and the rectifier diode are connected across the motor which helps unlock the door by turning the doorknob.

The system has a good degree of accuracy, being able to distinguish between number, tempo and intensity of various knocking patterns.
