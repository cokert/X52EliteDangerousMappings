# X52 Elite Dangerous Mappings
This repo has the two files needed to setup the keybinds described in this video series (https://www.youtube.com/playlist?list=PLbwEFrIX0iAi3Lh7_ozYTyatpI-JjIO3G) for the NON PRO version of the X52 HOTAS system.  The files linked in the descriptions of those videos will only work with the X52 Pro.  If you're using the silver X52 joystick, you'll need to use these files.  Functionally, they're (mostly) the same as what the video described.  There are some minor differences in how the software handles the two sticks that make the files incompatible between the different versions of the stick.

The .pr0 is the mapping file for the joystick/throttle.  It needs to go into C:\Users\Public\Documents\SmartTechnology Profiles.  Once it's in that folder, it will be avilable in the context menu of the X52 software's system tray icon.

The .binds file needs to go to C:\Users\<username>\AppData\Local\Frontier Developments\Elite Dangerous\Options\Bindings.  The .binds file in the linked description will unbind all axis mappings for the joystick.

## Notable differences

I've made some minor changes to the mappings as they're described in the videos.  This is all I can think of right now that was changed.

* Head Fix/Reset HMD is F11 instead of F12 to avoid conflicts with steam's screenshot functionality.
* Jettison all cargo is UNBOUND in Elite's configuration.  It's still defined in the X52 configuration software, so if you need it to work, go into Elite's control configuration and assign Ctrl + J and you will have jettison all cargo on pinky trigger + toggle 6.
* I am playing with a Rift, so I don't really have any need of the pinky trigger + hat left/right to access the left and right panels, nor do I need toggle 3 for the Role panel.  These buttons might be changed to something else in the future if I can come up with something useful to have there.
