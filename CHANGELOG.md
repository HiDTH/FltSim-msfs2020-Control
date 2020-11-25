# Changelog Ver 1.2.1

New 'Portrait' layout optimised for Android tablet devices (also works on IOS devices but has a few small formatting issues)

Extra instruments for Engine RPM% and Throttle %

Rudder Trim control added (but not tested) to trim out drift left or right


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
  
  

KNOWN ISSUES

Autopilot - Not all aircraft have autopilot (or all autopilot functions available).  Some Autopilot functions act differently in different aircraft - probably depending on how that actual Autopilot works. i.e. When you set the heading bug or altitude hold.  Speed Hold not tested

Lights - Some aircraft show lights as switched on whether they are or not

Automation - Certain functions still use keypresses and have no way of checking whether the item is active or not in FS (i.e. Active Pause, Camera Functions, Torch, ATC Window)

Fuel - Take care switching fuel tanks as some aircraft do not have the option for Fuel Selector to be set to 'Both' causing fuel to stop flowing and the engine to stop

Engine Instruments - Throttle, Mixture, Prop RPM and Engine RPM do not auto-update - pressing any of those buttons should refresh the displayed figures

Ice & Heat - Anti-Ice system works differently in different aircraft (i.e. in Daher TBM 930 it operates airframe and propeller de-ice but not Pitot heat (separate function) or Windshield - which does not have an allocated keyboard key either so must be done from within the cockpit)
 
Cameras - Cockpit camera movement and views sometimes cause the aircraft to bank unexpectedly when looking left or right rather than act as expected.  I have not been ale to pin down the exact circumstances under which it happens
 
 

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
