### Version information

### Known bugs (currently known but unresolved bugs will be displayed here)

1. plug-ins should not be hot-loaded using plug-ins like yum!
2. mission objectives, some items held in the hand and put down is a different item, so it can not be detected, it is
   recommended that here try not to use these special items as mission objectives, for example: red stone powder,
   railroad tracks, seeds ...

#### If you encounter errors, or plug-in conflicts and other problems, please add group feedback

------------
#### 1.13.9
**08 August 2022**
1. **Optimization** Better compatibility with mods

#### 1.13.9 update helper
Compare to version 1.13.8 Just replace the jar directly

#### 1.13.8
**28 July 2022**
1. **Fix** occasional sqlite deadlock issue

#### 1.13.8 update of the small helper
Compare to version 1.13.7. Just replace the jar directly.

#### 1.13.7
**21 July 2022**
1. **Fix** irregularities in npc quest cooldown times

#### 1.13.7 update of the little helper
Compare to version 1.13.6 Just replace the jar directly

#### 1.13.6
**July 02, 2022**
1. **Optimized** Add automatic pickup of completed tasks

#### 1.13.6 update small assistant
- config.yml added
```
# Automatic delivery of rewards for completing daily tasks (Automatic delivery of rewards for completing daily tasks)
autoReward: false
```

#### 1.13.5

**June 18, 2022**

1. **OPTIMIZATION** The mission coin mall will only refresh the gui after purchasing items will not be closed down

#### 1.13.5 update small assistant

Compared to 1.13.4 version directly replace the jar can be

#### 1.13.4

**June 13, 2022**

1. **Optimization** Better compatibility with 1.19

#### 1.13.4 update small assistant

Compare to 1.13.3 version Just replace the jar directly

#### 1.13.3

**May 21, 2022**
1. **New** New mission objective type added enchantment and kill players
2. **Optimization** Optimize a lot of code

#### 1.13.3 update small assistant
- Configuration file compared to version 1.13.0 no change, direct replacement jar can be

#### 1.13.2
**May 13, 2022**
1. **New** /plk coin [give|take|set] [player name] [quantity] give|take|set player task coin quantity

#### 1.13.2 update small assistant
- Configuration file compared to version 1.13.1 language file has changed, it is recommended to backup and regenerate the next

#### 1.13.1
**May 03, 2022**
1. **Fix** an abnormal issue with the id returned by the edit command
2. **Fix** the problem that rewards are not sent in full in some cases

#### 1.13.1 update small assistant
- Configuration file compared to version 1.13.0 no change, direct replacement jar can be

#### 1.13.0
**04/19/2022**
1. **Optimization** Special version causes item null exception

#### 1.13.0 update small assistant
- Configuration file compared to version 1.12.9 no change, direct replacement jar can be

#### 1.12.9
**04 April 04, 2022**
1. **optimized** item.json works for other language types as well
2. **Optimize** some problems with convert command

#### 1.12.9 update small helper
- The configuration file has no change compared to version 1.12.8, just replace the jar directly

#### 1.12.8
**03/04/2022**
1. **Fix** 1.8 submission type quest exception
2. **Fix** npc quest disable right click query

#### 1.12.8 update for small helpers
- No change in configuration file compared to 1.12.6, just replace the jar directly

#### 1.12.6
**March 30, 2022**
1. **Optimized** Compatible with MythicMobs 5.x

#### 1.12.6 update small assistant
- Configuration file no change compared to 1.12.5 version, just replace the jar directly

#### 1.12.5
**March 19, 2022**
1. **Fix** special items under mysql length too long error reported

#### 1.12.5 update small assistant
- Configuration file compared to version 1.12.4 no change, direct replacement jar can be

#### 1.12.4
**16 Mar 2022**
1. **Fix** a bug where items were not deducted for certain special cases of task submissions

#### 1.12.4 update small assistant
- The configuration file has no change compared to version 1.12.3, just replace the jar directly

#### 1.12.3
**March 11, 2022**
1. **Optimization** Task probability random refresh mechanism anomaly repair

#### 1.12.3 update small assistant
- Configuration file compared to version 1.12.2 no change, directly replace the jar can

#### 1.12.2
**March 02, 2022**
1. **Improvement** Removed logic from 1.12.1, now submit item type quests are integrated directly into the left click  
   When clicked, the item will be submitted and the task will be completed (only if the required number of items are in the backpack)

