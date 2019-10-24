==================================
|     HARDWARE PROBLEM SOLVER    |
|    by Matthias Schneglberger   |
==================================

To Use:

Open ProblemWithDevice.bat per rightclick and click on "edit"
change the line with "devcon.exe remove *YOUR_PID*" with your PID
You can find the pid of your device by opening the device Manager, search the device and go to properties > Details > Hardware-ID's
the PID should be in the Value Box
for example "USB\VID_9710&PID_7830" the PID would be 7830
it can also be antoher value than PID for example VID REV


testing:
cd THIS_PATH
devcon find *YOUR_NUMBER*
when you find only your problem this number is working