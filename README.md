######################################
# Simple Teleop System for MBot-Mini #
#            pgaskell                #
######################################


This is a simple teleoperation system to test the MBot-Mini

Use the arror keys to drive around.

You should see an image. if it is upside down or mirrored,
use the 'h' and 'v' keys to flip it.

close the qindow or press 'q' to quit

Copy this folder to both the Beaglebone Blue and the Raspberry Pi
on the MBot-Mini.

1. On the Beaglebone run 
   $ ./mbot_drive_simple

2. On the Raspberry Pi run 
   $ python3 mbot-teleop-simple.py

3. If you want to see the LCM traffic on the RPi
   in a different terminal run: 
   $ source setenv.sh
   $ lcm-spy
