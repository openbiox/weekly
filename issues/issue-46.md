---
comments: true
---

# 生信爱好者周刊（第 46 期）：你的苹果M系列芯片电脑跑生信顺利么？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo "「生信周刊讨论区（语雀）」") | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community "「生信讨论区（Gitter）」")

## 封面图

![](https://files.mdnice.com/user/33257/e40d1c30-7c19-4882-877e-0ccd6f59027d.png)

## 本周话题：[你的苹果M系列芯片电脑跑生信顺利么?](https://github.com/ShixiangWang/weekly/issues/1013 "你的苹果M系列芯片电脑跑生信顺利么?")

> ARM平台的苹果M系列芯片自发布以来已经有2年了，更强劲的M2系列芯片也可能在10月份发布。目前生信软件在M系列芯片上的兼容性也日趋完善，想必有不少小伙伴已经入手尝试了，那么来分享一下你在使用苹果M系列芯片电脑跑生信的感想吧！

`kkjtmac` - 最近入手了M1版本的Mac mini，尝试了R语言下的常规转录组下游分析，和Intel版本下的没有差异，而且基本没听到风扇转动。

## 生信研究

1、[ActiveSVM ｜ 提取scRNA-seq中的最小基因集](https://mp.weixin.qq.com/s/sl49BhheTXpB_8FmmVgcfg)

![](https://files.mdnice.com/user/33257/046f3584-11f2-4c1d-aa70-80a1fe0e2bb1.png)

作者开发了一种特征选择方法ActiveSVM，通过带有支持向量机分类器的主动学习策略来处理顺序特征选择。从大型单细胞 mRNA-seq 数据集中提取高信息量的基因，构建用于细胞分类的最小基因集。该方法可以降低计算和测序成本，为主动采样策略提供依据。

- 论文链接：https://www.nature.com/articles/s43588-022-00263-8
- 教程：https://pypi.org/project/activeSVC/

2、[Cancer Cell 专家论坛 | 肿瘤空间转录组学](https://mp.weixin.qq.com/s/uTxeN5-2yxjWUjiSHrqI0A)

![](https://files.mdnice.com/user/33257/af9c9ee2-53d6-4929-9ab8-0d189767da97.png)

空间转录组学和其他空间技术使科学家能够解剖肿瘤微环境中不同细胞类型的组织和相互作用。本文请专家讨论了该技术的一些方面，从揭示肿瘤微环境和异质性，到跟踪肿瘤进化，到指导肿瘤治疗，到目前的技术挑战。

- 论文链接：https://www.cell.com/cancer-cell/pdf/S1535-6108(22)00385-3.pdf

3、[Cell | "千人基因组计划"资源扩展——高覆盖全基因组测序和改进的分析方法发现更多基因变异](https://mp.weixin.qq.com/s/0anhpiS1r16gERvNrOQFXg)

![](https://files.mdnice.com/user/33257/91bf98b3-4b3f-4d72-93b6-fb2b4b532a6b.png)

近日，来自纽约基因组中心的研究人员与麻省总医院、耶鲁大学和人类基因组结构变异联盟（HGSVC）的合作研究在Cell上发表，其扩展了1kGP资源，分享了一个包含3202个样本高覆盖率WGS资源，包括602个完整的亲子三人组。研究团队通过机器学习模型集成了多种分析方法，进行了SNV和INDEL的鉴定，并生成了一组全面的SV数据集。研究团队还与前期数据集进行了比较，强调了此次变体鉴定方法的高灵敏度和高精度，特别是对罕见SNV、INDEL和不同频率SV的检测，这些都是以前低覆盖率测序无法实现的。

- 论文链接：https://www.cell.com/cell/fulltext/S0092-8674(22)00991-6?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0092867422009916%3Fshowall%3Dtrue

## 博文资讯

4、[四十年编程感想](https://mp.weixin.qq.com/s/PY6FfxxevyXybqofi9gJfg)

![](https://files.mdnice.com/user/33257/e4ec9712-08a8-46a0-bbb1-9bf867be94a1.png)

本文作者8岁学习编程，今年46岁，写了一大堆自己的感想，其核心要点如下：

- 编程是长期职业：你的目标不必局限在学习什么语言或框架，只要吃透基础知识，你可以学会任何你想要的东西。
- 多尝试不同的事情：1）刚开始不要急于求成；2）需要学习很多不同的东西，你按什么顺序学习它们并不是大问题；3）多学习一些困难的东西，容易发现自己的问题；4）最终需要深入某个领域
- 目标是变得更好：不管使用什么技术，你的目标都应该是动手做出成果，让自己变得更好。
- 继续工作：编程既不是短跑，也不是马拉松，而是日记。在日复一日的累积当中，完成你的事业。


5、[生物序列比对的几种应用场景](https://mp.weixin.qq.com/s/Z7FTlsQj6WuZt6kghI_Jlw)

![](https://files.mdnice.com/user/33257/4fda475a-3b6b-415e-96c7-0213b3c75dfb.png)

该推文列举了生物序列比较的主要应用场景：
- 物种/基因的进化
- 基因组学
- 不同功能的进化特征
- 引物设计
- 参考基因组比对

6、[熊说肿瘤｜跨越70年的癌症靶向治疗里程碑](https://mp.weixin.qq.com/s/pB8t4eEuuf6N6Hqe-0s9fQ)

![](https://files.mdnice.com/user/33257/21bdf90c-d627-47c7-988d-8fb7153a5bf5.png)

本文根据时间顺序整理归纳了癌症靶向治疗及其相关研究领域中的里程碑事件。

7、[论文投稿前必须检查的25个细节](https://mp.weixin.qq.com/s/g-ai18SCyy83IG-6uVyysg)

![](https://files.mdnice.com/user/33257/5a225214-fdd1-4d09-a825-d9f05e5c9e3b.png)

本文简述了在论文投稿前需要检查的25个细节，为文章的顺利接受提供有力的投稿准备！


## 工具

8、[ggmsa  |  多序列比对和相关数据的可视化探索工具](https://mp.weixin.qq.com/s/ZWh2fJoDCryrRTCucnEioQ)

![](https://files.mdnice.com/user/33257/a399e8a9-0808-4b6f-afff-34a6455d9c16.png)

ggmsa是Y叔团队开发的进行多序列比较结果可视化的R包，相关成果也发表在Briefings in bioinformatics上。

- 链接：https://github.com/YuLab-SMU/ggmsa

9、[ggpie | 绘制饼图的R包 ](https://github.com/showteeth/ggpie "ggpie | 绘制饼图的R包 ")

![](https://files.mdnice.com/user/33257/fd5ff151-9d73-42ea-a5d2-b8137c583f06.png)

ggpie利用ggplot2实现了饼图(2D和3D)、甜甜圈饼图和玫瑰饼图的绘制。

- 链接：https://github.com/showteeth/ggpie

10、[grafify包 | 一键搞定统计绘图](https://mp.weixin.qq.com/s/TRLeaC4zURoliJymCf0i5A)

![](https://files.mdnice.com/user/33257/24f8b7e9-8ed9-4254-9e4f-137fcf51df29.png)

R-grafify包，其包含了5大类共19种可视化图表，帮助大家更便捷的绘制符合出版要求的可视化图表。5个类别分别为：Two variables、Three or four variables、Numeric X-Y Plots、Before-after Plots、Data distributions。

- 链接：https://github.com/ashenoy-cmbi/grafify

11、[R Debugger | 在VScode调试R的插件](https://github.com/ManuelHentschel/VSCode-R-Debugger "R Debugger | 在VScode调试R的插件")

![](https://files.mdnice.com/user/33257/ea858184-1fa4-41f1-83a4-574f0f70c52d.png)

该插件将 R 语言的调试功能添加到 Visual Studio Code，依赖于R 包 vscDebugger 。

- 链接：https://github.com/ManuelHentschel/VSCode-R-Debugger

## 资源

12、[DIY.transcriptomics 数据分析课程](https://diytranscriptomics.com/project/lecture-intro "DIY.transcriptomics 数据分析课程")


![](https://files.mdnice.com/user/33257/3ab97e98-70ab-412c-843d-20de6f3082b7.png)

宾夕法尼亚大学的一门生物信息学自学课程，涉及 rna-seq 分析和单细胞转录组分析。网站包括课程 slides、video、以及其他一些免费资源。

- 资源链接：https://diytranscriptomics.com/project/lecture-intro

13、[design-resources-for-developers  |  开发者的设计资源集合](https://github.com/bradtraversy/design-resources-for-developers "design-resources-for-developers  |  开发者的设计资源集合")

![](https://files.mdnice.com/user/33257/5b8d7c02-f38f-4306-9089-71a92901a704.png)

该集合整合了设计各方面的资源，项目包含了图片、网站模版、CSS 框架、UI 等资源。

- 资源链接：https://github.com/bradtraversy/design-resources-for-developers

14、[单细胞ATAC-seq系列学习笔记汇总](https://mp.weixin.qq.com/s/ZjkSUdE_hek36OAoY566wA)

![](https://files.mdnice.com/user/33257/85d0eb6b-8e7a-4ab0-90a7-cc3a771429d8.png)

该笔记详细的scATAC-seq学习笔记汇总，从原始数据上游处理，数据整合，细胞分群，motif富集分析，轨迹分析等。

## 历史上的本周
- 2021：[第 6 期：你会买“炸场”Macbook Pro搞生信吗？](https://mp.weixin.qq.com/s/NeX9HO8LuIj9FWq7ul2Qxw)

## 贡献者（GitHub ID）

「Openbiox 生信周刊」运维小队：

- `@ShixiangWang`
- `@kkjtmac`
- `@NiEntropy`
- `@He-Kai-fly`
- `@JnanZhang`
- `@Tomcxf`
- `@wangdepin`

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。


![](https://files.mdnice.com/user/33257/08bffaca-8b56-433f-a47b-b87b0b5a6e7c.png)


（完）
