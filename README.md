# Macro_C
4U and 2.4" screen version of Ornament & Crimes/Hemisphere/Bemisphere and Squares & Circles

- 4 TRIGGER inputs
- 4 CV inputs with attenuators
- 4 CV ouputs with attenuators

Use it with a Teensy 3.2 as a normal Ornaments & Crime or Hemi/Bemisphere module

Use a teensy 4 or 4.1 when you want to use it as Squares & Circles 
Resistor R_SC only to be mounted when using Squares and Circles.
You need to cut the jumpers SJ1 and SJ2

Teensy 4:
Solder 2 wires
Pad 26 on the teensy to either of the 26 points on the pcb
Pad 27 on the teensy to either of the 27 points on the pcb

Teensy 4.1:
Solder 2 extra pin and headers on the teensy 4.1 on pad 26 and 27.

For more information and uploading of the firmware for Squares & Circles goes via https://github.com/eh2k/squares-and-circles

In case you want to use Phazerville and you have squares and circles there are a few steps to do:
- Unplug pin headers 26 and 27 on the back of the pcb left from the teensy.
- After that solder the 2 bridges together near the usb port called sj1 and sj2.
- Remove the resistor R_SC on the bottom of the pcb.
- Flash it with the new firmware.
