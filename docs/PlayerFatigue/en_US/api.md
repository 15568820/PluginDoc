## Welcome to develop more subsidiary plug-ins to this plug-in
You can make based on fatigue value for example: copy fatigue value limit, low fatigue value prohibit the execution of commands and so on to develop their own brainstorming

#### maven introduction
[click to view](https://www.showdoc.com.cn/handyMinecraft?page_id=4864562478005642 "click to view")

#### 1. Get the player's current fatigue value

````
PlayerFatigueApi.getAmount(player name)
PlayerFatigueApi.getAmount(player UUID)

Return the current fatigue value: Type Integer
```

#### 2. Get the upper limit of player fatigue value

```
PlayerFatigueApi.getMaxAmount(player name)
PlayerFatigueApi.getMaxAmount(player UUID)

Return the player fatigue limit: Type Integer
```

#### 3. Set the player fatigue value

```
PlayerFatigueApi.set(player name, fatigue value)
PlayerFatigueApi.set(player UUID,fatigue value)

Returns success or failure: type boolean
```

#### 4. Give the player fatigue value

```
PlayerFatigueApi.give(player name,fatigue value)
PlayerFatigueApi.give(player UUID,fatigue value)

Returns whether or not the function was successful: Type boolean
```

#### 5. Reduce player fatigue value

```
PlayerFatigueApi.take(player name, fatigue value)
PlayerFatigueApi.take(player UUID,fatigue value)

Returns whether the take was successful or not: Type boolean
```