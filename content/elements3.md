---
title: About Me
---

## Table of contents

- Education
- Experience
- Skills

## Education

Undergraduate Student at Virginia Tech
- Mechanical Engineering Major
- Computer Science Minor
- Overall GPA: 3.56
- In Major GPA: 3.70

*Relevant Courses Taken*
- PHYS 1 (Mechanics) & PHYS 2 (Electricity and Magnetism)
- Multivariable Calculus 
- Linear Algebra
- Software Design and Data Structures (Java)
- Statics
- Differential Equations
- Manufacturing Processes Lab
- Engineering Analysis Numerical Methods (MATLAB)
- Elements of Materials Engineering

*Courses Taking Spring 2021* 
- Thermodynamics
- Circuits
- Mechanics of Deformable Bodies
- Dynamics



## Experience
**Undergraduate Researcher (Nest ML)** -- |January 2020 - Present| -- My partner and I are currently developing a system that 
enhances the capabilities of the Nest Thermostat. The system uses a Raspberry Pi to approximate the heat transfer 
using an inside temperature node and weather API data. It will then be able to intuitively learn what the ideal set temperature 
for the Nest thermostat will be to maintain the designated ambient temperature. I worked on the database component of the project which
logs temperature data and calculated values into a sqlite database. The logging database references a lookup table
composed of three columns: temperature node reading (inside), outside weather temperature, and Qtotal (heat transfer). This lookup table is prepopulated 
with each row containing a different realistic combination of temperature node reading and outside weather temperature.
So when the user inputs a set temperature through the nest, the temperature node and outside weather data can be referenced. These values
are then inserted into a SQL query that can quickly pinpoint the corresponding Qtotal value. We are currently working on relating this Qtotal value, which 
is calculated by using a combination of radiation and convection heat transfer equations, to the ideal set temperature 
for the Nest. My partner and I have been learning to implement a feedforward neural network system. This network will take the Qtotal value along with 
temperature node data and weather API to estimate the ideal set temperature for the Nest that best maintains the user's ambient temperature setting 
(what the user wants the house to feel like). 


**Formula SAE Recruit** -- |October 2019 - Present| -- I am a recruit for the Electric Powertrain Team (EPT). I helped design the 
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
- MATLAB
- Java Programming
- Python 
- SQL
- Arduino(C, C++)
- Raspberry Pi
- Machine Learning
- GIT
- BitBucket and GitHub
- Microsoft Office


