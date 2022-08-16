### 作用:
- 多物品兌換稱號卡
- 隨機稱號卡,多種類稱號卡,普通稱號卡,給你的玩家一份rpg的全新玩法

### 新增稱號卡步驟:

##### 普通稱號卡
1. /plt listTitle 0 查看現有稱號id 或者 /plt shop裏查看稱號id

2. /plt changeItem [稱號id] [天數] [數量]
- 例如(給自己一個稱號編號為1的,時間為永久,數量為1的稱號卡)天數0為永久
  /plt changeItem 1 0 1
  [![WXV1dH.png](https://z3.ax1x.com/2021/07/30/WXV1dH.png)](https://imgtu.com/i/WXV1dH)

##### 隨機稱號卡
1. /plt randomCard [天數] (類型)
- 例如: /plt randomCard 0 可獲取的一個永久使用的隨機稱號

[![WXVYWt.png](https://z3.ax1x.com/2021/07/30/WXVYWt.png)](https://imgtu.com/i/WXVYWt)

### 註意:
已經擁有稱號卡對應id稱號的玩家,使用後物品會消失,而稱號是不會多一個重復的...