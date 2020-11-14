# Homework Embedded Linux

For this homework, you will need access to a Raspberry Pi, 
and a temperature sensor.  The simplest possible approach is 
to use the DS18B20 digital sensor that uses the one-wire
bus protocol.  If you prefer an off-board LED, see the videos
for more information, but you can use an on-board LED if your
RPi has one (true for all but the zero, I think).

If you do *not* have a Raspberry Pi and want to complete this
homework, I will set up my own hardware with the DS18B20
noted above and provide you a username and password for this 
assignment.  I will also try (but cannot promise) to provide 
a live video of it during certain hours of the day.

## Problem 1

Create a Python module (i.e., a `.py` file) named 
`embeddedfun.py`.  In that module, define the functions
`led_on()` and `led_off()` that turn the red (power)
indicator on or off, respectively.

## Problem 2

Add a function that gets the temperature from your 
sensor in degrees fahrenheit called `get_temperature()`.

## Problem 3

Use the functions you defined above to create a 
program that checks the temperature  
every 10 seconds and flashes the LED at 1 s intervals
when the temperature exceeds some threshold.

