---
date: 2024-07-27
comments: true
---
# 生信爱好者周刊（第 133 期）：年轻人的魄力

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![image](https://github.com/user-attachments/assets/fc06723e-6957-4cf9-989b-8e238dca060d)
[早期的中文键盘](https://spectrum.ieee.org/chinese-keyboard)

## 本周话题：年轻人的魄力

>我真的没想到，第一次投稿就中了。这篇论文被录用以后，在张老师的鼓励下，我又给当时的第三届全国青年计算机学术会议投稿，又录用了。
我今天回想起来，那些看起来很了不起的目标，试一试，也许没那么难。
所以我觉得，年轻人还是要有年轻人的魄力，不要听人家这个建议那个建议，敢想敢干最重要。

@kongjianyang：这段文字来自雷军以《成长》为主题的2023年演讲，可见成功如雷总也是从人生一个又一个小目标成长起来的，我们年轻人一定要有做成事的魄力。

## 生信研究

1.[Science子刊｜癌症和游离DNA中的全基因组重复图谱](https://mp.weixin.qq.com/s/3QACnnvojdkKJx7iLgOHdw)
约翰霍普金斯大学医学院的研究团队开发了一种名为ARTEMIS的新方法，可以在全基因组范围内识别和分析重复序列。这一突破性技术能够检测癌症组织和游离DNA中重复元件的变化，为癌症的早期诊断和监测提供了新的途径。研究发现，癌症中的重复序列景观发生了广泛改变，包括许多此前未知的变化；这些变化反映了癌症基因组中的结构、拷贝数和局部重复改变。更重要的是，这些变化可以在血液中的游离DNA中检测到，为无创癌症诊断开辟了新的可能性。
![image](https://github.com/user-attachments/assets/85b2d79a-5ff5-40bc-88a7-c630aa5a1c27)
> 全文链接：https://www.science.org/doi/10.1126/scitranslmed.adj9283

2.[Nat Methods | 中山大学贺雄雷团队提出一种量化祖细胞的统计方法，揭示了早期细胞命运的承诺](https://mp.weixin.qq.com/s/eMRqG2MYNi1u-X6QNpbZEw)
这篇文章介绍了中山大学贺雄雷团队在Nature Methods上发表的一项重要研究成果。他们开发了一种名为靶向聚结分析(TarCA)的创新统计方法，用于量化生物体中任何组织或细胞群体的祖细胞数量。这一方法突破了传统方法依赖特异性标记基因的限制，通过分析细胞系统发育树来实现祖细胞的量化。TarCA的优势在于其多功能性和稳定性，能够适用于各种复杂生物体的细胞系统发育分析。重要的是，这一方法还能用于识别胚胎发育过程中的关键基因，揭示早期细胞命运的决定。
![image](https://github.com/user-attachments/assets/8ec1452b-2dd6-4865-936e-f515960df38a)
> 全文链接：https://www.nature.com/articles/s41592-024-02189-7

3、[NEJM | 基于深度家系外显子测序的无创产前筛查技术（DES-NIPT） 实现胎儿特异性致病变异的精准检测](https://mp.weixin.qq.com/s/fLV-8SckJC1p8VFjadGoqA)

![](https://mmbiz.qpic.cn/sz_mmbiz_jpg/DMKW2dzPflIyjBqXhfu0MxI5Qr0uGIyYXyq7AicNl8IABcn6xp5CDtmG4KhlQAQcRqA1ibCodFM3KB37e5ibbhUFQ/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

这篇文章主要介绍了产前遗传诊断的重要性和最新进展。传统的产前家系外显子组测序虽然有诊断优势，但由于其侵入性和局限性，无法诊断更多的单基因疾病。无创胎儿检测（NIPT）技术的出现为产前筛查带来了革命性进步，但目前主要局限于染色体疾病的检测。文章重点介绍了丹麦研究团队开发的基于深度家系外显子组测序的无创产前筛查（DES-NIPT）方法。这种新方法具有以下特点：
- 全面性：可高灵敏度检测胎儿单核苷酸变异、小片段插入和缺失、大拷贝数变异以及染色体非整倍体。
- 非侵入性：通过分析母体血液样本中的cfDNA实现。
- 高精度：利用超深度、错误校正和家系外显子组测序技术，能够精确检测胎儿De Novo变异。

这项研究成果发表在《新英格兰医学杂志》上，为产前遗传诊断领域带来了新的突破，有望提高先天性遗传疾病的早期诊断率。

## 博文资讯

4.[详解XGBoost 2.0重大更新！](https://mp.weixin.qq.com/s/EpG9S3g0ALtWHemB7VlmqA)
这篇文章深入解析了XGBoost 2.0版本的重大更新：文章首先回顾了决策树、随机森林和梯度提升决策树的基本原理，为理解XGBoost的创新奠定了基础；随后，文章详细介绍了XGBoost的独特特性，如高效的计算、灵活的缺失值处理和正则化等。XGBoost 2.0的新功能，如多目标树、设备参数优化、新的默认树方法等，都得到了清晰的解释。
![image](https://github.com/user-attachments/assets/36b3776d-dccd-4bc2-b3d9-3b914766f895)
> 官方文档：https://github.com/dmlc/xgboost/releases

5、[使用 docker init](https://mp.weixin.qq.com/s/NQos_PaHdWPISh22WubXlQ)

![](https://github.com/user-attachments/assets/a9c465db-16aa-4f52-ac6e-67a13e60b3c9)


Docker 开发人员结合了生成式人工智能，创建了一个 CLI 实用工具 — docker init。docker init 是一个命令行应用程序，可帮助初始化项目中的 Docker 资源。它根据项目的要求创建 Dockerfiles、docker-compose 文件和 .dockerignore 文件。这简化了为项目配置 Docker 的过程，节省时间并降低复杂性。

6、[rlang 包 20 个操作技巧](https://mp.weixin.qq.com/s/sWBifP0Lqnv4CoSxPxHFrQ)

<img width="671" alt="image" src="https://github.com/user-attachments/assets/e3f57144-7acf-4130-a151-7a9dae358eb8">


rlang包提供了深入的函数式编程工具和语言抽象能力，让复杂的编程任务变得更加简洁和直观。然而，对于初学者来说，R语言的高级特性可能会显得有些难以接近。本文分享rlang包的20个实用技巧。

## 工具

7、[Noodle - 一款提升学习效率的开源工具](https://mp.weixin.qq.com/s/AZMYg36IQM7dUiXhoPhVPw)

![](https://mmbiz.qpic.cn/mmbiz_jpg/Xbg0KxKumFquoVbRhfGAewia9oiccXWf8OrJR78J1Q1xbx64Eqs32v45np50UiaibIOFIMq6I4VTaIJYcO5FJ6eumw/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

Noodle是一款开源的学习效率工具，其核心理念是将学习过程分解为独立任务并进行可视化管理。主要功能包括:

- 任务管理：创建、设置优先级和截止日期
- 时间管理：基于番茄工作法的计时器
- 学习进度追踪：记录完成任务和学习时间，生成报告
- 跨平台支持：兼容多种操作系统和Web
- 开源特性：允许用户查看和修改代码

Noodle的优势在于简洁易用、功能强大、免费开源，以及良好的跨平台支持。它旨在帮助学生重新思考学习方式，提高学习效率，有望成为学生学习生活中的必备工具。


8、[Xorbits，一个超强的 python 库](https://mp.weixin.qq.com/s/Lrh1jq4O0njLvxZFrCOhXA)

![](https://mmbiz.qpic.cn/mmbiz_gif/ibPqnScajrbEEHhzM1cyjjptTsHG8XzGCsQeoTQCJUXbpBh4iaia2zGun2wrrLPZIkic5eQibKjicPEJP7p2nM2633CA/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1)

Xorbits 是一个开源计算框架，可以轻松扩展数据科学和机器学习工作负载，从数据预处理到调整、训练和模型服务。其具有熟悉的 Python API，支持各种库，包括 pandas、NumPy、PyTorch、XGBoost 等。感兴趣的小伙伴可以进行详细阅读。

- 链接：https://github.com/xorbitsai/xorbits

9、[RNAseqQC｜给你的数据来个全面的 QC 检查](https://mp.weixin.qq.com/s/QZllBsSLME9uaGdYmYpeFQ)

![](https://github.com/user-attachments/assets/0ce61970-ef16-4bab-961c-a0dda6768fa2)

## 资源

10、[Miniforge：特定于conda-forge 的最小安装程序](https://github.com/conda-forge/miniforge#mambaforge)

![](https://opengraph.githubassets.com/4044c2aeac75665a4fe9644ca149a72d1b0bf8e958782aa97c179bf54ed586e5/conda-forge/miniforge)

Miniforge是基于conda-forge的Conda和Mamba的最小安装程序。Miniforge 包含Conda及其依赖项，它是一个更快的Conda替代品。此发行版都旨在简化在各种平台上安装Conda和Mamba的过程。它们为用户提供了一种便捷的方式来设置 Python 环境和管理包。

11、[动手实战人工智能 AI By Doing](https://aibydoing.com/intro)

![](https://cdn.jsdelivr.net/gh/huhuhang/cdn@master/images/aibydoing-thumbnail.png)

一本很不错的人工智能教程。通过动手实战人工智能，作者希望从监督学习开始，带入读者入门机器学习和深度学习。教程剖析和推导每一个基础算法的原理，将数学过程写出来，同时基于 Python 代码对公式进行实现，做到公式和代码的一一对应。


12、[Single Cell Sequencing Analysis](https://zhilongjia.github.io/scRNA/)

![](https://zhilongjia.github.io/scRNA/figure/%E8%AF%BE%E7%A8%8B%E5%86%85%E5%AE%B9%E7%9B%AE%E5%BD%95.png)

一本很好的单细胞分析的教程，值得翻阅和作为参考书。

## 历史上的本周

[生信爱好者周刊（第 93 期）：来自妈妈的Y染色体](https://mp.weixin.qq.com/s/RbT9bpXoyl3BhKyrYPrDyw)

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

![](https://files.mdnice.com/user/38661/17812364-5134-43ba-92cf-0be6aff405e8.png)

（完）

