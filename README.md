printer is a creality ender 3v2 chassis.
upgraded with the following:

hemera hotend

linear rails on x axis

dual motor z axis, independently controlled to allow gantry levelling function

bltouch for bed mesh and z stop

bigtreetech octopus pro mainboard

raspberry pi running mainsail os, with camera


to configure z offset, in printer.cfg, uncomment z-offset under [bltouch], then delete corresponding zoffset lines at bottom, under 'save_config'
