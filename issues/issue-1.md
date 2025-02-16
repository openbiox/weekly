---
date: 2023-02-09
comments: true
---

# 生信爱好者周刊（第 1 期）：生信是什么

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

讨论区的帖子[《谁在招人？》](https://github.com/openbiox/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

## 开刊词

我发布该周刊的驱动因素有两个：一是受到阮一峰《科技爱好者周刊》的影响，我常常能在其发布的内容中找到新颖有趣或值得思考的内容；二是处理浏览器不断增加的标签列表的焦虑感。我时常通过浏览器收藏非常不错的资源、文章，其中很多没看就忘记了，但我累积的内容却越来越多。

我希望给自己做做减法，这个减法就是输出。将自己收纳的信息及时地处理并输出出去，一方面锻炼自己的脑子，另一方面也能够过滤出真正重要的知识，而这些知识是可查询和追溯的。

当然了，对于读者，我希望这本周刊能够带给你思考或是效率的提升。注意，并不是所有的内容都适合你，你需要找到自己觉得最重要的内容。

由于个人研究内容在肿瘤基因组，所以一些生信内容会偏向该方向。如果越来越多的朋友加入分享，这一倾向可以被纠正。

第一期，我们将聚焦于对初学者有帮助的主题和资源。

## 封面图

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101435483.jpg)

当生物遇见计算机。（[via](https://pranavathiyani.medium.com/what-is-bioinformatics-703170763999)）

## 本周话题：生信是什么

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101436673.png)

生信是什么？你是如何理解它的？

无论你是一个新手还是老手，想必都有自己的看法。这个问题没有标准答案，可能会一直没有答案。这是个你需要一直学习、一直寻求突破的事业，它让你痛并快乐着，让你舍不得离开座位，让你肚子一圈圈变大。来吧，亲爱的朋友们。

