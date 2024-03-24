---
date: 2024-03-24
comments: true
---
# 生信爱好者周刊（第 116 期）：我国科研影响力是否已达到世界顶尖水平？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![](https://files.mdnice.com/user/33257/fa4efd5d-8f5b-46d1-af5d-7b559ea1ef82.png)
[英国的灯塔：每一个发光的点，就是一个灯塔。](https://fosstodon.org/@terence/111132852910410221)

## 本周话题：我国科研影响力是否已达到世界顶尖水平？PubMed论文按国别引用分析

@kkjtmac [这篇帖子](https://mp.weixin.qq.com/s/ZLUSFhtUDyVenUN--7IXow)从相对客观的指标-引用数（一个国家的论文被其他国家论文引用的次数）来反映该国的科研国际影响力，最终的结论是虽然我国虽然论文数很高（世界第二），但是论文的平均他引数并不高，大约是美国的1/3，在前10个国家中垫底。这一数据也提示了目前我国科研更加关注从数量向质量的转变（当下的整个评判体系也卷到这个层面了）。

## 生信研究

1、[Nucleic Acids Research | 哈工大/腾讯AI实验室合作构建迄今最大规模的单细胞蛋白质组数据库SPDB](https://mp.weixin.qq.com/s/m6rIuXh-m-D-M5vSxjOTJA)

![](https://files.mdnice.com/user/33257/246cb881-b5a4-46e6-9493-5d601185bccc.png)

SPDB(Single-cell Proteomic Database)是由哈尔滨工业大学研究团队联合腾讯人工智能实验室团队构建的单细胞蛋白质组学数据库。SPDB集成了来自12种基于抗体和质谱技术的143个单细胞蛋白质组学数据集，涵盖了4个不同物种（人类、小鼠、猕猴和猪）的3亿个细胞和8000多种不同的蛋白质。
作为一个用户友好的数据库，SPDB提供了广泛的功能，包括单细胞蛋白质组数据部署，数据集搜索和挖掘模块、蛋白质搜索和挖掘模块、数据统计模块，以及详细的用户手册。

- 论文链接：https://doi.org/10.1093/nar/gkad1018
- 数据库链接：https://scproteomicsdb.com/ 

2、[Nature Genetics | BANKSY：革命性算法，重塑空间组学数据分析](https://mp.weixin.qq.com/s/qO0gkkHtdjRWQ2uGWG5Zlw)

![](https://files.mdnice.com/user/33257/3f3d8027-7da1-49ae-95ce-f9dc8686389f.png)

Nature Genetics提供了一种名为BANKSY的空间组学数据分析算法（Building Aggregates with a Neighborhood Kernel and Spatial Yardstick），基于该算法的工具将空间组学数据中的细胞根据类型和组织域进行有效分类。通过结合细胞自身的转录组数据和其在微环境中的空间关系，有效地提高了细胞分类的准确性和效率。

- 论文链接：https://www.nature.com/articles/s41588-024-01664-3

3、[Nature Methods | scPerturb：统一的单细胞扰动数据](https://mp.weixin.qq.com/s/9yyrBtY6pTf69f8VPdAUDQ)

![](https://files.mdnice.com/user/33257/5d73038c-8b33-42ce-af32-f2cd25855b3d.png)

研究人员的工作通过对44个公开的单细胞扰动数据集（CRISPR、药物等“扰动”，然后测单细胞转录组、染色质开放性以及蛋白质组等数据）统一质控和注释，从而构建便于进一步协同整合分析的数据集- scPerturb。进一步，研究人员结合分析不同细胞群之间特征差异的统计方法“E-statistics”，分析了不同数据集在各种条件（比如靶向不同的基因等）下的扰动强度（用E-distance显示）、扰动显著性（E-test分析（基于Monte Carlo permutation））及其分析影响因素（细胞数、测序深度）。

- 论文链接：https://www.nature.com/articles/s41592-023-02144-y

## 博文资讯
4、[漫画介绍孟德尔随机化](https://mp.weixin.qq.com/s/-1syM5RrzlxYlMCfuvedlg)

![](https://files.mdnice.com/user/33257/778b3e05-a18a-43b1-9c55-45929042ffb4.png)

原始素材通过动画以“吸烟会影响寿命吗？”为例介绍孟德尔随机化。

5、[Molecular Cancer同款 | 桑基图](https://mp.weixin.qq.com/s/LzVlyUYV0GUF2SseefFejw)

![](https://files.mdnice.com/user/33257/76ff7980-9cde-4660-9f38-16bc67bc153a.png)

本文结合具体实例复现了[Molecular Cancer一文](https://doi.org/10.1186/s12943-023-01876-x)中不同样本类型中各亚群细胞比例的可视化结果。

6、[开源的测序仪，你敢想象？！](https://mp.weixin.qq.com/s/X1r4ZCnhBlwQkCw5J1thfQ)

![](https://files.mdnice.com/user/33257/bef63125-2cdc-4d01-b0f6-407c3915ebe2.png)

[美国公司454 Bio](https://454.bio/#td-block-1)的开源了DNA测序平台及相关技术（个人可以下载说明来搭建自己的DNA测序设备）。
该平台的主要功能包括：
- DIY DNA 测序设备的说明：易于遵循的可在家构建DNA测序设备的指南。
- 可定制的测序试剂盒：用户可以根据其个人研究需求创建特定于应用的测序耗材。
- 简化的分子生物学操作协议：该平台简化了复杂的程序，使非专家也可以管理使用。
- 社区驱动的创新：鼓励用户分享他们的修改和改进，为持续开发营造协作环境。

7、[学术期刊的长期和短期影响力分析](https://mp.weixin.qq.com/s/iIvkz4xvba_D9VVmwIFY5w)

本文通过2000到2023年之间pubmed生物期刊上发表的论文数和被引数，结合相关图表展示了不同期刊的长期和短期影响力：
- 总被引用数：展示了过去23年中被引用最多的前20个期刊。PNAS位居榜首，其次是PloS one和Nature，尽管PloS one的发文量远超过Nature和其他顶级期刊。
- 发表论文数：展示了这些期刊上发表的论文数量。
- 平均被引数：计算了每个期刊论文的平均被引次数，这是一个长期的平均引用指标，与影响因子不同。PloS one和Scientific reports的平均被引数较低，主要是由于它们的高发文量。

## 工具
8、[SEACells | 从单细胞基因组学数据推断转录和表观基因组细胞状态](https://mp.weixin.qq.com/s/-QqkQGWKPQzMiRpIikKMqA)

![](https://files.mdnice.com/user/33257/f6790db8-228e-4477-b4ca-296129602df4.png)

SEACells算法通过克服单细胞数据的稀疏性问题，同时保留传统细胞聚类可能掩盖的异质性，来识别元细胞。该算法在检测RNA和转座酶可及染色质（ATAC）模式的元细胞方面表现出色，能够全面、紧凑且分离良好地识别具有离散细胞类型和连续轨迹的数据集。

- 论文链接：https://www.nature.com/articles/s41587-023-01716-9
- 工具链接：https://github.com/dpeerlab/SEACells

9、[ShinyCell | 开发用于单细胞数据的交互式界面的R包](https://github.com/SGDDNB/ShinyCell)

![](https://files.mdnice.com/user/33257/bb8de73d-f709-4eb5-8fb6-bcfa278830db.png)

ShinyCell基于R语言的Shiny框架开放的开源工具包，用于构建交互式的数据可视化和Web应用程序。通过ShinyCell，用户可以创建直观的界面来展示和分析单细胞测序数据，使得复杂的数据更容易理解和探索。

- 工具链接：https://github.com/SGDDNB/ShinyCell

10、[syncthing | 开源的文件持续同步软件 ](https://github.com/syncthing/syncthing)

![](https://files.mdnice.com/user/33257/80687203-e0ab-41e2-83b7-4e4fad64cef6.png)

syncthing是一个支持多平台、允许用户在多个设备之间无缝同步文件和文件夹的开源软件。Syncthing使用了分布式的P2P（点对点）技术，这意味着同步操作直接在设备之间进行，无需通过中央服务器进行数据传输。

- 工具链接：https://github.com/syncthing/syncthing

## 资源
11、[生信导师推荐](https://zhuanlan.zhihu.com/p/441702265?utm_psn=1724834761464512512)

![](https://files.mdnice.com/user/33257/4b32df7d-3a78-4da3-9beb-9a35c1f4b698.png)

本文系统整理了生物信息方面的导师，感兴趣的同学建议都看看。

- 资源链接：https://github.com/DC-Jade/bioinfo_pi_atlas

12、[Mastering Software Development in R](https://rdpeng.github.io/RProgDA/)

![](https://files.mdnice.com/user/33257/87fee3db-462f-403b-8e6e-f2c004ece591.png)

本资源是与Coursera上的课程“Mastering Software Development in R”配套使用的教材。通过学习可以获得包括处理复杂数据、构建R包和开发定制数据可视化的技能。

- 资源链接：https://rdpeng.github.io/RProgDA/index.html

13、[每个生物信息学家都应该知道的十大免费在线工具](https://mp.weixin.qq.com/s/-PRnXP5HcePjyrPha9ofaA)
本资源分享的是每个生物信息学家都应该熟悉的不可或缺的工具，这些工具在生物信息学的各个方面都很有用，帮助专业人员完成从访问数据库到分析基因序列和预测蛋白质功能的任务。

## 历史上的本周

- 第75期：[学术需要批判氛围](https://mp.weixin.qq.com/s/Kffkr73VHnBvEQjb4zqivg)

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