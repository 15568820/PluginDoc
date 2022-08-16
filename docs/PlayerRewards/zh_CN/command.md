## 权限
##### 本插件默认无需配置任何权限,服主开箱即用
##### 很多下面涉及都类型不知道的 低版本请使用tab提醒,1.12以上会自动提醒
| 权限                        | 用途               | 默认拥有者 |
|---------------------------|------------------|-------|
| PlayerRewards.reload      | 重载插件             | op    |
| PlayerRewards.view        | 查看奖励             | op    |
| PlayerRewards.addReward   | 添加奖励             | op    |
| PlayerRewards.createBatch | 批量创建一次性激活码       | op    |
| PlayerRewards.create      | 创建激活码            | op    |
| PlayerRewards.createGift  | 创建奖励礼物           | op    |
| PlayerRewards.use         | 使用激活码            | 全部    |

## 指令:
| 指令                                  |  用途                         |
|-------------------------------------|-----------------------------|
| /pr addReward [奖励类型] [数量]           | 添加任务奖励(如果奖励类型是物品需要主手持有对应物品) |
| /pr create [激活码名称] [使用次数] [可用天数]    | 创建激活码                       |
| /pr createBatch [数量]                | 批量生成一次性激活码到cdk.yml中         |
| /pr createGift [礼物名称] (奖励ids) (玩家名) | 创建礼物                        |
| /pr use [激活码]                       | 玩家使用激活码                     |
| /pr view reward                     | 使用gui里查看奖励列表                |
| /pr reload                          | 重载配置文件                      |