# Printrbot2MiniMax
notes and instructions for converting printrbot simple 1405 to a MTW [MiniMax](http://store.makerstoolworks.com/printers-kits/minimax-by-makers-tool-works-full-printer-kit/)

# Printed Parts
* 1 x [Printrbot extruder mount](https://www.youmagine.com/designs/printrbot-extruder-mount-for-mtw-minimax)
* 1 x [Printrboard mount](https://www.youmagine.com/designs/printrboard-mount-for-extrusion)
* Additional but unnecessary printed modifications may be found [here](https://github.com/quillford/3D-Modeling/tree/master/Printer%20Mods/MiniMax).

# Additional Vitamins
* The Z-probe that comes with the newer printrbots is not of much use when the MiniMax has a way to properly level the bed which I find preferable. This means that you will need an additional microswitch/endstop for the Z axis. You could use the probe as a Z axis, but a microswitch is a bit easier. If you want to modify my extruder mount to make use of the probe, the scad is [here](https://github.com/quillford/3D-Modeling/blob/master/Printer%20Mods/MiniMax/scad/printrbot_extruder_adapter.scad).

# Modify parts from the printrbot
* For the Simple 1405, the X endstop needed to be lengthened and possibly the Y endstop depending on where it is used. Lengthening the wires is as simple as put extra wire between the existing ones to preserve the molex connector.
![endstop wire Lengthening](https://raw.githubusercontent.com/quillford/Printrbot2MiniMax/master/pictures/IMG_7687.JPG)

# Pictures
![extruder](https://github.com/quillford/Printrbot2MiniMax/blob/master/pictures/IMG_7681.JPG)
![extruder](https://github.com/quillford/Printrbot2MiniMax/blob/master/pictures/IMG_7683.JPG)
![extruder](https://github.com/quillford/Printrbot2MiniMax/blob/master/pictures/IMG_7685.JPG)
![printrboard mount](https://github.com/quillford/Printrbot2MiniMax/blob/master/pictures/IMG_7680.JPG)