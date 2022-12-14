### 卷轴任务介绍

> 在1.9.0+版本新增卷轴任务

```
新增指令 /plk changeItem [任务id] (玩家名称) 
```

使用该指令可以根据现有的任务 生成一个任务卷轴到玩家背包

### 任务绑定系统

* 每个卷轴任务在生成的时候都会绑定到对应玩家(服主不要出售卷轴，要生成出售指令)
* 只有对应玩家背包有该卷轴任务才可以进行任务
* 遗失或者其他玩家拿到该卷轴都无法进行任务

### 任务完成流程

* 玩家背包存在自己的任务卷轴会开始进行任务
* 任务目标会跟正常的任务一样有提醒
* 玩家在全部目标后，手持任务卷轴点击下空气即可完成任务领取奖励

### 卷轴任务适用场景

1. 菜单任务，可以配合菜单插件让玩家自己选择一个任务进行执行
2. 出售任务，可以把一些稀有度高的任务转化为卷轴，让玩家可以获取
3. 剧情任务，可以配合npc插件，npc对话结束后使用该指令给任务卷轴
4. 流程任务，可以完成上一个任务后奖励下一个任务(任务奖励可以使用命令奖励)
5. 每日任务扩展，可以如上，每日任务里的奖励设置为 命令例如

```
/plk addReward command 1 plk#changeItem#1#${player}
```

这个命令意思是 奖励玩家一个任务ID为1的任务卷轴