Aspice
======
Aspice is motion detection app for Raspberry Pi Camera. It allows you to use RPi as surveillance system to capture images based on movement in camera area.


Installation

1. Open terminal on your RPi and install PIL to run this script.
   sudo apt-get install python-imaging-tk

2. Make the script executeable by typing:
   chmod +x ~/aspice.py

3. You will need to create the folder to store your pictures:
   mkdir ~/aspice

4. Start the script by typing in Terminal:
   ~/aspice.py

The script is now running and taking pictures

Options

Adjust the settings of the script. Open Nano editor in terminal by typing:

nano ~/aspice.py

Now you can change settings of each feature, for example sending pictures to e-mail and adjust motion sensitivity.

Next up

Aspice is a work in progress. This is a beta release. There are a few things coming up:

Live streaming option
Surveillance system
