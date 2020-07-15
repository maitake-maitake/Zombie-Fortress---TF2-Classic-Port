Description:

A port of the SourceMod plugin, Zombie Fortress, to Team Fortress 2 Classic.
The original plugin can be found here:
https://forums.alliedmods.net/showthread.php?t=131282
Please refer to that thread for more info and for server/console commands.

SERVER CRASHING BUG: If a player spawns with the Scorching perk, the server will crash.
Disable the Scorching perk if running Perks. To do this, type "sm_zf_perk_disable scorching"

This simply solves errors in the original code and fits it for TF2 classic. Any further work or new additions will probably need to be done by a more knowledgeable coder.

It is recommended to use a map created for this mode. These maps usually start with zf (i.e zf_asylum_b3).
I have compiled a list of maps for this mode that I have tested for compatibility with TF2 Classic:
https://pastebin.com/raw/vn6zBUk5

Requirements:

Use of this plugin in a server will require SourceMod:
https://www.sourcemod.net/

Check with the TF2 Classic Discord for info on running SourceMod in TF2C. I recommend Scag's tools:
https://github.com/Scags/TF2Classic-Tools


Installation:

In your server, drop zombiefortress_perk.smx or zombiefortress_vanilla.smx into tf2classic/addons/sourcemod/plugins/

Known Issues:
4 Team maps will most likely not work but are untested.
VIP maps are incompatible but it may be possible to code this in.
The Civilian class is broken and will not be able to move correctly. Please set "tf2c_allow_special_classes 0".
