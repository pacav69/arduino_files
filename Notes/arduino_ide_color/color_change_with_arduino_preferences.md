# Using Zip files for themes


## Hexcode for colors
http://www.javascripter.net/faq/rgbtohex.htm

https://www.rapidtables.com/web/color/green-color.html

## File locations:

* on mac:
Arduino.app/Contents/Resources/Java/lib/theme/theme.txt 

* on Win7: 
C:\Program Files\Arduino\lib\theme\theme.txt

* on Linux: 
.../arduino-1.6.3/lib/theme/theme.txt

* on Windows 10: when installed as an App, C:\Program Files\WindowsApps\ArduinoLLC.ArduinoIDE_1.8.10.0_x86__mdqgnx93n4wtt\lib\theme\theme.txt, however it does not seem possible to edit it - it can be opened in notepad++ but a save fails.

## Procedure 

Using zip application create a zip file containing the original theme.txt found in the location of your operating system.
call it theme.txt.original.zip

Now modify the theme.txt file for colors, font sizes, etc
using zip application create a zip file containing the edited theme.txt found in the location of your operating system.
call it theme.txt.custom.zip

In the Arduino IDE goto the menu Arduino-->preferences under the option theme select theme.txt.custom.zip from the drop down list and restart Arduino IDE and the custom theme will take effect.

Copy the theme.txt.custom.zip file to a safe location so it will be available when there is an upgrade or reinstallation.

## Some suggested changes

changed console.font to 18
changed console.error.color to #7CFC00 - lawngreen

	# GUI - CONSOLE
	console.font = Monospaced,plain,11
	console.font.macosx = Monaco,plain,18
	console.color = #000000
	console.output.color = #eeeeee
	# original orange #E34C00
	# lime green #BFFF00 
	# lawngreen	#7CFC00
	console.error.color = #7CFC00

changed editor.comment2 to #434F54,bold - dark grey and bold

	# TEXT - COMMENTS
	editor.comment1.style = #434F54,bold
	editor.comment2.style = #434F54,bold

Increased linestatus.font to 14
increased linestatus.height to 30

	# LINE STATUS - editor line number status bar at the bottom of the screen
	linestatus.font	   = SansSerif,plain,14
	linestatus.height  = 30
	
## error message color
![<error message color lawngreen #7CFC00 >](<https://github.com/pacav69/arduino_files/blob/master/Notes/arduino_ide_color/errormessageinarduinoide.png>)


[arduino wiki](https://github.com/arduino/Arduino/wiki/Using-Zip-files-for-themes)

More info [ThemeTest github](https://github.com/per1234/ThemeTest)


you could also copy this file to the theme directory
[theme.txt_visually_improved pacav.zip](https://github.com/arduino/Arduino/files/2449671/theme.txt_visually_improved.pacav.zip)




