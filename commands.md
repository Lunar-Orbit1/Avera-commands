# Commands
Last updated: 12/01/25
## System information
Prefix: `;` <br>
Cmd bar: `L`

## Permissions
**User (0)** <br>
Only a few basic commands such as ;report. These are normal players <br>
**VIP (1)** <br>
They can run basic, server specific commands such as ;servermute <br>
**Moderator (2)** <br>
Allowed to run global commands such as ;ban<br>
**Admin (3)** <br>
Can promote lower ranked members and has access to high-impact commands like ;shutdown<br>
**Developer (4)** <br>
High power commands and data editor access<br>
**Owner (5)** <br>
Can promote or demote developers. Overrules all lower ranks <br>

## Commands
Press `control+F` (`command+F` if MacOS) to search for a specific command<br>
Commands are formatted like so: name {arguments:type}. For example, to run `unservermute` you would type this in chat or the command bar: `;unservermute Claym1x`, or to mute someone for two minutes with the reason "spam" you would type `;servermute clay 2 spam`

## Utility 
**cmds** <br>
Pulls up a list of all of the commands you have permissions to run (USER) <br> <br>
**report** <br>
Opens up a menu where you can report users to moderators (USER) <br> <br>
**notify {player} {message}** <br>
Sends a notification to the user's center screen (VIP) <br> <br>
**systemmessage {player} {message}** <br>
Sends a notification in the user's chat (VIP) <br> <br>
**scroll {player} {message}** <br>
Sends a notification to the bottom right of the user's screen (VIP) <br> <br>
**god/ungod {player}** <br>
Makes a player immune to damage (VIP) <br> <br>
**kill {player}** <br>
Kills a player (VIP) <br> <br>
**respawn {player} {keeptools:boolean}** <br>
Respawns a player right where they are. If keeptools == true, they will recieve their tools back <br> <br>
**noclip/clip {player}** <br>
Lets you fly through walls (ALIAS: fly/unfly) (VIP)<br> <br>
**teleport {player}** <br>
Teleports you to a player (VIP)<br> <br>
**bring {player}** <br>
Teleports a player to you (VIP)<br> <br>
**give {player}** <br>
Gives a tool to a player (VIP)<br> <br>
**forceuniform {player} {uniform_type:int}** <br>
Forces the player to wear a uniform. Type is a number but is optional (VIP)<br> <br>
**forceremoveuniform {player}** <br>
Resets a player's avatar (VIP)<br> <br>

## Moderation
**servermute {player} {duration:minutes} {reason}** <br>
Mutes a player in the server (VIP) <br> <br>
**unservermute {player:full username}** <br> 
Removes a server mute (VIP) <br> <br>
**chatlogs** <br>
Opens a log of every message sent in the past amount of time (Mod) <br> <br>
**cmdlogs** <br>
Opens a log of every command ran in the past amount of time (Mod) <br> <br>
**joinlogs** <br>
Opens a log of every player join, leave, or AFK in the past amount of time (Mod) <br> <br>
**anticheatlogs** <br>
Opens a log of anti-exploit events in the past amount of time (Mod) <br> <br>
**kick {player} {reason}** <br>
Kicks a player from the server (Mod) <br> <br>
**serverban {player} {duration:minutes} {reason}** <br>
Prevents a player from rejoining the server. Use 0 for an indefinite server ban (Mod) <br> <br>
**unserverban {player:full username}** <br>
Allows a server-banned user to rejoin the server (Mod) <br> <br>
**ban {player} {duration:days} {reason}** <br>
Bans a player from the game (Mod) <br> <br>
**unban {player:full username}** <br>
Removes a gameban from a user (Mod) \*isn't finished <br> <br>
**servershutdown {reason}** <br>
Shutdown a server. (Admin) <br> <br>