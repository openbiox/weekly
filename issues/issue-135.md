---
date: 2024-08-11
comments: true
---

# 生信爱好者周刊（第 135 期）：中国已经成为一个科学超级大国

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![](https://github.com/user-attachments/assets/9238f818-d6be-4a7b-80b3-36d783dc0f50)


## 本周话题：中国已经成为一个科学超级大国

![](https://github.com/openbiox/weekly/assets/25057508/8fdf17d2-c749-4a2f-9c36-0d9c2a607dba)

近些年随着国家对科研的大量投入，我们看到多个领域中我国的高影响文章贡献越来越多，国外经济学人杂志专门对此撰文。

`@ShixiangWang`：国家有时候像人一样，怕别人不追，又怕别人追上。我们国家的进步一方面敦促我们作出更好的成果，但同时对国内的科研竞争环境造成了或好或坏的影响，需要让子弹多飞一会儿。

## 生信研究

1、[Nature | 快速纳米孔测序+机器学习，手术期间实现中枢神经系统肿瘤的准确分类](https://mp.weixin.qq.com/s/bOImrshTU8VXhJKQ8KO07w)

![](https://github.com/user-attachments/assets/8585ca6f-702a-407f-8c55-e9c351787607)

近日，来自荷兰的研究团队开发了一种与患者无关的迁移学习神经网络Sturgeon，可用于CNS肿瘤的分子亚分类。将快速纳米孔测序与Sturgeon模型结合，在45个回顾性CNS肿瘤样本开始测序后40分钟内，Sturgeon给出了准确诊断。研究团队在25次手术过程中展示了该方法的实时适用性，实现了不到90分钟的诊断周转时间。

- 文章链接： https://www.nature.com/articles/s41586-023-06615-2

2、[NBT｜MMseqs2：超快速和敏感的序列比对和聚类软件](https://mp.weixin.qq.com/s/TvdmZ_TBGv5zpKCQKFLcBA)

![](https://github.com/user-attachments/assets/421a4e19-4da1-4e69-9389-ecb17bef2a8f)

MMseqs2（Many-against-Many序列搜索）是一个用于搜索和聚类大规模蛋白质和核苷酸序列集的软件套件。MMseqs2是在Linux、MacOS和（作为测试版本，通过cygwin）Windows上实现的开源GPL许可软件，采用C++编写。该软件设计用于在多个核心和服务器上运行，并具有非常好的可扩展性。MMseqs2的运行速度比BLAST快10000倍。以100倍的速度，它几乎能达到相同的灵敏度。在超过400倍的速度下，它可以执行与PSI-BLAST相同灵敏度的配置文件搜索。


- 文章链接：https://www.nature.com/articles/nbt.3988

3、[Nat Commun | 基于12种癌症类型的多组学数据分析，揭示体细胞结构变异对癌症蛋白质组的影响](https://mp.weixin.qq.com/s/kai8RQQOE7Bve1KofVQnIA)

![](https://github.com/user-attachments/assets/5d0c0d73-0cbb-47b8-b97d-30857c887ad5)

探究癌症中特定体细胞SV事件的真正功能影响，可能会对个体化精准治疗产生积极作用。近年来，基于质谱（MS）的蛋白质组学技术发展迅速，使得在数百种人类肿瘤标本中分析数万种蛋白质特征的表达成为可能。此外，临床肿瘤蛋白质组学分析联盟（CPTAC）等重大科学研究也已产生了基于MS的蛋白质组学分析数据，以及相应的多组学数据。美国贝勒医学院、阿拉巴马大学伯明翰分校的研究将基于MS的蛋白质组学数据与跨不同癌症类型的WGS、多组学数据相结合，以确定体细胞SV断点模式对附近基因蛋白表达的影响。结果显示，在mRNA水平上与SV相关、受顺式调控改变的数百个基因中，约25%在蛋白质水平上具有类似的相关性。此外，一部分与SV-蛋白相关的基因，与较差的患者生存模式或癌细胞系中基因敲除敏感性相关。

- 文章链接：https://doi.org/10.1038/s41467-023-41374-8



## 博文资讯

4、[管道与命令返回值](https://mp.weixin.qq.com/s/1tNDTvit9rDoSdSAwkomyQ)

![](https://github.com/user-attachments/assets/4391360e-f99f-43fa-b6e1-66134f73a8df)

本文介绍管道命令返回值使用`$?`判定的局限性，并介绍了解决方案`${PIPESTATUS[*]}`

5、[Wishlist-for-R](https://github.com/HenrikBengtsson/Wishlist-for-R)

这是一个github仓库，参与者可以将对R语言的建议提交到issue里面。

6、[How to run R code in the browser with webR](https://blog.djnavarro.net/posts/2023-04-09_webr/)

![](https://github.com/user-attachments/assets/b38a3565-1e3f-44c3-b959-d44dc9bb0ce8)

本文介绍了如何使用 webR 在浏览器中运行 R 代码。


## 工具
 
 
7、[CNAqc](https://github.com/caravagnalab/CNAqc/)

![](https://github.com/user-attachments/assets/98a6c0d2-0edc-4a7c-a44e-ece802095e8a)

CNAqc 是一款可以对bulk癌症测序数据进行QC的R包。 可用于以下数据的可视化和分析： 1.  体细胞突变，包括单核苷酸变体和插入缺失 2. 等位基因特异性拷贝数改变 （CNA） 和 3. 肿瘤纯度估计。

8、[SolidUI ｜ 一句话生成任何图形](https://github.com/CloudOrc/SolidUI)

![](https://github.com/user-attachments/assets/51f38c89-6bcd-4a56-a288-1dcf2585e5d1)

随着文本生成图像的语言模型兴起，SolidUI想帮人们快速构建可视化工具，可视化内容包括2D,3D,3D场景，从而快速构三维数据演示场景。SolidUI 是一个创新的项目，旨在将自然语言处理（NLP）与计算机图形学相结合，实现文生图功能。通过构建自研的文生图语言模型，SolidUI 利用 RLHF (Reinforcement Learning Human Feedback) 流程实现从文本描述到图形生成的过程。


9、[https://github.com/klmr/box](https://github.com/klmr/box)

```r
box::use(mod/hello_world)

hello_world$hello('Ross')
#> Hello, Ross!
```

box 实现了在 R 中使用类似 Python 的模块策略组织代码。


## 资源

10、[system-design-101](https://github.com/ByteByteGoHq/system-design-101)

![](https://github.com/user-attachments/assets/9d1f7d4e-e15c-47e8-959e-6a0a48c142ec)

使用视觉效果和简单术语解释复杂的系统。

## 历史上的本周

- 第 95 期：[中国人群泛基因组联盟](https://mp.weixin.qq.com/s/NW3leIwLOADiYYePGPoKEw)

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
- `@donghongyu2020`（董弘禹）
- `@DrRobinLuo`（罗鹏）

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

