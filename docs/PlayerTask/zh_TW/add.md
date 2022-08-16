## 例子
說明:
```
本插件的邏輯是:
1. 首先有了任務目標和任務獎勵
2. 然後將多個任務目標和任務獎勵組合起來創建出一個任務
3. 任務現在分為倆類,一種npc任務,一種每日任務(1.6.0+)
4. 註意,為了兼容rpg物品,所以請一定要保持手持物品的耐久為滿,不然會出現合成了物品但是卻任務沒+1的問題,那是因為耐久沒匹配到
```
假設我們要創建一個任務
任務名稱: &f[&e新手任務&f]

要求1: 合成 3個鉆石塊
要求2: 挖掘10個鉆石礦

獎勵1: 1個鉆石頭盔
獎勵2: 100金幣

步驟一. 新增: 任務目標
```
主手持鉆石塊輸入
/plk addDemand craftItem 3
主手持鉆石礦輸入
/plk addDemand blockBreak 10
```
步驟二. 新增: 任務獎勵
```
主手持鉆石頭盔輸入
/plk addReward itemStack 1
直接輸入
/plk addReward vault 100
```

步驟三. 新增每日任務
```
/plk create &f[&e新手任務&f] everyday
```

步驟三. 新增NPC任務(1.6.0+)
```
/plk create &f[&e新手任務&f] npc
```

特別提醒:
```
第一次創建好任務後/plk open中不會有,需要/plk gettoday進獲取今日任務
之後每天00:00會自動刷新每日任務(npc任務不會刷新)
```


這樣一個任務就完成了,上面的任務目標和任務獎勵只要創建了就可以無限的復用.
## 截圖說明
[![4oeBcj.png](https://z3.ax1x.com/2021/09/30/4oeBcj.png)](https://imgtu.com/i/4oeBcj)
[![4oeDjs.png](https://z3.ax1x.com/2021/09/30/4oeDjs.png)](https://imgtu.com/i/4oeDjs)
[![4oe03Q.png](https://z3.ax1x.com/2021/09/30/4oe03Q.png)](https://imgtu.com/i/4oe03Q)
[![4oesun.png](https://z3.ax1x.com/2021/09/30/4oesun.png)](https://imgtu.com/i/4oesun)
[![4oeyBq.png](https://z3.ax1x.com/2021/09/30/4oeyBq.png)](https://imgtu.com/i/4oeyBq)
[![4oeh34.png](https://z3.ax1x.com/2021/09/30/4oeh34.png)](https://imgtu.com/i/4oeh34)
[![4oegEV.png](https://z3.ax1x.com/2021/09/30/4oegEV.png)](https://imgtu.com/i/4oegEV)
[![4oeR4U.png](https://z3.ax1x.com/2021/09/30/4oeR4U.png)](https://imgtu.com/i/4oeR4U)
[![4oe2NT.png](https://z3.ax1x.com/2021/09/30/4oe2NT.png)](https://imgtu.com/i/4oe2NT)
[![4oe4gJ.png](https://z3.ax1x.com/2021/09/30/4oe4gJ.png)](https://imgtu.com/i/4oe4gJ)
[![4oeqUK.png](https://z3.ax1x.com/2021/09/30/4oeqUK.png)](https://imgtu.com/i/4oeqUK)
[![4oeouR.png](https://z3.ax1x.com/2021/09/30/4oeouR.png)](https://imgtu.com/i/4oeouR)