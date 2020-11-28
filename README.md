# Arduino Wire64
A modified version of the Arduino Wire library with a 32 Byte buffer which does not enable pull-up resistors on the SCL and SDA pins.

Add this library to your Sketchbook > libraries folder and include it as:
 
\#include <Wire64>
	 
Use just like the Arduino included Wire library but you can send/recieve up to 64 Bytes ata time.