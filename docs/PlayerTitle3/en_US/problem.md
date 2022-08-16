## Frequently Asked Questions

#### 1. Can't I Chineseize the shopping items in the Appellation Mall?

```
No.
Version 1.13+ will be Chineseized automatically

Other versions are configured in item.json
According to the json format has been custom configuration can be, configured will automatically Chinese, if not configured will not, please strictly ensure that each English word correct (recommended to use what items on the Chinese what, add here, and then instructions to reload the configuration file can be)

Example:
{
"NAME_TAG": "name tag",
"PAPER": "paper"
}
```

Verify that the json you wrote is in the correct format: [click to go](https://www.json.cn/)


#### 2. 1.7 or 1.8 versions use garbled or unusable

```
Plugin default UTF-8, please convert to ANSI encoding by yourself
```

#### 3. Invalid tab title or unlimited header titles

```
isTab show tab title and header title this small function and scoreboard plug-in conflict
Solution: Turn off istab in config.yml and use a plug-in compatible with the variable (e.g., TAB) to display it
```

#### 4. modified the prefix and suffix in the config, did not take effect

```
Prefix suffix is directly bound in the generation of the title, so after changing the previous title is not valid, after the generation of the title will be effective. It is recommended to determine the desired prefix and suffix at the time of the first use
I'm not sure if I'm going to be able to use it.
```

#### 5. I bought the title, how come the title store is gone? A one-time thing? How can others buy it?

```
The title store display is optimized.
The title store display optimization, the player has purchased the title to the player hidden, does not affect other players to view and buy
```

#### 6. How can I delete a player's title?

```
/plt view open [player name]
```

#### 7. Deleted the title plugin, but the tab and header still show the title, 2.7.7+ has been fixed

```
Install a scoreboard plug-in for conflict, for example: TabListPro
conflict is complete delete it on the line
```

#### 8. Can I set multiple conditions to buy a title?

```
Yes, with the menu to achieve, or use the store to exchange the title card can be such
```

#### 9. How can I delete or change the price of a title?

```
/plt view shop command
```

#### 10. Is it possible to change the lore of the title shop and warehouse?

``` 
The lore can be changed in the language file.
Yes, you can change the corresponding lore in the language file
```

#### 11. The particle effect is not displayed

```
1. Check if the front-end has SuperTrails or SuperTrailsPro or PlayerParticles loaded successfully
2. check if the client has enabled the particle display
3. The plugin completely disables any kind of hot loading, please restart it
4. After adding the particles, please check if the title description is already available
5. After adding particles, please rewear the title to take effect
6. the particles are tested on spigot and paper side, please test them yourself on other side
7. check whether your instructions are used in accordance with the same document
8. don't use the same three colors of particle wings
9. check if there is any error reported in the background, if so, please provide
10. check whether the version is the latest, the particle plug-in version is normal
````

#### 12. isTab is not displayed properly after opening, such as the lack of right bracket

```
1.12 and the following versions of the server title length more than 16 bits will be intercepted
1.13+ server length more than 64 bits will be intercepted
The color code also counts as length, which belongs to the mc mechanism itself
````

#### 13. purchase type is item is compatible with mod items

```
Test yourself, most mods are compatible
But do not exclude a very few special mod incompatible, welcome feedback
```

#### 14. 1.13 below the server material Chinese is not normal

```
The following server material is not normal
For example, clown fish become puffer fish (no help, because their materials are FISH, can not be identified)
Please do not use such items or can guide the player to right-click to see the required items
```