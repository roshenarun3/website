---
title: About Me
---

## Table of contents
---

> Education

> Experience

> Skills

## Education
---

Undergraduate Student at Virginia Tech
- Robotics and Mechatronics Major (Mechanical Engineering)

*Courses Taking Fall 2022* 
- Robotics and Automation
- Mechatronics: Theory and Application
- Engineering Design and Project




## Experience
---
**Undergraduate Researcher (Nest ML)** -- |January 2020 - May 2022| -- The goal of this project was to develop a system that 
enhances the capabilities of the Nest Thermostat. The system uses a Raspberry Pi to approximate the heat transfer 
using an inside temperature node and weather API data. It will then be able to intuitively learn what the ideal set temperature 
for the Nest thermostat will be to maintain the designated ambient temperature. I worked on the database component of the project which
logs temperature data and calculated values into a sqlite database. The logging database references a lookup table
composed of three columns: temperature node reading (inside), outside weather temperature, and Qtotal (heat transfer). This lookup table is prepopulated 
with each row containing a different realistic combination of temperature node reading and outside weather temperature.
So when the user inputs a set temperature through the nest, the temperature node and outside weather data can be referenced. These values
are then inserted into a SQL query that can quickly pinpoint the corresponding Qtotal value. The next step was to relate the Qtotal value 
to a set temperature for the Nest with machine learning. Over two semesters, we tried using two different methods of data collection to train 
a model. The first method was an automated thermal chamber to obtain relevant temperature metrics on a small scale. After I built this chamber and
started data collection, we concluded the chamber was too simplified and not accurately related to a house. This led us to the 
second method, building a automated temperature collecting node that collects relevant data features at each of our houses. This data 
was used to train a model that used a gradient boosted classifier to understand if a user is hot, cold, or comfortable. Additionally, 
the automated temperature collecting node had buttons that allowed the user to input how they felt (hot, cold, comfortable). 


**VT RockSat Finite Element Analysis (FEA) Engineer** -- |January 2021 - May 2022| -- I learned about the basics of 
modal analysis and static structural analysis. I completed a static stress analysis of the boom under estimated loads. Additionally, 
I completed modal analysis to ensure components natural frequencies were in designated ranges. This experience set my foundation that 
I was able to build on at Northrop Grumman in Finite Element Analysis. 

**Formula SAE Recruit** -- |October 2019 - October 2020| -- I was a recruit for the Electric Powertrain Team (EPT). I helped design the 
Emrax motor casing and PCB mounts for the Electric Vehicle (EV). The CAD Software used in designing was mainly NX12 and SOLIDWORKS. 
I additionally learned about the mechanics of both EV and internal combustion (IC) vehicle through attending different subteam meetings. The 
engine team taught me about the stages of combustion: intake, compression, combustion, and exhaust. Additionally, I helped service 
our transmission as there were issues with a chipped gear. The suspension team also taught me the extreme importance of a 
differential and the inner spider gears, which enable the power to be transmitted from the crankshaft to the wheels. 

**VEX Robotics** -- |2016 - 2018| -- I was the mechanical lead of the "Trial and Error" robotics
team at Rock Ridge High School. I mainly specialized in the chassis and drivetrain design. I used gear ratios that 
maximized speed or torque depending on our objective. I also used different servo configurations, giving me an understanding 
of both physical and software aspects of servos. 

**Air and Space Museum Intern**  -- |Summer 2019| -- I was an intern at the Smithsonian National Air and Space Museum. I 
taught the public about the fundamentals of flight using a Cessna exhibit. I also developed my public speaking and 
interpersonal skills through explaining how the Wright Flyer functioned to people of all ages. 

**NASA Langley Summer Academy**  -- |Summer 2018| -- I was on a team to design a manned mission
to Mars which would be pitched to a NASA panel of current employees. I served as a power specialist on the Mission 
Integration subteam. The final power system design for the crew transit vehicle (CTV) was to use solar panels as the main source of power
with radioisotope thermoelectric generators (RTGs) as a secondary source. Once on the surface of Mars, the main power source would be 
hybrid system of solar power and kilopower. 

## Skills
- CAD Software (SOLIDWORKS, NX12)
- Finite Element Analysis (Femap, Nastran)     
- Drone Hardware 
- Drone Software (Ardupilot, DroneKit, Software-in-the-loop)
- MATLAB
- Mathematica
- Java Programming
- C Programming
- Python 
- SQL
- 3D Modeling and Manufacturing 
- Arduino(C, C++)
- Raspberry Pi
- Robotics 
- Mechatronics
- GIT
- BitBucket and GitHub



