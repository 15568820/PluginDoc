### 任務稀有度介紹

> 在1.8.7+版本新增任務稀有度概念

config.yml中新增
```
# 任務稀有度刷新概率(Mission Rarity Refresh Probability)
# 顏色是推薦設置的任務名稱顏色，方便玩家識別任務(The colour is the recommended setting of the mission name colour to make it easier for players to identify the mission)
rarity:
# 普通任務（白色） normal task (white) &f
normal: 0.8
# 高級任務（藍色）advanced task (blue) &1
advanced: 0.5
# 稀有任務（紫色） rare task (purple) &5
rare: 0.3
# 罕見任務（粉色）rarer task (pink) &d
rarer: 0.2
# 史詩任務（橙色）epic task (orange) &e
epic: 0.1
# 神話任務 (漸變色) mythical task (gradient) &e&l
mythical: 0.01
不做任何限製,並享受售後,一對一服務,定製需求優先采納等尊貴特權
```

### 稀有度如上,默認有這些稀有度
1. 每日隨機生成的任務會根據上面配置按照概率生成,數量不足填充普通任務(歷史任務全部為普通)
2. 主要目的: 玩家想要高稀有度的任務就必須一直刷新每日任務,提高收益
3. 新增任務指令變更為/plk create [任務名稱] (任務類型) (任務稀有度)
4. 或者使用/plk setRarity [任務id] [稀有度] 來進行設置任務的稀有度