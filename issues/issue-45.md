---
comments: true
---

# 生信爱好者周刊（第 45 期）：读博还是择业？

这里记录每周值得分享的生信相关内容，周日发布。
本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。
[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo) | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community)


## 封面图


![](https://files.mdnice.com/user/34023/f242aaa9-5e22-4505-98d9-761170206134.jpeg)



## 本周话题：[读博还是择业？](https://mp.weixin.qq.com/s/_P59GQ2mPMIgq24gE1V9nA)
>  本周话题来自清华教授张焕晨（计算机专业），你真的适合读博吗？
>  9月，又到了校招的季节，身边的同学们也都开始关注校招信息，投简历了。是升学？还是就业？

@NiEntropy - 升学还是就业？我的话优先选择升学，计划申请生物信息学方向的博士（干湿结合/干实验均可）。2020级生物与医药专业（肿瘤药理方向），课题也都还在进行中。之前一直在做横向，今年上半年刚开始做自己的纵向课题（自己通过生信分析找的靶点）。目前还没有联系到博导，求推荐！

如果升学失败，就去工作，比起做实验，我更喜欢敲代码。目标：生信工程师
![](https://files.mdnice.com/user/34023/bd8ae2f3-2336-4c48-93a7-69fdc9861b33.png)

## 生信研究
1、[Science | 癌细胞在放疗后自毁DNA求生](https://mp.weixin.qq.com/s/ZtYfn8aPz7UqE7C1ZnW-TQ)

![](https://user-images.githubusercontent.com/25057508/190862459-e5df4441-1de4-49b7-9594-78ffb8dbe85b.png#crop=0&crop=0&crop=1&crop=1&id=XJhOy&originHeight=465&originWidth=1080&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

在临床中，有许多肿瘤对放疗不敏感。因此，“狡猾的”肿瘤细胞必定在进入DNA合成期（S）之后，进入分裂期（M）之前（即G2期），找到了救命的办法。丹麦哥本哈根大学Claus S. Sørensen教授团队研究发现，肿瘤细胞在DNA被放射线破坏之后，会招募一种核酸酶（CAD）到DNA损伤处，主动切断自身特定位点的DNA，阻止复制分裂的进行，使得肿瘤细胞停滞在G2期（DNA合成后期），为修复放疗导致的DNA损伤赢得宝贵时间。

- 论文链接：https://www.science.org/doi/10.1126/science.abi6378

2、[STAR Protocols | 给初学者进行长读测序基因组组装、分析结构变异的入门指南](https://www.sciencedirect.com/science/article/pii/S2666166722003860)

![](https://files.mdnice.com/user/34023/23b4cfe6-5088-4079-a006-8dda8a072d96.png)


本文详细介绍了初学者如何对长读测序技术产生的结果进行基因组组织、结构变异分析和基因注释。

- 论文链接：https://www.sciencedirect.com/science/article/pii/S2666166722003860

3、[Science｜深度学习对抗原序列的通用编码指导免疫治疗](https://mp.weixin.qq.com/s/Y74z7WbXuurUXRnEEcPfMA)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202209142028116.png#crop=0&crop=0&crop=1&crop=1&id=Ptq40&originHeight=322&originWidth=774&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

近日，在Science顶刊上，Achar等人通过机器人平台与机器学习相结合，对T细胞活化进行实验测量和理论建模，研究广泛的功能性T细胞对不同抗原刺激反应的数据来解决这个问题。使用机器学习，作者构建了一个简化的地图，可以将6种不同的抗原依赖性免疫反应的类别分开。了解这种抗原编码可以帮忙指导免疫治疗，包括工程化嵌合抗原受体（CAR)-T细胞和识别疫苗抗原。

- 论文链接：https://www.science.org/doi/10.1126/science.abl5311




## 博文资讯
4、[合著者间高效交流的十个简单规则](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010185)

 ![](https://files.mdnice.com/user/34023/23c9a130-659f-46b2-98ee-47a3c64283bc.png)



随着21世纪全球化的不断拓展，跨区域的合作交流越来越频繁。现如今在科研领域，一个科研项目可能涉及到多个国家、地区的科研工作者的协作。如何使交流更加顺畅有效，进而协调彼此间的工作变成为急需解决的问题。本文根据上述问题提出了十点建议，以供参考。

- 链接：https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010185

5、[人人都能看懂的EM算法推导](https://mp.weixin.qq.com/s/_tCMU3LR9jKoQMybf0sUZA)

![](https://user-images.githubusercontent.com/25057508/190862317-34b06767-db30-4424-bc61-8aa77025701d.png#crop=0&crop=0&crop=1&crop=1&id=EvTZb&originHeight=881&originWidth=777&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

EM算法是机器学习/优化的核心算法之一，本文系统地介绍了其由来、原理，并通过案例进行解读。

6、[如何检测和预防过拟合（英文）](https://analyticsindiamag.com/how-to-detect-and-prevent-overfitting-in-a-model/)

![](https://files.mdnice.com/user/34023/05fd4dd5-d8f3-4b4e-aa54-d92f873a77b3.png)


本文介绍过拟合的概念，如何进行判断以及预防过拟合的一些策略。

> 过拟合是指模型与训练数据集完美拟合时的概念。虽然这听起来很合适，但事实恰恰相反。在过拟合中，模型对不可见数据的表现要差得多。当一个模型完美地适合训练数据集，但在新的测试数据集上表现不佳时，它可以被认为是“过拟合”。另一方面，当一个模型被训练的时间不足以确定训练数据中有意义的模式时，就会发生欠拟合。过拟合和欠拟合都不能应用于大量新鲜和未见的数据集。


![](https://user-images.githubusercontent.com/25057508/190862830-73a1dce0-a01c-46d6-9159-21c728b20da3.png#crop=0&crop=0&crop=1&crop=1&id=tF9br&originHeight=516&originWidth=1248&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

7、[人物 | 徐鹰：AI生命科学的30年快意人生](https://mp.weixin.qq.com/s/j2p1lDsLDm_XeUZB6CCxew)

![](https://files.mdnice.com/user/34023/1ec29fb8-c51a-4fbd-ad64-fa1fdbce8218.png)
（徐鹰与父亲合照）

非常有意思的一篇文章，读一读可以了解生物信息学很多事情的来龙去脉，感受不同人对于人生与成就的理解和实践。
## 工具
8、[Rldeogram | 绘制全基因组数据图谱](https://github.com/TickingClock1992/RIdeogram)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202209150848093.png#crop=0&crop=0&crop=1&crop=1&id=FhcL0&originHeight=813&originWidth=922&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

RIdeogram 包用于绘制 SVG（可缩放矢量图形）图形，以可视化和映射染色体带上的全基因组数据。

- Github：https://github.com/TickingClock1992/RIdeogram
- Usage：https://cran.r-project.org/web/packages/RIdeogram/vignettes/RIdeogram.html

9、[R包 | plotbb图形语法介绍](https://yulab-smu.top/pkgdocs/plotbb.html)
![](https://files.mdnice.com/user/34023/6cc71db1-8185-4723-8cb8-7b5b57c6b6a1.png)

本文介绍了plotbb的基本语法，例如美学映射、几何布局等。

10、[forestploter | 轻松绘制发表级别的森林图](https://github.com/adayim/forestploter)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202209150854778.png#crop=0&crop=0&crop=1&crop=1&id=rlZfy&originHeight=687&originWidth=826&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

**forestploter**的目标是更加轻松便捷的制作出发表级别森林图。与制作森林图的R包相比，其提供了一些额外的显示。该数据集将用作森林图的基本布局，列表绘制置信区间的宽度可以用列的字符串长度来控制。可以使用空间来控制这一点。图中的元素放在行和列中，将图形视为表。

- Github：https://github.com/adayim/forestploter

11、[R包｜cosmosR](https://github.com/saezlab/cosmosR)

![](https://user-images.githubusercontent.com/38637596/190838188-bc2b319f-cb02-4a55-b76b-f16bceb86a96.png#crop=0&crop=0&crop=1&crop=1&id=dqYaA&originHeight=905&originWidth=2128&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

cosmosR包含蛋白质组学、转录组学和代谢组学数据集等多组学集成分析方法。cosmosR基于信号通路、代谢网络和基因调控的广泛先验知识，利用计算方法估计转录因子和激酶的活性，以及网络水平的因果推理。可以为跨多个组学数据集的实验观测提供机制解释。

- Github：https://github.com/saezlab/cosmosR

12、[BeeWare ](https://docs.beeware.org/en/latest/)

![](https://user-images.githubusercontent.com/75790226/190890668-24f795ae-5a8b-4420-a0b9-0c0405ba2801.png#crop=0&crop=0&crop=1&crop=1&id=AQ2Jh&originHeight=256&originWidth=256&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

BeeWare 包含一套工具和库，它们彼此间协同工作，以帮助使用者编写跨平台的本机 GUI Python 应用程序。

- 链接：https://docs.beeware.org/en/latest/

## 资源
13、[ProjecTILs | 单细胞投影](https://github.com/carmonalab/ProjecTILs)

![](https://user-images.githubusercontent.com/75790226/190890899-91c03d5c-ab3a-4095-8b8c-89801ac971e4.png#crop=0&crop=0&crop=1&crop=1&id=sDpeL&originHeight=312&originWidth=270&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
ProjecTILs是一种将scRNA-seq数据投影到参考单细胞图谱中的计算方法，并使其能够在稳定的注释坐标系中直接比较。
与其他方法相比，ProjecTILs不仅可以在不改变数据结构的情况下准确地将新的scRNA-seq数据嵌入到参考文献中，还可以发现以前未知的细胞状态，这些细胞状态“偏离”了参考。同时它也能准确地预测细胞扰动的影响，并识别在不同条件和组织下改变的基因程序。

- 链接：https://github.com/carmonalab/ProjecTILs

14、[Scissor | 整合bulk+单细胞RNA测序鉴定表型相关细胞亚群的R包](https://github.com/sunduanchen/Scissor)

![](https://user-images.githubusercontent.com/45822462/190653276-43d4b721-5f5f-419f-9cd3-e7408a87b35c.jpg#crop=0&crop=0&crop=1&crop=1&id=HW5II&originHeight=2065&originWidth=1886&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

去年发表在Nature Biotechnology上的Scissor算法，可利用大量单细胞数据和表型信息识别与疾病高度相关的细胞亚群，从一个新的角度来探索和解释了单细胞数据。小伙伴们有试过该工具最终效果如何？

- 链接：https://sunduanchen.github.io/Scissor/vignettes/Scissor_Tutorial.html

15、[study-is-wonderful](https://github.com/xioacd99/study-is-wonderful)

![](https://user-images.githubusercontent.com/38637596/190838379-798ff5a6-b84d-493b-8d94-b8bd1466a79f.png#crop=0&crop=0&crop=1&crop=1&height=754&id=o87do&originHeight=1508&originWidth=2546&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=&width=1273)

收集了一些比较好的课程资源，主要面向汉语人群。

- 链接：https://github.com/xioacd99/study-is-wonderful

16、[一个独特的简历生成器](https://github.com/AmruthPillai/Reactive-Resume)

![](https://user-images.githubusercontent.com/38637596/190838464-59eb7919-4ecf-4f86-8b7d-881fe568f29e.png#crop=0&crop=0&crop=1&crop=1&height=554&id=JNv0S&originHeight=1108&originWidth=3360&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=&width=1680)

该工具可通过各种配置，让创建、更新、共享简历的过程变得更加简单便捷，并且免费开源，支持中文！你可以一次性创作多份简历，并为每个简历生成特定链接，导出生成 PDF 文件，随时随地进行分享。另外，它还支持对简历外观进行灵活定制，颜色、主题、布局任意变动。暗黑模式与明亮模式，快速切换。所有的内容与外观变动，均所见即所得，无需等待与加载更新，整个过程极为流畅。

-  链接：https://mp.weixin.qq.com/s/DdH46AsgKF0HUgvaAvWztQ

## 历史上的本周

- 2021：[第 5 期：相关非因果](https://mp.weixin.qq.com/s/Jtb5zPlCSE7uc8onBGTlhw)
## 贡献者（GitHub ID）
「Openbiox 生信周刊」运维小队：

- @ShixiangWang
- @kkjtmac
- @NiEntropy
- @He-Kai-fly
- @JnanZhang
- @Tomcxf
- @wangdepin
## 订阅
这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。
微信搜索“优雅R”或者扫描二维码，即可订阅。
![](https://cdn.nlark.com/yuque/0/2022/png/2626379/1663487227743-514de66e-6232-4ea6-a81a-a27a5bab7110.png#clientId=ue027453f-4bb5-4&crop=0&crop=0&crop=1&crop=1&from=paste&id=ud125f811&originHeight=258&originWidth=258&originalType=url&ratio=1&rotation=0&showTitle=false&status=done&style=none&taskId=u3ed671bb-3a08-4920-82e3-5ff7c894944&title=)
（完）
