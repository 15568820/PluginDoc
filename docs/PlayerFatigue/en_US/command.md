## Permissions
##### This plug-in default does not need to configure any permissions, the owner of the service out of the box that use
##### a lot of the following types involved do not know the low version, please use the tab reminder, 1.12 or more will automatically remind
| Permissions | Usage | Default owner |
| ------------ | ------------ | ------------ |
| playerfatigue.setblock | Set the specified block | op |
| playerfatigue.give | Give player fatigue | op |
| playerfatigue.take | Reduce player fatigue | op |
| playerfatigue.set | set player fatigue | op |
| playerfatigue.setMax | Set the player's maximum fatigue value | op |
| playerfatigue.addMax | add player's maximum fatigue | op |
| playerfatigue.vip | vip rights | op |
| playerfatigue.viewblock | View the specified block | op |
| playerfatigue.reload | reload plugin | op |

## Command:
| command | usage |
| ------------ | ------------ |
|/plf setBlock [type] [requiresFatigue] | Add a block that consumes Fatigue"|
| /plf give [player name] [number] | Increase player fatigue value"|
| /plf take [player name] [number] | Decrease player fatigue"|
| /plf set [player name] [number] | set player fatigue value"|
| /plf setMax [player name] [number] | set the player's maximum fatigue value"|
| /plf addMax [player name] [number] | add player's maximum fatigue value"|
| /plf viewblock | View set the specified square |
| /plf reload | reload plugin"|

```
Type is divided into: mining (break) synthesis (craftItem)
Example: Handheld diamond mine input
/plf setBlock break 1
It is to let the player dig the diamond mine with a little fatigue value
```

Translated with www.DeepL.com/Translator (free version)