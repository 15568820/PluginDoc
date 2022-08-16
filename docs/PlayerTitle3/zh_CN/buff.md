### 新增buff指令

>  /plt buff addBuff [称号ID] [buff类型] (buff属性)  -> 新增buff
>  /plt buff deleteBuff [称号ID]  -> 移除对应称号buff

#### buff类型分为:
* attribute_plus  [MCBBS](https://www.mcbbs.net/thread-898670-1-1.html)
* sx_attribute [2.x](https://www.mcbbs.net/thread-793362-1-1.html) [3.x](https://www.mcbbs.net/thread-1083840-1-1.html)
* potion_effect 原版药水
* MMOItems [MCBBS](https://www.mcbbs.net/thread-1104772-1-1.html)

### 例子 
注意事项: # 代替空格
1. 新增: attribute_plus 的buff
```
/plt buff addBuff 1 attribute_plus 物理伤害:#100
```

2. 新增: sx_attribute 的buff
```
/plt buff addBuff 1 sx_attribute 物理伤害:#100
```

3. 新增: potion_effect 的buff
```
/plt buff addBuff [称号ID] potion_effect [药水属性] [药水等级] [是否显示例子 true不显示,false显示]
/plt buff addBuff 1 potion_effect ABSORPTION(伤害吸收) 3 true
```

4. 新增: MMOItems 的buff (需手持MMOItems对应的物品)
>必须手持对应类型为MMOItems的物品执行下面指令  
绑定这个自定义物品的属性到称号buff里  
请不要使用**剑**类型的物品，无效的，默认是使用的副手类型，你可以试试

类型为MMOItems  
类型后面的描述 &e这是第一行介绍,&e这是第二行介绍为介绍 英文,分割换行  
注意，最后一个描述参数可以不加，这样直接会用mmo物品的lore作为称号buff介绍
```
/plt buff addBuff [称号ID] MMOItems (buff描述)
/plt buff addBuff 1 MMOItems &e这是第一行介绍,&e这是第二行介绍为介绍
或者
/plt buff addBuff 1 MMOItems
```