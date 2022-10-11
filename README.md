# Ender_3_Pro_V4.2.2._Sprite_Extruder
Share Marlin Config for Ender 3 Pro with V4.2.2. Board, BLTouch, CRTouch or Clones with new Sprite direct drive Extruder.

Changes:
1) Resize Build Plane to 210mmx210mmx250mm (WxLxH) to avoid collision of Sprite extruder with right X-Axis
2) Auto-bed-leveling grid 4x4 with 30mm margin due to Probe Offset 
3) max extruder temp is 260 degrees celsius- no unlock for 300 degrees
4) after flashing new firmware change e-steps of extruder stepper to 424.9 steps/mm

firmware is tested with Ender 3 Pro with V4.2.2. Board and BLTouch Clone
