## 權限
##### 本插件默認無需配置任何權限,服主開箱即用
##### 很多下面涉及都類型不知道的 低版本請使用tab提醒,1.12以上會自動提醒
|  權限 | 用途  | 默認擁有者 |
| ------------ | ------------ | ------------ |
| playerfatigue.setblock  | 設置指定方塊  | op |
| playerfatigue.give  | 給玩家疲勞值  | op |
| playerfatigue.take  | 減少玩家疲勞值  | op |
| playerfatigue.set  | 設置玩家疲勞值  | op |
| playerfatigue.setMax  | 設置玩家最大疲勞值  | op |
| playerfatigue.addMax  | 添加玩家最大疲勞值  | op |
| playerfatigue.vip  | vip權利  | op |
| playerfatigue.viewblock  | 查看設置指定方塊  | op |
| playerfatigue.reload  | 重載插件  | op |

## 指令:
|  指令 | 用途  |
| ------------ | ------------ |
|/plf setBlock [類型]  [需要疲勞值]   |     添加一個消耗疲勞值的方塊"|
|/plf give [玩家名稱] [數量]  |      增加玩家疲勞值"|
| /plf take [玩家名稱] [數量] |       減少玩家疲勞值"|
| /plf set  [玩家名稱] [數量]  |      設置玩家疲勞值"|
| /plf setMax  [玩家名稱] [數量]  |      設置玩家最大疲勞值"|
| /plf addMax  [玩家名稱] [數量]  |      添加玩家最大疲勞值"|
| /plf viewblock  | 查看設置指定方塊  |
| /plf reload                |       重載插件"|

```
類型分為: 挖掘(break) 合成 (craftItem)
例如: 手拿鉆石礦輸入
/plf setBlock break 1
就是讓玩家挖掘鉆石礦的時候消耗一點疲勞值
```