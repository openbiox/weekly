---
comments: true
---

# 生信爱好者周刊（第 68 期）：颠覆性大滑坡，科研还能有实质创新吗？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/ShixiangWang/weekly/discussions)

## 封面图

![](https://files.mdnice.com/user/5208/88c49ea9-4c63-42ea-85bf-1f93d29e813d.png)

## 本周话题：[颠覆性大滑坡，科研还能有实质创新吗？](https://mp.weixin.qq.com/s/O0GNf6XtPBovOwqIA9UGjw)
> 科幻小说《三体》讲述了这样一个情节：通过干扰粒子物理研究，三体文明“封锁”了人类的科技发展。此后，人类社会虽仍有各种技术进步，却不再有根本性的科技变革。美国明尼苏达大学的Michael Park、Russell J. Funk与亚利桑那大学的Erin Leahey近日在**Nature**发表文章称：“通过对六个大型数据库中的4500万篇论文和390 万项专利进行分析，我们发现论文和专利越来越难以颠覆既往，也难以引领科技进入新方向。” 研究人员认为，这种颠覆性进展的缺位，反映了科技发展性质的根本性转向。

- 论文链接：https://www.nature.com/articles/s41586-022-05543-x

@He-Kai-fly - 科学研究固然需要变革性进展，但累积式渐进，才是切实推动社会进步的基石。

## 生信研究

1、[Advance Funtional Materials | 一款新型隐形眼镜通过快速捕获细胞的“垃圾袋”来进行癌症诊断](https://github.com/ShixiangWang/weekly/issues/950)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303081631499.png)

> 2022年8月10日， 发表在《Advance Funtional Materials》上的一项新研究中，来自**寺崎生物医学创新研究所（TIBI）领导的研究团队开发了一种智能隐形眼镜，该镜片嵌有与抗体结合的微型腔室，可以很容易地捕获泪液中的外泌体，从而为癌症预筛查提供了一种简单、快速、灵敏、经济、无创的支持性诊断平台。**该团队表示，这一突破有望为廉价的“一刀切”式疾病筛查项目打开大门。

- 论文链接：https://doi.org/10.1002/adfm.202206620



2、[Nature Biotechnology | 新型单碱基分辨率测序方法同时获取DNA的遗传和表观遗传信息](https://mp.weixin.qq.com/s/XOi6ezNnIpBjiDkS2xjtZw)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303101710011.png)

>  英国剑桥大学研究团队提出了一种新的单碱基分辨率全基因组测序方法，在一个工作流程中对完整的遗传学和两种最常见的胞嘧啶修饰进行测序。这种全基因组测序方法可以在进行测序的同时，检测出5mC（5-甲基胞嘧啶）和5hmC（5-羟甲基胞嘧啶）。DNA样本只使用酶进行处理，避免了亚硫酸氢盐处理的DNA降解和基因组覆盖偏差。

- 论文链接：https://www.nature.com/articles/s41587-022-01652-0



3、[Genome Biol丨全面评估面向肿瘤研究的基于深度学习的多组学数据融合方法](https://mp.weixin.qq.com/s/xqR_oaeB57GnbHPRiTHLoQ)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303101713359.png)

> 该研究将16种具有代表性的深度学习方法在模拟多组学数据集、单细胞多组学数据集和癌症病人多组学数据集上进行了全面评估，为生物医学研究人员选择合适的基于深度学习的多组学数据融合方法提供了参考，也为未来开发更有效的多组学数据融合方法提出了指导性建议。

- 论文链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02739-2



4、[Cancer Cell | 基于949种细胞系的泛癌症蛋白质组图谱](https://mp.weixin.qq.com/s/s-pNissEtFAh7kS_gV9gXQ)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303101707555.png)

> 在Cancer Cell上发表了题为“Pan-cancer proteomic map of 949 human cell lines”的文章。作者团队使用质谱法分析了28种组织和40多种癌症类型的949个人类癌细胞系的蛋白质组，定量了8498种蛋白质，并将蛋白质组数据与多组学、药物反应和CRISPR-Cas9基因必需性数据集进行了整合。文章利用深度学习方法发现了与癌症易感性相关的蛋白质生物标志物，揭示了高度连接和共调控的蛋白质网络。这项研究为泛癌蛋白质组图谱（ProCan-DepMapSanger）提供了一个全面的资源，为精准医学和药物开发提供了新的线索和机会。

- 论文链接：https://pubmed.ncbi.nlm.nih.gov/35839778/
- Cell Model Passports：https://cellmodelpassports.sanger.ac.uk/
- 原始数据：http://proteomecentral.proteomexchange.org/cgi/GetDataset?ID=PXD030304
- 分析代码：https://zenodo.org/record/6563157#.ZAdtdvFByUk
- 药物反应数据：https://www.cancerrxgene.org/


## 博文资讯

5、[mission bio 的单细胞 DNA 测序技术](https://mp.weixin.qq.com/s/T9601QzbjUPAvR-p1BxmLQ)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303101714111.png)

> mission bio 公司开发的单细胞 DNA 测序技术，可以一次检测成千个单细胞的 DNA 和细胞表面蛋白。这项技术的工作原理是用微流控技术，将要检测的单细胞悬液转变成油包水的乳浊液。接着，将目标 DNA 片段加上特定的细胞 barcode 序列。最后，通过高通量测序，得到目标 DNA 片段的序列，对照片段上连的细胞 barcode 序列，来得知每一条 DNA 序列最初是归属于哪一个细胞。

- 可以用于直接检测单个细胞的基因水平的突变，对肿瘤基因突变的检测灵敏度很高，所以对肿瘤科研的意义很大。
- 用在对基因编辑后的细胞做基因检测，以确定基因编辑的效率。
- 还可以结合带标签链的抗体，以检测细胞表面蛋白的含量。



6、[常用 7 大类型图形可视化——组成成分图形](https://mp.weixin.qq.com/s/GeHYQp1rBJ-Gksel3GkIuw)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303112109123.png)

> 本文介绍了可视化中常用 7 大类型图形中的组成成分图形：华夫饼图、饼图和条形图。



7、[GP-GCN框架教程｜如何把DNA序列编码成深度学习的向量化输入](https://mp.weixin.qq.com/s/J7vsAs6R2e6aBMW7Uj1zRQ)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303101711460.png)

> 现在越来越多的工作利用深度学习来实现DNA序列的分类或者回归任务，但是如何把DNA序列编码成深度学习的向量化输入？换句话说，怎么把由A,C,G,T组成的DNA“字符串”转化成深度学习需要的向量（矩阵）格式？

- https://github.com/deepomicslab/GCNFrame





8、[ggraph | 优雅的绘制环状网络图](https://mp.weixin.qq.com/s/2PFko_kpmK9CfPxEn5IW8Q)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303101708598.png)



>　这篇推文是关于使用ggraph包在R语言中绘制环状网络图的教程，作者介绍了数据的导入、整合、可视化的步骤，并给出了代码和结果图。

- 示例代码：[ggraph示例代码 NiEntropy/Exampl_R#1](https://github.com/NiEntropy/Exampl_R/issues/1)
- github：https://github.com/thomasp85/ggraph
- 使用手册：
  https://cran.r-project.org/web/packages/ggraph/ggraph.pdf
  https://ggraph.data-imaginist.com/





## 工具

9、[rgg命令｜一个使搜索更加便捷的工具](https://github.com/lilydjwg/search-and-view)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303112110885.png)

> ag 是一个类似于grep的文本搜索工具，它命令短，默认忽略掉你通常不想看的文本，而且是C语言 编写的，比 ack 更快。而另一个工具 cgvg，包含两个命令：一个（cg）用来搜索，另一个（vg）用来在编辑器里打开。受此启发，作者做了三个工具rgg、rgv和vv，希望能够很便利地使用编辑器查看匹配的地方。

- 中文博客：https://blog.lilydjwg.me/2014/7/18/search-and-view-quickly.53141.html



10、[gghighlight | 突出gglot2中图形元素的R包](https://mp.weixin.qq.com/s/GeHYQp1rBJ-Gksel3GkIuw)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303112113874.png)

- 工具教程：https://yutannihilation.github.io/gghighlight/articles/gghighlight.html



11、[cransay | 抓取 CRAN 传入的 ftp 文件夹](https://github.com/r-hub/cransays) 

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303112127261.png)

> cransay 被设计用来抓取 CRAN 传入的 ftp 文件夹，以查找每个提交工作的位置，并生成dashboard。


12、[pdfimager包：提取PDF文件中的图像](https://github.com/sckott/pdfimager)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303101715459.png)

## 资源

13、[cbioportal | 可视化大规模癌症基因组数据](https://github.com/cBioPortal/cbioportal)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303101712997.png)

> 癌症基因组学的 cBioPortal 提供大规模癌症基因组学数据集的可视化、分析和下载。有关 cBioPortal 的简短介绍，请参阅这些介绍性幻灯片。

- 链接：https://docs.google.com/presentation/d/1hm0G77UklZnpQfFvywBfW2ZIsy8deKi5r1RfJarOPLg/edit#slide=id.p3





14、[【陈巍翻译】视频：了解免疫系统](https://mp.weixin.qq.com/s/QrTFZG1zCzsiov9ch5zyng)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303081633185.png)

> 这个视频概要地介绍了人的免疫系统，包括先天性免疫系统、和特异性免疫系统，和这两个系统的基本的工作原理。



15、[使用ClusterGVis包在热图中对指定 cluster 添加注释](https://mp.weixin.qq.com/s/sJlaUS9mPaYOPtbQrttfMA)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202303112138666.png)

- 工具教程：https://github.com/junjunlab/ClusterGVis/wiki/document




## 历史上的本周
- 第28期：[华大Stereo-seq系列成果揭秘超高分辨率生命全景时空图谱](https://mp.weixin.qq.com/s/0GxIPLXa7fh0ZiZxgrh8eg)

## 贡献者（GitHub ID）

「Openbiox 生信周刊」运维小队：

- `@ShixiangWang`（王诗翔）
- `@kkjtmac`（阚科佳）
- `@NiEntropy`（赵启祥）
- `@He-Kai-fly`（何凯）
- `@JnanZhang`（张佳楠）
- `@Tomcxf`（陈啸枫）
- `@wangdepin`（王德品）
- `@kongjianyang`（空间阳）

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）



