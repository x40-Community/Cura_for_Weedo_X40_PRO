# Ultimaker Cura Configuration for WEEDO X40 PRO
![image](http://www.x40-community.org/images/x40/Cura_Aqua_Theme.jpg)

## Weedo X40 PRO
X40 PRO is an improvement for the Weedo X40V1 and Weedo X40V2 printer. It eliminates the printer weaknesses from the cooling system, bugs in the firmware, extends the functionality of the firmware and adapts the printer to the Ultimaker Cura in order to be able to use the printer fully.

The X40 PRO system consists of:
- [X40 PRO Coolingsystem](https://github.com/x40-Community/X40_PRO-Community_Coolingsystem)
- [X40 PRO High Temperature upgrade](http://www.x40-community.org/index.php/firmware/x40-pro-high-temperature) (optional)
- [X40 PRO Extruder upgrade](http://www.x40-community.org/index.php/firmware/weedo-x40-extruder-upgrade) (optional)
- [X40 PRO Firmware](http://www.x40-community.org/index.php/firmware/x40-pro-firmware)
- X40 PRO Cura configuration
- [X40 PRO Cura Plugins](http://www.x40-community.org/index.php/cura/cura-plugins/9-cura-workflow/84-cura-plugins-2)

Project flyer (PDF) https://my.hidrive.com/lnk/M4UNmCwu

More information see http://www.x40-community.org/index.php/firmware/x40-pro-system

Youtube Video see https://www.youtube.com/@x40-community



## Ready to use
The X40 Community Cura configuration is much more than just a printer definition. It contains a printer visualization and hundreds of tested print profiles. Simply select a supported filament, make small adjustments such as support structure etc. and just print. There is no need to search for and test the correct print parameters. 

Here you can see the supported filament and the current status: http://www.x40-community.org/index.php/cura/cura-quality-and-intent-profiles

Standard configuration for Weedo X40 PRO
- Available for Cura 4.X and 5.X
- Full Idex printing support (Single LH, Single RH, dual mode normal, dual mode mirrored, copy mode)
- The configuration contains about 4000 print profiles.
- There are additional printing profiles for the high-temperature (HT) variant.
- Supported nozzle size 0,2mm, 0,4mm, 0,6mm and 0,8mm (not for all printing profiles)
- You may have wondered why the first layer is sometimes different. We found the bug and fixed it. Weebuilder cannot fix the bug!
- The Cura plugin for embedding the printer preview image is not part of the configuration!

More Information see http://www.x40-community.org/index.php/cura/cura-configuration

## Help
Please note that support is only available for X40 community members. Questions on github will therefore not be answered.
You can join the X40 community at: http://www.x40-community.org/index.php/members-area

A Cura crash does not necessarily mean that the configuration is defective. Normally, the user is just too dumb to do so because not everything has been taken into account!

## Supported Cura Version 
- Ultimaker Cura 4.13
- Ultimaker Cura 5.0.0
- Ultimaker Cura 5.1.0
- Ultimaker Cura 5.2.0
- Ultimaker Cura 5.3.0

The Configuration doesn't work together with Weedo Cura! 

## Supported Hardware Version 
- X40 V1: The first mass production version. The production time is from November 2020 to June 2021.
- X40 V2: The second production version. The production batch start from July 2021.


## Information
Starting with the version for Cura 5.3, the configuration can be used with all Weedo X40 and Weedo X40 PRO Firmware variants. In the older versions, the configuration is matched to the X40 PRO firmware.

The Weedo X40 PRO Cura plugin only works with the latest X40 PRO firmware. **The plugin is not part of the configuration and is only available to X40 community members.**

More informations see http://www.x40-community.org/index.php/cura/cura-plugins/9-cura-workflow/84-cura-plugins-2

## Install
Download the Zip-file from the github server. The zip file for Cura 4.12 / 4.13 / 5.0.0 can only be used with Cura 4.12.X / 4.13.X / 5.0.0. So make sure you have the right version! Unzip the zip file and look for the resources directory.  

The configuration files, materials and printing profiles for the Weedo X40 can be found in the following subdirectories: 

    definitions
    extruders
    intent
    materials
    meshes
    quality
    variants

Now look for the resources directory on your PC from your Cura installation.

    Windows
    Cura 4.X (C:\Program\Ultimaker Cura 4.13\resources)
    Cura 5.X (C:\Program Files\Ultimaker Cura 5.0.0\share\cura\resources)

    Linux
    /usr/share/cura/resources
    or
    ~/.local/share/cura/4.13



    MacOS 
    (In Finder go to the application folder, find Cura 4.13, right click in the application, open show contents, contents, MacOS, resources)

 

Copy the complete content from the Zip-file into the resources directory of the Cura installation and restart Cura.
