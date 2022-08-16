## Version information

### Known bugs (currently known but unresolved bugs will be displayed here in unison)
> I. Plugins are not recommended to be hot loaded with plugins like yum!  
> II. 1.x version upgrade to version 2.x Note (using sqlite storage )!   
> Please change the playerTitle.db file name to PlayerTitle.db first before upgrading

#### If you encounter errors, or plug-in conflicts and other problems, please add group feedback

------------
# [**click to go to version 3.x update log**](PlayerTitle3/zh_CN/log)

#### 2.10.8
**March 19, 2022**
1. **Optimized** Variables now support showing offline players

#### 2.10.8 update small assistant
- The configuration file has no change compared to version 2.10.7, just replace the jar directly

#### 2.10.7
**04 February 2022**
1. **OPTIMIZED** Adapted to PlayerIntensify Enhanced Plugin version 1.1.2+

#### 2.10.7 update mini-helper
- No changes to the configuration file compared to version 2.10.6, just replace the jar directly

#### 2.10.6
**February 04, 2022**
1. **Fix** an issue where using sqlite would report an error

#### 2.10.6 update small assistant
- Configuration file compared to 2.10.5 version no change, directly replace the jar can be

#### 2.10.5
**February 03, 2022**
1. **Fix** Sometimes open gui exception when using mmoItems as buff

#### 2.10.5 update small helper
- Configuration file compared to version 2.10.4 no change, direct replacement jar can be

#### 2.10.4
**January 04, 2022**
1. **Fix** particle effect error when using multiple attached particle plugins

#### 2.10.4 update small assistant
- Configuration file compared to 2.10.3 version no change, directly replace the jar can

#### 2.10.3
**January 03, 2022**
1. **Optimization** Some people alerted to the problem of abnormal connection to the server

#### 2.10.3 update small assistant
- Configuration file compared to version 2.10.2 no change, direct replacement jar can be

#### 2.10.2
**January 02, 2022**
1. **OPTIMIZED** After config turn off isEnableBuff configuration, do not trigger clear buff event

#### 2.10.2 update small helper
- Configuration file compared to version 2.10.1 no change, directly replace the jar can be

#### 2.10.1
**December 30, 2021**
1. **Optimization** Add more api, check javadoc for details

#### 2.10.1 update small assistant
- Configuration file compared to version 2.10.0 no change, direct replacement jar can be

#### 2.10.0
**December 28, 2021**
1. **optimization** api restore the type of previous version deleted

#### 2.10.0 update small assistant
- Configuration file compared to version 2.9.9 no change, direct replacement jar can be

#### 2.9.9
**December 27, 2021**
1. **New** api for removing reset player buffs, see [**api documentation**](PlayerTitle/en_US/api)

#### 2.9.9 update of the mini-helper
- The configuration file is unchanged from 2.9.8, just replace the jar directly

#### 2.9.8
**December 15, 2021**
1. **Fix** Potion buffs do not take effect after respawning

#### 2.9.8 update small assistant
- Configuration file compared to version 2.9.7 no change, direct replacement jar can be

#### 2.9.7
**07 December 2021**
1. **Fix** Fix for title card's lore not supporting rgb colours

#### 2.9.7 update of the little helper
- No change in config file compared to version 2.9.6, just replace the jar directly

#### 2.9.6
**December 04, 2021**
1. **Fix** Fix the bug that causes tab errors in lower versions in order to adapt 1.18

#### 2.9.6 update small assistant
- Configuration file compared to version 2.9.5 no change, direct replacement jar can be

#### 2.9.5
**December 02, 2021**
1. **Optimisation** Better adaptation to 1.18

#### 2.9.5 update small helper
- No change in configuration files compared to 2.9.4, just replace the jar directly

#### 2.9.4
**December 01, 2021**
1. **Optimized** Better adaptation to 1.18
2. **Optimization** The monster immunity in buffs can now be set to take effect in the world  

