## Permissions
##### The default of this plug-in does not need to configure any permissions, service owners out of the box
##### Many of the following types involved do not know the low version, please use the tab reminder, more than 1.12 will automatically remind

# 2.x version

## specific permissions
| Permissions | Usage | Default owner |
| ------------ | ------------ | ------------ |
| playertitle.addcoin | Add title coins to player | op |
| playertitle.add | Add a new title to the Title Store | op |
| playertitle.addpermission | Add a permission title | op |
| playertitle.addplayertitle | Give a title directly to a player | op |
| playertitle.addreward | Add a reward to the corresponding number of titles | op |
| playertitle.changeitem | Convert a title with the corresponding id to a right-clickable item | op |
| playertitle.randomcard | Get a random title card | op |
| playertitle.reload | reload plugin | op |
| playertitle.set | Set the player's title for the corresponding number of days | op |
| playertitle.settitlebuff | Add a buff attribute to a title | op |
| playertitle.subtractcoin | reduce coins for players | op |
| playertitle.view | View the corresponding gui and manage it | op |
| playertitle.getIp | Query server ip | op |
| playertitle.shop | Open the title shop gui | all |
| playertitle.open | Open the title store gui | all |
| playertitle.settitleparticle | Add a particle effect to a title | op |
| playertitle.removetitleparticle | removetitleparticle | op
| playertitle.setdescription | Add a description to a title | op |
| playertitle.listtitle | Query all titles | op |
| playertitle.adminshop | Manage title shop | op |
| playertitle.delbuff | Delete buffs | op |
| playertitle.convert | convert data source | op |
| playertitle.custom| Player Custom Titles | all |
| playertitle.setCustom| Set the number of times a player can customize a title |op|
| playertitle.del| Delete a title |op|

## Command (Admin):
|command |usage |
| ------------ | ------------ |
| /plt addcoin [player name] [amount] | Add title coin to player |
| /plt add [title type] [title name] [amount] (days) (hidden or not) (player name) | Add a new title to the title store |
| /plt addpermission [title name] [requires permission] | Add a permission title |
| /plt addPlayerTitle [player name] [title name] (days) | Add a new hidden title directly to the player, and give the title to the corresponding player, if not fill in the number of days default permanent|
| /plt addreward [number of titles] [type] [amount] | Add rewards to the corresponding number of titles |
| /plt changeitem [title id] [number of days] [quantity] (player name) | convert the title with the corresponding id into a right clickable item |
| /plt randomcard [days] (type) | Get a random title card | 
| /plt reload | Reload the plugin |
| /plt set [player name] [title ID] [number of days] | Set the player's title to the corresponding number of days |
| /plt settitlebuff [title id] [type] [attribute tag] | Add buff attributes to the title |
| /plt subtractcoin [player name] [amount] | Subtract coins from the title for the player | 
| /plt view [type] (player name) | View the corresponding gui and manage the type: shop; open; reward|
| /plt shop | Open the title shop gui | 
| /plt open | Open the title store gui | 
| /plt getId | View server ip | 
| /plt setTitleParticle [title id] [particle type] [particle id] (color) (color) (color)|Add a particle effect to a title|
| /plt removeTitleParticle [title id]|Remove title particle effect|
| /plt setDescription [title id] [title description] | Add a description to a title|
| /plt listTitle [page] | Query the list of server titles |
| /plt adminShop | Open the admin title mall gui (for modifying or deleting titles) |
| /plt delBuff [buffid] | Delete the buff effect corresponding to the buffid |
|/plt convert [type] | Convert data source, type mysql or sqlite|
|/plt custom [title name]| Set custom title gui |
|/plt setCustom [player name] [customizable times] | Set the number of times a player can customize |
|/plt del [id] | The command to delete a title will also delete the title the player has.

|[] is a required parameter; () is a non-required parameter|

```
To delete the title, please enter /plt view shop or /plt adminShop to view
Pass true/false when it comes to whether

/plt view open [player name] can delete the player's title

/plt settitlebuff [title id] [type] [attribute tag]
The type of setTitleBuff contains.
1. attribute_plus: "ap attribute" [requires prefix AttributePlus]
2. sx_attribute: "sx attribute" [requires prefix SX-Attribute]
3. monster_truce: "monster truce" 
4. potion_effect: "Potion effect" 5.
5. player_intensify: "Intensify effect" [Requires previous PlayerIntensify]

Attribute tag e.g.: physical_damage:100 If you need a space you can replace it with #

Example
/plt settitlebuff 1 attribute_plus &e physical damage:#&c100
/plt settitlebuff 1 sx_attribute &ePhysical damage:#&c100
/plt settitlebuff 1 monster_truce all
/plt setTitleBuff 1 potion_effect [potion type] [potion level] [whether to show particle effect]
Potion type please tab reminder
/plt settleTitlebuff 1 player_intensify &e increases the probability of reinforcement:6
```

## Command (player):
| command | use |
| ------------ | ------------ |
| /plt shop | Open title shop gui |
| /plt open | Open title store gui |
| /plt custom [title name]| set custom title gui |