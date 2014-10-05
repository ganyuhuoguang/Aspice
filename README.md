Aspice
======
<b>Aspice</b> is motion detection app for Raspberry Pi Camera. It allows you to use RPi as surveillance system to capture images based on movement in camera area.


<b>Installation</b>

1. Open terminal on your RPi and install PIL to run this script.

  <code> sudo apt-get install python-imaging-tk </code>

2. Make the script executeable by typing:
   
  <code> chmod +x ~/aspice.py </code>

3. You will need to create the folder to store your pictures:
   
  <code> mkdir ~/aspice </code>

4. Start the script by typing in Terminal:
  
  <code> ~/aspice.py </code>

The script is now running and taking pictures

<b>Options</b>

Adjust the settings of the script. Open Nano editor in terminal by typing:

  <code> nano ~/aspice.py </code>

Now you can change settings of each feature, for example sending pictures to e-mail and adjust motion sensitivity.

<b>Next up</b>

Aspice is a work in progress. This is a beta release. There are a few things coming up:

<li>Live streaming option</li>

<li>Surveillance system</li>
