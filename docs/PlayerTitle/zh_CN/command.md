<!-- docs/PlayerTitle/zh_CN/command.md -->

## 权限
##### 本插件默认无需配置任何权限,服主开箱即用
##### 很多下面涉及都类型不知道的 低版本请使用tab提醒,1.12以上会自动提醒

# 2.x版本

## 具体权限
|  权限 | 用途  | 默认拥有者 |
| ------------ | ------------ | ------------ |
| playertitle.addcoin  | 给玩家添加称号币  | op |
| playertitle.add  | 添加一个新称号到称号商城 | op |
| playertitle.addpermission  | 添加一个权限称号 | op |
| playertitle.addplayertitle  | 直接给玩家称号 | op |
| playertitle.addreward  | 给对应数量的称号添加奖励 | op |
| playertitle.changeitem  | 将对应id的称号转换成右键可使用的物品 | op |
| playertitle.randomcard  | 获取一个随机称号卡 | op |
| playertitle.reload  | 重载插件 | op |
| playertitle.set  | 给玩家设置对应天数的称号 | op |
| playertitle.settitlebuff  | 给称号添加buff属性 | op |
| playertitle.subtractcoin  | 给玩家减少称号币 | op |
| playertitle.view  | 查看对应gui并管理 | op |
| playertitle.getIp  | 查询服务器ip | op |
| playertitle.shop  | 打开称号商城gui | 全部 |
| playertitle.open  | 打开称号仓库gui | 全部 |
| playertitle.settitleparticle  | 给称号添加粒子效果 | op |
| playertitle.removetitleparticle  | 删除称号粒子效果 | op |
| playertitle.setdescription  | 给称号添加描述 | op |
| playertitle.listtitle  | 查询全部称号 | op |
| playertitle.adminshop  | 管理称号商城 | op |
| playertitle.delbuff  | 删除buff | op |
| playertitle.convert  | 转换数据源 | op |
| playertitle.custom| 玩家自定义称号 | 所有|
| playertitle.setCustom| 设置玩家可以自定义称号次数 |op|
| playertitle.del| 删除称号 |op|

## 指令(管理员):
|  指令 | 用途  |
| ------------ | ------------ |
| /plt addcoin [玩家名称] [金额] | 给玩家添加称号币  |
| /plt add [称号类型] [称号名称] [金额] (天数) (是否隐藏) (玩家名) | 添加一个新称号到称号商城 |
| /plt addpermission [称号名称] [需要权限]  | 添加一个权限称号 |
|/plt addPlayerTitle [玩家名称] [称号名称] (天数)  |直接新增一个隐藏的称号,并把这个称号给对应玩家,天数如果不填默认永久|
| /plt addreward [称号数量] [类型] [金额]  | 给对应数量的称号添加奖励 |
| /plt changeitem  [称号id] [天数] [数量] (玩家名称)   | 将对应id的称号转换成右键可使用的物品 |
| /plt randomcard [天数] (类型)  | 获取一个随机称号卡 | 
| /plt reload  | 重载插件 |
| /plt set [玩家名称] [称号ID] [天数] | 给玩家设置对应天数的称号 |
| /plt settitlebuff [称号id] [类型] [属性标签]   | 给称号添加buff属性 |
| /plt subtractcoin [玩家名称] [金额]  | 给玩家减少称号币 | 
| /plt view [类型] (玩家名)   | 查看对应gui并管理类型: shop; open;  reward|
| /plt shop  | 打开称号商城gui | 
| /plt open  | 打开称号仓库gui | 
| /plt getId  | 查看服务器ip | 
|/plt setTitleParticle [称号id] [粒子类型] [粒子id] (颜色) (颜色) (颜色)|给称号添加粒子效果|
|/plt removeTitleParticle [称号id]|删除称号粒子效果|
| /plt setDescription [称号id] [称号描述] | 给称号添加描述|
| /plt listTitle [页数]   | 查询服务器称号列表  |
| /plt adminShop   |  打开管理称号商城gui(修改或者删除称号用) |
| /plt delBuff [buffid]   |  删除对应buffid的buff效果 |
|/plt convert [类型] | 转换数据源，类型mysql或者sqlite|
|/plt custom [称号名称]| 设置自定义称号gui |
|/plt setCustom [玩家名称] [可自定义次数] | 设置玩家可以自定义的次数 |
|/plt del [id] | 指令删除称号，同时会删除玩家拥有的该称号 |

|[]为必填参数;()为非必填参数|

```
删除称号请输入/plt view shop 或者/plt adminShop查看
涉及到 是否的 都是传 true/false

/plt view open [玩家名] 可以对玩家的称号删除

/plt settitlebuff [称号id] [类型] [属性标签]
setTitleBuff 的类型包含：
1. attribute_plus: "ap属性" [需要前置 AttributePlus]
2. sx_attribute: "sx属性" [需要前置 SX-Attribute]
3. monster_truce: "怪物休战" 
4. potion_effect: "药水效果"
5. player_intensify: "强化效果" [需要前置 PlayerIntensify]

属性标签 例如： 物理伤害:100 如果需要空格可以用#替换

例子：
/plt settitlebuff 1 attribute_plus &e物理伤害:#&c100
/plt settitlebuff 1 sx_attribute &e物理伤害:#&c100
/plt settitlebuff 1 monster_truce all
/plt setTitleBuff 1 potion_effect [药水类型] [药水等级] [是否显示粒子效果]
药水类型请tab提醒
/plt settitlebuff 1 player_intensify &e增加强化概率:6
```

## 指令(玩家):
|  指令 | 用途  |
| ------------ | ------------ |
| /plt shop   |  打开称号商城gui |
| /plt open    |  打开称号仓库gui |
|/plt custom [称号名称]| 设置自定义称号gui |