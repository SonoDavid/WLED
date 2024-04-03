# Word Clock Usermod V2 NL

This usermod drives an 11x10 pixel matrix wordclock with WLED. There are 4 additional dots for the minutes. 
The visualisation is described by 4 masks with LED numbers (single dots for minutes, minutes, hours and "clock"). The index of the LEDs in the masks always starts at 0, even if the ledOffset is not 0.
There are 3 parameters that control behavior:
 
active: enable/disable usermod
diplayItIs: enable/disable display of "Het is" on the clock
ledOffset: number of LEDs before the wordclock LEDs


## Installation

Copy and update the example `platformio_override.ini.sample` 
from the Rotary Encoder UI usermod folder to the root directory of your particular build.
This file should be placed in the same directory as `platformio.ini`.

### Define Your Options

* `USERMOD_WORDCLOCK_NL`   - define this to have this usermod included wled00\usermods_list.cpp

### PlatformIO requirements

No special requirements.
