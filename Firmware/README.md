Firmware update on the Aether smart air filter is simple, and it can be done by either downloading the source code, or a pre-compiled hex from this folder.:

Using the source code:

1.) Download the source code (if you download it as a zip, extract it)
   
2.) If you don't have it installed, download, and install arduino IDE from  : https://www.arduino.cc/en/software

3.) Open the Firmware.ino file with the IDE

4.) Connect the Aether air filter with usb to the computer

5.) Select the arduino nano (atmega328p)  board from the Tools->Board menu

6.) Select the port from the Tools->Port menu

7.) Select Sketch->Upload 

8.) Wait for the upload to finish.

9.) Done. Ejoy!

Using a HEX file:

1.) Download the firmware.HEX file
   
2.) Download xLoader2 from : https://github.com/arrsoft312/arduino-hex-loader/releases/tag/v2.1.0

3.) Open the Firmware.hex file by clicking on the ... button

4.) Connect the Aether air filter with usb to the computer

5.) Select the COM port for the board

6.) Select the 115200 Baud rate

7.) Click upload

8.) Wait for the upload to finish.

9.) Done. Ejoy!

We do not have anything to do with either Arduino IDE, or the xLoader2 software, use them at your own risk!
