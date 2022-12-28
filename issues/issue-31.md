---
comments: true
---

# 生信爱好者周刊（第 31 期）：Openbiox 生物信息学社区 2022 拟开展项目，正式招募 ！

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo) | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community)

## 封面图


![](https://files.mdnice.com/user/4331/bc9f86ef-7226-4428-8b0b-31587dceb1b7.png)

官网地址：<https://openbiox.org/>

## 本周话题：[Openbiox 生物信息学社区 2022 拟开展项目，正式招募 ！](https://mp.weixin.qq.com/s/v4Hg_NzK9-LUpzV7jfxskg)

Openbiox 生物信息学开源社区由国内外知名高校在读研究生、博士后和研究人员于 2019 年共同发起和建设。在此，我们向科学社区发起新一轮生物信息学协作项目，以期为大家提供更多有用的生物信息学工具/内容和有意义的研究成果。

感兴趣的读者和朋友请阅读原文并通过<lee_jianfeng@openbiox.org>联系剑峰。

## 生信科技动态

1、[Cell | 基于50种癌症类型绘制肿瘤-基因-转移谱，揭示癌症转移模式基因组特征](https://mp.weixin.qq.com/s/VKVa8Dsz2Is52M-AZkoMxA)


![](https://files.mdnice.com/user/4331/fb4ada45-2cda-4947-bf6a-0166a7773133.png)

本文研究团队对约25,000名患者的肿瘤基因组图谱和转移结果的临床信息进行了分析，共包含50种不同癌症类型，揭示了不同转移模式的基因组特征，绘制了肿瘤-基因-转移谱。研究发现，癌症转移不是由基因突变驱动的，而是由癌细胞与周围环境中的正常细胞相互作用发生的表观遗传学变化驱动的。


2、[Briefings in Bioinformatics | 王秀杰/裴小兵合作开发单细胞组学细胞标记基因鉴定算法COSG](https://mp.weixin.qq.com/s/RZZ1Y6yR_mGwgheNmvwiNA)


![](https://files.mdnice.com/user/4331/550acab3-47bc-4d70-8ece-85c84245a5a5.png)


本研究提出了一种基于余弦相似度的方法COSG，该方法能在单细胞RNA测序数据、单细胞ATAC测序数据和空间转录组数据中更准确和快速地鉴定出细胞标记基因。

> COSG程序的代码已通过GitHub网站开源发布。COSG程序的Python语言版本和R语言版本的代码链接分别为https://github.com/genecell/COSG和https://github.com/genecell/COSGR

3、[生命科学领域首部AI辅助创作图书亮相上科大](https://mp.weixin.qq.com/s/ALed3HWCSPdz-BKpSluMZg)


![](https://files.mdnice.com/user/4331/60ac661d-dbfc-4f49-903e-47c0d8603ff6.png)


信息时代，每年发表学术论文的数量呈井喷式增长。如何帮助研究人员快速了解科学进展前沿、帮助领域内的青年科研人员和学生快速掌握研究领域核心知识体系面临着重大挑战。为解决这一问题，学术出版机构施普林格-自然（Springer Nature）出版集团在近几年开发了一套基于人工智能辅助的文献知识总结系统Dimensions Autosummarizer（DA），以辅助研究人员进行图书出版。


## 文章

1、[一文讲清肠道菌对免疫的影响机制](https://mp.weixin.qq.com/s/IxZQYI2VnwQ7TzJdMG6bqQ)


![](https://files.mdnice.com/user/4331/45270059-9cf6-47b8-8932-dac1fbc8ad18.png)


2、[gglmannotate包——添加线形回归统计指标](https://mp.weixin.qq.com/s/HGHk8Q_KH6vwHMCcheO4EA)

这种工具更具备组合性（相比ggpubr）。

![](https://files.mdnice.com/user/4331/90baca86-2d8d-4feb-9eab-34a68a9775c5.png)

3、[Data Organization in Spreadsheets](https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1375989)

本文介绍如何使用Excel的表格整理数据的一些原则、建议。

## 工具

1、[CBNplot - 你的富集分析好助手](https://mp.weixin.qq.com/s/lMhVxC-00bC_JY1BoXFY9Q)

这个包的输入，就是clusterProfiler系列包的输出，它内部再调用bnlearn包来做贝叶斯推断，然后画网络图。

![](https://files.mdnice.com/user/4331/1d5b2f75-2888-4d8b-92f5-c18af1a464e8.png)


2、[unglue - 逆向glue操作](https://github.com/moodymudskipper/unglue)

```r
library(unglue)
library(glue)
library(magrittr)
library(utils)
glued_data <- head(mtcars) %>% glue_data("{rownames(.)} has {hp} hp")
glued_data
#> Mazda RX4 has 110 hp
#> Mazda RX4 Wag has 110 hp
#> Datsun 710 has 93 hp
#> Hornet 4 Drive has 110 hp
#> Hornet Sportabout has 175 hp
#> Valiant has 105 hp
unglue_data(glued_data, "{rownames(.)} has {hp} hp")
#>         rownames...  hp
#> 1         Mazda RX4 110
#> 2     Mazda RX4 Wag 110
#> 3        Datsun 710  93
#> 4    Hornet 4 Drive 110
#> 5 Hornet Sportabout 175
#> 6           Valiant 105
```

3、[escape - Easy single cell analysis platform for enrichment](https://github.com/ncborcherding/escape)

提供一个单细胞版本的富集分析工具。

![](https://files.mdnice.com/user/4331/10e98272-1359-4401-9da1-741aa723921c.png)


5、[谷歌简明搜索导航](https://search.fuyeor.com/zh-cn/Google)

适合没有梯子的同学们。

## 资源

1、[生信基础知识100讲](https://mp.weixin.qq.com/s/Gr_0H4-GaTYkgUkbNHcMcg)

2、[超过1000本的计算机经典书籍分享](https://github.com/forthespada/CS-Books)


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648291334186-bd3390be-c83c-4396-aabd-ca39f588c15d.png)

感谢以下读者往期的赞赏：

- 🦀️

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

