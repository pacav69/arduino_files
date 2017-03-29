
# Arduino Files

# Introduction
These are files that i have found to use with Arduino

## Using CH340 USB to serial driver

If you have purchased an Arduino clone that has a CH340 USB to serial chip
then you will need the driver to use on your Mac OS X or PC.


CH340 USB to Serial chip drivers it can be found here:

[CH341SE driver](http://www.wch.cn/download/CH341SER_ZIP.html)

or in the drivers folder.

Some detailed instructions can be found here

[nstructables](https://www.instructables.com/id/Arduino-Nano-CH340/)

## On a Mac

After downloading the drivers file
Install the package and before rebooting do the following:

* Open terminal
* Write the following: 
	
	sudo nvram boot-args="kext-dev-mode=1" 

* Do not mess up here. It may ruin your computer if you write the wrong code.

* Once you have pressed enter, you will be prompted you for your password.
* Once done, restart your computer.
