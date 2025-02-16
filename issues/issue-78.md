---
date: 2023-06-04
comments: true
---

# 生信爱好者周刊（第 78 期）：霸凌是平庸科学家登上顶峰的手段

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/43254/b78623ce-23d8-4058-ad65-0181cafc825e.png)

[图片：地图的失真](ttps://twitter.com/SteveStuWill/status/1532753978253094914 "图片：地图的失真")

> 有时候，看地图会误判，地图上俄罗斯过大（6400公里），非洲过小（7200公里）。这并不是地图画错了，而是地球为球形，投影成平面地图会失真，高纬度地区被拉长了。

## 本周话题：[霸凌是平庸科学家登上顶峰的手段](https://mp.weixin.qq.com/s/K4iQILbAlztuPpBpVdHwYQ)

>如今大家早已不再痴迷于所谓的「好学生」滤镜，能够更加理性地认识到，「霸凌他人」与「擅长学术」两件事并不冲突。
>
>可事实也许还要更糟糕一些：一篇来自 Nature Correspondence 的文章表示，许多所谓的「明星学者」之所以能够出人头地，正是因为他们在职业生涯中选择了当个坏人——
>
>霸凌行为，正是这些平庸的学者登上顶峰的手段。

`@kongjianyang`：学术圈中的霸凌行为远未得到足够的重视，每年都会有研究生和导师之间的问题被曝光。虽然人们普遍认为，面对霸凌最好的做法是勇敢地寻求帮助并奋力对抗，但只有科研人员才知道，当霸凌者是自己的导师或PI时，想要反抗是多么困难。这篇文章为受到霸凌的科研人员提供了一些建议，希望每位科研工作者都能开心科研，对于霸凌行为勇敢的说不。

## 生信研究

1、[Cancer Cell | 基于bulk RNA-seq精准重建肿瘤TME的机器学习新算法Kassandra](https://mp.weixin.qq.com/s/0DascCYd5eadwdl77gcyeA)

![](https://github.com/openbiox/weekly/assets/13445428/b0e98fe5-0a1e-4a59-80b0-eef39c82c96d)

美国MD安德森癌症中心和BostonGene公司的研究团队共同开发了一种名为“Kassandra”的决策树机器学习（ML）算法。这个算法经过训练，使用超过9,400个组织和血液分选的细胞RNA图谱，并将其与数百万个人工转录组数据整合在一起，以准确地重建肿瘤微环境（TME）。Kassandra算法基于细胞RNA的独特特征，可以适用于不同类型的细胞，并帮助我们更好、更全面地理解仅包含RNA-seq数据的档案样本中的生物学信息。这项研究未来有望在多种疾病的临床应用中发挥重要作用。

- 文章链接：https://www.cell.com/cancer-cell/fulltext/S1535-6108(22)00319-1#secsectitle0015

2、[Science封面！华大构建全球首个脑再生时空图谱 ](https://mp.weixin.qq.com/s/2nc81ul7Q1oCJUGbHPnqOg)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202306011704621.png)

> 2022年9月2日，由杭州华大生命科学研究院主导，联合来自3个国家的17个单位的科学家共同组成的研究团队分析比较了蝾螈脑发育和再生过程，**构建了首个蝾螈脑再生时空图谱，这也是全球首个脑再生时空图谱, **相关成果以背靠背封面文章的形式发表于国际顶级学术期刊《科学》。科学家找到了蝾螈脑再生过程中的关键神经干细胞亚群，描绘了此类干细胞亚群重构损伤神经元的过程，同时还发现脑再生与发育过程具有一定的相似性，为认知脑结构和发育过程提供助力，为神经系统的再生医学研究和治疗提供新的方向。

- 论文链接：https://www.science.org/doi/10.1126/science.abp9444


3、[NPJ GENOM MED | 43万人大型临床诊断队列研究揭示，DNA和RNA配对检测能更准确地诊断遗传性癌症](https://mp.weixin.qq.com/s/FkvmXWf6QigjTzpJ47jd1w)

![](https://github.com/openbiox/weekly/assets/13445428/29a1edd6-14c8-49e2-8c49-21a2e3182418)

美国Ambry Genetics公司在npj Genomic Medicine杂志上发布了一项大规模队列研究的结果，研究团队通过将DNA和RNA测序配对来解决剪接变体识别和解释的难题，并描述了由43,524名接受遗传性癌症易感基因检测的个体组成的临床队列中的突变和剪接情况。该研究证明了DNA和RNA-seq配对检测的效用，其可以检测到影响剪接的致病变异，包括深内含子变异，从而能够鉴定出额外的具有临床可操作结果的个体。该研究结果强调了RNA-seq在提高仅采用DNA诊断方法可能会漏检的高危人群识别方面的重要性。

- 论文链接：https://www.nature.com/articles/s41525-022-00323-y


## 博文资讯

4、[jjVolcano | 一行代码绘制单细胞火山图](https://mp.weixin.qq.com/s/b3NAQUcRJYUZiSoDGqQmPg)

![](https://github.com/openbiox/weekly/assets/25057508/e1c0470e-42c1-401d-b2c1-4baa28c015ea)

本文介绍如何使用 scRNAtoolVis 包中的 jjVolcano 函数进行多组火山图的绘制。


5、[UCSCXenaTools探索各类型肿瘤的TN差异分析](https://mp.weixin.qq.com/s/l4wRWr0RSQ4jgrDXuKAWWA)

![](https://github.com/openbiox/weekly/assets/13445428/8a19019f-3e44-49d7-ab50-0001cd03cf2b)

UCSCXenaTools是由@ShixiangWang开发的R客户端，用于下载UCSC Xena平台的数据。这篇文章给出了利用UCSCXenaTools探索各种肿瘤与对照组之间在全局水平上（例如mRNA，lncRNA，miRNA，甲基化和蛋白质）的差异情况的分析流程。

6、[​2 万字系统总结，带你实现 Linux 命令自由](https://mp.weixin.qq.com/s/iVn6s8O3XQbGj3ElvftD5g)

![](https://github.com/openbiox/weekly/assets/13445428/1ab41995-dc07-4555-ac6c-a77e5c2b0fae)

Linux命令在生物信息分析中的重要性不言而喻。本文对Linux平台上一些常见命令进行了系统梳理，值得一读。


## 工具

7、[gptstudio：大语言模型的Rstudio插件](https://github.com/MichelNivard/gptstudio "gptstudio：大语言模型的Rstudio插件")

![](https://github.com/openbiox/weekly/assets/13445428/65ec783b-734b-495d-9569-54bf13dc7443)

一款能够将大语言模型整合到R语言分析工作流中的插件。这个插件很火，不到几个月已经在GitHub拿到了超过600的star，感兴趣的可以去尝试使用下它。

- 工具链接：https://github.com/MichelNivard/gptstudio

8、[GPT Academic：GPT 学术优化](https://github.com/binary-husky/gpt_academic "GPT Academic：GPT 学术优化")

![](https://github.com/openbiox/weekly/assets/13445428/2580bc8b-3e72-4624-831e-ab707b3114fc)

同样是一款基于大预言模型开发的工具，为ChatGPT/GLM提供图形交互界面，特别优化论文阅读润色体验，模块化设计支持自定义快捷按钮&函数插件，支持代码块表格显示，Tex公式双显示，支持Python和C++等项目剖析&自译解功能，PDF/LaTex论文翻译&总结功能，支持并行问询多种LLM模型，支持清华chatglm等本地模型。

- 工具链接：https://github.com/binary-husky/gpt_academic

9、[tidyclust ｜ 聚类模型的 tidy 通用接口](https://github.com/tidymodels/tidyclust "tidyclust ｜ 聚类模型的 tidy 通用接口")

![](https://github.com/openbiox/weekly/assets/25057508/f7dc73a0-1187-4b02-b767-5df8959768be)

## 资源

10、[适合撰写课程论文的 LaTeX 模板](https://mp.weixin.qq.com/s/4dM55x8Vt_4zUIk61rWJgg)

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202306011705663.png)

本文推荐了几个适合写书和笔记的LaTeX模板：

- Elegant LaTeX: https://github.com/ElegantLaTeX
- ElegantPaper: *https://github.com/ElegantLaTeX/ElegantPaper*
- ElegantBook: *https://github.com/ElegantLaTeX/ElegantBook*
- ElegantNote: *https://github.com/ElegantLaTeX/ElegantNote*


11、[推特上最新超15w阅读的科技论文写作新手指南](https://mp.weixin.qq.com/s/nBiAYxZNY9Vv7Ud4syqoHg)

![](https://github.com/openbiox/weekly/assets/13445428/197b240e-fb01-445e-9db3-73a60c3f9df8)

这是一篇在推特上广受关注的科技论文写作指南的中文译文，对于需要一些论文写作思路的同学来说，可以参考一下。

12、[AI工具导航网站](https://ai-bot.cn/ "AI工具导航网站")

![](https://github.com/openbiox/weekly/assets/13445428/945ebbc6-461e-4324-a790-e8eb8292f960)

随着ChatGPT的火爆，各种人工智能工具不断涌现，这个网站汇集了国内外热门的人工智能工具和网站，可以浏览一下，看看是否能找到你所需的人工智能工具。

- 网站链接：https://ai-bot.cn/

## 历史上的本周

第 38 期：[选人不选项目的「基石项目」能否走向成功？](https://mp.weixin.qq.com/s/iKOJEAtkHezmPtqHYIjhnw)

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

![](https://files.mdnice.com/user/38661/17812364-5134-43ba-92cf-0be6aff405e8.png)

（完）

