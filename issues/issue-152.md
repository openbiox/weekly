---

date: 2024-12-22

comments: true
---
# 生信爱好者周刊（第152期）：2024 Science年度十大科学突破


这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源[（GitHub: openbiox/weekly）](https://github.com/openbiox/weekly)，欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![](https://files.mdnice.com/user/80107/3597c30a-f411-44ea-9d0b-55fe72931cae.jpg)



## 本周话题：[ 2024 Science年度十大科学突破](https://mp.weixin.qq.com/s/5W04bXueWIb_VNO9BJDCnQ)

这篇文章是对“2024 Science年度十大科学突破”的详细报道，主要概述了《科学》杂志评选出的本年度十大科学突破，包括长效HIV预防针剂lenacapavir作为暴露前预防（PrEP）的重要进展，其显著降低了HIV感染风险并展现出对抗其他病毒性疾病的潜力；嵌合抗原受体T细胞（CAR-T）疗法在自身免疫疾病治疗方面的新突破，为狼疮、硬皮病等疾病患者带来希望；詹姆斯·韦伯空间望远镜（JWST）揭示的宇宙早期星系的形成与演化机制；基于RNA干扰（RNAi）的杀虫剂在害虫控制领域的创新应用；硝基体作为真核生物固氮细胞器的发现对进化论的补充；地幔波动对大陆轮廓形成及地质活动影响的新理论；SpaceX“星舰”火箭的成功着陆及其对未来太空探索成本降低的意义；以及其他在遗传学研究、固氮细胞器发现、地幔波动研究等领域的重大进展。这些突破共同展示了2024年在科学领域的广泛进步和深远影响。


                      

## 生信研究

1. [Nat Commun | AlphaFold2新方法高通量预测蛋白质构象分布，准确率超80%
](https://mp.weixin.qq.com/s/v2sVYO8MLa8osVoUMuF11A)

![](https://files.mdnice.com/user/80107/09a0f523-66b6-4ea1-b51b-c1d37ac7d6ce.png)

这篇文章是关于“AlphaFold 2新方法高通量预测蛋白质构象分布”的研究报告摘要，主要讲述了美国布朗大学的研究团队在Nature Communications上发表的一项研究，该研究提出了一种创新的AlphaFold 2（AF2）使用方法，通过亚采样多序列比对预测蛋白质构象分布，准确率超过80%。

- 论文链接： https://doi.org/10.1038/s41467-024-47504-0


2. [ Science |纳米孔测序揭示人类端粒长度与生俱来，且具有染色体特异性和个体间保守性
](https://mp.weixin.qq.com/s/tZ5jwBYpYbrLP25Us1q1lg)



![](https://files.mdnice.com/user/80107/9043fe39-b6fa-4a81-8ded-87f6855cbe35.png)


文章介绍了一种基于纳米孔测序技术的端粒分析方法——Telomere Profiling，可以在单核苷酸分辨率下测量细胞中每个端粒的长度。该方法具有低成本、高度准确性及优异的可重复性。

- 文章链接：https://www.science.org/doi/10.1126/science.ado0431



3. [ Nature | 多器官多组学多时间点解析耐力运动后的分子变化
](https://mp.weixin.qq.com/s/Bs7lW34VfVJ3AVWvImkwkA)


![](https://files.mdnice.com/user/80107/d8e1ad2e-ac0d-4e8e-a450-f22ea53f1517.png)

文章使用雌雄大鼠模型，从多器官、多组学、多时间点解析耐力运动后的分子变化，并总结分析了其关联生物学通路的组织、性别差异。

- 论文链接：https://www.nature.com/articles/s41586-023-06877-w

4. [ Science丨解析迄今最完整小鼠基因组图谱
](https://mp.weixin.qq.com/s/a5R3a-KbWmAvANKwDZbopg)



![](https://files.mdnice.com/user/80107/08d83b32-0eac-445f-9607-d74ffa05801a.png)


文章综合了众多三代基因测序技术，进行了基因测序和组装，获得了长度为2.77 Gbp（表示十亿个碱基对）的完整的高质量小鼠参考基因组序列，填补了约7.7%的基因组空白。

- 文章链接：https://www.science.org/doi/10.1126/science.adq8191




## 博文资讯

5. [ excluderanges
](https://dozmorovlab.github.io/excluderanges/articles/excluderanges.html)


![](https://files.mdnice.com/user/80107/879d580c-1b60-42bd-b949-542e40048324.png)

excluderanges是一个用于处理和检索问题基因组区域（problematic genomic regions）的R工具包，适用于人类、小鼠和一些模式生物。它提供问题基因组区域的坐标信息，这些区域在基因组数据分析时应避免使用。统一了多个实验室生成的不同排除集（exclusion sets）的检索。

6. [ 撰写研究计划
](https://www.science.org/content/article/writing-research-plan)


![](https://files.mdnice.com/user/80107/18532396-20f3-4179-a5b5-5052ffffd4cb.jpg)


这篇文章是关于如何撰写研究计划的指南，主要介绍了撰写研究计划的重要性、步骤、技巧以及注意事项，旨在帮助研究人员更好地规划和准备研究项目。


7. [如何清除Docker缓存并释放系统空间
](https://depot.dev/blog/docker-clear-cache)



![](https://files.mdnice.com/user/80107/7d29044f-4989-4f11-821c-62c0d3509cd6.png)


这是关于篇文章是如何清除Docker缓存和释放系统空间的指南，主要介绍了Docker中占用磁盘空间的不同构建缓存项和如何逐个或全部清除它们，以及在持续集成(CI)环境中管理Docker构建缓存的方法。



## 工具
8、[OpenWDL (The Workflow Description Language (WDL))](https://openwdl.org/)


![](https://files.mdnice.com/user/80107/09429262-0904-45e6-9ee1-5a4f06f64df7.png)

工作流描述语言（WDL）是一种开放标准，用于用人类可读和可写的语法描述数据处理工作流。WDL使得定义分析任务、将它们在工作流中连接起来以及并行执行变得简单直接。该语言力求对所有类型的用户都易于访问和理解，包括程序员、分析师和生产系统操作员。该语言允许使用常见的模式，如散列收集和条件执行，以简单的方式表达。WDL旨在具有可移植性，并提供多种实现方式，可在各种环境中运行，包括高性能计算系统和云平台。

9、[MuSiC | 多样本单细胞去卷积](https://github.com/xuranw/MuSiC)


![](https://files.mdnice.com/user/80107/f6bb1e4e-e7b3-466c-b0e3-c72526a7cdce.png)


MuSiC的原始版本是一种去卷积方法，该方法利用跨样本scRNA-seq来估计bulk RNA-seq数据中的细胞类型比例。

MuSiC2是一种迭代算法，旨在通过使用scRNA-seq数据作为参考，在大量RNA-seq数据生成自具有多个临床条件（其中至少有一个条件与scRNA-seq参考不同）的样本时，提高细胞类型去卷积。

10、[Yew | 用于创建可靠和高效的Web应用程序的Rust/Wasm框架](https://github.com/yewstack/yew)


![](https://files.mdnice.com/user/80107/82afe438-dcf7-40a6-ba6a-0b27405935d3.png)

## 资源
11、[在线数据库周刊（11.11-11.17）](https://mp.weixin.qq.com/s/iLWSqLj26xjZ8Aa92GnSQQ)

![](https://files.mdnice.com/user/80107/c7794194-eac1-44fa-b327-bb9cab262436.png)
这篇文章主要介绍了医学科学研究过程中常用的网络数据库，包括各种专注于转录本、表观遗传基因编辑、药物预测、基因siRNA效能等方面的数据库资源。


## 贡献者（GitHub ID）
「Openbiox 生信周刊」运维小队：

- @ShixiangWang（王诗翔）
- @kkjtmac（阚科佳）
- @NiEntropy（赵启祥）
- @He-Kai-fly（何凯）
- @JnanZhang（张佳楠）
- @kkjtmac（阚科佳）
- @Tomcxf（陈啸枫）
- @wangdepin（王德品）
- @kongjianyang（空间阳）
- @donghongyu2020（董弘禹）
- @DrRobinLuo（罗鹏）
- @Wangcy-rachel - 王春阳
- @zoe3251 - 舒晨阳
 


## 订阅
这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://files.mdnice.com/user/80107/49b94363-6ce9-4fc8-83b9-f66cd88f7d86.png)