对生信，这里不会给出教科书式的定义。如果你想要畅聊自己的看法，欢迎在[GitHub讨论区](https://github.com/openbiox/weekly/issues/1)发表自己的意见。

从个人的经历来看，生信主要有3大块内容，或者说它基本是由3个学科交叉形成的新的科学。

- 生物学
- 统计学
- 计算机

这里生物学是根、统计学是内核、计算机是外核。3者通其2，便能立足该领域。

## 生信科技动态

1、[国际组学数据质量控制联盟第四期研究成果](https://www.nature.com/articles/s41587-021-00993-6)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101453017.png)

该项目由美国食品药品监督管理局（FDA）牵头，历时5年多，聚集了来自全球100多个单位的300多位科学家参与。通过建立和使用一系列基因组参考物质，国际组学数据质量控制联盟对众多新一代测序平台和生物信息学方法在体细胞和胚系突变、拷贝数变异、肿瘤靶向测序和液态活检、单细胞测序等多个应用场景的性能进行了系统研究。

2、[Pan-Cancer Analysis of Whole Genomes 2020 成果合集](https://www.nature.com/collections/afdejfafdb/)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101436309.jpg)

癌症是一种基因组疾病，由细胞获得关键癌症基因的体细胞突变引起。这些突变改变了调节细胞生长和与组织环境相互作用的途径。直到最近，对癌症基因组的研究都集中在蛋白质编码基因上，这些基因加起来只占基因组的1%。为了解决这个问题，ICGC/TCGA全基因组泛癌症分析(PCAWG)项目对超过2600个原发癌症及其38种不同肿瘤类型的匹配正常组织进行了全基因组测序和综合分析。这项研究揭示了大规模结构突变在癌症中所发挥的广泛作用，识别了之前未知的基因调控区域的癌症相关突变，推断了多种癌症类型的肿瘤进化，阐明了体细胞突变和转录组之间的相互作用，并研究了种系遗传变异在调节突变过程中的作用。该集合包括描述PCAWG联盟进行的核心分析集的论文，并展示了数据、工具和其他资源，对那些寻求进一步探索这个遗留数据集的人是有用的。

3、[Pan-Cancer Atlas 2018 成果合集](https://www.cell.com/pb-assets/consortium/pancanceratlas/pancani3/index.html)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101436280.jpg)

通过对33种最普遍的癌症形式的超过11000个肿瘤的分析，泛癌症图谱提供了一个独特的全面、深入和相互关联的理解，肿瘤如何、在哪里和为什么会在人类中出现。泛癌症地图集作为一个单一和统一的参考点，是在追求精准医疗的过程中开发新疗法的重要资源。

4、[TGCA pan-cancer analysis 2013 成果合集](https://www.nature.com/collections/ffebghgeba/)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101436704.png)

人体不同部位不同细胞类型的基因组改变会导致数百种不同形式的癌症，而这些改变导致具有不同生物学、病理学和治疗策略的肿瘤的方式正开始被描述。TCGA研究网络已经将数千个肿瘤基因组的DNA、染色质和RNA的畸变与匹配的正常细胞基因组进行了分类，并分析了它们的表观遗传和蛋白质后果。在这里，泛癌症倡议检查了在TCGA分析的前12种肿瘤类型中发现的基因组和细胞改变之间的异同。这种对癌症类型的首次观察提供了基因组学和生物信息学的新工具，以及在肿瘤的临床分类之外，根据肿瘤的分子病理学重新定位靶向治疗的前景。

## 文章

别人怎么看生信？

1、[What is Bioinformatics?](https://theconversation.com/explainer-what-is-bioinformatics-9911)（英文）

> 生物信息学支撑并使整个生命科学的研究成为可能。这包括从大量还原科学（基因组学、蛋白质组学和其他“组学”，基因活性调节、表观遗传学、蛋白质和RNA结构和功能、细胞组织）到比较、进化和系统生物学。尤其是后者，试图发现我们的身体是如何工作的。

2、[What is Bioinformatics?](https://pranavathiyani.medium.com/what-is-bioinformatics-703170763999)（英文）

> 测序和微阵列等高通量生物实验数据的爆炸式增长催生了生物信息学这门科学。生物信息学是一门类似于数据科学的解决生物学问题的交叉学科。

3、[What is Bioinformatics?](https://www.genomicseducation.hee.nhs.uk/education/core-concepts/what-is-bioinformatics/)（英文）

> 生物信息学是一门相对较新的、不断发展的学科，它结合了计算机科学和生物学的技能和技术，帮助我们更好地理解和解释生物数据。


## 工具

1、[Anaconda](https://anaconda.org/)：当前全球最流行的开源数据分析平台/环境。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101437668.png)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101437444.png)

> By data scientists, for data scientists

2、[Jupyter](https://jupyter.org/)：当前最流行的交互式数据分析笔记本（编辑器）（支持多语言）。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101437373.png)

3、[RStudio](https://www.rstudio.com/)：当前最流行的R语言编辑器。

![202109101445595](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101448492.png)

4、[VS Code](https://code.visualstudio.com/)：当前最流行的通用集成开发环境IDE。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101437033.png)

5、[GitHub desktop](https://desktop.github.com/)：最流行代码存储库GitHub的桌面版软件。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101437111.png)


## 资源

目前通用的生物信息学研究中，3大编程语言为：R、Python和Shell。Shell必学，其他两者选择其一即可。下面收集和分享适合初学者的各类资源。

1、[The Unix Workbench](https://seankross.com/the-unix-workbench/)（英文）

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101449838.png)



> 这本书是为那些刚接触编程和刚接触类似unix的操作系统（如macOS）和Linux发行版（如Ubuntu）的人准备的。本书中讨论的大多数技术都可以通过命令行接口访问。命令行界面一开始看起来很陌生，所以这本书试图在使用命令行和你通常使用鼠标和键盘时采取的动作之间画出相似之处。你还将学习如何用一种名为Bash的编程语言编写小块软件，它允许你将我们将要讨论的工具连接在一起。我希望在本书结束时，你能够像使用连接乐高积木一样使用不同的Unix工具。

2、[R for data science](https://r4ds.had.co.nz/)（英文）

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438172.png)

> 这是“R数据科学”的网站。这本书将教你如何使用R进行数据科学：你将学习如何将数据转换为R，使其成为最有用的结构，转换它，可视化它并建模它。在这本书中，你会发现数据科学的技能实践。就像化学家学习如何清洁试管和储存实验室一样，你也将学习如何清洁数据和绘图——以及其他许多事情。这些都是让数据科学发生的技能，在这里你将发现用R来做这些事情的最佳实践。你将学习如何使用图形语法、读写编程和可重复研究来节省时间。你还将学习如何管理认知资源，以便在争论、可视化和探索数据时促进发现。

3、[廖雪峰的Python教程](https://www.liaoxuefeng.com/wiki/1016959663602400)（中文）

学习Python必读必推荐。

4、[Introduction to Bioinformatics and Computational Biology](https://liulab-dfci.github.io/bioinfo-combio/)（英文）

> 这是哈佛大学STAT115/215 BIO/BST282的课程材料。本课程的所有YouTube视频都在2021年[STAT115播放列表](https://www.youtube.com/playlist?list=PLeB-Dlq-v6taAXK6ZCGfqImrNWJzFt3p3)下（视频我记得B站上也有，大家觉得有需要就去搜一下）。

主要作者是[Xiaole Shirley Liu](http://http//liulab.dfci.harvard.edu/)

5、[Computational Genomics with R](http://compgenomr.github.io/book/)（英文）

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438127.jpg)

> 这本书的目的是为基因组学提供数据分析的基础。我们根据每年开设的计算基因组学课程开发了这本书。我们总是有来自物理、生物、医学、数学、计算机科学或其他定量领域的跨学科听众。我们希望这本书是一个起点，为计算基因组学学生和进一步的数据分析在基因组学更具体的主题指南。这就是为什么我们试图涵盖从编程到基础基因组生物学的各种各样的主题。由于这是一个跨学科的领域，不同背景的人需要有不同的起点。生物学家可能跳过基本基因组生物学的部分，从R编程开始，而计算机科学家可能想从基因组生物学开始。同样，一个经验丰富的人在需要做某种类型的分析时，可能会想要参考这本书，但之前没有经验。

6、Bioinformatics Data Skills（英文）

【付费：出于版权问题我不会在公众平台分享PDF资源，请需要的读者打赏（至少2元）并留下邮箱和资源信息名，我会统一通过邮件发送。**一定要留邮箱**，当然单独打赏也是可以的。以后PDF等电子书的分享也采用相同的模式】

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438436.png)

8、[极客R：数据分析之道](https://shixiangwang.github.io/geek-r-tutorial/)（中文）：我之前写了两章介绍就停了的书。对初学者还是很有用的。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438722.png)

7、[Markdown 入门参考](http://xianbai.me/learn-md/index.html)（中文）

> Markdown 是一种轻量级标记语言，创始人为约翰·格鲁伯（John Gruber）。它允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的 XHTML（或者 HTML）文档”。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。

## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者 GitHub 仓库主页提供的支付宝/微信二维码打赏。

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）
