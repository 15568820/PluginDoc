<!-- docs/PlayerTitle/zh_CN/command.md -->

## 權限
##### 本插件默認無需配置任何權限,服主開箱即用
##### 很多下面涉及都類型不知道的 低版本請使用tab提醒,1.12以上會自動提醒

# 2.x版本

## 具體權限
|  權限 | 用途  | 默認擁有者 |
| ------------ | ------------ | ------------ |
| playertitle.addcoin  | 給玩家添加稱號幣  | op |
| playertitle.add  | 添加一個新稱號到稱號商城 | op |
| playertitle.addpermission  | 添加一個權限稱號 | op |
| playertitle.addplayertitle  | 直接給玩家稱號 | op |
| playertitle.addreward  | 給對應數量的稱號添加獎勵 | op |
| playertitle.changeitem  | 將對應id的稱號轉換成右鍵可使用的物品 | op |
| playertitle.randomcard  | 獲取一個隨機稱號卡 | op |
| playertitle.reload  | 重載插件 | op |
| playertitle.set  | 給玩家設置對應天數的稱號 | op |
| playertitle.settitlebuff  | 給稱號添加buff屬性 | op |
| playertitle.subtractcoin  | 給玩家減少稱號幣 | op |
| playertitle.view  | 查看對應gui並管理 | op |
| playertitle.getIp  | 查詢服務器ip | op |
| playertitle.shop  | 打開稱號商城gui | 全部 |
| playertitle.open  | 打開稱號倉庫gui | 全部 |
| playertitle.settitleparticle  | 給稱號添加粒子效果 | op |
| playertitle.removetitleparticle  | 刪除稱號粒子效果 | op |
| playertitle.setdescription  | 給稱號添加描述 | op |
| playertitle.listtitle  | 查詢全部稱號 | op |
| playertitle.adminshop  | 管理稱號商城 | op |
| playertitle.delbuff  | 刪除buff | op |
| playertitle.convert  | 轉換數據源 | op |
| playertitle.custom| 玩家自定義稱號 | 所有|
| playertitle.setCustom| 設置玩家可以自定義稱號次數 |op|
| playertitle.del| 刪除稱號 |op|

## 指令(管理員):
|  指令 | 用途  |
| ------------ | ------------ |
| /plt addcoin [玩家名稱] [金額] | 給玩家添加稱號幣  |
| /plt add [稱號類型] [稱號名稱] [金額] (天數) (是否隱藏) (玩家名) | 添加一個新稱號到稱號商城 |
| /plt addpermission [稱號名稱] [需要權限]  | 添加一個權限稱號 |
|/plt addPlayerTitle [玩家名稱] [稱號名稱] (天數)  |直接新增一個隱藏的稱號,並把這個稱號給對應玩家,天數如果不填默認永久|
| /plt addreward [稱號數量] [類型] [金額]  | 給對應數量的稱號添加獎勵 |
| /plt changeitem  [稱號id] [天數] [數量] (玩家名稱)   | 將對應id的稱號轉換成右鍵可使用的物品 |
| /plt randomcard [天數] (類型)  | 獲取一個隨機稱號卡 | 
| /plt reload  | 重載插件 |
| /plt set [玩家名稱] [稱號ID] [天數] | 給玩家設置對應天數的稱號 |
| /plt settitlebuff [稱號id] [類型] [屬性標簽]   | 給稱號添加buff屬性 |
| /plt subtractcoin [玩家名稱] [金額]  | 給玩家減少稱號幣 | 
| /plt view [類型] (玩家名)   | 查看對應gui並管理類型: shop; open;  reward|
| /plt shop  | 打開稱號商城gui | 
| /plt open  | 打開稱號倉庫gui | 
| /plt getId  | 查看服務器ip | 
|/plt setTitleParticle [稱號id] [粒子類型] [粒子id] (顏色) (顏色) (顏色)|給稱號添加粒子效果|
|/plt removeTitleParticle [稱號id]|刪除稱號粒子效果|
| /plt setDescription [稱號id] [稱號描述] | 給稱號添加描述|
| /plt listTitle [頁數]   | 查詢服務器稱號列表  |
| /plt adminShop   |  打開管理稱號商城gui(修改或者刪除稱號用) |
| /plt delBuff [buffid]   |  刪除對應buffid的buff效果 |
|/plt convert [類型] | 轉換數據源，類型mysql或者sqlite|
|/plt custom [稱號名稱]| 設置自定義稱號gui |
|/plt setCustom [玩家名稱] [可自定義次數] | 設置玩家可以自定義的次數 |
|/plt del [id] | 指令刪除稱號，同時會刪除玩家擁有的該稱號 |

|[]為必填參數;()為非必填參數|

```
刪除稱號請輸入/plt view shop 或者/plt adminShop查看
涉及到 是否的  都是傳 true/false

/plt view open [玩家名] 可以對玩家的稱號刪除

/plt settitlebuff [稱號id] [類型] [屬性標簽]
setTitleBuff 的類型包含：
1. attribute_plus: "ap屬性" [需要前置 AttributePlus]
2. sx_attribute: "sx屬性" [需要前置 SX-Attribute]
3. monster_truce: "怪物休戰" 
4. potion_effect: "藥水效果"
5. player_intensify: "強化效果" [需要前置 PlayerIntensify]

屬性標簽 例如： 物理傷害:100 如果需要空格可以用#替換

例子：
/plt settitlebuff 1 attribute_plus &e物理傷害:#&c100
/plt settitlebuff 1 sx_attribute &e物理傷害:#&c100
/plt settitlebuff 1 monster_truce all
/plt setTitleBuff 1 potion_effect [藥水類型] [藥水等級] [是否顯示粒子效果]
藥水類型請tab提醒
/plt settitlebuff 1 player_intensify &e增加強化概率:6
```

## 指令(玩家):
|  指令 | 用途  |
| ------------ | ------------ |
| /plt shop   |  打開稱號商城gui |
| /plt open    |  打開稱號倉庫gui |
|/plt custom [稱號名稱]| 設置自定義稱號gui |