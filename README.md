# 2048

《2048》是一款单人在线和移动端游戏，由19岁的意大利人Gabriele Cirulli于2014年3月开发。游戏任务是在一个网格上滑动小方块来进行组合，直到形成一个带有有数字2048的方块。

它是滑块类游戏的一种电脑变体，非常类似于在2014年2月发布的Threes!应用。作者开发这个游戏是为了测试自己是否有能力从零开始创造一款游戏，但游戏飙升的人气（不到1周内有400万访客）完全出乎他的预料。事实上，它已被称为网络上“最上瘾的东西”。

华尔街日报将其评价为“属于数学极客的Candy Crush”。该游戏为开源软件，这导致它衍生出许多改进版和变种，包括积分排行榜、提升触屏的可玩性[6]、或者使用其他的换算规则和素材等。

2048游戏设计源自一个类似的游戏《1024》和Saming开发的《2048》（Saming的2048同样改编自1024），而1024的灵感来自于移动端游戏Threes!（但Threes!作者对此感到不满，Threes!的玩家认为1024与2048是抄袭作品）



## 操作方法

玩家每次可以选择上下左右其中一个方向去滑动，每滑动一次，所有的数字方块都会往滑动的方向靠拢靠死，相同数字的方块在这个过程中会碰撞相加变成一个更大数字的方块（不触发连锁效果），完成后系统会在空白的地方随机出现一个数字方块（2或4）。玩家需要不断地滑动，想办法叠加出越来越大的数字，直到达成2048就算成功。

本游戏是根据Maurits在Linux终端设计的2048游戏https://github.com/mevdschee/2048.c 移植到了RT-Thread终端上，用户可以通过方向键，或WASD键，或HJKL键控制方向，来替代原版游戏中滑动手机屏幕的操作。

![screenshot](screenshot.png)

在ENV工具的配置方法：

```
 RT-Thread online packages  --->
    miscellaneous packages  --->
        games: games run on RT-Thread console  --->
            [*] 2048: An indie puzzle video game run on RT-Thread console
```

在终端下键入：

```shell
msh> 2048
```

即可运行。



## 维护&联系

Meco Man

jiantingman@foxmail.com

https://github.com/mysterywolf/2048

