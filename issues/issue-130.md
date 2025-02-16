---
date: 2024-07-07
comments: true
---
# 生信爱好者周刊（第 130 期）：走出还原论，拥抱复杂性

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/34023/8b8d419a-110f-471f-9562-3d2f2ff7de4b.png)


来源：Cell
## 本周话题：[走出还原论，拥抱复杂性](https://mp.weixin.qq.com/s/6yM1c55URiW8LY3xmNXgPA)
>还原论（reductionism）:将肿瘤的复杂性分解为基本的生物学单元，再从这些基本单元中重建对肿瘤复杂性的理解;
>整体论（holism）:强调将肿瘤视为一个整体，研究其内部的相互作用和联系。
>癌症作为一种全身性疾病的复杂性，包括肿瘤的发生和发展、肿瘤微环境和免疫宏观环境、衰老、代谢和肥胖、癌症恶病质、昼夜节律、神经系统相互作用、肿瘤相关的血栓形成和微生物组。

@NiEntropy：作为一个科研民工，每天测肿瘤细胞系的各种指标，来评估预测对肿瘤治疗的价值。就像作者说的我们沉浸在自己的研究领域，将肿瘤细胞从体内的复杂环境中转移到体外简单的培养环境中捕捉肿瘤生长，死亡，迁移，免疫杀伤，分子表达的有无，细胞间结合等观测指标。但是肿瘤是复杂的，通过体外筛选研究的这些成本低的idea，大多数早就被前人想到并且已经做过了，同时也相应开发了很多靶向治疗策略。如何超越前人？拥抱复杂性是一个不错的选择，比如从细胞水平的观测，提升的动物个体水平，可以观测的指标就会变的更多，并且更接近应用。科研人可以试着写写小说，有些想法没有足够的财力根本做不了，把这种难以实现的烧钱的不切实际的，但是理论可行的idea写成小说，传递下去。


