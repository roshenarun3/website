---
title: Magic Mirror
---

## **Table of contents**
----
> ### Overview

> ### Main Takeaways
>* Raspberry Pi/Linux
>* Software Concepts



## Overview
----
{{< figure src="/images/mirror.jpg" title="Magic Mirror" height="400" >}}
This project was an extremely fun, enlightening, and useful build. The magic mirror concept 
has been around for a while, so there are numerous github pages and videos explaining 
how to build one. However, I added certain widgets and went for a frameless design
to further personalize my mirror. The mirror itself is comprised of a wooden frame and glass with a two-way mirror film. 
When light is blocked out from one side of the film, the other side becomes completely reflective. Since the program runs a 
black background, the text and images shine through the glass while the background is reflective, 
creating the magic mirror effect. No matter how many times I check my mirror, the view never gets old. 

## Main Takeaways
----
### Raspberry Pi/Linux 
{{< figure src="/images/mirror2.JPG" height="300" class="pull-left"  >}} 
Everything about the Raspberry Pi and Linux was relatively new to me, from uploading the OS onto the SD card to 
maneuvering around files throughout the device. This experience allowed me to learn **bash commands** to alter, move, and 
work with files. I also furthered my understanding of **Git** as I used clones from github to obtain localized versions of 
files and add-ons. Additionally, I configured my Raspberry Pi to my MacBook Air through **Microsoft Remote Desktop**. This allowed 
me to remote access my Raspberry Pi without having to directly use the mirror. Another learning experience I had was with the **audio inputs and 
outputs** of the Raspberry Pi. I configured a usb microphone and usb speaker to the Raspberry Pi. However, I couldn't get my Python script, 
which transferred the microphone input into text through **google's voice recognition library**, to register the microphone. Based on 
online forums, there seemed to be issues with Raspberry Pi 4 **audio drivers** which were common but extremely hard to solve. Overall I have learned and 
experimented with my Raspberry Pi, facilitating me with experience that can be not only be applied to Raspberry Pi devices but 
also other linux devices and projects down the line. 

### Software Concepts
The magic mirror software exposed me to different types of files and computer science concepts. **API keys** were a crucial concept 
to understand, enabling the magic mirror to obtain localized information and weather. I added a Spotify module that used 
**OAuth Tokens** which allow the magic mirror to obtain user data from my Spotify account. These two concepts are very powerful in terms 
of application building and obtaining data. I also added a significant amount of phrases that would change according to the 
 weather and time of day. This was implemented using a standard decision structure in JSON. Moving forward, I plan to experiment and research
 further into **JSON** for web development purposes as it remains an incredibly powerful tool. 







