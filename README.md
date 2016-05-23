# TF2 Crosshair Switcher
Team Fortess 2 Config File to switch Crosshairs for each weapon Slot on each Class.

Install
---------
Just add all files to you Tf2 "cfg" Folder and adjust the setting sin the class Files



Class Files
-----------

#### `cl_autoreload 1`
* Value = 1
  Turns on weapon autoreload for this Class
* Value = 0
  Turns off weapon autoreload for this Class
  
  
#### `exec crosshairSwitcher`
Noting to configure. Executes the crosshair Switcher


#### `alias primary "medium; green; cross; off"`
Defindes the Crosshair for the primary slot.
The parameters are listed in the quotes and seperatet by semicolons

**1. Parameter: Size**

  tiny / smallest / small / medium / big / biggest / huge / invis
  
**2. Parameter: Color**

  red / green / blue / yellow / cyan / pink / orange / purple / mint / lime / skyblue / black / grey / white
  
**3. Parameter: Shape**

  cross_with_dot / half_cross_with_dot / ring / ex / dot / open_cross / cross / default
  
**4. Parameter: Viewmodel of weapon**

  Range 60 - 120
  off = No weapon viewmodel _(viewmodel_fov = 90; r_drawviewmodel = 0;)_


#### `STANDART`
Defindes the default crosshair fot his class, if the alias ist not set or the crosshair switches fails

Same order as above, but vertical



Known Bugs
----------

Many...


Credits
-------
Going to Spok. Hey old buddy
