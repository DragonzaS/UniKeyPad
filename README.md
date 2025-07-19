# UniKeyPad
UniKeyPad is a 11 key macropad, with a rotary encoder and an OLED display. Uses QMK firmware!

I made as introduction for myself to PCB design, and also can be used as minimal numberpad companion for my current TKL keyboard.

## Features
- Simple, two part 3D printed case
- one Rotary Encoder for mode selection, together with 128x32 OLED display for friendly UI.
- 11 Customizable keys

## Case

Together it fits using two 3D printed parts, that are kept together with four M3 screws and heatset inserts.
(Angled stand coming soon, to have same angle as my main keyboard)


<img src=assets/onshape.png alt="CAD" width="450"/>

All together

<img src=assets/case.png alt="Opened case" width="450"/>

Case only

Made with OnShape.

(To the reviewer: I added a simplified CAD file, without the switches, the full size one is very big!)
## PCB

Made in Kicad (my first time!). Included also 3D models that I used (they are from GrabCad), it was quite a pain to get them working.

Schematic

<img src=assets/schematic.png alt="Schematic" width="450"/>

PCB

<img src=assets/pcb_design.png alt="PCB Design" width="450"/>
<img src=assets/pcb_render.png alt="PCB render" width="450"/>

Also tried using Ground plane and thicker traces for 5V to OLED for stability.

## Firmware

For now QMK only, might do a KMK version.

OLED is not yet implemented, everything else should work.
Basic functionality tested with a Raspberry Pico and a dupont cable :)
Works!

## Bill of Materials
Hopefully everything that I used:


- 11x Cherry MX Switches
- 11x DSA Keycaps
- 11x 1N4148 Diodes
- 4x M3x5x4 Heatset inserts
- 4x M3x12mm SHCS Bolts
- 1x 0.91" 128x32 OLED Display
- 1x EC11 Rotary Encoder
- 1x XIAO RP2040
- 1x Case, two 3D printed parts (I can print them myself)

## Extra
I enjoyed making it!

Possible thanks to HackClub!
