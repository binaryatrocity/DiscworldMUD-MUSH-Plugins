# DiscworldMUD MUSHClient Plugins
<br/>

## XPTimer.xml
This plugin displays the time since you last 'checked' various XP hotspots. Timers listed beneath the "Death" section have been counting since you saw an NPC death. Timers in the "Visit" section have been counting since GMCP data last showed that room (actually being in the room, WAMG, scrying etc).  This plugin relies on Quow's minimap plugin for data broadcasts, you can find it [here](http://quow.co.uk/minimap.php).
* 'dt' or 'deathtimers' will display the list of timers
* 'gsdt' will share the timers with your group
* 'dtreset <all/target>' will reset all timers or a specific spot. 'all' marks everything Unseen, 'target' sets zero, like you just killed/visited the spot.
* 'dtdebug' toggles debugging output. victim/killer and room vnums will be displayed. useful for adding new spots. 
* 'dtwindow' toggles a mini-window displaying timer info, can click and drag to move it. **\*\*experimental\*\***
* 'help deathtimer' will display this info in-client
  
## DeadLetter.xml
This plugin displays the full name and location of your dead letter target. Currently works for Difficult Customer, Distant Land, and Far Away letters.
* 'sl' or 'solveletter' will read the letter in your inventory and display additional information
  
## DeliverySolver.xml
This plugin provides hints on where to find items for the Ankh-Morpork Job Market item delivery missions. Currently only works for the Deliverer of Rare Items job-type.
* 'sj' or 'solvejob' will read the employment writ in your inventory and display additional information

## AlignWindow.xml
This was written for a specific character and so requires a few things:
* Battle Monitor `Hp: ##(##) Gp: ##(##) Xp: ######## Burden: ##% Align: # #`
* Prompt: `<<< $align$ >>>$newline$`

If your battle monitor and/or prompt match the above strings, this will show your most recently displayed alignment in a miniwindow that you can click+drag to move. 
* 'alignwindow' command will toggle the window on and off
* If your prompt matches the above, it will be gagged from MUD output

<br/>

###### Written by Ruhsbaar of the Venerable Council of Seers
