---
date: 2024-09-08
comments: true
---

# 生信爱好者周刊（第 139 期）：震惊！基因泰克将关闭癌症免疫学研究部门，明星科学家将离职

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo "「生信周刊讨论区（语雀）」") | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community "「生信讨论区（Gitter）」")

## 封面图




## 本周话题：[震惊！基因泰克将关闭癌症免疫学研究部门，明星科学家将离职](https://mp.weixin.qq.com/s/TwMxcAG6r7jnwiUPzVnO7g)


![](https://files.mdnice.com/user/37191/16580c21-7220-4dca-8dc1-d4a4085ff7a9.png)


>2024年8月17日，星期六，上海阳光明媚，晴空万里。但药时代团队的心头却布满了乌云，为什么呢？因为Endpoints News、Fierce Biotech等多家知名外媒先后报道了一条关于基因泰克的爆炸性新闻，“基因泰克将关闭癌症免疫学研究部门，明星科学家将离职”。
>
>这令我们倍感震惊，不禁要问：
**到底发生了什么呢？这对全球癌症免疫学赛道会有怎样的影响呢？**

## 生信研究
1. [Nature Cancer | 张泽民团队通过单细胞整合分析揭示结直肠癌肿瘤微环境分型](https://mp.weixin.qq.com/s/V_xTRkm2C3KMrAaREX9rbw)


![](https://files.mdnice.com/user/37191/52890a00-ab4c-4ba2-9c90-25a7b13c13d1.png)


2024年8月15日，北京大学生物医学前沿创新中心（BIOPIC）张泽民课题组在Nature Cancer发表了题为“Integrative single-cell analysis of human colorectal cancer reveals patient stratification with distinct immune evasion mechanisms”的研究论文。该研究建立了包括健康、肠炎、肠道息肉、癌旁和肿瘤组织的单细胞图谱，描绘了肿瘤特异性的细胞亚型和转录组变化。基于肿瘤微环境的细胞组成，研究将结直肠癌病人分成6组，描绘了每组病人不同的肿瘤微环境特征及其对应的不同主导免疫逃逸机制。

- 论文链接：https://www.nature.com/articles/s43018-024-00807-z


2. [Genome Biol | 三代测序的结构变异（SV）检测流程综合评估](https://mp.weixin.qq.com/s/JFxafYrlv_7s79tOJGEHsg)

![](https://github.com/user-attachments/assets/ab68c51c-25bd-4c93-98ee-644fe0a31123)


第三代测序技术（TGS）能够产生长读数，有望更准确地检测SV。当前已开发出多种基于TGS的SV检测方法和工具，大多数都建立在SV检测的比对策略上，一个SV检测流程（pipeline）通常包括一个比对工具和一个调用器。目前有五种常用的长读取比对工具（包括LRA、minimap2、NGMLR、pbmm2和winnowmap）。与此同时，调用工具也在不断发展，例如cuteSV、cuteSV2、DeBreak、DELLY和SVision。由于SV的复杂性和TGS数据中的噪声，基于不同假设和模型的工具在SV检测中往往表现出不同的性能和相对较低的一致性，因此从TGS数据中准确检测出所有SV位点和基因型对大多数现有工具来说仍然是一个巨大的挑战。中山大学李淼新团队利用PacBio（CLR: Continuous Long Read, CCS: Circular Consensus Sequencing）和Nanopore（ONT）平台的模拟和真实数据，对53个SV检测流程在检测不同大小和类型的SV、断点偏差和不同测序深度的基因分型准确性方面的性能进行了综合评估。分析发现，将多个流程与相同的比对工具（如pbmm2或winnowmap）相结合可以显著提高性能。


- 论文链接：https://doi.org/10.1186/s13059-024-03324-5

3. [Cell | 肠道菌群拓扑评分可预测癌症免疫疗法疗效](https://mp.weixin.qq.com/s/JGeC2VBLi5Jebn85ieTufg)


![](https://files.mdnice.com/user/37191/35d6eb83-2a9d-4c71-a727-15b8a6008395.png)


近日，来自法国ClinicObiome的Laurence Zitvogel研究组在Cell上发表题为Custom scoring based on ecological topology of gut microbiota associated with cancer immunotherapy outcome 的文章，通过肠道菌群的丰度网络分析，建立了肠道菌群与肿瘤免疫疗法疗效之间的相关性。

作者的工作建立了基于粪便宏基因组测序的拓扑评分与黑色素瘤和结直肠癌患者的免疫治疗疗效的相关性。此外，本文报道的观察性队列共包括872例非小细胞肺癌、泌尿生殖系统癌和结直肠癌患者，也为免疫疗法响应与肠道菌群的相关性提供了资源。

- 论文链接：https://doi.org/10.1016/j.cell.2024.05.029

4. [Nature Methods|CellRank2:百万级单细胞分化轨迹分析工具](https://doi.org/10.1038/s41592-024-02303-9)


![](https://files.mdnice.com/user/37191/460b6a52-0c06-4213-ab54-f90cf4784d12.png)


单细胞RNA测序允许我们使用表达相似性或RNA速度对细胞状态动力学和命运决策进行建模，以重建状态变化轨迹；然而，轨迹推断不包含有价值的时间点信息或利用额外的模式，而解决这些不同数据视图的方法不能组合或无法缩放。在这里，我们提出了CellRank 2，这是一个多功能且可扩展的框架，用于以统一的方式使用多达数百万个细胞的多视图单细胞数据来研究细胞的命运。CellRank 2在人类造血和内皮发育中持续恢复跨数据模式的终端状态和命运概率。我们的框架还允许在实验时间点内和实验时间点之间结合过渡，这是我们用来恢复在咽内皮发育期间促进髓质胸腺上皮细胞形成的基因的特征。此外，我们能够从代谢标记数据中估计细胞特异性转录和降解率，我们将这些数据应用于肠道类器官系统，以描述分化轨迹并确定调控策略。

感谢`@OlafTobark42 `投稿。

- 论文链接：https://doi.org/10.1038/s41592-024-02303-9



## 博文资讯

5. [清华大学生命科学学院张强锋教授：AI 理解生命科学的海量数据，解析复杂调控网络](https://mp.weixin.qq.com/s/ASsfSkP2e6oC1bcGRkBPqw)


![](https://files.mdnice.com/user/37191/412570e3-4dff-41e7-bf1d-18f900f4139f.png)


清华大学生命科学学院、清华-北大生命科学联合中心研究员、博导张强锋教授在第六届北京智源大会的「AI for Science」论坛上以「当人工智能遇上生命科学」为题，分享了如何利用 AI 结合冷冻电镜实现蛋白质结构的解析。

「人工智能技术的进展，给生命科学带来了革命性的突破，能够让我们有机会理解生命科学的海量大数据、解析生命科学的复杂调控网络。」


6. [可视化工具SandDance](https://mp.weixin.qq.com/s/6fquAfz4Kq_KHVqnH9ijTg)

![](https://github.com/user-attachments/assets/79b0c42d-88b8-40e7-b891-207283c46c30)

SandDance是由微软研究院的可视化和交互式数据分析（VIDA）小组创建，通过提供了触控式的界面，实现使用者和3D信息图表进行互动，更加特别的是可以以不同的角度不同的方式呈现分析结果，新开源版本的SandDance已经被重新编写，实现了模块化和可扩展性，支持嵌入到自定义应用程序中，并与现代JavaScript工具链集成使用。除了具有更大的拓展性，支持更多的图表类型外，SandDance还可以作为Visual Studio代码和Azure Data Studio的扩展使用，并且已经作为Power BI自定义Visual Studio重新发布。


7. [For Sale! 英国“生信+多组学+SaaS”明星项目](https://mp.weixin.qq.com/s/-2ADGjiK6BOcpE3r4XZZpA)


![](https://files.mdnice.com/user/37191/1109027f-3ea1-45ef-9005-88aa753fcd66.png)


## 工具

8. [Github上一款打造完美日程管理工具：tui.calendar](https://mp.weixin.qq.com/s/RHRoasaUbv0GKGFWphhtfQ)

![](https://files.mdnice.com/user/37191/51137c8b-4c0b-40d8-999c-d9b3aa99cac8.png)

tui.calendar是一个功能强大的JavaScript日历插件，提供了丰富的功能和定制选项，可以轻松集成到任何网页中。无论是需要简单的日程管理功能，还是复杂的日程调度系统，tui.calendar都能满足用户的需求。

- 项目地址：https://github.com/nhn/tui.calendar

9. [Overleaf-Workshop 插件：VSCode 中联动 overLeaf 的高效 LaTeX 协同神器](https://mp.weixin.qq.com/s/Bvf4ouBDYuv_ZN-epuGbAg)



![](https://files.mdnice.com/user/37191/c0b8cd06-3ded-4754-8ad4-93b3a37bb8d2.png)


你是否厌倦了在Overleaf和VSCode之间来回切换，只为编辑和预览LaTeX文档？现在，有了Overleaf-Workshop插件，你可以直接在VSCode中无缝集成Overleaf/ShareLaTeX项目，享受实时编译预览和便捷的协作体验！

- 项目地址：https://github.com/iamhyc/Overleaf-Workshop

10. [Kener：极度轻量且漂亮自托管的状态页面](https://mp.weixin.qq.com/s/oIrgUrvTBBZ1g1bYEEZZTw)



![](https://files.mdnice.com/user/37191/9cef0838-34da-4603-9ca9-a93cf6a3e6ec.png)



在企业和开发者社区中，可靠地监控服务状态变得越来越重要。Kener应运而生，它是一个现代的自托管状态页面，使得服务状态监控和通知变得轻松而直观。

- 项目地址：https://github.com/rajnandan1/kener

## 资源

11. [哈佛大学的数据科学公开课](https://x.com/akshay_pachaar/status/1680555390960844800)


![](https://files.mdnice.com/user/37191/ddc00285-14ed-44bb-8675-5277dd7f7788.png)




12. [蓝绿系配色](https://mp.weixin.qq.com/s/3TE0KBczOlWWEDp5qtFB2A)

![](https://github.com/user-attachments/assets/4ec2d7c9-90fc-4781-a33c-4e3144e87f39)

文章展示了蓝绿系从配色到排版的例子和代码实现，确实看着很舒服。


## 历史上的本周
- 2023 [生信爱好者周刊（第 99 期）：发论文还是生孩子，女性在学术界会遭遇什么？](https://mp.weixin.qq.com/s/Hd0XsdZe7l733nAlyw6VMA)

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

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。


![](https://files.mdnice.com/user/37191/484e56e7-6d4d-41a3-a70c-53e240bb2dcd.png)


（完）