Headless-Ripper
===============

GDVD, 0.8 - Greg's automatic DVD encoder
 
This script was designed on Debian 5.0 but should work on other distros without much work.

In order to run this script;
apt-get install the following 
HandBrakeCLI - for the encoding 
hal - to automatically run the program on DVD insert
lsdvd - to retrieve the title of the DVD

Change the settings in this file to suit;

Then place these files in the following locations;
/usr/share/hal/fdi/information/20thirdparty/dvdinsert.fdi 
/usr/lib/hal/pgmrun 
/usr/lib/hal/dvdinsert

Chmod to 600 and allow them to be excuted, restart hal with "/etc/init.d/hal restart", throw in a DVD and enjoy! :)

Any questions, comments, or suggestions please contact me 
via my we site, www.Gregology.net
