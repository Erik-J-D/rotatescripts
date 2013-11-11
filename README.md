###Screen Rotation Scripts for X220T Running Ubuntu

These scripts are for rotating the screen and pen and touch interfaces for an X220T.

To install:

    cd ~
    git clone https://github.com/Erik-J-D/rotatescripts.git
    cd rotatescripts
    chmod 744 ./*
    cp ./autorotate ~/.config/autostart/ #only if you want autorotation
    

If you followed the last step for autorotation, log out and log back in for it to work.

You can also run "rotatebutton" (or map to a hardware button) to rotate the screen in 90 degree increments.
The trackpoint is disabled for all orientations except normal.

Tested on Ubuntu 12.10 -> 13.10, based on [link](https://help.ubuntu.com/community/X61T).