#### 1.12.2 update helper
- No changes to the configuration file compared to 1.12.1, just replace the jar directly

#### 1.12.1
**14 February 2022**
1. **Optimization** Event prioritization
2. **Optimized** customizable submit task button in version 1.18

#### 1.12.1 update of the small helper
- config.yml added
```
# MIDDLE mouse middle key (or mouse scroll wheel key) DOUBLE_CLICK double click mouse left key
# Specific view https://bukkit.windit.net/javadoc/org/bukkit/event/inventory/ClickType.html
# Keyboard and Shift related keys are not available
submitClickType: MIDDLE
```

#### 1.12.0
**25/01/2022**
1. **Fixes** some low version upgrades that caused error reporting on task creation

#### 1.12.0 update for small helpers
- No change in configuration file compared to 1.11.9, just replace the jar directly

#### 1.11.9
**January 23, 2022**
1. **FIX** Refreshing a task causes other people's tasks to be refreshed as well
2. **FIX** Abnormal number of task refreshes
3. **Fix** the problem that batch synthesis only counts 1 quantity
4. **Fix** some erroneous sql that causes delete to delete more tasks

#### 1.11.9 update small assistant
- Configuration file compared to version 1.11.8 no change, directly replace the jar can be

#### 1.11.8
**21/01/2022**
1. **Fix** incorrect number of placement type tasks bug
2. **Fix** /plk up upgrade command optimization
3. **Fix** Unable to paginate issue

#### 1.11.8 update of the small assistant
- The command /plk up must be re-executed to convert the data to upgrade
- Material.yml has new content

#### 1.11.7
**12/01/2022**
1. **Fixes** long-lasting bug with placement type tasks

#### 1.11.7 update for small helpers
- Must re-execute command /plk up for data upgrade conversion
- No change in config file compared to 1.11.6, just replace the jar directly

#### 1.11.6
**11/01/2022**
1. **Fix** delete command parameter exception
2. **Fix** unpage-down exception in gui
3. **Fix** plk up command exception
4. **Fix** an issue that may cause sqlite to lock the library

#### 1.11.6 update helper
- The command /plk up must be re-executed to convert the data update
- No change in configuration file compared to 1.11.4, just replace the jar directly

#### 1.11.4
**January 04, 2022**
1. **Fix** sqlite sometimes sql execution fails

#### 1.11.4 update small helper
- Configuration file compared to version 1.11.3 no change, direct replacement jar can be

#### 1.11.3
**January 03, 2022**
1. **Fix** Sometimes special items can cause sql query exceptions

#### 1.11.3 update small assistant
- Must execute command /plk up for data update conversion
- Configuration file compared to version 1.11.2 no change, direct replacement jar can be

#### 1.11.2
**January 02, 2022**
1. **Fix** the exception that only one item can appear when disassembling in synthesis

#### 1.11.2 update small assistant
- Must execute command /plk up for data upgrade conversion
- Configuration file compared to version 1.11.1 no change, directly replace the jar can be

#### 1.11.1
**January 02, 2022**
1. **FIX** Unintentionally initialized mysql field lengths causing error reports

#### 1.11.1 update assistant
- Must execute command /plk up for data upgrade conversion
- The configuration file has no change compared to version 1.11.0, just replace the jar directly

