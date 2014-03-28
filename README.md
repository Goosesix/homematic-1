Homematic Scripts
-----------------

The following are scripts I use in conjunction with my Homematic installation. I do tend not to use additional modules / software on my systems, so things should work without additions.


Router Presence Script (presencedetection.sh)
------------------------

This script runs on my router ( a fritz!box , but should work on any unix ).  The script set or unsets the variables on a CCU2 when a users presence is detected. You can add devices by their IP Address or Ethernet address or even IP ranges for detection of guests for example.


TurnHeatingOn (homematic script)
-----------------------
This script iterates through all heating thermostats and turns the main switch for the heating system on depening on the actual and set temperatures as well as valve states of the thermostats.




