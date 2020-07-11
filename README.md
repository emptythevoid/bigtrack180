This is an xorg config file for the BIGtrack or Crayola PC Trackball. 

https://www.ablenetinc.com/bigtrack-2

For some people, the trackball may be easier to use if the buttons are placed on the bottom, rather than the top (Mickey Mouse style).  This requires a few options to be set in the xorg file to allow for this.  

The configuration also includes scrollwheel emulation when the right-mouse button is held.

This config is written for the older serial-only model, using a serial-to-usb adapter and inputattach --mouseman. This will cause the Identifier to be "Logitech M+ Mouse".  Change this if you are connecting a newer model using USB or a PS/2 adapter.

