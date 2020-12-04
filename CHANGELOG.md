# Changelog Ver 1.2.1

New 'Portrait' and 'Landscape' layouts optimised for Android tablets (also works on iPads) - only download either portrait or landscape.   If you need both there are instructions in the README.MD file

New Font Size button for higher resolution screens - adjusts the font size on a number of buttons and panel labels

Extra instruments in portrait layout for Engine RPM% and Throttle %

Rudder Trim control added in portrait mode to trim out drift left or right

Various bugs fixed

# To install FltSim-msfs2020-Control:
1. Delete any existing version of the page from within Touch Portal
2. Download the latest version of FltSim-msfs2020-Control zip file from releases
3. Unzip the file, select 'import page' from Touch Portal and navigate to and select either 'FltSim 2020 Control-Portrait.tpz' OR 'FltSim 2020 Control-Landscape.tpz' from your download folder location

# To install MSFS Touch Portal Plugin:
1. Delete any existing copy of the Plugin from Settings from within Touch Portal
2. Download the latest version of the Plugin from https://github.com/Touch-Portal-MSFS/MSFSTouchPortalPlugin/releases the files can be found by clicking on 'assets' at the bottom of the first batch of text on the releases page
3. Select 'import plugin' from the spanner icon at the top of the Touch Portal window and navigate to your downloads folder to import the file
4. Having installed both the FltSim-msfs2020-Control page and the MSFS Plugin you now need to exit Touch Portal by right clicking on the Touch Portal icon from the Windows 10 system tray ^ on the right hand side of the task bar at the bottom of the windows 10 screen
5. Now restart Touch Portal and you should be good to go

# To install FltSim-msfs2020-Control with both Portrait and Landscape pages installed:
I sometimes run the page on my Galaxy Tab in Portrait mode, and other times on my iPad in Landscape mode, so I have both versions installed.
Firstly install the Portrait mode page into Touch Portal then delete all of the 'Global Objects - States' or custom states that start with 'fsc.', next install the Landscape version of the page before restarting Touch Portal as above

# Notes
Tested and working well on both my iPad (IOS) and Samsung Galaxy Tab A10 (Android) - other devices may need the font sizes tweaking

Assumes default keyboard configuration and key assignments in Microsoft Flight Simulator 2020

Tested using single engine aircraft although nearly all functions should also work with multiple engines. Not all aircraft support all functions i.e. some smaller aircraft are not equipped with autopilot or retractable undercarriage

# KNOWN ISSUES

Autopilot - Not all aircraft have autopilot (or all autopilot functions available).  Some Autopilot functions act differently in different aircraft - probably depending on how that actual Autopilot works. i.e. When you set the heading bug or altitude hold.  Speed Hold not tested

Lights - Some aircraft show lights as switched on whether they are or not

Automation - Certain functions still use keypresses and have no way of checking whether the item is active or not in FS (i.e. Active Pause, Camera Functions, Torch, ATC Window)

Fuel - Take care switching fuel tanks as some aircraft do not have the option for Fuel Selector to be set to 'Both' causing fuel to stop flowing and the engine to stop

Engine Instruments - Throttle, Mixture, Prop RPM and Engine RPM do not auto-update - pressing any of those buttons should refresh the displayed figures

Ice & Heat - Anti-Ice system works differently in different aircraft (i.e. in Daher TBM 930 it operates airframe and propeller de-ice but not Pitot heat (separate function) or Windshield - which does not have an allocated keyboard key either so must be done from within the cockpit)
 
Cameras - Cockpit camera movement and views sometimes cause the aircraft to bank unexpectedly when looking left or right rather than act as expected.  I have not been ale to pin down the exact circumstances under which it happens


Part of the Touch Portal MSFS2020 Discord community https://discord.gg/3FfDwdS with particular thanks to @Nickname_Pending for the plug-in, @arbi_ph for icons and graphics, and @FordMustang0288 for paving the way with his flight simulator Touch Portal pages


# Changelog Ver 1.2

More buttons now working through the plug-in rather than using keypresses

Panel for Cockpit Camera Controls added so that the view can easily be moved or switched in the cockpit - uses keypresses as not supported by plugin yet

Panel for Heat & Ice added for flying in icing conditions - some functions use keypresses (Cowl Flap)

Propeller Pitch/RPM added for aircraft with variable pitch props - uses keypresses as not supported by plugin yet

Checks to prevent inadvertantly switching off the battery, alternator or engine unless parking brake is set

Parking Brake cannot be inadvertantly put on whilst in the air

Confirmation checks for setting mixture to lean, dumping fuel, or shutting off the fuel selector or fuel valve

Coarse and Fine adjustments for Autopilot Altitude, Heading, Airspeed and Vertical Speed settings

ATC Panel Button opens ATC window in MSFS (assuming it starts closed) other panel buttons close it again  - uses keypresses as not supported by plugin yet

Tested primarily with Cessna 172 Skyhawk (G1000) with some testing on XCub and Daher TBM 930

 

# Changelog Ver 1.1

Updated to MSFS Touch Portal Plugin v0.52

Improved display graphics.

Added displays on top line for Airspeed & Vertical Speed

Added display for Com1 & Nav1 Radios and Alerts

Added panel names

Added additional light switches

Added panels for Radios, ATC, Engine & Fuel. Panels changes use Touch Portal Custom States in order to keep everything on one page

Added Active Pause switch

Added Vertical Trim position indicator
