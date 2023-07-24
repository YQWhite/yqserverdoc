<p align="center">
<font size="7">  
    POKEMON WORLD 
</font><br>
<font size="4">  
    服务器主要文档 
</font> </p>
<br>
<br>
<br>

# 宝可梦世界
这里是服务器的文档，你可以在这里找到一些基本指令（不会排版，将就看吧）


## 服务器指令
***
### 玩家
- shift+F即可打开主菜单
- F即可打开签到菜单

#### 宝可梦相关
##### /pokeheal
用于治疗宝可梦

    /pokeheal

##### /fs
查看宝可梦信息

    /fs
***

#### 经济相关
##### 金币
###### /money
查看剩余的金币

    /money
###### /pay
向其他人支付指定数量金币

    /pay <玩家ID> <想支付的金币数量>

##### 点券
###### /points me
查看剩余点券

    /points me
###### /points pay
向其他人支付指定数量点券

    /points pay <玩家ID> <向支付的点券数量>

***
##### 交易系统
###### 箱子商店
手中拿着要出售的物品，面对箱子左键，在聊天栏输入价格即可上架物品
###### 全球市场
- /gs open
用于打开全球市场
***
#### 领地相关
##### /plot
地皮主命令，可以使用以下命令圈地

    /plot claim
###### /plot home
回到自己的地皮

    /plot home
###### /plot clear
<font color=red>危险！</font> 此命令会清除您的地皮为平坦地形

    /plot clear
##### 圈地
使用木锄即可在资源世界，生存世界进行圈地，左键选择A点，右键选择B点，两点所形成的四边形即为您的领地。

a | x |x
- | - |-
x | x |b

***
### 管理员
#### 回档操作
##### /co
Coreprotect相关配置
###### /co i
查询方块破坏/放置记录

输入指令后对任意方块右键即可，再次输入即可关闭

    /co i
###### /co rollback
主要回档命令

    /co rollback u:<玩家ID> r:<以你为中心的半径> t:<多少分钟前>

    例:将玩家a三分钟前在以你为中心半径30格内的更改撤销掉
    使用/co rollback u:a r:30 t:3
##### /ir
背包回档命令
###### /ir restore
回档玩家背包

    /ir restore <玩家ID>
***
    