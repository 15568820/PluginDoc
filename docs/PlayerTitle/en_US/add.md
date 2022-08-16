## Example
Description:
```
/plt add [get condition] [number of conditions] [amount] (days) (hidden or not) (player name)
Add a new title to the title mall
Acquisition conditions: not(unconditional) vault(gold) playerpoints(points) coin(title coins) itemStack(item name) 
Number of conditions: the number required for the condition selected above
Number of days: days can only be positive integers, 0 is permanent
Whether to hide: false hide true show
Player name: will be added to the title mall after filling out the direct issue to the player at the same time
The [] is required () is optional
````

Note:
The last parameter in the example below is 0, which means that the player will hold the title for a permanent period after purchase.
Player title expiration is judged according to the time of login to delete the expired title

1. New: White whoring title player can click to get permanent
```
/plt add not &f white john 0 0
```

2. New: Gold title players need to consume 666 gold coins to get 6 days (need: Vault support)
```
/plt add vault &e gold 666 6
```

3. add: voucher title Player needs to consume 666 coins to get 6 days (need: PlayerPoints support)
```
/plt add playerPoints &ePoints 666 6
```
4. new: Diamond Sword title Players need to consume 1 Diamond Sword to get the permanent title
   Note: You need to hold the original Diamond Sword to enter the command
```
/plt add itemStack &e Diamond Sword 1 0
```
5. New: rpg item title: Players need to consume 1 rpg item to get 6 days
   Note: You need to hold an rpg item to enter this command
```
/plt add itemStack &erpg title 1 6
```
6. add: title coin title: players need to consume 666 title coins to get 6 days
```
/plt add coin &e title coin title 666 6
```

## Screenshot description
[![WXVAo9.png](https://z3.ax1x.com/2021/07/30/WXVAo9.png)](https://imgtu.com/i/WXVAo9)
[![WXVViR.png](https://z3.ax1x.com/2021/07/30/WXVViR.png)](https://imgtu.com/i/WXVViR)
[![WXVkdJ.png](https://z3.ax1x.com/2021/07/30/WXVkdJ.png)](https://imgtu.com/i/WXVkdJ)
[![WXVFZ4.png](https://z3.ax1x.com/2021/07/30/WXVFZ4.png)](https://imgtu.com/i/WXVFZ4)
[![WXVPLF.png](https://z3.ax1x.com/2021/07/30/WXVPLF.png)](https://imgtu.com/i/WXVPLF)
[![WXVZJ1.png](https://z3.ax1x.com/2021/07/30/WXVZJ1.png)](https://imgtu.com/i/WXVZJ1)
[![WXVeRx.png](https://z3.ax1x.com/2021/07/30/WXVeRx.png)](https://imgtu.com/i/WXVeRx)
[![WXVKsO.png](https://z3.ax1x.com/2021/07/30/WXVKsO.png)](https://imgtu.com/i/WXVKsO)
[![WXVuQK.png](https://z3.ax1x.com/2021/07/30/WXVuQK.png)](https://imgtu.com/i/WXVuQK)