# ChuckLooper
The basic functions of the Boss RC-50 LoopStation... with chuck and a Midi Controller (examples with AKAI LPD8)

This is an attempt to emulate the basic functions of the boss RC-50 LoopStation.

![Boss RC-50 LoopStation](https://github.com/rodolfoap/chucklooper/blob/master/img/rc_50_top_gal.jpg "Boss RC-50 LoopStation")

This uses an AKAI LPD8 controller to control the RC-50 pedal functions:

![Akai LPD8 Midi Controller](https://github.com/rodolfoap/chucklooper/blob/master/img/lpd8_web_large.png "Akai LPD8 Midi Controller")

Basically, Pads 1, 2, 3 are used to enable/disable track loops. Pad 8 ends. Vol controls 1 to 3 will be used to control levels.

Here's a script to run it on Linux. I suppose a similar one should do for windows.

	$ cat rc50

	#!/bin/bash
	chuck.pulse rc50.chuck

Enjoy!
