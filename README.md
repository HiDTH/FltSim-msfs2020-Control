# FltSim-Control for MSFS2020 Readme file
Control Microsoft Flight Simulator 2020 cockpit buttons and functions from a mobile device or tablet using Touch Portal

# Includes the ability to:
Increase/decrease and view the current Simulation Rate  
View True, Indicated or Mach Airspeed and Speed over the Ground  
View current Altitude AGL  
Set Autopilot to Heading, Altitude, Vertical Speed and Speed in Kts in supported aircraft   
Switch on and off multiple lights includine Navigation, Taxi, Landing, Logo, Panel and Cabin lights    
Refuel and set Left, Right or Both fuel tanks  
Set COM and NAV radios  
Change and view the current simulation rate (speed up or slow down time)  
Easily move the direction and location of cockpit cameras    
Set the Parking Brake on or off and view it's current status  
Extend or Retract Landing Gear and see it's status  

# New addition:
Launch Control - Make those short runways a breeze at the touch of a button

# Requirements:
Full version of Touch Portal running on the same PC as Microsoft Flight Simulator 2020  
v0.60 or later of the MSFS Touch Portal Plugin from https://github.com/Touch-Portal-MSFS/MSFSTouchPortalPlugin/releases the files can be found by clicking on 'assets' at the bottom of the first batch of text on the releases page  

# To install FltSim-Control for MSFS2020:
1. Delete any existing version of the page from within Touch Portal (if you have setup additional custom buttons they can be exported through Touch Portal)  
2. Download the latest version of FltSim-Control zip file from releases   
3. Unzip the file, select 'import page' from Touch Portal and navigate to and select either 'FltSim Control-Portrait.tpz' OR 'FltSim Control-Landscape.tpz' from your download folder location   

# To install MSFS Touch Portal Plugin:
1. Delete any existing copy of the Plugin from Settings from within Touch Portal  
2. Download the latest version of the Plugin from https://github.com/Touch-Portal-MSFS/MSFSTouchPortalPlugin/releases the files can be found by clicking on 'assets' at the bottom of the first batch of text on the releases page  
3. Select 'import plugin' from the spanner icon at the top of the Touch Portal window and navigate to your downloads folder to import the file  
4. Having installed both the FltSim-msfs2020-Control page and the MSFS Plugin you now need to exit Touch Portal by right clicking on the Touch Portal icon from the Windows 10/11 system tray ^ on the right hand side of the task bar at the bottom of the windows 10/11 screen  
5. Now restart Touch Portal and you should be good to go  

# To install FltSim-msfs2020-Control with both Portrait and Landscape pages installed:
I sometimes run the page on my Galaxy Tab in Portrait mode, and other times on my iPad in Landscape mode, so I have both versions installed.  
Firstly install the Portrait mode page into Touch Portal then delete all of the items in the 'VALUES' tab, next install the Landscape version of the page before restarting Touch Portal as above

# Notes
Please also reference the notes in Changelog.md

Tested and working well on both my iPad (IOS) and Samsung Galaxy Tab A10 (Android) - other devices may need the font sizes tweaking

Assumes default keyboard configuration and key assignments in Microsoft Flight Simulator 2020 with the additions detailed below if you need to use them:

# MSFS Keyboard Controls
For certain functions to work the following buttons need to be set in the <keyboard> controls section of <Controls Options Settings> in Flight Simulator

For Active Pause                        MSFS>Control Options>Keyboard>  Active Pause		=>	<Pause> 

To Swap COM1/COM2 as Active Com Radio   MSFS>Control Options>Keyboard>  COM1 Transmit		=>	<Shift><ALT>1 
                                        MSFS>Control Options>Keyboard>  COM2 Transmit		=>	<Shift><ALT>2 
                                        MSFS>Control Options>Keyboard>  COM1 Receive		=>	<Shift><ALT>5 
                                        MSFS>Control Options>Keyboard>  COM2 Receive		=>	<Shift><ALT>6

To set VOR OBS (NAV1)                   MSFS>Control Options>Keyboard>  Increase VOR2 OBS	=>	<Shift><ALT><Home> 
                                        MSFS>Control Options>Keyboard>  Decrease VOR2 OBS	=>	<Shift><ALT><End>

Tested using a range of mainly single engine aircraft although nearly all functions also work with multiple engines.  Not all aircraft support all functions i.e. some smaller aircraft are not equipped with autopilot or retractable undercarriage

Part of the Touch Portal MSFS2020 Discord community https://discord.gg/3FfDwdS with particular thanks to @Nickname_Pending for the plug-in, @arbi_ph for icons and graphics, and @FordMustang0288 for paving the way with his flight simulator Touch Portal pages
