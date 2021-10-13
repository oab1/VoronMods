# V2 Direct Drive Toolhead
Codename: Tronhead

Compact toolhead with direct drive extruder weighing in at 265 grams with steel hardware. Features a modified sherpa mini extruder for tighter integration with hotend, magnetic probe, and optional Huvud integration all under the cover. 

![picture](Images/tronhead_complete_3.PNG)
![picture](Images/uncovered.PNG)


>>RC1:
- 30 x 10mm hotend fan
- TL Dragon hotend
- New toolhead mount with exhaust flow path considerations to extract more flow from smaller fan, 5mm increase in y-travel
- Modified X-Carriage integrates LDO NEMA14 motor with backlash adjustment, forms part of exhaust exit duct
- Modified Sherpa mini extruder mounting locations for direct connection to carriage. 16mm lower stack height than current modular design. Tension screw flipped around for smaller package.
- Currently only made a inductive probe sensor version (will add quick-draw style probe carriage)
- single or dual mgn9 carriage setup (I am testing it with the standard single mgn9 first)

![picture](Images/RC2_huvud_integration.PNG)
>>RC2
- dual mgn9h rail (top/bottom orientation)
- dockable magnetic probe instead of inductive sensor
- Huvud integration in connector cover (folds forward and down, instead of v2.2 style up/back)

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
