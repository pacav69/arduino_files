
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


[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="encrypted" value="-----BEGIN PKCS7-----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-----END PKCS7-----
">
<input type="image" src="https://www.paypalobjects.com/en_AU/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal – The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_AU/i/scr/pixel.gif" width="1" height="1">
</form>
)