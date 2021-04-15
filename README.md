# esphome-waterlevel
A water level monitoring system for homeassistant using esphome and ultrasonic sensor.

![calculate-2](https://user-images.githubusercontent.com/61015809/114900443-7f399b80-9e31-11eb-833e-3b0cfbc1038f.png)

Measure the following:
MAX --> Distance from sensor to the max water level in CM.
MIN --> Distance from sensor to min water level in CM.

Calculate M:
M= 100/(MIN-MAX)

Expression:
M(MIN - (X*100))



Example:
Say MAX is 10cm and MIN is 120cm

M= 100/(120-10) = 0.9

So the expression will be:
0.9(120- (X*100))




