# OpenAndOn
SmartThings App to notify if something is open when power to device is on.  

Allows users to select the power meter to use as well as multiple contact sensors.  If power passes a customizable threshold (default 100 watts) and any selected contact is open, an alert or optional text is sent.  If a contact sensor is opened for more than a customized time delay (default 1 minute) after power is flowing, an alert/text is also sent.

The alert/text will contain the names of all open contacts.

I designed this app in particular to overcome the current limitation of the Honeywell Lyric smart thermostat, which does not have a public API and does not integrate with SmartThings.  As a workaround, I connected my furnace/blower to a smart outlet to register when the power draw increased.  Now I get an alert when the AC/Heat comes on and windows are open.
