## 權限
##### 本插件默認無需配置任何權限,服主開箱即用
##### 很多下面涉及都類型不知道的 低版本請使用tab提醒,1.12以上會自動提醒
| 權限                        | 用途         | 默認擁有者 |
|---------------------------|------------|-------|
| PlayerRewards.reload      | 重載插件       | op    |
| PlayerRewards.view        | 查看獎勵       | op    |
| PlayerRewards.addReward   | 添加獎勵       | op    |
| PlayerRewards.createBatch | 批量創建一次性激活碼 | op    |
| PlayerRewards.create      | 創建激活碼      | op    |
| PlayerRewards.createGift  | 創建獎勵禮物     | op    |
| PlayerRewards.use         | 使用激活碼      | 全部    |

## 指令:
| 指令                               |  用途                         |
|----------------------------------|-----------------------------|
| /pr addReward [獎勵類型] [數量]        | 添加任務獎勵(如果獎勵類型是物品需要主手持有對應物品) |
| /pr create [激活碼名稱] [使用次數] [可用天數] | 創建激活碼                       |
| /pr createBatch [數量]             | 批量生成一次性激活碼到cdk.yml中         |
| /pr createGift [禮物名稱] (獎勵ids)    | 創建禮物                        |
| /pr use [激活碼]                    | 玩家使用激活碼                     |
| /pr view reward                  | 使用gui裏查看獎勵列表                |
| /pr reload                       | 重載配置文件                      |