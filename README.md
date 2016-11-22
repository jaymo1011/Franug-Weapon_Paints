# About this fork
This is a fork of the fraung's weaponpaints plugin for sourcemod.
I aim to make this fork better or on par with fraung's private weapon paints plugin and 100% free!
Sadly though, this fork will NOT have Multilanguage support.
Sorry I don't speak or have the time to translate all the phrases in to any other languages.

# How to install
- Installation (Public server with GSLT)

- Compiling the plugin:
1. Open  jaymo_weaponpaints.sp file in a text editor
2. Go to line 80 and follow the instructions given and save the file
3. Open and extract the scripting.zip included in the download to your desktop.
4. Open the scripting folder and move the edited jaymo_weaponpaints.sp file into it
5. Drag and drop the .sp file on to spcomp.exe, a command prompt window will open
6. After the command prompt closes there should now be a jaymo_weaponpaints.smx

You have now compiled the plugin and you can move on to the next step

Upload .cfg file to addons/sourcemod/configs
Upload .smx file you just finished creating to addons/sourcemod/plugins
Upload .phrases.txt file to addons/sourcemod/translations


- Installation (Private server with no GSLT):
Upload the .cfg file to addons/sourcemod/configs
Upload the .smx file from the zip to addons/sourcemod/plugins  (WARNING IF YOUR SERVER IS PUBLIC, YOUR LOGIN TOKEN WILL BE BANNED)
Upload the .phrases.txt file to addons/sourcemod/translations
Add a entry called "weaponpaints" to addons/sourcemod/configs/databases.cfg
A example of a basic databases.cfg is http://pastebin.com/XqsEjPhS


- Cvars:
sm_weaponpaints_c4 "0" // Enable or disable that people can apply paints to the C4. 1 = enabled, 0 = disabled
sm_weaponpaints_saytimer "-1.0" // Time in seconds for block that show the plugin commands in chat when someone type a command. -1 = never show the commands in chat
sm_weaponpaints_roundtimer "-1.0" // Time in seconds after the round has started for can use the commands for change the paints. -1.0 = always can use the command
sm_weaponpaints_rmenu "1" // Re-open the menu when you select a option. 1 = enabled, 0 = disabled.
sm_weaponpaints_onlyadmin "0" // This feature is only for admins. 1 = enabled, 0 = disabled.
sm_weaponpaints_zombiesv "1" // Enable this for prevent crashes in zombie and 1v1 servers for knifes. 1 = enabled, 0 = disabled.

- Little bit of ass covering:
I am not responsible for your game server login token being banned or your steam account being banned from CS:GO matchmaking.

# To Do
- Update Installation instructions.
- Some GLST ban prevention
- Other stuff ;)
