# Amazfit-Bip-Watchface
A digital watchface I made for the Amazfit Bip.  It is a 12 hour (am/pm) watch face and midnight to 12:59AM displays as "0:00" to "0:59".  I've tried fixes to get around that issue but "10:00" to "10:59" don't work when I try them.

This .json file and images can be used to create an Amazfit Bip watchface.  
The .bin file is ready to install.  You can make changes by editing the
.json file and/or changing the images.  This page has some details about the .json file format.

You can see the changes before
installing on the watch at https://amazfitwatchfaces.com/editor/watchfaceEditor/?bip.
This site also lets you see the view with different settings (time-of-day, temperature, etc)

This page describes the steps needed to hex edit the .bin file 
and install the .bin as a "Local watch face"  
https://amazfitwatchfaces.com/forum/viewtopic.php?f=14&t=128
The .bin file in this repository has already been hex edited.

Issues:
* When I created the images I had antialiasing enabled.  The watch has very limited colors and some of the small digits and the background look fuzzy because of this.  I'm happy with it so haven't gone back to clean it up.
* Midnight shows as "0:00" instead of "12:00".  Some people say they've fixed this but their technique breaks "10:00".  I'm happy with 12AM being "0".