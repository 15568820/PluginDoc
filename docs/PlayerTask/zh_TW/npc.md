## 例子
說明:
```
npc任務的邏輯是:
1. 首先你按照例子1中,新增一個npc任務出來
/plk create NpcTask npc normal
2. 然後使用指令綁定到對應的npc上
```
假設我們有已經個npc任務,如圖,類型為npc任務

這時候我們看看公民Citizens插件的npc列表

可以看到有,0,1,2三個npc

### 輸入指令進行綁定
2021-02-06 18:39:20 星期六
```
指令: 
/plk addNpcTask [任務id] [npcId] [是否永久任務] [可完成次數] [冷卻時間] (前置任務id)

示例: 
/plk addNpcTask 23 2 1 0 60

解釋:
將Id為23號的任務綁定到npc2號上,設置為1,表示永久循環任務,後面的0,是任務可完成次數(前面一個參數設置為0生效), 60為冷卻時間 ,前置任務id可不傳,默認就沒有前置任務,如果需要有前置任務傳對應任務id即可
```

### 上面一頓操作後的效果

### 如何查看npc綁定過的任務
```
/plk view npc

註意: 點擊刪除後會把玩家接過的該任務也同步刪除掉
```

[![4oeTD1.png](https://z3.ax1x.com/2021/09/30/4oeTD1.png)](https://imgtu.com/i/4oeTD1)
[![4oe7Hx.png](https://z3.ax1x.com/2021/09/30/4oe7Hx.png)](https://imgtu.com/i/4oe7Hx)
[![4oebE6.png](https://z3.ax1x.com/2021/09/30/4oebE6.png)](https://imgtu.com/i/4oebE6)
[![4oeL4O.png](https://z3.ax1x.com/2021/09/30/4oeL4O.png)](https://imgtu.com/i/4oeL4O)

