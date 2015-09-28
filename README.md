# NE555_pwm_SMD
Simple, small and cheap PWM regulator on NE555.

Single-sided pcb layout with only 1 jumper.

You can use it to drive 12V motor, LED strip, Peltier module, lightbulb etc.
PCB dimensions: 34.29 x 20.63 mm. 
Pulse width regulated by standard potentiometer.
You can use any Mosfet in DPAK (TO-252) case as You like and follow Your requirements. I am using 2SK3918 from old pc motherboard.

I also designed even smaller version with components on both sides, but is now without tests. 

As soon as possible i make photos and movie to show prototype.

If You want to make it, just download the ne555_pwm_smd_top.pdf file, print it and make thermotransfer.
All SMD resistors and capacitors are in 1206 cases.
You can find partlist in bom.txt file.

Schematic:

  ![alt tag](https://raw.githubusercontent.com/virtmedia/NE555_pwm_SMD/master/schematic.png)

PCB layout:

  ![alt tag](https://raw.githubusercontent.com/virtmedia/NE555_pwm_SMD/master/pcb_layout.png)
  
Partlist (from file bom.txt):
Part Value  Device         Package   Description                  
C1   100n   C-EUC1206      C1206     CAPACITOR, European symbol   
C2   100n   C-EUC1206      C1206     CAPACITOR, European symbol   
C3   10n    C-EUC1206      C1206     CAPACITOR, European symbol   
D1   LL4148 DIODE-MINIMELF MINIMELF  DIODE                        
D2   LL4148 DIODE-MINIMELF MINIMELF  DIODE                        
D3   LL4148 DIODE-MINIMELF MINIMELF  DIODE                        
IC1  NE555D NE555D         SO08      TIMER                        
JP1  ZAS    PINHD-1X2      1X02      PIN HEADER                   
JP2  OUT    PINHD-1X2      1X02      PIN HEADER                   
Q1   MFET-N 	TO252_STM  TO252_STM IGBT                         
R1   1K     R-EU_R1206     R1206     RESISTOR, European symbol    
R2   47R    R-EU_R1206     R1206     RESISTOR, European symbol    
R3   100K   3RP/1610N      3RP/1610N 16mm Potentiometer one level 
