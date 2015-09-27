### [CS:GO] Player Trails (v1.0.1 2015-09-27)
<a href="http://www.maxximou5.com/"><img src="http://maxximou5.com/sourcemod/assests/img/playertrails_csgo.png" alt="csgo player trails plugin" width="600" /></a>
===============

Enables player colored trails.

### Main Features

- Trail Beam Options:
 - Duration of trail
 - Width of trail
 - Fade duration of trail
 - End width of trail
 - Command usage per round
- Trail Color Options:
 - Red
 - Orange
 - Yellow
 - Green
 - Blue
 - Purple
 - Pink
 - Cyan
 - White
 - None
- Admin Only

### Features to Add

- Beam Starts Again (Without TIMER_REPEAT)

### Commands

- sm_trail <color> [red, orange, yellow, green, blue, purple, pink, cyan, white, none]
- sm_trails <color> [red, orange, yellow, green, blue, purple, pink, cyan, white, none]

### ConVars

- sm_trail_enable (Default) 1 - Enable or Disable all features of the plugin.
- sm_trail_adminonly (Default) 0 - Enable trails only for Admins (VOTE Flag).
- sm_trail_duration (Default)  5 - Duration of the trail.
- sm_trail_end_width (Default) 1 - Width of the trail.
- sm_trail_fade_duration (Default) 3 - Duration of the trail.
- sm_trail_per_round (Default) 5 - How many times per round a client can use the command.
- sm_trail_width (Default) 5 - Width of the trail.
- sm_playertrails_version (Default) 1 - Gives clients a colored trail when moving.

### Compatibility

This plugin is tested on the following Sourcemod & Metamod Versions.

- <a href="http://www.sourcemod.net/snapshots.php">Sourcemod 1.7.3+</a>
- <a href="http://www.sourcemm.net/snapshots">Metamod 1.10.4+</a>

Auto-Update Support requires <a href="https://forums.alliedmods.net/showthread.php?t=169095">updater</a> to be installed.

### Instructions

- Extract zip file and place files in the corresponding directories of **/addons/sourcemod**
- /plugins/playertrails.smx
- /scripting/deathmatch.sp (necessary only for compiling)
- /scripting/include/csgocolors.inc (necessary only for compiling)
- /scripting/include/updater.inc (necessary only for updater)

### Changelog

To view the most recent changelog visit the <a href="https://github.com/Maxximou5/csgo-playertrails/blob/master/CHANGELOG.md">changelog</a> file.

### Download

Once installed, the plugin will update itself as long as you've done as described in the requirements section; otherwise, downloaded the latest release below.
Please download the latest **playertrails.zip** file from <a href="https://github.com/Maxximou5/csgo-playertrails/releases">my releases</a>.

### Bugs

If there are any bugs, please report them using the <a href="https://github.com/Maxximou5/csgo-playertrails/issues">issues page</a>.

### Credit

A thank you to those who helped:

- <a href="https://forums.alliedmods.net/member.php?u=249285">ESK0</a> (TE_SetupBeamFollow)

### Donate

If you think I am doing a good job or you want to buy me a beer or feed my cat, please donate.
Thanks!

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=VSHQ7J8HR95SG"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" alt="csgo player trails plugin"/></a>
