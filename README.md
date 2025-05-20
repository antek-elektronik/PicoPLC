# picoPLC

Work in progress! 

This is 'industriual' adaptation for raspberry pi pico 2W. This is a hobby project developed by me (AntekElektronik) with no plans for building it (yet). 

## features 

This device features a 8 optotransistor 24V inputs, 4 10A 230V relay outputs and 4 transistor outputs latching to ground. The device is powered by 24V external power supply and has 24V -> 5V switching power regulator onboard (the rpi pico 2w takes care of regulating 3.3V). 

## wireles connectivity

I am aware that rpi pico's wireless features won't work enclosed inside a metal case. I plan on changing to esp32 with external 