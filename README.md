
![Ajs/Ogar-Unlimited - Graphics by LegitSoulja](http://ogarul.tk/ajs.png)
### - The Next Generation Ogar
[![Build Status](https://travis-ci.org/AJS-development/Ogar-unlimited.svg?branch=master)](https://travis-ci.org/AJS-development/Ogar-unlimited) [![Join the chat at https://gitter.im/AJS-development/Ogar-unlimited](https://badges.gitter.im/AJS-development/Ogar-unlimited.svg)](https://gitter.im/AJS-development/Ogar-unlimited?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)  [![GitHub issues](https://img.shields.io/github/issues/AJS-development/Ogar-unlimited.svg)](https://github.com/AJS-development/Ogar-unlimited/issues)  [![GitHub forks](https://img.shields.io/github/forks/AJS-development/Ogar-unlimited.svg)](https://github.com/AJS-development/Ogar-unlimited/network)  [![GitHub stars](https://img.shields.io/github/stars/AJS-development/Ogar-unlimited.svg)](https://github.com/AJS-development/Ogar-unlimited/stargazers)  [![Plugin](https://img.shields.io/badge/Official%20Plugin%20Library-OgarUL--Plugin--Library-green.svg)](https://github.com/AJS-development/OgarUL-Plugin-Library)  [![MS](https://img.shields.io/badge/Client-AJS--dev-green.svg)](https://github.com/AJS-development/OgarUL-Client) [![Plugin](https://img.shields.io/badge/Forums-OgarUl-green.svg)](http://forum.ogarul.tk) [![Plugin](https://img.shields.io/badge/Stats-OgarUl-green.svg)](http://stats.ogarul.tk)  [![MS](https://img.shields.io/badge/Client-AJS--dev-green.svg)](http://play.ogarul.tk) 
[![Demo] (https://img.shields.io/badge/Demo-Heroku-green.svg)] (https://github.com/AJS-development/Ogar-unlimited/wiki/Demos)

A fully functional open source Agar.io server implementation, written in Node.js by AJS development team. Ogar Unlimited *(or in short, OgarUL)* is designed to be used with the latest Agar.io client and also our own official client, [**play.ogarul.tk**](http://play.ogarul.tk/). It is basically what it says in the title, Ogar, except its functionality is unlimited!

##Table of Contents
- [Installation Guide (short)](https://github.com/AJS-development/Ogar-unlimited#installation-guide-short)
- [Troubleshooting, FAQ and Tutorial](https://github.com/AJS-development/Ogar-unlimited#troubleshooting-faq-and-tutorial)
- [Highlight features](https://github.com/AJS-development/Ogar-unlimited#hightlight-features-in-ogar-unlimited)
- [Note](https://github.com/AJS-development/Ogar-unlimited#note)
 - [DO NOT BUY OGAR UL!](https://github.com/AJS-development/Ogar-unlimited#do-not-buy-ogar-ul)
 - [Do not get from other sources](https://github.com/AJS-development/Ogar-unlimited#do-not-get-from-other-sources)
- [Obtaining and Using](https://github.com/AJS-development/Ogar-unlimited#obtaining-and-using)
- [Configuring Ogar UL](https://github.com/AJS-development/Ogar-unlimited#configuring-ogar-ul)
- [Plugins](https://github.com/AJS-development/Ogar-unlimited#plugins)
 - [How can I get plugins? Is there any official library?](https://github.com/AJS-development/Ogar-unlimited#how-can-i-get-plugins-is-there-any-official-library)
 - [How do I use other plugins?](https://github.com/AJS-development/Ogar-unlimited#how-do-i-use-other-plugin)
 - [How do I create a plugin? Is there any documentation?](https://github.com/AJS-development/Ogar-unlimited#how-do-i-create-a-plugin-is-there-any-documentation)
- [Multiverse](https://github.com/AJS-development/Ogar-unlimited#multiverse)
- [Minions](https://github.com/AJS-development/Ogar-unlimited#minions)
- [Skin list and custom skins](https://github.com/AJS-development/Ogar-unlimited#skin-list-and-custom-skins)
- [OP features](https://github.com/AJS-development/Ogar-unlimited#op)
- [Easy Verify (anti bot measure)](https://github.com/AJS-development/Ogar-unlimited#easy-verify-anti-bot-measure)
- [Custom Game Modes](https://github.com/AJS-development/Ogar-unlimited#custom-game-modes)
- Commands
 - [Chat commands](https://github.com/AJS-development/Ogar-unlimited#chat-commands)
 - [Console commands](https://github.com/AJS-development/Ogar-unlimited#console-commands)
- [Contributing](https://github.com/AJS-development/Ogar-unlimited#contributing)
- [Things that I don't want you to copy](https://github.com/AJS-development/Ogar-unlimited#things-that-i-dont-want-you-to-copy-copying-it-to-your-own-file-or-fork)

###### Installation Guide (short)
1. Download and install Node
    * Required version [**v5.9.0**](https://nodejs.org/download/release/v5.9.0/)
2. Download Ogar Unlimited (Zip or Git)
    * [Download Latest Zip](https://github.com/AJS-development/Ogar-unlimited/archive/master.zip)
    * ``` git clone git@github.com:AJS-development/Ogar-unlimited.git ```
3. Once downloaded
    * Extract the zip folder into somewhere else. Then,
    * CD to the extracted zip folder, or clone to **Ogar-unlimited** folder.
4. Install Modules
    * While in system command line _(cmd or terminal)_, type: `npm install`, wait until done. Or,
    * Run Install Dependencies (Windows).bat file in the **src** folder. _(Windows only)_
5. Launch Ogar Unlimited
    * CD to the **src** folder inside **Ogar-unlimited** and run the start.bat/sh file or use command (**node index.js**). Or,
    * Just run **Start.bat** inside **src** folder _(Windows only)_
6. You're all done. Now, you can play it by go to [**play.ogarul.tk**](http://play.ogarul.tk/). Continue reading for more info

###### Troubleshooting, FAQ and Tutorial
- [Troubleshooting Guide](https://github.com/AJS-development/Ogar-unlimited/issues/1335)

- [FAQ](https://github.com/AJS-development/Ogar-unlimited/issues/1336)

- [How To Tutorial](https://github.com/AJS-development/Ogar-unlimited/issues/729)

### Highlight features in Ogar Unlimited
 1. More useful commands! *(eg. `pmsg`, `merge`, `freeze`; see [here](https://github.com/AJS-development/Ogar-unlimited#console-commands) for more info)*
 2. OP *(a.k.a OverPowered! Makes player OP, see [here](https://github.com/AJS-development/Ogar-unlimited#op) for more info)*
 3. More game modes! *(see [here](https://github.com/AJS-development/Ogar-unlimited#custom-game-modes) for more info)*
 4. Better physics *(ejected mass, split, autosplit, virus, etc; most of it are configurable, see "config.ini" or "advConfig.ini")* 
 5. Skins! *(see [here](https://github.com/AJS-development/Ogar-unlimited#skin-list-and-custom-skins) for more info)*
 6. Minions! *(see [here](https://github.com/AJS-development/Ogar-unlimited#minions) for more info)*
 7. Chat __*(play.ogarul.tk only)*__
 8. Plugins *(add gamemodes and commands easily! see [here](https://github.com/AJS-development/Ogar-unlimited/wiki/Plugin-API-Tutorial) for how to make your own plugin!)*
 9. Multi server support (see [multiverse](https://github.com/AJS-development/Ogar-unlimited#multiverse)) __*(play.ogarul.tk only)*__
 10. Teaming bots *(for testing purposes)*
 11. Chat commands __*(play.ogarul.tk only)*__
 12. "Opbyip" *(Makes player always OP using player's IP)*
 13. Tutorials *(runs only once in console)*
 14. Database free high score keeper
 15. Customizable console output color and style *(by using colortext command)*
 16. Live console *(see "advConfig.ini", where a live console appears) __NOTE: This is way different that Ogarserv's Console__*
 17. Ban, Unban, Ban List and Autoban option *(with revolutionary ban technique, no lag, no DDoS attacks)(see "advConfig.ini")*
 18. Uniban *(a pre-made banlist of already known bad IPs)*
 19. Easy verify system *(anti bot measure, see "advconfig.ini")*
 20. Mousefilter *(anti bot measure, see "advconfig.ini")*
 21. Client's configuration *(see "clientConfig.ini")* __*(play.ogarul.tk only)*__
 22. Quadrants *(improve performance and reduce lag)*
 23. Garbage collection *(prevent memory leaks)*
 24. Language support *(currently English and Spanish, we might need more language)*

### Note:
Please note that this is updated very frequently and you should check for updates every week. I added an update system but It needs to be initialized by you (because I don't think it is the right thing to do, updating without your consent). Also you may copy this and modify it just please give some credit to the hard working dev team, that is all I care. Another note is that I am sometimes terrible in my grammar (I still cannot spell potato out loud). If there is an issue, please notify me. If there is something you want in this, just make a pull request.

### DO NOT BUY OGAR UL!
If you've purchased a copy of Ogar UL, **you've just been scammed**! Ogar UL is an open source project, which means it is **FREE**. Yes, **FREE!** So if you paid any money for it, well, too bad.

### Do not get Ogar UL from other sources
If you got OgarUL from anywhere besides github, **YOU SHOULD DELETE IT IMMEDIATLY!!!** Those might be bundled with **viruses and other things**. Remember, you are running this probably from `sudo`. **Get it from github only!**: https://github.com/AJS-development/Ogar-unlimited

### Obtaining and Using
As Ogar Unlimited is written in Node.js, you must have Node.js and its modules installed to use it. You can usually download Node using your distribution's package manager _(for *nix-like systems)_, or from the [**Node website**](http://nodejs.org) *(use version 5.9.0)*. To install the modules that is required, open up your system command line *(cmd for windows, terminal for mac)*, and simply type "**npm install**". If you are on windows, you could simply double click the `Install Dependencies (Windows).bat`. To see a detailed guide, go to the [Installation guide](https://github.com/AJS-development/Ogar-unlimited/wiki/Installation) in the wiki.

Currently, OgarUL listens on the following addresses and ports *(by default)*:
* *:88 - for the stats server
* *:443 - for the "Main" game server

To start the game, simply double click the `Start.bat` or run "index.js" by typing `node index.js` in the console. Please note that on some systems, you may have to run the process as root or otherwise elevate your privileges to allow the process to listen on the needed ports.
Once the game server is running, you can connect *(locally)* by typing `play.ogarul.tk/?ip=127.0.0.1:443` into your browser's address bar.

If you want to use agar.io site as your client, use [OgarUL-NoClient](https://github.com/AJS-development/Ogar-unlimited-Noclient) instead. The instruction would be the same as above, except that you need to use `agar.io/?ip=127.0.0.1:443` to play *(locally)*.

 **If you are getting an _EADDRINUSE_ error, it means that the port required to run Ogar UL is being used. Usually, Skype is the culprit. To solve this, either close out skype, or change the serverPort value in settings/advconfig.ini to a different port. You will have to change your IP connection to "127.0.0.1:PORT"**

### Configuring Ogar UL
To control how your server is running, you can edit your settings to your own liking in `src/settings/`. If you don't want your config gets overwritten by the updates, you can copy the configs you want and paste it into `override.ini` *(where the configs come from doesn't matter, either from "config.ini", "advConfig.ini" or "clientConfig.ini")*

### Plugins
#### How can I get plugins? Is there any official library?
Yes, we have our own official library. It's only right here: [**https://github.com/AJS-development/OgarUL-Plugin-Library**](https://github.com/AJS-development/OgarUL-Plugin-Library)

To install any plugins from the library, first do `plugin search [name_of_plugin]`, copy the "exact" plugin name that you get and then do `plugin install [plugin_name]`. *(NOTE: The plugin names are __case sensitive__)*

#### How do I use other plugins?
To use a plugin, simply download the folder and drag it into the "**plugins**" folder under "**src**" folder or use the `plugin add` command. To use the plugin add command, the plugin must have a "**files.txt**" file. Then click on that file, click raw, and then copy the URL. Then do `plugin add [url] [pluginname]` and it will reload automatically for you. Thats it! Example, doing `plugin add https://raw.githubusercontent.com/AJS-development/OgarUL-Plugin-Library/master/devtools-plugin/files.txt devtools` will add a plugin called "devtools" to your plugins.

#### How do I create a plugin? Is there any documentation?
This is the fun part, creating your own plugins. There is an example plugin you should look at and there is a template plugin. You can look at [plugin API documentation](https://github.com/AJS-development/Ogar-unlimited/wiki/Plugin-API-Tutorial) for more detail.

### Multiverse
Multiverse is for having multiple servers in one console. The command for multiverse is `multiverse [command] [arg]`. Available commands are:
- `multiverse create [name] [port] [gamemode] [title(optional)]` - Creates a server *(the title arg is optional and spaces are allowed, which is to display it in the client aka play.ogarul.tk. Note that only the main server has a statsport and sends multiverse data)*
- `multiverse list` - Listing all servers and their ports *(also tells which server is a main server)*
- `multiverse remove [name]` - Removes a server
- `multiverse select [name]` - Selects which server that you want to control

### Minions
In order to use minions, you can spawn them by typing `minion [yourid] [amount] [minionname]` in console. The way that client controls the minion between agar.io and play.ogarul.tk are different. To control your minions:

#### play.ogarul.tk
Input | Description
----|----
E | Splits the minion
R | Makes minion to eject some mass
T | Freezes the minion

#### agar.io *(change `useER = 0` in config.ini)*
Input | Description
----|----
Q | Toggles control mode between you and your minion *(a letter "B" will appear next to your name, indicates that you are in "minion" control mode)*
Space | Splits the minion *(while in "minion" mode)*
W | Makes minion to eject some mass *(while in "minion" mode)*
You can disable minions by typing `minion [id]` in console, or do `minion destroy` and it will remove all minions in your server.

### Skin list and custom skins
**Play.ogarul.tk**
- To see the default skins list, click "*Want skin list?*" located at the bottom left corner. Then, you can choose the skin that you wanted. After that, type your name next to the `<skinname>`. *(eg: `<nuclear>Bomb` would give you a "nuclear" skin with the name of "Bomb")*

**Agar.io**
- To use agar.io skins, type `<skinname>` and then type your name. For example `<spy>lol` will give you "spy" skin with name of "lol". You can also use a custom skin from a website by typing `[website_url]name` *(without typing `http://` or `https://`, you need to use a url shortener though)*

You can use custom skins by putting them in customskins.txt. The format should be `[skin_shorcut] :http//image_url` for using skin image from URL, or use `[skin_shortcut] :%skinname` for using agar.io skin instead. To use URL skin, use `:http//url_image`. **NOTE: Use only "http"(not "https"). Also, don't forget to put `:` before "http")**
You can see more detailed guide on the [wiki](https://github.com/AJS-development/Ogar-unlimited/wiki/Skins-and-skin-shortcuts)

### OP
OP is used for having fun in your server like trolling, increases your mass, shoots virus, etc. You can make yourself OP by typing `op [yourid]` in console. To toggle between modes, you need to press "Q" in order to use OP's features. Then, a "C" will appears next to your name. If you press "Q" again, it will add another "C" until you have 4 "C"'s. If you press Q once again, it will go back to normal state. What these does is:

C's(in order) | When pressing "W"       | When pressing "Space"
--------------|-------------------------|---------------------
**C**         | Gives you 100 more mass | Able to merge instantly *(for short of time)*
**CC**        | Shoots virus            | Shoots tiny "things" *(almost invisible)* that if someone eats it, their mass reduced by 100
**CCC**       | Shoots "troll" virus    | Shoots "exploding" virus
**CCCC**      | Shoots "one-hit-kill" virus | Shoots "kick" virus
**No C's**    | Normal feed             | Normal split

__NOTE: Names *(CC's)* don't work when player's name is blank and it doesn't work on Leap gamemodes and/or while using minions. Also, you can configure this in config.ini__

### Easy Verify (anti bot measure)
For those of you who have trouble with minions and such, this feature is for you. Currently, there is no program that can get through all of Ogar Unlimited's filters and features. But in some future, someone might be able to crack the other anti bot measures. So we created an easy verify system, a currently foolproof system that filters out the bots. To turn on, turn `verify` to 1 in "advConfig.ini". Then when a player spawns, he is frozen at a spot and is given a 3 digit code. Then that player presses "W" to kill himself and types in the code in the nickname box. Afterwards, when pressing "Play" again, it shows a success message. Press "W" again to play.

## Custom Game Modes
Ogar UL has support for custom game modes. To switch between game modes, change the value of "serverGamemode" in the configurations file to the selected game mode id and restart the server. The current supported game modes are:

Id   | Name                         | Additional Description
-----|------------------------------|-----------------------
0    | Free For All                 | Everyone on there own
1    | Teams                        | Team and be the best
2    | Experimental                 | Something cool
3    | Timed FFA                    | Normal FFA but with time limit *(see "config.ini" for time configuration)*
4    | Virus Off                    | No virus in the map
5    | Unlimited PVP                | Where you can split indefinitely and rejoin instantly - 1v1 game *(created by me)*
6    | Unlimited FFA                | Same as above *(Unlimited PVP)* except in FFA *(created by me)*
7    | Shrinking FFA                | Shrinks the game *(map size)* as time passes
8    | Experimental v2              | An improved Experimental mode
9    | Anonymous FFA                | Everytime you spawn, your name would be random *(anonymously)*
10   | Tournament                   | Normal FFA, but with no respawn and time limit
11   | Hunger Games                 | Adapted from a movie called *"The Hunger Games"*
12   | Zombie Mode                  | Infection-like mode
14   | Team Experimental            | Teaming in Experimental
15   | NoCollision Teams            | Same as Teams mode but no collision between teammates
17   | NoCollision TeamX            | Same as Team Experimental mode but no collision between teammates
18   | Leap                         | Where you leap instead of split *(made by Ogarplus)*
20   | Rainbow FFA                  | Where every entity gets rainbow effect. Hint: Use *"Acid Mode"* in the custom client's settings
22   | BlackHole                    | Normal FFA but with one big black hole at the middle of the map.

## Chat Commands
The available in-game chat commands.

 Command                      | Usage
------------------------------|-----------------------------------------------------------------------------------------------
help                          | Shows list of commands
color [r] [b] [g]             | Changes the color of your chatname
mute                          | Mutes/unmutes chat
pm [chatname] [msg]           | Sends a private message

## Console Commands
The current available console commands are listed here. Command names are not case sensitive, but player names are.

 Command                      | Usage
------------------------------|-----------------------------------------------------------------------------------------------
help                          | Shows list of commands
ophelp                        | Shows how to use op
addbot [number]               | Adds [number] of bots to the server. If an amount is not specified, 1 bot will be added.
announce                      | Starts the high score announce feature.
ban [ip]                      | Bans an IP and sends a Message. Do (**ban record**) to record a ban.
banlist                       | Lists banned IP's
clearban                      | Clears ban list
unban [ip]                    | Unbans an IP
blind [id]                    | Blinds/Unblind a player *(player can't see other players)*
board [String 1] [String 2] ...| Replaces the text on the leaderboard with the string text.
boardreset                    | Resets the leaderboard to display the proper data for the current gamemode
change [config setting] [value]| Changes a config setting to a value. _(Usage: **change serverMaxConnections 32**)_.Note that some config values *(like serverGamemode)* are parsed before the server starts so changing them mid game will have no effect.
changelog [page]              | Changelog of the latest update. The arg **[page]** is a number of page.
chat [command] [args]         | Chat from console. (**all**, **pm**) _(Usage: **chat all [msg]**)_
chatban [id]                  | Ban people user id from chatting
clear                         | Clears the console output
color [id] [r] [g] [b]        | Replaces the color of the specified player with this color.
colortext [color]             | Changes console color and style. *(blue, green, red, yellow, bold, reset, dim, white, help)*
enlarge [amount]              | Enlarge the game place space. _Amount is optional_
exit                          | Closes the server
explode [id]                  | Explodes a player
fmsg [message 1] [message 2] [etc...] | Force players to read a message. Changes leaderboard, freeze players, and change their name temporarily.
food [x pos] [y pos] [mass]   | Spawns a food cell at those coordinates. If a mass value is not specified, then the server will default to *"foodStartMass"* in the config.
freeze [id]                   | Freezes a player
gamemode [id]                 | Changes the gamemode of the server. **Warning. _This can cause problems!._**
hide [id]                     | Hide/Unhide a player *(will not seen by other players)*
kickrange/killrange/banrange [start] [end] | Kicks/kills/bans in a range _(eg: "**killrange 1 10**" will kill players whos ids are between them)_
kick [id]                     | Kicks a specific player or bot from the server
kickbots [number]             | Kick a specific number of bots. *(leave blank to kick all)*
kill [id]/killall             | Kills all cells belonging to a specific player. Do **killall** to kill all players.
mass [id] [mass]              | Sets the mass of all cells belonging to a specified player
merge [id]                    | Forces a player to merge
minion [id] [amount] [name]   | Create minions. To turn off, do **minion [id]**. To destroy, do **minion destroy**.
msg [message1] [message2] [etc...] | Changes the leaderboard to a message for a short time
multiverse [command] [args]   | Manage multiple servers in 1 console. *(see [here](https://github.com/AJS-development/Ogar-unlimited#multiverse) for more info)*
name [id] [new name]          | Changes the name of the player with the specified id with **[new name]**. Skin name can be added aswell. _(Usage: **name 1 <kraken>Kraken**)_
nojoin [id]                   | Makes a player unable to join
op [id]                       | Makes a player OP
dop [id]                      | De-OP's a player
rop                           | Resets player's OP
opbyip [command] [ip]         | OP based on ip. Available commands are: **add, remove, list, clear, record**.
pause                         | Pauses/Unpauses the game
pcmd [delay] [repeattime] [command] [flag] | Periodic commands _(where **[flag]** is a command's arg)_
pfmsg [delay] [duration] [x to repeat] [msg1] [msg2] [etc...] | Periodically sends a force message *(in seconds)*
spfmsg                        | Stops pfmsg
playerlist                    | Shows a list of connected players, their IP, player ID, the amount of cells they have, total mass, and their position.
plugin [command] [name]       | Manage plugins. (Usage: **reload, list, delete, add, install, update, search**)
pmsg [delay] [duration] [x to repeat] [msg1] [msg2] [etc...] | Periodically sends a message *(in seconds)*
spmsg                         | Stops pmsg
quickrestart                  | Quickly restart your server. *(does not restart, nor reduce memory)*
rainbow [id]                  | Gives a player a rainbow effect
range [start] [end] [command] [flag] | Bulk commands, where **[flag]** is a command's arg. _(Usage: **range 1 10 freeze**)_ freezes players 1-10*(id)*
reload                        | Reloads the config file used by the server. However, some configs are not affected. *(eg: serverPort, serverGamemode, serverBots, serverStatsPort, serverStatsUpdate, etc.)*
reset                         | Destroys everything and start from scratch.
resetvirus                    | Turns specials viruses *(from OP's)* into normal ones.
restart [minutes]             | Restarts the server after a specific amount of minutes. *(leave blank for instant restart)*
shrink [amount]               | Shrinks the game play space. _Amount is optional_
spawnmass [id] [mass]         | Sets a player spawnmass. Default is (0)
speed [id] [mass]             | Sets a player base speed. Default is (0)
split [id] [count]            | Splits a player into **[count]** pieces.
status                        | Shows the amount of players currently connected, time elapsed, memory usage *(memory used/memory allocated)*, and the current gamemode.
team [id] [team (r,g,b)]      | Changes a players team. *(you might have to split to see the changes though)*
tp [id] [x pos] [y pos]       | Teleports the specified player to the specified coordinates.
troll [id]                    | You'll figure this one out. It's a suprise!
update  [all,botname,skin]    | Update to current/recent version & replace old with new.
verify [command] [id]         | Verifies/Re-verifies a player. _(Usage: **verify reverify 1** force 1 to verify again)_
virus [x pos] [y pos] [mass]  | Spawns a virus cell at those coordinates. If a mass value is not specified, then the server will default to "virusStartMass" in the config.
whitelist [ip]                | Whitelist an IP. Do **whitelist** only for a list of whitelisted IP
unwhitelist [ip]              | Remove an IP from whitelist

## Contributing
Just make a pull request or make your own copy.

### Things that I don't want you to copy *(copying it to your own file or fork)*
1. No-Lag antibot measures
2. OP
3. Minions
4. Smart bot/despawn
5. Easy verify
6. Periodic things *(pmsg, pcmd, etc..)*
7. Mousefilter
8. Plugins
9. Advanced multiverse system
10. Client config system
11. Language support system
12. Tutorial system
13. Quadrants

**Anything else, if you improved it, you don't have to give us credit. Or else, if you just copied, you must give us credit**
