# PlotSquared地皮插件

## 介绍
PlotSquared (又名 plot2)是一款功能强大并且可高度自定义配置的地皮生成和管理插件。

## 角色(Tiers)

>玩家可以通过这个设置访问限制并且与信任的朋友来一起建造

- `Owner`地皮所有者
  - 拥有其地皮的所有权限
  - 添加/移除玩家
  - 放置/破坏方块
  - 删除地皮
  - 等等

- `Helper`地皮援建者
  - 可以传送到地皮
  - 放置/破坏方块
  - 在该地皮使用创世神

- `Trusted`可信玩家
  - 可以在所有者在线时放置/破坏方块
  - 可以传送到地皮

- `Denied`黑名单
  - 不能操作地皮
  - 不能进入地皮

## 属性(Flag)

>Flag(属性)是用来配置玩家地皮区域的所有属性参数，玩家可以通过这些参数来自定义您的地皮！

- `titles`地皮名  
- `greeting`欢迎语
- `farewell`欢送语
- `feed`食用、喂养
- `heal`治疗
- `notify-enter`进入通知
- `notify-leave`离开通知
- `item-drop`物品掉落
- `invincible`无敌状态
- `instabreak`可打破
- `drop-protection`跌落保护
- `forcefield` 力场
- `pve`PVE
- `pvp`PVP
- `fly`飞行
- `stone_plate`石质踏板
- `lever`拉杆
- `wooden_door`木门
- `iron_door` 铁门
- `trapped_chest` 陷阱箱
- `chest`箱子
- `wooden_plate`木质踏板
- `stone_button`石质按钮
- `dispenser`发射器
- `trap_door`活板门
- `wooden_button`木质按钮
- `dropper`投掷器
- `gamemode`游戏模式
- `time`时间
- `weather`天气

## 命令

>这里只提供用户使用的指令，风纪委请至 ~~专业页面~~ 进行学习！

- `/plot claim`认领当前脚下的地皮
- `/plot unclaim`解除认领当前的地皮
- `/plot auto`认领最近的一处可用地皮
- `/plot home <id|alias>`前往你的地皮
- `/plot visit <player>`拜访某玩家的地皮
- `/plot tp <alias|id|player>`传送到一个地皮
- `/plot set home`将你当前位置设置为该地皮的家位置
- `/plot set flag <key> [value]`设置地皮的属性
- `/plot clear`清除你当前的地皮
- `/plot delete`删除当前的地皮
- `/plot merge <N|E|S|W>`合并你的地皮
- `/plot unlink`拆分你之前合并的地皮
- `/plot setowner <player>`设置地皮所有者
- `/plot denied <add|remove> <player>`设置地皮玩家黑名单
- `/plot helpers <add|remove> <player>`设置地皮援建者名单
- `/plot trusted <add|remove> <player>`设置地皮可信玩家名单
- `/plot kick <player>`从地皮里踢出一个玩家
