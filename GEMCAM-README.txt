Userland fork with raspigemcam in host_applications/linux/apps/raspicam/

New files:
RaspiGCam.c
RaspiGCmds.c
RaspiGemcam.c
RaspiGemcam.h
RaspiGMotion.c
RaspiGUtils.c

Modified file in same directory:
CMakeLists.txt

After building, raspigemcam will be located in /opt/vc/bin on the raspberry

Note: raspigemcam is a slightly modified copy of raspimjpeg.

As raspimjpeg is de facto a dedicated driver for RPi_Cam_Web_Interface, It was not
feasable to use it als for the RaspiGemcam.

I want all files neatly in the install directory in the apache directory (as it is 
intended for dedicated use only), and that is also not possible,

Too much hassle without returns.


