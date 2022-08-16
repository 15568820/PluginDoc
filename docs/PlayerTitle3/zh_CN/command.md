## 权限

##### 本插件默认无需配置任何权限,服主开箱即用

##### 很多下面涉及都类型不知道的 低版本请使用tab提醒,1.12以上会自动提醒

# 3.x版本

## 具体权限

| 权限                    | 用途             | 默认拥有者  |
|-----------------------|----------------|--------|
| playerTitle.addReward | 添加称号数量奖励       | op     |
| playerTitle.buff      | 称号buff相关       | op     |
| playerTitle.card      | 称号卡相关          | op     |
| playerTitle.coin      | 称号币相关          | op     |
| playerTitle.convert   | 转换数据库          | op     |
| playerTitle.getIp     | 获取服务器信息        | op     |
| playerTitle.particle  | 称号粒子相关         | op     |
| playerTitle.player    | 玩家称号相关         | op     |
| playerTitle.reload    | 重载插件           | op     |
| playerTitle.title     | 称号相关           | op     |
| playerTitle.view      | 查看管理           | op     |
| playerTitle.open      | 称号仓库           | true   |
| playerTitle.shop      | 称号商城           | true   |

## 指令(管理员):

| 指令                                                    | 用途                       |
|-------------------------------------------------------|--------------------------|
| /plt addReward [称号数量] [类型] [金额]                       | 给对应数量的称号添加奖励             |
| /plt buff [addBuff/deleteBuff]                        | 新增                       |删除buff|
| /plt card [create/random]                             | 创建｜随机 称号卡                |
| /plt coin [give/set/take] [玩家名称] [金额]                 | 给予｜设置｜拿走 玩家称号币           |
| /plt convert  [类型]                                    | 转换数据，类型可选mysql或者sqlite   |
| /plt getIp                                            | 获取服务器地址                  |
| /plt particle [addParticle/deleteParticle]            | 新增｜删除 粒子                 |
| /plt player [addTitle/setTitle/listTitle/deleteTitle] | 新增｜设置｜查看｜删除 玩家称号         |
| /plt reload                                           | 重载插件                     |
| /plt title [add/delete/list/import/description]       | 新增｜删除｜查看｜导入｜描述 称号        |
| /plt view [类型] (玩家名)                                  | 查看对应gui并管理               |
| /plt shop                                             | 打开称号商城gui,可选参数类型,不填默认全部  |
| /plt open                                             | 打开称号仓库gui                |

|[]为必填参数;()为非必填参数|

## 指令(玩家):

| 指令                | 用途            |
|-------------------|---------------|
| /plt shop         | 打开称号商城gui     |
| /plt open         | 打开称号仓库gui     |