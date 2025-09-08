---
date: 2025-08-20
comments: true
---

# 生信爱好者周刊（第 172 期）：为什么现在有的大学越来越像高中？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图



![](https://files.mdnice.com/user/5208/9034d756-f86e-4539-882c-e6e3bc1f5cb6.png)


## 本周话题：[为什么现在有的大学越来越像高中？](https://mp.weixin.qq.com/s/7L5Z6Ji36sNfqimTpAypUQ)

> 在《人物》报道中，同济大学教育现代化研究中心研究员李俊在观察中发现，过去大学时期是学生高考后开始自我探索、独立生活的起步阶段，但现在大学校园里几乎只剩下两种人——一种是习惯性延续着高中阶段学习方式、目标极为明确、拼命卷自己的学生，另一种则是高考后完全放松、无所事事的人。他提出疑问：为什么大学越来越像高中了？

- @He-Kai-fly：高考的压力和竞争逻辑被延续到了大学，而大学原本作为自我探索、能力拓展的阶段，反而被“两极化”取代——要么继续“卷”到极致，要么彻底“躺平”。这背后既有社会就业焦虑、考研考编等竞争加剧的因素，也有高校培养模式同质化、缺乏多元成长路径的问题。

## 生信研究

1.[Science | 微软公司开源发布生成式AI模型BioEmu，可快速、精准预测蛋白质多种构象状态](https://mp.weixin.qq.com/s/4kpwRoMqNkOmhavThpK5-g)



![](https://files.mdnice.com/user/5208/c84c5a9a-3e9d-4b33-84d6-61becc5c1da4.png)

> 近日，微软研究院AI for Science团队开发了一种生成式深度学习模型BioEmu，能够以前所未有的效率和精度模拟蛋白质的构象变化。BioEmu能够在一个GPU小时内生成数千种构象状态，其速度显著优于传统MD模拟。此外，通过结合大量的蛋白质结构数据、超过200毫秒的MD模拟数据以及实验测量的蛋白质稳定性数据，BioEmu能以约1 kcal/mol的相对自由能误差准确预测蛋白质的平衡态构象。


参考文献：

1. https://cen.acs.org/biological-chemistry/proteomics/Microsoft-AI-predicts-protein-conformations/103/web/2025/07
2. https://phys.org/news/2025-07-ai-tool-protein-dynamics-aiding.html



2.[Nat.Commun| 人工智能计算方法CGMega解析癌症基因模块](https://mp.weixin.qq.com/s/L1jV40K0eT4Dh58je0_-Zw)


![](https://files.mdnice.com/user/5208/b14e6382-9ae6-4d18-8ea6-4bcab83158a9.png)


> 文章提出基于可解释图注意力机制的计算框架CGMega，实现了癌症基因模块的辨识与解析。

- 文章链接：https://www.nature.com/articles/s41467-024-50426-6


3.[Nature Machine Intelligence | 深度学习框架助力基因组数据提升肿瘤治疗](https://mp.weixin.qq.com/s/y7vcLtkxx92I6dnT15qN-A)


![](https://files.mdnice.com/user/5208/c32c61e2-7fde-491d-9c15-2356b84bc9a4.png)



> 文章提出了一种解释性深度学习框架，称为ResGitDR，通过整合基因组数据和细胞状态，显著提高了癌症药物反应预测的准确性。 


- 文章链接：https://www.nature.com/articles/s42256-024-00866-y
  
4.[2篇《自然》连发！樊荣/唐力团队揭示Type-2免疫增强肿瘤免疫疗法的重要机制](https://mp.weixin.qq.com/s/y1OzuAJRhdt29C33bvAwYg)


![](https://files.mdnice.com/user/5208/478b0714-d3eb-4e91-a1d3-cddab73440a6.png)

> 北京时间2024年9月25日23时，Nature同期连发两篇重磅研究，揭示了Type-2免疫在维持经CAR-T治疗的B-ALL患者超 8年无癌临床反应的关键作用，以及Type-2细胞因子Fc–IL-4协同Type-1免疫疗法高效、持久清除多种实体肿瘤的内在免疫学和分子生物学机制。这两项研究分别聚焦患者长期临床追踪（超10年）和临床前机理研究，得出了一致且相互支持的结论，即Type-2免疫可能在维持长效持久的抗癌免疫反应中起关键作用。这一发现揭示了Type-2免疫反应在肿瘤免疫中的未知功能，挑战了传统免疫学关于Type-2免疫应答在肿瘤免疫中负面作用的认知，并可能推动未来肿瘤免疫治疗设计的范式转变。

-论文链接：
1. https://www.nature.com/articles/s41586-024-07762-w
2. https://www.nature.com/articles/s41586-024-07962-4



## 博文资讯

5.[因果森林（Causal Forest）的运用 ](https://mp.weixin.qq.com/s/PI_QkxEe4igDH9P3Rf5PiA)


![](https://files.mdnice.com/user/5208/ac5fd72f-1d07-4d8e-91d9-7ff0fb7c2140.png)

> 因果森林（Causal Forest）是一种用于因果推断的机器学习方法。它基于随机森林（Random Forest）算法，但专门设计用于估计处理效应，即不同处理（或干预）对结果的影响。该文介绍因果森林模型在R语言中的运用。


6.[全球AI for Science领域顶尖科学家李子青教授出任百图生科首席科学家](https://mp.weixin.qq.com/s/UTMMSdF6l3XdOTL-t_qixg)


![](https://files.mdnice.com/user/5208/363a347d-5773-4f14-988b-d1f47ef381f0.png)

> BioMap 百图生科宣布，全球人工智能领域的顶尖专家、西湖大学人工智能讲席教授——李子青教授出任百图生科首席科学家（AI大模型）。李教授将指导和带领公司多个AI大模型项目的研发与应用，参与公司整体技术战略的规划和执行，为公司在“AI for Life Science”领域的前沿创新提供战略支持。


7.[英国生物银行与牛津纳米孔达成合作，构筑五万人表观遗传图谱](https://mp.weixin.qq.com/s/j1GgGqq8WvdTZrWakj2LQQ)



![](https://files.mdnice.com/user/5208/3b519944-213f-4006-b82b-383a3a69d0ba.jpg)


> 牛津纳米孔公司的突破性基因测序技术将对英国生物银行的 50,000 个样本进行分析，以创建全球首个“表观遗传图谱”。



## 工具
8.[猫步简历 ｜ 一款开源免费的简历制作神器](ttps://maobucv.com/ "猫步简历 ｜ 一款开源免费的简历制作神器")

![](https://files.mdnice.com/user/5208/2a8c0f33-1a2a-49f4-8069-ee52ba664d3f.png)

- Github：https://github.com/Hacker233/resume-design

9.[Lightpanda ｜ 专为AI和自动化设计的浏览器](https://github.com/lightpanda-io/browser "Lightpanda ｜ 专为AI和自动化设计的浏览器")



![](https://files.mdnice.com/user/5208/267e3a40-d84c-4bd3-b0c2-0159f0475614.png)


10.[podscript | 使用语言和语音转文字模型生成播客字幕](https://github.com/cottongeeks/podscript "podscript | 使用语言和语音转文字模型生成播客字幕")


![](https://files.mdnice.com/user/5208/de895d99-7480-4539-8130-181378dc3f16.png)





## 资源

11.[Tidy design principles](https://design.tidyverse.org/ "Tidy design principles")

![](https://files.mdnice.com/user/5208/fc886f84-3dbf-41f0-8d97-28b4a5e5352a.png)

> 本书的目标是帮助你编写更好的R代码。


12.[medicaldata-包含19个医疗数据集的数据包](https://mp.weixin.qq.com/s/08nf47JL-xQuK47N8OnL9g)


![](https://files.mdnice.com/user/5208/36a3bf70-70dd-4ba6-8aaa-39e9e14ff8ff.png)
> 这是一个包含19个医疗数据集的数据包，用于借助R语言教授可重复的医学研究相关知识。这个数据包对于任何向医疗专业人员（包括医生、护士、药剂师、实习生和学生）教授R语言的人来说都非常有用。这些数据集涵盖范围广泛，既有詹姆斯·林德1757年的坏血病数据集的重构版本、1948年原始的链霉素治疗肺结核试验数据，也有2012年吲哚美辛预防ERCP术后胰腺炎的随机对照试验数据，还有关于SARS-CoV2检测结果的队列数据等。许多数据集来自美国统计协会的TSHS（健康科学统计学教学）资源门户，该门户由马萨诸塞大学的卡罗尔·比奇洛维护（已获得许可）。开发版本中越来越多的数据集是由弗兰克·哈雷尔从其网站慷慨捐赠的，这些数据集目前仅存在于GitHub上的开发版本包中，预计将于2023年6月纳入CRAN。



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
- `@Wangcy-rachel` - 王春阳
- `@zoe3251` - 舒晨阳

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）
