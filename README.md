# CNC CAD PEOJECT 

This is a project of me designing a CNC machine in onshape the goal is I'll submit it and then try to actually physically build it with the money to get a hardware grant.
This was done for Hack Club Horizons with Basic 12 by 12 inch design running a gantry


<img width="614" height="677" alt="image" src="https://github.com/user-attachments/assets/5dc87f9b-d381-45b1-8ff2-6c0acdeec743" />

<img width="599" height="387" alt="image" src="https://github.com/user-attachments/assets/9c7d6bf2-ba7b-4d34-84e3-c4ff3397d43e" />

## Pinout

| Connection | Board Interface | Notes |
|---|---|---|
| Main power | DC-007B-2.1mm barrel jack | 12–24V DC, max 5A, 10A fuse |
| X motor | X motor slot | Onboard driver, no external driver needed |
| Y motor | Y motor slot | Onboard driver |
| Z motor | Z motor slot | Onboard driver |
| X limit switch | X endstop — GND + S | Mechanical switch, no power pin needed |
| Y limit switch | Y endstop — GND + S | Same |
| Z limit switch | Z endstop (separate connector from XY) | Same |
| E-stop | Reset button port | Doubles as emergency stop input |
| Spindle control | SPINDLE terminal (X1/X2) → spindle controller signal-in | **Signal only.** Board's native spindle output maxes at 20W @ 24V — not enough for a 500W spindle. |
| Spindle power | Spindle kit's own AC supply | Fully isolated from the DLC32's 24V rail |
| USB | Micro USB | Flashing + tethered control |
| SD card | TF card slot | Offline jobs — FAT32, Class4/10, 4–16GB |


AI FORMATTED
# WHY WAS IT DONE?

This was done because I wanted to Get better at CAD and also I really want to build myself a CNC machine and this would be a fun way to acquire some funding for it and get to build it.

# Steps to reproduce

Grab the card files from either the Github repository or this link to the onshape document Then from there you will notice what you need to assemble and what you need to buy and what to print.
Then you can grab the materials you need to purchase from the bom.
Proceed to assemble the project using the onshape as some sort of a assemble guide
after that you can download the software and get it to your ESP 32 Chip on the board
AI USE As this is mainly a CAD project I will state that the code was completely AI generated I am not asking for time for that because that is not the goal
# Onshape document link
https://cad.onshape.com/documents/a1a4b60e02dc7bbfaa1fbfe5/w/f0d9976aef77285046fc5a94/e/683484fc6956fd1e9030d168?renderMode=0&uiState=6a7f770e94f6e1ceab1280c8

# BOM

# Bill of Materials (BOM)

###  Electronics & Control

| Qty | Component Description | Source |
| :--- | :--- | :--- |
| 1 | MKS DLC32 V2.1 Control Board | [Amazon Link]([https://amazon.com](https://www.amazon.com/gp/product/B07X142VGC/ref=ox_sc_act_title_2?smid=A30QSGOJR8LMXA&psc=1) |
| 1 | 24V Power Supply Unit (PSU) | [Amazon Link]([https://amazon.com](https://www.amazon.com/gp/product/B0DJR8QGRG/ref=ox_sc_act_title_1?smid=A2QJRKWT0U76FU&th=1) |
| 1 | Rattm Motor 500W Spindle Kit with Power Supply | [Amazon Link]([[https://amazon.com](https://www.amazon.com/gp/product/B07X142VGC/ref=ox_sc_act_title_2?smid=A30QSGOJR8LMXA&psc=1](https://www.amazon.com/gp/product/B07X142VGC/ref=ox_sc_act_title_2?smid=A30QSGOJR8LMXA&psc=1) |
| 1 | Limit Switch Pack | [Amazon Link]([https://amazon.com](https://www.amazon.com/gp/product/B07X142VGC/ref=ox_sc_act_title_2?smid=A30QSGOJR8LMXA&psc=1) |
| 3 | NEMA 17 Motor | Base Parts List |

###  Motion & Drive Components
| Qty | Component Description | Source |
| :--- | :--- | :--- |
| 2 | T8 Lead Screw | [Amazon Link](https://amazon.com) |
| 3 | Flexible Couplings (5mm to 8mm) | [Amazon Link](https://amazon.com) |
| 8 | Linear Bearings | [Amazon Link](https://amazon.com) |
| 16 | 688ZZ Bearing | Base Parts List |
| 2 | 8mm ID Bearing (14mm OD, 5mm WD, Shielded, Flanged) | Base Parts List |
### Structural & Framing

| Qty | Component Description | Source |
| :--- | :--- | :--- |
| 4 | REV-21-1000 1" Aluminum Extrusion (Clear Anodized) | Base Parts List |
| 4 | Hole adapter | Base Parts List |
| 4 | Bearing beam | Base Parts List |
| 5 | T8 port | Base Parts List |
| 1 | Gantry shoulder | Base Parts List |

### 3D Printed Parts

| Qty | Component Description | Source |
| :--- | :--- | :--- |
| 17 | Side bracket | 3D Printed STL |
| 6 | Perpendicular holding bracket | 3D Printed STL |
| 2 | Gantry holder | 3D Printed STL |
| 1 | Bed | 3D Printed STL |

###  Hardware & Fasteners

| Qty | Component Description | Source |
| :--- | :--- | :--- |
| 89 | #4-40 x 3/8" L BHCS (Steel, Black Oxide) | Base Parts List |







# AI use

I used AI to help me cut some basic design concepts and how to do it to be affordable as well as helping me figure out some of the drivers and what parts would be necessary for the robotics area and the code 
and bom formatijng
## All CAD was done by me with no assistance except for trying to figure out how to rename parts which I used a google search