> /plt setTitleBuff 1 monster_truce world  
The last parameter of the command is the valid world name  
Not passing the last parameter will validate all worlds by default

#### 2.9.4 update small helper
- The configuration file is unchanged from version 2.9.3, just replace the jar directly.

#### 2.9.3
**November 18, 2021**
1. **Fix** Fix the bug that color.yml configuration is invalid

#### 2.9.3 update small assistant
- Configuration file compared to 2.9.2 version no change, directly replace the jar can be

#### 2.9.2
**16 November 2021**
1. **FIXED** In some cases, the title and introduction would show the colour code
2. **FIXED** Adding a buff in mysql case, the field length was not long enough to cause an error

#### 2.9.2 update helper
- The configuration file has no change compared to version 2.9.1, just replace the jar directly.

#### 2.9.1
**November 4, 2021**
1. **Fix** 2.9.0 version of /plt adminShop cannot be opened
2. **Optimize** buff processing part of the code

#### 2.9.1 update small helper
- No change in configuration file compared to version 2.9.0, just replace the jar directly

#### 2.9.0
**October 21, 2021**
1. **New** Add ${player} as a player name variable in the gui
2. **Optimized** Add pre-particle effect PlayerParticles Chinese text

#### 2.9.0 update small helper
- Configuration files have changed compared to version 2.8.8 language files
- Just replace the jar directly

#### 2.8.8
**October 21, 2021**
1. **Fix** item.yml localization process will not conflict with cloud localization anymore
2. **New** Added bStats statistics

#### 2.8.8 Update Assistant
- There is no change in the configuration file compared to the 2.8.7 version, just replace the jar directly

#### 2.8.7
**14 October 2021**
1. **Fix** /plt set command error after turning on auto-use of title

#### 2.8.7 update small helper
- No changes to the configuration file compared to 2.8.6, just replace the jar

#### 2.8.6
**10 October 2021**
1. **Fix** MMOItems type buff, buff will not disappear after the title expires
2. **Optimized** Limit title expiration related optimization

#### 2.8.6 update helper
- No changes to the configuration file compared to 2.8.5, just replace the jar

#### 2.8.6
**October 10, 2021**
1. **Fix** MMOItems type buff, the buff will not disappear after the title expires
2. **Optimize** the optimization process related to the expiration of the authority title

#### 2.8.6 update small assistant
- The configuration file has no change compared to version 2.8.5
- Directly replace the jar can be

#### 2.8.5
**09/29/2021**
1. **Fix** 2.8.4 version Cancel the use of the title buff does not normally disappear the problem

#### 2.8.5 update small assistant
- The configuration file has no change compared to version 2.8.4
- Just replace the jar directly

#### 2.8.4
**09/29/2021**
1. **Optimized** now developing buff type api, external plugins can inject custom buffs
2. **Fix** Permission title not expiring properly, now modified to handle at regular intervals
3. **Fix** some language alerts not existing

#### 2.8.4 update small helper
- No changes to the configuration file compared to version 2.8.2
- Just replace the jar directly

#### 2.8.3
**18 September 2021**
1. **New** support for titles, title mall, title store button, title card model customization [**custom model support**](PlayerTitle/en_US/resourcepacks)
2. **New** Particle plugin PlayerParticles compatible
3. **Optimized** Network error alert at launch in some areas

#### 2.8.3 update small assistant
- Language files have been changed, it is recommended to delete the old language file and generate a new one
- material.yml has been greatly improved, please make sure to regenerate it
- Then just replace the jar

#### 2.8.2
**September 13, 2021**
1. **Fix** the problem that the title buff variable does not change after switching titles
2. **New** title buff compatible with MMOItems
3. **Optimization** Some api optimization check [**api documentation**](PlayerTitle/en_US/api)

#### 2.8.2 update small assistant
- The configuration file has no changes compared to version 2.8.1
- The language file has changed, it is recommended to delete the old language file to generate a new one.
- Just replace the jar directly

