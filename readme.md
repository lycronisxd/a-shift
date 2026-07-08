# a-shift
## a high-quality sim racing shifter targeted at being as cheap as possible to manufacture.

<img width="407" height="737" alt="shifter" src="https://github.com/user-attachments/assets/7af0d89a-b6e3-4d0b-bb7c-fc8a4d2be5b1" />

### pcb and schematic
<img width="1138" height="781" alt="image" src="https://github.com/user-attachments/assets/02b31dea-feff-4e7d-801d-387bfd542889" />
<img width="1038" height="781" alt="image" src="https://github.com/user-attachments/assets/903b0cd3-2a69-4966-873a-851ff336b1f5" />
<img width="1138" height="781" alt="image" src="https://github.com/user-attachments/assets/3f853175-bdd9-4c53-9660-663e7c5d3abf" />

### bill of materials

﻿ Item No. | Part No. | Part Name | Qty. | Supplier | Unit Cost | Total Cost |
|---|---|---|---|---|---|---|
| 1 | 3D-001 | 3d printed y-axis chamber | 1 | 3d printing service / at home printing | N/A | N/A |
| 2 | 3D-002 | 3d printed x-axis bearing peg | 2 | 3d printing service / at home printing | N/A | N/A |
| 3 | 3D-003 | 3d printed y-axis bearing peg | 1 | 3d printing service / at home printing | N/A | N/A |
| 4 | 3D-004 | 3d printed main chassis | 1 | 3d printing service / at home printing | N/A | N/A |
| 5 | 3D-005 | 3d printed shift gate | 1 | 3d printing service / at home printing | N/A | N/A |
| 6 | 3D-006 | 3d printed y-axis bearing holder | 1 | 3d printing service / at home printing | N/A | N/A |
| 7 | 3D-007 | 3d printed shift knob | 1 | 3d printing service / at home printing | N/A | N/A |
| 8 | 3D-008 | 3d printed clamp head | 1 | 3d printing service / at home printing | N/A | N/A |
| 9 | 3D-009 | 3d printed clamp body | 1 | 3d printing service / at home printing | N/A | N/A |
| 10 | BR-001 | 608 series bearing | 4 | aliexpress | £0.44 | £4.35 (10pcs) |
| 11 | BR-002 | 625 series bearing | 2 | aliexpress | £0.37 | £3.68 (10pcs) |
| 12 | MNT-001 | m3x5mm bolt | 4 | accu | £0.27 | £1.08 |
| 13 | MNT-002 | m4 nut | 8 | accu | £0.18 | £1.44 |
| 14 | MNT-003 | m6 washers | 8 | accu | £0.19 | £1.52 |
| 15 | MNT-004 | m4x10mm bolt | 15 | accu | £0.15 | £2.25 |
| 16 | MNT-005 | m5 nut | 2 | accu | £0.43 | £0.86 |
| 17 | MNT-006 | m5x10mm bolt | 2 | accu | £0.49 | £0.98 |
| 18 | MNT-007 | m10 washer | 1 | accu | £0.82 | £0.82 |
| 19 | MNT-008 | m10 nut | 1 | accu | £1.01 | £1.01 |
| 20 | SPR-001 | 25mm long, 5mm diameter springs | 2 | aliexpress | £0.29 | £2.89 (10pcs) |
| 21 | SPR-002 | 45mm long, 5mm diameter springs | 2 | aliexpress | £0.37 | £3.73 (10pcs) |
| 22 | SPR-003 | 20mm long, 11mm diameter spring | 1 | aliexpress | £0.26 | £2.59 (10pcs) |
| 23 | MSC-001 | 200mm m10 threaded rod | 1 | aliexpress | £4.31 | £4.31 |
| 24 | MSC-002 | kw13-2 limit switches | 8 | aliexpress | £0.16 | £1.63 |
| 25 | PCB-001 | a-shift pcb (if assembled, ignore the following parts) | 1 | jlcpcb with gerber files | £4 | £4 |
| 26 | PCB-002 | CL21B105KBFNNNG 1uF capacitor | 1 | digikey | £0.09 | £0.09 |
| 27 | PCB-003 | CL21C220JBANNNC 22pF capacitor | 2 | digikey | £0.08 | £0.16 |
| 28 | PCB-004 | CL21B104KBCNNNC 0.1uF capacitor | 4 | digikey | £0.08 | £0.32 |
| 29 | PCB-005 | 1050170001 micro usb connector | 1 | digikey | £0.70 | £0.70 |
| 30 | PCB-006 | RC0805FR-0710KL 10k ohm resistor | 1 | digikey | £0.08 | £0.08 |
| 31 | PCB-007 | RC0805FR-0722RL 22 ohm resistor | 2 | digikey | £0.08 | £0.16 |
| 32 | PCB-008 | 1825910-6 tactile switch | 1 | digikey | £0.10 | £0.10 |
| 33 | PCB-009 | ATMEGA32U4-AU microcontroller | 1 | digikey | £4.01 | £4.01 |
| 34 | PCB-010 | ABM3-16.000MHZ-D2Y-T 16mhz crystal oscillator | 1 | digikey | £0.42 | £0.42 |\

total price (excl. 3d printing services, shipping and tax), <b>£43.18 (~60 USD)</b>

### relevant links
link to **public onshape project**:
<a href="https://cad.onshape.com/documents/ae479125a780254f271543a6/w/35b4ca05e55e778462ce5fb0/e/28c8145b059bf4585cd308b0"> click this </a>

link to **3d printed parts**:
<a href="https://www.thingiverse.com/thing:7376293">click here!</a>

### features
<ul>
<li>custom designed pcb based on the atmega32u4 for ease of future designing :)</li>
<li>7+R normally</li>
<li>5+R capability</li>
<li>sequential shifter capability</li>
</ul>

### how it works
<ul>
<li>uses a combination of software and hardware to be used as a shifter in racing or driving games</li>
<li>the used limit switches are mapped as controller buttons inside of game settings</li>
<li>can use the shifter sequentially if printing the sequential shift gate and using rubber bands!</li>
</ul>

### instructions
<a href="https://github.com/lycronisxd/a-shift/blob/main/instructions.md">click here!</a>

### credits + ai declaration
<a href="https://www.youtube.com/@amstudioprojects">amstudio</a> for <a href="https://www.youtube.com/watch?v=YMD8e26s7VE&t=88s">this video</a>\
about <a href="https://www.thingiverse.com/Noctiluxx/designs">noctiluxx's <a href="https://www.thingiverse.com/thing:1274947">h-pattern shifter design</a> for the forwards and backwards action of the shifter being locked <3 

i used google gemini to understand why the length of the shift lever mattered\
i used chatgpt to confirm the selection of the electronic components that i plan to use for the pcb (capacitors, resistors etc.)
