---
date: 2023-02-11
comments: true
---

# 生信爱好者周刊（第 3 期）：百年杨振宁

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/ShixiangWang/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/ShixiangWang/weekly/issues/32)

## 封面图

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109242307803.png)

对抗与对流。（[via](https://twitter.com/thomasp85/status/1437678096220659713/photo/1)）


## 本周话题：[百年杨振宁](https://mp.weixin.qq.com/s/CsSWfjUXFTkA9WeH2klDlw)

> 2021年10月1日，杨振宁先生将迎来农历100周岁生日，学术界纷纷推出活动或文集祝贺杨先生百岁诞辰。《赛先生》自8月起陆续刊发系列重温杨振宁先生重要贡献的经典文章。9月22日起与《知识分子》联合推出 “百年风华杨振宁” 系列文章。邀请朱邦芬、潘建伟、施一公、饶毅等科学家及杨振宁先生学生为杨先生百岁诞辰送上祝福。

你认识杨振宁吗？知道他有哪些成果？哪些成果和品德让你钦佩？他的经历是否促进你对科学和生信科研的思考？🤔

欢迎读者在留言讨论区进行评论交流。

愿我们都能为国家、为生信、为自己奋斗百年！

## 生信科技动态

1、[Science再次发布“全世界最前沿的125个科学问题”](https://mp.weixin.qq.com/s/Vy7k1TDBZGHZNK3f810aGg)

其中生命科学领域的问题可以作为各位读者思考和以后攻克的方向。

1. What could help conservation of the oceans?
什么可以帮助保护海洋？
2. Can we stop ourselves from aging?
我们可以阻止自己衰老吗？
3. Why can only some cells become other cells?
为什么只有一些细胞会变成其他细胞？
4. Why are some genomes so big and others very small?
为什么有些基因组非常大而另一些却很小？
5. Will it be possible to cure all cancers?
有可能治愈所有癌症吗？
6. What genes make us uniquely human?
哪些基因使我们人类与众不同？
7. How do migratory animals know where they're going?
迁徙动物如何知道它们要去哪里？
8. How many species are there on Earth?
地球上有多少物种？
9. How do organisms evolve?
有机体是如何进化的？
10. Why did dinosaurs grow to be so big?
为什么恐龙长得如此之大？
11. Did ancient humans interbreed with other human-like ancestors?
远古人类是否曾与其他类人祖先杂交？
12. Why do humans get so attached to dogs and cats?
人类为什么会对猫狗如此着迷？
13. Will the world's population keep growing indefinitely?
世界人口会无限增长吗？
14. Why do we stop growing?
我们为什么会停止生长？
15. Is de-extinction possible?
能否复活灭绝生物？
16. Can humans hibernate?
人类可以冬眠吗？
17. Where do human emotions originate?
人类的情感源于何处？
18. Will humans look physically different in the future?
未来人类的外貌会有所不同吗？
19. Why were there species explosions and mass extinction?
为什么会发生物种大爆发和大灭绝？
20. How might genome editing be used to cure disease?
基因组编辑将如何用于治疗疾病？
21. Can a cell be artificially synthesized?
可以人工合成细胞吗？
22. How are biomolecules organized in cells to function orderly and effectively?
细胞内的生物分子是如何组织从而有序有效发挥作用的？


2、[单细胞分析迈入多组学时代](https://mp.weixin.qq.com/s/LPXNXERF53mxr7GqS3-h-w)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632538328451-image.png)

一系列迅速发展的软件工具正在帮助研究人员分析多个庞大的组学数据集。过去十年见证了单细胞基因组学的爆炸式增长。描述基因表达的单细胞RNA测序 (RNA-seq)是最常用的技术。其他方法则详细描述了甲基化、遗传变异、蛋白质丰度和染色质可及性等过程。


3、[Robust haplotype-resolved assembly of diploid individuals without parental data](https://arxiv.org/abs/2109.04785)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632538197133-image.png)


常规单样本单倍型解析组装仍然是一个未解决的问题。在这里，我们描述了一种新算法，该算法结合了 PacBio HiFi 读数和 Hi-C 染色质相互作用数据，以生成单倍型解析的组装，而无需对亲本进行测序。应用于人类和其他脊椎动物样本，我们的算法始终优于现有的单样本组装管道，并生成与最佳基于谱系的组装质量相当的组装。


4、[利用长读长测序数据解析遗传变异的深度学习算法NanoCaller](https://mp.weixin.qq.com/s/aKR-ozvj1dbOLSEzX2I7SA)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632538454223-image.png)

与短读长测序技术相比，长读长测序技术成本更低，reads长度更长，可以克服短读长测序无法解决的多个挑战性问题，已成功用于对不同物种的基因组进行测序。但与短读长测序数据相比，长读长测序的精准度较低，检测错误率也更高。有研究表明，利用基于深度学习的算法，在长读长测序数据上可以精确检测变异。根据单倍型数据的分阶段比对可提高变异识别的准确性，现有的三种算法（DeepVariant、Clairvoyante和Clair）在短读长和长读长数据上都能很好地运行单倍型数据比对，但这些算法在SNP检测中都忽略了来自远端单倍型SNP的重要信息。

近日，费城儿童医院王凯教授团队开发了一种新的深度学习算法--NanoCaller，可充分利用长读长测序在基因组区域中检测变异，并在Genome Biology上发表了题为*NanoCaller for accurate detection of SNPs and indels in difficult-to-map regions from long-read sequencing by haplotype-aware deep neural networks*的研究文章。NanoCaller可利用单倍型信息检测SNP，使用称为SNP的长reads进行定相，并通过局部重新排列检测InDel。研究团队利用NanoCaller检测了一个被广泛使用的基准基因组中的41个全新变体，这是此前其他方法无法实现可靠检测，有助于从长读长测序中发现复杂基因组区域的新变体。

5、[Subtype-GAN: a deep learning approach for integrative cancer subtyping of multi-omics data](https://mp.weixin.qq.com/s/BXnJIAbCzZVcWTx67y8QiA)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632539328951-image.png)

癌症亚型的发现有助于探索癌症发病机制，确定治疗中的临床可操作性，并提高患者的生存率。然而，由于多组学数据的多样性和复杂性，开发用于肿瘤分子亚型的集成聚类算法仍然具有挑战性。本文提出了 Subtype-GAN，这是一种基于多输入多输出神经网络的深度对抗学习方法，可以准确地对复杂的组学数据进行建模。通过从神经网络中提取潜在变量，Subtype-GAN 使用共识聚类和高斯混合模型来识别肿瘤样本的分子亚型。与其他最先进的子分型方法相比，Subtype-GAN 在由来自 10 种癌症类型的 4000 个 TCGA 肿瘤组成的基准数据集上取得了出色的表现。作者将 Subtype-GAN 应用于 BRCA 数据集，并自动获得了 1031 个 BRCA 肿瘤的亚型数量和亚型标签。通过详细分析，作者发现识别出的亚型具有临床意义，并且在特征空间中显示出不同的模式，证明了 Subtype-GAN 的实用性。


- 论文链接：https://doi.org/10.1093/bioinformatics/btab109
- Github链接：https://github.com/haiyang1986/Subtype-GAN


6、[DTI-Voodoo: machine learning over interaction networks and ontology-based background knowledge predicts drug–target interactions](https://mp.weixin.qq.com/s/BXnJIAbCzZVcWTx67y8QiA)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632539444980-image.png)

预测DTI的方法可以利用药物的表型效应来识别潜在的药物靶点而间接进行，也可以是直接的利用分子信息直接预测结合亲和力。这两种方法都可以与有关交互网络的信息相结合。作者开发了DTI-Voodoo，将药物的分子特征和本体编码的表型效应与蛋白质-蛋白质相互作用网络相结合，并使用GCN来预测DTI。作者证明了药物效应特征可以利用相互作用网络中的信息，而分子特征则不能。DTI-Voodoo旨在预测给定蛋白质的候选药物；实验证明了DTI-Voodoo比最先进的DTI预测方法有显著的改进。

- 论文链接：https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btab548/6329632
- 代码链接：https://github.com/THinnerichs/DTI-VOODOO 


7、[Cathy Wu/Shirley Liu 团队建立多中心免疫肿瘤生物标志物开发平台](https://mp.weixin.qq.com/s/4GvrHdx565DbN4FBWR2Xig)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632539695089-image.png)


哈佛大学/丹特-法博癌症研究所Cathy Wu及X.Shirley Liu 团队在Clinical Cancer Research 期刊上发表了题为*Cross-Site Concordance Evaluation of Tumor DNA and RNA Sequencing Platforms for the CIMAC-CIDC Network*的文章。该研究建立并描述了免疫治疗临床试验中产生的跨中心多组学数据的整合分析平台及策略，并描述了建立多中心网络免疫肿瘤生物标志物开发的关键要素。其中包括平台建设、免疫分析检测的验证和协调、数据读取和集成平台以及多组学数据分析的策略。该研究也指出，DNA 和 RNA 平行测序能够显著提高肿瘤免疫治疗标志物筛选结果，可为精准诊断、精准治疗提供重要的参考信息。


https://github.com/ShixiangWang/weekly/issues/40


## 文章

1、[绘制GC含量和测序深度（GC-Depth）分布图评估基因组质量](https://mp.weixin.qq.com/s/xeF6_TZd54WaTwTp0xVrTQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632540139682-image.png)

对于组装后的基因组序列，将组装基因组结果中的contigs/scaffolds序列分隔为一定长度的滑窗，统计每段滑窗内的各碱基占比，或者GC含量等，以查看组装结果中碱基分布是否均匀，基因组中存在多少比例的高GC区域等。据此，可在一定程度上推测物种基因组结构特征，组装中是否存在明显的错配，或判断测序数据中是否存在其他物种污染等。


2、[Lessons learned in writing my first book](https://shinglyu.com/web/2020/04/05/lessons-learned-in-writing-my-first-book.html)

作者介绍了自己写第一本书的的经历感悟以及一些技巧分享。

3、[Visualize the 'real' circular genome](https://jokergoo.github.io/2021/09/18/visualize-the-real-circular-genome/)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632540271666-image.png)


circlize包提供了基因组的环形可视化方法。现在的问题是如何可视化一个“真正的”环形基因组，其中完整的圆圈对应于基因组，并且基因组的“末端”平滑地越过基因组的“起点”。

4、[R tips: rlang中的expression操作符](https://mp.weixin.qq.com/s/MOBQrbO4LzV5RqzK1ge6Xg)

生信菜鸟团的这篇推文简要介绍了rlang操作非标准计算的方式。

5、[ggplot2的热图玩法](https://mp.weixin.qq.com/s/ihdDP689Y1_5FeT5-Buxpw)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632540902957-image.png)


画热图的体系用的比较多的是pheatmap和ComplexHeatmap这两个包，前者胜在代码简单，功能强大，而后者胜在细节无穷无尽，只有你想不到，没有它做不到。ggplot2在画热图这件事上，是存在感不太强的。但有时候还必须得用它来画，以期和其他ggplot2的图严丝合缝的拼在一起。

因此我收集了一下ggplot2的成果，发现又解锁了y叔的一个新包aplot，以及前段时间刚出的ggheatmap（居然是大三的学生写的，后生可畏）。我写了三种方法，ggheatmap最为简单，可以直接去看方法3。


## 工具

1、[typora](https://typora.io/) - 最好用的Markdown编辑器

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632540565298-image.png)

除了默认内置的几种主题，读者还可以通过<https://theme.typora.io/>从主题库中筛选自己喜欢的。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632540675233-image.png)

2、[spiralize](https://github.com/jokergoo/spiralize) - 可视化螺旋数据


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632541154187-1632541088194-image.png)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632541327348-image.png)


顾神新出品的精品R包。可以螺旋化沿阿基米德螺线可视化数据。它在可视化方面有两大优势：

- 它能够以高分辨率可视化具有很长轴的数据。
- 时间序列数据可以有效地揭示周期性模式。

作者在<https://jokergoo.github.io/spiralize_vignettes/examples.html>提供了非常多的实例，感兴趣的一定要看看！


3、[jupyverse](https://github.com/jupyter-server/jupyverse) - 一组实现一个Jupyter服务器的FPS插件

4、[ggheatmap](https://github.com/XiaoLuo-boy/ggheatmap) - ggplot2的热图实现


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632540943869-image.png)


本期文章有一篇相关推文。

5、[可视化代码执行](https://pythontutor.com/)

【原载于[《科技爱好者周刊（第 177 期）》](https://mp.weixin.qq.com/s/F9zXp02T8n15QCS22JYYkg)】。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632541890948-image.png)


这个网站会将代码的执行流程，转成可视化图形，展示代码一步步是怎么执行的。目前支持 Python、Java、C、C++、JavaScript 和 Ruby 代码。


## 资源

1、[数据科学小抄](https://www.aliyundrive.com/s/688q5eGAKdE)

我之前收集各类数据科学小抄，感兴趣的读者可以通过阿里云盘<https://www.aliyundrive.com/s/688q5eGAKdE>下载。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632541437396-image.png)

2、[R中处理因果推断](https://github.com/malcolmbarrett/causal_inference_r_workshop)

包含如下内容：

- 00 Intro
- 01 Whole Game
- 02 Causal Diagrams
- 03 Introduction to Propensity Scores
- 04 Using Propensity Scores
- 05 Checking Propensity Scores
- 06 Fitting the outcome model
- 07 G-Computation
- 08 Tipping Point Sensitivity Analyses

3、[Information is beautiful网站](https://informationisbeautiful.net/visualizations/) - 一个非常多可视化案例的网站

该网站里面包含了各种各样好看的可视化图表，以及相关的介绍。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-9-25/1632541659841-1632541605142-image.png)


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

感谢以下读者往期赞赏：

- 拼命做实验的昌浩
- Robin
- 爪爪
- Oligomath
- 李浩

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）
