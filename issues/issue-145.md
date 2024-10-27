---
date: 2024-10-27
comments: true
---

# 生信爱好者周刊（第 145 期）：班车司机与诺贝尔奖

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202410272322616.png)

[来源](https://unsplash.com/photos/a-waterfall-with-a-green-and-purple-aurora-above-it-1gWakPC5e5Q)

## 本周话题：班车司机与诺贝尔奖

> 科学有时很残酷。对于Douglas Prasher来说，在卖车行打一份一小时挣10美元的工，与获得诺贝尔奖及其带来的荣耀和120万美金，只有一线之差。

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202410272320826.webp)

`@ShixiangWang`：非常认可作者朱勇在最后的一段话：“从古至今，人类凭借着自强不息的精神，对知识的好奇心，对真理的渴望，不断推动科学和技术的交替进步，促进社会的发展。在漫漫的科技历史长河中，既有牛顿和爱因斯坦这样灿若星辰照亮世界的天才人物，也有Prasher在黑暗中踯躅而行的寂寥身影。他们都是英雄。”对于个人而言，有所爱必有所得。

## 生信研究

1、[Quantitative Biology | 生物信息与大语言模型](https://mp.weixin.qq.com/s/IwKiW1O6JQhwwFd21HjVLQ)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202410272231500.webp)

本文从基于文本的大语言模型在生物学信息任务上的应用与基于生物学数据预训练的基础模型两个角度探讨了基础模型对生物信息领域的影响，目前的发展与局限性，及潜在的发展方向。

- 论文链接：https://doi.org/10.1002/qub2.69



2、[Nature | 新工具AF-Cluster预测蛋白不同构象](https://mp.weixin.qq.com/s/AppHdy0K0pgu8O0Si6fFlg)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202410272234805.png)

对蛋白多构象解析可以帮助人们进一步理解其功能，但是目前相关工具欠缺。布兰迪斯大学Dorothee Kern等研究人员开发了预测蛋白质构象的新工具AF-Cluster，该工具成功预测已知与未知的蛋白构象。该工作主要的创新想法是：部分蛋白家族多序列比对（multiple sequence alignment (MSA)）能够体现蛋白在不同构象下的氨基酸残基共演化（coevolution）信息；因此，对这些蛋白家族基于序列相似性进行聚类，分cluster进行蛋白结构预测（基于AlphaFold2）就可以解析其不同构象。

- 论文链接：https://www.nature.com/articles/s41586-023-06832-9



3、[Sci China Inf Sci｜基于张量网络的密度聚类算法](https://mp.weixin.qq.com/s/Q-1EdFX0RAqTJIqf0K-Nbw)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202410272237905.webp)

本文创新性地将物理学中的张量网络应用于数据科学领域，为解决具有不确定数量簇的聚类问题提供了一种新的视角和解决方案。

- 论文链接：https://link.springer.com/article/10.1007/s11432-023-3869-3



4、[Nat Med | Paige、微软携手发表迄今最大的计算病理学基础模型Virchow，为AI癌症病理学树立新标杆](https://mp.weixin.qq.com/s/yUMFhehYsAq53XjW2Z2Dug)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202410272242410.webp)

AI病理学解决方案提供商Paige公司联合微软发表了合作开发的顶级AI癌症病理基础模型——Virchow，展示了其如何在超过100万个WSIs上进行训练（同类数据集中规模最大），从而具备对病理学图像中观察到的各种模式进行前所未有的建模能力。数据显示，Virchow在生物标志物预测、细胞识别和泛癌检测方面具有一流的性能。

- 论文链接：https://www.nature.com/articles/s41591-024-03141-0



## 博文资讯

5、 [当 ggSCvis 遇到ggmagnify](https://mp.weixin.qq.com/s/5L4dxlRbTgjZC_zwl3wReQ)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202410272244252.webp)

本文主要针对关于如何使用R语言中的ggmagnify包来放大散点图中的特定细胞进行了详细展示。



6、[CircRNA的体外环化技术介绍](https://mp.weixin.qq.com/s/7Ym6AxwEu_BuXYB3sSs78A)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202410272314735.png)

7、[英文｜Large Language Models in Molecular Biology](https://towardsdatascience.com/large-language-models-in-molecular-biology-9eb6b65d8a30)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202410272317243.png)



## 工具

8、[Gmeek｜超轻量博客框架](https://github.com/Meekdai/Gmeek)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202410272249889.jpg)

Gmeek是一个博客框架和超轻量级个人博客模板。其完全基于Github Pages 、 Github Issues 和 Github Actions。不需要本地部署，从搭建到写作，只需要18秒，2步搭建好博客，第3步就是写作。

9、[xcp|一个拓展的cp命令](https://github.com/tarka/xcp/)

xcp 是 Unix cp 命令的（部分）克隆。它并非旨在完全替代，而是一个具有更友好的用户反馈和某些在特定任务下有意义的优化的辅助工具。



10、[Photor ｜ photor.fun](https://www.photor.fun/)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202410272254071.png)

简单几步，让你的截图不再单调。



## 资源

11、[今日三句半](https://www.threenhalf.com/)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202410272313273.png)

订阅免费邮件，每天收到热点科技新闻总结！



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

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）