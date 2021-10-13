# V2 Direct Drive Toolhead
Codename: Tronhead

Compact toolhead with direct drive extruder weighing in at 265 grams with steel hardware. Features a modified sherpa mini extruder for tighter integration with hotend, 30mm  fan, dual 4010 part cooling fants, a magnetic probe and optional cover for mounting a Huvud toolhead PCB. 

There are 3 versions. The major difference is the X-carriage:

(1) Voron dual mgn9h with inductive probe and cable chains

(2) Redoubt dual mgn9h with dockable magnetic probe and umbilical cord

(3) Redoubt dual mgn9h + HUVUD toolhead PCB (different connector cover and fan front plate)

[(1) Voron V2] -
- 4mm increase in y-travel, 
- ~200g lighter than aferburner toolhead

[(2) ANNEX Redoubt] -
- 15mm increase in y-travel
- dual mgn9h rail (top/bottom orientation) 
- dockable magnetic probe instead of inductive sensor
- rear mounting clamp for umbilical cord

[(3) ANNEX Redoubt + HUVUD]
- same but with forward folding connector cover for integration of Huvud toolhead board
- Removed mounting clamp for umbilical cord


![picture](Images/tronhead_complete_3.PNG)
![picture](Images/uncovered.PNG)


>>RC1:
- 30 x 10mm hotend fan
- TL Dragon hotend
- New toolhead mount with exhaust flow path considerations to extract more flow from smaller fan, 5mm increase in y-travel
- Modified X-Carriage integrates LDO NEMA14 motor with backlash adjustment, forms part of exhaust exit duct
- Modified Sherpa mini extruder mounting locations for direct connection to carriage. 16mm lower stack height than current modular design. Tension screw flipped around for smaller package.

![picture](Images/RC2_huvud_integration.png)
>>RC2


## Hardware needed:
- Extruder uses all the same hardware as Sherpa Mini
- X-carriage uses all the same hardware as existing v2.2 carriage.
- 30mm axial fan
- 2x 4010 radial (blower) fans
- Triangle Labs Dragon hotend
- LDO NEMA 14 motor
- omron/fotek inductive probe (if building RC1) OR mouse switch (if building RC2)
- Huvud toolhead PCB (optional for RC2)

## Sherpa Mini Extruder
Original design for this extruder from Annex Engineering:

https://github.com/Annex-Engineering/Sherpa_Mini-Extruder

## HUVUD Toolhead PCB
https://github.com/bondus/KlipperToolboard
