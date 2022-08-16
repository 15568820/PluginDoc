## Example
Description:
```
The logic of npc quests is:
1. first you add a new npc quest out as in example 1
/plk create NpcTask npc normal
2. then use the command to bind to the corresponding npc
````
Suppose we already have an npc task, as shown in the figure, of type npc task

At this point we look at the Citizen Citizens plugin npc list

You can see that there are three npc, 0,1,2

### Enter the command to bind
2021-02-06 18:39:20 Saturday
```
command: 
/plk addNpcTask [task id] [npcId] [permanent task or not] [number of completions] [cooldown] (predecessor task id)

Example: 
/plk addNpcTask 23 2 1 0 60

Explanation:
Bind the task with Id 23 to npc2, set it to 1, which means the permanent recurring task, followed by 0, which is the number of times the task can be completed (the previous parameter is set to 0 to take effect), 60 is the cooldown time, the pre-task id can not be passed, there is no pre-task by default, if you need to have a pre-task, pass the corresponding task id.
````

### The effect of the above a operation

### how to view the npc bound tasks
```
/plk view npc

Note: Clicking on delete will delete the quests that the player has received as well
```

[![4oeTD1.png](https://z3.ax1x.com/2021/09/30/4oeTD1.png)](https://imgtu.com/i/4oeTD1)
[![4oe7Hx.png](https://z3.ax1x.com/2021/09/30/4oe7Hx.png)](https://imgtu.com/i/4oe7Hx)
[![4oebE6.png](https://z3.ax1x.com/2021/09/30/4oebE6.png)](https://imgtu.com/i/4oebE6)
[![4oeL4O.png](https://z3.ax1x.com/2021/09/30/4oeL4O.png)](https://imgtu.com/i/4oeL4O)

