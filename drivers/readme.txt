
For MAC Users
after installing the drivers
type this in the terminal

sudo ln -s /dev/tty.wch\ ch341\ USB\=\>RS232\ 1410 /dev/tty.wch

Quick Tutorial

Download Driver Files for your OS
CH341SER Mac IconCH341SER Mac 0.00 KB
Download
CH341SER Linux IconCH341SER Linux 0.00 KB
Download
CH341SER Windows IconCH341SER Windows 0.00 KB
Download
Install software but don’t restart yet.
Launch Terminal
sudo nvram boot-args=”kext-dev-mode=1″

One more additional step for Mac OS X users. Disable the kext signing security setting with this command.

sudo nvram boot-args="kext-dev-mode=1"

How to test it;

on the terminal type;

ls /dev/tty*

you should see something like "/dev/tty.wchusbserial1410". In addition, if you open up your Ardunio IDE then goto Tools->Port. You should see something similar to below.

Restart your Mac
Launch Terminal
sudo ln -s /dev/tty.wch\ ch341\ USB\=\>RS232\ 1410 /dev/tty.wch


ln -s /dev/tty.wch\ ch341\ USB\=\>RS232\ fd120 /dev/tty.wch


cd /Users/[username]/Applications/Arduino.app/Contents/Java/hardware/arduino/avr


