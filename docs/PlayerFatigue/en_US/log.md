## Version information


### Known bugs (currently known but unresolved bugs will be displayed here in one place)
- None

#### If you encounter errors, or plug-in conflicts and other problems, please add the group feedback

------------
#### 1.4.0
**December 01, 2021**
1. **Optimisation** Better adaptation to 1.18

#### 1.4.0 update small helper
- No changes to the configuration file compared to version 1.3.8, just replace the jar directly

### 1.3.8
**09/13/2021**
1. **Optimization** Optimization code

#### 1.3.8 update small assistant
No changes compared to 1.3.7, just replace the jar directly

### 1.3.7
**08/07/2021**
1. **Optimization** Now the real player name will be stored in the database, the historical data player login will be automatically synchronized off
2. **Fix** mysql /plf viewBlock can't be viewed
3. **Fix an exception with /* /plf give command

#### 1.3.7 update small assistant
No change compared to 1.3.6, just replace the jar directly

### 1.3.6
**06/08/2021**
1. **Optimization** Optimization code

#### 1.3.6 update small helper
No changes compared to 1.3.5, just replace the jar directly

### 1.3.5
**08/01/2021**
1. **Fix** sqlite /plf viewBlock cannot be viewed

#### 1.3.5 update small helper
No changes compared to 1.3.4, just replace the jar directly

### 1.3.4
**24 July 2021**
1. **Fix** give command can give more than the maximum strength problem
2. **Fix** addMax repeat execution invalid issue
3. **Optimize** code structure

#### 1.3.4 update small assistant
No change compared to 1.3.3, just replace the jar directly

### 1.3.3
**July 03, 2021**
1. **new** command /plf convert mysql(convert sqlite data to mysql)
2. **New** command/plf convert sqlite(convert mysql data to sqlite)
> Please try to convert when no player is online, and restart the server after the conversion operation.
3. **Optimization** Improve the serialization of custom item storage
4. **Optimization** Compatible with 1.17

#### 1.3.3 update small assistant
Language file has content update (mainly add command help), suggest to regenerate

### 1.3.2
**January 27, 2021**
1. **Fix** some fatal errors caused by type

#### 1.3.2 update small helper
No changes compared to 1.3.1, just replace the jar directly

### 1.3.1
**January 25, 2021**
1. **Fix the problem that ** api can't get the current fatigue value

#### 1.3.1 update small assistant
The language file has content update,suggest to regenerate

### 1.3.0
**December 24, 2020**
1. **Added** New command   
   /plf addMax [player name] [number] increases the player's maximum fatigue value in stages

#### 1.3.0 update small assistant
The language file has updated content, suggest to regenerate

### 1.1.6
**November 19, 2020**
1. **New** Now you need to add the type when creating a block, currently supports synthesis and excavation two types
````
The types are divided into: mining (break) synthesis (craftItem)
For example: hand held diamond mine input
/plf setBlock break 1
is to let the player dig the diamond mine when consuming a little fatigue value
````

#### 1.1.6 update assistant
The language file has been updated, it is recommended to regenerate it

### 1.1.5
**November 17, 2020**
1. **optimized** plugin completely free
2. **Fix** MaxFatigue variable %PlayerFatigue_maxFatigue% modified to %PlayerFatigue_maxfatigue%

#### 1.1.5 update small assistant
Just replace the jar directly

### 1.1.4
**September 10, 2020**
1. **Optimization** Add cache button,improve performance

#### 1.1.4 update small helper
The following content has been added to config.yml: please add it yourself, or regenerate it
````
# Whether to enable caching
# It is recommended to turn on caching for a single service
# For group services, it is recommended to turn it off during the configuration phase, and then turn it on when the configuration will not change for a long time to improve performance
isCache: true
``` ### 1.1.3

### 1.1.3
**August 31, 2020** 1.
1. **Added** Timed tasks to switch between resuming online or offline player configurations

#### 1.1.3 update small assistant
The following content has been added to config.yml: please add it yourself, or regenerate it
````
# timingOfflineRecovery: false: players will recover only if they are online true: all players will recover (including offline)
timingOfflineRecovery: false
# Whether to turn on the timing recovery mode, when the time is set, all players will be recovered directly,
# The time will be restored online or offline according to the above configuration
timingRecovery: false
# The recovery time of the timing recovery mode
timing: 00:00
````

### 1.1.2
**August 31, 2020** 1.
1. **New** Timed recovery function, you can set a certain time point to recover full strength directly
2. **Optimize** the problem of fatigue value exceeding the upper limit in extreme cases

#### 1.1.2 update small assistant
The following content has been added to config.yml: please add it yourself or regenerate it
````
# Whether to turn on the timer recovery mode, when the time is set, it will directly restore all the stamina,
# According to the above configuration to decide whether to resume online or offline
timingRecovery: false

# The recovery time of the timing recovery mode
timing: 00:00
````

### 1.1.1
**August 22nd, 2020:**
1. **Optimization** Optimized the code to avoid possible fatigue breaking the cap

#### 1.1.1 update small assistant
Just replace the jar directly

### 1.1.0
**August 17, 2020:**
1. **Optimization** Now you can switch whether to use ActionBar to show fatigue consumption in config.yml
2. **Optimization** Removed redundant enchantment display on the view set cube page

#### 1.1.0 update small assistant
The config.yml and language files have been updated, it is recommended to read the documentation to add or delete and regenerate.

### 1.0.0
**August 14, 2020:**
1. This plug-in release
