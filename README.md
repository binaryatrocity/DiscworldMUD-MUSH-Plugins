# DiscworldMUD-MUSH-Plugins

## XPTimer.xml
This plugin displays the time since you last 'checked' various XP hotspots. Timers listed beneath the "Death" section have been counting since you saw an NPC death. Timers in the "Visit" section have been counting since GMCP data last showed that room (actually being in the room, WAMG, scrying etc).  This plugin relies on Quow's minimap plugin for data broadcasts, you can find it [here](http://quow.co.uk/minimap.php)
* 'dt' or 'deathtimers' will display the list of timers
* 'gsdt' will share the timers with your group
* 'dtreset <all/target>' will reset all timers or a specific spot
* 'dtdebug' enables debugging output. victim/killer and room vnums will be displayed. useful for adding new spots
* 'help deathtimer' will display this info in-client
  
## DeadLetter.xml
This plugin displays the full name and location of your dead letter target. Currently works for Difficult Customer, Distant Land, and Far Away letters.
* 'sl' or 'solveletter' will read the letter in your inventory and display additional information
  
## DeliverySolver.xml
This plugin provides hints on where to find items for the Ankh-Morpork Job Market item delivery missions. Currently only works for the Deliverer of Rare Items job-type.
* 'sj' or 'solvejob' will read the employment writ in your inventory and display additional information