#### 2.8.1
**08/18/2021**
1. **Fix** hotload plugin causes multiple null in front of the name
2. **FIX** A bug (because announcing it will cause players to know, so do not announce it, but the bug affects badly, please use the item exchange title of the rotten bamboo must upgrade)

#### 2.8.1 update small assistant
- Language file added content, please be sure to regenerate the new

#### 2.8.0
**08/2021**
1. **New** custom title length limit
2. **OPTIMIZED** Now the permission type title will disappear after the permission is cancelled and the corresponding permission title is logged in again
3. **Optimized** New titles will now return the title id in the chat
4. **Added** New delete title command /plt del [title id]
5. **Optimized** api optimization, welcome developers to dock

#### 2.8.0 update small assistant
- Language file and config file have new content, please make sure to backup the previous one and regenerate the new one.

#### 2.7.9
**07/26/2021** 1.
1. **Added** Now 1.17 items will be Chineseized properly
2. **New** api is available for other plugins to dock, see [api documentation](PlayerTitle/zh_CN/api)
   The first to start docking can contact me to provide technical guidance support

#### 2.7.9 update small assistant
- Configuration file compared to version 2.7.8 without any changes, direct replacement jar can be

#### 2.7.8
**07/19/2021** 1.
1. **Added** /plt addCustom command to add title customization times
2. **Fix** color code & can be used when compatible with ap
3. **Fix** /plt adminShop pagination is not displayed properly

#### 2.7.8 update small assistant
- Language file added, please delete the language file to regenerate

#### 2.7.7
**07/18/2021**
1. **Optimize** new way to use iaTab,
2. **Fix** Probably will fix the previous isTab conflict with the scoreboard
3. **Fix** the problem that the title prefix does not disappear after closing isTab
4. **FIX** The length of the title is intercepted by default to a maximum of 16 bits in the case of less than 1.13, and 64 bits in the case of greater than or equal to 1.13

#### 2.7.7 update small assistant
- Configuration file compared to version 2.7.6 no change, direct replacement jar can be

#### 2.7.6
**07/15/2021**
1. **Optimized** now uses real player names for title number ranking
2. **New** Now the search criteria button under the title mall can be configured via material.yml
3. **Optimized** Now the descriptions can be line feed, just add English to the content, split it, Chinese, no split
> For example, this is the first line of description, this is the second line of description
4. **Fix** low version mysql compatibility adjustment
5. **Fixed** Chat bar reminder is displayed normally when the title and other contents are modified in /plt adminshop
6. **New** Player custom titles are now available
> /plt custom [title name] set custom title gui
/plt setCustom [player name] [customizable times] set the number of times a player can customize
7. **Fix** crash problem caused by too long titles after isTab is opened (not recommended to set titles with more than 16 bits)
8. **FIX** Fix the problem of using &1 color code in sx3.x version, this 1 is also counted as attribute.
9. **New** two variables
> Player customizable %playerTitle_custom_num%
Number of times player has customized %playerTitle_custom_usenum%

#### 2.7.6 update small helper
- The language file has changed a little, suggest to regenerate
- material.yml file has changed, suggest to backup the previous one, then regenerate

#### 2.7.4
**06/30/2021** 1.
1. **Fix** plt convert sqllite command exception

#### 2.7.4 update small helper
- The configuration file has no changes compared to version 2.7.3, just replace the jar directly

#### 2.7.3
**June 29, 2021**
1. **Fix** plt convert mysql command exception

#### 2.7.3 update small helper
- The configuration file has no changes compared to version 2.7.2, just replace the jar directly

#### 2.7.2
**June 26, 2021**
1. **Optimization** Now a plugin is compatible with both sx2.x version and 3.x version

#### 2.7.2 update small helper
- Configuration file compared to version 2.7.1 no change, directly replace the jar can be

#### 2.7.1
**June 24, 2021**
1. **optimization** now does not require 5.7 + mysql, compatible to mysql low version (pro-test 5.5 version still have problems, will be completely compatible in version 2.7.5)

