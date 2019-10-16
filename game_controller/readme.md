# Intro
# Required

Part | Manufacturer | Supplier | Manufacturer part no. | Supplier part no.
-----|--------------|----------|-----------------------|------------------|
Fiber optic cable | Broadcom Limited | Digikey | HFBR-RUD500Z | 516-2094-ND
Fiber optic transmitter | Broadcom Limited | Digikey | SP000063814 | 516-2213-ND
Fiber optic receiver | Broadcom Limited | Digikey | SP000063855 | 516-2455-ND
Teensy 3.5 microcontroller board | SparkFun Electronics | Digikey |DEV-14055 |1568-1443-ND
Gate driver | Texas Instruments | Digikey | SN75451BP | 	296-1746-5-ND
Hose 13mm ID, black PE|Panduit Corp|Digikey|CLTS50F-C|298-13576-ND
Hose 19.48mm ID, black PE|Panduit Corp|Digikey|CLTS75F-C|	298-13577-ND
Polycarbonate Pan Head Philips Screw 8-32 x 1" | | McMaster-Carr||93140A782
Polycarbonate Pan Head Philips Screw 8-32 x 1/2" | | McMaster-Carr||93140A588
Nylon 6/6 Female Threaded Round Standoff 8-32 x 1/4"||McMaster-Carr||96110A026

# Mechanical

## Required
- CAD Software
- Slicing software
- Access to 3D printer

List of CAD files needed
1. Casing_Top
2. Casing_Bottom
3. Switch_Body
4. Shutter_Blade
5. Shutter_Cap
6. Button_Cap
7. DPad_Support
8. DPad_Cross
9. Y_Splitter (optional)
10. Interface_Casing_Top
11. Interface_Casing_Bottom

## 3D printing parts
All 3D printed parts were printed on a Ultimaker 3 printer (Ultimaker) using PLA or ABS plastic.

## Assembly
1. For each control on the controller, cut one length of duplex fiber optic to desired length between controller and interface module + 150 mm
- Split each length of fiber on its length to separate the 2 fibers on a distance of approx. 750 mm from one end, and 25 mm from second end
- Label each fiber with the name of matching control. On the end where the fibers are split for the largest distance (controller end) place a label on each single fiber
- Strip and polish fibers **(need procedure)**
- Cut two 500 mm lengths of the 13 mm ID plastic hose and fix those on the ends of the Y splitter
- Fix second end of plastic hoses to extrusions on part *Casing_Bottom*
- For each control, place a *Switch_Body* in matching groove inside casing
- Insert the fiber optics into Y splitter and push gently until both fibers emerge inside of casing. Make sure that the length protruding inside the casing is enough to reach into the corresponding *Switch_Module* and allow to lay out cleanly inside casing.
- For each control, glue both fibers in place **(Need glue specs)**
- Optional: Depending on the fit tightness of *Switch_Module* parts inside grooves, it is also possible to glue the module in place. If gluing modules in place, wait for glue on fibers to set before proceeding

# Electronics

## Obtaining interface printed circuit board

## Assembling circuit


# Software
