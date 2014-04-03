AntennaTracker
==============

Auto-tracking antenna groundstation SW for balloon flights

Built with labview 8.2.1; open the .lvproj file, update any path conflicts as needed (newer versions of LV should do this automatically) then open the Control Panel.vi instrument to run.  Expects a Pololu servo driver, a NMEA GPS target (the balloon), and an OceanServer tilt/compass sensor.  Configure each item's serial port id on the respective tabs, start the parsing engine, and engage auto or manual drive mode as desired.
