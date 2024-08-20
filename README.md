![Bismuth Logo (2)](https://github.com/user-attachments/assets/0e810f82-dcf4-4951-af5d-ffe281d8f081)

# **BISMUTH** At A Glance
* Custom designed 3D printer _from scratch_
* 180mm * 180mm * 300mm bed size
* Cross Gantry Motion System
* Triple leadscrew Zed Axis
* Maxwell Kinematic Bed Joints

### This open source project is the culmination of over 100 hours of CAD, 20 hours of research, and many hours to come of building and firmware. As of this point, Bismuth is _just a cad design_. I am currently working on sourcing all of the parts to build this, after which I will work on firmware and tuning. You too can design your own printer. Use online models of other designs. Do research. Set goals. Most importantly, ask questions! I have learned so much from this project that I would not have known prior. 
------------
My Goals: 

Print Fast 🚗💨

Print Well ✅

Print Strong 💪

------------
![Main (14)](https://github.com/user-attachments/assets/005da63f-5968-4543-8921-6144759d0324)


Before I get into the specifications of the machine, you can find the full CAD design in [Onshape](https://cad.onshape.com/documents/ea3003fedda180a5827edece/w/24975c8a2f1006566d68c26a/e/f749387482ee518d7d44cc61).

There is also a [Bill Of Materials (WIP)](https://docs.google.com/spreadsheets/d/1hfmNby30dr6oSOva0FiEPYDqOrh_QXyWs_c3G39DLlM/edit?gid=0#gid=0)

_(While price was not something I thought about much for this design,  my goal was to have the final BOM come out to under $750)_

-----------



# Technical Specs   

I will go over each seperate section of my printer in detail, explaining the design requirements, what I chose, and why. During my design process I focused on a few key things: 
 
  Can It Be 3D-Printed? 🖨️
 
  Is It Easy To Repair? 🛠️

  Will It Let Me Accomplish My Goals? 🦾 
  
![Main (17)](https://github.com/user-attachments/assets/ce75745e-4e7a-479c-b75c-bcc664dc6d23)

------------
## Frame

* Utilizes 3030 Extrusion, Plasma Cut **Steel** Gussets, and 3D-Printed Brackets
* MGN12 Linear Rails, which are bigger and stronger than the more typical MGN9
* Fully enclosed to better print stronger "engineering grade" filaments
* Side panels are laser cut .125 in acrylic panels
* One of _two_ possible spool holders rests on the frame. It is the standard peg shape that mounts to the frame and holds the spool.
* 17"L * 16"W * 24"H Volume

There is a "Top Hat" on top of the printer that allows me to open the top of the printer to remove prints, introduce more airflow, etc. This is made with more 3030 extrusion and .125 in acrylic panels. It utilizes printed hinges to swing open/closed. 

  ![Main (15)](https://github.com/user-attachments/assets/77e26faf-cea2-4864-8dc5-db332c999d70)

**BISMUTH** has a back mounted electronics panel for easy access to the electronics. This is different from a more standard bottom mount electronics panel as it allows me to work on the printer without flipping it on its side. 

  ### Electronics 
  [BTT Octopus Pro Motherboard](https://biqu.equipment/products/bigtreetech-octopus-pro-v1-0-chip-f446?variant=40144816767074)
 
  [Raspberry Pi 4 Model B](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/)
  
  [Nitehawk-36 USB Toolhead Board](https://www.fabreeko.com/products/nitehawk-36-for-round-pancake-motors-usb-toolhead-by-ldo)
  
  [Meanwell 24V 350W Power Supply](https://www.amazon.com/MEAN-WELL-LRS-350-24-Switching-Printer/dp/B07SQLJG5L?hydadcr=19107_13375052&keywords=meanwell+24v+350w&qid=1696872093&sr=8-3&th=1)

  These electronics were picked after many hours of extensive research determining how many stepper motors I needed, how much power I needed, what co-processor I wanted, etc. 

![Main (16)](https://github.com/user-attachments/assets/821a31e8-a020-4f20-8880-78be07152c14)

----------
## X/Y/ToolHead


This assembly is the gem of the machine. It took me the majority of the time spent on this project on perfecting this part of the printer. It is, after all, the most important. 

![Main (18)](https://github.com/user-attachments/assets/973a0a51-c3c6-4970-bd9e-249151787005)

* Cross Gantry Motion system, a system similar to CoreXY, but has 2 linear rails forming a cross for increased stability
* Both the X and Y axis on this machine have 2 [Nema 17 46mm Shaft Stepper Motors](https://www.filastruder.com/products/ldo-stepper-motors-all-types?variant=39923122339911) each

  ### Tool Head
  My toolhead consists of:
  * [Sherpa Mini 2 Extruder](https://github.com/Annex-Engineering/Sherpa_Mini-Extruder)
  * [Bambu Lab](https://us.store.bambulab.com/products/bambu-hotend-x1c)/[E3D ObXidian Hotend](https://e3d-online.com/products/hf-obx-bambu)
  * Dual 4010 Blower Fans + Custom Fan Ducts for cooling
  * [Beacon Eddy Current Sensor for ABL](https://beacon3d.com/product/beacon/)
  * [Nitehawk-36 USB Toolhead Board](https://www.fabreeko.com/products/nitehawk-36-for-round-pancake-motors-usb-toolhead-by-ldo)

  These componants were all picked for their effectiveness, weight, price point, and size. My custom toolhead has a weight of under 325 grams!
  
  ![Extruder Assembly (3)](https://github.com/user-attachments/assets/90e3be61-e391-4f24-ba6a-c489960c05d8)

-----------
## Z Axis

The Z Assembly consists of the motion system and the bed mounting system. 

* Triple Leadscrew Motion System
* [Maxwell Kinematic Bed Mounting](https://en.wikipedia.org/wiki/Kinematic_coupling)
* Custom Machined MIC6 Aluminum Bed
* Magnetic Powder Coated PEI Spring Steel Bed

![Z Assembly](https://github.com/user-attachments/assets/33bc946c-1f25-4a07-9fd8-b9d33524e162)

----------
## Skirt
The Skirt is the last assembly of **BISMUTH**. It encloses the bottom of the printer and houses a few vital componants of the printer.

* Bento Box Carbon + HEPA Filter
* _Second_ filament holder _inside_ the printer for better packaging
* [HULA Anti Vibration Feet](https://makerworld.com/en/models/417509#profileId-502144)
* Holes for easy wiring

![Skirt Assembly](https://github.com/user-attachments/assets/8a701cf8-7781-447b-a4e5-ec6102f0ae6b)

---------
### Why Call It Bismuth?

Bismuth is a chemical element with atomic number 83. Wheh crystalized, it makes really awesome square-like crystal shapes, like the shape of this printer. Additionally, bismuth comes in all sorts of shapes and colors. When combined with other materials, it is used as electrical fuses and more! All of these factors combined makes the name Bismuth a perfect name for this printer! Plus, Bismuth is my personal favorite mineral :)

![image](https://github.com/user-attachments/assets/71cf03f4-cfa9-48e0-ac46-cd12883f80db)



![Main (19)](https://github.com/user-attachments/assets/64b1e7ce-e1e8-4ad6-a8eb-66caf02fe40e)


