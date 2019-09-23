# open-source-snes-controller
Open Source Hardware implementation of a SNES controller


## Project Goals

 1 Create a cheap, lagless, non-ghosting SNES controller
 2 Have an easy to solder design
 3 Use modern (Active production) components
 4 Have 3d printable case, or make pcb compatible with original controller case
 
 
 ## State of project
 
Parts have been purchased and I'm currently prototyping with some friends, after we have a working proof of concept, I'll begin designing the pcb

## Inital parts list and rough designs:

Here's the initial parts list for the controller (subject to change!):
 - 74HC165 x2 (Parallel to Serial Shift register)
 - B3F-1000 x10 (Tactile switch from omron, aka the buttons)
 - B3F-3100 x2 (Tactile switch from omron, sholder buttons)
 - 74HC14D x1 (Inverter, could be changed out for cheaper component)
 - Resistors x12 values and types to be determined
 
 Here's a rough logical design:
 
![initial design](https://raw.githubusercontent.com/MattRCole/open-source-snes-controller/master/img/snes-initial-design.png)
