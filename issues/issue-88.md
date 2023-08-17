---
date: 2023-08-17
comments: true
---

# 生信爱好者周刊（第 88 期）：Vim之父因病离世，一生写下Vim传奇

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo "「生信周刊讨论区（语雀）」") | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community "「生信讨论区（Gitter）」")

## 封面图


![](https://files.mdnice.com/user/37191/847a1833-9b65-4216-98a1-8a2c25495b65.jpg)

 - 图片来源：[pixabay](https://pixabay.com/zh/ "pixabay")

## 本周话题：[「Vim之父」因病离世，一生写下Vim传奇](https://mp.weixin.qq.com/s/FDEQG_WmeoM4rO9LoykTYw)




![](https://files.mdnice.com/user/37191/8f6a6dd6-56a0-4fbd-986f-20541afe5a17.png)



>8月3日，「Vim之父」Bram Moolenaar因病离开了所有人，年仅62岁，开发者社区的人们纷纷缅怀悼念。在Bram的一生中，他将近半的时间全部奉献给了Vim，为开源社区做出了巨大的贡献。与此同时，他还是一个慈善家，资助了乌干达儿童。


## 生信研究

1. [ Nature Methods | 新方法从单细胞多组学数据解析动态基因调控网络](https://mp.weixin.qq.com/s/zjqXUVse89GK_lwM3rU7HA)


![](https://files.mdnice.com/user/37191/fe3c9f36-37dd-482a-9a9b-09de46e09f49.png)


哈佛大学医学院研究人员开发了一种新工具**Dictys**，它可以整合分析单细胞转录组(scRNA-seq)和染色质开放性数据(scATAC-seq)，结合转录因子结合足迹和转录因子表达/调节活性分析，从单细胞多组学数据中解析动态基因调控网络。该工具在人造血系统等方面实现了发育连续过程基因调控网络的动态分析，并提高了时间/细胞状态分辨率以及feedback loop分析等能力。

- 工具链接：https://github.com/pinellolab/dictys

- 论文链接：https://www.nature.com/articles/s41592-023-01971-3


2. [ JAMA Oncol | 基于31基因的AI模型实现对结直肠癌-肝转移的精准分型](https://mp.weixin.qq.com/s/yEeddUwYoWiBtr8JByWIuA)


![](https://files.mdnice.com/user/37191/e4cd6264-a294-40be-ab46-fa5fba46cacf.png)


结直肠癌（CRC）的一个主要转移部位是肝脏，大约25%的CRC患者最终会发生肝转移，这部分患者往往生存率较差。来自美国芝加哥大学医学院的研究团队及合作者首次对一个新型的31基因神经网络分类器进行了临床验证，其可以准确预测CRC肝转移分子亚型。该神经网络分类器是基于切除的转移瘤的mRNA和miRNA的表达谱训练，并以96%的准确度预测了CRC的分子亚型（典型、免疫或基质亚型）。这篇文章也为转移分期和分类提供了一个新框架。

- 文章链接：https://jamanetwork.com/journals/jamaoncology/article-abstract/2807472



3. [ 同日9篇！人类生物分子图谱计划（HuBMAP）里程碑登Nature封面，肠道、肾脏和胎盘空间分辨细胞图谱发布](https://mp.weixin.qq.com/s/O4B3sS8VdwwK-XqQbIgdnA)


![](https://files.mdnice.com/user/37191/0773074b-a8c3-401b-98ed-3478adf8aa38.png)


 人类生物分子图谱计划（HuBMAP）是美国国立卫生研究院于2018年发起的一个项目，旨在利用单细胞技术，建立一个涵盖人体器官中各种生物分子（如转录、蛋白质和代谢物）的空间分布的综合图谱。近日，HuBMAP发表了最新研究成果，报道了**人类肠道、肾脏和胎盘空间分辨细胞图谱。**

- 论文链接：https://www.nature.com/immersive/d42859-023-00019-y/index.html


4. [Nature | 基于超1万例癌症样本分析，揭示染色体非整倍体如何驱动癌症进展](https://mp.weixin.qq.com/s/VuqwgDxnaOHpZji3uV33UQ)


![](https://files.mdnice.com/user/37191/46a005ae-4a36-4216-bc58-c0883c058f5a.png)


研究团队开发了一种名为BISCUT（Breakpoint identification of significant cancer undiscovered targets）的算法，通过研究端粒或着丝粒边界拷贝数事件的长度分布以确定受适应度优势或劣势影响的基因位点。研究人员将BISCUT应用于癌症基因组图谱（TCGA）中的超10,000例肿瘤，系统地量化了选择和机械偏差在驱动非整倍体方面的作用，对癌症内和癌症间染色体臂非整倍体模式的影响，并发现arm-SCNA的速率与其对细胞适应度的影响高度相关。

值得注意的是，研究团队对 Arm 水平的拷贝数变异进行了细分，除了覆盖整个 Arm 的变异，还包括：从端粒或着丝粒开始的SCNA断点位置（分别被称为tel-SCNA和cent -SCNA，统称partial-SCNA）。

另外，该论文通讯作者之前是著名拷贝数分析软件 GISTIC2 文章的共同通讯。

- 论文链接：https://www.nature.com/articles/s41586-023-06266-3

## 博文资讯


5. [“生物科学俱乐部”中的“生信规则”](https://mp.weixin.qq.com/s/Cq_pCPIAXwr3jP5wsI1Ndg)

<img width="849" alt="截屏2023-08-12 07 55 28" src="https://github.com/openbiox/weekly/assets/45822462/305f14e5-a72e-485f-9ec8-ac0431b25230">

本推文介绍了生物信息书籍Biostar Handbook中生物信息学的四条”规则“，并进行了解读。


6. [图解！决策树、随机森林、bagging、boosting、Adaboost、GBDT、XGBoost总结](https://mp.weixin.qq.com/s/S9tyTayZtEd2WexS6RJxkQ)


![](https://files.mdnice.com/user/37191/a305e34f-8dd3-4ada-941a-b3eefe5c4b34.png)


一篇以图片形式总结了常见的机器学习算法的文章，写的略显粗糙，可以翻翻。



7. [全新单细胞+分子标签测序试剂盒](https://mp.weixin.qq.com/s/USiLd0lKDer-Q1Q8ie92lg)


![](https://files.mdnice.com/user/37191/e7b4d388-0de5-4a93-a68b-b910817f5c17.png)


本文介绍了由Takara推出的这套单细胞测序试剂盒SSmRNA + UMIs，其具有以下优势特点：
  - 获得全长转录组信息
  - 添加UMI校正
  - 免费的数据分析流程


8. [Jupyter 中的生成式 AI](https://blog.jupyter.org/generative-ai-in-jupyter-3f7174824862 "Jupyter 中的生成式 AI")


![](https://files.mdnice.com/user/37191/79dbcab1-f015-480a-b326-27137f499fc5.png)



Jupyter AI为Jupyter笔记本带来了生成式人工智能，使用户能够解释和生成代码，修复错误，总结内容，询问有关本地文件的问题，并从自然语言提示生成整个笔记本。使用其强大的魔法命令和聊天界面，Jupyter AI将Jupyter与来自AI21, Anthropic, AWS, Cohere和OpenAI等提供商的大型语言模型(LLM)连接起来。我们使用LangChain来支持所有流行的llm和提供商，让您在新模型发布时访问它们。LangChain也会让Jupyter AI使用本地模型。用于JupyterLab 3的Jupyter AI版本1.0和用于JupyterLab 4的Jupyter AI 2.0现在都是免费的开源软件。

> 我只能说很强大，安装和使用都免费。喜欢用 Jupyter 的伙伴赶紧试试，向大家分享使用体验。

 - 文章链接：https://blog.jupyter.org/generative-ai-in-jupyter-3f7174824862
## 工具

9. [aplotExtra: 利用“aplot”生成复合图](https://github.com/YuLab-SMU/aplotExtra "aplotExtra: 利用“aplot”生成复合图")

许多复杂的图表实际上是由复合图表组成的。我们可以使用'ggplot2'生成子图，然后使用'aplot'将它们组合起来创建复合图表。通过在最终图表中添加、删除或修改子图，很容易自定义这些复杂的图表。这个软件包提供了一套实用工具，帮助用户创建子图和复杂图表。

 - 工具链接：https://github.com/YuLab-SMU/aplotExtra

10. [kitty: 跨平台GPU终端](https://github.com/kovidgoyal/kitty "kitty: 跨平台GPU终端")


![](https://files.mdnice.com/user/37191/0b626062-cead-4435-bd7b-1a1647ff7a5d.png)

Kitty是一个基于GPU的跨平台终端，其速度快，内置了丰富的功能。它的配置是一个简单的、可由人编辑的单个文件，以便易于复制。它不依赖于任何庞大而复杂的用户界面工具包，仅使用OpenGL进行渲染。最后，它的设计目标之一是易于扩展，以便未来可以相对轻松地添加新功能。

 - 工具链接：https://github.com/kovidgoyal/kitty


11. [ThemePark | 一款有意思的流行元素配色方案R包](https://github.com/MatthewBJane/theme_park/?anything "ThemePark | 一款有意思的流行元素配色方案R包")


![](https://files.mdnice.com/user/37191/3bfd2690-b798-4717-b7e3-05dd60da2ea6.png)


ThemePark是一个提供当下热门电影、游戏和电视剧等配色方案的R包，这些方案包含权力游戏、星球大战和塞尔达等。

 - 工具链接：https://github.com/MatthewBJane/theme_park/?anything

12. [webR4Shiny](https://github.com/RinteRface/webR4Shiny "webR4Shiny")


webR4Shiny可以在用户的Shiny包项目中设置与webR兼容的基础设施。该包基于George Stagg关于{webR}的工作，特别是用于在Netlify上部署Shiny应用程序的这个存储库。

 - 工具链接：https://github.com/RinteRface/webR4Shiny
## 资源


13. [《TypeScript 教程》发布了](https://mp.weixin.qq.com/s/POSNF8iMkb8Wc9WLOEjmhg)


![](https://files.mdnice.com/user/37191/a6e2966b-cfc3-4400-af8c-55fd5c2cc44c.png)



14. [Learn Makefiles](https://makefiletutorial.com/ "Learn Makefiles")


![](https://files.mdnice.com/user/37191/140252de-4636-4723-8305-3e1fa12b1711.png)


Makefile是一个文本文件，它告诉Make工具如何编译和链接一个由多个C或C++源文件和头文件组成的项目。编译是将源代码转换为可执行文件的过程，而构建是将多个文件编译成一个完整的程序的过程。Make是GNU提供的一个构建工具，它可以根据Makefile中的规则和命令，自动执行编译和构建的任务，从而节省程序员的时间和精力。要使用Make，我们需要学习如何编写Makefile，以及如何利用Makefile的各种特性和技巧。

这篇教程是一个很好的入门资源，它可以帮助你掌握Makefile的基本概念和用法，并避免一些常见的陷阱和错误。

- 教程链接：https://makefiletutorial.com/

本文对 Python 的核心基础知识进行了梳理。

15. [文章作图icon资源](https://mp.weixin.qq.com/s/TNsc4W0r0xYRInnxnwrZ7A)


![](https://files.mdnice.com/user/37191/377d44e0-ae0a-4451-94b1-175c0601ab0a.png)



这篇文章分享了比较常用的免费的icon资源，方便文章绘制示意图。

- https://www.iconfont.cn/
- https://healthicons.org/
- https://bioicons.com/
- https://erikflowers.github.io/weather-icons/
- https://www.smashingmagazine.com/2021/08/open-source-icons/
- https://thenounproject.com/
- https://www.phylopic.org/
- https://www.flaticon.com/
- https://reactome.org/icon-lib/
- https://smart.servier.com/
- https://www.svgrepo.com/
- http://www.gerdarntz.org/isotype.html
- https://fonts.google.com/icons

16. [图书下载：Statistics and Machine Learning in Python](https://pyoflife.com/download-statistics-and-machine-learning-in-python/ "图书下载：Statistics and Machine Learning in Python")


![](https://files.mdnice.com/user/37191/377f7492-2d71-4955-8cab-982b96dbc300.png)


在本书中，我们将回到数学领域，学习统计学以及如何基于数据集计算重要的数值。我们还将学习如何使用各种Python模块来获取所需的答案，并学习如何根据所学知识创建能够预测结果的函数。

 - 下载链接：https://pyoflife.com/download-statistics-and-machine-learning-in-python/

## 历史上的本周
- [第 48 期：人生不能只有一个支点](https://mp.weixin.qq.com/s/epnFf5crhS9rYku2wJRBSQ?scene=25#wechat_redirect)

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


![](https://files.mdnice.com/user/37191/484e56e7-6d4d-41a3-a70c-53e240bb2dcd.png)


（完）