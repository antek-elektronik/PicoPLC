# picoPLC

Work in progress! 

This is 'industriual' adaptation for raspberry pi pico 2W. This is a hobby project developed by me (AntekElektronik) with no plans for building it (yet). 

## features 

This device features a 8 optotransistor 24V inputs, 4 10A 230V relay outputs and 4 transistor outputs latching to ground. The device is powered by 24V external power supply and has 24V -> 5V switching power regulator onboard (the rpi pico 2w takes care of regulating 3.3V). 

## wireles connectivity

I am aware that rpi pico's wireless features won't work enclosed inside a metal case. I plan on changing to esp32 with external antenna in future. This project could be used as a base for mainstream microcontroller based PLC controllers

## software

for the time of writing this, I do not have any software written. First stage would be a micropython file with predefined variables and functions for basic I/O operations on picoPLC platform, the rest would have to be written in micropython. 

I plan to use an existng project like openPLC, find something similar or write from scratch a program for executing ladder logic or function blocks. 