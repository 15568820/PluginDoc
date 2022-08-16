## 权限
##### 本插件默认无需配置任何权限,服主开箱即用
##### 很多下面涉及都类型不知道的 低版本请使用tab提醒,1.12以上会自动提醒
|  权限 | 用途  | 默认拥有者 |
| ------------ | ------------ | ------------ |
| playerfatigue.setblock  | 设置指定方块  | op |
| playerfatigue.give  | 给玩家疲劳值  | op |
| playerfatigue.take  | 减少玩家疲劳值  | op |
| playerfatigue.set  | 设置玩家疲劳值  | op |
| playerfatigue.setMax  | 设置玩家最大疲劳值  | op |
| playerfatigue.addMax  | 添加玩家最大疲劳值  | op |
| playerfatigue.vip  | vip权利  | op |
| playerfatigue.viewblock  | 查看设置指定方块  | op |
| playerfatigue.reload  | 重载插件  | op |

## 指令:
|  指令 | 用途  |
| ------------ | ------------ |
|/plf setBlock [类型]  [需要疲劳值]   |     添加一个消耗疲劳值的方块"|
|/plf give [玩家名称] [数量]  |      增加玩家疲劳值"|
| /plf take [玩家名称] [数量] |       减少玩家疲劳值"|
| /plf set  [玩家名称] [数量]  |      设置玩家疲劳值"|
| /plf setMax  [玩家名称] [数量]  |      设置玩家最大疲劳值"|
| /plf addMax  [玩家名称] [数量]  |      添加玩家最大疲劳值"|
| /plf viewblock  | 查看设置指定方块  |
| /plf reload                |       重载插件"|

```
类型分为: 挖掘(break) 合成 (craftItem)
例如: 手拿钻石矿输入
/plf setBlock break 1
就是让玩家挖掘钻石矿的时候消耗一点疲劳值
```