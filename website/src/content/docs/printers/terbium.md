---
title: "Terbium"
description: "Can't afford a printer? Terbium, build one. Cheap CoreXY printer!"
project_name: "Terbium"
repository: "https://raw.githubusercontent.com/akulsaju/terbium/refs/heads/main/JOURNAL.md"
---
# Terbium - The DIY printer

DIY!!! I'm gonna make it as easy as possible

Made by: @akul  
Repository link: https://github.com/akulsaju/terbium  
Hours so far: 99h 23m  

- [x] I have a Prusa and access to larger printers  
Printer that's gonna be small, fast, cheap!

## The plan  
I don't know, but I'll figure it out in the vacations. I never failed anything when money isn't a constraint :D  

1. Cheap (hope so)  
2. Capable of printing a Benchy  
3. 210x210x210mm  
4. Cute & colorful  
5. DIY-Friendly  

I'm buying everything from China (AliExpress, etc.).  
Currently, the outline is 210mm x 210mm  

### Log  

| Date  | Task                     | Time      | Notes                                                                           |
| ----- | ------------------------ | --------- | ------------------------------------------------------------------------------- |
| 10/02 | Init                     | 20 min    | Setting up Journal.md. Just getting started, felt like a productive move. |
| 11/02 | Checking random YT videos | 1 hour    | Videos being too complicated lol. People either over-explain or barely explain. |
| 11/02 | Defining dreams          | 10 min    | What are my needs? Realized I just want a printer that's cheap and works. |
| 14/02 | Searching parts on AliExpress | 3 hours   | Who knows if every part works!! So many options, too many choices. |
| 16/02 | Searching then designing in Onshape  | 9.5 hours | There goes my day (Makes sense why I need Spotify Premium). |
| 17/02 | More parts and modeling              | 8 hours | Got Spotify Premium. Design starting to look like an actual printer. |
| 18/02 | Found out I messed up my dimensions (mm and cm) | 6 hours | Fixing in Onshape. My brain swapped mm for cm, massive mistake. |
| 21/02 | Lol fixing                               | 2 hours  | :D Just fixing what I messed up earlier, happens a lot. |
| 21/02 | Making bed                   | 3.5 hours  | Should I put a design on the bed? Custom engraving might be cool. |
| 21/02 | Finish Y axis                        | 6 hours | Yay, one axis down. Feels like progress! |
| 21/02 | Start of Z axis                      | 4 hours | Looks nice :P Adding constraints and making sure it moves properly. |
| 22/02 | Finished Z axis!!!                   | 3 hours | Only printhead and electronics to go. Getting closer. |
| 23/02 | Working on head                      | 3 hours | Trying to make it modular for easy upgrades. |
| 24/02 | Tiny bit of research                 | 23 min   | Continuing... Needed a break but still made progress. |
| 26/02 | Trying to get CFD work               | 20 min | Works! Thermal and airflow analysis looks decent. |
| 27/02 | Refining frame design                | 5 hours  | Adjusting dimensions, verifying part alignment. Making it more rigid. |
| 28/02 | Finalizing motion system             | 6 hours  | Optimizing belt paths, ensuring smooth motion. No skipped steps allowed! |
| 29/02 | Fixing minor issues in Y axis        | 4 hours  | Adjusting tolerances, better mounting for stability. Belt tension was off. |
| 02/03 | Updating Z axis model                | 5 hours  | Strengthening structure, reducing weight. Swapping out a few parts. |
| 03/03 | Designing printhead mount            | 4 hours  | Ensuring compatibility with hotend and extruder. Swapping between different mounting styles. |
| 05/03 | Improving electronics mounting       | 5 hours  | Adding cable management solutions. Wires everywhere are NOT fun. |
| 07/03 | Testing different bed support options| 4 hours  | Preventing warping, improving heat distribution. Making sure the bed stays level. |
| 09/03 | Revising extruder mounting           | 4 hours  | Checking for better filament path. Want minimal resistance for smoother prints. |
| 10/03 | Investigating different hotend options | 3 hours | Ensuring best heat dissipation and flow. Hotend affects everything! |
| 11/03 | Enhancing cooling solutions          | 3 hours | Adding better fans for part cooling. Essential for bridging. |
| 12/03 | Working on aesthetic elements        | 3 hours | Making it look good! No boring black printers. |
| 13/03 | Structural analysis for frame        | 4 hours | Ensuring rigidity and minimizing vibrations. Vibration = ugly prints. |
| 14/03 | Bed leveling mechanism improvements  | 3 hours | Making leveling more precise and easy. Manual vs auto leveling? |
| 15/03 | Finalizing assembly constraints      | 5 hours  | Making it truly DIY-friendly. Every part should be easy to put together. |
| 16/03 | Reviewing entire model for conflicts | 4 hours  | Ensuring every part fits correctly. Adjusting minor interferences. |
| 17/03 | Simulation of movement parts         | 5 hours  | Checking stress points and possible failures. Making sure things don’t snap. |
| 18/03 | Running final interference checks    | 5 hours  | Making sure nothing collides, testing tolerances in software. No unexpected crashes! |
| 19/03 | Fixing Colliding parts  | 6 hours  |Fixing it |
| 20/03 | another part is too thin | 6 hours  | Fixed!! |
## BOM (Bill of Materials)

