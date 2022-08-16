## 权限

##### 本插件默认无需配置任何权限,服主开箱即用

##### 很多下面涉及都类型不知道的 低版本请使用tab提醒,1.12以上会自动提醒

| 权限                                  | 用途         | 默认拥有者         |
|-------------------------------------|------------|---------------|
| playerIntensify.reload              | 重载插件       | op            |
| playerIntensify.giveRyanCokes       | 获取强化石      | op            |
| playerIntensify.giveEnchantedCokes  | 获取高级强化石    | op            |
| playerIntensify.giveProtectionCard  | 获取强化保护券    | op            |
| playerIntensify.probability         | 测试强化率      | op            |
| playerIntensify.createHd            | 创建强化排行全息图  | op            |
| playerIntensify.giveSecretMedicines | 获取强化秘药     | op            |
| playerIntensify.up                  | 提升强化等级     | op            |
| playerIntensify.adminUp             | 强行设置强化等级   | op            |
| playerIntensify.giveIntensifyCard   | 获取强化券      | op            |

## 指令:

| 指令                                      | 用途           |
|-----------------------------------------|--------------|
| /plis reload                            | 重载插件         |
| /plis giveRyanCokes [数量]                | 给玩家指定数量强化石   |
| /plis giveEnchantedCokes [数量]           | 给玩家指定数量高级强化石 |
| /plis giveProtectionCard [数量]           | 给玩家指定数量强化保护券 |
| /plis probability  [等级]                 | 测试当前等级的强化率   |
| /plis createHd                          | 创建全息图排行      |
| /plis giveSecretMedicines [数量]          | 获取强化秘药       |
| /plis up                                | 提升强化等级       |
| /plis adminUp                           | 管理设置强化等级     |
| /plis giveIntensifyCard [类型] [等级] [数量]  | 获取强化券        |

#### 强化券类型

```
# 强化券类型  -> 默认概率 例如 iron_ingot 概率为百分之1
# iron_ingot -> 1
# bronze -> 5
# bai_yin -> 10
# gold_ingot -> 30
# platinum -> 50
# emerald -> 70
# diamond -> 90
# intensify_card -> 100
intensifyCardType:
    iron_ingot: "&5黑铁装备强化券"
    bronze: "&5青铜装备强化券"
    bai_yin: "&5白银装备强化券"
    gold_ingot: "&5黄金装备强化券"
    platinum: "&5铂金装备强化券"
    emerald: "&5翡翠装备强化券"
    diamond: "&5钻石装备强化券"
    intensify_card: "&5装备强化券"
```