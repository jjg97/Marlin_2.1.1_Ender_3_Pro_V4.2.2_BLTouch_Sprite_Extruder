# Ender_3_Pro_V4.2.2._Sprite_Extruder
Share Marlin Config for Ender 3 Pro with V4.2.2. Board, BLTouch, CRTouch or Clones with new Sprite direct drive Extruder.

Changes:
1) Resize Build Plane to 210mmx210mmx250mm (WxLxH) to avoid collision of Sprite extruder with right X-Axis
2) Auto-bed-leveling grid 4x4 with 30mm margin due to Probe Offset 
3) max extruder temp is 260 degrees celsius- no unlock for 300 degrees
4) after flashing new firmware change e-steps of extruder stepper to 424.9 steps/mm

firmware is tested with Ender 3 Pro with V4.2.2. Board and BLTouch Clone

How to:
1) download .bin file
2) save .bin file on an empty microSD card
3) turn off Ender 3 
4) insert mSD card with .bin file (please check that there is the .bin file only on the sd card)
5) turn on Ender 3
6) now there's blank screen
7) wait until new firmware is updateted
8) test auto home and bed leveling before you start a print
9) change extruder e-steps manually to 424.9 steps/mm 
