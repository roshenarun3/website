---
title: Alfred - Robot
---

## Table of contents

* Overview
 --
* Main Tasks
--
  - Software
  - Hardware


## Overview
----
{{< figure src="/images/ALRED.jpg" title="Magic Mirror" height="400" >}}
ALFRED is an emotional support robot that resides on my desk. The main purpose of the robot
was to gain experience using Arduino microcontrollers, sensors, and servos. ALFRED is a 4 axis robotic arm, utilizing 
four servo motors and a gesture sensor (PAJ7620U2). It can sense numerous hand signals and react accordingly. ALFRED can 
also respond to its own name. I am currently working on further developing this ability as I am dependent on google's 
voice recognition library. A project I am looking into for furthering my **machine learning** knowledge is to implement a 
**neural network** that can recognize the name ALFRED. Moving forward, I hope to applying new computer science and
mechanical engineering concepts I learn from my classes.

## Main Tasks
----
### Software
{{< figure src="/images/mirror2.JPG" height="300" class="pull-left"  >}} 
From a software standpoint, Arduino uses **C/C++**. Since I took two **data structures and algorithms classes in Java**,
the functionality and syntax was relatively straightforward to learn. The Arduino IDE is incredibly helpful for downloading and locating packages 
for specific sensors and servos. After I downloaded the necessary packages, I ensured the file paths were correct and the 
packages were being referenced in the code. Then, I wrote a sketch using a decision structure based on the gesture sensor 
reading which activated the corresponding servo positions and movements. A crucial step was finding each servo's position
limit which is dependent on the design of the arm. During my mechanical design phase of the robotic arm, I wasn't paying attention 
to the orientation of the servos and snapped an arm clean in half. That's when I limited the servo positions to ensure that each servo can't 
break the arm. 

### Hardware
The first major step in the construction of ALFRED was building a functional arm. I used basic *statics* and my understanding of 
weight distribution to construct the arm. Once I was satisfied with the design, I had to integrate the servos, wiring, and 
sensor. I used **Ohm's law** when choosing a power source and wiring path for the servos, ensuring that all the servos were sufficiently
powered. The servos were powered by a 5V DC power supply, while the Arduino directly powered the gesture sensor with 3.3 volts. In order for the gesture sensor to function with the Arduino, I had 
to **solder** the header pins to the sensor, enabling me to use Arduino jumper wires. Finally, I connected all the components 
using a breadboard to keep track of the wiring. I added a singular LED to the servo power circuit to have a visual cue when its active. This 
cue is mainly added precaution to ensure people, including myself, understand when the circuit is live and prevents people from shocking themselves. 