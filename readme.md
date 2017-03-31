
# Arduino Files

# Introduction
These are files that i have found to use with Arduino

## Using CH340 USB to serial driver

If you have purchased an Arduino clone that has a CH340 USB to serial chip
then you will need the driver to use on your Mac OS X or PC.


CH340 USB to Serial chip drivers it can be found here:

[CH341SE driver](http://www.wch.cn/download/CH341SER_ZIP.html)

or in the drivers folder.

Some detailed instructions can be found here:

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

## For Mac OS X Sierra

Use ch340g-ch34g-ch34x-mac-os-x-driver.zip located in the driver folder.

For more information:

[Visit MPParsley's github](https://github.com/MPParsley/ch340g-ch34g-ch34x-mac-os-x-driver)


### Links

#### Projects

[arduino.cc](http://www.arduino.cc/)

[arduino.org](http://www.arduino.org/)


[arduino projecthub](https://create.arduino.cc/projecthub)

[luckyresistor](https://luckyresistor.me/)

[allaboutcircuits](https://www.allaboutcircuits.com/)

[hackster](https://www.hackster.io/)

#### LCD

[u8g2 library](https://github.com/olikraus/u8g2)

p.s:
I **LOVE** coffee! Buy me a coffee at:   
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=adriankoooo%40gmail%2ecom&lc=SK&item_name=Adrian%20Mihalko&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)


![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="encrypted" value="-----BEGIN PKCS7-----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-----END PKCS7-----
">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal – The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_AU/i/scr/pixel.gif" width="1" height="1">
</form>
)
