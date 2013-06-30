#tintin++ client scripts for Discworld MUD with a wizzard player in mind


For the full experience you need festival-tts and mpg321 installed for text-to-speech support and mp3 file support.


# IN-MUD Setup
You need the following settings in your Discworld options.

* verbose combat;
* brief money;
* monitor on;
* alias xp money brief;score brief
* alias quitt quit;
* alias suu su;
* alias afterinventory alias tintin-settings; xp

Additional commands provided by the client:

* groupbar on/off
* partyadd playername:	 adds a player to the groupbar and tracks their tpa and kills
* kills:	shows you the tracked kills
* gkills: shows the group the tracked kills (using gs for group say)
* ded:	shows the timers for special npcs
* gded:	shows the timers to the group (using gs again)

**Please have a read of config.tin and change it accordingly.**

Original work by Dextar d'Parranoid: http://code.google.com/p/dw-tt-script/

# TODO
* use 'group status brief' to update group
* use 'group shields' to update group
* use messages for people joining and leaving groups to update party line
* Elfindrol's comment on TPA counting
* Elfindrol's comment on CCC counting
* Elfindrol' comment on XP counting
* Figure out something to do when checking components left
* Use #GREP to see how many times group members dropped TPA ?
* Rewrite groupbar display with FOREACH / WHILE ?
