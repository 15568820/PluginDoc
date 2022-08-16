### MMOItems buff

> PlayerTitle-version 2.8.2+ started to add MMOItems compatibility  
> Based on MMOItems6.6.0 development

1. add a new title
```
/plt add not &f test mmo title 0
```
If the title id returned by the successful addition is 1

2. Add a title mmoItem buff

The following command must be executed with an item of the corresponding type MMOItems  
Bind the properties of this custom item to the title buff  
Please do not use **sword** type items, it is invalid, the default is to use the vice type, you can try

Type is MMOItems  
type after the description &e this is the first line of introduction, &e this is the second line of introduction for the introduction English, split new line  
Note that the last description parameter can not be added, so directly will use the lore of MMO items as the title buff introduction

```
/plt setTitleBuff 1 MMOItems &eThis is the first line of introduction, &eThis is the second line of introduction
```
or
```
/plt setTitleBuff 1 MMOItems
```