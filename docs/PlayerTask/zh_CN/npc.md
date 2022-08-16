## 例子
说明:
```
npc任务的逻辑是:
1. 首先你按照例子1中,新增一个npc任务出来
/plk create NpcTask npc normal
2. 然后使用指令绑定到对应的npc上
```
假设我们有已经个npc任务,如图,类型为npc任务

这时候我们看看公民Citizens插件的npc列表

可以看到有,0,1,2三个npc

### 输入指令进行绑定
2021-02-06 18:39:20 星期六
```
指令: 
/plk addNpcTask [任务id] [npcId] [是否永久任务] [可完成次数] [冷却时间] (前置任务id)

示例: 
/plk addNpcTask 23 2 1 0 60

解释:
将Id为23号的任务绑定到npc2号上,设置为1,表示永久循环任务,后面的0,是任务可完成次数(前面一个参数设置为0生效), 60为冷却时间 ,前置任务id可不传,默认就没有前置任务,如果需要有前置任务传对应任务id即可
```

### 上面一顿操作后的效果

### 如何查看npc绑定过的任务
```
/plk view npc

注意: 点击删除后会把玩家接过的该任务也同步删除掉
```

[![4oeTD1.png](https://z3.ax1x.com/2021/09/30/4oeTD1.png)](https://imgtu.com/i/4oeTD1)
[![4oe7Hx.png](https://z3.ax1x.com/2021/09/30/4oe7Hx.png)](https://imgtu.com/i/4oe7Hx)
[![4oebE6.png](https://z3.ax1x.com/2021/09/30/4oebE6.png)](https://imgtu.com/i/4oebE6)
[![4oeL4O.png](https://z3.ax1x.com/2021/09/30/4oeL4O.png)](https://imgtu.com/i/4oeL4O)

