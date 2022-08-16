## Permissions
##### This plugin does not require any permissions to be configured by default, the service owner can use it out of the box
##### Many of the following types are not known. Please use the tab to remind you of low versions, 1.12 or above will be automatically reminded.

| Permissions               | Usage                                                    | Default owner   |
|---------------------------|----------------------------------------------------------|-----------------|
| playerTask.addList        | Add task                                                 | op              |
| playerTask.addDemand      | Add task target                                          | op              |
| playerTask.addReward      | Add a new task reward                                    | op              |
| playerTask.addShop        | Add a new task shop item                                 | op              |
| playerTask.open           | Daily quest gui                                          | op              |
| playerTask.shop           | Task Shop gui                                            | op              |
| playerTask.create         | Create a task                                            | op              |
| playerTask.delete         | Delete a task                                            | op              |
| playerTask.view           | Manage Tasks                                             | op              |
| playerTask.vip            | vio permissions                                          | op              |
| playerTask.getToday       | Get today's tasks now                                    | op              |
| playerTask.delToday       | Clear today's task list and all players' tasks (1.4.1+)  | op              |
| playerTask.delShop        | Delete the shop item with the corresponding id           | op              |
| playerTask.reload         | reload configuration                                     | op              |
| playerTask.edit           | Edit task (1.7.1+)                                       | op              |
| playerTask addNpcTask     | Adding npc tasks (1.6.0+)                                | op              |
| playerTask delNpcTask     | DeleteNpcTask(1.6.0+)                                    | op              |
| playerTask.setRarity      | Edit Task Rarity (1.8.7+)                                | op              |
| playerTask.changeItem     | Generate quest scrolls (1.9.0+)                          | op              |
| playerTask setDescription | add task description (1.9.7+)                            | op              |
| playerTask.coin           | Operation Player Mission Coins (1.13.2+)                 | op              |

## Command (Admin):
| command                                                                                                                         | usage                                                                                                        |
|---------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| /plk addDemand [target type] [number]                                                                                           | Add quest target (requires main hand to have item)                                                           |
| /plk addReward [reward type] [number]                                                                                           | Add a reward (if the reward type is an item, the master must have the corresponding item in hand)            |        
| /plk addShop [type] [price]                                                                                                     | Add Quest Shop item rewards (type: once: once; unlimited: infinite)                                          |
| /plk addReward [type] [price]                                                                                                   | Add Quest Shop item rewards (type: once: once; unlimited)                                                    |
| /plk create [quest name] (quest type) (quest rarity)                                                                            | Use gui to create tasks (recommended)                                                                        |
| /plk addList [task name] [title target id] [task reward id]                                                                     | Add a task using the command method                                                                          |
| /plk delete [type] [corresponding id]                                                                                           | Use the command to delete a quest, quest target, quest reward                                                |
| /plk view [type]                                                                                                                | Use the gui to view and manage types, [list:task,demand:task target,reward:task reward, e.g.: /plk view list |
| /plk getToday                                                                                                                   | Execute a get today task immediately                                                                         |
| /plk delToday                                                                                                                   | Clear today's task list and all players' tasks (1.4.1+)                                                      |
| /plk delShop [Corresponding ID]                                                                                                 | Deletes the Quest Coin Shop item with the corresponding id                                                   |
| /plk getIp                                                                                                                      | Get ip                                                                                                       |
| /plk reload                                                                                                                     | reload configuration                                                                                         |
| /plk edit [task id]                                                                                                             | Use gui to edit tasks (1.7.1+)                                                                               |
| /plk addNpcTask [task id] [npcId] [whether task is permanent] [number of completions possible] [cooldown] (predecessor task id) | addNpcTask(1.6.0+)                                                                                           |
| /plk delNpcTask [npcId]                                                                                                         | Remove npc task (1.6.0+)                                                                                     |
| /plk setRarity [task id] [rarity]                                                                                               | Edit task rarity (1.8.7+)                                                                                    |
| /plk changeItem [quest id] (player name)                                                                                        | Generate quest scroll (1.9.0+)                                                                               |
| /plk setDescription [task id] [task description]                                                                                | Add task description (1.9.7+)                                                                                |
| /plk coin [Type] [Player Name] [Number]                                                                                         | Operation Player Mission Coins (1.13.2+)                                                                     |

## Command (Player):
| command    | use                       |
|------------|---------------------------|
| /plk open  | Opens the daily quest gui |
| /plk shop  | open quest coin mall gui  |

### The currently supported task target types are as follows
```
craftItem 
BlockBreak 
Fish 
Interact 
Kill 
consume 
killNormal 
submit 
killPlayer (1.13.3+)
enchantment (1.13.3+)
```

### The currently supported mission reward types are as follows
```
vault 
playerPoints 
coin 
itemStack 
command 
```

Translated with www.DeepL.com/Translator (free version)


```
# The player executes the command, the 0 in the middle means it is executed according to the player's identity, if the player does not have permission it will fail.
/plk addReward command 0 eco#give#${player}#666
# Players execute the command, a 1 in the middle means it is executed as an op
/plk addReward command 1 eco#give#${player}#666
```

> Task types are divided into everyday (daily tasks) npc (NPC tasks) Not interchangeable
