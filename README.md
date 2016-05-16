# X52 Elite Dangerous Mappings
This repo has the files needed to setup the keybinds described in this video series (https://www.youtube.com/playlist?list=PLbwEFrIX0iAi3Lh7_ozYTyatpI-JjIO3G).  The folder EDX52ProV1 has Matt's original files that work with the X52 PRO. Users of the silver/NON PRO version of the X52 will need to use the files in EDX52NonProV1.  Functionally, they're (mostly) identical and follow what's described in the video series.  There are some minor differences in how the software handles the two sticks that make the files incompatible between the different versions of the stick.

The .pr0 is the mapping file for the joystick/throttle.  It needs to go into C:\Users\Public\Documents\SmartTechnology Profiles.  Once it's in that folder, it will be avilable in the context menu of the X52 software's system tray icon.

The .binds file needs to go to C:\Users\<username>\AppData\Local\Frontier Developments\Elite Dangerous\Options\Bindings.  This will overwrite any custom changes you've made.  Make sure you copy your .binds file somewhere else or rename it if you want to keep it around.  There doesn't seem to be any recognition of file names other than Custom.1.8.binds, contrary to what you can find on the internet.

## Notable differences

I've made some minor changes to the mappings as they're described in the videos.

* Head Fix/Reset HMD is F11 instead of F12 to avoid conflicts with steam's screenshot functionality.
* Jettison all cargo is UNBOUND in Elite's configuration.  It's still defined in the X52 configuration software, so if you need it to work, go into Elite's control configuration and assign Ctrl + J and you will have jettison all cargo on pinky trigger + toggle 6.
* I am playing with a Rift, so I don't really have any need of the pinky trigger + hat left/right to access the left and right panels, nor do I need toggle 3 for the Role panel.  These buttons might be changed to something else in the future if I can come up with something useful to have there.
