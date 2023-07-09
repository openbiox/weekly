# 生信爱好者周刊（第 83 期）：2022 Science年度十大科学突破

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图
![图片](https://mmbiz.qpic.cn/mmbiz_png/TxnZTCx6rVFq9jps6aFzhpUgv3ZsfChViaDfHUYLwecIudYZmJzCBnW8YbHfP7Of1L29mOfic6vPE7ib29Ntlnx4Q/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

## 本周话题：[2022 Science年度十大科学突破](https://mp.weixin.qq.com/s/I6kBfXwS24dDSG3le65zWg)
- https://github.com/openbiox/weekly/issues/1247

> 每一年，《科学》杂志的编辑团队都会评选出一项年度科学突破冠军以及九项年度科学突破入围奖。它们是一年里最重大的科学发现、科学进展和趋势。

@NiEntropy -2022年 Science推出的十大科学突破中，有一项让我这个生信爱好者很感兴趣——冻土古DNA序列揭示失落世界。这项突破展示了环境DNA在重建过去生态系统方面的巨大潜力，为生物信息学提供了新的数据来源和研究对象，揭示了地球历史上的生物多样性和演化过程，为生物信息学提供了新的知识和理解。另一项让我这个普通人受益匪浅的突破是——创造性人工智能的快速发展。它让生活充满了便利和乐趣，我可以生成各种我喜欢的图片、音乐、视频等。它也让学习更加高效和有意义，我可以利用创造性人工智能来辅助我学习和获取知识。

@ShixiangWang -看到「惊人的巨型细菌」，不得不感慨人类总是为自己的见识所束缚，自然界存在种种超脱人意料的可能。



## 生信研究
1、[ Nature Methods | Cue: 一个用于发现结构变异和基因分型的深度学习框架](https://mp.weixin.qq.com/s/v3reY_HijT51yOiNlztjDw)

![image](https://user-images.githubusercontent.com/75790226/251717921-cc22a40c-a8e0-4d7b-9c8a-52a16f4b0977.png)

来自美国布罗德研究所、威尔康奈尔医学院的研究团队在Nature Methods上发表了一种名为Cue的深度学习框架，用于从DNA测序数据中检测和基因分型结构变异（SV）。SV是一组大于50个碱基对的基因组改变，是人类基因组中遗传多样性和疾病的关键驱动因素。现有的SV检测器依赖于手工设计的特征和启发式方法来建模SV，无法扩展到SV的广泛多样性，也无法充分利用测序数据中可用的信息。Cue将比对转换为编码SV信息的图像，并使用堆叠沙漏卷积神经网络来预测每个图像中捕获的SV的类型、基因型和基因组位点。Cue在合成和真实的短读数据上检测多种类别的SV方面表现优于现有技术水平，并且可以轻松扩展到其他测序平台。

- 论文链接：https://doi.org/10.1038/s41592-023-01799-x





2、[NC | 蛋白质-蛋白质相互作用的层次图学习](https://mp.weixin.qq.com/s/3_qtelJ_DqHeJ2JzJuRblg)

![image](https://user-images.githubusercontent.com/13445428/251237008-3cf8d93d-32f8-48ea-9a32-776a95272440.png)

由香港科技大学、中国科学院大学、腾讯公司人工智能实验室共同发表在nature communications的文章。文章提出了一个双视图层次图学习模型HIGH-PPI，以预测蛋白质-蛋白质相互作用（PPI）并推断所涉及的分子细节。HIGH-PPI检查人类相互作用组的蛋白质外部和内部，以建立对PPI的强大机器理解。该模型在预测PPI方面表现出高精度和稳健性。此外，HIGH-PPI可以通过精确识别重要的结合和催化位点来解释PPI的作用模式。总体而言，HIGH-PPI是一个领域知识驱动和蛋白质相互作用预测研究的可解释框架。

- 论文链接：https://www.nature.com/articles/s41467-023-36736-1#citeas



3、[ NC| 深圳湾实验室孙坤课题组揭示游离DNA片段化模式的调控机理及其应用](https://mp.weixin.qq.com/s/zDFAYxn0s5Qv-EZbLmtzEQ)

![image](https://user-images.githubusercontent.com/75790226/251719455-b5c68f6e-2e46-4217-9136-24ce4d59b4c6.png)

近日，深圳湾实验室孙坤课题组在Nature Communications期刊发表了题为“DNA methylation analysis explores the molecular basis of plasma cell-free DNA fragmentation”的文章。该研究揭示了DNA甲基化是外周血中循环血浆游离DNA（cell-free DNA，cfDNA）的重要调控元件，并基于此原理开发了全新的泛癌种、跨平台癌症诊断标志物，深入探索了cfDNA片段化模式的分子机理以及临床转化价值。

- 论文链接：https://www.nature.com/articles/s41467-023-35959-6



4、[Nature Genetics︱预测免疫治疗反应性的新生物标志物](https://mp.weixin.qq.com/s/wGgxhY9PFTMJZdAgLO7R5g)

![image](https://user-images.githubusercontent.com/25057508/251331984-3d90326a-7737-4770-9491-011839af1ad5.png)

本文研究人员开发了一种算法——SOPRANO（蛋白质注释区域的选择），其可以计算任何目标基因组区域内部（ON target或ON-dN/dS）和外部（OFF target或OFF-dN/dS）的三核苷酸背景校正的dN/dS，允许在多个或单个个体之间进行队列和患者特异性的dN/dS比较。同时，本文的方法使用了由（1）单个HLA等位基因（即HLA-A0201）、（2）由6个HLA单倍型组成的原始HLA等位基因或（3）患者特定的6个HLA I类等位基因组成的靶免疫多肽组中的点突变（错义和/或截短单核苷酸变体）。基于此，研究人员在不同的背景中应用SOPRANO来量化免疫选择，并确定免疫逃逸的影响，分析了>10,000例原发肿瘤和356例ICI治疗的转移瘤，利用免疫dN/dS（即免疫多肽组中非同义突变与同义突变的比率）来测量队列和个体的免疫选择，成功使用dN/dS来区分免疫编辑肿瘤和免疫逃逸肿瘤、测量潜在的抗原性，并最终实现对治疗反应的预测，以此强调了考虑肿瘤进化动力学对未来个性化医学的重要性。

- 论文链接：https://doi.org/10.1038/s41588-023-01313-1

## 博文资讯
5、[生信学习入门常见错误可能的原因分类总结和求助指南](https://mp.weixin.qq.com/s/YMdatIVYgEITGchZW78Mcw)

![截屏2023-07-07 08 52 20](https://user-images.githubusercontent.com/45822462/251608844-2f2ea413-bee7-4314-a51b-0c9d36785923.png)

本文作者整理了入门生信时R或shell中可能遇到报错，并且分享了相应解决方案。

6、[单细胞上游数据处理](https://mp.weixin.qq.com/s/nbkVA5E0hYT-0DaqOwzSFg)

![image](https://user-images.githubusercontent.com/25057508/251332514-300349fe-5c6a-439c-820b-beeeaf994e39.png)

本文介绍单细胞处理的上游分析步骤和代码。





7、[eulerr| 优雅的可视化韦恩图](https://mp.weixin.qq.com/s/m_FCQgim-znsMeVg1n_nTw)

![image](https://user-images.githubusercontent.com/13445428/251243268-f94a2c05-5da3-4305-a016-e01f98ee27e8.png)

eulerr是一款能够生成面积比例欧拉图的R包，可以显示集合关系（交集、并集和不相交），并且不要求所有集合交互都存在（无论它们是否为空）。另外也可以尝试VennDiagram和ggvenn。

- 教程：https://cran.r-project.org/web/packages/eulerr/vignettes/

8、[PanCanSurvPlot |  一款解决泛肿瘤KM生存分析的Shiny网页工具](https://mp.weixin.qq.com/s/pZPPRnwADRENhFOl9QhFRg)

![image](https://user-images.githubusercontent.com/13445428/251245366-fec7fd37-2a55-422c-b339-2d10c07dacc6.png)

PanCanSurvPlot是一款以网页为基础的便捷肿瘤相关生存分析工具，能够提供给用户探查不同肿瘤、不同生存状态下转录组标志物的生存预测结果。推荐使用！

- 工具链接：https://smuonco.shinyapps.io/PanCanSurvPlot/



## 工具
9、[starship | 个性化命令行](https://github.com/starship/starship)

![image](https://user-images.githubusercontent.com/75790226/251721429-9d06b4d2-cd3a-4b33-bea6-f3d0d5835cd5.png)



Starship是一个命令行提示符，它可以在终端中显示有关系统和shell状态的信息。它旨在提供一个快速，可定制且易于使用的提示符，适用于各种不同的shell环境，例如Bash、Zsh、Fish等。它可以显示有关当前目录、Git分支、Docker容器、Node.js版本、Python虚拟环境等信息，并且可以通过配置文件进行自定义和扩展。Starship是一个跨平台的工具，可以在Windows、macOS和各种Linux发行版上使用。



10、[scverse ｜ 单细胞组学数据分析的基础工具](https://scverse.org/)

![image](https://user-images.githubusercontent.com/25057508/251332665-69faa1e4-7f7b-4e9b-a264-0d5187679b30.png)

得益于研究团队利用 Python 处理单细胞数据的不断深耕，创造了一系列工具，现在，它们组成了 Python 处理单细胞数据的生态 scverse，推动了 Python 在该领域的应用。





11、[Typst | 一款强大的语言的排版系统](https://typst.app/)

![image](https://user-images.githubusercontent.com/108639312/251936134-69fa0443-e79f-4ce7-ace6-e4de49bf9fb7.png)

Typst 是一种全新的基于标记语言的排版系统，它的设计目标是与 LaTeX 一样强大，但更加易于学习和使用。相较于 LaTeX，Typst 内置了用于处理最常见格式化任务的标记语言，同时为其他所有任务提供了灵活的功能。





12、[Truvari | 结构变异的比较、合并和注释工具包](https://github.com/ACEnglish/truvari)

![image](https://user-images.githubusercontent.com/45822462/251608909-520dfc91-2b6e-49d0-b5df-2632663f345e.png)

- 文献链接：https://doi.org/10.1186/s13059-022-02840-6



## 资源
13、[在Docker中使用R和Rstudio进行可重复性研究的教程](https://github.com/jsta/r-docker-tutorial)

![img](https://i0.wp.com/www.gis-blog.com/wp-content/uploads/2019/12/docker_r.jpg?resize=800%2C308&ssl=1)

本教程是针对R和RStudio使用者的Docker入门指南。教程首先介绍了Docker的基本概念以及其用途，然后详细介绍如何在可重复且可转移的项目中使用Docker。





14、[Single-cell best practices | 单细胞最佳实践](https://www.sc-best-practices.org/preamble.html)

![image](https://user-images.githubusercontent.com/108639312/251936353-cf588caf-151b-40e8-bc2e-21c1523ba397.png)

《Single-cell best practices》是一本详尽且定期更新的在线书籍，全书53个章节，其主要内容有单细胞数据的预处理、可视化、聚类、细胞亚群注释、染色质可及性、空间组学、蛋白质学、免疫组学等等。



## 历史上的本周

- [第43期：RNA-seq差异分析究竟应该用什么？](https://mp.weixin.qq.com/s/RmzbuRuKWcmodAK0ROnObQ)



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