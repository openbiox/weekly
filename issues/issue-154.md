---
date: 2025-01-03
comments: true
---

# 生信爱好者周刊（第 154 期）：海归青椒“硬着陆”

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)



> 在发布这期内容之前，我回查了下记录：2021年9月12日我发布了第1期的内容，2022年8月6日开始以协作组的形式发布了第39期的内容。现在回头其实难以想象，为这个没有什么直接受益的事情坚持了三年多的时间，访问阅读量其实也并不多。我其实也不知道有多少读者能够有所收获，但我们一直在坚持着。这种坚持离不开所有weekly成员的付出，除了我之外，像阚科佳、陈啸枫、何凯、赵启祥等2024年都负责了超过了4次内容的编排，他们以及其他成员活跃地贡献了大部分内容的整理。感谢我自己的坚持，也感谢他们的坚持和信任，共同的努力是延续的根本。三年多前，我刚博士毕业、博士后入站不久；当前，我成为一名较为独立的科研工作者、高校教师，weekly以及weekly团队伴随了这一段成长经历，真心希望「生信爱好者周刊」的标志也能够伴随每位团队成员和读者的分享和成长。2025，我们坚持分享周刊进入第5年了，感谢大家！
>
> ——王诗翔



## 封面图

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250103171105494.png)

树莓派掌上电脑



## 本周话题：[海归青椒“硬着陆”](https://mp.weixin.qq.com/s/WGRwlLOiXkNRTBokOBSpsQ)

> 数据显示，中国留学人员环流趋势明显。2020年留学回国发展人数首次超过出国留学人数，2021年留学回国人员超过100万，十五年前，这一数字为6.93万人。今天，与大批留学回国人员一起求职的还有1000多万本土应届毕业生。在近年来的相关研究或者社会讨论中，人们愈发关注归国青年教师所面临的多重挑战。对于他们中的许多人来说，找到一份合适的教职仅仅是第一关，他们还需要从零启动科研，建立新的学术网络联结，在教学、研究与行政琐事寻找平衡。“非升即走”背景下，水涨船高的考核标准如同达摩克利斯之剑一般，悬在许多人头上。有人在阵痛期顺应土壤，调整自己的重心和工作安排；有人累积科研资本，申请"人才帽子"等以保障自己稳定的科研生产。也有人离开，重启赛道。

`@ShixiangWang`：政策和文化不要通过竞争机制去消耗人才资源，去生硬地适应环境，而是通过竞争连接、分享、沉淀、创新。这算是我个人对于推文最后一段内容的回应吧。



## 生信研究

1、[Cell | 整合多组学、多类型的肿瘤数据，构建全面的肿瘤治疗靶点全景图](https://mp.weixin.qq.com/s/uwtPhycoHqI8l0Go3gy7LQ)

文章通过整合多种组学、多种癌症类型的肿瘤数据，构建了全面的肿瘤治疗靶点全景图，成功发现并验证了多种癌症治疗的潜在靶点，揭示了改进和开发癌症治疗策略的新机会。

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250103171402856.png)

- 论文链接：https://www.cell.com/cell/fulltext/S0092-8674(24)00583-X

2、[Nature Communications|通过野生和栽培辣椒基因组研究揭示辣椒为什么会辣](https://mp.weixin.qq.com/s/OSor6FrykcXk6CwtUC5aug)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250103171437018.png)


文章通过组装两个端粒到端粒（T2T）无缺口辣椒基因组，深入解析了辣椒着丝粒序列特征，发现了独特的重复序列元件。并基于分子钟估计了茄科中辣椒素合成通路的进化时间节点，揭示了茄科植物中辣味形成和丧失的遗传基础。
- 论文链接：https://www.nature.com/articles/s41467-024-48643-0

3、[Nature Communications | 肿瘤外显子测序数据的ecDNA扩增鉴定新方法](https://mp.weixin.qq.com/s/eVx72TUptOwMUQfK-F4YsA)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250103171914551.png)

研究团队研发了一种机器学习模型和工具GCAP，用于预测肿瘤基因组中的ecDNA扩增及其相关基因。该模型从基因组变异角度出发，结合了肿瘤样本和基因水平的基因组损伤、拷贝数变异信息以及其他相关因素，能够预测单一样本中ecDNA扩增的情况。此外，该方法还适用于肿瘤全基因组和SNP芯片数据，具有广泛的实用价值。

- 论文链接：https://www.nature.com/articles/s41467-024-45479-6



## 博文资讯

4、[一个快速构建多个Git标识的小技巧](https://garrit.xyz/posts/2023-10-13-organizing-multiple-git-identities)

![](https://files.mdnice.com/user/5208/8f3db6cf-a737-448f-acf7-3fce5522ed23.png)
> Git是一个分布式版本控制软件，Garrit Franke的这篇博客分享了关于如何快速构建多个Git标识。

5、[一图流：机器学习基本流程](https://mp.weixin.qq.com/s/wqQ-T4uZi0FQbbwArjf7YA)
![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250103171618306.png)

原文用一张图介绍了机器学习的基本流程和知识，适合机器学习的初学者进行阅读。



## 工具

6、[GW-快速浏览基因组数据信息](https://github.com/kcleal/gw?tab=readme-ov-file)

![](https://files.mdnice.com/user/5208/2b4abbb1-5898-4caf-be2b-da3043645ada.png)


> GW是一个快速的基因组浏览器，允许您显示测序数据，特征轨迹，缩略图，生成静态图像和标签变体。

7、[sshx | 一个安全的基于网络的协作终端](https://sshx.io/)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250103172020175.png)



8、[Omnivore-全面的文本阅读器](https://github.com/omnivore-app/omnivore?tab=readme-ov-file)
![](https://files.mdnice.com/user/5208/f710f213-a96e-41c9-8e34-b3675d82bb59.png)

> Omnivore是一个完整的、开源的文本阅读器，它支持高亮显示、笔记、搜索和分享、全键盘导航等功能。

9、[RainbowGPT AI Agent](https://github.com/ZhuJD-China/RainbowGPT)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250103172100827.png)

RainbowGPT结合了AI Agent代理、GPT-4、GPT3.5、ChatGlm3、Qwen LLM、ChromaDB矢量数据库、Langchain知识库问答检索和谷歌搜索引擎。

## 资源

10、[jyshare-工具导航站](https://www.jyshare.com/)


![](https://files.mdnice.com/user/5208/c4276e1f-8826-434f-9945-da03c77255f9.png)


> 一个很齐全的工具导航站点，涵盖常用的编译、搜索和AI应用等相关工具软件，建议收藏！



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