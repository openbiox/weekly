---
comments: true
---

# 生信爱好者周刊（第 24 期）：从有隙到无间，首个人类完整基因组发布

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo)

## 封面图


![](https://files.mdnice.com/user/4331/e4b981d0-31f5-460a-aec2-0c1de5e35922.png)

[Science人类基因组特刊](https://www.science.org/toc/science/current)


## 本周话题：[从有隙到无间，首个人类完整基因组发布](https://mp.weixin.qq.com/s/SXYwb0rdySa_459valluGw)


人类基因组计划 (HGP) 被誉为历史上最伟大的科学成就之一。该项目的目标是发现和绘制人类基因组的完整蓝图，包括估计的约25,000个基因，以促进进一步的生物医学研究。HGP项目于1990年正式启动，在花费10年时间后，也就是在2000年，第一版人类基因组首次发布。虽然当时它被认为是“完整的”，但是受限于Sanger测序和NGS的技术能力，实际上第一版人类基因组距离真正的完整仍然存在许多差距。在随后的20年中，虽然科学家们不断使用新的技术填补了一些空白，但直到2020年，仍然有8%左右的人类基因组序列未被绘制出来。

GRCh38缺失了人类基因组约8%的序列，有上百万碱基未知，被字母“N”表示；有169段重要的重复序列未能成功拼接；还有相当一部分序列难以分析组装。具有重要生物功能的染色体近端着丝粒的短臂、着丝粒和数个重复的常染色质区域也未能解析，只能以模式序列代表。这些信息和人类众多疾病息息相关，受限于测序技术，这些重要序列的解读组装未能实现。

这次的 T2T-CHM13 组装增加了五个完整的染色体臂。与过去 20 年任何参考基因组版本相比，更新了更多的未知序列。


## 生信科技动态

1、[美国All of Us项目发布首批人群队列数据](https://mp.weixin.qq.com/s/C0nzR4OOc9TKEXAQZK9A4Q)


![](https://files.mdnice.com/user/4331/83434926-0b11-4e96-912d-f8694ebdc253.png)


近日，美国“All of Us”研究项目公布了第一批近10万人的全基因组测序数据，同时包括身高、体重和血压等身体相关数据，以及调查数据，例如关于参与者的人口统计数据、生活方式和总体健康状况的数据。这些基因组数据可以通过一个基于云的平台All of Us研究员工作台获得。随着All of Us首批基因数据的发布，将有助于研究人员解决健康和疾病相关尚未回答的问题，进而推动新的突破和发现，以减少持续存的种族和族裔人口之间数据差异和医疗差异问题。

2、[Nature | 基于66种癌症类型训练机器学习模型，绘制癌症基因潜在驱动突变图谱](https://mp.weixin.qq.com/s/y-icef-Jyr9K_gOzxkf7tw)


![](https://files.mdnice.com/user/4331/81cee88e-835d-4cda-8b34-f33cb58d0e29.png)


巴塞罗那生物医学研究所研究团队通过模拟中性突变，用机器合成一组推测的从动癌基因突变，以此来模拟在人体内癌症相关基因的多米诺骨牌式突变。研究团队基于机器学习的方法开发出一种算法“boostDM”，用于评估给定基因所有可能的诱变，并评估它们对癌症发展影响的可能性。该算法可帮助临床医生对于病人的癌症发展做出更准确的解释。

3、[Nucleic Acid Research | 单细胞全基因组甲基化数据库scMethBank](https://mp.weixin.qq.com/s/1N2CGkg8YTW_ymWXeE-pUQ)


![](https://files.mdnice.com/user/4331/f4f025ff-e146-4e18-8f4f-f84eff3aaed1.png)

scMethBank 是一个开放访问和综合性的全基因组单细胞DNA甲基化数据库，收集基于重亚硫酸氢盐转换的单细胞原始测序数据，以标准化的工作流程在单碱基分辨率下检测甲基化状态并构建多种状态下的单细胞甲基化图谱。数据库目前收录了来自于15个公开的单细胞数据集的8328个单细胞全基因组重亚硫酸氢盐测序数据和人工审编的元数据，涉及人和小鼠两个物种、29种细胞类型和两种疾病状态。


## 文章

1、[forestploter: 分组创建具有置信区间的多列森林图](https://mp.weixin.qq.com/s/1xmOEqWOp9Z-rDFI7C1UrQ)

本文介绍如何绘制美丽的森林图。

![](https://files.mdnice.com/user/4331/2a35d164-e0a5-4721-88b6-d25178b61525.png)

2、[使用linkET包绘制相关分析组合图](https://mp.weixin.qq.com/s/bqEYio4RTbGwtO0n5iu1vw)

有很多人对下面这种图形比较感兴趣，本文介绍如何绘制它们。


![](https://files.mdnice.com/user/4331/ddf3cbc5-6934-4b3c-868f-da127b7949fc.png)

3、[（英文）Academic writing in R Markdown I](https://www.marianamontes.me/post/academic-writing-in-r-markdown-i/)

本文介绍如何使用RMarkdown进行学术写作和分享。


![](https://files.mdnice.com/user/4331/83d1429d-33eb-4e68-bc08-90a0f30b8d99.png)



## 工具

1、[GitHub action - Hub Mirror Action](https://github.com/Yikun/hub-mirror-action)

一个Github Action，用于在Github和Gitee之间同步代码。


![](https://files.mdnice.com/user/4331/91c4dbda-0d96-4c90-80d8-d90b9800e3b5.png)

2、[Repobeats - Stunning insights for
your GitHub Repo](https://repobeats.axiom.co/)

展示你GitHub详细信息的极佳工具。


![](https://files.mdnice.com/user/4331/4fff8857-267c-47ce-ba04-ed56222bf219.png)

3、[MLmetrics - Machine Learning Evaluation Metrics](https://github.com/yanyachen/MLmetrics)

一个R包，用于提供评估机器学习的模型性能指标的各种计算函数。


## 资源

1、[生物机制图资源库](https://mp.weixin.qq.com/s/_yizT7t4VbAAmLcOnirSlw)

详情看Y叔推文。

![](https://files.mdnice.com/user/4331/ff5b18d5-e11e-4163-951c-423d374e0170.png)

2、[华人人群遗传资源数据库合集](https://mp.weixin.qq.com/s/AbftLn8a8GAE38RuFZbtcg)


![](https://files.mdnice.com/user/4331/57b1040a-3547-4f5e-9a2f-e170410054ea.png)


3、[生物信息领域大牛导师推荐（第一季）](https://mp.weixin.qq.com/s/oY6p94lDxCS2cvsszTnnlg)


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648291334186-bd3390be-c83c-4396-aabd-ca39f588c15d.png)

感谢以下读者/组织往期的赞赏和赞助：

- Openbiox
- 李浩
- 周通

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

