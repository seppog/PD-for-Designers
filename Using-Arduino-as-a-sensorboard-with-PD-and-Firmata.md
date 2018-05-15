# Setting up your Arduino and PD for Firmata

Firmata control of the Arduino requires loading an Arduino with the special Firmata sketch.<br
You can download the Arduino software from the Arduino website. After opening the Arduino IDE, follow these steps to install Firmata on your Arduino:<br>
Click File->Examples->Firmata->StandardFirmata<br>
From the Tools->Board menu, select the type of Arduino you are using.<br>
From the Tools->Serial Port menu, choose the USB port to which your Arduino is connected.<br>
Click the upload button (it looks like a right arrow, just next to the checkmark) and wait for your sketch to upload.<br> 
A message in the bottom black windowwill indicate success or failure

Setting up Pure Data:<br>
Install Pure Data(0.48-1) from http://msp.ucsd.edu/software.html<br><br>
Installing comport external to pure data via Deken<br>
Click -> Help -> find externals (in German last entry in menu)<br>
Search for  comport<br>
Install latest version for Your OS<br>
Installingpduino to pure data via Deken<br>
Click -> Help -> find externals (in German last entry in menu)<br>
Search for pduino<br>
Install latest version for Your OS<br>
Click -> Help -> Brwoser -> pduino -> arduino-help.pd or<br>
Click -> Help -> Brwoser -> pduino -> arduino-gui-help.pd to test<br>
