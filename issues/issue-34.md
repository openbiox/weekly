---
date: 2023-03-12
comments: true
---

# 生信爱好者周刊（第 34 期）：中国百万人群大队列，何去何从？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo) | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community)

## 封面图


![](https://files.mdnice.com/user/4331/24989391-e218-4a71-9611-e2c5a0cd8316.png)

[via](https://mp.weixin.qq.com/s/2V7vfj9X6z48Ad8DM2jZbQ)


## 本周话题：[中国百万人群大队列，何去何从？](https://mp.weixin.qq.com/s/2V7vfj9X6z48Ad8DM2jZbQ)

> 大队列研究，做好了对人类医学非常有益。世界上有几个突出的例子。但是外国的榜样有时在中国走样，甚至变成要大钱，但不做大事，或者不把大事做好。经费大增后的中国科学界，是否对得起科学、是否对得起中国纳税人，如何做包括队列在内的大项目，可能是试金石之一，检验能力、作风、良心。

你可能看到了很多已经结题的项目名称，但你可能从来不知道从哪里去获取以及是否容易获取：

![](https://files.mdnice.com/user/4331/5cd02846-9ef9-41e1-ad65-2d936b05f9cb.png)

现实是**采到的样本分散储藏在某处，极少测序，收集的基本数据去向不一，意味着课题组外的研究者或企业，如果想利用这些资源的话，会相当困难。**

中国缺乏类似TCGA的标志性大型项目！

## 生信研究

1、[Cell | 结合蛋白质组与外显子组技术构建转录因子互作图谱，揭示先心病的遗传决定因素](https://mp.weixin.qq.com/s/Pfeoiy3pwzuWXtUNwDzGCA)


![](https://files.mdnice.com/user/4331/127355be-dd23-4e6b-b5d5-c9713a022ea7.png)


研究团队通过整合蛋白质组学和人类遗传学方法，解析人类心脏祖细胞内源性GATA4和TBX5的蛋白质相互作用体，以识别和优先检测潜在的心脏疾病基因、CHD相关变异体，揭示了心脏基因调控的各方面功能。

2、[Cell | 泛癌研究揭示不同肿瘤类型的免疫特征图谱](https://zhuanlan.zhihu.com/p/473794440?utm_source=wechat_session&utm_medium=social&utm_oi=841811531518836736)


![](https://files.mdnice.com/user/4331/481c5964-4cac-497d-a26b-0c93f2c2c91a.png)

为了能从不同类型的肿瘤中寻找到主要的免疫系统原型，UCSF免疫分析联盟（UCSF Immunoprofiler Initiative）共收取了跨越12个不同类型肿瘤共计364份新鲜肿瘤组织的外科样本，快速消化成单细胞悬液并通过多参数流式细胞仪进行免疫分型。此外，作者还借助单细胞转录组测序技术（scRNA-seq）获取了这些外科标本的细胞组成和转录组学信息。通过对T细胞和单核吞噬细胞亚群的更精细的分类和定义，作者从3个粗略的细胞特征（T细胞特征、髓样细胞特征和非免疫的基质细胞特征）开始，通过不断的渐进分析，最终确定了10个主要免疫原型的稳定视图。

3、[Genome Biology综述 | 如何为临床诊断提供准确可靠的结构变异解析？](https://mp.weixin.qq.com/s/g9aelcLEgITRU81eH1uZvg)


![](https://files.mdnice.com/user/4331/830f434f-656f-4780-a708-0d060f068e6e.png)


文章分别总结了三个方面展望应用染色体SV进行临床诊断。分别是：1.建立标准参考材料；2.选择最优的测序策略；3.选择获取最佳的SV识别信号的方案。


## 博文资讯

1、[rstudio::conf(2022) Conference Schedule](https://www.rstudio.com/blog/rstudio-2022-conf-schedule/)

rstudio发布年度会议安排表。注册网址：<https://www.rstudio.com/conference/>。没钱的只能吃瓜～

![](https://files.mdnice.com/user/4331/fe37e429-ea09-47d1-a514-6e50eb13a744.png)

2、[gghalves包介绍](https://mp.weixin.qq.com/s/cnhucGCgHvOjXsWETkE3mg)


![](https://files.mdnice.com/user/4331/bf6a0e3e-0d68-4ce1-bc04-3c7109c3969d.png)


3、[T细胞耗竭](https://github.com/ShixiangWang/weekly/issues/476)


![](https://files.mdnice.com/user/4331/f11d6dbb-4391-4b79-8328-0983a561f107.png)


慢性感染和癌症病人，T细胞受到抗原持续刺激，细胞记忆不能有效地发育分化，T细胞变得精疲力竭，称之为T细胞耗竭（Tex）。

Tex细胞在功能上有别于Teff和Tmem，其特点是效应功能丧失，抑制性受体(IRS)表达增高且持续，表观遗传和转录谱改变，代谢方式改变。

T细胞衰竭是癌症病人免疫功能障碍主要因素之一。


## 工具

1、[Transformers - 为 Jax、PyTorch 和 TensorFlow 打造的先进的自然语言处理](https://github.com/huggingface/transformers/blob/main/README_zh-hans.md)


![](https://files.mdnice.com/user/4331/0439f1bc-3c8f-45bd-bb75-e7c4bd99b466.png)


2、[scDVA - 一个基于R Shiny的工具，用于单细胞RNA-seq数据可视化和分析](https://github.com/liziyie/scDVA)


![](https://files.mdnice.com/user/4331/6ba44d19-9cd6-4e5e-8d0c-f5be63d6c8e9.png)


![](https://files.mdnice.com/user/4331/37b1dc66-1df4-49ad-880a-50c2c1db5123.png)



3、[Jupyter笔记本和nteract的Go内核](https://github.com/gopherdata/gophernotes)


![](https://files.mdnice.com/user/4331/aafc65f7-e465-41b1-a880-cd425fb9fea3.png)


![](https://files.mdnice.com/user/4331/70401a1f-d2d5-4569-b8e6-244a90b65db1.png)

4、[beautifyR - RStudio插件用于格式化Rmarkdown表](https://github.com/mwip/beautifyR)


![](https://files.mdnice.com/user/4331/14b1b9a2-7c36-432c-9ced-11bfe9b5e8f2.png)

## 资源

1、[深度学习的综述的综述](https://mp.weixin.qq.com/s/oNdz1-JR7Kdw9C_NKAXg2Q)

对想要了解深度学习脉络的读者可能有帮助。

2、[Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)

一堆展示GitHub Profile的工具。让GitHub主页成为你的简历。


![](https://files.mdnice.com/user/4331/60b3fe10-a5a8-419a-a132-438b613a1ab5.png)



## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648291334186-bd3390be-c83c-4396-aabd-ca39f588c15d.png)

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

