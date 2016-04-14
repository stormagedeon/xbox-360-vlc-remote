**This is for the more advanced users, a little extra information for tweaking etc.**

# Button Configuration #
As can be seen in the configuration image, currently the hotkeys are triggered by the default xbox controller buttons assigned to video playback on an xbox plus a few extras. Many other buttons are available to be coded, feel free to experiment. (The codes for the controller buttons are all listed here: http://glovepie.org/w/index.php?title=Preliminary_Documentation_v0.43#XBox360_Controller)

# How to launch script (advanced) #
Other than simply clicking File>Open within GlovePIE, or selecting open with>GlovePIE, you may also use the command line interface for glovePIE to directly run the PIE file without having to open first. (by using the -filename.PIE switch, other commands available in the GlovePIE help file). This is useful when starting this script on computer start with GlovePIE minimised to the tray through the following method:

1. Create a shortcut to GlovePIE executable

2. Move the shortcut to Start Menu>Startup

3. Right-click>Properties on shortcut

4. Add the following to the end of the target box:
> -"C:\_mypath_\xbox360VLCremote.PIE" /tray
where _mypath_ is the location of the script you downloaded

# Limitations #
-Set focus to VLC media player does not work yet (if you have any suggestions I would be happy to hear them

-Subtitle position movement will only work if you have manually assigned Shift + Up to -subtitle up and Shift + Down to subtitle down.

-Startup script shortcut will only work if you have placed the GlovePIE.ink shortcut the Startup folder in the Start Menu and also extracted GlovePie to the recommended location (C:\Program Files\GlovePIE)