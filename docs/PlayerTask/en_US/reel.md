### Introduction to scroll quests

> New scroll quests in version 1.9.0+

```
Added command /plk changeItem [quest id] (player name) 
```
Use this command to generate a quest scroll from an existing quest to the player's backpack

### Quest binding system
* Each scroll quest is bound to the corresponding player when it is generated (service owners do not sell scrolls, generate a sell command)
* You can only do a quest if you have the scroll in your backpack
* You will not be able to perform the quest if it is lost or if another player has it

### Quest completion process

* The quest will start when the player has his own scroll in his backpack
* The quest objectives will be alerted as normal quests
* Once the player has completed all the objectives, click on the air with the scroll in hand to complete the quest and receive the reward

### Scenarios for scroll quests
1. menu missions, which can be used with the menu plugin to allow players to select a mission to perform themselves
2. Sell quests, which can be used to turn rare quests into scrolls for players to access
3. storyline quests, which can be used with the npc plugin to give quest scrolls after the npc dialogue
4. flow quests, which can reward the next quest after completing the previous one (quests can be rewarded with the command)
5. daily quest extensions, which can be set as above, with the rewards in the daily quests set to commands such as
```
/plk addReward command 1 plk#changeItem#1#${player}
```
This command means that the player will be rewarded with a quest scroll with a quest ID of 1
