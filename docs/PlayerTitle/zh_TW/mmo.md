### MMOItems buff

> PlayerTitle-2.8.2+版本開始 增加兼容MMOItems  
> 基於 MMOItems6.6.0 開發

1. 新增一個稱號
```
/plt add not &f測試mmo稱號 0
```
假如新增成功返回的稱號id為1

2. 新增稱號mmoItem buff

必須手持對應類型為MMOItems的物品執行下面指令  
綁定這個自定義物品的屬性到稱號buff裏  
請不要使用**劍**類型的物品，無效的，默認是使用的副手類型，你可以試試

類型為MMOItems  
類型後面的描述 &e這是第一行介紹,&e這是第二行介紹為介紹 英文,分割換行  
註意，最後一個描述參數可以不加，這樣直接會用mmo物品的lore作為稱號buff介紹

```
/plt setTitleBuff 1 MMOItems &e這是第一行介紹,&e這是第二行介紹
```
或者
```
/plt setTitleBuff 1 MMOItems
```