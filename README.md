

## ads

### 基本信息

- 插件 ID: `ads`
- 插件名: Ad_Dev_Server
- 版本: 1.0.3
  - 元数据版本: 1.0.3
  - 发布版本: 1.0.3
- 总下载量: 114514
- 作者: [Ad_closeNN](https://github.com/Ad-closeNN)
- 仓库: https://github.com/Ad-closeNN/Ad_Dev_Server/
- 仓库插件页: https://github.com/Ad-closeNN/Ad_Dev_Server/
- 标签: 工具
- 描述: 不错的娱乐插件，``?ads``查看Ads及GM插件的帮助信息

### 插件依赖

| 插件 ID | 依赖需求 |
| --- | --- |
| [mcdreforged](https://github.com/Fallen-Breath/MCDReforged) | \>=2.5.0 |

### 包依赖

| Python 包 | 依赖需求 |
| --- | --- |

### 介绍
>START 

------------

#### [Ads](https://github.com/Ad-closeNN/Ad_Dev_Server/ "Ads")插件
- 使用 ``?ads help`` 命令可以显示这条插件帮助信息
- 使用 ``?ads`` 命令可以查看 Ad_Dev_Server 插件的信息
- 发送 ``byd`` 可以生成一个标题
- ~~发送 ys 可以启动~~
- 使用 ``!gm help`` 命令可以查看 GM 插件的帮助信息
- 使用 ``!!yb`` 命令可以让 Supreme ~~达成目标~~
- 使用 ``!!c`` 命令可以切换成创造模式，且作弊榜会加 1
- 使用 ``!!s`` 命令可以切换成生存模式，作弊榜不会改变
- 使用 ``?ads reloadall`` 命令可以重新加载 MCDR 的全部插件
- 使用 ``?ads reload`` 命令可以重新加载 ads 插件
- 使用 ``!!pig`` 命令可以永远都不会原谅你
- 使用 ``?op`` 命令可以让你成为 op
- 使用 ``?deop`` 命令可以让你失去 op
- 使用 `?sb` `?b` `?kb` 命令可以召唤/传送/移除 假人b (要有`carpet` mod)
- 使用 `?heal` 命令可以治疗自己
- 使用 `?qb` 命令可以快速使用[Quick Backup M](https://github.com/TISUnion/QuickBackupM/ "Quick Backup Multi")插件备份存档（备注名：ads 紧急备份）
#### [GM](https://github.com/xksnetcbs/MCDR-gamemode_helper-1.16- "GM")插件（由 Ads 插件附加）
- 使用 ``!gm help`` 命令可以显示GM插件指令帮助信息
- 使用 ``!Clear`` 命令可以使你注册 GM 插件
- 使用 ``!c`` 命令可以使你进入旁观者模式
- 使用 ``!s`` 命令可以使你返回生存模式，并回到你使用 !c 的位置
- 使用 ``!gm del @s`` 命令可以使你删除你在 GM 插件的信息(有确认，还要确认一遍)
- 使用 ``!gm del @s confirm`` 命令可以使你删除你在 GM 插件的信息(无确认，直接执行删除命令)

#### 就这么多！

------------

> END

# Tips
- 使用``!!yb``命令记得要注意必须要有名字是``Supreme``的玩家，可以是假人也可以是真人，否则不够真实
- 使用``byd``命令要注意你发了之后不会被其他玩家打(指令有@a)
- 在使用``!!c``命令要注意你已经创建了名为``zb``，类型为``dummy``的计分板:``/scoreboard objectives add zb dummy``，否则作弊次数将不计入

#### Warning 注意
本插件是为 Ad_Dev_Server 服务器开发的，所以有什么服务器适配不正常而 Ad_Dev_Server 服务器正常的自己去调，本人不负责任。如果 Ad_Dev_Server 服务器也不能用的就去提[Issues](https://github.com/Ad-closeNN/Ad_Dev_Server/issues "Issues")，本人看情况修改bug。别指望这个插件能为你的服务器带来什么好处，因为这插件真的没啥用，如果你是认真看完插件的代码的话，你就会发现这个插件的代码都是最基础的，所以写这插件就单纯拿来练练写代码能力和装B用的。

Discord: https://discord.gg/MY5tPs6p5y

# 更新内容 (V1.0.3)
## 加入
1.加入了`?heal`，可以瞬间治疗自己\
2.加入了`?qb`，可以快速备份QBM\
（TIPS:
1.前提是要有Quick BackupM这个插件
2.备注是"ads 紧急备份"）\
3.加入了`?b`,`?kb`,`?sb`，可以将假人b召唤到你的位置/移除/生成
## 修改
1.将`!!c`的计分板设为自动设置\
2.将`?ads help`的指令帮助增加了加入的新指令\
3.将`!!help`的指令帮助删除/增加了内容\
4.将`?ads`的版本信息修改\
5.将`元数据`的版本信息修改\
6.将`README.md`的版本信息和元数据版本信息修改\
7.将`README.md`的介绍等信息修改
## 删除
1.移除了`?ads line114`，因为行数无法控制