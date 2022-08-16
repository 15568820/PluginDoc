## 例子
說明:
```
/plt add [獲取條件] [條件數量] [金額] (天數) (是否隱藏) (玩家名)
添加一個新稱號到稱號商城
獲取條件：not(無條件) vault(金幣) playerpoints(點卷) coin(稱號幣) itemStack(物品名) 
條件數量：上方所選條件所需數量
天數:天數只能為正整數,0為永久
是否隱藏:false隱藏 true顯示
玩家名:填寫後會新增到稱號商城的同時直接發給該玩家
[] 的為必填項  () 的為選填
```

註意:
下面例子中最後一個參數為0就是購買稱號後玩家持有時間為永久
玩家稱號過期是按照登錄時候進行判斷刪除過期稱號

1. 新增: 白嫖者稱號 玩家點擊即可獲取永久
```
/plt add not &f白嫖者 0 0
```

2. 新增: 金幣稱號  玩家需要消耗666金幣來獲取6天(需:Vault支持)
```
/plt add vault &e金幣 666 6
```

3. 新增:點券稱號 玩家需要消耗666金幣來獲取6天(需:PlayerPoints支持)
```
/plt add playerPoints &e點券 666 6
```
4. 新增:鉆石劍稱號 玩家需要消耗鉆石劍1個來獲取永久稱號
   備註:需要手持原版鉆石劍來輸入該命令
```
/plt add itemStack &e鉆石劍 1 0
```
5. 新增: rpg物品稱號: 玩家需要消耗rpg物品1個來獲取6天
   備註:需要手持rpg物品來輸入該命令
```
/plt add itemStack &erpg稱號 1 6
```
6. 新增: 稱號幣稱號: 玩家需要消耗稱號幣666來獲取6天
```
/plt add coin &e稱號幣稱號 666 6
```

## 截圖說明
[![WXVAo9.png](https://z3.ax1x.com/2021/07/30/WXVAo9.png)](https://imgtu.com/i/WXVAo9)
[![WXVViR.png](https://z3.ax1x.com/2021/07/30/WXVViR.png)](https://imgtu.com/i/WXVViR)
[![WXVkdJ.png](https://z3.ax1x.com/2021/07/30/WXVkdJ.png)](https://imgtu.com/i/WXVkdJ)
[![WXVFZ4.png](https://z3.ax1x.com/2021/07/30/WXVFZ4.png)](https://imgtu.com/i/WXVFZ4)
[![WXVPLF.png](https://z3.ax1x.com/2021/07/30/WXVPLF.png)](https://imgtu.com/i/WXVPLF)
[![WXVZJ1.png](https://z3.ax1x.com/2021/07/30/WXVZJ1.png)](https://imgtu.com/i/WXVZJ1)
[![WXVeRx.png](https://z3.ax1x.com/2021/07/30/WXVeRx.png)](https://imgtu.com/i/WXVeRx)
[![WXVKsO.png](https://z3.ax1x.com/2021/07/30/WXVKsO.png)](https://imgtu.com/i/WXVKsO)
[![WXVuQK.png](https://z3.ax1x.com/2021/07/30/WXVuQK.png)](https://imgtu.com/i/WXVuQK)