# HIKVISION-PTZ-control-Node-Red
Node-red flow for PTZ control of hikvision using HTTP PUT method from Hikvision ISAPI 



This flow allows the user to aim a PTZ from Hikvision to a preset. Which is already made in the PTZ menu.

The method used is HTTP PUT from the Hikvisoin ISAPI.

You need to put the follow details of the PTZ or NVR:

IP (either of the NVR or from the PTZ itself) 
Port (usually 80)
 Password (PTZ / NVR password) 
User (PTZ / NVR user) 
Channel (1 for PTZ, for the NVR depending on which channel you want to control) 
Preset (the preset number you want to call)

![Knipsel2](https://user-images.githubusercontent.com/32663614/153726949-c42abc3c-b3d4-4ca5-8df4-72ce1b883168.PNG)
![Knipsel](https://user-images.githubusercontent.com/32663614/153726950-b48d37f2-5acf-439c-9bd1-a686f5c84cd0.PNG)


