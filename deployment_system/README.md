# Deplyoment System Assembly Instructions

All the information and part files that you need to build a deployment mechanism can be found here. I would recommend starting the 3D prints first, as the 3D prints are the most time consuming. Gathering all of the components beforehand, as well as lasercutting everything out first will make assembly much easier. 

### Parts List
Part | Quantity
-------- | --------
2020 Aluminum Extrusion | 2 x 15.75"<br>1 x 14.25"<br>3 x 10"<br>9 x 6"<br>6 x 3"
V-Slot Aluminum Extrusion | 3 x 11.75"
90&deg; 2020 bracket | 24
45&deg; 2020 bracket | 6
Nema 17 Stepper Motor | 3
Stepper Motor Bracket | 3
GT2 Pulley - 16 Tooth | 3
GT2 Idler Kit | 1
GT2 Belt 102.5mm | 3
V-Wheel Kit | 18
M5 x 40mm Bolt | 18
M5 x 16mm Bolt | 9
M4 x 10mm Bolt | 12
M3 x 8mm Bolt | 12
M3 x 10mm Bolt | 12
M5 Spacer x 20mm | 18
M3 Spacer x 8mm | 2
M3 Spacer x 4mm | 4
CNC Shield with Arduino | 1
DRV8825 Driver Board | 3
Limit Switch Board | 3

In addition to all of the purchased components, there are various 3D printed and lasercut acrylic pieces that need to finished before the full assembly can begin. All of the files, for both 3D print and lasercut, can be found in the STL and DXF folders.

### 3D Printed Parts
Part File Name | Quantity | Notes
-------- | -------- | --------
belt\_bracket.STL | 3 | Onyx is prefered as these will be tapped<br>and support the whole weight of the beacon.
belt\_bracket\_top.STL | 3 | Onyx is prefered as these will be tapped<br>and support the whole weight of the beacon.

Assuming that assembly of the beacons have begun, you should not have to lasercut the gantry gripper piece nor the limit switch mounts. For these parts use 1/4" acrylic. All the other parts needed have been organized into a larger file to be cut out of a 12"x24" sheet. Each sheet will produce 5 of the 3 required gantry plates, and 2 of the 1 required stepper motor plate. This means that eventually 3 more of the gantry plates will need to be cut out. The individual files are also included in the directory DXF\_FULL.

### Lasercut Acrylic Pieces
Part File Name | Quantity | Notes
-------- | -------- | --------
deployment\_sheet.DXF | 1 | Use a full 1/4"x12"x24" sheet of acrylic

## Step 1: Assemble the 8020 Frame

#### Parts Needed:
- 2 x 15.75" 2020
- 1 x 14.25" 2020
- 3 x 10" 2020
- 3 x 11.75" V-Slot
- 6 x 90&deg; 2020 Bracket
- 6 x 45&deg; 2020 Bracket
- 12 x 2020 T-Slot Nut
- 12 x M5 x 8mm Bolt

Begin by tapping the ends of the 10" 2020 extrusions with an M5 tap. Assemble the frame as is shown in the drawing, below.

![frame_assembly](https://raw.githubusercontent.com/greg-lund/marble_beacon/master/assembly_photos/frame_assem_drawing.png)

## Step 2: Stepper Motor Mounting

#### Parts Needed:
- Stepper plate acrylic panel
- 3 x Nema 17 stepper motors
- 3 x Stepper motor bracket
- 3 x 16 tooth GT2 pulley
- 3 x T-nut and bolt
- 12 x M4 x 10mm Bolt and Nut
- 12 x M3 x 8mm Bolt and Nut
- 2020 frame assembly

Begin by attatching the motor brackets, as well as motors to the acrylic plate. Use the M4 and M3 screws here. Attach the motor assembly to the top of the frame assembly via the t-nuts and M5 holes in the plate. Attatch the pulleys at any point.

## Step 3: Fork Subassemblies

#### Parts Needed:
- 9 x 6" 2020 
- 6 x 3" 2020
- 18 x 90&deg; 2020 bracket
- 33 x T-nut and bolt
- 3 x Side plate acrylic panel
- 3 x Gantry gripper acrylic panel
- 18 x M5 x 40mm bolt
- 18 x 20mm M5 spacer
- 18 x V-Wheel kit
