ArduinoCompilationWithAVR
=========================

This project shows how you can compile an Arduino program with AVR-GCC.<br/>
The advantages of this solution are :
<ul>
	<li>The software upload is easier for the user (just a file to upload, no need libraries and program compilation)</li>
	<li>The software deployment without the program source</li>
	<li>You don't need user interface to compile and upload program into the arduino board</li>
</ul>
INSTALLATION
------------
* Debian/Ubuntu<br/>
<code>apt-get install avr-libc avrdude binutils-avr arduino-core</code>	
* Windows<br/>
	
COMPILATION
-----------
To compile, place you into the project directory and run make<br/>
<code>cd ArduinoCompilationWithAVR/<br/>
make</code>

UPLOAD
------
To upload, place you into the project directory and run make upload<br/>
<code>cd ArduinoCompilationWithAVR/<br/>
make upload</code>

USE
---
* Display USB trace<br/>
<code>cat /dev/ttyACM0</code>