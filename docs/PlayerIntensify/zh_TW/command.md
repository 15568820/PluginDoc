## 權限
##### 本插件默認無需配置任何權限,服主開箱即用
##### 很多下面涉及都類型不知道的 低版本請使用tab提醒,1.12以上會自動提醒
| 權限                                  | 用途        | 默認擁有者   |
|-------------------------------------|-----------|---------|
| playerIntensify.reload              | 重載插件      | op      |
| playerIntensify.giveRyanCokes       | 獲取爐巖碳     | op      |
| playerIntensify.giveEnchantedCokes  | 獲取高級爐巖碳   | op      |
| playerIntensify.giveProtectionCard  | 獲取強化保護券   | op      |
| playerIntensify.probability         | 測試強化概率    | op      |
| playerIntensify.createHd            | 創建強化排行全息圖 | op      |
| playerIntensify.giveSecretMedicines | 獲取強化秘藥    | op      |
| playerIntensify.up                  | 提升強化等級    | op      |
| playerIntensify.adminUp             | 強行設置強化等級  | op      |
| playerIntensify.giveIntensifyCard   | 獲取強化券     | op      |

## 指令:
| 指令                                      | 用途           |
|-----------------------------------------|--------------|
| /plis reload                            | 重載插件         |
| /plis giveRyanCokes [數量]                | 給玩家指定數量強化石   |
| /plis giveEnchantedCokes [數量]           | 給玩家指定數量高級強化石 |
| /plis giveProtectionCard [數量]           | 給玩家指定數量強化保護券 |
| /plis probability  [等級]                 | 測試當前等級的強化率   |
| /plis createHd                          | 創建全息圖排行      |
| /plis giveSecretMedicines [數量]          | 獲取強化秘藥       |
| /plis up                                | 提升強化等級       |
| /plis adminUp                           | 管理設置強化等級     |
| /plis giveIntensifyCard [類型] [等級] [數量]  | 獲取強化券        |

#### 強化券類型
```
# 強化券類型  -> 默認概率 例如 iron_ingot 概率為百分之1
# iron_ingot -> 1
# bronze -> 5
# bai_yin -> 10
# gold_ingot -> 30
# platinum -> 50
# emerald -> 70
# diamond -> 90
# intensify_card -> 100
intensifyCardType:
    iron_ingot: "&5黑鐵裝備強化券"
    bronze: "&5青銅裝備強化券"
    bai_yin: "&5白銀裝備強化券"
    gold_ingot: "&5黃金裝備強化券"
    platinum: "&5鉑金裝備強化券"
    emerald: "&5翡翠裝備強化券"
    diamond: "&5鉆石裝備強化券"
    intensify_card: "&5裝備強化券"
```