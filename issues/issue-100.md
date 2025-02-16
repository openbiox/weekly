---
date: 2023-11-18
comments: true
---

# 生信爱好者周刊（第 100 期）：朋友好

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图


![](https://files.mdnice.com/user/43254/96630006-0819-4fc1-8190-d81f063a35fa.png)


在美国阿拉斯州加克拉克湖国家公园，沙尘暴中的灰熊在海滩上用一只爪子挡住自己的眼睛躲避风沙。Ingo Arndt/高品图像 Gaopinimages

## 本周话题：朋友好

> 一个健康的社会，年轻人应该不仅希望自己有好朋友，而且希望朋友做的好，为朋友高兴。我们会有越来越多的人期待：中国的学术界将更多互相激励和欣赏而逐渐成熟；中国的社会将建立、营造和加强“互信、互乐、互助”的环境。 

@kongjianyang：从自身做起，相信这种期待同行越来越好的环境不仅会存在于学术界，也会扩散到整个社会！

## 生信研究

1、[Nature Genetics | 迄今最全面的人类肺细胞空间图谱，首次揭示腺体相关的免疫生态位](https://mp.weixin.qq.com/s/3QOpNTmsW6o6jFr3rXjYTQ)

![](https://files.mdnice.com/user/43254/d59bb56e-da4a-41c3-8d0f-341d06669661.png)


近日Nature Genetics上题为“A spatially resolved atlas of the human lung characterizes a gland-associated immune niche”的文章对已故器官捐献者的健康肺和气道进行了深层组织分析，沿着呼吸树近端到远端轴线对细胞类型进行描述，并使用无偏空间转录组学（ST）的方法确定健康人类肺和气道的组织微环境中的细胞类型和状态。

在文章中研究团队共区分了80种细胞类型和状态，其中包括11种在先前的肺图谱研究中未被注释的细胞群，绘制了迄今为止最全面的肺细胞图谱，并定义了一个腺体相关的免疫生态位。

- 论文链接：https://www.nature.com/articles/s41588-022-01243-4

2、[Genome Biology | 精细解析胃癌肿瘤微环境中的关键特征](https://mp.weixin.qq.com/s/tjRSIi3NayVYz1saT2ZFTA)

![](https://files.mdnice.com/user/43254/0f7dc361-7eba-4234-ab47-14d85125ead8.png)


研究团队使用单细胞转录组测序技术（scRNA-seq）全面分析了胃癌TME，并匹配了24例胃癌患者的正常样本，以生成胃癌间质的高分辨率细胞图谱。通过将这些单细胞数据与匹配的转录组测序数据相结合，研究团队捕获了胃癌中重要的失调生物过程，并确定了与胃癌生存率相关的细胞类型。

- 论文链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02828-2


3、[Cancer Cell | 序祯达生物多组学技术助力全球最大规模食管鳞癌分子分型研究](https://mp.weixin.qq.com/s/St2tgUJyNpYMROUX0uI03g)

![](https://files.mdnice.com/user/43254/79b0163c-0c57-4b10-8084-8f7a844a5f03.png)


这是一篇由中国医学科学院肿瘤医院刘芝华/焦宇辰团队、深圳湾实验室詹启敏/崔永萍团队联合上海序祯达生物科技有限公司（以下简称“序祯达生物”）在Cancer Cell上发表的关于食管鳞癌分子分型研究文章。研究基于多组学数据分析，将食管鳞癌分为四个分子亚型：细胞周期通路激活型（CCA）、NRF2通路激活型（NRFA）、免疫抑制型（IS）和免疫调节型（IM）。这是国际上首次基于多组学数据的食管鳞癌分类标准，并为每个亚型寻找了潜在的治疗靶标和/或诊断标志物。该项研究为未来ESCC的研究提供了宝贵的资源。


## 博文资讯

4、 [强化学习发现矩阵乘法算法，DeepMind再登Nature封面推出AlphaTensor](https://mp.weixin.qq.com/s/kCayZUk1MNZqE7j_l_bLOA)

![](https://files.mdnice.com/user/43254/acb33faf-9c95-42b7-bd68-417d1bb11fcb.png)


去年的一篇Nature 封面论文《Discovering faster matrix multiplication algorithms with reinforcement learning》。在该文中DeepMind 提出了 AlphaTensor，并表示它是第一个可用于为矩阵乘法等基本任务发现新颖、高效且可证明正确的算法的人工智能系统。简单来说，使用 AlphaTensor 能够发现新算法，并且有助于加深我们对矩阵乘法算法丰富性的理解。这项研究揭示了 50 年来在数学领域一个悬而未决的问题，即找到两个矩阵相乘最快方法。

5、[前向-前向神经网络训练算法](https://zhuanlan.zhihu.com/p/588588443?utm_medium=social&utm_oi=841811531518836736&utm_psn=1582142539959906304&utm_source=wechat_session "前向-前向神经网络训练算法")


![](https://files.mdnice.com/user/43254/9c1982c6-daee-400b-b986-598f8b317988.png)


在NeurIPS 2022 会议演讲中，Geoffrey Hinton 表示，「机器学习研究社区在意识到深度学习对计算机构建方式的影响上一直表现缓慢。」他认为，人工智能的机器学习形式将引发计算机系统的变革，这是一种将 AI「放入你的烤面包机」的新型软硬结合。

在这次演讲中，Hinton 花了大部分时间谈论一种新的神经网络方法，他称之为 Forward-Forward（FF）网络，它取代了几乎所有神经网络中使用的反向传播技术。Hinton 提出，通过去除反向传播，前向网络可能更合理地接近现实生活中在大脑中发生的情况。

- 论文链接：https://link.zhihu.com/?target=https%3A//www.cs.toronto.edu/~hinton/FFA13.pdf

6、[npj Precision Oncology｜Foundation Medicine 发表超大人群KRAS突变泛癌研究](https://mp.weixin.qq.com/s/M_AJDyNxM333oGm7em9PvQ)


![](https://files.mdnice.com/user/43254/46cbd97b-77a9-4823-939e-fb0e9b0700c6.png)


去年12月由Foundation Medicine发表在 npj Precision Oncology 的文章。在这项研究中，作者进行了一项全面的泛癌基因组分析，确定了24种癌症类型中KRAS突变的发生率，包括G12C和KRAS以外突变的分布。通过与TMB、PD-L1表达、互斥伴发和mutation signature等相关分析，评估了不同KRAS突变相关的基因组特征。此外通过 FMI 临床基因组数据库(CGDB)中收集到的临床生存信息，还评估了非小细胞肺癌(NSCLC)、结直肠癌(CRC)和胰腺癌(PDAC)队列中不同 KRAS 突变亚型的预后影响。

## 工具

7、[babeldown | 实现文档内容的自动翻译](https://github.com/ropensci-review-tools/babeldown/ "babeldown | 实现文档内容的自动翻译")

```R
babeldown::deepl_translate_markdown_string(
  "[So _incredibly_ **wonderful**](https://ropensci.org "So _incredibly_ **wonderful**")!",
  source_lang = "EN",
  target_lang = "ES"
)
#> [1] "[Así que *increíblemente* **maravilloso**](https://ropensci.org "1] "[Así que *increíblemente* **maravilloso**") ¡!"
```

- https://docs.ropensci.org/babeldown/articles/quarto.html

8、[WiggleTools：大规模并行处理基因组数据](https://github.com/Ensembl/WiggleTools "WiggleTools：大规模并行处理基因组数据")


![](https://files.mdnice.com/user/43254/1021472e-3953-4a1a-b50a-dcb4a5aaf652.png)


WiggleTools 软件包允许将基因组数据文件作为数值函数来处理，并配备了所有标准的函数分析运算符和衍生统计计算。

9、[Knowledge | 定制化内容的大语言模型工具](https://github.com/KnowledgeCanvas/knowledge "Knowledge | 定制化内容的大语言模型工具")


![](https://files.mdnice.com/user/43254/f655cfea-1ef5-418a-834a-5017feded7ea.png)


Knowledge是一个大型语言模型工具，根据个人输入并保存的所有网站、文档和文件内容进行动态对话，深入探索概念，加深理解。

- 工具教程：https://github.com/KnowledgeCanvas/knowledge/wiki/Getting-Started

## 资源

10、[Shiny for Python APP范例](https://shinylive.io/py/examples/ "Shiny for Python APP范例")


![](https://files.mdnice.com/user/43254/15a822e8-0248-42c9-b3e0-04f6041136ff.png)


Shiny可以基于R也可以基于Python，这是一个基于Python开发Shiny APP的范例，值得参考。


11、[ Stable Diffusion整合包v4_汉化](https://www.bilibili.com/video/BV1iM4y1y7oA/?spm_id_from=333.788.recommend_more_video.0&vd_source=3afc2da90da868f4f01d17b6a37ffeba " Stable Diffusion整合包v4_汉化")


![](https://files.mdnice.com/user/43254/a5a4215f-ba51-435f-9320-1d82545c41b0.png)


由UP主发布在bilibili上面的基于开源项目Stable Diffusion WebUI制作的整合包，需要的话可以去看看视频。

12、[七款网工在线画拓扑工具](https://mp.weixin.qq.com/s/M5IEsWRXt2ahicmPkSyX_g)

![](https://files.mdnice.com/user/43254/5cb9fc3b-4c7a-4dcc-addf-d3150a701313.png)


本资源推荐了7款在线的绘制拓扑图的工具：
 1. zen flowchart
 2. Excalidraw
 3. draw io
 4. xGraph
 5. processon
 6. 迅捷画图
 7. 坚果云绘图

## 历史上的本周

[生信爱好者周刊（第 60 期）：孟德尔诞辰 200 周年](https://mp.weixin.qq.com/s/itaXq3NqWT2W2vXq41Zp7A)

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

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://files.mdnice.com/user/38661/17812364-5134-43ba-92cf-0be6aff405e8.png)

（完）