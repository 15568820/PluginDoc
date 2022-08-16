## 歡迎對接本插件開發更多附屬插件~
你可以基於疲勞值做出 例如: 副本疲勞值限製, 低疲勞值禁止執行指令等等自己開發腦洞

#### maven引入
[點擊查看](https://www.showdoc.com.cn/handyMinecraft?page_id=4864562478005642 "點擊查看")

#### 1. 獲取玩家當前疲勞值

```
PlayerFatigueApi.getAmount(玩家名)
PlayerFatigueApi.getAmount(玩家UUID)

返回當前疲勞值: 類型 Integer
```

#### 2. 獲取玩家疲勞值上限

```
PlayerFatigueApi.getMaxAmount(玩家名)
PlayerFatigueApi.getMaxAmount(玩家UUID)

返回玩家疲勞值上限: 類型 Integer
```

#### 3. 設置玩家疲勞值

```
PlayerFatigueApi.set(玩家名,疲勞值)
PlayerFatigueApi.set(玩家UUID,疲勞值)

返回是否成功: 類型 boolean
```

#### 4. 給予玩家疲勞值

```
PlayerFatigueApi.give(玩家名,疲勞值)
PlayerFatigueApi.give(玩家UUID,疲勞值)

返回是否成功: 類型 boolean
```

#### 5. 減少玩家疲勞值

```
PlayerFatigueApi.take(玩家名,疲勞值)
PlayerFatigueApi.take(玩家UUID,疲勞值)

返回是否成功: 類型 boolean
```