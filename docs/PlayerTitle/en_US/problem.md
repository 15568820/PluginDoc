## Frequently Asked Questions

#### 1. Error reported using mysql for storage
```
mysql version is too low, please use mysql5.7 or higher (version 2.7.5+ is fixed)
```
#### 2. Can't I Chineseize the shopping items in the Appellation Mall?
```
No.
 Version 1.13+ will be automatically Chineseized
 
 Other versions are configured in item.json
 According to the json format has been custom configuration can be configured, configured will automatically Chinese, if not configured will not, please strictly ensure that each English word correct (recommended to use what items on the Chinese what, add here, and then instructions to reload the configuration file can be)
 
 Example:
 {
  "NAME_TAG": "name tag",
  "PAPER": "paper"
}
```

Verify that the json you wrote is in the correct format: [click to go](https://www.json.cn/)

#### 3. 1.7 or 1.8 versions use garbled or unusable

```
Plugin default UTF-8, please convert to ANSI encoding by yourself
```

#### 4. Invalid tab title or unlimited header titles

```
isTab show tab title and header title this small function and scoreboard plug-in conflict
Solution: Turn off istab in config.yml and use a plug-in compatible with the variable (e.g., TAB) to display it
```

#### 5. modified the prefix and suffix in the config, did not take effect

```
Prefix suffix is directly bound in the generation of the title, so after changing the previous title is not valid, after the generation of the title will be effective. It is recommended to determine the desired prefix and suffix at the time of the first use
```

#### 6. Can you customize the title that no one else has within the species

```
Command:/plt add [title type] [title name] [amount] (days) (hidden or not) (player name)
Example:/plt add not &e custom title 0 0 false xiongliu
to specify the number of days, please modify the number of days 0 for the corresponding number of days can be, if you want other players can also buy, change false to true can be, other parameters and add a title consistent
After version 2.7.8, the new /plt addCustom command and /plt custom can customize the title
```

#### 7. I bought a title, how come the title store is gone? A one-time deal? How can others buy it?
```
The title store display is optimized.
The title store display optimization, the player has purchased the title to the player hidden, does not affect other players to view and buy
The title shop display is optimized.
```
#### 8. How can I delete a player's title?

```
/plt view open [player name]
```

#### 9. Deleted the title plugin, but the tab and header still show the title, 2.7.7+ has been fixed

```
Install a scoreboard plug-in for conflict, for example: TabListPro
conflict is complete delete it on the line
```

#### 10. Can I set multiple conditions to buy a title?

```
Yes, with the menu to achieve, or use the store to exchange title cards and such can be
```

#### 11. 2.x version how to delete or change the price of the title and other operations?

```
1.x version use /plt adminshop command  
2.x version use /plt view shop command or /plt adminshop command
```

#### 12. Is it possible to change the lore of the title shop and warehouse?

```
Yes, you can change the corresponding lore in the language file
```

#### 13. sx version issue raises an error (2.7.2+ is already compatible with both 2.x and 3.x of sx)

```
For example, this see SxAttribute without thinking that your sx version is not right
SxAttribute default support is sx3.x version, if you use the sx is 2.x please go to the web site to download the repair version compatible with sx low version

```

#### 14. particle effect does not show

```
1. check whether the front is normal at present there are SuperTrails or SuperTrailsPro or PlayerParticles
2. check if the client has enabled the particle display
3. the plugin completely prohibits any kind of hot loading, please restart
4. After adding the particles, please check if the title description is already there
5. after adding particles, please rewear the title to take effect
6. the particles are tested on spigot and paper side, please test them yourself on other side
7. check whether your instructions are used in accordance with the same document
8. don't use the same three colors of particle wings
9. check if there is any error reported in the background, if so, please provide
10. check whether the version is the latest, the particle plug-in version is normal
```

#### 15. 1.x version of the title upgrade 2.x version of the mall without the old title

```
1.x version upgrade to version 2.x Note (using sqlite storage ) !!!   
Please change the playerTitle.db file name to PlayerTitle.db first before upgrading
```

#### 16. How to delete a title owned by all players

```
1. The /plt del [id] command deletes the title and also deletes the title owned by the player
   or /plt adminShop to delete the corresponding title, both will automatically delete the title owned by the player
2. Use /plt add to add an identical title (optional)
```

### 17. How to use variables to display titles in MiaoChat plugin
config.yml configuration
```
### Configuration file version number Do not modify
Version: 1.8.5

#BC Cross-Service Mode
BungeeCord: false
#Current server name (variable is %mct_server%)
Server: '§a survival service'
#Formats list
Formats:
  #Format names
  default: 
    #priority (will be detected from smallest to largest, e.g. 1-50 priority detection 1 if it matches, show it if it doesn't, detection 2 ...)
    index: 50
    #Permissions
    permission: 'MiaoChat.default'
    #range (0 is no limit)
    range: 0
    #Chat format ([xxx] will call the corresponding format under format.yml)
    format: '[title] [player]&f: '
    #parse item(%i=>item in hand,%0-9 shortcut bar items)
    item: true
    #Item parsing rules
    itemformat: '&6[&b%s&6]&r'
  #Format name
  admin: 
    #priority (will be detected from smallest to largest, e.g. 1-50 priority detection 1 if it matches, show it if it doesn't match, detection 2 ...)
    index: 49
    #permissions
    permission: 'MiaoChat.admin'
    #Chat format ([xxx] will call the corresponding format under format.yml)
    format: '[title] [player]&f: '
    #range (0 is no limit)
    range: 0
    #parse items (%i=>items in hand,%0-9 items in shortcut bar)
    item: true
    #Item parsing rules
    itemformat: '&6[&b%s&6]&r'
```
format.yml configuration
```
#The current file is the base file for defining the format
player: 
  text: '&f%player_name%'
  tip: 
  - '&r
  - '&6▶ &eClick to send transfer request'
  click: 
    type: 'SUGGEST'
    command: '/tpa %player_name%'
title:
  text: '%playerTitle_use%'
  tip: 
  - '&8▪ &6 number of titles: %playerTitle_number%'
  - '&8▪ &6 number of title coins: %playerTitle_number%'
```

#### 18. isTab does not display properly when turned on, e.g. missing right bracket

```
1.12 and below server titles longer than 16 bits will be intercepted
1.13+ server length more than 64 bits will be intercepted
The color code also counts as length, and is part of the mc mechanism itself
```

#### 19. purchase type is item is compatible with mod items

```
Test yourself, most mods are compatible
But do not exclude a very few special mod incompatible, welcome feedback
```

#### 20. MiaoChat is not compatible with the RGB color designation variable
```
No help, miaoChat design flaws Please replace the use of trchat, which supports
```

#### 21. 1.13 below the server material Chinese is not normal
```
For example, clown fish become puffer fish (no help, because their materials are FISH, can not be identified)
Please do not use such items or can guide the player to right-click to see the required items
```