## Permissions

##### This plug-in default does not need to configure any permissions, the owner of the service out of the box that use

##### Many of the following types involved do not know the low version, please use the tab reminder, 1.12 or more will automatically remind

# 3.x version

## specific permissions

| Permissions           | Usage                  | Default owner  |
|-----------------------|------------------------|----------------|
| playerTitle.addReward | Add title number bonus | op             |
| playerTitle.buff      | Title buff related     | op             |
| playerTitle.card      | Title card related     | op             |
| playerTitle.coin      | Coin related           | op             |
| playerTitle.convert   | convert database       | op             |
| playerTitle.getIp     | Get server information | op             |
| playerTitle.article   | Particle-related       | op             |
| playerTitle.player    | Player title related   | op             |
| playerTitle.reload    | Reload plugin          | op             |
| playerTitle.title     | title-related          | op             |
| playerTitle.view      | View Management        | op             |
| playerTitle.open      | Title Repository       | true           |
| playerTitle.shop      | name shop              | true           |

## Command (Admin):

| command                                                 | purpose                                                                 |
|---------------------------------------------------------|-------------------------------------------------------------------------|
| /plt addReward [number of titles] [type] [amount]       | Add a reward to the corresponding number of titles                      |
| /plt buff [addBuff/deleteBuff]                          | add ｜delete Buff                                                        ||
| /plt card [create/random]                               | create｜random title card                                                |
| /plt coin [give/set/take] [player name] [amount]        | give｜set｜take player title coin                                         |
| /plt convert [type]                                     | convert data, type can be mysql or sqlite                               |
| /plt getIp                                              | Get the server address                                                  |
| /plt particle [addParticle/deleteParticle]              | Add｜delete particle                                                     |
| /plt player [addTitle/setTitle/listTitle/deleteTitle]   | add｜set｜view｜delete player title                                        |
| /plt reload                                             | reload plugin                                                           |
| /plt title [add/delete/list/import/description]         | Add｜Delete｜View｜Import｜Description Title                                |
| /plt view [type] (player name)                          | View the corresponding gui and manage                                   |
| /plt shop                                               | Open title shop gui, optional parameter type, default all if not filled |
| /plt open                                               | Open the title store gui                                                |

|[] is a required parameter; () is a non-required parameter|

## Command (player):

| command            | use                  |
|--------------------|----------------------|
| /plt shop          | Open title mall gui  |
| /plt open          | Open title store gui |