# Elegoo-Neptune-2D-Cura-Profile

*  This is an updated version of https://github.com/Toylerrr/ELEGOO_Neptune2_Cura to fully incorporate the changes needed to make the profiles work with the Neptune 2D to make it easier to share until he is able to update the changes. 
*  You will need to install it the "hard" way; copy the files into C:\users\username\appdata\cura\4.13\  where username reflects your username and 4.13 corresponds to the version of cura you have installed; for mac and linux the file locations will be different but the process is the same, and then run cura and then the Neptune 2 and Neptune 2D should be available in the add printer wizard under non-networked printer, for the Neptune 2S use the Neptune 2 profile.
*  You can still use the quality settings from https://github.com/just-trey/elegoo_neptune_2_CHEP_cura_profiles
*  If you are running a bltouch or other bed levling probe then remove the ';' from the beginning of the start gcode to enable the mesh and / or create a new mesh, remember for stock firmware it will ask you to set/ confirm your z-offset if you run G29.
