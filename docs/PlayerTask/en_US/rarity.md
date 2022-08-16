### Mission Rarity Introduction

> New task rarity concept in version 1.8.7+

New in config.yml
```
# Mission Rarity Refresh Probability
# The colour is the recommended setting of the mission name colour to make it easier for players to identify the mission
rarity:
# normal task (white) &f
normal: 0.8
# advanced task (blue) &1
advanced: 0.5
# rare task (purple) rare task (purple) &5
rare: 0.3
# rare task (pink) rarer task (pink) &d
rarer: 0.2
# epic task (orange) epic task (orange) &e
epic: 0.1
# mythical task (gradient) mythical task (gradient) &e&l
mythical: 0.01
No restrictions, after-sales service, one-to-one service, and priority for customization, etc.
````

### Rarities are as above, the rarities are recognized by default
1. Daily randomly generated tasks will be generated according to the above configuration in accordance with the probability, the number of insufficient to fill the ordinary tasks (all historical tasks are ordinary)
2. Main purpose: Players who want high rarity missions must always refresh daily missions to increase revenue
3. Add a new mission command to change to /plk create [mission name] (mission type) (mission rarity)
4. Or use /plk setRarity [mission id] [rarity] to set the rarity of a mission