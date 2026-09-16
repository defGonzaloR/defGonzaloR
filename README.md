# Welcome to my portfolio!
I am currently a junior Electrical Engineering student at Rutgers University

Exploring robotics, power distribution and electrical system design, machine and reinforcement learning, and previously interned at Reworld Waste, a Thermal Test Facility (TTF) transforming waste into energy.

A bit about me is I love to learn everything about engineering, not just Electrical Engineering as a discipline. I'm currently throwing myself into embedded systems design through my flight control system project, while also learning about Multi-modal learning models through a course at Rutgers, so I definitely love exposing myself to everything possible. And yes I love comics and video games, Spider-Man is definitely my favorite superhero right now.


contact me at: gonzalomramos356@gmail.com

# Table of contents + section overviews

1. ***Work Experience***
   
   1.1 **Reworld Waste**

2. ***Projects***
   
   2.1 **Rutgers Dynamics Quadruped**
   
   2.2 **STM32 Flight Controller** 

   2.3 **Hexapod** 

   2.4 **Micromouse** 
   
   2.5 **Valentines PCB** 
   
4. ***Hackathons***
   
   3.1 **MakeCU 2025** (Roach Busters)
   
   3.2 **StarkHacks 2026** (Assisted Eating Device)
   

# 1. Work Experience
# 1.1 Engineer Intern @ Reworld Waste
For my summer 2026 internship, I assisted Reworld's Essex location and their engineering department in various projects, applying skills such as AutoCAD design, P&ID (Piping and Instrumentation Diagram) documentation, and overall project management. 
It was a great introduction to the utilities industry, and I learned so much about it and Reworld as a company. I gained lots of industry connections, and it was a great first internship as I had free reign to work on whatever I wanted to.
I primarily worked on the AutoCAD design of access ports and P&ID documenation. For my access port projects, it consisted of me walking down third-party contractors of desired locations of the access ports, measuring out the area, and then designing based of several designs already in the plant, so I became super familiar with numerous systems there!

<img width="1416" height="866" alt="image" src="https://github.com/user-attachments/assets/227442b7-992a-4572-8ead-c89c9eb66190" />


A drawing I made for the fabrication / installation of a port door of a duct within the facility, my first design made in AutoCAD


<img width="1429" height="845" alt="Screenshot 2026-08-11 133238" src="https://github.com/user-attachments/assets/d4fa3af5-a4da-4a7a-9d13-4de37b02dcaf" />


<img width="701" height="483" alt="image" src="https://github.com/user-attachments/assets/d64169ed-b8be-411c-a5bc-6b714b068660" />

<small>A P&ID I made recently for the pneumatic devices attached to the boilers, I helped document the design made by the lead engineer</small>.

<img width="421" height="446" alt="image" src="https://github.com/user-attachments/assets/07cc3409-c688-4692-a50e-9064994b5213" />

<small> I get to see a lot of electrical systems in and around the plant! This one is used for training </small>

# 2 Projects
## 2.1 Rutgers Dynamics Quadruped
During my academic career at Rutgers University, I've grown increasingly interested in pursuing robotics projects, and this summer hope to increase my fluency in robotic systems.
As a founding member and Co-President of Rutgers Dynamics, I learned all about power distribution systems and gained my first experience with robotics. It was here I collaborated with several subdivisions and learned about reinforcement learning, 3d modeling, and kinematics on top of what I learned through upperclassmen involved in the electrical division. This upcoming year I strive to lead the organization to an open-source, inexpensive approach to robotics to help those who were in the same shoes I was in.

My contribution to this project was designing v2 of the board, shown in my repo for it, that was heavily inspired by our v1. It was my first time designing power distribution, and I got to learn a lot about signal integrity, filtering, and copper pours. We did all of our testing on v1, results that I used to make changes on v2, which will soon be updated to a third version by our new Electrical lead and his team

<img width="475" height="325" alt="image" src="https://github.com/user-attachments/assets/d071a33f-db09-4fc2-8f02-4c6425ef78d3" />


## 2.2 Flight Controller 

