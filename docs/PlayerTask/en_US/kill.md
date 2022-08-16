Kill mm monster description:
```1.
1. only MythicMobs monsters or normal monsters are supported for kill missions
2. a kill mission target can only choose one MythicMobs monster or normal monster
3. a mission is a combination of multiple mission targets
MythicMobs

## Hitting MythicMobs monsters Example
## First way: Using gui creation
Let's say we want to create a mission objective - kill 5 zombie kings

Step 1. Add a kill mission with a kill count of 5
````
/plk addDemand kill 5
```
Step 2, see the picture below and choose according to the gui you opened

## The second way: use the command to create directly
Suppose we still want to create a mission objective - kill 5 zombie kings

Step 1. Add the kill task, the number of kills required is 5
````
/plk addDemand kill 5 SkeletalKnight
```
Finish

## Kill normal monsters Example (based on monster type)
## Kill normal monsters quest

Step 1. Add the kill task, kill the zombie number required 1 specific monster name to see their own wiki
````
/plk addDemand killNormal 1 Zombie
```