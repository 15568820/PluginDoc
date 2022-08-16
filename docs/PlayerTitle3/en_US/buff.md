### Add buff command

> /plt buff addBuff [title ID] [buff type] (buff attribute) -> add buff
> /plt buff deleteBuff [title ID] -> Remove the corresponding title buff

#### buff type is divided into :
* attribute_plus [MCBBS](https://www.mcbbs.net/thread-898670-1-1.html)
* sx_attribute [2.x](https://www.mcbbs.net/thread-793362-1-1.html) [3.x](https://www.mcbbs.net/thread-1083840-1-1.html)
* potion_effect Original potion
* MMOItems [MCBBS](https://www.mcbbs.net/thread-1104772-1-1.html)

### Example
Notes: # Instead of spaces
1. New: buff for attribute_plus
```
/plt buff addBuff 1 attribute_plus Physical damage:#100
```

2. New: buff for sx_attribute
```
/plt buff addBuff 1 sx_attribute Physical damage:#100
`` `

3. add: buff to potion_effect
```
/plt buff addBuff [title ID] potion_effect [potion_attribute] [potion_level] [show example true no,false show]
/plt buff addBuff 1 potion_effect ABSORPTION(damage absorption) 3 true
```` New: MMOItems

4. add: buff for MMOItems (must hold the item corresponding to MMOItems)
>You must be holding an item of type MMOItems and execute the following command  
Bind the attributes of this custom item to the title buff  
Please don't use **sword** type items, they are not valid, the default is to use the secondary hand type, you can try

Type is MMOItems  
type after the description &e this is the first line of introduction, &e this is the second line of introduction for the introduction English, split new line  
Note that the last description parameter can not be added, so directly will use the lore of MMO items as the title buff introduction
```
/plt buff addBuff [title ID] MMOItems (buff description)
/plt buff addBuff 1 MMOItems &eThis is the first line of introduction,&eThis is the second line of introduction for the introduction
or
/plt buff addBuff 1 MMOItems
```