The easy part of this project will be the electrical design, which is already 98% done, aside from final design/electric rule checks. My goal for this project is to build a full fledged flight control system, including the shown PCB, a Simulink simuation of the system, and finally full development of required firmware -- something I'm super excited to get into. The hardest part of this project is funding it, as the GPS components can definitely get a little pricier. This is my most recent electrical design and I definitely think its my best, but I hope to come back to it repeatedly to apply whatever tracing/layout theory I learn.


<img width="772" height="529" alt="image" src="https://github.com/user-attachments/assets/04733dd8-e6a0-4f70-ba65-0233418dc9d6" />


## 2.3 Hexapod 
Of course, in a club setting, it's very difficult to gain experience in all facets of robotics design, so this summer I gave myself the challenge of designing my own from scratch. I'm currently in the 3D modeling phase (I have so much to learn!). It's both a humbling yet educational endeavor that I hope to show off once completed. Right now I'm on the design of the leg, and after I complete a fully modeled design, I plan to apply what I've learned about reinforcement learning

My next step is to complete fabricaton and test this board, but I also want to create a V2 to implement even better signal integrity design choices, such as isolating from the Raspberry Pi logic, something I didn't do to initially save money on components.


<img width="1010" height="523" alt="image" src="https://github.com/user-attachments/assets/3b97dda3-5ae8-49ef-803d-5665c55e5383" />

<img width="846" height="466" alt="MMVRH_PDB1" src="https://github.com/user-attachments/assets/fb981d26-4eeb-4939-8e3f-c1ccf090b428" />

<img width="1156" height="607" alt="MMVRH_PDB" src="https://github.com/user-attachments/assets/5b9e3dcc-18f8-4bc9-962a-6b3b3839c6ae" />



## 2.4 Micromouse
This was my first time designing a PCB, which is definitely noticeable. I think after this project I definitely gained more confidence in the process, for example, I'd probably never implement header pins for a microcontroller, instead I'd just design around the original chip for a better form factor. This PCB had so many mistakes in it but it taught me to be intentional with all of my design choices.

<img width="396" height="341" alt="image" src="https://github.com/user-attachments/assets/40029660-6f4a-43fa-9410-061a155c7d96" />

## 2.5 Valentines PCB

As a cute side project for Valentines day, I designed an astable 555 timer based circuit that lit up red LEDs. I definitely learned a lot through my mistakes from this project, such as picking the appropriate battery holder and designing with surface mounted LEDs.
If you're familiar with cheap electronic design, you'll notice the 555 timer in the heart of the board. I picked this idea up from a lab of mine at school, and I thought it was really cool. If I redesign this, I want to switch to THT LED's as I didnt have a heat gun to properly solder the smd components on.
<img width="505" height="385" alt="image" src="https://github.com/user-attachments/assets/caa6db93-92dd-4bbb-a205-9744d3cc5a2f" />


# 3 Hackathons
## 3.1 MakeCU 2025 (Roach Busters) : https://devpost.com/software/roach-buster

My first ever hackathon and my first ever project, especially with a team. Our goal was to integrate sensor and AI capabilities to detect and prevent roach infestations, something homeowners go through at least once in their lives. What could've been a simple point & click app was realized into a handheld prototype, designed to take photos and help prevent and combat infestations through informative next steps. The highlight of this project, however is its RF capabilities, using wifi signals to look within walls for any movement, signalling towards possible infestations within your home.

My involvement on this project was the electrical design, where I gave a lot of input into choice of parts and helped program the Arduino/ RF components.

## 3.2 StarkHacks 2026 (Assisted Eating Device): https://devpost.com/software/assistive-eating-device

At this hackathon, one of the sponsors was AMD, so we used their given SO-101 arm design and provided GPU capabilities to train a VLA model. What it does it remember (through hours of training) movements to swap out utensils on it's arm, and then feed the patient. The target demographic for this project are those who are physically impaired and can't feed themselves, and to further build on that idea, on top of assisting with training and assembly I also worked on the front-end aspect of the care-taker application that connects to the ESP32 present in the design. Through this, they can ensure that the automation is working well on its own while taking care of other necessary tasks.

Watch an early demonstration on our devpost linked above.
