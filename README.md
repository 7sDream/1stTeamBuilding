# YSTC 1st Team building - Code/Art/Vtuber

欢迎大家来到第一届燕宝技术委员会（YSTC）的团建活动！

YSTC 是一个自由的寻求编程爱好者和 DD 交集的组织。我们希望每位 DD 都能玩的开心， D 的开心，代码写的开心！

本次 YSTC 团建活动的内容主旨是寻求代码-艺术-Vtuber 的一个平衡点。我们希望能见证这三者碰撞在一起所能产生的惊奇效果。

## 如何参加活动

本次活动将通过 GitHub 平台来举办。你需要将你最终的代码提交到指定的 GitHub repo（https://github.com/projectyanbao/1stTeamBuilding.git ） 中。因此，为了参加本次活动你至少需要一个 GitHub 账号。并了解 GitHub 的 pr 机制。

## 活动内容

你需要提交三个指定的函数，分别为

```
red(x: int, y: int) => int

green(x: int, y: int) => int

blue(x: int, y: int) => int
```

这三个函数需要返回为位于 x,y(0~1023) 处点的颜色值的 r/g/b 对应的三个分量值(0~255)。最终整个程序将通过这三个函数绘制一幅 1024*1024 的图画。

除此之外，为了便于别人了解你是谁，你需要补充完 `code.author`里的内容。

在本 repo 中，位于 `codes` 文件夹下已经有一个 `code_template.js` 文件，你只需要复制他并重名为 `code_your-id.js` 并补完整个文件。然后讲新的内容提交到本 repo。

## 活动持续时间

2020.12.21 22:00 - 2021.1.1 22:00（暂定）

## 活动评分

本次活动正如标题所示，我们会从作品的艺术性，代码难度和是否 vtuber 相关三个维度来考虑作品。

本次活动讲接受开放投票，只要你拥有 GitHub 账户都可以对任意作品投票点赞来表达你的喜爱和支持。我会在 repo 的 issues 中列出所有的作品的最终运行效果（一个作品一个单独的回复），然后每个人通过对该回复 Pick heart emoji 来投票。我们会根据诸位的投票来选取最受欢迎的几份作品。

除此之外，本次会分别设立最具技术奖/最具艺术奖和最dd奖。分别奖励在三个维度做的最棒的三份作品。该奖项评选则由 YSTC board members 评选得出。

## 活动奖励

首先，十分抱歉因为 YSTC 刚刚开始活动，我们目前暂无给大家提供任何实物奖品的能力。本次活动会参考最终参与人数，按比例选取投票最高的几位人员获得 YSTC master member 晋升资格（三位特别奖项获得者同样拥有资格）。三位特别奖项获得者除了这些外，还将获得由我个人送出的 SHENZHEN I/O 游戏一份。
