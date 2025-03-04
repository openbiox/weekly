---
date: 2025-03-02
comments: true
---
# 生信爱好者周刊（第 158期）：AI离彻底改变人类社会的能力只有10年

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![image](https://github.com/user-attachments/assets/54152759-196e-4f57-863a-dbe8bea0dd54)


## 本周话题：[AI离彻底改变人类社会的能力只有10年](https://mp.weixin.qq.com/s/WTUYJsrOTt0djufxaqT6lA)

谷歌DeepMind CEO Demis Hassabis说，将人工智能视为普通技术是错误的，人工智能将具有“划时代的意义”，很快将治愈所有疾病、解决气候和能源问题并丰富我们的生活，AGI大概需要 10 年时间，因为还需要 2 到 3 项重大创新，下一项就是基于代理的系统，能够完成你给它的特定目标或任务。


## 生信研究

1、[Evo2 | NVIDIA发布预测所有物种DNA、RNA、蛋白质的形式和功能的最大AI生物模型](https://mp.weixin.qq.com/s/o4ECM6F-dK2PUagS8kSYbg)

![image](https://github.com/user-attachments/assets/1aecb7d1-a2b7-4f79-9e95-1a327ec35196)


Arc研究所、斯坦福大学和NVIDIA联合发布了史上最大生物AI模型Evo-2。该模型基于128,000个基因组训练，涵盖从人类到细菌的多种生物，可预测DNA、RNA、蛋白质的功能，并生成染色体和小基因组。它还理解非编码基因变体，有望助力基因组设计和疾病研究。

- 论文链接：https://arcinstitute.org/manuscripts/Evo2

2、[Science | 赢得诺奖不是终点！David Baker再获里程碑突破——AI首次从头设计出蛋白酶](https://mp.weixin.qq.com/s/yHTjbCu3uhS4AD-N4breuw)

![image](https://github.com/user-attachments/assets/294197d9-bb22-4ee0-9b47-724fdc30c0aa)


该研究利用 AI 从头设计了具有复杂活性位点的**丝氨酸水解酶**，这也是首次从头设计一种新的酶，其能够加快一个**四步化学反应**，该反应对于许多生物和工业过程至关重要，其中包括塑料降解和回收。

- 文章链接：https://www.science.org/doi/10.1126/science.adu2454

3、[Cancer Cell | 三阴性乳腺癌化疗与免疫治疗的协同机制](https://mp.weixin.qq.com/s/EQSHcae7AsliaZet24Wnng)

![image](https://github.com/user-attachments/assets/dc4efe32-8582-41a5-8183-5c5440c8ee99)


研究团队系统整合了前期关于紫杉醇联合PD-L1抗体治疗的单细胞测序数据，并结合最新生成的白蛋白结合型紫杉醇（Nab-PTX）与PD-L1抗体联合的单细胞测序数据，对TNBC患者接受紫杉醇、白蛋白紫杉醇及其与PD-L1抗体阿替丽珠单抗联合治疗后的肿瘤免疫微环境进行了系统性分析，揭示了不同化疗药物在拮抗或协同免疫治疗中的独特作用机制，并提出了肥大细胞作为潜在治疗靶点的新观点，为优化TNBC的精准治疗策略提供了全新的理论依据。

- 论文链接：https://www.cell.com/cancer-cell/fulltext/S1535-6108(25)00025-X

## 博文资讯

4、[跟着Nature学作图——风车图](https://mp.weixin.qq.com/s/B7ibmD36BbZvv81kmmyzSA)

![image](https://github.com/user-attachments/assets/6b84683c-6a4c-45be-93fc-6a7ab99588ce)


该推文复现了Nature中出现的风车图，包含所有代码和数据文件。

5、[万人围观，用DeepSeek搭建个人知识库，真香！（附完整教程）](https://mp.weixin.qq.com/s/5pHIfyGqvfvtEekjWE0F1A)

![image](https://github.com/user-attachments/assets/0a6b27f9-19ca-499d-9f81-b268b3cd03fb)


本文介绍如何使用DeepSeek搭建个人知识库，方便集中管理和快速检索文档、笔记等资料。教程包括：下载安装Cherry Studio、注册登录“硅基流动”平台、配置API秘钥、添加对话和嵌入模型、创建知识库、上传文件并生成向量，以及通过智能助手引用知识库回复问题。网页版适合个人数据不涉及泄露风险的用户，本地部署则需较高硬件配置。

6、[一个完整的生信研究流程](https://mp.weixin.qq.com/s/C7ESVU5v0p8z-5PYJDbbYg)

![image](https://github.com/user-attachments/assets/9903aedf-ebc5-420e-9bfb-0059af188ba6)


推文中详细讲解了如何设计一个生物信息学研究，包括从科研问题到数据分析的各个步骤。

## 工具

7、[shiny 版交互式大语言模型 shiny.ollama](https://mp.weixin.qq.com/s/vcqM7YNWghIgtz4hVROGZw)

![image](https://github.com/user-attachments/assets/fe83d2e2-5d9b-4b1d-884b-8b0bd72cffc5)


本文介绍了 shiny.ollama，一个基于 R Shiny 和 Ollama 的交互式大语言模型工具，支持本地部署，具备完全离线、隐私保护、模型选择、消息输入、聊天记录保存等功能。用户需先安装 Ollama 和 shiny.ollama（可通过 CRAN 或 GitHub 下载）。安装完成后运行 shiny.ollama::run_app() 即可启动应用。

8、[知识库AI问答助手 - 馆长](https://www.ncurator.com/zh)

![image](https://github.com/user-attachments/assets/531dd777-60fe-42e3-b6ca-114892741cc6)


9、[Stirling-PDF | 本地托管的 PDF 操作工具](https://github.com/Stirling-Tools/Stirling-PDF)

![image](https://github.com/user-attachments/assets/8f1dc907-3888-411d-8987-0caca01e11f4)


- 试用地址：https://stirlingpdf.io/?lang=zh_CN

## 资源

10、[生物信息学中最常用的 30 个 Python 库](https://mp.weixin.qq.com/s/Q5iOJtnlwv6ypNEMfiKJ1g)

![image](https://github.com/user-attachments/assets/45855e11-27a1-4223-b44f-ee8d4473aa5b)


推文中分类介绍了生物信息学中最常用的30个Python库，包括SciPy、Matplotlib、Biopython等。

11、[40个顶刊同款图含代码](https://mp.weixin.qq.com/s/KOj-7MAUMWR6H0VL0nVLdA)

![image](https://github.com/user-attachments/assets/aefd4ea4-c490-40ea-8a84-ad77d3db261d)


推文汇总了40个顶刊的同款图以及代码，包括拟合散点图、火山图、小提琴图、韦恩图、累积柱状图、热图、箱线图、火柴杆图等。

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
