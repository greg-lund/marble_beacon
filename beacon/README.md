# COM Beacon Assembly Instructions

All the information and part files that you need to build a COM beacon can be found here. I would recommend starting the 3D prints first, especially the electronics core rail pieces, as the 3D prints are the most time consuming. Gathering all of the components beforehand, as well as lasercutting everything out first will make assembly much easier. 

### Parts List
Part | Quantity 
-------- | --------
Power Antenna | 1
Rock64 with eMMC | 1
Batter Pack | 1
Doodle Radio | 1
12V to 5V Automotive Regulator | 1
FeatherLight Latching Relay | 1
Pushbutton with Light | 1
DPDT Switch | 2
DC Jack | 1
3 Pin Molex (Male + Female) | 1
9 Pin Circular Connector (Male + Female) | 1
3.5mm DC Jack - 90&deg; | 1
M2.5 Nylon Standoff and Nut | 8
M2.5 x 5mm bolt | 8
1/4" Wire Loom | 2 ft
Assorted Zipties | 

In addition to all of these purchased components, there are a variety of 3D printed and lasercut acrylic parts that need to be made before beginning the full assembly. The appropriate files for the 3D printer and lasercutter can be found in the STL and DXF directories, respectively. 

### 3D Printed Parts
Part's File Name | Quantity | Notes
-------- | -------- | --------
beacon\_foot.STL | 8 | PLA should be fine
electronics\_core\_rail.STL | 12 | PLA should be fine
lid\_bracket.STL | 1 | Use high infill or Onyx<br>as these require holes to be tapped
package\_bracket.STL | 6 | Use high infill or Onyx<br>as these require holes to be tapped

The lasercut parts for a single beacon have been organized into larger files to be cut out of 1/8"x12"x24" acrylic sheets. There are two main files that take up most of their sheets, and the electronics core must be cut separately.

### Lasercut Parts
Part's File Name | Quantity | Notes
-------- | -------- | --------
beacon\_sheet\_1.DXF | 1 | Use a full 12"x24" sheet
beacon\_sheet\_2.DXF | 1 | Use a full 12"x24" sheet
electronics\_core.DXF | 1 | Either use scrap or fit 2 on a sheet

If an individual part's DXF is required they can be found in the FULL\_DXF directory.

## Step 1: Assembling the Acrylic Box

#### Parts Needed:
- The four acrylic side panels
- Bottom acrylic panel
- 12 electronics core rail 3D prints

Begin by gluing the electronics core rail to the two identical, larger side panels. If you can't find a side plate raile template piece, lasercut one out. Line up the template with a side plate, and attach it via the two M3 screw holes. Either use superglue or acrylic cement to glue the 6 rail pieces to the plate. Don't forget to use clamps and ensure the flanges are facing eachother. Do the same on the other side, ensuring they are opposite and will fit up together.

Once the glue on the side panels has cured, glue all the pieces together, ensuring that the mounting holes for the switches and charging ports are on top and that the holes in the base plate are opposite those ports. Use either superglue or acrylic cement. Tape or clamp everything together ensuring that everything is square.


## Step 2: Assembling the Electronics Core

#### Parts Needed:
- Electronics core acrylic panel
- Battery
- Rock64
- Latching Relay
- Step-down converter
- Doodle radio
- M2.5 standoffs and screws
 