## 生信研究
1、[National Science Review | 免疫与肿瘤互作驱动的食管鳞癌空间定向进化](https://mp.weixin.qq.com/s/oyTS0XgwI3KqkFCRTsnPEQ)

![](https://files.mdnice.com/user/34023/2a3a5b93-b482-4aad-903a-be0d733c218a.png)

在全球范围内食管癌的发病率与死亡率均排在前列，世界上50%以上的食管癌发生在我国，其中约90%的病理类型为鳞状细胞癌（esophageal squamous cell carcinoma，ESCC）。食管鳞癌在基因组变异和肿瘤微环境等方面均具有广泛的肿瘤异质性。而造成食管鳞癌异质性的原因目前还不清楚。全面解析肿瘤异质性的特征以及其形成机制有助于指导食管鳞癌药物开发以及临床治疗。该研究基于多组学技术系统刻画了ESCC的空间异质性图谱，基于环境（饮酒）-微环境（免疫）-空间克隆进化（肿瘤）三者之间的交互作用，提出了肿瘤空间定向进化的新模式，同时鉴定到了一个新的食管鳞癌相关基因PREX2，为阐明食管鳞癌的发病机制提供了新的见解。

- 论文链接：https://academic.oup.com/nsr/advance-article/doi/10.1093/nsr/nwae150/7656974?searchresult=1

2、[Science｜5万代大肠杆菌，探究突变适应性效应的变化规律](https://mp.weixin.qq.com/s/vVFgtcqRSDosRxYwIgei8w)

![](https://files.mdnice.com/user/34023/2967cdcf-5172-4d1d-be88-417970b5282b.png)

这项研究通过长期细菌演化实验，量化突变对适应性的影响，并观察这些影响如何随着时间的推移而变化。研究人员利用跨越50,000代演化的大肠杆菌品系，分析了每个基因中插入突变的适应性效应。
研究发现，有害突变的比例变化不大，而有益突变的比例急剧下降，接近指数分布；个体基因的必要性和有害效应常常同时发生变化，这些变化只能部分地用结构变异来解释；尽管有益突变的特征和效应大小迅速变化，但由于功能丧失突变的重要性，许多选择目标仍然是可预测的。这些结果揭示了突变对适应性的影响是动态的，但在统计上是可预测的，对理解生物演化过程具有重要意义。
- 论文链接：https://pubmed.ncbi.nlm.nih.gov/38271521/

3、[Nature | 从原肠胚到出生的小鼠产前发育的单细胞图谱](https://mp.weixin.qq.com/s/gH5yVlP8MUxOkI0XF7nr1A)

![](https://files.mdnice.com/user/34023/4f96a21c-62c6-4b6f-980c-921d8e4e907b.png)

这篇文章介绍了小鼠从原肠胚到出生的单细胞时间推移图谱。研究团队通过优化的单细胞组合索引技术，分析了83个胚胎的1240万个细胞核的转录状态，覆盖了从胚胎第8天到出生的整个发育过程。提供了哺乳动物从单细胞受精卵到出生的全景视图，为理解哺乳动物发育提供了宝贵的数据和分析框架。

- 论文链接：https://pubmed.ncbi.nlm.nih.gov/38355799/

## 博文资讯

4、[描述进化树的若干基本概念](https://mp.weixin.qq.com/s/YmA8LMyW1Xdx-cLJDN2aYg)


![](https://files.mdnice.com/user/34023/10daa868-b818-4c32-9673-11b56acbb327.png)

值得初学者作初步了解和学习。

5、[RPython | 好看的火山图](https://mp.weixin.qq.com/s/TN-yuIAYTZW0HxFSlniFbw)

![](https://files.mdnice.com/user/34023/ffb009b1-bf7c-40c6-a87e-b468574984c1.png)

火山图是转录组数据分析中最为常见的图片，推文提供了一个好看的火山图绘制模板。

6、[人类参考基因组38版与19版的区别](https://mp.weixin.qq.com/s/5Pve36EQ0IkIcVhJQsUuGQ)

![](https://files.mdnice.com/user/34023/2e20c32b-8f12-43d3-983f-2e417b1f3f9a.png)

- **序列改进**：GRCh38纠正了8000个碱基对的错误，填补了空白，并增加了着丝粒序列。
- **多样性增加**：GRCh38包含261条替代等位基因序列，丰富了基因组的多样性。
- **准确性提升**：GRCh38在检测结构变异方面更准确，假阳性率更低。
- **外显子组扩展**：GRCh38的外显子组大小增加了26.90%，提高了基因组注释的全面性。


## 工具
7、[scMetabolism | 单细胞代谢分析R包](https://github.com/wu-yc/scMetabolism "scMetabolism | 单细胞代谢分析R包")


![](https://files.mdnice.com/user/34023/333ec2b6-a1da-49de-9b0f-d6cefd9d18b9.png)


- 论文链接：https://pubmed.ncbi.nlm.nih.gov/34417225/

8、[留痕｜提取微信记录](https://github.com/LC044/WeChatMsg "留痕｜提取微信记录")

![](https://files.mdnice.com/user/34023/ceaca453-d746-4a71-b753-cac27e802bee.png)

提取微信聊天记录，将其导出成HTML、Word、Excel文档永久保存，对聊天记录进行分析生成年度聊天报告，用聊天数据训练专属于个人的AI聊天助手。

- 可视化报告 demo：https://memotrace.cn/demo.html

9、[Dandelion |  10X Chromium 5' 数据的单细胞 BCR/TCR V(D)J-seq 分析包](https://github.com/zktuong/dandelion "Dandelion |  10X Chromium 5' 数据的单细胞 BCR/TCR V(D)J-seq 分析包")


![](https://files.mdnice.com/user/34023/b16ca670-c50b-4bc3-989f-b9d03325755a.png)


10、[uwot](https://github.com/jlmelville/uwot?tab=readme-ov-file "uwot")

![](https://files.mdnice.com/user/34023/bfdefbf7-a1b6-4027-9a70-a7cd1fb9f93b.png)

原始 UMAP 算法在 R 中的重新实现，并且包括监督学习和度量学习扩展。
## 资源
11、 [ISLR-python](https://github.com/JWarmenhoven/ISLR-python?tab=readme-ov-file "ISLR-python")

![](https://files.mdnice.com/user/34023/b8e416d0-4eae-4c68-88b7-ce6161058af2.png)


该项目包含 James、Witten、Hastie、Tibshirani (2013) 所著《R 应用统计学习简介》一书第一版中精选表格、图形和 LAB 部分的 Python 代码。主题包括线性回归、分类、重采样方法、线性模型选择、基于树的方法、支持向量机和无监督学习。

## 历史上的本周
- 第 88 期：[视频学习胜过读书吗](https://mp.weixin.qq.com/s/oGzJ4i9QxEM5GbBhNgsl6w)

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