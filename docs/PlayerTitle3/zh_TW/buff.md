### 新增buff指令

>  /plt buff addBuff [稱號ID] [buff類型] (buff屬性)  -> 新增buff
>  /plt buff deleteBuff [稱號ID]  -> 移除對應稱號buff

#### buff類型分為:
* attribute_plus  [MCBBS](https://www.mcbbs.net/thread-898670-1-1.html)
* sx_attribute [2.x](https://www.mcbbs.net/thread-793362-1-1.html) [3.x](https://www.mcbbs.net/thread-1083840-1-1.html)
* potion_effect 原版藥水
* MMOItems [MCBBS](https://www.mcbbs.net/thread-1104772-1-1.html)

### 例子
註意事項: # 代替空格
1. 新增: attribute_plus 的buff
```
/plt buff addBuff 1 attribute_plus 物理傷害:#100
```

2. 新增: sx_attribute 的buff
```
/plt buff addBuff 1 sx_attribute 物理傷害:#100
```

3. 新增: potion_effect 的buff
```
/plt buff addBuff [稱號ID] potion_effect [藥水屬性] [藥水等級] [是否顯示例子 true不顯示,false顯示]
/plt buff addBuff 1 potion_effect ABSORPTION(傷害吸收) 3 true
```

4. 新增: MMOItems 的buff (需手持MMOItems對應的物品)
>必須手持對應類型為MMOItems的物品執行下面指令  
綁定這個自定義物品的屬性到稱號buff裏  
請不要使用**劍**類型的物品，無效的，默認是使用的副手類型，你可以試試

類型為MMOItems  
類型後面的描述 &e這是第一行介紹,&e這是第二行介紹為介紹 英文,分割換行  
註意，最後一個描述參數可以不加，這樣直接會用mmo物品的lore作為稱號buff介紹
```
/plt buff addBuff [稱號ID] MMOItems (buff描述)
/plt buff addBuff 1 MMOItems &e這是第一行介紹,&e這是第二行介紹為介紹
或者
/plt buff addBuff 1 MMOItems
```