# 生信爱好者周刊（第 43 期）：RNA-seq差异分析究竟应该用什么？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo) | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community)

## 封面图


![](https://files.mdnice.com/user/4331/c1f740f2-3bf3-4847-ba4f-f6bb32fb6a2b.png)

第一张免疫系统连接图谱：人体免疫系统由在全身循环的细胞分布网络组成，这些细胞必须动态地形成物理关联，并利用其细胞表面蛋白质组之间的相互作用进行通信。[via](https://mp.weixin.qq.com/s/VCCqSjrc1qgBK1wCVNlEAg)

## 本周话题：[RNA-seq差异分析究竟应该用什么？](https://mp.weixin.qq.com/s/DSgGMI_QUV0wquw9gAkTwA)

> RNA-seq是目前生信一个重要的技术组成和科研内容。一般来说，我们在RNA-seq进行差异分析时最好使用Count值，因为limma-voom、edgeR和DESeq2都是针对RNA-seq的Count值分布进行假设，从而设计的软件。但是，在实际过程中，我们并不是总能获得其Count值，而经常得到的是FPKM或者TPM值，那对于这种情况，我们能不能使用类似于分析芯片的方法进行差异分析呢？
>
> 文章利用数据集 GSE145894 对比了count数据和几种不同的FPKM形式得到的差异基因列表，发现不同结果存在较大的差异（具体见下图）。


![](https://files.mdnice.com/user/4331/039646a1-13c8-4227-a83d-096221ea8bf9.png)

`@ShixiangWang` - 不难发现两两交集的比各自独立的少很多，也就是不同的表达矩阵形式会很大影响结果。如果对该数据集下count数据的不同差异分析方法再做个对比和这个图结合起来看，可能会有一个更为全面的认识。比如，有兴趣的读者可以看看[*TPM, FPKM, or Normalized Counts? A Comparative Study of Quantification Measures for the Analysis of RNA-seq Data from the NCI Patient-Derived Models Repository*](https://translational-medicine.biomedcentral.com/articles/10.1186/s12967-021-02936-w)这篇文章。


## 生信研究

1、[Science Advances | 单分子突变测序SMM-seq，可检测低丰度体细胞突变](https://mp.weixin.qq.com/s/Aq6dJ40I-QnN6eXZ8MXOig)


![](https://files.mdnice.com/user/4331/35fb181f-5707-4cf0-bcd9-7d396862e84f.png)

本文介绍一种新型双重测序技术-单分子突变测序（SMM-seq），它可以用于检测细胞和组织中的超罕见突变，目前研究团队正在向商业化中，从而更大范围的探索各种疾病的诱变因素。

- 论文链接：https://www.science.org/doi/10.1126/sciadv.abm3259


2、[bioRxiv | 单细胞多组学整合分析解析人类肿瘤浸润T淋巴细胞的细胞状态特异性增强子图谱](https://mp.weixin.qq.com/s/L3mMZ54YspJHqWFvb2zzKA)


![](https://files.mdnice.com/user/4331/eb72c05c-5471-46f8-9f09-258b0862443e.png)

该研究利用改进优化后单细胞ATAC-seq测序技术构建了不同肿瘤TILs中T细胞的染色质可及性图谱，并解析了不同功能状态T细胞亚群染色质可及性的异质性特征和耗竭性T细胞的组织特异性调控元件及其核心拟时序分化发育轨迹。通过单细胞多组学数据的整合分析，鉴定了不同细胞亚群特异的增强子-启动子互作关系和关键调控靶基因，并利用CRISPRi/a基因编辑技术验证了这些远程调控增强子元件对相应靶基因的互作调控关系。总之，结果为深入研究T细胞耗竭关键基因的非编码调控元件开辟了新的途径，并为基于CRISPR i/a介导的增强子编辑技术干预T细胞功能和免疫治疗提供了潜力。

- 论文链接：https://doi.org/10.1101/2022.03.16.484513


3、[European Heart Journal | 中国首个冠心病多基因风险评分（PRS）模型建立](https://mp.weixin.qq.com/s/dC_RD5UaSADHkAfPW4uACA)


![](https://files.mdnice.com/user/4331/991c1558-0654-4278-b2d2-f34b21949ce0.png)

国家心血管病中心/中国医学科学院阜外医院顾东风院士与鲁向锋教授团队成功建立我国首个冠心病多基因风险评分（PRS）模型，为冠心病风险评估和干预措施选择提供了解决方案。该研究建立了我国居民冠心病高危人群早期筛查的实用性评估模型，并提出不同遗传和临床风险人群的心血管健康管理路径和方案。

- 论文链接：https://doi.org/10.1093/eurheartj/ehab923


4、[HiFi 5mC 直接测序，探索基因组新维度](https://mp.weixin.qq.com/s/k_yqzgeVS-0RVv-OJ-ry6A)


![](https://files.mdnice.com/user/4331/a0f3f79e-3c72-4428-a444-6d93fcbc74a6.png)

在哺乳动物基因组中，DNA 甲基化是一种常见的表观遗传修饰，其中最常见的一种甲基化方式是通过 DNA 甲基化转移酶将甲基转移到胞嘧啶的 C5 位置以形成 5-甲基胞嘧啶（5mC）。

随着 SMRT Link V11.0 软件的发布，PacBio 已经实现通过HiFi测序直接检测 DNA 样本中 CpG 位点的 5-甲基胞嘧啶（5mC甲基化）。从现在开始只需在HiFi测序时在 SMRT Link Run Design 中选择 5mC 检测，Sequel II 和Sequel IIe 系统将会在 .bam 文件中自动输出带有标签的 HiFi 数据，这些标签包括 CpG 位点 5mC 甲基化的位置和概率信息。 


![](https://files.mdnice.com/user/4331/a8b57503-c62d-40bf-ab3d-e40e775fea0c.png)


## 博文资讯

5、[中国英文科技期刊：Research](https://mp.weixin.qq.com/s/7vP6p2IctaSCHdQ2dBysZQ)

![](https://files.mdnice.com/user/4331/aee04be3-b537-49cd-a442-8cbbd4d92cc0.png)

Research (ISSN 2096-5168 EISSN 2639-5274 CN 10-1541/N)是中国科学技术协会与美国科学促进会于2018年共同创办的综合性科技期刊，是美国Science 自1880年创刊以来的第一本合作期刊。Research 定位为国际化、高影响力的世界一流水平期刊，对标 Science 和 Nature。

![](https://files.mdnice.com/user/4331/df190348-6a83-46c1-bcef-8a0758172ed6.png)

- 期刊网址：https://spj.sciencemag.org/journals/research/



6、[simplifyEnrichment 新特性：展现你的分组特异 pattern](https://twitter.com/jokergoo_gu/status/1565382698880860163)

最新版本支持在左侧添加不同组别的富集条目数目的比较条形图，为不同的分组比较带来更直观的效果。

![](https://files.mdnice.com/user/4331/4a0fa277-9e60-4e7f-9b29-dce9094a3030.png)


7、[这次终于彻底理解了傅里叶变换](https://mp.weixin.qq.com/s/xLVa3dhvd7fk_xIBAvH-Pw)


![](https://files.mdnice.com/user/4331/61d1b74b-c08f-4c3a-8ac2-ed134d005ae0.png)

太有意思了！！！任何一段波长，都可以分解为若干正弦波的组合；任何一个2D图形可以被通过周转圆分解为若干2D正弦波的组合，同样适用于3D。这就是傅里叶变换，可以将事物分解成不同频率的正弦波。

- 原文链接：https://www.jezzamon.com/fourier/index.html



8、[ ivs (said, “eye-vees”) - 处理区间R包介绍](https://blog.davisvaughan.com/posts/2022-04-20-ivs-0-1-0/)


![](https://files.mdnice.com/user/4331/95ffcdac-6a1b-4f9d-a24f-b21f924ddd94.png)

本文通过具体实例介绍了如何使用ivs包进行时间（日期）上的交叉重叠计算，以及相关的拓展应用。


9、[WGCNA原理及实操](https://mp.weixin.qq.com/s/2VXprzgJSYJ39AhZ_FprCQ)


![](https://files.mdnice.com/user/4331/86325670-b777-42f4-8e2d-ded39a6fd72e.png)

WGCNA最初用于芯片测序数据，也适用于RNA-seq数据。本文详细介绍了WGCNA分析的原理，并参考官网代码与数据进行了实操。

- WGCNA官网教程: https://horvath.genetics.ucla.edu/html/CoexpressionNetwork/Rpackages/WGCNA/)

## 工具

10、[cbpManager - R包](https://github.com/arsenij-ust/cbpManager/)


![](https://files.mdnice.com/user/4331/a7c1db93-6b71-46ac-93d7-dd33dd41b42b.png)

R包cbpManager提供了一个R Shiny应用程序，它有助于生成适合于癌症基因组学cBioPortal导入的文件， 从而让用户能够管理和编辑临床数据，维护新的患者数据。


11、[notestar - R包](https://github.com/tjmahr/notestar)


![](https://files.mdnice.com/user/4331/defaf82b-287e-43af-a524-5a9b190eaa44.png)

Notestar包是一个基于 targets包所开发的便于记录的笔记系统包，适用于平常的数据分析项目中，具体使用可参考[示例教程](https://github.com/tjmahr/notestar-demo)。


12、[paint - data.frame彩色打印包](https://github.com/MilesMcBain/paint)


![](https://files.mdnice.com/user/4331/391af523-4d14-41d5-9327-65c3442f6a03.png)


13、[MetBrewer - 纽约大都会艺术博物馆大师级作品的配色方案](https://github.com/BlakeRMills/MetBrewer)


![](https://files.mdnice.com/user/4331/2b46ce01-7aa2-439d-852f-45dd18711f0f.png)

调色板的灵感来自于纽约大都会艺术博物馆的作品。所选作品来自不同的时期、地区和媒介。


14、[ggprism - GraphPad Prism风格的绘图包](https://github.com/csdaw/ggprism)


![](https://files.mdnice.com/user/4331/f29c66c1-b53a-4ac3-87d3-393dd79046a7.png)


在ggplot的基础上修改图，功能：theme_prism(）修改主题；scale_colour_prism()修改颜色；scale_fill_prism() 修改填充颜色；scale_shape_prism()修改点的形状；以及其他：修改坐标轴，添加p值等。

- R包教程：https://csdaw.github.io/ggprism/articles/ggprism.html

## 资源

15、[BS831 Genomics Data Mining and Statistics
课程材料](https://montilab.github.io/BS831/index.html)

该课程将学习代码和材料融合在一个R包中，方便学习。课程包括7个模块：1) Introduction to Genomics Analysis; 2) Data Preprocessing and Quality Control; 3) Comparative Experiments based on Microarrays and Linear Models (LM); 4) Comparative Experiments based on RNA-sequencing and Generalized Linear Models (GLM); 5) Comparative Experiments based on Differential Enrichment Analysis; 6) Classification; and 7) Clustering and Class Discovery.


![](https://files.mdnice.com/user/4331/69554327-f247-4c3d-bdba-f8f5be27efa1.png)


16、[微软 GitHub 开源技术教程](https://mp.weixin.qq.com/s/rK8U_QR6uSbQYhzQGqohGw)


![](https://files.mdnice.com/user/4331/11b46d78-ef74-4ec7-9ecd-80b81985bb90.png)

微软在 GitHub 推出了一系列「XX-for-Beginners」的开源技术教程。顾名思义，就是写给初学者看的技术教程，里面覆盖了 Web 开发、机器学习、Python、物联网、全栈、数据科学、DevOps 等诸多内容。以上内容已收录至 GitHubDaily 的开源项目列表中：https://github.com/GitHubDaily/GitHubDaily


17、[150年《自然》杂志精选的809篇文章，集合在一套书里](https://mp.weixin.qq.com/s/eBs1c6J2ZFNC55SzXznC0Q)


![](https://files.mdnice.com/user/4331/aa0890f3-6ab3-45ad-81eb-72d4c41a304a.png)

不缺钱的可以买着收藏～


## 历史上的本周

- 2021：[第 3 期：百年杨振宁](https://mp.weixin.qq.com/s/Rik1s8Tz8vGYfSg-xJXH_w)

## 贡献者（GitHub ID）

「Openbiox 生信周刊」运维小队：

- `@ShixiangWang`
- `@kkjtmac`
- `@NiEntropy`
- `@He-Kai-fly`
- `@JnanZhang`
- `@Tomcxf`
- `@wangdepin`

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

