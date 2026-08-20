# ThumbsUp! v13 RP2040-based ProMicro 3x12 chord keyboard for Omron and mouse switches.
                           
Steno/chord keyboard (number key instead of a bar)
2-key Thumb Cluster
Cirque ProGlide trackpad/touchpad


Omron mouse switches or 6x6 two-pin switches.

* RP2040 ProMicro x2
* TRS (3-wire) audio cable to connect the halves.
* USB-C connectors.

Silicone O-rings are used for the key paddles suspension: CS2.4mm, OD 11mm (12mm works too).
Cross section 2-2.5 mm works well.
OD less than 11mm result in much heavier keys. 
OD more than 12mm is a bit too loose.

This is a functional clone of my v12 rev.6 board with columnar stagger removed - all the finger keys are lined up along the asterisk key middle line.
https://github.com/ak66666/ThumbsUpV12_Omron
Schematics, thumbcluster and the MCU/touchpad corner are the same.
The only difference is the finger keys alignment.

Hinge boards are connected to the bottom layer with 10mm M3 stand-offs and M3 5-6mm bolts, for example from here:
https://www.amazon.ca/dp/B075GXLRF6
https://www.amazon.ca/dp/B00W8YSCIS

Omron switches sit in cradles.
Cradle model is: 3D Printed\Switch Raiser Omron Tilted.stl
Important: place it on the printer bed and sink it so the distance between the lower corner and the plate is 0.3-0.5 mm.
If the installed key is a bit too low - put a piece of electric or duct tape on the bottom side of the key.

3D printed tenting "heel" should fit since the innermost side is unchanged.


#Rev.0
![v13](https://github.com/ak66666/ThumbsUpV13_Omron/blob/main/Photos/rev.0/IMG_20260819_211051118_HDR.jpg)
![v13](https://github.com/ak66666/ThumbsUpV13_Omron/blob/main/Photos/rev.0/IMG_20260819_211058846_HDR.jpg)
![v13](https://github.com/ak66666/ThumbsUpV13_Omron/blob/main/Photos/rev.0/IMG_20260819_211128919.jpg)
![v13](https://github.com/ak66666/ThumbsUpV13_Omron/blob/main/Photos/rev.0/IMG_20260819_211135449_HDR.jpg)


Other pictures and videos in Photos folder.

# Firmware

TX-Bolt interface as the only connectivity option for now:
https://github.com/ak66666/qmk_firmware/tree/thumbsup_20240523/keyboards/thumbsup/rev12_rp2040_split_steno
