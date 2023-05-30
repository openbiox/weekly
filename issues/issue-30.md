---
date: 2023-03-08
comments: true
---

# 生信爱好者周刊（第 30 期）：生信的核心修炼道路在哪里？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo) | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community)

## 封面图


![](https://files.mdnice.com/user/4331/01d68a29-07d0-42be-ac5b-a1cf8ad9bf54.png)

[via](https://www.healthecareers.com/articles/recruiting/career-pathway-programs)

## 本周话题：生信的核心修炼道路在哪里？

生信是多学科：统计、计算机、生物学。。。

生信是多领域：基因组、转录组、蛋白组、表冠遗传、宏基因组。。。

生信是多技能：Linux、R/Python、JS/HTML/CSS。。。

生信是多应用：动物、植物学、医学。。。

生信是多背景：有的搞生物的、有的搞计算机的、有的搞数据库的、有的搞算法。。。。

有人说它是科学，有人说它是应用，还有人说它只是服务。

值得思考的是，如果你作为一名纯小白，你认为能够为你提供系统学习的生信核心修炼体系是怎么样的？


## 生信科技动态

1、[Cell | 映射单细胞的转录组向量场](https://mp.weixin.qq.com/s/c8lz3SlnZFpdW6hp_k_iog)


![](https://files.mdnice.com/user/4331/3a6464ce-2c8b-48c5-ab92-a49fe1b92a54.png)


本文介绍由美国马萨诸塞州怀特黑德生物医学研究所的Xiaojie Xu和Jonathan S. Weissman以及匹兹堡大学计算与系统生物学系的Jianhua Xing共同发表在Cell的研究成果：基于单细胞测序(scRNA-seq)RNA速度和代谢标记预测细胞状态。作者提出了一个分析框架dynamo (https://github.com/aristoteleo/dynamo-release)，推断绝对RNA速度，重建预测细胞命运的连续向量场，利用微分几何提取潜在的规则，最终预测出最佳的重编程路径和扰动结果。进一步分析了dynamo在克服传统基于剪接的RNA速度分析的基本限制方面的能力，表明其能在代谢标记的人类造血scRNA-seq数据集上精确估计速度。此外，微分几何分析揭示了驱动早期巨核细胞出现的机制，并阐明了PU.1-GATA1电路中的不对称调节。利用最小作用路径方法，dynamo可以准确预测驱动无数造血系统的转变，并最终由计算机干扰预测基因微扰引起细胞命运的转变。综上，Dynamo有助于开展细胞状态转变的定量分析和预测。


2、[Nature Communication ｜肿瘤基因组数据报告解读平台，可满足商业报告解决方案](https://mp.weixin.qq.com/s/FI4tA7DZEIJQLGe380dsEA)


![](https://files.mdnice.com/user/4331/d886da22-ade0-4c5e-b997-7b62b95f1669.png)


随着精准医疗的不断发展，科学研究和临床应用中对癌症基因组数据的解读需求也在增加。虽然目前癌症测序数据分析流程的自动化提高了报告的速度和结果的可重复性，通过使用交互而非静态报告，临床对复杂基因组数据的理解有所改善。但仍然有部分结果的解释难以实现自动化。因此，基因组数据解读仍然是推广精准医学最大的瓶颈之一。

加拿大Michael Smith基因组科学中心等单位的联合研究团队在Nature Communications发表了题为“A platform for oncogenomic reporting and interpretation”的文章，报道了一个自主开发的完全开源的研究平台——Platform for Oncogenomic Reporting and Interpretation （PORI）。该平台可以通过知识库匹配将不同的注释集成到精确的肿瘤基因测序工作流程中，并为用户提供一个报告界面，以管理、编辑和与结果数据交互。研究团队表示，PORI可以替代商业报告解决方案，适用于精准肿瘤学的全面基因组数据解读，有效促进精准医学的普及和发展。

GitHub地址：<https://github.com/bcgsc/pori/>

3、[iMeta期刊青年编委招募](https://mp.weixin.qq.com/s/h90iQ6Z_dmSttlrFfRQ5FA)


![](https://files.mdnice.com/user/4331/0232bd0b-476d-4bb0-a265-a48535c14b17.png)


“iMeta” 是由威立、肠菌分会和本领域数百位华人科学家合作出版的开放获取期刊，主编由中科院微生物所刘双江研究员和荷兰格罗宁根大学傅静远教授担任。目的是发表原创研究、方法和综述以促进宏基因组学、微生物组和生物信息学发展。目标是发表前10%(IF > 15)的高影响力论文。期刊特色包括视频投稿、可重复分析、图片打磨、青年编委、前3年免出版费、50万用户的社交媒体宣传等。2022年2月正式创刊发行！

认同办刊理念，一起打造国际顶刊，解决我国本领域期刊出版卡脖子问题，愿意为期刊发展作贡献的优秀青年科学家。

破五唯，满足以下条件中的任意一项即可。其他任何有助期刊发展有利的个人能力请在申请表格中个人简介部分说明即可。

▸ 具有副高级以上职称
e
▸ 第一作者或通讯作者(含共同)论文IF > 10

▸ 引用 > 1000

▸ H指数 > 12

▸ 编辑能力，如文字校对、润色，图片绘制、美化等

▸ 个人影响力，如组织会议、公众号主、专业交流群主等

4、[Nature Genetics | 癌症基因组中的双等位突变揭示关键驱动突变机制](https://mp.weixin.qq.com/s/FYnvPfN4axThyFNej2kgjg)

e
![](https://files.mdnice.com/user/4331/00d058e3-0edd-4491-9549-3c1ed481cf0a.png)


在单个二倍体谱系中，由于双等位基因突变（即同一碱基在两个亲本上独立突变）发生概率较小，一直都被忽视或被认为是“技术错误”，但其确实发生在超五分之一的癌症病例中，需要在分析癌症基因组时加以考虑。 

英国弗朗西斯·克里克研究所的研究团队及其合作者在Nature Genetics上发表了最新的研究成果，文章题目为“Biallelic mutations in cancer genomes reveal local mutational determinants”。研究团队从全基因组泛癌症分析研究（PCAWG）的559份（21%）批量测序样本中鉴定出了18,295个双等位基因突变，并对其进行了研究。研究结果显示，双等位突变揭示了E26转化特异性（ETS）和活化T细胞核因子（NFAT）结合位点的紫外线损伤热点，以及POLE突变体和其他癌症中的超可变基序。此外，研究团队还提供了建模和检测双等位基因突变的框架，以便变体的识别。 

## 文章

1、[WGCNA分析，简单全面的最新教程](https://mp.weixin.qq.com/s/3Z7RNq8gOzmPie1HX6vpyg)


![](https://files.mdnice.com/user/4331/83a13837-fbc7-46ff-8746-756afa8d9364.png)


2、[使用ggtree包绘制带聚类树的物种丰度堆叠柱形图](https://mp.weixin.qq.com/s/dVXzlTROzAMeYhzavjW7nw)


![](https://files.mdnice.com/user/4331/29c04bbe-5032-4d72-ac77-8a24fd46191b.png)


3、[代谢组学数据通常是OPLS-DA或者PLS-DA来代替PCA](https://mp.weixin.qq.com/s/-R50aZ-q0PsEja4JkknWeg)


![](https://files.mdnice.com/user/4331/7f43b0f1-df79-4202-80e9-b7ccd326bc4f.png)


## 工具

1、[AnnoProbe - GEO数据下载与处理](https://github.com/jmzeng1314/AnnoProbe)

生信技能树创始人Jimmy为方便大家下载GEO数据提供的镜像、ID转换等工具包。通过以下方式安装：

```r
library(devtools)
install_github("jmzeng1314/AnnoProbe")
library(AnnoProbe)
```

大家觉得有用记得去GitHub给它点个Star，目前用的人应该比点赞的多很多。

2、[Cepo](https://github.com/PYangLab/Cepo)


![](https://files.mdnice.com/user/4331/4370d92f-2f85-42ce-8b73-cd321d9e5ed0.png)

定义细胞的身份是理解细胞对各种环境信号和扰动的异质性的基础。该工具提出了一种从单细胞rna测序数据中探索细胞特性的新方法——Cepo，该方法使用差异稳定性作为定义细胞特性基因的新指标。Cepo计算与差异稳定基因表达相关的细胞类型特异性基因统计。

[发表文献](https://www.nature.com/articles/s43588-021-00172-2.epdf)


3、[ClearML - Auto-Magical Suite of tools to streamline your ML workflow
Experiment Manager, MLOps and Data-Management](https://github.com/allegroai/clearml)


![](https://files.mdnice.com/user/4331/1d9d13d1-ec0a-4cad-be14-4d3501d5ccf9.png)


![](https://files.mdnice.com/user/4331/2f765252-f776-4dfc-a61d-56098fb5a7d9.png)



4、[emmeans - Estimated marginal means](https://github.com/rvlenth/emmeans)

估计边际平均值（以前在传统回归模型中称为最小二乘平均值)是通过使用一个模型在预测器组合的规则网格(称为参考网格)上进行预测而得到的。这些预测可能被一个或多个预测因子平均(通常具有相同的权重）。这种边缘平均预测对于描述拟合模型的结果是有用的，特别是在提出因素的影响方面。emmeans包可以很容易地生成这些结果，以及它们的各种图形(交互风格的图形和并排的间隔)。


## 资源

1、[2021 年最佳开源软件榜单](https://mp.weixin.qq.com/s/DqjMS4GihpZ3auiGmrw8Ew)


![](https://files.mdnice.com/user/4331/27eb002f-ec2c-47cd-8329-6751b38d37f4.png)


InfoWorld 是一家信息技术媒体公司，成立于 1978 年目前隶属于 IDG。每年 InfoWorld 都会根据软件对开源界的贡献，以及在业界的影响力评选出当年的“最佳开源软件” (BOSSIE)，该奖项评选已经延续了十多年。本次获奖的 29 个开源项目包括：软件开发、开发、云原生计算、机器学习等类型。

2、[统计学回顾（精华目录收藏）（statquest+协和八+ NGSHotpot）](https://mp.weixin.qq.com/s/O915_Tcm-lNjFvR0OFP1Sg)


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648291334186-bd3390be-c83c-4396-aabd-ca39f588c15d.png)

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

