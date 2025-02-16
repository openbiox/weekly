---
date: 2023-12-16
comments: true
---

# 生信爱好者周刊（第 104 期）：百度文心一言和GPT的差距有多大？
这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/5208/2629bb04-bd80-4896-9096-dc1686072118.png)




## 本周话题：[百度文心一言和GPT的差距有多大？](https://www.zhihu.com/question/597449020/answer/3324062749 "百度文心一言和GPT的差距有多大？")

> 文心一言和ChatGPT都是基于深度学习技术的自然语言处理模型，有各自的优势和使用场景，无法简单地比较 ChatGPT 和文心一言哪一个功能更强大，它们各自具有优势和局限性，需要根据具体需求进行选择。





## 生信研究
1、[Cell|黄海所、华大等机构发表迄今最大动物基因组参考序列](https://mp.weixin.qq.com/s/j3qxZnmvs7CLqqkHU2jizw)


![](https://files.mdnice.com/user/5208/f6b5be0b-e59b-4c17-a030-248ac99f1ea3.png)

> 2023年3月2日，由中国水产科学研究院黄海水产研究所、青岛华大基因研究所、德国阿尔弗雷德.魏格纳研究所、澳大利亚联邦科学与工业研究组织等机构组建的国际研究团队，完成了迄今为止最大动物基因组参考序列--南极磷虾基因组组装，并揭示了南极磷虾适应极端环境和群体历史演化的分子基础。相关研究成果于国际顶级学术期刊《细胞》在线发表。


- 论文链接：https://doi.org/10.1016/j.cell.2023.02.005


2、[Nature Communications | 人类肿瘤全基因组范围内增强子元件-目标基因映射调控图谱及其作用机制](https://mp.weixin.qq.com/s/LEKi-MsHz8EHaR_OYnhMjg)


![](https://files.mdnice.com/user/5208/9cf71454-e0c0-461a-ad58-a0621a7c5452.png)

> 武汉大学公共卫生学院缪小平和田剑波教授采用Activity-by-Contact (ABC) 模型，即候选调控元件对目标基因表达的定量影响应该取决于它作为增强子的活性（Activity），加权于它与目标基因启动子的染色质接触频率（Contact）；而一个候选调控元件对目标基因表达的相对贡献值取决于该元件的定量影响除以目标基因所在区域内所有候选调控元件的总定量影响，在全基因组范围内绘制增强子-目标基因映射图谱。该研究在全基因组范围内系统绘制了目前为止人类肿瘤最全的增强子调控元件-目标基因遗传调控映射图谱，为全面解析癌症的遗传复杂病因和易感新机制提供了新的理论线索和分析框架，发现的功能遗传标志物可为肿瘤高危人群识别和个体化精准防治和提供有效工具，具有潜在的早期筛查和临床应用转化价值。

- 论文链接: https://www.nature.com/articles/s41467-023-41690-z

3、[Nucleic Acids Research | 全面预测表观基因组、染色质组织和转录组的通用框架](https://mp.weixin.qq.com/s/ZIHGS0GDz1mLFNRYiekRnA)



![](https://files.mdnice.com/user/5208/aa3c10a4-c33d-4a03-bcc4-485d0be0454d.png)

> 本研究提出了EPCOT框架，该框架能够细胞特异性地预测多种基因组学特征，并且能够在不同预测任务之间共享通用表示。通过使用染色质可及性数据作为输入，EPCOT能够为新的细胞类型提供有意义的预测。此外，EPCOT还能够识别转录因子序列结合模式、分析细胞特异性转录因子对增强子活性的影响，从而提供生物学洞察。

- 论文链接：https://academic.oup.com/nar/article/51/12/5931/7177889


## 博文资讯

4、[一行命令完成 Counts 到 CPM、FPKM、TPM、UQ、CUF、TMM 、CTF 的转换](https://mp.weixin.qq.com/s/P9t3QFrtOQo1tW3MQxmOhg)

![](https://files.mdnice.com/user/5208/3e7d2ddd-01b8-4836-94a6-e89f3e022b9e.png)

> 本文介绍了通过Python实现RNAseq中Counts 到 CPM、FPKM、TPM、UQ、CUF、TMM 、CTF 的转换工具RNAnorm和执行代码。

- 工具链接：https://github.com/genialis/RNAnorm

5、[“科学探索奖”之初](https://mp.weixin.qq.com/s/wlXpuL31wNe8Zd9R02fOPg)


![](https://files.mdnice.com/user/5208/b6617a60-aa42-4386-a5a9-dc96f7e9f3ec.png)
>支持45岁以下青年科学家的“科学探索奖”成为我国单一企业与科学家发起支持科学最大的民间科学奖项。它与之前2015年多个企业家和多个科学家发起联合成立的表彰我国科学家突出的终身科学成就的“未来科学大奖”、之后2022年开始的支持55岁以下科学家的“新基石研究员项目”，鳞次栉比，形成我国科学界一以贯之的标杆。
它们不仅确立我国科学卓越的标准，而且提倡探索自然的趣味、坚持公正的文化，让重要（S）、原创（C）、优雅（E）在我国科学界逐渐成为我国科学界的追求。


6、[图神经网络在科学领域的应用](https://mp.weixin.qq.com/s/5v_Ny7jGiPifI_Tgon4toQ)

![](https://files.mdnice.com/user/5208/2c802fe1-d391-4af8-8861-69a10a9c1d0b.png)
> 如今机器学习模型的可解释性已经引起人们的广泛关注，而图机器学习作为机器学习领域的重要组成部分，其可解释性更值得人们的深入研究。GNN for Science 将科学知识融入机器学习领域，从另一方面体现了机器学习的可解释性，也可以对人们如何提高模型可解释性有所启发。
本文介绍的是黄文炳老师讲解的 GNN for Science 报告，主要内容包括：

- Science、GNN 背景介绍
- GNN for Science 相关研究
- 最新进展——欧式等变图神经网络
- 总结

7、[余光创-ggtree: 系统发育数据集成与可视化](https://mp.weixin.qq.com/s/7b6sPiKbLZ7ZsixhOySjqg)



![](https://files.mdnice.com/user/5208/fb18fef4-d291-49fc-a505-e0179ac599e7.png)

> Y叔基于ggtree包对系统发育数据集成和可视化讲解，感兴趣可以听下


8、[人类细胞的内部长什么样？](https://mp.weixin.qq.com/s/U-P3skq-EX4i5Dlzt0KzwA)


![](https://files.mdnice.com/user/5208/d1b94bd5-d4aa-4ff7-b886-04f7de85654e.png)

> 在所有细胞研究中，有一个看似简单而基础，却被证明相当难以量化和回答的问题，那就是，我们的细胞是如何组织它们的内部结构的？今日，科学家首次提出了一种新方法来研究这个问题。艾伦细胞科学研究所的团队通过使用数十万张高分辨率图像，对人类细胞的内部组织进行了统计。通过这项研究，科学家捕捉到了大量有关细胞形状变化的细节，这些形态变化即使是在相同条件下生长的有着相同基因的细胞也会出现。论文已发表在《自然》杂志上。


## 工具

9、[Reminders：一个漂亮的开源 Linux 应用，可帮助你完成工作 | Linux 中国](https://mp.weixin.qq.com/s/A0NVBGPZrRBky8J3KfZqcQ)

![](https://files.mdnice.com/user/5208/32a42830-32e6-44a7-8b75-b08f5f1afabd.png)

> “Reminders” 应用可以成为你的小帮手，提醒你未完成的工作。



10、[boxly包制作交互箱线图](https://github.com/Merck/boxly "boxly包制作交互箱线图")

![](https://files.mdnice.com/user/5208/e0ec6b80-e09a-4e4f-9b9b-c48f277e8b64.png)
> boxly 包可为临床试验分析和报告创建交互式箱形图。
- Github链接：https://github.com/Merck/boxly


11、[ggflowchart | ggplot 绘制流程图](https://github.com/nrennie/ggflowchart "ggflowchart | ggplot 绘制流程图")

![](https://files.mdnice.com/user/5208/e76aa674-f267-433c-bf96-964e72bc2e84.png)
```
data <- tibble::tibble(from = c("A", "A", "A", "B", "C", "F"),
                       to = c("B", "C", "D", "E", "F", "G"))

ggflowchart(data)
```

![](https://files.mdnice.com/user/5208/f80c1fed-21ff-4653-b0eb-8535d3693fb4.png)




## 资源
12、[2023ASCO丨肺癌，靶向免疫治疗最新进展汇总](https://mp.weixin.qq.com/s/9OZFOJzLWx0loSK-1rCZRA)


![](https://files.mdnice.com/user/5208/8dcae82a-cc4f-47e6-b30c-ed6de97d6f5a.png)

> 本文概要：非小细胞肺癌的靶向治疗和免疫治疗。

13、[图解机器学习特征工程](https://mp.weixin.qq.com/s/eP3JOqYzXPYo0GKsN5_PMQ)

![](https://files.mdnice.com/user/5208/e84ec851-d06d-4160-83e7-971274a975d7.png)
> 本文（ 约16000字，建议阅读20+分钟）对机器学习中数据预处理和特征工程的实战应用细节做一个全面的解读。


## 历史上的本周
- 第64期：[“讨好型人格”：越是乞求，越是被推开](https://mp.weixin.qq.com/s/PIIu3rDK3oKNpK0AF4z0SQ)


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

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

