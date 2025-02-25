printer is a creality ender 3v2 chassis.
upgraded with the following:

  * e3d hemera hotend

  * linear rails on x axis

  * dual motor z axis, independently controlled to allow gantry levelling function

  * bltouch for bed mesh and z stop

  * bigtreetech octopus pro mainboard https://github.com/bigtreetech/BIGTREETECH-OCTOPUS-Pro

  * raspberry pi running mainsail os, with camera https://docs-os.mainsail.xyz


to configure z offset, in printer.cfg, uncomment z-offset under [bltouch], then delete corresponding zoffset lines at bottom, under 'save_config'

using cura as a slicer, there is a slicer configuration file for PLA

if you want a 3d cad program, fusion 360 is perfect. the hobbyist licence is free. 


Todo:

  * print enclosure for motherboard. 

  * print enclosure for pi

  * power pi directly from mainboard

  * led lights (wiring already in place)