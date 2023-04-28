---
date: "2023-2-20"
comments: true
---

# 生信爱好者周刊（第 12 期）：你的饮食模式需要改变吗？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/ShixiangWang/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/ShixiangWang/weekly/issues/325)

## 封面图

![](https://user-images.githubusercontent.com/25057508/145682107-e33cf486-9cd6-4340-bc14-3816782d442f.png)

禁食在能量限制饮食的反应中起着至关重要的作用。([via](https://www.nature.com/articles/s42255-021-00466-9/figures/7))

## 本周话题：[你的饮食模式需要改变吗？](https://pansci.asia/archives/333595)

2021 年 10 月 18 日，国际期刊《自然医学》公开发表一篇研究论文，探讨饮食模式和改善生理健康之间的关系。研究将小鼠分为5组：（1）自由取食、（2）限制 30% 的热量摄取，单没有禁食期、（3）限制 30% 的热量摄取，半天内给食三次，另外半天禁食、（4）限制 30% 的热量摄取，每天只给食一次，另外半天禁食、（5）热量摄取总量不变，但每天禁食 21 小时。 

研究运用代谢组学与转录组分析等方法，发现仅仅「禁食」而没有减少摄取的总热量，就足以得到在限制热量的饮食模式时出现的大部分代谢与核酸转录组特征，以及延长寿命、防止衰弱等健康上的好处。

**读者觉得这种饮食模式可以迁移到人吗？**

> 从个人角度来看，如果每天只有3小时能自由吃饭，其他21小时无法进食，吃饭后6-8小时消化后带来的饥饿感对人的肠胃、精神带来的影响很难忽略。

## 生信科技动态

1、[Nature Communication | scGCN is a graph convolutional networks algorithm for knowledge transfer in single cell omics](https://mp.weixin.qq.com/s/oVwGBgDjNfEPGYImd9UF3A)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-12/1639276991838-image.png)

在文献和公共基因组学资源库中，单细胞组学是增长最快的基因组学数据类型。利用不断增长的标签数据集，并将标签从现有数据集迁移到新产生的数据集，将增强单细胞组学数据的探索。然而，目前的标签迁移方法性能有限，主要是由于细胞群的内在异质性和数据集之间的外在差异。在这里，作者提出了一个强大的图模型--单细胞图卷积网络（scGCN），以实现不同数据集之间的有效知识迁移。通过在总共30个单细胞组学数据集上与其他标签迁移方法的比较，scGCN在利用来自不同组织、平台和物种的细胞以及在不同分子层的细胞分析上始终表现出卓越的准确性。

2、[Science Advanced | 机器学习通过分析水平基因转移，预测抗生素耐药性传播](https://mp.weixin.qq.com/s/cZk7_Y1iaw6VleZUSmLlyg)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-12/1639277107047-image.png)

我们熟悉的从父母遗传给孩子一般被称为垂直基因转移；水平基因转移，则是指的是一个或多个基因，通过父母遗传以外的方式进行传递。

水平基因转移常见于细菌之中，有些细菌主动同周围的细菌发生接合作用并共享基因，从而实现基因转移。即使它们是完全不同的种类，一些细菌收集从其他细胞释放出来的基因并将它们收为己用。如果外源基因适应良好，在增殖时细菌会将外源基因传递给后代；假如这个外源基因是抗生素抗性基因，将会给疾控带来了非常大的困扰。

系统发育距离、共享生态学和基因组约束通常被认为是控制水平基因转移（HGT）的关键驱动因素，尽管它们的相对贡献尚不清楚。

康奈尔大学的研究人员将机器学习算法应用于一组精选的不同细菌基因组，以梳理特定功能特征对 HGT 事件的重要性。
研究人员发现功能性内容准确预测HGT网络，涉及抗生素抗性基因（ARG）的转移的性能进一步提高，突出了HGT机制、生态位特异性和代谢功能的重要性。发现尚未检测到的高概率 ARG 转移事件，几乎是人类相关细菌所独有的。该方法在预测病原体的 HGT 网络方面是可靠的，包括鲍曼不动杆菌和大肠杆菌，以及在局部环境中，例如个人的肠道微生物组。

3、[Cancer Cell | 基于小细胞肺癌单细胞图谱，鉴定与转移、免疫抑制及预后相关的细胞亚群](https://mp.weixin.qq.com/s/MMDucQjub5XipnGMV-4Ikw)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-12/1639277322042-image.png)

作为最具侵袭性的肺癌类型，小细胞肺癌（SCLC）患者的预后较差，并且大多数患者在诊断之时就已经发生了转移。被寄予厚望的免疫检查点阻断疗法也仅略微提高了患者的中位生存率。虽然SCLC在形态学上表现同质，但近期来自小鼠模型和人类肿瘤的数据表明，SCLC仍然存在显著的异质性。根据癌细胞中四种转录因子（ASCL1、NEUROD1、POU2F3和YAP1）的差异表达，研究人员对SCLC进行了分类。然而，这种分类下的不同亚型是否与特定的疾病阶段、转移潜能或免疫微环境相关，以及亚型之间是否存在可塑性等难题仍未得到解决。

近日，美国纪念斯隆·凯特琳癌症中心研究团队借助单细胞转录组和成像技术，构建了SCLC的单细胞图谱，鉴定出一组潜伏在肿瘤细胞周围、PLCG2高表达的干细胞样细胞亚群，这类细胞能够推动肿瘤的转移，并与患者的预后密切相关。该研究为小细胞肺癌的分子特征提供了支撑，为将来更加深入的研究提供了宝贵的数据资源，也为更为精准的治疗奠定了理论基础。

4、[Bioinformatics | BioDynaMo：一个研究生物过程的新计算平台](https://mp.weixin.qq.com/s/eDLM3DkzYX7lSwCYxoiYAw)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-12/1639277612151-image.png)


基于代理的模拟 (ABS) 是一种强大的工具，可帮助生命科学家更好地理解复杂的生物系统。计算机模拟是一种快速测试有关细胞群、组织、器官或整个生物体的（病理）生理学假设的廉价且有效的方法。然而，此类计算机模拟对科学研究的有效性通常是有限的。

萨里大学、欧洲核子研究中心、纽卡斯尔大学等研究机构的研究人员合作，提出了一种称为 BioDynaMo 的新型模拟平台。研究人员证明 BioDynaMo 可用于模拟以下领域的用例：神经科学、肿瘤学和流行病学。对于每个用例，研究人员使用实验数据或分析解决方案来验证 BioDynaMo 的模拟发现。性能测试结果表明 BioDynaMo 的性能比当前最先进的基线快三个数量级。读者可以通过<https://biodynamo.org/>查看相关示例。

## 文章

1、[tidyverse团队重新发布诸多包的许可协议，统一更改为MIT](https://www.tidyverse.org/blog/2021/12/relicensing-packages/)

tidyverse团队（包括r-lib、tidymodels）近十五年为R社区贡献了诸多的工具包和相关生态。但由于采取了多种不同的开源许可协议，使用者常常会感到混乱。本文总结了团队为重新制定许可协议作出的努力，全部更改为MIT协议。

2、[ggridges包—峰峦图详细介绍](https://mp.weixin.qq.com/s/LtFp5_SVDGHJl6VHznXDdA)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-12/1639278063842-image.png)


峰峦图对于可视化随时间或空间分布的变化非常有用，本文介绍如果通过ggridges包进行相关图形的绘制。


## 工具

1、[fgsea：快速基因集富集分析](https://github.com/ctlab/fgsea)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-12/1639278140826-image.png)

2、[tidybulk：将转录组学引入tidyverse生态](https://github.com/stemangiola/tidybulk)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-12/1639278216962-image.png)

转录组学分析可能因此变得顺滑，后面如果有分析需求或者有时间学习文档我再单独分享。

3、[ggVennDiagram：ggplot2实现的韦恩图](https://github.com/gaospecial/ggVennDiagram)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-12/1639278349460-image.png)

4、[flextable：表格展示利器](https://github.com/davidgohel/flextable)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-12/1639278415399-image.png)

提供了一整套表格展示语法，并支持Office。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-12/1639278454596-image.png)


## 资源

1、[互联网游荡杂志：一个超有意思的周刊](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzU5ODc3OTA0NQ==&action=getalbum&album_id=2061901943265951744&scene=173&from_msgid=2247487348&from_itemidx=1&count=3&nolastread=1#wechat_redirect)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-12/1639278549170-image.png)


这里记录一段时间作者在互联网上看到的有意思的内容与信息，防止它们在我的脑袋里走丢了。

（感谢[@mugpeng](https://github.com/mugpeng)的投稿）

2、[28张图全解深度学习知识](https://zhuanlan.zhihu.com/p/420155821)

吴恩达在推特上展示了一份由 TessFerrandez 完成的深度学习专项课程信息图，这套信息图优美地记录了深度学习课程的知识与亮点。因此它不仅仅适合初学者了解深度学习，还适合机器学习从业者和研究者复习基本概念。

## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

感谢以下读者的往期赞赏：

- 李浩

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）

