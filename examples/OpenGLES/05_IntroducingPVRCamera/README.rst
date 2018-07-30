====================
IntroducingPVRCamera
====================

.. figure:: ./IntroducingPVRCamera.png

Use the PVRCamera library to get the hardware camera of a device, and apply a simple color inversion shader to it.

Description
-----------
The PVRCamera library gives a very simple, unified API to access the video feed of an iOS or Android device as an OpenGL ES texture. This demo displays this texture on the screen using a very simple shader that inverts the colours.
Note: On desctop platforms, the camera interface returns a dummy static texture to facilitate development. On android N, the Camera permission must be given to the application.

APIS
----
* OpenGL ES 2.0+

Controls
--------
- Quit- Close the application
