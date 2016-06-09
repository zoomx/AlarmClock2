# AlarmClock2
An Arduino sketch that makes use of an LCD Keypad Shield and a DS1302 RTC to build an Alarm Clock.

 Original version
https://github.com/pAIgn10/AlarmClock

 Modifications by Zoomx 2015
 * SLCDKeypad and DS1302 libraries are in the same sketch folder.
 * Changed from DS1307 to DS1302.
 * used the ICSP pins to communicate with DS1302 and avoid any solder.
 * Added Set hours and minutes of RTC.
 * When you set hours and minutes you start from the actual values and not from zero.

LEFT: When in Set Alarm Minutes jump to Set Hours and Minutes

TODO: Save alarm time in EEPROM!

![](https://lh3.googleusercontent.com/-2ueynXZgc2c/Vjsc-EEsrxI/AAAAAAAAaMk/bZjBRKhtbFY/s1152-Ic42/20151022_143945.jpg)
