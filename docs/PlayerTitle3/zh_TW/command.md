## 權限

##### 本插件默認無需配置任何權限,服主開箱即用

##### 很多下面涉及都類型不知道的 低版本請使用tab提醒,1.12以上會自動提醒

# 3.x版本

## 具體權限

| 權限                    | 用途             | 默認擁有者  |
|-----------------------|----------------|--------|
| playerTitle.addReward | 添加稱號數量獎勵       | op     |
| playerTitle.buff      | 稱號buff相關       | op     |
| playerTitle.card      | 稱號卡相關          | op     |
| playerTitle.coin      | 稱號幣相關          | op     |
| playerTitle.convert   | 轉換數據庫          | op     |
| playerTitle.getIp     | 獲取服務器信息        | op     |
| playerTitle.particle  | 稱號粒子相關         | op     |
| playerTitle.player    | 玩家稱號相關         | op     |
| playerTitle.reload    | 重載插件           | op     |
| playerTitle.title     | 稱號相關           | op     |
| playerTitle.view      | 查看管理           | op     |
| playerTitle.open      | 稱號倉庫           | true   |
| playerTitle.shop      | 稱號商城           | true   |

## 指令(管理員):

| 指令                                                    | 用途                       |
|-------------------------------------------------------|--------------------------|
| /plt addReward [稱號數量] [類型] [金額]                       | 給對應數量的稱號添加獎勵             |
| /plt buff [addBuff/deleteBuff]                        | 新增                       |刪除buff|
| /plt card [create/random]                             | 創建｜隨機 稱號卡                |
| /plt coin [give/set/take] [玩家名稱] [金額]                 | 給予｜設置｜拿走 玩家稱號幣           |
| /plt convert  [類型]                                    | 轉換數據，類型可選mysql或者sqlite   |
| /plt getIp                                            | 獲取服務器地址                  |
| /plt particle [addParticle/deleteParticle]            | 新增｜刪除 粒子                 |
| /plt player [addTitle/setTitle/listTitle/deleteTitle] | 新增｜設置｜查看｜刪除 玩家稱號         |
| /plt reload                                           | 重載插件                     |
| /plt title [add/delete/list/import/description]       | 新增｜刪除｜查看｜導入｜描述 稱號        |
| /plt view [類型] (玩家名)                                  | 查看對應gui並管理               |
| /plt shop                                             | 打開稱號商城gui,可選參數類型,不填默認全部  |
| /plt open                                             | 打開稱號倉庫gui                |

|[]為必填參數;()為非必填參數|

## 指令(玩家):

| 指令                | 用途            |
|-------------------|---------------|
| /plt shop         | 打開稱號商城gui     |
| /plt open         | 打開稱號倉庫gui     |