#### 2.7.1 update small assistant
- Configuration file compared to version 2.7.0 without any changes, direct replacement of jar can be (please look carefully at the 2.7.0 update log)

#### 2.7.0
**06/23/2021** 1.
1. **New** command /plt convert mysql(convert sqlite data to mysql)
2. **New** command/plt convert sqlite(convert mysql data to sqlite)
> Please try to convert when no player is online, and restart the server after the conversion operation.
3. **New** New function of whether to turn on title buff or not (for some subservices don't want buff)

#### 2.7.0 update small assistant
- Language file added, you can add yourself to the helps node, or delete the language file to regenerate
```
"&e/plt convert [type] &f convert data, type can be mysql or sqlite"
```

- New in config.yml, you can add it to config.yml yourself, or delete the configuration file and regenerate it
```
# Whether to enable title buff function, can be true/false. true case, title buff will be loaded normally, false case, title buff will be invalid (can be used for some lobby or special rpg service)
isEnableBuff: true
```

#### 2.6.0
**June 13, 2021**
1. **New** Compatible with version 1.17

#### 2.6.0 update small helper
- Configuration file compared to version 2.5.8 without any changes, direct replacement of jar can be

#### 2.5.8
**May 22, 2021**.
1. **Fix** some versions of mysql will generate an exception error after the automatic use of the title is turned on
1. **Fix** some strange core title card use error reporting problem

#### 2.5.8 update small assistant
- Configuration file compared to version 2.5.7 without any changes, direct replacement jar can be

#### 2.5.7
**10 May 2021**.
1. **New** New configuration for automatic use after getting a title

#### 2.5.7 update small assistant
- The configuration file has changed compared to 2.5.6, the following new content in the config, you can copy and add it yourself, or delete the config and restart the server automatically generated
```
# Whether to enable auto use, true/false. true case, the player will get a new title will be put into the warehouse and automatically used, false case, the player will get a new title will only be put into the warehouse and not automatically used
isAutoUse: false
```

#### 2.5.6
**May 5, 2021** 1.
1. **Optimized** Now compatible with PlayerPoints-3.0.1 version [original post of the Points plugin](https://www.spigotmc.org/resources/playerpoints.80745/ "New address for the Points plugin")

#### 2.5.6 update small helper
- The configuration file has no changes compared to version 2.5.5, just replace the jar directly.

#### 2.5.5
**20 April 2021**
1. **New** global buff function
2. **New** compatible reinforcement plugin PlayerIntensify [reinforcement plugin introduction wiki](https://www.showdoc.com.cn/PlayerIntensify?page_id=6670125914381777 "reinforcement plugin introduction wiki")
2. **Fix** the error caused by asynchronous removal of potion effect

#### 2.5.5 update small assistant
- Configuration file changes compared to version 2.5.4 are as follows

config.yml is new - you can delete it and re-generate it or copy the following to the end
```
# Whether to open the global warehouse buff, optional true/false. true case, all the buffs of the title of the player's backpack will be loaded, false case, only the title buff worn by the player will be loaded
isAllBuff: false
```
New language file in language - can be deleted and regenerated or added manually
```
# PlayerIntensify reminder
playerIntensifySucceedMsg: "&a successfully loaded PlayerIntensify, enabling player enhancement related features!"
playerIntensifyFailureMsg: "&4 PlayerIntensify not found, player enhancement related features not enabled!"

setTitleBuff:
  playerIntensify: "&a reinforcement effect"
```
#### 2.5.4
**March 15, 2021**
1. **Optimization** Optimize some code
2. **Fix** Cannot convert other purchase conditions to permission purchase conditions in amdinshop

#### 2.5.4 update small assistant
- Configuration file compared to version 2.5.3 without any changes, direct replacement of jar can be

#### 2.5.3
**February 13, 2021**
1. **FIX** Low version error with original item as commit condition
2. **Fixed** Now it will clear the cache (important update)
3. **New** Now you can set cooldown time for switching titles

#### 2.5.3 update small assistant
- Configuration file changes compared to version 2.5.2 are as follows

config.yml added - can be deleted to allow regeneration or copy the following content to the end
```
# Toggles the cool down time of the title, in seconds - set 0 to turn off the function
togglesCoolDown: 10
```
New language file in language - can be deleted to recreate or copy the following content to any location under the open node
```
open:
  togglesCoolDownMsg: "&4 cooldown not yet reached, please toggle after ${time} seconds"
```

#### 2.5.2
**February 10, 2021**
1. **Fix** Get title card sometimes report error

#### 2.5.2 update small assistant
- Configuration file compared to version 2.5.1 no change, direct replacement jar can be

#### 2.5.1
**February 10, 2021**
1. **Optimization** No longer limit the length of the tab title display.

#### 2.5.1 update small helper
- The configuration file has no change compared to version 2.5.0, just replace the jar directly.

#### 2.5.0
**February 09, 2021**
1. **New** Fix the problem of very low probability that the permission title can't open /plt adminshop

#### 2.5.0 update small assistant
- Configuration file compared to version 2.4.9 without any changes, direct replacement of jar can be

#### 2.4.9
**February 07, 2021**
1. **New** 1.16+ server name support RGB16 bit color, new color.yml configuration file

#### 2.4.9 update small assistant
- Configuration file compared to version 2.4.8 without any changes, direct replacement jar can be

#### 2.4.8
**February 07, 2021**
1. **New** command to delete single line buff /plt delBuff [buffId]
   buffId can be viewed in /plt adminshop

#### 2.4.8 update small helper
- The language file in languages also has new language content, it is recommended to delete and regenerate it if it has not been changed.

#### 2.4.7
**February 04, 2021**
1. **Optimization** Compatible with ap3.x version

#### 2.4.7 update small assistant
The configuration file has no changes compared to version 2.4.6, just replace the jar directly

#### 2.4.6
**February 04, 2021** 1.
1. **New** customizable alert message after getting the title
   How to use: Added a new configuration file message.yml, click on it to see for yourself, the comments are very clear

#### 2.4.6 update small assistant
Configuration file compared to version 2.4.5 without any changes, directly replace the jar can be

#### 2.4.5
**February 02, 2021**
1. **Added** customizable item material for the title in the mall
   How to use: Added a new configuration file material.yml, open it yourself, the comments are very clear
   [item material help URL](https://minecraft-ids.grahamedgecombe.com/ "item material help URL")

#### 2.4.5 update helper
The configuration file has no change compared to 2.4.4 version, just replace the jar directly.

#### 2.4.4
**January 28, 2021**
1. **Optimization** Optimize some functions of title lore display

#### 2.4.4 update small assistant
Configuration file compared to version 2.4.3 without any changes, direct replacement of jar can be

#### 2.4.3
**January 14, 2021**
1. **Optimization** Optimization of some vulnerabilities caused by low versions, highly recommended upgrade

#### 2.4.3 update small assistant
Configuration file compared to version 2.4.2 without any changes, direct replacement of jar can be

#### 2.4.2
**January 12, 2021**
1. **New** Added /plt listTitle to command to view title id
2. **New** Added /plt adminShop to view admin title gui, the effect is equivalent to /plt view shop

#### 2.4.2 update small assistant
A bit of language file related reminders added, you can regenerate the language file or manually add the following language file
```java
listTitle:
  # Query the title of the player's title list
  titleList: "&e&m一一一一一一一&f[&e所有称号列表§f]&e&m一一一一一一一"
  # No player data found
  noTitleFailureMsg: "&a server currently has no titles"
  # Wrong number format
  titleIdFailureMsg: "&4 page numbers can only be numeric"
  id: "&a serial number: "
  titleName: "&a title name: "
  buyType: "&aBuyType: "
  amount: "&aAmount: "
  number: "&aquantity: "
```

#### 2.4.1
**December 15, 2020**
1. **New** Add cstats statistics

#### 2.4.1 update small helper
Configuration file compared to version 2.4.0 no changes, direct replacement jar can be

#### 2.4.0
**November 27, 2020**
1. **Optimization** Fix some bugs that you don't understand, and optimize the code

#### 2.4.0 update small assistant
Configuration file compared to version 2.3.9 without any changes, direct replacement of jar can be

#### 2.3.9
**November 23, 2020**
1. **Fix** the title card can be used in the secondary hand resulting in the brush title bug, now only the main hand to use the title card

#### 2.3.9 update small assistant
Configuration file compared to version 2.3.8 without any changes, directly replace the jar can be

#### 2.3.8
**October 15, 2020**
1. **Fix** The cache of the group service switching service title is not cleaned
2. **Fix ** 1.13 below the version of the tab error reported invalid problem

#### 2.3.8 update small assistant
Configuration file compared to version 2.3.7 without any changes, direct replacement jar can be

#### 2.3.7
**October 13, 2020**
1. **Fix** the variable %playerTitle_description% of the title description is not displayed
2. **New** variables for title buffs (multiple buffs will be, separated) %playerTitle_buff%
3. **New** variable for title particle %playerTitle_particle%
4. **Fix** sqlite generate table error

#### 2.3.7 update small assistant
Compared to version 2.3.6, no configuration changes, direct replacement of jar, if it is an earlier version, please see the previous update small helper

#### 2.3.6
**October 13, 2020**
1. **Optimization** Now a same title given to a player at different times will stack up,
   For example, if a player is given the title A-3 days, and then given the title A-5 days, then the expiration time of the title A should be 8 days

#### 2.3.6 update small assistant
The language file has been updated, it is recommended to delete the languages folder and let it be regenerated.

#### 2.3.5
**October 12, 2020**
1. **FIXED** The header title and tab title will now change

#### 2.3.5 update of the small assistant
Please make sure to see the 2.3.4 update

#### 2.3.4
**October 12, 2020**
1. **New** Now new title type - Active (this type will be displayed in the title mall, but players can not buy, only see, use the command or title card to give players)
2. **New** title description, now you can describe the title, it is recommended that a short sentence, for example (obtained through 2020 National Day), too long is not recommended, the command /plt setDescription [title id] [title description]
   If you don't want the title description to be displayed in the lore, just find the corresponding lore in the language file and delete the corresponding line.
3. **Added** New variable for title mall and warehouse Description: ${description} , write this in the corresponding lore in the language file, and it will be replaced by the title description automatically
4. **Added** Add variable %playerTitle_description% Description of the player's title
5. **Fix** When deleting a title, the corresponding particle effect is also deleted.

#### 2.3.4 update assistant
The language file has been updated, it is recommended to delete the languages folder to recreate it.

#### 2.3.3
**October 10, 2020**
1. **Fix** Fix the bug that the potion effect of the previous title is not cleared when switching titles

#### 2.3.3 update small assistant
No change in configuration, just replace the jar directly

#### 2.3.2
**October 8, 2020**
1. **Optimization** Make some inconsequential code optimization

#### 2.3.2 update small assistant
No changes to the configuration, just replace the jar directly

#### 2.3.1 (full version preemptive experience)
**October 5, 2020**
1. **Optimization** Now canceling the title will also cancel the particle effect attached to the title
2. **Optimized** Fully compatible with SuperTrailsPro now

#### 2.3.1 update small assistant
The language file has been updated, it is recommended to delete the languages folder to recreate it.

#### 2.3.0
**September 30, 2020**
1. **New** support for particle titles [click to view](https://www.showdoc.com.cn/PlayerTitle?page_id=5518933383532639 "click to view")

#### 2.3.0 update small assistant
The language file has been updated, it is recommended to delete to let regenerate

#### 2.2.0
**September 29, 2020**
1. **Optimization** optimize performance, modify some methods to asynchronous execution
2. **Optimization** Player input /plt help will also be alerted now
3. **New** command /plt getIp will show your server real ip and port after input
4. **Optimized** Fixed some problems that caused screen swiping because the server was not accessible outside (now up to 6 requests)
5. **Optimization** Fix some reminders that language files are not available
6. **Optimization** Now potion effects can be translated in the language file by your own configuration
7. **OPTIMIZATION** Now the permanent title will not show 2120-00-00 anymore, it will show permanent directly

#### 2.2.0 update assistant
The language file has been updated, it is recommended to delete to let regenerate

#### 2.1.7
**September 10, 2020**
1. **Fix** temporarily adjust the player buff settings from asynchronous to synchronous execution, because asynchronous plus potion buff will report an error

#### 2.1.7 update small assistant
Compared to version 2.1.6, no configuration updates, direct replacement of jar can be

#### 2.1.6
**August 21, 2020**
1. **Fix** Player respawn reset buff optimization

#### 2.1.6 update small assistant
Compared to version 2.1.5, no configuration update, direct replacement jar can be

#### 2.1.5
**August 19, 2020**
1. **Fix** permission title in the shop display problem (but I do not recommend showing it, because the player will automatically get the title as long as they have permission to log in)
2. **Fix** /plt view open (player name) command to delete a player's title, it will jump to their own title store

#### 2.1.5 update small assistant
Compared to version 2.1.4, no configuration update, just replace the jar directly

#### 2.1.4
**August 17, 2020**
1. **Fix** the bug that potion buffs are lost after players respawn

#### 2.1.4 update small assistant
Compared to version 2.1.3, no configuration update, direct replacement jar can be

#### 2.1.3
**August 12, 2020**
1. **Fix the bug that the corresponding title attributes are not added to the player immediately when entering the game

#### 2.1.3 update small assistant
Compare to version 2.1.2, no configuration update, just replace the jar directly

#### 2.1.2
**August 7, 2020**
1. **Optimization** Code optimization, no change in functionality

#### 2.1.2 update small assistant
Just replace the jar directly

#### 2.1.1
**August 7, 2020**
1. **Added** Command: /plt addPlayerTitle [player name] [title name] (days)  
   Add a hidden title directly, and give this title to the corresponding player, the number of days if you do not fill in the default permanent

#### 2.1.1 update small assistant
Language file has a small adjustment, new help help (let us remember the fastest dying 2.1.0 version ...)

#### 2.1.0
**August 7, 2020** 1.
1. **New** compatible title buff add type Original potion effect

#### 2.0.1 update small assistant
Language file has a small adjustment, new potion buff-related fields, it is recommended to make up all by themselves or backup the old, and then let regenerate the language text


#### 2.0.1
**August 5, 2020**
1. **Fix** /plt view shop in the management of the title, the title buff does not show the problem
2. **Fix** the problem that hidden titles in /plt view shop are not shown
3. **Optimization** New /plt will show help

#### 2.0.1 update small assistant
Compare to version 2.0.0, no configuration update, just replace the jar directly

#### 2.0.0
**August 3, 2020**
1. **Optimization** Better compatibility - Perfectly compatible with 1.7-1.16
2. **Optimized** Compatible sx changed from version 2.0 to 3.0 reset version
3. **New** cloud Chinese system 1.13-1.16 automatic full item Chinese, other versions can be configured in item.json can also use cloud Chinese
4. **Optimization** Redo the number of rewards of the name, more convenient to receive, more intuitive gui
5. **Optimized** remove a large number of instructions, can be managed by the gui will be managed by the gui (new instructions first see the language file)
6. **New** You can view the gui of the player's title and manage it
7. **New** You can view the number of titles rewarded gui and manage
8. **New** You can view and manage the gui of the title mall
9. **New** permission to use separate commands for title types
10. **Optimized** Now there is no limit to the price of the title
11. **New** Now the plugin is divided into public and full version

#### 2.0.0 update small assistant
Upgrade to 2.x will not have any changes to the previous 1.x title data and players, just more convenient for the administrator to operate
The content of config.yml has changed, and the language file has changed a lot, so it is recommended to delete it and let it be regenerated.
Material.yml delete