-----------------------------------------------------------------
Controls summary for all Cores
==============================

Check each Core's README for Core specific controls.

-----------------------------------------------------------------

Keyboard inputs:

  Coin           : Escape
  Start player 1 : F1
  Start player 2 : F2

  Cursor Up/Down/Left/Right : Movement
  Fire           : SPACE

Joystick controls:

  Movement  : D-Pad  
  Fire      : Button 1 
  OSD       : SELECT+START

-----------------------------------------------------------------

Joystick Customisations:

Put these entries in the mist.init section [mist]

iBuffalo SNES (D-Pad, A/B/X/Y, Select{COIN}, Start{Player1}, Y+A{OSD} ):
joy_key_map=1000,29 ;L2 to ESC
joy_key_map=2000,3A ;R2 to F1
joystick_remap=0583,2060,1,2,4,8,10,20,40,80,400,800,1000,2000
