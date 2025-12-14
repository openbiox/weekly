# 生信爱好者周刊（第179期）：在大数据时代，研究设计应优先考虑统计显著性

这里记录值得分享的生信相关内容，每半月发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")
 
## 封面图  


![](https://files.mdnice.com/user/143074/01c08c94-64d6-4f43-b413-0b158bacf226.jpg)


## 本周话题：[在大数据时代，研究设计应优先考虑统计显著性](https://www.nature.com/articles/d41586-024-03843-y "In the big data era, prioritize statistical significance in study design")
>许多数据驱动研究面临的核心问题并非分析工具不足，而是样本量受限导致效应被夸大、结果难以重复。在这一背景下，单纯追求更大样本并不总是可行或必要。通过在研究设计阶段优化样本构成、控制混杂因素并采用合适的统计模型，可以在有限样本条件下提高结果的稳健性与可重复性。这使得实验设计本身成为确保研究结论可靠性的关键环节。


## 生信研究

1、[Cell | 刘光慧团队破译运动抗衰密码，确定首个“运动模拟物”——甜菜碱，开拓科学抗衰新路径](https://mp.weixin.qq.com/s/rZ3tRPkYwf5BqIEI9xa0sA)

![](https://files.mdnice.com/user/143074/282c0525-85c8-4178-aa98-e457a2f2af01.jpg)

该研究系统性地剖析了运动重塑人体生理、延缓衰老的关键分子枢纽。“运动模拟物”甜菜碱不仅能精准模拟运动的抗炎与衰老保护效应，还能规避运动相关损伤风险，为老年群体开辟新型健康增益策略。  

- 论文链接：https://doi.org/10.1016/j.cell.2025.06.001


2、[Nat Methods | MassQL规范了代谢组数据分析，帮助研究者更好的解读代谢组数据，寻找未发现的代谢物](https://mp.weixin.qq.com/s/ya6wPFqlxTmOMVfo6M-s8A)  

![](https://files.mdnice.com/user/143074/3215b4f1-950b-4067-997d-de35b5b68c35.png)

该研究提出了一种通用的质谱查询语言——Mass Spectrometry Query Language (MassQL)，旨在解决当前质谱数据挖掘遗漏，脚本扩展性低和可重复性不足的问题。MassQL 提供了一个可表达、可复用的查询语言体系，用于识别并挖掘质谱数据中的特征模式，包括母离子峰、同位素模式、碎片特征等。它使科学家能够以统一的方式高效检索公共质谱数据库中的信息，促进跨研究领域的再分析与新发现。

- 论文链接：https://doi.org/10.1038/s41592-025-02785-1    

3、[Genome Biol | 基于单细胞和批量转录组学扩展人类蛋白编码基因的全基因组表达图谱，涉及所有主要组织和器官](https://mp.weixin.qq.com/s/lkgnApx6Z-wy6QZDP1TsPQ)   

![](https://files.mdnice.com/user/143074/968dce85-c5dc-4668-97ce-aea9e55bad5d.jpg)

研究团队利用单细胞转录组测序和批量转录组测序，扩展了涉及所有主要人体组织和器官中蛋白质编码基因的全基因组资源。所有结果都可以在更新的开放获取人类蛋白质图谱（HPA）的单细胞类型部分获得，该部分新增了17种新组织和37种新细胞类型，拓宽了对细胞多样性和复杂转录组学的了解，为探索这些组织和细胞类型中所有蛋白质编码基因的单细胞类型数据提供了公开工具。

- 论文链接：https://doi.org/10.1186/s13059-025-03616-4

## 博文资讯
4、[英国政府启动OpenBind，构建全球最大蛋白小分子交互数据库，重塑AI药物研发](https://mp.weixin.qq.com/s/ObVW-ovia_OX-KpXoEPFMw)

![](https://files.mdnice.com/user/143074/424a1f39-8c11-4a2d-879b-e4a82a9d8fdf.png)

本文介绍了英国政府启动的 OpenBind 计划，旨在构建全球最大规模的蛋白-小分子相互作用数据库，为 AI 药物研发提供高质量数据基础，推动 AI 制药进入系统化、规模化发展的新阶段。  

5、[机器学习因果推断中治疗异质性分析的R与Python体系](https://mp.weixin.qq.com/s/NJOS35hYmx-Byuy2XHAKrw)   

![](https://files.mdnice.com/user/143074/9f70a68b-a442-4221-aa4c-8a3ec8e19bc3.png)

本文系统梳理了机器学习因果推断中治疗异质性分析的 R 与 Python 工具体系，对比了两大生态在方法框架、代表性工具、应用场景与部署能力上的差异，并结合医疗健康等实际案例分析其优势与局限，为不同研究与应用场景下的工具选择提供参考。


6、[R包HPAanalyze：从 HPA 自动化批量下载数据并进行探索性分析
](https://mp.weixin.qq.com/s/w3Fnao7-30F2wqUy8qVP3Q)  

![](https://files.mdnice.com/user/143074/e41508e9-d97f-404d-9a03-a21f9ac939db.jpg)

本文介绍了R包HPAanalyze，该包用于从Human Protein Atlas（HPA）数据库中下载、解析与可视化蛋白表达数据，并结合 EGFR 示例展示了其在蛋白类别、组织表达、抗体信息及免疫组化图像获取中的实际应用。

7、[Nature 复现 | 绝美雷达图](https://mp.weixin.qq.com/s/DIgq_16wimecJ3HH5ITO2Q)

![](https://files.mdnice.com/user/143074/d8d69b27-4393-4b46-b721-f3aacfb5b9e0.png)

本文介绍了如何在 R 中复现多边形雷达图、分面雷达图以及带外圈注释的雷达图，结合顶级期刊实例，总结了雷达图标注、分面与布局等常见复现技巧。

## 工具   
8、[Sceptic：面向时序单细胞测序与成像数据的伪时间分析新工具](https://mp.weixin.qq.com/s/IJGJeodWfIdXtvMgjHUpWQ)

![](https://files.mdnice.com/user/143074/5eeb25ba-054d-4570-ade2-30b7dd73f0e9.jpg)

Sceptic 是一种基于支持向量机（SVM）的有监督伪时间分析方法，可用于时间序列的 scRNA-seq、scATAC-seq 及单核显微图像数据，在多模态单细胞数据中表现出较高的时间推断准确性。   
  
- 文章链接：https://doi.org/10.1186/s13059-025-03679-3

9、[ mLLMCelltype: 利用多个大语言模型共识进行单细胞RNA测序细胞类型注释的Python框架](https://github.com/cafferychen777/mLLMCelltype "mLLMCelltype")   
 
![](https://files.mdnice.com/user/143074/9ae3e1d1-0a77-455d-b139-081440bf252d.png)

mLLMCelltype 是一个创新的Python框架，用于单细胞RNA测序 (scRNA-seq) 数据的细胞类型自动注释。该工具通过多个大语言模型的迭代共识方法，显著提高注释准确性并提供可靠的不确定性量化指标。

- 工具链接：https://github.com/cafferychen777/mLLMCelltype    

10、[盘点“低成本实现分子动力学模拟”的Web工具或本地工具
](https://mp.weixin.qq.com/s/zQ11X_Axzqrm7ZS-P4B9BQ)

![](https://files.mdnice.com/user/143074/905d10e5-c4c4-480e-bd3f-f2d3ccaeecc9.png)

iMODS、ProDy、WebNMA 和 CABS-flex 2.0 等工具提供了基于 NMA 与弹性网络模型的蛋白构象变化与柔性分析方案，能够在无需高性能计算资源的情况下实现对蛋白动力学特征的快速探索。 

11、[BioDigital Human](https://human.biodigital.com/explore "BioDigital Human")

![](https://files.mdnice.com/user/143074/0b1d0455-34da-43d8-994a-3f182903a027.jpg)

BioDigital Human平台相当于一个精确的数字医学人体虚拟地图。主要内容包括8000多个解剖结构3D模型动画和视频，600多个3D健康状态、疾病状态和治疗模型，以及一个用于创建特定视图和模型的工具包Human Studio。可帮助用户以直观的方式理解和掌握解剖学、病理学以及治疗学的相关知识。

- 工具链接：https://human.biodigital.com/explore

## 资源   
12、[mkdocs-document-dates](https://github.com/jaywhj/mkdocs-document-dates "mkdocs-document-dates")       

![](https://files.mdnice.com/user/143074/13d29525-130d-4d6a-82a7-8392807ca86f.png)

新一代用于显示文档确切创建日期、最后更新日期、作者、头像、邮箱等信息的 MkDocs 插件。

13、[Enseqlopedia](http://enseqlopedia.com/ "Enseqlopedia")

![](https://files.mdnice.com/user/143074/d5d84f19-5d8f-49aa-bf66-6c306053e447.jpg)

Enseqlopedia 是一个面向 NGS 领域研究者与技术人员的综合性社区资源平台，整合了博客、用户地图和协作式 wiki，用于交流测序技术、实验经验与实践知识。 

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
- `@Wangcy-rachel`（王春阳）   
- `@zoe3251`（舒晨阳）   
- `@yanbin85`（严彬）   
- `@MadDERt`（王章宇） 
- `@yepu03`（孙裕钧）

## 订阅
这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。       
微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://files.mdnice.com/user/143074/4fa0b827-afe2-486c-9b1f-6d1aa805033a.png)    

（完）