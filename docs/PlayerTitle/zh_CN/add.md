<!-- docs/PlayerTitle/zh_CN/add.md -->

## 例子
说明:
```
/plt add [获取条件] [条件数量] [金额] (天数) (是否隐藏) (玩家名)
添加一个新称号到称号商城
获取条件：not(无条件) vault(金币) playerpoints(点卷) coin(称号币) itemStack(物品名) 
条件数量：上方所选条件所需数量
天数:天数只能为正整数,0为永久
是否隐藏:false隐藏 true显示
玩家名:填写后会新增到称号商城的同时直接发给该玩家
[] 的为必填项  () 的为选填
```

注意:
下面例子中最后一个参数为0就是购买称号后玩家持有时间为永久
玩家称号过期是按照登录时候进行判断删除过期称号

1. 新增: 白嫖者称号 玩家点击即可获取永久
```
/plt add not &f白嫖者 0 0
```

2. 新增: 金币称号  玩家需要消耗666金币来获取6天(需:Vault支持)
```
/plt add vault &e金币 666 6
```

3. 新增:点券称号 玩家需要消耗666金币来获取6天(需:PlayerPoints支持)
```
/plt add playerPoints &e点券 666 6
```
4. 新增:钻石剑称号 玩家需要消耗钻石剑1个来获取永久称号
   备注:需要手持原版钻石剑来输入该命令
```
/plt add itemStack &e钻石剑 1 0
```
5. 新增: rpg物品称号: 玩家需要消耗rpg物品1个来获取6天
   备注:需要手持rpg物品来输入该命令
```
/plt add itemStack &erpg称号 1 6
```
6. 新增: 称号币称号: 玩家需要消耗称号币666来获取6天
```
/plt add coin &e称号币称号 666 6
```

## 截图说明
[![WXVAo9.png](https://z3.ax1x.com/2021/07/30/WXVAo9.png)](https://imgtu.com/i/WXVAo9)
[![WXVViR.png](https://z3.ax1x.com/2021/07/30/WXVViR.png)](https://imgtu.com/i/WXVViR)
[![WXVkdJ.png](https://z3.ax1x.com/2021/07/30/WXVkdJ.png)](https://imgtu.com/i/WXVkdJ)
[![WXVFZ4.png](https://z3.ax1x.com/2021/07/30/WXVFZ4.png)](https://imgtu.com/i/WXVFZ4)
[![WXVPLF.png](https://z3.ax1x.com/2021/07/30/WXVPLF.png)](https://imgtu.com/i/WXVPLF)
[![WXVZJ1.png](https://z3.ax1x.com/2021/07/30/WXVZJ1.png)](https://imgtu.com/i/WXVZJ1)
[![WXVeRx.png](https://z3.ax1x.com/2021/07/30/WXVeRx.png)](https://imgtu.com/i/WXVeRx)
[![WXVKsO.png](https://z3.ax1x.com/2021/07/30/WXVKsO.png)](https://imgtu.com/i/WXVKsO)
[![WXVuQK.png](https://z3.ax1x.com/2021/07/30/WXVuQK.png)](https://imgtu.com/i/WXVuQK)