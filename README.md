![Bismuth Logo (1)](https://github.com/user-attachments/assets/9c9e8940-ce27-4102-9270-910c59ca3b7a)

# What Is **BISMUTH**?
**BISMUTH** is my custom designed 3D printer that I designed _from scratch_ to fufill my dream of making my own super-printer. It has a 180mm * 180mm * 300mm bed size, and utilized a Cross Gantry Motion System with a triple leadscrew setup and Maxwell Kinematic Bed joints.

### This project is the culmination of over 100 hours of CAD, 20 hours of research, and many hours to come of building and firmware. As of this point, Bismuth is _just a cad design_. I am currently working on sourcing all of the parts to build this, after which I will work on firmware and tuning. You too can design your own printer. Use online models of other designs. Do research. Set goals. Most importantly, ask questions! I have learned so much from this project that I would not have known prior. 
------------
My Goals: 

Print Fast 🚗💨

Print Well ✅

Print Strong 💪

------------
![Main (11)](https://github.com/user-attachments/assets/4e9a6585-c2a4-4801-9d20-e600c330fde5)


Before I get into the specifications of the machine, you can find the full CAD design in [Onshape](https://cad.onshape.com/documents/ea3003fedda180a5827edece/w/24975c8a2f1006566d68c26a/e/f749387482ee518d7d44cc61).

There is also a [Bill Of Materials (WIP)](https://docs.google.com/spreadsheets/d/1hfmNby30dr6oSOva0FiEPYDqOrh_QXyWs_c3G39DLlM/edit?gid=0#gid=0)

_(While price was not something I thought about much for this design,  my goal was to have the final BOM come out to under $750)_

-----------



# Technical Specs   

I will go over each seperate section of my printer in detail, explaining the design requirements, what I chose, and why. During my design process I focused on a few key things: 
 
  Can It Be 3D-Printed? 🖨️
 
  Is It Easy To Repair? 🛠️

  Will It Let Me Accomplish My Goals? 🦾 

------------
## Frame

### ![Frame Assembly (1)](https://github.com/user-attachments/assets/932d1e86-c070-43b9-b76d-8c26dee534a9)

Utilizing 3030 Extrusion, Plasma Cut **Steel** Gussets, and 3D-Printed Brackets, this is one heck of a beefy frame. The reason this frame is so strong is because I intend to push the speed as much as possible, and a big, sturdy frame is key for that. Additionally, I wanted to use MGN12 Linear Rails, which are bigger and stronger than the more typical MGN9. Again, this was so I could push my printer as fast as possible. 

**BISMUTH** is fully enclosed to better print stronger "engineering grade" filaments. My side panels are laser cut .125 in acrylic panels.

There is a "Top Hat" on top of the printer that allows me to open the top of the printer to remove prints, introduce more airflow, etc. This is made with more 3030 extrusion and .125 in acrylic panels. It utilizes printed hinges to swing open/closed. 

One of _two_ possible spool holders rests on the frame. It is the standard peg shape that mounts to the frame and holds the spool. 

![Frame Assembly (2)](https://github.com/user-attachments/assets/fb020cc0-4156-4579-a920-cbdc4171d8d5)

**BISMUTH** has a back mounted electronics panel for easy access to the electronics. This is different from a more standard bottom mount electronics panel as it allows me to work on the printer without flipping it on its side. 

  ### Electronics 
  [BTT Octopus Pro Motherboard]([url](https://biqu.equipment/products/bigtreetech-octopus-pro-v1-0-chip-f446?variant=40144816767074))
  [Raspberry Pi 4 Model B]([url](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/))
  [Nitehawk-36 USB Toolhead Board]([url](https://www.fabreeko.com/products/nitehawk-36-for-round-pancake-motors-usb-toolhead-by-ldo))
  [Meanwell 24V 350W Power Supply]([url](https://www.amazon.com/MEAN-WELL-LRS-350-24-Switching-Printer/dp/B07SQLJG5L?hydadcr=19107_13375052&keywords=meanwell+24v+350w&qid=1696872093&sr=8-3&th=1))

  These electronics were picked after many hours of extensive research determining how many stepper motors I needed, how much power I needed, what co-processor I wanted, etc. 

  
## X/Y/ToolHead

This assembly is the gem of the machine. It took me the majority of the time spent on this project on perfecting this part of the printer. It is, after all, the most important. 

![Extruder Assembly (1)](https://github.com/user-attachments/assets/6d3d3b6e-9b3a-4a7e-bc12-56f0570dbb62)

**BISMUTH** uses a Cross Gantry Motion system, a system similar to CoreXY, but has 2 linear rails forming a cross for increased stability, especially at higher speeds. Both the X and Y axis on this machine have 2 motors each, leading to increased amounts of torque without losing speed. I used [Nema 17 46mm Shaft Stepper Motors](https://www.filastruder.com/products/ldo-stepper-motors-all-types?variant=39923122339911) for my X and Y axis due to their power and speed, which was necessary to achieve my goals. 

  ### Tool Head
  My toolhead consists of 
## Z Axis



## Skirt

### Why Call It Bismuth?

Bismuth is a chemical element with atomic number 83. Wheh crystalized, it makes really awesome square-like crystal shapes, like the shape of this printer. Additionally, bismuth comes in all sorts of shapes and colors. When combined with other materials, it is used as electrical fuses and more! All of these factors combined makes the name Bismuth a perfect name for this printer!



![Main (12)](https://github.com/user-attachments/assets/8f1930d0-68b5-478f-8c8d-24d834be3062)

Motherboard - BTT V1.4 w/ MOTv1.0 for a total of 8 stepper motors


Power Supply - MeanWell 24V 350W Power Supply 


Heated Bed: Custom with something idk yet


Stepper Motors - 


Nozzle - Hardened CHT Nozzle with standard M6 Threads. 


Extruder - Sherpa Mini


Display: Will get octoprint set up, but also hoping for a nice touchscreen


Firmware: I will get a custom klipper profile set up


Auto Leveling: I will have autoleveling, just unsure as to how. 


Core XY machine, 3 Motor Leadscrew with kinematic joints to have tramming


Enclosed, hoping to reach chamber temps of ~60C at least, 


Hotend: Phateus Rapido HF


Nevermore Carbon Filter to allow for printing of all materials safely. 


Links:


