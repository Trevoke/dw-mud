# tintin++ client scripts for Discworld MUD with a Wyzzard player in mind


For the full experience you need festival-tts and mpg321 installed for text-to-speech support and mp3 file support.


# IN-MUD Setup
You need the following settings in your Discworld options.

* verbose combat
* brief money
* monitor on
* alias xp money brief;score brief
* alias quitt quit
* alias suu su
* alias afterinventory alias tintin-settings; xp

# What you need to do before this might work for you
**Please have a read of config.tin and change it accordingly.**

# WHAT THIS WILL DO FOR YOU

* When you join a group, the groupbar will be enabled automatically
* When someone joins, their name is added to the groupbar, their TPA and kills are monitored
* When someone leaves, their name is removed to the groupbar, their TPA/kills cleared
* When you type 'group status', it will populate the groupbar with the names it finds

# Additional commands provided by the client:

* groupbar on/off
* kills:	shows you the tracked kills
* gkills: shows the group the tracked kills (using gs for group say)
* ded:	shows the timers for special npcs
* gded:	shows the timers to the group (using gs again)

## Extra commands you should not need to use
* partyadd playername:	 adds a player to the groupbar and tracks their tpa and kills
* partyremove playername: remove a player from the groupbar

# Credits

Original work by Dextar d'Parranoid: http://code.google.com/p/dw-tt-script/
