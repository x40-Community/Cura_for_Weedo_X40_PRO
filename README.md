# Ultimaker Cura Configuration for WEEDO X40 PRO
![image](http://www.x40-community.org/images/x40/Cura_Aqua_Theme.jpg)

## Weedo X40 PRO
X40 PRO is an improvement for the Weedo X40V1 and Weedo X40V2 printer. It eliminates the printer weaknesses from the cooling system, bugs in the firmware, extends the functionality of the firmware and adapts the printer to the Ultimaker Cura in order to be able to use the printer fully.

Project flyer (PDF) https://my.hidrive.com/lnk/M4UNmCwu

More information see http://www.x40-community.org/index.php/firmware/x40-pro-system



## Ready to use
The X40 Community Cura configuration is much more than just a printer definition. It contains a printer visualization and hundreds of tested print profiles. Simply select a supported filament, make small adjustments such as support structure etc. and just print. There is no need to search for and test the correct print parameters. 

Here you can see the supported filament and the current status: Cura Quality and Intent Profiles

There are two Ultimaker Cura configurations for the Weedo X40 printer:

Standard configuration for Weedo X40 or other Firmware
- Available for Cura 4.X and 5.X
- Full Idex printing support (Single LH, Single RH, dual mode normal, dual mode mirrored, copy mode) up start script Rev. 11
- The configuration contains about 3000 print profiles.
- Supported nozzle size 0,4mm and 0,6mm (not for all printing profiles)
- The Cura plugin for embedding the printer preview image is not part of the configuration!

More Information see http://www.x40-community.org/index.php/cura/cura-configuration

## Help
Please note that support is only available for X40 community members. Questions on github will therefore not be answered.
You can join the X40 community at: http://www.x40-community.org/index.php/members-area

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
Starting with the version for Cura 5.3, the configuration can be used with all Weedo X40 and Weedo X40 PRO variants. In the older versions, the configuration is matched to the X40 PRO firmware.

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
