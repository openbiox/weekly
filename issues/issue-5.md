---
date: 2023-02-13
comments: true
---

# 生信爱好者周刊（第 5 期）：相关非因果

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/ShixiangWang/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/ShixiangWang/weekly/issues/93)

## 封面图


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634370734597-image.png)

智慧校园。（[via](https://twitter.com/jmuiuc/status/1447585346519281664)）

## 本周话题：相关非因果

本期话题与今年的最后一个诺贝尔奖有关。

加州大学伯克利分校的David Card、麻省理工学院的Joshua D. Angrist和斯坦福大学Guido W. Imbens，共同获得了今年的诺贝尔经济学奖。

瑞典皇家科学院表彰他们在劳动经济学和**从自然实验中分析因果关系**方面做出的贡献。

初入生信的萌新，可能还在各种技术贴和教程里畅游，但如果稍有些科研经验，可能就会对**因果话题**产生疑惑和进行自己的探索。这是因为，当我们完成一项课题，所需要总结汇集产生的结论往往是**因果**，而绝大部分我们进行的数据分析只能产生**相关**。

**相关非因果，因果必相关。相关到因果的过渡在如今的生物医学科研中往往困难重重**。你与今天的话题有哪些疑惑和共鸣？欢迎在评论讨论区留言。

目前科研中你看到的主要的因果结论生成形式是依赖背景进行因果逻辑推断。在统计学方法中，通过贝叶斯体系可以直接从概率中推断因果。而其他领域，从相关到因果，可能真正产生一些根本性变革。

> Judea Pearl与今年的诺贝尔获奖者颇有渊源，他因为开发因果推理的算法在AI上的贡献，而获得图灵奖。
>
> 不过Pearl却是其中两位获奖者的坚定反对者。
> 因为Pearl认为，他们的研究违反了因果推理的两个基本定律，即反事实定律和条件独立定律。

推荐感兴趣的读者看下《为什么：因果关系的新科学》一书，目前我也只是初步看了一点内容，从其他领域的系统理论中我们有可能获取当前科研进步的新力量。


## 生信科技动态

1、[Bioc Asia 2021会议近期举行](https://biocasia2021.bioconductor.org/)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634372135028-iShot2021-10-16%2016.15.11.png)



从去年开始（没记错的话），Bioconductor每年针对亚洲区间举办年度会议（线上）。今年的会议会在11月1号-4号举行，会议安排请查看[Schedule](https://biocasia2021.bioconductor.org/schedule/)。除了会议报告，还有很多的[workshops](https://biocasia2021.bioconductor.org/workshops/)，新手读者朋友们看看是否有感兴趣的内容。

**中文workshop**：

- (Day1) 陈金金 Jinjin Chen: “Gene-set Analysis Workshop”
- (Day2) 孙建强 Jianqiang Sun: “Introduction to image recognition with deep learning”
- (Day3) 孙建强 Jianqiang Sun: “Prediction of CRISPR guide RNA activity with deep learning”
- (Day4) 周烺 Lang Chau: “Visualization and exploration of MSAs and associated data with ggmsa”

2、[QB期刊将直播GWAS最新研究进展](https://mp.weixin.qq.com/s/q5yxgftDpJY3S8yY4B7SUQ)

2005年，Hoh及其同事首次成功利用基因组关联研究（Genome Wide Association Study, GWAS）鉴定了与年龄相关的黄斑变性主要基因。在随后的16年中，众多研究报道了数十万种遗传变异与数千种性状和疾病之间的可重复关联信号。世界各地开发了越来越多的生物库，参与者多达100万人，以期通过GWAS分析促进复杂性状的遗传研究。此外，已启动的许多联盟项目收集的各种类型数据对GWAS分析具有重要价值。这些丰富的数据给科学家们在数据管理、计算、分析、集成和解释方面带来了巨大的机遇和挑战。由Quantitative Biology （QB）期刊发起，美国耶鲁大学的赵宏宇教授，清华大学的侯琳教授，美国威斯康星大学麦迪逊分校的吕琼石教授和香港科技大学的杨灿教授共同组织了QB期刊2021年第二期的GWAS专辑（点击文末“阅读原文”查看本专辑所有文章）及本次网络研讨会。6位国内外专家将介绍GWAS最新科研进展和互联网时代的应用进展，并与参会专家一起展开深入交流。欢迎从事GWAS相关研究的老师和同学积极参与。（来源：公众号「QB期刊」）

本次会议由Quantitative Biology （QB）期刊编辑部主办，授权蔻享学术进行网络直播（https://www.koushare.com/frontiers/qb）。扫描加入下面微信群，将实时获取最新会议通知。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634372533967-image.png)

**直播时间**：2021年11月13日上午10：00 - 12：00


3、[武大联合Elsevier创办生物医学期刊Cell Insight](https://mp.weixin.qq.com/s/2gmmVHdeq-BKmfSKQtQuFw)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634372387589-iShot2021-10-16%2016.19.39.png)


Cell Insight 是一本开放获取双月刊，以打造“世界一流期刊”为目标，以“推动中国科技期刊高质量发展”为理念，重点报道生物医学领域的最新科学与技术成果。

Cell Insight由中科院院士、武汉大学舒红兵教授担任主编，病毒学国家重点实验室主任、武汉大学蓝柯教授担任执行主编，由来自中国、美国、加拿大、英国、澳大利亚、日本、意大利、比利时、韩国等全球著名学术机构的40余位学者担任编委。

Cell Insight 将提供专业且快速的论文审稿流程，论文投稿一周内决定是否送审，对送审稿件在二至四周内返回审稿意见，接受稿件 1 月内在线发表，同时在微信公众号加以推送。此外，Cell Insight 还对某些高水平、存在激烈竞争的稿件提供绿色通道快速发表。

Cell Insight 将于 2022 年 1 月正式出版第一期，创刊前三年所发表的文章均免除文章出版费。(来源：公众号「科研大匠」)


## 文章


1、[一条指令，修改ggplot所有的字体](https://mp.weixin.qq.com/s/V8GSwWrNdl4t8zQ4bmQN_A)

Y叔编写函数`set_font()`解决一次性字体设定。

```R
g2 <- set_font(p, 
              family="Arial", 
              fontface="italic")
```


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634372748527-image.png)

（来源：公众号「YuLabSMU」）

2、[Python 3.10发布：优化错误调试，新增match语句等](https://mp.weixin.qq.com/s/5UJqgdWrDBVIWGMQcBLXNQ)

**更好的错误跟踪**

Python3.10 新增两个特性，可以更好地处理错误，即更好的错误消息和用于调试的精确行号。以下列代码为例，代码中包含字典和函数，然而这段代码显示没有关闭字典。

```python
some_dict = {1: "jack", 2: "john", 3: "james" ,
a_results = a_useful_function()
```

旧版本错误显示：


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634372916624-image.png)

新版本错误显示：

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634372933810-image.png)

Python 3.10 关于错误跟踪新特性将有助于加快调试速度，并减少初学者挫败感。

**引入结构模式匹配**

如果你已经使用过 C++ 等其他编程语言，或许你会期待 Python 有 switch 语句，这样就不必通过长的 if、 elif、 elif…. else 语句来完成任务。Python 3.10 的一个新特性是增加了结构模式匹配，或者换句话说，增加了 match case 语句，它的语法如下：

```python
match subject:
    case <patt1>:
        <act1>
    case <patt2>:
        <act2>
    case <patt3>:
        <act3>
    case _:
        <action_default>
```

（来源：公众号「Python开发者」）

3、临床研究[阴性](https://mp.weixin.qq.com/s/TGEYC42OLUtNSBzMXrhIyg)[阳性](https://mp.weixin.qq.com/s/sWJgSTmNe_JSFK2EBASZXA)结果解读

**对结果和研究的一些有益的思考策略**。

阳性结果，思考：

1. P＜0.05就足够好吗？
2. 获益程度有多大？
3. 临床上，这一主要研究终点重要吗？
4. 获得次要研究终点的支持了吗？
5. 重要的亚组获益一致吗？
6. 样本含量足够大？结论足够可信吗？
7. 研究被提前终止了吗？
8. 安全性问题会抵消获益吗？
9. 疗效及安全性的均衡是患者特异性的吗？
10. 研究设计及执行存在缺陷吗？
11. 研究结果适用于我的患者吗？

阴性结果，思考：

1. 有潜在获益的趋势吗？
2. 把握度是否足够
3. 主要研究终点是否合适(被准确定义)
4. 研究对象是否合理？
5. 治疗剂量是否合理？
6. 研究执行过程是否有缺陷？
7. 非劣效结论有意义吗？
8. 亚组分析是否有积极信号？
9. 次要研究终点有阳性发现吗？
10. 改变分析方式有帮助吗？
11. 有更充分的外部数据吗？
12. 是否有充分的生物学依据支持这一治疗？

4、[基于 KDE 的最佳 Linux 发行版]()

KDE 是目前最具定制性和最快速的桌面环境之一。虽然你可以随时安装 KDE，但最好选择一个 KDE 开箱即用的 Linux 发行版。

在这里，作者列出一些最好的基于 KDE 的 Linux 发行版。

例如，KDE Neon


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634373418997-image.png)

5、[王立铭：进化论是地球上唯一的成功学](https://mp.weixin.qq.com/s/200k7tVecyZ3XjD7zVAshw)

虽然这是一篇推销文，但其中作者提及的几个观点值得大家阅读和思考。

> 在生物的自私本能和环境资源的相对匮乏这一对矛盾的推动下，进化履带上的四根链条——可遗传的变异、生存竞争、自然选择和生殖隔离——滚滚开动，在混乱的大自然中建立生命的秩序，并逐步自我完善和分叉，从一颗种子长成枝繁叶茂的生命之树。

6、[8种方法可视化你的单细胞基因集打分](https://mp.weixin.qq.com/s/ohfMH6bUc7wN0EaWrcfN-g)

这期最后推荐的一篇文章以「生信技能树」的一篇近期推文收尾：校正批次效应后的数据，会掩盖部分真实的生物学差异。但校正批次效应后的数据是否能用于基因集富集分析，以及样本之间的批次效应是否会影响基因富集分析结果仍然是一个争论。文章重新审视了9种常见的功能集打分方法：GSEA、GSVA、PLAGE、Zscore、AddModuleScore、ssGSEA、AUCell、UCell和singscore。


## 工具

1、[gggenes：ggplot2绘制基因结构图](https://github.com/wilkox/gggenes)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634373880951-image.png)

2、[shinyAce](https://github.com/trestletech/shinyAce)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634379338290-image.png)

shinyAce包使Shiny应用程序开发人员能够在他们的应用程序中使用Ace文本编辑器。

3、[ggpubr](https://github.com/kassambara/ggpubr/) - 基于ggplot2的publication ready图生成


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634379494372-image.png)

“ggpubr”包提供了一些易于使用的函数，用于创建和定制基于“ggplot2”的出版准备图，包括点图、提琴图、条形图等。这个包中文搜索已经有非常非常多的介绍和使用推文了。

4、[ggstatsplot](https://github.com/IndrajeetPatil/ggstatsplot) - 基ggplot2于带有统计细节的图


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634379776629-image.png)

对于发表文章非常推荐的一个绘图包，详细地展示统计细节而不仅仅只有显著性。支持常见的分析绘图。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634379845707-iShot2021-10-16%2018.23.49.png)

5、[flomo](https://mp.weixin.qq.com/s/6K9koO8wMGTumwXqfJndHQ) - 快速记录碎片知识与灵感的工具。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634379953995-image.png)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634379984145-image.png)



（[@mugpeng](https://github.com/mugpeng)投稿）

## 资源

1、[biofast](https://github.com/lh3/biofast) - 对生物信息学中常见任务的编程语言/实现进行基准测试

该仓库可以查看对于基本的生信处理任务，不同编程语言的计算性能。这对于初学者学习合适的编程语言可能提供帮助。

下面展示的是FASTQ解析的结果：

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634380115843-iShot2021-10-16%2018.28.15.png)

2、[肿瘤免疫学](https://mp.weixin.qq.com/mp/appmsgalbum?action=getalbum&__biz=MzAwMDUzNTIxNA==&scene=1&album_id=2018077716062715908&count=3#wechat_redirect)

正在进行的肿瘤免疫学系统推文。（来源：公众号「OncoLab」）

3、[类似GitBook在线文档创作平台汇总](https://mp.weixin.qq.com/s/FVSnkTlSfXbODMW5woF6QQ)


4、[Creating Beautiful Data Visualizations in R: a ggplot2 Crash Course](https://sctyner.github.io/talks/Conferences/user2020/#1)（英文在线幻灯片）


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-16/1634380451204-iShot2021-10-16%2018.33.33.png)


详细的ggplot2介绍课件。


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

感谢以下往期赞赏/捐赠的读者：

- Robin
- 张林

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）