#### 1.11.0
**January 02, 2022**
1. **New** A large number of api interfaces, see [github](https://github.com/handy-git/PlayerTaskVersions)
2. **Optimized** Now performance is improved, but to improve performance, you have to perform /plk up for data conversion

#### 1.11.0 update small helper
- You must execute the command /plk up to convert the data update
- The configuration file is unchanged compared to version 1.10.2, just replace the jar directly

#### 1.10.1
**December 03, 2021**
1. **Optimization** Language file optimization

#### 1.10.1 update small assistant
- Configuration file compared to version 1.10.0 no change, direct replacement jar can be

#### 1.10.0
**01 December 2021**
1. **Optimised** Better adaptation 1.18

#### 1.10.0 update mini-helper
- No change in configuration file compared to 1.9.8, just replace the jar directly

### 1.9.8
**November 29, 2021:**
1. **Optimisation** Improved compatibility of Groupware with MythicMob

**1.9.8 Upgrade Assistant**
- No changes to the configuration file compared to 1.9.7, just replace the jar

### 1.9.7
**November 21, 2021:**
1. **Added** /plk setDescription [task id] [task description] to add task description to tasks"
2. **Fix** an error caused by mm not configuring the monster name

**1.9.7 upgrade assistant**
- The language has a file change, suggest to regenerate

### 1.9.6
**November 4, 2021:**
1. **Optimization** Improved compatibility with MythicMob, should now support all mm versions at the same time
2. **Optimization** Version 1.13+ also adds item.yml for custom name translation of mod items

**1.9.6 upgrade helper**
- No changes to the config file compared to 1.9.5, just replace the jar directly

### 1.9.5
**November 1, 2021:**
1. **Optimization** Improved compatibility with some mod items

**1.9.5 Upgrade Assistant**
- No changes to the configuration file compared to 1.9.4, just replace the jar

### 1.9.4
**28th October 2021:**
1. **Optimisation** Scroll quests to improve compatibility with other plugins

**1.9.4 upgrade mini-helper**
- No changes to the configuration file compared to 1.9.3, just replace the jar directly

### 1.9.3
**20 October 2021:**
1. **Optimized** pagination to show &a symbol in case of language file errors
2. **New** New bStats stats added

**1.9.3 upgrade mini-helper**
- No changes to the configuration file compared to 1.9.2, just replace the jar directly

### 1.9.2
**October 19, 2021:**
1. **Fix** error when alerting permission has been registered when starting

**1.9.2 upgrade small assistant**
- Configuration file compared to version 1.9.1 no change, direct replacement jar can be

### 1.9.1
**October 18, 2021:**
1. **Fix** scrolling task, error reported in the case of mysql data source

**1.9.1 Upgrade Assistant**
- Please see the 1.9.0 upgrade helper

### 1.9.0
**18 October 2021:**
1. **New** reel task, see [**reel task**](PlayerTask/en_US/reel)

**1.9.0 Upgrade Assistant**
- The language file languages has been added compared to 1.8.8, so it is recommended to regenerate it or copy it in.
- material.yml has new content compared to version 1.8.8, we suggest to regenerate it or copy it in.
- Then just replace the jar

### 1.8.8
**October 16, 2021:**
1. **Fix** Fix the possibility of generating duplicate tasks
2. **optimize** add task return id
3. **FIX** Task rarity is displayed normally
4. **FIX** wrong mm monster name caused mm error
5. **FIX** item.yml Chinese processing will not be in the dash off cloud Chinese
6. **Optimized** Now deleting tasks in /plk view list will delete the picked up tasks simultaneously

**1.8.8 upgrade assistant**
- The language file languages has been added compared to version 1.8.6, it is recommended to regenerate or copy into it
- Then you can replace the jar

### 1.8.7 

**October 12, 2021:**
1. **New** Mission rarity system, each mission has a rarity (historical missions are all normal by default), refreshing appearances based on probabilities in config.ymL
2. **Optimized** The gui-related code has been significantly reorganized and built with the latest handyLib.
3. **FIXED** Exception when selecting a task target
4. **New** New materiat.ymL for each task and /pLt open button material and custom model modification
5. **New** New command /plk setRarity [mission id] [rarity] to modify mission rarity

**1.8.7 update mini-helper**
- This is a major update: changes have been made to the config.yml and language files, it is recommended to backup the old one and regenerate the new one
- Then just replace the jar

### 1.8.6
**September 18, 2021:**
1. **New** config.yml can be configured to refresh daily tasks at regular intervals
2. **Optimized** Command type rewards can now have descriptions added

**1.8.6 Upgrade Assistant**
- The configuration file is new compared to 1.8.5, we suggest to regenerate it or copy it in
```
# Daily task refresh time, 24 hour system
setTodayDate: "00:00"
```
- Then just replace the jar

### 1.8.5
**August 11, 2021:**
1. **Change** abandoned compatible < MythicMobs4.7 version, if you want to use, please mcbbs post download compatible version

**1.8.5 upgrade assistant**
- Configuration file compared to 1.8.4 version no change, direct replacement jar can be

### 1.8.4
**August 7, 2021:**
1. **Fix** some issues with MythicMobs

**1.8.4 upgrade small helper**
- The configuration file has no changes compared to 1.8.3, just replace the jar directly

### 1.8.3
**July 26th, 2021:**
1. **optimized** compatible with version 1.17 of the Chinese, if you are upgrading remember to delete the zhch.json in the configuration

**1.8.3 upgrade assistant**
- Configuration file compared to version 1.8.1 no change, directly replace the jar can be

### 1.8.1
**July 20, 2021:**
1. **Fix** Error on player command execution in the background
2. **Optimization** Code structure optimization
3. **Optimize** disable adding mm kill task when no mm is loaded

**1.8.1 upgrade small assistant**
- Configuration file compared to version 1.8.0 no change, direct replacement jar can be

#### 1.8.0
**July 03, 2021**
1. **New** command/plk convert mysql(convert sqlite data to mysql)
2. **New** command/plk convert sqlite(convert mysql data to sqlite)
> Please try to convert when no player is online, and restart the server after the conversion operation.
3. **Optimization** Improve custom item storage serialization (in human terms, fix the reward rpg items not stacking properly)

#### 1.8.0 update small assistant
- Configuration file compared to version 1.7.2 without any changes, directly replace the jar can be

#### 1.7.2
**26 June 2021**.
1. **Optimized** Compatible with both low and high versions of mm now

#### 1.7.2 update small helper
- Configuration file compared to version 1.7.0 without any changes, direct replacement of jar can be

#### 1.7.0
**June 13, 2021**
1. **New** Compatible with version 1.17

#### 1.7.0 update small assistant
- Configuration file compared to version 1.6.8 without any changes, direct replacement of jar can be

#### 1.6.8
**04 April 04, 2021**
1. **Optimization** Now the public version is not limited to create 10 tasks, you can create unlimited tasks
1. **Optimization** Now the public version is no longer limited to the number of rewards you can get if you have playertask.vip access

#### 1.6.8 update small assistant
Configuration file compared to version 1.6.7 without any changes, directly replace the jar can be

#### 1.6.7
**March 25, 2021**
1. **Fix** /plk view list page flip error fixed

#### 1.6.7 update small helper
The configuration file has no changes compared to version 1.6.6, just replace the jar directly

#### 1.6.6
**March 14, 2021**
1. **Optimization** Add index of player task progress table to mysql storage (performance improvement for 100 people service)

#### 1.6.6 update small assistant
Configuration file compared to version 1.6.5 without any changes, direct replacement jar can be

#### 1.6.5
**February 20, 2021**
1. **Optimization** Optimize some code

#### 1.6.5 update small assistant
Configuration file compared to version 1.6.4 without any changes, direct replacement of jar can be

#### 1.6.4
**02/18/2021**.
1. **New** monster.yml configuration file used to translate the name of the normal monster kill, how to use the comments inside
2. **New** npc quest page add reminders, and you can right click to see the details of the quest
3. **New** /plk open can be set to turn on or off the button to /plk shop
4. **New** button to go to/plk open is added to /plk shop
5. **Optimized** The monster type of killing normal monsters is now automatically alerted

#### 1.6.4 update small assistant
Re-generate or manually fill in the following content into the old config and language files
New section in config:
```
# New town button for mission coin shop
shop:
  # The location to be displayed in the mission gui
  index: 45
  # Whether to display
  enable: true
  # Button material
  material: CHEST
```
Language file has a new change section:
Added under taskNpc node
```
taskNpc:
  help:
    name: "&eNpc task system"
    lore:
      - ''
      - '&c&l>> Mouse&a left click&c&l to complete the task!'
      - '&c&l>> Mouse&a middle button&c&l click to submit quest item!'
      - '&c&l>> Mouse&a right click&c&l to view quest requirements and rewards!'
```

#### 1.6.3
**February 17, 2021**
1. **New** Task refresh button now supports point coupons
2. **New** Task refresh times support custom permissions corresponding to the number of times now
3. **Fix** Cat terminal 1.12 /plk view npc open blank problem

#### 1.6.3 update small assistant
Regenerate or manually fill in the following contents to the old config and language files
If your server only uses vouchers or gold, you can remove the extra lore and set the price to 0.
The config change section:
```
# Refresh button
refresh:
  # Position in the task gui
  index: 49
  # Whether to display
  enable: true
  # How many coins to spend, 0 is not consumed, Vault is required
  cost: 666
  # How many points to spend, 0 is not consumed, PlayerPoints are required
  points: 666
  # The number of times you can refresh per person per day, restart the server or refresh at 0:00 the next day
  # Default is default:3 which means 3 times, if you have playertask.vip permission, you can get extra times.
  # You can add your own, the same as the ess home extension permission e.g. vip1: 10 vip2: 10
  times:
    default: 3
    vip: 5
  # Button material
  material: MAP
```
Language file change section:

```
# Refresh button log
refresh:
  name: "&a refresh task"
  lore:
    - ''
    - '&f[ &c refresh description &f]'
    - ''
    - '&c&l>> Click the button to refresh today's task!'
    - '&c&l>> If the task has already been claimed and completed!'
    - '&c&l>> Cannot proceed to refresh!'
    - ''
    - '&c&l>> Refreshable times: &a${times}'
    - ''
    - '&f[ &c refresh price &f]'
    - ''
    - '&c&l>> Gold: &a${cost}'
    - '&c&l>> Points: &a${points}'
    - ''
    - '&6>>&4>>&5>> &b${button} &6<<&4<<&5<<'
```

#### 1.6.2
**08 February 2021**
1. **FIX** Some items with nbt are not able to submit quests when re-entering the game

#### 1.6.1 update small assistant
Configuration file compared to version 1.6.1 without any changes, direct replacement jar can be

#### 1.6.1
**February 07, 2021**
1. **Fix** the problem that servers below 1.13 can't open/plk view npc page

#### 1.6.1 update small assistant
Configuration file compared to version 1.6.0 without any changes, direct replacement of jar can be

#### 1.6.0(mega update)
**February 06, 2021**
1. **New** NPC type tasks, please see the documentation for details
2. **Optimized** Plugin renamed: Daily Random Quest Adjusted to Player Quest Plugin

#### 1.6.0 update small assistant
- There are new contents in config,
- The language file in languages has also been added.
- It is recommended to delete the old one, then it will automatically regenerate the new one
- (If you don't regenerate, there will be a lot of missing language files!!!)

#### 1.5.0
**February 05, 2021**
1. **New** submission type task
2. **Optimized** New quest help display
3. **Fix** bug that invalidates killing normal monsters

#### 1.5.0 update small assistant
config has new content, language file also has new content, suggest to regenerate

#### 1.4.7
**February 05, 2021**
1. **Fix an abnormal error caused by ** mm monster without a name

#### 1.4.7 update small assistant
Configuration file compared to version 1.4.6 no change, directly replace the jar can be

#### 1.4.6
**January 14, 2021**
1. **Optimization** Optimization of some vulnerabilities caused by low versions, highly recommended upgrade

#### 1.4.6 update small assistant
Configuration file compared to version 1.4.5 without any changes, direct replacement of jar can be

### 1.4.5
**December 15, 2020:**
1. **New** New configuration to consume gold to refresh daily tasks

New in config.yml
```
# Refresh button
refresh:
  # The position to be displayed in the task gui
  index: 49
  # Whether to display
  enable: true
  # How many coins to spend, 0 is not consumed, Vault is required
  cost: 666
  # The number of refresh times per person per day, restart the server or refresh at 0:00 the next day
  times: 3
  # Button material
  material: MAP
```
New in language file:
```
# Refresh button log
refresh:
  name: "Refresh task"
  lore:
    - ''
    - '&f[ &c refresh description &f]'
    - ''
    - '&c&l>> Click the button to refresh today's task!'
    - '&c&l>> If the task has already been claimed and completed!'
    - '&c&l>> Cannot proceed to refresh!'
    - ''
    - '&c&l>> Refreshable times: &a${times}'
    - '&c&l>> Refresh price: &a${cost}'
    - ''
    - '&6>>&4>>&5>> &b${button} &6<<&4<<&5<<'
  refreshButton: "&6>>&4>>&5>> &bClick to refresh &6<&4<&5<<"
  noButton: "&6>>&4>>&5>> &c unable to refresh &6<&4<&5<<"
  # Command execution success alert
  successMsg: "&a task refresh successful"
  # Command execution failure alert
  failureMsg: "&a task refresh failed"
  notSufficientFunds: "$a balance is insufficient"
```

**1.4.5 Upgrade Assistant**
- Compared to 1.4.4 configuration file and language file have changed, suggest to regenerate

### 1.4.4
**November 27th, 2020:**
1. **New** New command /plk getip to get server ip
2. **New** New command/plk reload reload server configuration

**1.4.4 upgrade small assistant**
- Compared to 1.4.2, there is no change in the configuration file, just replace the jar directly

### 1.4.2
**November 17, 2020:**
1. **New** New command /plk delShop [ID] to delete items from mission coin store
2. **Optimized** More comprehensive display of Quest Coin Shop items

**1.4.2 upgrade small assistant**
- Suggest to regenerate the language file

### 1.4.1
**October 10, 2020:**
1. **New** New command /plk delToday Remove today's tasks and player tasks
2. **Optimized** now get daily tasks, is fixed at 00:00 pm to get

**1.4.1 Upgrade Assistant**
- Suggest to regenerate the language file

### 1.4.0
**October 8, 2020:**
1. **New** Now you can add quest type,kill normal monsters
2. **Optimization** I forgot what to optimize, but I submitted a bunch of stuff anyway

**1.4.0 upgrade assistant**
- Suggest to regenerate the language file

### 1.3.3
**August 26th, 2020:**
1. **Optimization** Now you can create kill missions directly by command
   Suppose we still want to create a mission objective - kill 5 zombie kings
   Step 1. Add a kill mission with a kill count of 5
````
/plk addDemand kill 5 SkeletalKnight
```
Finish

**1.3.3 Upgrade Assistant**
- Compared to 1.3.2, there is no change in the configuration file, just replace the jar directly

### 1.3.2
**August 21, 2020:**
1. **Fix the bug that /* /plk view list can't be opened with a kill type task error

**1.3.2 upgrade small assistant**
- Compared to 1.3.1 configuration file no change, directly replace the jar can be

### 1.3.1
**August 19, 2020:**
1. **Fix** vip permission display problem in open

**1.3.1 upgrade small assistant**
- Compared to 1.3.0 configuration file no change, directly replace the jar can be

### 1.3.0
**August 17, 2020:**
1. **New** task coin mall function, task coins are useful now
2. **New** vip privileges, players with corresponding privileges can get a custom multiplier of rewards
3. **Optimize** permission refinement

**1.3.0 upgrade assistant**
- The language file has changed, it is recommended to backup and regenerate it.
- config.yml has changed, suggest backup and regenerate

### 1.2.0
**August 7, 2020:**
1. **New** support for killing MythicMobs monster types
2. **New** /plk will appear help
3. **Optimized** Right click in /plk open will show more comprehensive quest objectives and quest rewards
4. **Optimized** More language type support [Optional Chinese Simplified:zh_CN;Chinese Traditional:zh_TW;English:en_US]

**1.2.0 Upgrade Assistant**
- The language file has changed, it is recommended to regenerate

### 1.1.5
**July 31, 2020:**
1. **Optimization** Optimization of version 1.7-1.12 Cloud Chinese and custom Chinese can be compatible to use together

**1.1.5 upgrade assistant**
- No change in other functions, just replace the jar directly

### 1.1.4
**July 29th, 2020:**
1. **Fixed** Giving item rewards can be non-normal stacking
2. **New** Quest rewards can now be customized with commands,
   Use # instead of spaces in the middle of the command, and use ${player} instead of spaces in the player variable
   For example:
```
# The player executes the command, the 0 in the middle means it is executed according to the player's identity, if the player doesn't have permission, the execution will fail
/plk addReward command 0 eco#give#${player}#666
# Players execute the command, the middle 1 means execute as op
/plk addReward command 1 eco#give#${player}#666
````

**1.1.4 Upgrade Assistant**
- Language file in languages Add command: "&f command" at line 50
- You can add it manually, or delete the language file and regenerate it

### 1.1.3
**July 28th, 2020:**
1. **Optimization** Improve compatibility with 1.7, no change in functionality, just replace the jar directly

### 1.1.2
**July 27, 2020:**
1. **optimize** the bug of duplicate registration commands, no change in functionality, just replace the jar directly

### 1.1.1
**July 26th, 2020:**
1. **optimize** jar package size, no change in functionality, just replace the jar directly

### 1.1.0
**July 26, 2020:** 1.
1. **Fix** The digging task is now invalid for precise collection
2. **Optimized** The item in the hand of the creation task reward and task target will only default to 1 now
3. **New** Send actionbar alerts when a mission is in progress (1.8+)
4. **New** Send title reminder when the task is completed (1.9+)
5. **New** task reward and task target and task list delete command
6. **New** You can view all current task list, all task reward list, all task target list in gui, and click to delete
7. **New** Now in the daily task list, you can preview the task target items, and task reward items if you right click
8. **New** search criteria in the quest target and quest reward gui
9. **New** mission objective type added **Consume** **Kill (not enabled)**
10. **Added** You can get today's task immediately by command

**1.1.0 Upgrade Assistant**
- Please make sure to delete the language file in languages and let it be generated automatically again

### 1.0.0
**July 22nd, 2020:**
1. This plugin is released