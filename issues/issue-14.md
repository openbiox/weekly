---
date: 2023-02-22
comments: true
---

# 生信爱好者周刊（第 14 期）：为什么有些朋友，走着走着就散了

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/openbiox/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/openbiox/weekly/issues/374)

## 封面图

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-26/1640522450525-image.png)


第三代Xenobot(红色)和松散干细胞组成的聚集体(绿色) 。（[图片来源](https://mp.weixin.qq.com/s/ofgiKEyVSZ965hswKT1rtA)）

> 去年1月，美国佛蒙特大学、塔夫斯大学和哈佛大学的4名科学家共同开发首个活体机器人Xenobot。从外面看起来，它只是一个毫米大小的细胞团，但却相当厉害。它能朝特定的方向移动，具有强大的延展性和可塑性，在被切开后，还能自行复原。


## 本周话题：[为什么有些朋友，走着走着就散了](https://mp.weixin.qq.com/s/Q-EVrYONuj3iypiOb4qw1g)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-26/1640522370962-image.png)

>在各奔前程的过程中，旧友不断流失，但在新的环境里，又未能建立起可以弥补这种流失的关系。是这两者的合力，共同酿成了“失友”的感受。
>
>真正可贵和难得的情谊，不会轻易被时空打败。哪怕人生的际遇疏离化了一些关系，哪怕彼此的联系不如往日频繁，哪怕已经许久未见，哪怕不能第一时间知晓你的近况，但在我需要你的时候，我知道你就在那里。
>
>别离是人生常态，身边的人也确实来来往往更迭不断，但总有一些人，已经陪伴了我们很久，还将陪伴我们更久。


## 生信科技动态

1、[Genome Medicine | 人工智能临床决策工具GEM，通过快速基因组注释助力遗传病诊断](https://mp.weixin.qq.com/s/qSqpEpRqQOK1XcduuMYAEw)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-26/1640521870171-image.png)

Fabric Genomics Inc的Mark Yandell研究团队联合Martin G. Reese研究团队，开发了一种用于快速基因组注释的临床决策支持工具——Fabric GEM。GEM是一种新型的基于人工智能的临床决策支持工具。研究团队在回顾性队列中对GEM进行的基准测试显示，GEM能将90%以上的致病基因排在优先候选基因中，几乎囊括了所有变异类型。此外，结合深层表型分析发现，GEM可以实现快速、准确、全面地基于WGS和WES数据进行诊断，有效降低了成本并加快变异评估。 

2、[Nature Biotechnology | Genentech公司开发TraCe-seq系统用于识别癌症药物反应的转录特征](https://mp.weixin.qq.com/s/OUMbfVLvblQOE30rt0SdVw)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-26/1640521992172-image.png)

针对致癌驱动基因突变的靶向治疗为癌症患者提供了显著的临床获益，为精准医疗带来了巨大的希望。但并非所有癌症患者都能产生治疗反应，其他既存的和获得的耐药机制对患者的整体反应和药效持久性提出了巨大的挑战。近年来，靶向蛋白降解这一新的作用机制 (MOA) 引起了人们的广泛关注。与传统的基于占位的靶向抑制不同，异质双功能靶向蛋白降解物能够同时将E3泛素连接酶富集到目标位置，并通过泛素介导的蛋白质水解诱导靶向降解的分子，并被证明在特定情况下优于单独的酶抑制。但目前尚不清楚双作用抑制剂-降解剂是否具有普遍优势。 

为了解决上述难题，美国Genentech公司研究团队开发了一个名为TraCe-seq (Tracking differential clonal response by scRNA-seq) 的系统，能够同时跟踪肿瘤起源并比较肿瘤细胞对不同疗法的即时反应，大大加速药物反应机制或者耐药机制的研究。

3、[Genome Biology | 精准解析SNV、SV和甲基化的综合性分析方法PRINCESS，填补基因组学研究空白](https://github.com/openbiox/weekly/issues/173)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-26/1640522190392-image.png)

研究团队针对目前测序数据分析短板（对于长读段数据中染色体结构变异的综合分析）进行了补充，开发了一种可以精准解析SNV、InDel、SV和甲基化数据的单倍型分析方法：PRINCESS。PRINCESS能够以最低的成本为每个样本提供全面的、单倍型解析结果。


## 文章

1、[GO富集分析你画的柱状图可能误导你了](https://mp.weixin.qq.com/s/6sHM3caX2gGGfLlBaLrmAQ)

这篇文章介绍了GO功能富集分析的冗余性和解决方法。

```r
ego2 <- simplify(ego, cutoff=0.7, by="p.adjust", select_fun=min)
```

2、[4 Tips to Make Your Shiny Dashboard Faster](https://www.rstudio.com/blog/4-tips-to-make-your-shiny-dashboard-faster/)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-26/1640521359944-image.png)

- 找出Shiny应用在哪里花了时间
- 使用更快的函数
- 注意Shiny应用中的对象作用域
- 使用缓存操作

3、[Tired: PCA + kmeans, Wired: UMAP + GMM](https://www.rstudio.com/blog/4-tips-to-make-your-shiny-dashboard-faster/)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-26/1640521681625-image.png)

这篇文章比对了两种将降维和聚类结合的策略。相比PCA+Kmeans，作者跟推荐UMAP+GMM。

## 工具

1、[crosslink - 分组节点的网络可视化跟踪](https://github.com/zzwch/crosslink)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-26/1640522698055-image.png)

2、[readpaper - 论文阅读管理](https://mp.weixin.qq.com/s/xc5rTytLwEWXoW5pnBxIdA)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-26/1640522769577-image.png)

3、[tidyHeatmap - 用整洁的数据框架简单地绘制热图](https://github.com/stemangiola/tidyHeatmap)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-26/1640522845626-image.png)


## 资源

1、[GitHub 上最大的算法开源库：The Algorithms](https://the-algorithms.com/zh_Hans)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-26/1640521004771-image.png)

在这个网站上面，收录了包括 Python、Java、C++、JavaScript、Go 等多种主流编程语言的算法代码实现。
你可以通过搜索框，快速寻找自己需要学习的算法。

2、[数据集成工具的基准分析](https://github.com/theislab/scib)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-26/1640521183422-image.png)


这个存储库包含用于数据集成工具基准测试研究的代码。在我们的研究中，我们在85批基因表达和染色质可及性数据上对16种方法进行了基准测试，包括4种预处理步骤组合，一共68种方法组合。


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

感谢以下读者往期的赞赏：

- 李浩
- Robin

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）

