---
date: "2023-4-1"
comments: true
---

# 生信爱好者周刊（第 53 期）：为什么现在的中国大学生普遍焦虑内卷？

这里记录每周值得分享的生信相关内容，周日发布。
本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。
[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo) | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community)

## 封面图
![](https://files.mdnice.com/user/5208/b1e089ca-0fc5-4e6c-bb9d-535b7d1b0f66.png)


## 本周话题：[为什么现在的中国大学生普遍焦虑内卷？](https://mp.weixin.qq.com/s/e7JBmNiA2tDwNLyR76-yOg)

>  钱颖一教授根据自己在清华担任教师、院长17年期间的改革实践、深入观察以及与学生的倾心交流，将两个著名的钱氏问题进一步具体化为当前中国大学学生培养中的七个普遍现象和七个重要权衡，并追溯到市场和政府的评价体系以及 “育才” 压倒 “育人” 的状况。由此提出钱氏问题的 “第三维缺位论”——教育在市场和政府之外的第三维缺位了，即教育内在的评价和愿景这个维度的缺位。

@He-Kai-fly - 剖析“内卷”背后的原因，离不开一个词：竞争。大学生们内卷，也是应对竞争压力的正常反应。但卷的同时自己也需要想明白“我到底希望成为怎样的人”。

## 生信研究

1、[Genome Research|高效捕获染色质开放位点和染色质相互作用的新技术NicE-C](https://mp.weixin.qq.com/s/KVFsF9zZK60hyoo4pDQ8uQ)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202211182132679.png)

中国科学技术大学生命学院与医学部宋晓元课题组基于染色质构象捕获（3C）及其相关技术的研究揭示了哺乳动物细胞内不同层次的染色质高级结构，包括染色质隔室（A/B compartments）、拓扑结构域（TADs）和染色质环（chromatin loops）。研究表明启动子与增强子间可以通过形成染色质环（E-P loops）来调控基因的表达，该成果近期发表于**Genome Research**期刊上。

论文链接：https://genome.cshlp.org/content/32/3/534.long


2、[Nature Communications| 基于scRNA-Seq数据的细胞通讯推断的不同方法和资源比较](https://www.nature.com/articles/s41467-022-30755-0)



![](https://files.mdnice.com/user/5208/c07db8ad-6054-4785-839c-7f1e00651e46.png)


当前有许多计算工具用于细胞通讯推断，每个都有其相应的细胞间相互作用先验知识资源和预测潜在细胞通讯事件方法。然而，细胞通讯资源和推断方法的选择对结果预测的影响，在很大程度上尚不清楚。为了阐明这一点，作者团队系统地比较了16个细胞通讯推断资源和7种方法，以及不同方法预测的一致结果。在这些资源中，仅发现较少的特有相互作用，存在不同程度的重叠，以及在特定途径和组织富的蛋白质的不均一覆盖度。作者团队测试了不同方法和资源的所有可能组合，提出两者都能很大程度影响着细胞间相互作用结果的预测。为了方便使用该工作中描述的方法和资源，作者团队提供LIANA（LIgand-receptor ANalysis frAmework）R包供用户使用。

论文链接：https://www.nature.com/articles/s41467-022-30755-0

3、  [Science Advances | 癌症体细胞突变AI注释平台——CancerVar](https://mp.weixin.qq.com/s/yV6rfz8_0aPZyiJXBFmSIg)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202211151300320.png)

美国费城儿童医院**王凯团队、周筠筠团队及合作者**联合在***Science Advances***发表了一种改进版的体细胞突变体解释工具——**CancerVar**，是基于Python编程语言搭建的一个网络服务器，包含1,911个癌症相关基因中1,300万个体细胞突变的临床证据。**用户可以使用染色体位置或蛋白质变化等信息查询变异的临床解释，并基于先验知识或其他用户指定的标准，交互式微调特定评分特征的权重。**CancerVar能够自动生成总结描述性解释的文本，包括诊断、预后、靶向药物反应和许多热点突变的临床试验信息，大大减少了精准肿瘤学实践中临床医生的工作量。 

论文链接：https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9075800/

4、[Nature Genetics | 为何很多吸烟者不会患肺癌？单细胞测序发现部分吸烟者肺部体细胞突变频率存在上限](https://mp.weixin.qq.com/s/ZhmFpAXtVJCKO17JFkFfAA)


![](https://files.mdnice.com/user/5208/c0161030-cce1-4fe6-aab2-6fcdd822d685.png)

为什么大多数烟民不会患肺癌？Nature Genetics期刊上一篇文章利用单细胞全基因组测序技术，对不吸烟者和吸烟者的肺细胞进行测序。结果提示虽然吸烟者肺细胞中的突变频率更高，但是当吸烟量累积到一定量时，DNA突变率增加趋于平稳，这使重度吸烟者的突变频率与轻度吸烟者没有显著差异，限制了肺部细胞的突变积累，从而降低肺癌风险。

论文链接：https://www.nature.com/articles/s41588-022-01035-w


## 博文资讯
5、 [How to precompute package vignettes or pkgdown articles](https://ropensci.org/blog/2019/12/08/precompute-vignettes/)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202211182137663.png)

截至今年早些时候，我们针对所有rOpenSci包都会自动构建二进制和pkgdown文件，我们遇到的问题是一些含有vignette的包都需要一些特殊的工具/数据，而这些在通常在服务器上不可用。这个博客将说明如何在你的包中包装这样的vignette和文章。

6、[scRNAtoolVis - 提供了一系列个性化单细胞数据可视化函数](https://mp.weixin.qq.com/s/vnaHjPYBC-rzzInUm5FRPw)

![](https://files.mdnice.com/user/5208/854f8df4-c83b-4cf7-afb2-80da7da27862.png)

GitHub: https://github.com/junjunlab/scRNAtoolVis

7、 [英国生物样本库UKB-PPP开创性蛋白组学研究进展首批发布](https://mp.weixin.qq.com/s/wzduw423WhTsAetgwFi3Rg)


![](https://files.mdnice.com/user/5208/9d7676d1-c665-46e5-9afa-c53d7baee93b.png)


英国生物样本库（UK Biobank, UKB）是目前世界上最大、最全面的生物医学数据库和研究资源之一，致力于对生物样本进行高通量蛋白组检测，已与由十家顶级生物制药公司组成的联盟联合，启动了一项全球最大的血液蛋白组研究。最近，英国生物样本库联合数十家药厂发布的基于Olink ExploreTM平台的开创性蛋白组学研究，首次披露针对54,306参与者的蛋白组学和基因测序的数据进行pQTL（Protein Quantiative Trait Loci）Mapping分析，通过对1,463蛋白标志物的研究，发现了10,248个主要遗传关联，其中85%之前尚未有过报道。  

论文链接：https://doi.org/10.1101/2022.06.17.496443

8、[中国基因测序产业链图谱与市场分析](https://mp.weixin.qq.com/s/iolVNLbLn30NRATcFIvikg)

![](https://files.mdnice.com/user/5208/d6d6142a-edc9-4b93-bdea-20dd9cf1ab4d.png)


本文系统地介绍了基因测序产业在我国的发展情况。值得注意的是该产业链基本还没有走向普通百姓哈（除了一些带忽悠的遗传风险检测体检服务），全世界都还在基础科研和临床研究中应用。

> 我国基因测序行业正处于高速成长阶段，部分创新企业的三、四代测序技术达到国内领先、国际先进水平，越来越多的具有完全自主知识产权的基因测序产品获批上市实现商业量产，实现基因测序仪进口国产化替代。随着技术的进步、精准医学的发展和利好政策的推动，我国基因测序市场拥有巨大的应用前景，我国基因测序行业迎来“黄金期”。

9、[第15届中国 R 会（北京）-机器学习专场](https://mp.weixin.qq.com/s/px9E9zLooyOR5Fjb7q_CyA)


![](https://files.mdnice.com/user/5208/c68268f1-9c5f-43ad-8c0c-b793c5e92c2e.png)


> 时间：2022年11月20日 上午8:30-10:55
> 
> 腾讯会议号：191863973


## 工具
10、[ggblend | 修改图层融合叠加的ggplot2扩展包](https://github.com/mjskay/ggblend)


![](https://files.mdnice.com/user/5208/4bad2ebf-c703-447c-bb37-685e1263b2f0.png)


ggblend是在ggplot2基础上修改图层融合模式等细节的扩展R包。


11、[eVITTA - 转录组分析的一个简单的分析可视化工具箱](https://github.com/easygsea/eVITTA)


![](https://files.mdnice.com/user/5208/660f4004-b712-421b-8f7a-5cf673a49d21.png)


主要提供了 3 个分析可视化模块，通过 https://tau.cmmt.ubc.ca/eVITTA/ 可以在线访问，适合不会生信的同志们。

12、**Cog—用于机器学习的容器**

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202211190934158.png)

Cog是一种可以让您在标准的、可制作生成的容器中包装机器学习模型，您可以将包装模型部署到自己的基础架构中，也可以进行复制。

Github：https://github.com/replicate/cog


13、 [Science| CellTypist-跨组织免疫细胞分析揭示了人类组织特异性特征](https://www.celltypist.org/) 

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202211151327450.png)

人免疫系统由许多不同的细胞类型组成，但目前对这些细胞类型的细胞类型的细胞变化鲜为人知。使用单细胞基因组学，检查了从12个已故的成人器官供体中从16个不同组织中提取的300,000多个单个免疫细胞的基因表达谱。使用CellTypist（由作者设计的自动化细胞分类工具）分配细胞身份,深入的数据分析揭示了有关免疫系统如何适应在不同器官环境中有效起作用的见解。  

Github: https://github.com/Teichlab/celltypist  
官网：https://www.celltypist.org/  
文章：https://www.science.org/doi/10.1126/science.abl5197




## 资源
14、[工具/资源推荐 | 支持中文！秒建 wiki 知识库的开源项目，构建私人知识网络](https://zhuanlan.zhihu.com/p/498848013?utm_source=wechat_session&utm_medium=social&utm_oi=841811531518836736)


![](https://files.mdnice.com/user/5208/d82ef40e-7acf-4497-9e71-b850942fc0eb.png)


wiki.js 是一款轻量级、功能强大的 wiki 开源项目，拥有评论、Markdown 编辑器、图片上传、标签、全局搜索、协同编辑、编辑历史、用户管理、谷歌分析等功能，而且支持高度自定义。

Github：https://github.com/requarks/wiki

15、 [ggplot2语法的韦恩图绘制R包-ggvenn](https://github.com/yanlinlin82/ggvenn)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202211151331022.png)

韦恩图可以用来展示各个数据集直接的重叠关系，ggvenn包设计灵感来自于Venny, 主要函数为ggvenn，符合ggplot2的基本语法。

16、**UpSetR - 一个产生静态UpSet图的R包**

UpSetR产生静态的UpSet图形，这UpSet技术可根据分组和查询的集合交叉点进行可视化，有效的展示相关数据统计信息。对于更详细细节可参考[UpSet website](http://vcg.github.io/upset/about/)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202211190952463.png)

Github：https://github.com/hms-dbmi/UpSetR


## 历史上的本周
- 2021：[第 13 期：他开发了基因界的百科全书，贡献却少有人知](https://mp.weixin.qq.com/s/U4NAw3xMqxrYCfLFaDER-Q)
## 贡献者（GitHub ID）

「Openbiox 生信周刊」运维小队：

- `@ShixiangWang`（王诗翔）
- `@kkjtmac`（阚科佳）
- `@NiEntropy`（赵启祥）
- `@He-Kai-fly`（何凯）
- `@JnanZhang`（张佳楠）
- `@Tomcxf`（陈啸枫）
- `@wangdepin`（王德品）

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

