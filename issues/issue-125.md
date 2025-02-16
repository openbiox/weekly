---
date: 2024-06-02
comments: true
---

# 生信爱好者周刊（第 125 期）：一周是一年的2%

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图
![](https://files.mdnice.com/user/33257/85fe79c7-26b3-4865-bc64-7493072152c6.png)
[重建的人类大脑皮层](https://www.science.org/doi/10.1126/science.adk4858 "重建的人类大脑皮层")
## 本周话题：一周是一年的2%
本周的话题来自[科技爱好者周刊（第293期）](https://www.ruanyifeng.com/blog/2024/03/weekly-issue-293.html "科技爱好者周刊（第293期）")
> 我一直觉得，每周七天是很短的时间，尤其是发布周刊以后，更是过得飞快。但是，他的这句话让我意识到，每周其实是一年当中很重要的组成部分。虚度一周就是虚度一年的2%。你没有几周可以虚度的。只要多浪费几周，这一年很快过去。反过来，过好这一周，那么这一年的2%就有价值了。只要这样多过几周，一年就会变得很充实，有拿得出手的成果。我坚持写周刊，每周记录一点东西，整理一些思考，现在想起来，其实就是在督促自己过好这一年的2%。

@kkjtmac 一周作为一年52周中的一个，确实大约占据了一年时间的2%，这个数据突然让我认识到一年的短暂以及如何在一年中划分和利用时间。

## 生信研究
1、[Nature communications | 100多个数据集的单细胞泛癌分析](https://mp.weixin.qq.com/s/xsOuEcYQ00QcYYbd2vHMdA)

![](https://files.mdnice.com/user/33257/cfc814d2-4374-4c68-9b18-ea567e4a9853.png)

这篇Nature Communications的泛癌scRNA-seq研究，作者系统整合了30多种癌症的104个数据集，涵盖单细胞、bulk和空间转录组学数据，构建了一个庞大而丰富的泛癌单细胞图谱。通过多角度、多层次的分析，揭示了肿瘤微环境中免疫细胞和间质细胞的异质性特征，绘制出各种细胞状态在不同器官和癌症中的分布图景。文章还利用空间转录组数据，分析了不同细胞状态在组织空间的相互作用和临床意义。这项研究展示了整合多组学大数据研究肿瘤异质性的新思路。

- 论文链接：https://www.nature.com/articles/s41467-024-48310-4
- 文章代码：https://zenodo.org/records/10651059

2、[Science | 系统描绘转录起始连续动态全过程](https://mp.weixin.qq.com/s/8XxqAvJnzjcHioQovEMBHg)

![](https://files.mdnice.com/user/33257/73d57e1d-8582-4287-8026-371b8a04204a.jpg)

《Science》杂志这篇研究通过58万张冷冻电镜照片，首次捕捉并重建了转录从头起始的16个连续动态过程，详细揭示了通用转录因子与RNA聚合酶Pol II协同调控转录起始向转录延伸转变的分子机制，为深入理解基因表达调控提供了重要视角。

 - 论文链接：https://www.science.org/doi/10.1126/science.adi5120

3、[Cell Reports | 14种不同癌症类型的mRNA-蛋白相关性分析揭示基因突变如何影响转录后调控](https://mp.weixin.qq.com/s/soeIRg2dxa7nxB1Pq5-ncg)

![](https://files.mdnice.com/user/33257/b1c2c2ea-2d5c-45c8-977c-e986bb526ed9.png)

这篇发表在Cell Reports上的研究通过分析14种不同癌症类型的转录组和蛋白质组学数据，系统探索了癌症中转录后调控的全貌。研究发现一些关键基因在泛癌中受到强烈的转录后调控，且较高的mRNA-蛋白相关性与患者生存期缩短相关。此外，文章还揭示了癌症驱动基因突变如何影响转录后调控水平。这项工作加深了我们对癌症基因表达调控机制的理解，强调了系统性认识转录后调控在癌症诊断和预后中的重要性。

- 论文链接：https://doi.org/10.1016/j.celrep.2023.113172

## 博文资讯
4、[染色质三维结构 | compartment & TADs & loop](https://mp.weixin.qq.com/s/SbGoUgblN7Anqj_c-4BqHg)

![](https://files.mdnice.com/user/33257/cab01a31-7154-450d-8bd1-2333986c9318.png)

这几天听了有关三维基因组的几场报告，突然发现之前学的细胞生物学中染色体多级螺旋模型只是对染色质宏观的描述，染色质三维结构还能进行更精细的划分。这篇笔记主要整理一下染色质三维结构--compartment、TADs、loop。

5、[人类基因组计划的 RNome 研究](https://mp.weixin.qq.com/s/swfNHJ2D1aJf8bBYX5l1cw)

![](https://files.mdnice.com/user/33257/ed4ebbd4-1a23-4b52-999c-8bdb9f397bd0.png)

美国国家科学、工程和医学院 (NASEM)的一份报告提出了一项雄心勃勃的计划，呼吁开展类似人类基因组计划的RNome研究，重点关注RNA及其表观遗传修饰的测序。但到目前为止，大多数 RNA-seq 都是通过短读长测序完成的，它无法绝对确定地对许多 RNA isoforms进行测序。NASEM的共识研究报告概述了一项公私合作伙伴关系的 15 年计划，旨在开发新方法可以直接对 RNA 分子进行测序，并检测在其上发现的数十个（如果不是数百个）表观遗传修饰。除了技术开发之外，关键任务还包括制定 RNA 标准（可能在美国国家标准与技术研究院的帮助下）、培养精通 RNA 的科学队伍，并为这些工具创建新的应用程序。

- https://medicine.at.brown.edu/human-rnome-project-gets-underway/

6、[KEGG通路分析的可视化炫酷可视化--KEGG流星图](https://mp.weixin.qq.com/s/tc7f7A9rpQlqvrolU5c-SQ)

![](https://files.mdnice.com/user/33257/a6925e75-c4f2-44d8-b8ef-5069d1c3eb8a.png)

这篇文章介绍了一种新颖的KEGG通路分析可视化方法——KEGG流星图，突破了传统散点图的局限，更加直观、精美地展示富集结果。该方法不仅考虑了每条通路的p值和参与差异物的数量，还能体现出每条通路中上调和下调差异物的整体变化趋势。文中提供了详细的R代码实现过程，可以让读者轻松掌握并应用到自己的数据分析中。对于想要提升KEGG通路分析可视化水平的研究人员来说，KEGG流星图是一个新的选择。

7、[RNA速率分析](https://mp.weixin.qq.com/s/seG_3i04vlz6hkrZU25h3A)

![](https://files.mdnice.com/user/33257/2ce39461-1d97-4b9b-a751-34fa02f2f3b5.png)

RNA速率能够通过叠加剪接信息来推断细胞分化的方向性。本文介绍了基于scVelo如何估计RNA速率。

## 工具
8、[ Zotero不好用！计算机专业博士生，手搓一款开源免费且强大的文献管理神器！](https://mp.weixin.qq.com/s/53g2AMbq6wOqIEu1PrbzLg)

![](https://files.mdnice.com/user/33257/0881b999-252e-42ad-965a-013bd81ed4f6.png)

你在用zotero时有下面这个痛点吗？
很多会议论文例如，NIPS，ICLR，没有 DOI 编码，导致文献管理软件几乎无法匹配他们的发表信息元数据，那么在写论文的时候，不得不一次次的搜索 Google Scholar，DBLP 来确保引文的发表信息无误。
特别是在计算机领域，会议论文占据主要地位，如果每次都需要自己重新检索来匹配论文元数据，那确实挺费事的！
如果上面的痛点也是你的痛点，不妨继续往下看，看看一位计算机专业的博士生是如何解决这个问题的！
- 工具链接：https://paperlib.app/cn/

9、[一行代码就能发生信顶刊的GPTCelltype做单细胞亚群注释](https://mp.weixin.qq.com/s/fKZVW1DpmnwLRCFi_KMTVg)

![](https://files.mdnice.com/user/33257/64ce678a-ff9d-4716-8c09-93ee30295ef6.png)

在朋友圈刷到了一个（Published: 25 March 2024）的文章：《Assessing GPT-4 for cell type annotation in single-cell RNA-seq analysis》，题目短小精悍，就两个作者，关键是发表在《Nature Methods》杂志，算是生信顶刊了。

- 工具链接：https://github.com/Winnie09/GPTCelltype

10、[avatar | 在线虚拟形象设计网站](https://sinqi.tools/zh/avatar "avatar | 在线虚拟形象设计网站")

![](https://files.mdnice.com/user/33257/b96012bd-48f0-4cef-a305-6b302543afc2.png)

avatar是一个在线小工具，它允许用户创建虚拟形象或头像，可以用作社交媒体的个人资料图片、游戏中的代表角色等场合。用户可以通过选择不同的面部特征、发型、服装和其他自定义选项来设计自己的虚拟形象。

- 工具链接：https://sinqi.tools/zh/avatar


11、[AppFlowy | 开源的 Notion 替代品](https://mp.weixin.qq.com/s/1whTTHROIH65ZqAaTJL5BA)

![](https://files.mdnice.com/user/33257/823df6b4-6f09-4e82-9833-b71658138482.png)

AppFlowy是一个开源的Notion替代品，由Flutter和Rust构建，支持私有化部署，强调数据隐私和本地流畅体验。它具有社区驱动的可扩展性，可定制化强，易于集成AI对话等能力。界面美观，支持暗黑模式，同时提供项目管理和任务可视化功能。

- 工具链接：https://www.appflowy.io/
## 资源
12、[R Graphics Cookbook 第二版（英文）](https://r-graphics.org/ "R Graphics Cookbook 第二版（英文）")

![](https://files.mdnice.com/user/33257/ab5d6d17-ea64-4023-9373-cb412bc8bacb.png)

该书介绍了 R 常用的常用的任务处理的例子，非常值得参考。之前的第一版本我们 Openbiox 组织翻译了第一个中文版本 [Cookbook for R 中文版](https://openbiox.github.io/Cookbook-for-R-Chinese/ "Cookbook for R 中文版")。

13、[Outstanding User Interfaces with Shiny](https://unleash-shiny.rinterface.com/ "Outstanding User Interfaces with Shiny")

![](https://files.mdnice.com/user/33257/fd5eedfc-1e40-400f-9e22-7c12c8f10fd9.png)

本资源是David Granjon撰写的一本书籍，旨在填补Shiny初学者和高级用户之间的知识空白。该书深入探讨了如何深度定制和增强Shiny应用程序，使其界面与经典Web应用程序难以区分。自2012年Shiny首次提交以来，其社区已迅速发展，但直到2021年，还没有一个全面的资源来集中Shiny用户和开发者的经验和智慧。这本书由R包bookdown构建，由Kenton Russell推荐，认为它填补了搜索可能无法得到有用结果的主题空白。

## 历史上的本周

- 生信周刊第 84 期：[认识自己的缺点](https://mp.weixin.qq.com/s/JDXjzLqmTDsXxgUy_Miy_Q)

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