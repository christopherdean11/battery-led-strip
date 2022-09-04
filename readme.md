# Battery Boost LED Strip Driver
This repo contains the Kicad project files for a PCB to boost a 4-AA battery bank up to 12V to drive an LED tape strip. 

## Goal
Deisgn a PCB to power a 12V LED strip in a closet that turns on when the door opens and off when the door closes, in an area where there are no outlets availble for wall power.

## LED Tape Strip
I selected this LED tape strip from HitLights, model number: `L0512V-401-1630-U`.
Some quick information about these LEDs:  
* 16.4ft long, can be cut to length every 2 inches
* Runs on 12V
* 24W to power the full strip. This works out to 2A for the full strip, or 20 mA per cuttable 2 inch segment
* 4000 K LED color (this felt like a good compromise for a closet between 2700 K or 3000 K which is a warm white, and 5000 K "daylight" which is usually a bit harsh for me)

## PCB Rev0
See [Rev0 Design Notes](BatteryLedStripDriver-R0/readme.md)  
Here is a gif demonstrating the circuit on a short strip of LEDs
<img src="BatteryLedStripDriver-R0/images/FullDemo.gif" alt="PCB" width="800"/>  

Here are some [ideas for a future revision](BatteryLedStripDriver-R0/readme.md#next-gen-ideas)