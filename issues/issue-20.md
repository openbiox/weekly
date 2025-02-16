---
date: 2023-02-28
comments: true
---

# 生信爱好者周刊（第 20 期）：科研苦行

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/openbiox/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/openbiox/weekly/issues/496)

## 封面图


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-6/1646580222458-1646580162366-image.png)

现代与自然的设计结合：裂开的大楼（[via](https://www.globalconstructionreview.com/work-begins-on-mad-architects-cracked-denver-residential-tower/)）。



## 本周话题：[科研苦行](https://mp.weixin.qq.com/s/NLmG2GvEKOssEgGtHKUGdQ)

“双料”院士王晓东背着一袋尿素要进研究所大楼，却被拒之门外；同学在认真做学术报告，台下的王晓东却惊得大跌眼镜；天台上，王晓东身穿实验服，抱着电吉他，前仰后合地忘情弹奏。

这些场景都出自近日爆火的一段视频，由北京生命科学研究所（NIBS）所长、百济神州创始人王晓东带领他的学生“整点儿奇活”，最终制成贺岁大片《苦行僧》科研版和王晓东solo大作《晓东RAP》！

这是课题组第七次放送贺岁视频，融合了摇滚和RAP，并用黑色幽默的形式将时下的热梗融入科研，展现了科研“苦行僧”在梦想与现实，杂念和初心之间的“斗争”和“修行”。

科研是苦是乐，科研人心中评说～你是否也会用类似的方式表达与科研“欲罢不能”的情感？

## 生信科技动态

1、[Briefings in Bioinformatics | 高歌课题组建立人类RNA转录本编码能力定量](https://mp.weixin.qq.com/s/BCwrvwEaFOUD7tRQmMFQFQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-6/1646580441519-image.png)


高歌课题组收集了发表于公共数据库22个不同细胞类型的人类Ribo-seq/RNA-seq配对数据，并进行系统挖掘分析，对数据中101,170条转录本的翻译状态进行了严格判定。其中，46%的转录本为编码，43%为非编码。值得注意的是，研究团队发现11%的转录本，在不同细胞中呈现不同的翻译状态，即在部分细胞中编码，而在另一部分细胞中非编码。研究团队将其命名为“环境依赖编码转录本”(context-dependent coding transcripts, CDCTs)。

在此基础上，高歌课题组应用数据驱动的特征选择算法，综合运用序列内生和细胞环境特征，建立了人类RNA转录本编码能力跨细胞定量模型RiboCalc，实现了对人类转录本在多种细胞环境下的编码能力的高精度预测(r = 0.81)。模型分析显示，转录本的序列和所在细胞环境都对编码能力的决定起到了重要作用，提示转录本的编码能力不应被简化为单纯的编码/非编码二分分类，而是一个依赖于环境的连续定量指标。值得注意的是，自14年以来即有若干工作报导一些非编码RNA可以在特定条件下结合核糖体甚至产生肽段(如[1])，RiboCalc分析显示这些RNA转录本与不结合核糖体的RNA相比编码能力分数显著高，为理解相关现象提供了新的线索。

2、[Bioinformatics | HPODNets: 预测人类蛋白质-表型关联的深度图卷积网络](https://mp.weixin.qq.com/s/VBh1QsRJz8983IIn5iBAuQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-6/1646580506373-image.png)

破解人类基因/蛋白质与异常表型之间的关系，对疾病的预防、诊断和治疗具有重要意义。人类表型本体 (HPO)是描述人类疾病中遇到的表型异常的标准化词汇表。但是目前的HPO注释是不完整的。因此有必要预测人类蛋白质-表型关联。就目前的蛋白质标注计算方法而言 (如功能注释)，有三个重要特征：1)多重网络输入，2)半监督学习，3)深度图卷积网络 (GCN)，而目前还没有包含所有这些特征的方法来预测人类蛋白质的HPO注释。

作者开发了具有上述三个特征的预测模型：HPODNets，用于预测人类蛋白质-表型关联。HPODNets采用8层GCN从多个蛋白质相互作用网络中获取高阶拓扑信息。实验结果表明HPODNets的有效性，在蛋白质功能预测方面优于7种最先进的方法。

3、[Nature Machine Intelligence | 在实验中恢复转录组范围内RNA结构谱丢失信号的方法](https://mp.weixin.qq.com/s/GvfCJtOSHvHxZWc5gGQAJQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-6/1646580619230-image.png)


基于测序的 RNA 结构探测可以生成 RNA 二级结构的全转录组谱。需要足够的结构覆盖才能获得关于 RNA 结构和功能的客观见解，但探测方法通常会产生不均匀的覆盖，在许多转录本中缺少结构分数。

为了克服这一障碍，清华大学的研究人员开发了 StructureImpute，这是一种受计算机视觉深度补全启发的深度学习框架，它将 RNA 序列与相邻核苷酸的可用 RNA 结构信息相结合，以推断缺失的结构分数。


## 文章

1、[比较微生物组中的差异分析方法](https://mp.weixin.qq.com/s/SjIoBofoI2T7x_VtsgV7FA)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-6/1646580833696-image.png)


2、[肿瘤中的突变表位](https://mp.weixin.qq.com/s/LU96fW1oF9spTMNh_IgC2w)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-6/1646580778426-image.png)


3、[谁是Python/R中最强Dashboard APP开发工具？](https://zhuanlan.zhihu.com/p/429709268)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-6/1646580802423-image.png)



## 工具

1、[R包sessioninfo - 更好地打印你的会话信息](https://github.com/r-lib/sessioninfo)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-6/1646580899341-image.png)

2、[wifi-password - Get the password of the wifi you're on (bash)](https://github.com/rauchg/wifi-password)

3、[croc - Easily and securely send things from one computer to another](https://github.com/schollz/croc)

命令行安装：

```sh
curl https://getcroc.schollz.com | bash
```


## 资源

1、[UCR基因组研究所手册](http://manuals.bioinformatics.ucr.edu/)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-6/1646581139744-image.png)

2、[图书 - Modern Statistics with R：From wrangling and exploring data to inference and predictive modelling](http://www.modernstatisticswithr.com/)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-6/1646581212357-image.png)


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

感谢以下读者往期的赞赏：

- 谢子敬

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）

