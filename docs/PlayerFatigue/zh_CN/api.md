## 欢迎对接本插件开发更多附属插件~
你可以基于疲劳值做出 例如: 副本疲劳值限制, 低疲劳值禁止执行指令等等自己开发脑洞

#### maven引入
[点击查看](https://www.showdoc.com.cn/handyMinecraft?page_id=4864562478005642 "点击查看")

#### 1. 获取玩家当前疲劳值

```
PlayerFatigueApi.getAmount(玩家名)
PlayerFatigueApi.getAmount(玩家UUID)

返回当前疲劳值: 类型 Integer
```

#### 2. 获取玩家疲劳值上限

```
PlayerFatigueApi.getMaxAmount(玩家名)
PlayerFatigueApi.getMaxAmount(玩家UUID)

返回玩家疲劳值上限: 类型 Integer
```

#### 3. 设置玩家疲劳值

```
PlayerFatigueApi.set(玩家名,疲劳值)
PlayerFatigueApi.set(玩家UUID,疲劳值)

返回是否成功: 类型 boolean
```

#### 4. 给予玩家疲劳值

```
PlayerFatigueApi.give(玩家名,疲劳值)
PlayerFatigueApi.give(玩家UUID,疲劳值)

返回是否成功: 类型 boolean
```

#### 5. 减少玩家疲劳值

```
PlayerFatigueApi.take(玩家名,疲劳值)
PlayerFatigueApi.take(玩家UUID,疲劳值)

返回是否成功: 类型 boolean
```