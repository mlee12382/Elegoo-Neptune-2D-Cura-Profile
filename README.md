## :warning: USE AT YOUR OWN RISK :warning:
Just to cover my ass

# Elegoo-Neptune-2D-Cura-Profile

*  This is an updated version of https://github.com/Toylerrr/ELEGOO_Neptune2_Cura to fully incorporate the changes needed to make the profiles work with the Neptune 2D to make it easier to share until he is able to update the changes. 
*  You will need to install it the "hard" way; copy the files into C:\users\username\appdata\cura\4.13\  where username reflects your username and 4.13 corresponds to the version of cura you have installed; for mac and linux the file locations will be different but the process is the same, and then run cura and then the Neptune 2 and Neptune 2D should be available in the add printer wizard under non-networked printer, for the Neptune 2S use the Neptune 2 profile.
*  You can still use the quality settings from https://github.com/just-trey/elegoo_neptune_2_CHEP_cura_profiles
*  If you are running a bltouch or other bed levling probe then remove the ';' from the beginning of the start gcode to enable the mesh and / or create a new mesh, remember for stock firmware it will ask you to set/ confirm your z-offset if you run G29.


![Img of Cura with Neptune 2](https://i.imgur.com/2yjM7Hl.png) 
## Overview 

This is the Cura profile that was made by ELEGOO and I modified it to work with the newest version of cura and removed some unused defaults. I have also added the STL of the bed from the original Neptune 2 STEP files

## How to install
<b>Hard</b>: Just download the master zip and drop the contents into your cura install folder or Appdata

<b>Easy</b>: Download the plugin version from the [Releases](https://github.com/Toylerrr/ELEGOO_Neptune2_Cura/releases) section and drag and drop into the cura windows

## Better Profiles
Just-Trey made some printer profiles for this machine definition. 

Those can be found here: https://github.com/just-trey/elegoo_neptune_2_CHEP_cura_profiles

## Alternate Bed Mesh
 Merrik over on Thingiverse made an alternate bed mesh you can find that here: https://www.thingiverse.com/thing:5141570
## FAQ
[How to get icons on print screen](https://github.com/Toylerrr/ELEGOO_Neptune2_Cura/wiki/How-to-get-icons-on-print-screen)

[How to get MKS Wifi to show up when outdated](https://github.com/Toylerrr/ELEGOO_Neptune2_Cura/wiki/How-to-get-MKS-Wifi-to-show-up-when-outdated)

[How to fix wobbly buildplate](https://github.com/Toylerrr/ELEGOO_Neptune2_Cura/wiki/How-to-fix-wobbly-heat-bed)

[How to fix wobbly base](https://github.com/Toylerrr/ELEGOO_Neptune2_Cura/wiki/How-to-fix-wobbly-base)

