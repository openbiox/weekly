---
date: 2023-02-14
comments: true
---

# 生信爱好者周刊（第 6 期）：你会买“炸场”Macbook Pro搞生信吗？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/openbiox/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/openbiox/weekly/issues/140)

## 封面图


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1635001300654-1635001195320-image.png)



看上去是不同角度拍摄的同一条街道，但是实际上，它们是同一张图片并排放在一起。([via](https://mp.weixin.qq.com/s/jo_g-j1bjtNCZlneHig8HQ))

> 可视化是工具，不是结果。利用它，但别被它控制。

## 本周话题：你会买“炸场”Macbook Pro搞生信吗？

今后人们要吐槽的就是竟然连苹果电脑都要有刘海了。 新款MacBook Pro为了让屏幕面积更大，为电脑屏幕加上了一个刘海设计。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1634996645633-image.png)

你觉得它漂亮吗？个人觉得丑裂...


不过刘海是次要的，近期发布会的最大亮点，当属苹果新发布的两款芯片——M1 Pro和M1 Max。

M1 Pro 配备了多达 10 个 CPU 核心，其中包括 8 个高性能核心和两个节能核心，比M1提速70%。在图形方面，M1 Pro 拥有 16 核 GPU，其性能是M1 的两倍。新芯片还支持更多内存，配置选项最高可达 32GB，拥有高达200GB/s的内存带宽。M1 Pro使用了337亿个晶体管，大约是 M1 晶体管数量的两倍。支持外接两台显示器，可以同时播放多达20条4K ProRes视频。

M1 Max是是M1 Pro的进阶版，虽然跟Pro一样样拥有10个CPU，但M1 Max将统一内存进一步拓展到64GB，内存带宽至 400GB/s，比M1提速6倍。同时在GPU方面，Max在Pro的基础上再度翻了一倍，32核GPU让其速度达到M1 的四倍之多。（来源：公众号「[硅星人](https://mp.weixin.qq.com/s/aIcFMgfLa9V-_zURnDJHCw)」）

**So，你会买“炸场”Macbook Pro搞生信吗？**


## 生信科技动态

1、[新型AI系统可基于乳腺超声图像识别恶性病变，准确率与放射科医生相当](https://mp.weixin.qq.com/s/JiebXt9jFrsrhbDrDLwl_g)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1634997006898-image.png)


乳腺癌是女性癌症死亡的第二大原因，早期发现、治疗可以有效提高治愈率。X光检查是应用最广泛的乳腺癌筛查和早期发现的成像技术，但对于组织致密的乳腺，在X光检查中很难发现癌症。乳腺超声检查已被证实能够检测到X光检查中的隐匿性癌症，通常被作为乳房X光检查的补充手段，在乳腺癌筛查、检测和鉴定中发挥重要作用。但乳腺超声检查结果仍会获得较高的假阳性率，进而导致不必要的组织活检。

近日，美国纽约大学研究团队开发了一种新型人工智能（AI）系统，可以在超声图像中实现放射科医生级别的准确率来识别乳腺癌。结果显示，在该人工智能系统的帮助下，放射科医生诊断的假阳性率降低37.3%，在保持相同敏感性水平的前提下，组织活检率减少27.8%，突出了人工智能在提高乳腺超声诊断的准确性、一致性和效率方面具有很大的潜力。该研究成果已发表于*Nature Communications*期刊上，文章题为“*Artificial intelligence system reduces false-positive findings in the interpretation of breast ultrasound exams*”。

2、[DDInter：药物-药物相互作用数据库](https://mp.weixin.qq.com/s/Io8fdLZ65axSFn2E528FgQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1634997180715-image.png)

药物-药物相互作用 (DDI) 是临床合理用药和上市后药物警戒中最重要的问题之一。DDI是指同时或连续服用两种或两种以上药物时，一种药物的活性可能因其他药物的存在而发生改变。随着现代疾病谱的增加以及患者耐药性的升高，多药处方已成为常见的治疗选择，特别是对于伴有癌症、糖尿病、心血管疾病等多种慢性疾病的患者。这往往会增加临床相关 DDI 的风险，并对治疗管理提出了新的挑战。

来自中南大学曹东升教授课题组、浙江大学侯廷军教授课题组和湘雅医院刘韶教授课题组联合发表的一篇文章“*DDInter: an online drug–drug interaction database towards improving clinical decision-making and patient safety*”。本文介绍了一个全面且实用的数据库DDInter，包含约24万个经临床药师审阅和校正的相互作用药物对，覆盖了1833个FDA批准药物。DDInter 为每个DDI提供了丰富的信息，包括作用机制、严重程度、对于潜在风险的管理策略、药物替换方案、文献引用等。用户可以轻松浏览药物条目和相互作用，检索基本信息和药物相互作用网络，并借助相互作用检查器组件进行处方检查。为了帮助用户更好地理解和探索搜索结果，嵌入了多个数据可视化工具来动态显示复杂的关系。医生和药剂师通过使用DDInter可以获得剂量调整、药物更换以及风险判断和管理的实用指导；数据科学家可以将其用于潜在DDI的推导和其他预测工具的评估。

3、[为什么不吸烟也会得肺癌？NIH团队揭示不吸烟肺癌患者基因突变演化史](https://mp.weixin.qq.com/s/_lAOJGlQoZ4-f_nK3b5c1w)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1634997373907-image.png)

近期，来自美国国立卫生研究院（NIH）下属国家癌症研究所（NCI）癌症流行病学和遗传学部门的流行病学家Maria Teresa Landi博士领导的研究团队在*Nature Genetics*期刊上发表题为“*Genomic and evolutionary classification of lung cancer in never smokers*”的研究文章。研究团队对无吸烟史肺癌患者进行全基因组测序，绘制了不吸烟肺癌患者基因突变演化史。分析结果发现，大部分肿瘤都是由机体自然过程所引起的突变而引发。同时，该研究还关注了不吸烟群体与肺癌之间的健康问题，为肺癌早期诊疗提供了科学依据。

基因组突变图谱结果显示，EGFR是最常见的突变（28.4%），其次是KRAS（7.3%）、ALK （6.0%）、MET（4.3%）、ERBB2（3.9%）、ROS1（2.6%）和RET（1.3%），这7个基因突变互相呈现强烈的互斥分布。


4、[机器学习揭示基因组在单个细胞中的表达差异](https://mp.weixin.qq.com/s/kWNAHXusQAv6u_5X-0ykbQ)

在单个人类细胞的微观视界内，蛋白质和 DNA 的复杂折叠和排列决定了每个细胞的命运：哪些基因被表达，哪些基因被抑制，这决定了细胞是保持健康还是发生病变；宏观角度则反映了一个人的健康状况。单细胞 Hi-C （scHi-C） 技术可以识别三维 （3D） 染色质组织的细胞间差异性，但测量相互作用的稀疏性会带来分析挑战。

卡内基梅隆大学的研究人员提出了一种基于超图表示学习框架的算法——**Higashi**，可以合并单个细胞之间的潜在相关性，以增强接触图的整体插补。Higashi 优于现有的 scHi-C 数据嵌入和插补方法，并且能够识别单个细胞中的多尺度 3D 基因组特征，例如区室化和 TAD 样域边界，从而可以精确描绘其细胞间差异性。该研究以*Multiscale and integrative single-cell Hi-C analysis with Higashi*为题，于2021年10月11日发布在杂志*Nature Biotechnology*。

5、[3 个问题：MIT专家论述关于阻碍AutoML发展的障碍](https://mp.weixin.qq.com/s/ihpMMGaaiVme-LvNptuIbg)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1634997694441-image.png)

研究人员希望更多用户友好的机器学习系统将使非专家能够分析大数据——但这样的系统能完全自主吗？本文介绍麻省理工学院计算机科学家 Kalyan Veeramachaneni分享了他对自动化机器学习 （AutoML）现状、创建全自动机器学习系统的挑战以及未来道路的看法。Kalyan Veeramachaneni 是麻省理工学院信息与决策系统实验室的首席研究科学家，自 2010 年以来一直在研究 AutoML，他在 ACM Computing Surveys 杂志上合著了一篇论文，详细介绍了一个七层示意图，用于根据 AutoML 工具的自主级别来评估它们。

3个问题：

- 自动机器学习在过去十年中是如何发展的，AutoML系统的现状如何？
- 机器学习流程的哪些步骤最难自动化，为什么自动化它们如此具有挑战性？
- 您希望通过您在论文中概述的用于评估 AutoML 系统的七层框架实现什么目标？


## 文章

1、[可别再说base plot不能图形语法！](https://mp.weixin.qq.com/s/rfVLZEbLmSCSxkF8jioLzQ)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1634997938326-image.png)

R自带绘图包采用画家模式，难以实现灵活有序的图形生成。本文中Y叔介绍了基于图像语法的base plot生成以及相应的R包实现plotbb。对可视化感兴趣的读者非常推荐阅读！

2、[GATK 的Somatic Mutation流程--肿瘤基因组测序数据分析专栏](https://mp.weixin.qq.com/s/-sTXZT4FznMPIQTaOeXsDg)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1634998157969-image.png)

本文介绍了GATK 的Somatic Mutation检测流程。

3、[R包earth的多元自适应样条回归（MARS）以及对变量重要性的评估](https://mp.weixin.qq.com/s/ilCHW7YSKZeyuHAKYfM2Bw)

多元自适应样条回归（Multivariate Adaptive Regression Splines，MARS）是一种非参数回归方法，它通过对数据进行分区，并在每个区间的预测变量值范围内分别构建线性模型或广义线性模型来实现，即一种分段回归形式。本文介绍了该方法的基本原理和通过实例评估变量重要性。

4、[R语言快速制作学术论文三线表](https://zhuanlan.zhihu.com/p/417254582)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1634998313831-image.png)


三线表以其形式简洁、功能分明、阅读方便而在科技论文中被推荐使用。

本文主要使用table1包制作三线表，生成的三线表为html格式，可以直接复制到word中。


5、[一个人能领导多少人？](https://www.patkua.com/blog/how-many-people-can-someone-lead/)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1634998378492-image.png)

这个问题没有简单的答案。虽然本文作者通常使用5-7个人的经验法则，但你可以看到这完全取决于情况。


## 工具

1、[survminer：生存分析和可视化](https://github.com/kassambara/survminer)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1635000058759-image.png)

2、[rstatix：基础统计检验的管道友好框架](https://github.com/kassambara/rstatix)

提供简单直观的管道友好框架，与“tidyverse”设计哲学相一致，用于执行基本统计检验，包括t检验、Wilcoxon检验、方差分析、Kruskal-Wallis和相关分析。

3、[lexer：一个支持多语言扩展的JS版开源词法分析器](https://github.com/WGrape/lexer)

一个基于DFA法的支持多语言扩展的JS版开源词法分析器，代码精简，易于学习和使用。（[@WGrape](https://github.com/WGrape)投稿）


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1635000276388-image.png)


4、[annotables：用于注释/转换基因id的R数据包](https://github.com/stephenturner/annotables)

```R
grch38 %>% 
    dplyr::filter(biotype == "protein_coding" & chr == "1") %>% 
    dplyr::select(ensgene, symbol, chr, start, end, description) %>% 
    head %>% 
    knitr::kable(.)
```

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1635000417324-image.png)

5、[styler：R代码格式化](https://github.com/r-lib/styler)

R代码丑？就用它。我常用的一个R包，可以从文件、目录和包三个不同的水平格式化R代码。

6、[docker与podman：容器与管理工具](https://podman.io/getting-started/)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-23/1635000612460-image.png)

容器化技术已经变革了云服务与软件应用开发和部署方式，也为可重复的数据分析提供强大的底层支撑。对技术感兴趣的读者一定不要错过容器技术。（知乎用户 @幻舞花火 的投稿）

7、[rsthemes：完整的RStudio IDE和语法主题](https://github.com/gadenbuie/rsthemes)

```R
# 安装包
devtools::install_github("gadenbuie/rsthemes")

# 安装主题
rsthemes::install_rsthemes()

# 尝试主题
rsthemes::try_rsthemes()
```


## 资源

1、[《生物信息就该这么学》专栏合集](https://mp.weixin.qq.com/s/gkFZd5RMX6YmsklWTKmy8w)

2、[李沐：深度学习论文精读](https://github.com/mli/paper-reading)

推荐学习深度学习的读者关注。

3、[免疫学拾遗](https://mp.weixin.qq.com/mp/appmsgalbum?action=getalbum&__biz=MzAwMDUzNTIxNA==&scene=1&album_id=1647467076418060289&count=3#wechat_redirect)

## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

感谢以下读者往期的赞赏：

- 张林
- 曾健明

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）
