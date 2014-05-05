###Screen Rotation Scripts for X220T Running Ubuntu/Debian

These scripts are for rotating the screen and pen and touch interfaces for an X220T.

To install:

    cd ~
    git clone https://github.com/Erik-J-D/rotatescripts.git
    cd rotatescripts
    chmod 744 ./*
    #Next step only if you want autorotation, on ubuntu
    cp ./autorotate ~/.config/autostart/ 


xinput must be installed for automatically disabling / enabling trackpoint.    
If you're using Debian (tested on 7), ignore the last step and simply add it to your startup applications.

If you followed the last step for autorotation, log out and log back in for it to work.

You can also run "rotatebutton" (or map to a hardware button) to rotate the screen in 90 degree increments.
The trackpoint is disabled for all orientations except normal.

Tested on Ubuntu 12.10 through 13.10, based on [link](https://help.ubuntu.com/community/X61T).
