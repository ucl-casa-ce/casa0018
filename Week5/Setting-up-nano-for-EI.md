# Enabling data acquisition on Nano

We will use WebUSB to collect data from the Arduino Nano 33 BLE Sense as this seems the simplest method to configure.  
Note that WebUSB is not supported by Safari or Firefox web browsers, so you will need to use Chrome or Edge.  
The following link will guide you through the process:  
https://docs.edgeimpulse.com/hardware/boards/arduino-nano-33-ble-sense#connecting-to-edge-impulse  
but you only need to follow the two steps:
1. Connect the development board to your computer

2. Update the firmware

That's all. You don't need to install the Edge Impulse CLI to use WebUSB.


Installing Arduino CLI for Windows
----------------------------------
https://arduino.github.io/arduino-cli/0.21/installation/  
Copy arduino-cli.exe to somewhere sensible and add enclosing folder to your Path



Installing Edge Impulse firmware for Nano 33 BLE Sense  
------------------------------------------------------
https://cdn.edgeimpulse.com/firmware/arduino-nano-33-ble-sense.zip  
Unzip and run flash_windows.bat file


