# 2048

《2048》小游戏的开发者是一个年仅19岁的意大利男孩。令人颇感意外的是，他当时仅用一周时间，就开发出这款深受很多人喜爱的游戏。这位出身意大利北部Gorizia的19岁青年戚鲁利表示，这是他设计开发的第一个游戏。这个游戏是要用户把类似数字的方块结合在一起，以创造出更大数字的新方块，一直到拿到最后包含数字“2048”的方块。游戏推出后大受欢迎，迅速蹿红，也带起一阵模仿潮、美化潮。

原版2048首先发布于GitHub上，后被移植到各个平台。这款游戏是基于《1024》和《小3传奇》的玩法开发而成的新型数字游戏。



## 操作方法

玩家每次可以选择上下左右其中一个方向去滑动，每滑动一次，所有的数字方块都会往滑动的方向靠拢靠死，相同数字的方块在这个过程中会碰撞相加变成一个更大数字的方块（不触发连锁效果），完成后系统会在空白的地方随机出现一个数字方块（2或4）。玩家需要不断地滑动，想办法叠加出越来越大的数字，直到达成2048就算成功。

本游戏是根据Maurits在Linux终端设计的2048游戏https://github.com/mevdschee/2048.c 移植到了RT-Thread终端上，用户可以通过方向键，或WASD键，或HJKL键控制方向，来替代原版游戏中滑动手机屏幕的操作。

![screenshot](screenshot.png)

在ENV工具的配置方法：

```
 RT-Thread online packages  --->
    miscellaneous packages  --->
        [*] 2048: An indie puzzle video game run on RT-Thread console.
```

在Finsh终端下键入：

```shell
msh> 2048
```

即可运行



## 维护&联系

Meco Man

jiantingman@foxmail.com

https://github.com/mysterywolf/2048

