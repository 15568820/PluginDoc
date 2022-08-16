### Add title command

> /plt title add [title type] [title name] [amount] (number of days) (whether to hide) (title description)

#### The title type is divided into:
* not: unconditional
* vault: Gold
* playerPoints: points
* coin: coins
* itemStack: item
* permission: Permissions
* activity: activity

#### amount/quantity
* type: gold,coin,coin -> purchase price
* type: item -> quantity required (requires master to hold the corresponding item)
* Type: Other -> Not useful

#### Number of days
* Number of days to sell the title, can only be positive integer, 0 is permanent

#### hidden or not
* false hidden (not shown in plt shop) true shown
#### Description
* The description of the title can be line feed with a comma **,**

### Additional Notes
* []'s are required ()'s are optional

### Examples

1. New: White john title Player can click on it to get permanent
```
/plt title add not &e white john title 0 0 true This is the title description, this is the second line
This is the second line.
```

2. new: gold title player need to consume 666 gold to get 6 days (need: Vault support)
```
/plt title add vault &e gold title 666 6 true This is a gold title
```

3. add:Vault title Players need to spend 666 vouchers to get 6 days(need:PlayerPoints support)

```
/plt title add playerPoints &e point title 666 0 false This is a hidden point title
```

4. new: diamond sword title players need to consume 1 diamond sword to get the permanent title
   Note: You need to hold a diamond sword to enter this command
```
/plt title add itemStack &e Diamond Sword title 1 0 false You need to be holding a Diamond Sword to enter this command
```

5. new: title coin title: players need to consume title coin 666 to get 6 days
```
/plt title add coin &e title coin title 666 6 true This is a title coin title
```

6. add: permission title: player has permission **test** to get it automatically after login
```
/plt title add permission permission title test This is the description of a permission title that players have permission to **test** automatically get after logging in
```

7. new: event title: this kind of title can't be bought, only given by OP command
```
/plt title add activity activity title 0 0 true This is an activity title that can only be given by OP
```