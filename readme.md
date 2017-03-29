
#

## Using CH340 USB to serial driver

If you have purchased an Arduino clone that has a CH340 USB to serial chip
then you will need the driver to use on your Mac OS X.


CH340 USB to Serial chip it can be found here:

http://www.wch.cn/download/CH341SER_ZIP.html

or in the drivers folder.

Some detailed instructions can be found here

https://www.instructables.com/id/Arduino-Nano-CH340/

For the drivers to work, do this before you reboot your mac:

1. Open terminal

2. Write the following (just copy from here): 

    sudo nvram boot-args="kext-dev-mode=1" 

Do not mess up here. It may ruin your computer if you write the wrong code.

3. Once you have pressed enter, terminal will prompt you for your user password. Type this and press enter.

4. Once done, restart your computer.

