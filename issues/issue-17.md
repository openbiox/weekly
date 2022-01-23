# 生信爱好者周刊（第 17 期）：Cox比例风险模型著作者离世

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/ShixiangWang/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/ShixiangWang/weekly/issues/439)

## 封面图


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-23/1642930486202-image.png)

由ezcox包所绘制的Cox回归森林图（[via](https://shixiangwang.github.io/ezcox/articles/ezforest.html)）。


## 本周话题：[Cox比例风险模型著作者离世](https://mp.weixin.qq.com/s/fFYTr2P0BFPtOBlY3v0ncQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-23/1642930408444-image.png)


戴维·罗斯贝·科克斯爵士，Sir David Roxbee Cox，1924年7月15日－2022），英国著名统计学家，英国皇家学会院士暨英国社会科学院院士，美国科学院、丹麦皇家科学院外籍院士。曾任国际统计协会、伯努利数理统计与概率学会、英国皇家统计学会主席。主要学术贡献包括Cox过程和影响深远且应用广泛的Cox比例风险模型等。

> 目前的临床医学研究、生物信息学研究都从Cox模型中颇为受益，它是鉴别变量对生存数据影响力的有效手段。科学家追求的理想应就是这种有著作流芳百世，福泽后人。

## 生信科技动态

1、[两院院士评选“2021年中国/世界十大科技进展新闻”揭晓](https://mp.weixin.qq.com/s/DxXqaHZ8e6tBGLvoWgadiA)

这里仅介绍一例，其余读者可以通过链接文章阅读。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-23/1642930937740-image.png)

奥地利科学院生物学家Sasha Mendjan和团队使用人类多能干细胞培养出芝麻大小的心脏模型，又称心脏线。它可以自发地进行组织，在不需要实验支架的情况下发展出一个中空的心房。Mendjan团队以特定的顺序激活所有参与胚胎心脏发育的6个已知信号通路，诱导干细胞自我组织。

2、[Nucleic Acids Research | 疗效药物靶标的比较性研究与数据平台构建](https://mp.weixin.qq.com/s/rys-1FXn5ZmqilTz1iD-pQ)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-23/1642931037487-image.png)

在人工智能药学急速发展的今天，迫切需要累积针对药靶的比较性研究数据，以推进基于大数据的AI药学研究。浙江大学药学院朱峰教授、医学院裘云庆教授和清华大学深圳研究生院陈宇综教授合作开展了全面的药靶比较性研究。研究结果涵盖了所有FDA已批准药物作用的、一万余个临床研究药物作用的、两万五千余个临床前和实验研究中药物作用的药靶。（https://idrblab.org/ttd/）


3、[NEJM | 超快纳米孔技术8小时测序基因组，找到致病基因，挽救生命](https://mp.weixin.qq.com/s/ssk4y8s2wFZv5Kz_frj0Ig)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-23/1642931433302-image.png)

在对病人进行基因组测序并返回结果上，耗时几周时间，已经被大多数医生认为是快速了。那么，能否进一步将耗时缩短到几天甚至几个小时呢？本文研究团队开发了一种新的超快速基因组测序方法，用于诊断罕见的遗传疾病，平均仅需耗时8小时，这在标准的临床护理中前所未见。快速诊断意味着病人在重症监护病房花费的时间更短，需要的检查更少，恢复得更快，在护理上花费更少。更重要的是，这种更快的测序技术并没有牺牲准确性，测序结果依旧可靠。


## 文章

1、[ggbreak让你更好地利用画图空间](https://mp.weixin.qq.com/s/1pVrOdUr5YzO-xBi5rndwQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-23/1642931593526-image.png)


2、[如何使用 ggplot2 绘制双轴分离图？](https://mp.weixin.qq.com/s/QiMHA10X8nGtK5iOH4armQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-23/1642931502937-image.png)


3、[系统生物学中的建模：因果理解先于预测?](https://mp.weixin.qq.com/s/0eLe0BJmke_3kV3J4RUsUQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-23/1642931738678-image.png)


技术的进展为我们提供了大规模的生物数据，但要如何从中获得对生物学机制的理解？一方面我们可以使用来自科学文献的先验知识，但这种知识驱动方法往往基于特定的情境，不适合进行因果关系预测；另一方面，纯数据驱动的推断方法专注于创建特定情境下的预测模型，却很难进行有意义的生物学解释。

2021年6月，发表于Cell 旗下Patterns 杂志的论文“蛋白质组中的因果相互作用：分子数据遇见通路知识”，介绍了一款名为 CausalPath 的因果推断工具，能够结合新的测量结果与先验知识，推断蛋白质组数据中因果信号的相互作用。这种方法模仿了生物学家用先验知识解释新的实验数据的传统方法，但可以在数十万反应的规模上进行。

## 工具

1、[PyWebIO - 像数据分析一样写 Web 页面](https://mp.weixin.qq.com/s/zQSCeYmC0Q5AQKwuv3n3bA)

2、[Omni - 一款 Chrome 快捷键管理工具](https://mp.weixin.qq.com/s/cS7m9EAox53aD-IIY0w66g)

它拥有 50 多项特性，为提高生产力而生。主要目的，是让你可以像极客一样，通过键盘快捷键来使用 Chrome。

3、[emayili - 发邮件的R包](https://github.com/datawookie/emayili)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-23/1642931952238-image.png)


## 资源

1、[GitHub Repo: 教师的世界](https://github.com/crazyhottommy/The-world-of-faculty)

一些教职相关的资料。

2、[本文近期整理分享的图书资料，适合系统学习](http://42.192.87.178:3030/)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-23/1642932112712-image.png)



## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

感谢以下读者往期的赞赏：

- Robin

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）

