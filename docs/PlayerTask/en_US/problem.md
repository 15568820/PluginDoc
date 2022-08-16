## Frequently Asked Questions

#### 1. Where do the daily random quests come from?

Before version 1.4.1
```.
The plugin will make a logical judgment every hour after it starts (as long as the daily task list has not been created today, it will keep judging)
1. the task was created
2. the number of tasks configured in config.yml is greater than 0
3. the daily task list is generated, and the task is given to all online players
4. when players are online, they will automatically get the daily task list, and those that have already been obtained will not be obtained again
5. daily random tasks theoretically refreshed between 0-1 (if you have created a task)
6. the available command /plk getToday will be executed once immediately to get, repeated execution will not be repeated to get
````
After version 1.4.1
```
Logical determination at 00:00 time to generate daily tasks
The first time the available command /plk getToday is configured, it will be executed once immediately and will not be repeated if repeatedly executed.
```
After version 1.6.0
```
The daily task will be generated automatically at 00:00 by logical judgement, and will only be extracted from those of type everyday
Use the /plk getToday command with caution, use this command to clear the previous player task data and regenerate today's random tasks (it will not affect the created task list)
For performance reasons, it now clears out all the old historical task data when generating a new daily task each day
```

After version 1.11.0
```
Daily quests will be automatically available when players log in to the game   
At 00:00, yesterday's tasks will be deleted and today's tasks will be re-generated  
(Only those of type EVERYDAY will be selected)
````

#### 2. Can't I Chineseize the quest requirements and reward items?
```
 Version 1.13+ will be Chineseized automatically
 Other versions are configured in item.json
 If you have not configured it, please make sure that each English word is correct (we recommend to use what items you want to Chineseize, add them here, and then reload the configuration file)
 
 Example:
 {
  "NAME_TAG": "name tag",
  "PAPER": "paper"
}
```

#### 3. Do you support mod items and custom items?

```
Support
```

#### 4. Mission rewards using custom commands
```
Use # instead of spaces in the middle of the command, and use ${player} instead of spaces in the player variable.
For example:
# The player executes the command, the 0 in the middle means it is executed according to the player's identity, if the player doesn't have permission it will fail
/plk addReward command 0 eco#give#${player}#666
# Players execute the command, the middle 1 means execute as op
/plk addReward command 1 eco#give#${player}#666
```

#### 5. How to submit a type of task
```
Middle mouse button
Plugin version 1.12.2+ is integrated into the left mouse button function
```

#### 6. NPC binding quest after clicking invalid
```
Please note the pvp status
World pvp ban or birth point protection etc. can't trigger events
```

#### 7. Refreshing tasks or insufficient number of tasks after the player enters the game
```
Reason: The number of daily tasks is too small, I suggest that the number of tasks for each rarity is set to more than 2 times the total number of tasks for today is more reasonable
In general, there is no need to deal with the situation, the player will automatically reenter the game to complete
```