### **Frame**
| Item                          | Quantity | Price (USD)  |
|-------------------------------|----------|--------------|
| 2020 T-Slot 200mm              | 4        | -            |
| 2020 T-Slot 250mm              | 4        | -            |
| L brackets                     | 2        | $8.88        |
| T brackets                     | 2        | -            |
| 2020 Corner Bracket            | 4        | $3.00        |

### **Motion**
| Item                          | Quantity | Price (USD)  |
|-------------------------------|----------|--------------|
| GT2 6mm wide Belt (4 meters)  | 1        | $10.00       |
| 20 Tooth 5mm Bore Pulley      | 4        | $12.00       |
| F695 Bearing Pack (10 bearings, 12 needed) | 2 | $8.00 |
| MGN9C 150mm for X             | 1        | $11.33       |
| Nema17 with XH2.54 Cable (48mm max for Y motor) | 4 | $53.00 |
| 8mm Linear Rod 250mm for Y and Z | 4      | $7.00        |
| LM8LUU 8x15x45mm              | 4        | $27.08       |
| 3:1 Gear Reduction with belts | 2        | $18.00       |
| 50mm x 5mm pin for Z Gearbox  | 2        | $10.00       |

### **Hardware**
| Item                                      | Quantity  |
|-------------------------------------------|-----------|
| M3 x 6mm Buttonhead (for toolhead)        | 4         |
| M3 x 8mm Socket Head                      | 30        |
| M3 x 12mm Socket Head                     | 4         |
| M3 x 16mm Socket Head                     | 4         |
| M3 x 20mm Bambu Hotend Mount              | 2         |
| M3 x 35mm (for Dragon Burner mount)       | 2         |
| M3 T-Nut (to mount linear rail to X 2020 extrusion) | 4 |
| M5 x 8mm Socket Head                      | 76        |
| M5 x 16mm Socket Head                     | 7         |
| M5 x 30mm Socket Head                     | 1         |
| M5 T-Nut                                  | 76        |
| M5 Washer (M5x10x1 x50pcs)               | 4         |
| Heatsets M3 X D5.0 X L4.0 (Order 300)     | -         |
| Rubber Feet (38 x 20)                     | 4         |
| Additional bolts for Dragon Burner Toolhead | -        |

### **Extruder + Hotend**
| Item                              | Quantity | Price (USD) |
|-----------------------------------|----------|-------------|
| Dual Gear Extruder HGX-LITE-Extruder | 1       | $60.00      |
| Bambu X1 style hotend            | 1        | $22.00      |

### **Electronics**
| Item                              | Quantity | Price (USD) |
|-----------------------------------|----------|-------------|
| 24V 8A AC Adapter                 | 1        | $40.00      |
| Mellow DP5 Mainboard              | 1        | $35.00      |
| 3010 24V Fan (2 Pin HX2.54 connector) | 1      | $11.00      |
| 4010 24V Blower (2 Pin HX2.54 connector) | 2    | $11.00      |
| BLTouch                           | 1        | $10.00      |

### **Total Cost**
| Currency | Amount   |
|----------|----------|
| CAD      | $394.29  |
| USD      | $307.55  |

## Pics  
