### MMOItems buff

> PlayerTitle-2.8.2+版本开始 增加兼容MMOItems  
> 基于 MMOItems6.6.0 开发

1.新增一个称号
```
/plt add not &f测试mmo称号 0
```
假如新增成功返回的称号id为1

2. 新增称号mmoItem buff

必须手持对应类型为MMOItems的物品执行下面指令  
绑定这个自定义物品的属性到称号buff里  
请不要使用**剑**类型的物品，无效的，默认是使用的副手类型，你可以试试

类型为MMOItems  
类型后面的描述 &e这是第一行介绍,&e这是第二行介绍为介绍 英文,分割换行  
注意，最后一个描述参数可以不加，这样直接会用mmo物品的lore作为称号buff介绍

```
/plt setTitleBuff 1 MMOItems &e这是第一行介绍,&e这是第二行介绍
```
或者
```
/plt setTitleBuff 1 MMOItems
```