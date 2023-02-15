# RainbowShift-KlipperCode
RainbowShift Klipper Code for WLED Effects

Highly modified from https://github.com/digitalninja-ro/klipper-neopixel/blob/master/README.md as this only works on Neopixles.
The idea is to port this to work (Partly) with WLED in Moonraker.


Very early code of bed temp and progress display on rainbowshift by Vector3D https://vector3d.co.uk/product/rainbowshift-kit/

#### Assumptions 

* You have the WLED section in "moonrafer.conf" and that they are called "DaybreakNeos"
  https://moonraker.readthedocs.io/en/latest/configuration/#wled

* You also have in your macros the WLED Macros provided by https://moonraker.readthedocs.io/en/latest/configuration/

* Also your using a Daybreak with 13 pixles on it, and this all works by using the WLED Web address when you set them up.

* Currently Its also fixed colours Blue (cold) to Pink (Hot) / Blue (0%) to Pink (100%) complete 
