## MXChip example ##
Scrolling text and images on mxChip display. This example shows some welcome to workshop text.
More information about creating it you can find [on my blog](https://www.programistkaikot.pl/2020/01/mxchip-fajne-powitanie-na-warsztatach.html) 


## image2cpp ##

Use this tool online at http://jlamch.net/MXChipWelcome/ 

image2cpp is a simple tool to change images into byte arrays (or your array back into an image) for use with (monochrome) displays suchs as OLEDs, like those from Adafruit or Sparkfun. Alternatively you can also enter a byte array as input to turn it back into an image. This might be useful for debugging.

### Running the tool ###
You don't need any special dependencies / internet connection; all the necessary parts sit in a single .html file. So just open this index.html page in a (recent) browser to run the tool.
Or you can use the online version at http://jlamch.net/MXChipWelcome/

### Example Arduino code ###
You can find a simple Arduino example sketch [over here](https://github.com/javl/image2cpp/blob/master/oled_example/oled_example.ino) in the repository.

### MXChip example ###
MXChip example you can see in this repository

### Screen types ###
This code was written with 128x64 pixel monochrome OLED display in mind, but it should work with most similar displays. You might need to change some export settings; those are explained in the tool.

### Credit ###
Initial code by [javl](https://github.com/javl), with aditional code by (in alphabetical order) [davidalim](https://github.com/davidalim), [jochenderwae](https://github.com/jochenderwae), [whoisnian](https://github.com/whoisnian) and [wiredolphin](https://github.com/wiredolphin).
The example sketch is based on code by [Adafruit](https://github.com/adafruit). Orginal tool you can find [here](http://javl.github.io/image2cpp/)