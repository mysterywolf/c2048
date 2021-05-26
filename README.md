# 2048 for RT-Thread

[中文](README_CN.md) | English

[2048](https://en.wikipedia.org/wiki/2048_(video_game)) is a single-player sliding tile puzzle video game written by Italian web developer Gabriele Cirulli and published on GitHub. The objective of the game is to slide numbered tiles on a grid to combine them to create a tile with the number 2048.

This project ported the [2048 game](https://github.com/mevdschee/2048.c) that designed by Maurits in the Linux terminal to the [RT-Thread](https://www.rt-thread.io/) terminal, so players can get to control the direction through the arrow keys, WASD keys, or HJKL keys, instead of sliding the phone screen.

![screenshot](screenshot.png)

Configure the project in the [RT-Thread Env tool](https://www.rt-thread.io/download.html?download=Env) or [RT-Studio](https://www.rt-thread.io/studio.html), as shown below:

```
 RT-Thread online packages  --->
    miscellaneous packages  --->
        entertainment: terminal games and other interesting software packages  --->
            [*] 2048: An indie puzzle video game run on RT-Thread console

```

Enter `msh> 2048` in the terminal can get it successfully running. 