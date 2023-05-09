# Mantis_Toolhead_PCB

| ❗ NOTE          |
|:---------------------------|
| This alternative design is functionally the same as the one in main branch but a different layout, shape & connection points on PCB. |

![Alternative PCB design.](/images/alternative_pcb.jpg)

## Description

This toolhead board was designed to be used with mantis toolhead mod for voron 3D printers.

The input is 16 pin molex microfit connector and outputs include
* 1 x 2 pin microfit/JST XH connector for Heater
* 1 x 2 pin microfit/JST XH connector for Thermistor
* 1 x 2 pin microfit/JST XH connector for Hotend fan
* 1 x 2 pin microfit/JST XH connector for X-endstop
* 1 x 2 pin microfit/JST XH connector for Magprobe/Klicky/Quickdraw
* 2 x 2 pin microfit/JST XH connector for Cooling fans (connected in parallel)
* 1 x 4 pin microfit connector for Extruder motor

This PCB is simply a breakout for the inputs from 16 pin connector so the user may decide where the outputs are actually used and stray from the original designed functions of the ports.

## BOM

* PCB
* 7 x 2 pin microfit pcb headers/2 pin JST XH connectors (You can use what you like, the holes are designed for microfit connectors so hole pitch is a bit high for JST XH but should work with careful soldering, note that there is no real need for using microfits for anything other than heater for which it is recommended due to higher current.)
* 1 x 4 pin microfit pcb header (JST-XH will not work here due to too small pitch)
* 1 x 16 pin microfit pcb header horizontal or vertical.

![Assembled PCB.](/images/pcb_assembled.jpg)

## Mounting

PCB can be mounted on the mantis carriage with the two m3 holes on the board as shown in the images below.

![Mounted PCB.](/images/pcb_mounted.jpg)
![PCB in use on a printer.](/images/pcb_in_use.jpg)

