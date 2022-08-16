## Permissions
##### This plug-in default does not need to configure any permissions, the owner of the service out of the box that use
##### a lot of the following types involved do not know the low version, please use the tab reminder, 1.12 or more will automatically remind
| Permissions               | Usage                                  |  Default owner |
|---------------------------|----------------------------------------|----------------|
| PlayerRewards.reload      | reload plugin                          | op             |
| PlayerRewards.view        | View Rewards                           | op             |
| PlayerRewards.addReward   | Add Reward                             | op             |
| PlayerRewards.createBatch | Batch create one-time activation codes | op             |
| PlayerRewards.create      | create activation codes                | op             |
| PlayerRewards.createGift  | Create a bonus gift                    | op             |
| PlayerRewards.use         | use activation code                    | all            |

## Command:
| commands                                                                      |  purpose                                                                                                     |
|-------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| /pr addReward [reward type] [number]                                          | Add a quest reward (if the reward type is an item you need to have the corresponding item in your main hand) |
| /pr create [activation code name] [number of uses] [number of days available] | create activation code                                                                                       |
| /pr createBatch [number]                                                      | Generate one-time activation codes in batch to cdk.yml                                                       |
| /pr createGift [gift name] (rewardids)                                        | createGift                                                                                                   |
| /pr use [activation code]                                                     | Players use activation codes                                                                                 |
| /pr view reward                                                               | Use the list of rewards in the gui                                                                           |
| /pr reload                                                                    | Reload the configuration file                                                                                |
