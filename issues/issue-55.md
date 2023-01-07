---
comments: true
---

# 生信爱好者周刊（第 55 期）：科学创新四十年，我们可能还没搞明白科学和技术的基本概念

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/ShixiangWang/weekly/discussions)

## 封面图


![](https://files.mdnice.com/user/38451/5df4a1f8-b5fa-4162-9e20-2ac0c614a8f2.png)

[测序中碱基识别](https://github.com/ShixiangWang/weekly/issues/1089)

## 本周话题：[科学创新四十年，我们可能还没搞明白科学和技术的基本概念](https://github.com/ShixiangWang/weekly/issues/821)

@wangdepin - “我们中国人默认的科学观的核心就是“科学”与“技术”不分。在我们中国人的日常语言中，“科学”二字特别容易念成“科技”，可是“科技”二字深究起来，更多的是指“技术”，而不是“科学”和“技术”的简称。这说明，在我们的潜意识里，是将“科学”和“技术”混为一谈的。” -- 吴国盛老师的《科学的故事》。如果在概念上我们都理解错误,怎么能进行创新。


## 生信研究


1、[Cancer Discovery | 迄今为止最大规模的黑色素瘤全基因组测序研究](https://mp.weixin.qq.com/s/Tn62EU2mtm7cJPJiKIn96g)


![](https://files.mdnice.com/user/38451/3dd355a7-6574-4a10-99e7-432b108d28d2.png)


该研究是迄今为止最大规模的黑色素瘤全基因组分析，通过WGS，RNA-seq和甲基化测序全面比较了四种主要黑色素瘤亚型的基因组学。这项研究强调了亚型之间的相似性和差异，为黑色素瘤的病因学和生物学提供了新的见解。

论文链接: https://aacrjournals.org/cancerdiscovery/article/12/12/2856/711161/Comparative-Genomics-Provides-Etiologic-and

2、[Nature Medicine | MSKCC 直肠癌分子研究](https://mp.weixin.qq.com/s/xTEgw1T3H6itGNhf-9Nj5A)


![](https://files.mdnice.com/user/38451/f8334bb8-96e2-47e8-895f-5138eff4d1ad.png)


该研究通过对迄今为止最大样本量的直肠癌进行了全面的分子层面的分析，建立了基因突变、转录组学、免疫学特征与临床治疗结果的联系。这些研究成果为预测患者对新辅助疗法的反应提供了重要参考。他们根据肿瘤的免疫浸润程度，确定了一个微卫星稳定的免疫热肿瘤亚型，这一亚型对新辅助疗法有更好的反应，并有更长的无病生存期。

论文链接：https://www.nature.com/articles/s41591-022-01930-z

3、[西安交大叶凯教授团队在《自然・方法》发表基因组结构变异检测的突破性研究成果](https://mp.weixin.qq.com/s/JjcfPoArT0PGqWmybhZ6zA)


![](https://files.mdnice.com/user/38451/c5cb4226-d651-4573-86cd-3665c029d2ed.png)


该研究基于复杂结构变异背景混杂、类型繁多未知的难点，设计了二维序列相似性图，首次将结构变异研究从序列空间建模求解转换为图像空间的多目标识别问题，实现了背景高噪声下未知复杂类型结构变异的精准识别。该方法主要由编码模块，基于卷积神经网络的多目标识别模块以及基于图结构的复杂结构变异表征模块构成。其中编码模块成功去除了基因组背景噪声对于检测的影响；多目标识别模块实现了只用简单结构变异训练神经网络就可以识别未知复杂类型结构变异的功能，避免了耗费大量资源创建复杂结构变异训练集；复杂结构变异表征模块为后续统一不同研究中报道的复杂结构变异类型提出了重要解决方案，避免了专家导向的复杂结构变异类型定义方式。

论文链接：https://www.nature.com/articles/s41592-022-01609-w

4、[Nature | 基于长读长测序的等位基因特异性分析揭示人类组织转录组变异](https://mp.weixin.qq.com/s/U9SM4H3I32HHZ-VUKZ05CQ)


![](https://files.mdnice.com/user/38451/dc73a18c-7a6c-42f6-b009-8eeaebe6dfa1.png)


近日，来自美国纽约哥伦比亚大学的研究团队利用ONT平台，对GTEx项目的细胞系和人体组织的88个样本进行了长读长RNA-seq。分析显示，**长读长测序数据的基因和转录组定量与Illumina RNA-seq高度一致**。低相关性基因和转录组在ONT数据中表达较低，复杂性较高的基因和转录组包含多个外显子，该研究结果发表**Nature**上。

论文链接：https://www.nature.com/articles/s41586-022-05035-y


## 博文资讯

5、[2022新版TCGA教程](https://mp.weixin.qq.com/s/rPeU_zpAkasW5i72A63NcQ)


![](https://files.mdnice.com/user/38451/51dd264d-8ebf-4475-a8e4-64a8c01d52ad.png)


本文介绍了新版TCGA数据的临床和表达矩阵下载、数据整理。

6、[无所不在的方差分析](https://mp.weixin.qq.com/s/KeZ7ysfaSsOYvCF98Pw6Bg)


![](https://files.mdnice.com/user/38451/e678e356-11f9-4e11-9ce5-502d53a847ca.png)


本文较为系统地对方差的应用做了介绍：方差分析是统计学中常用的方法，它在统计中的很多地方或明或暗地出现。在试验设计中有它，在回归分析中有它，在因果推断中有它，在时间序列分析中有它，在聚类分析中还有它。由于方差分析的表现形式很多，所以在实际领域，它的应用成功案例多得数不胜数。虽然名字叫做方差分析，但均值却是方差分析的主角，方差分析的目的往往是判定若干总体均值是否相等。

7、[肿瘤进化研究方法](https://mp.weixin.qq.com/s/x8mop-HI0UQKPUl9_7W5wQ)


![](https://files.mdnice.com/user/38451/a39811af-cccf-45f3-81f6-7d27efec7692.png)


肿瘤克隆进化是肿瘤研究中的宏伟命题，分析肿瘤样本中细胞群结构，可以针对性靶向肿瘤细胞治疗，这里针对发表在**Nature Methods**期刊上的几篇综述解读肿瘤进化研究内容。

参考文献：A practical guide to cancer subclonal reconstruction from DNA sequencing:  https://pubmed.ncbi.nlm.nih.gov/33398189/

## 工具

8、[R包:RforProteomics](https://github.com/lgatto/RforProteomics)

![](https://files.mdnice.com/user/38451/530f9476-7371-4435-81cd-82fda5fb6816.png)

该软件包详细介绍了如何用R和一些专用软件包访问质谱蛋白组学数据、操作和可视化数据，如何处理无标签和有标签的定量数据以及如何分析定量数据。

9、[aplot | 装饰主图的拼图R包](https://github.com/YuLab-SMU/aplot)


![](https://files.mdnice.com/user/38451/e9f52692-14a3-4f72-a20c-556424618572.png)


aplot包是Y叔开发的在主图周围加注释图的R包。

工具教程：https://yulab-smu.top/pkgdocs/aplot.html


10、[Graphormer](https://github.com/ShixiangWang/weekly/issues/959)


![](https://files.mdnice.com/user/38451/09f3ba66-2c77-46ad-ace2-4c2660067209.png)


Graphormer是一个深度学习库，研究人员可以利用这个包进行分子建模任务，训练自定义模型。它的目的是加速人工智能在材料发现、药物发现等领域的应用。



11、[rig | R软件管理工具](https://github.com/r-lib/rig)


![](https://files.mdnice.com/user/38451/7edf2cd0-6187-4637-8b99-b779e87f9734.png)


rig是一个支持多平台、对R软件进行安装、版本切换等多功能的管理软件。



12、[用于conda-生态系统用户包隔离的conda-smith存储库](https://github.com/conda-forge/conda-ecosystem-user-package-isolation-feedstock)

```sh
conda install conda-ecosystem-user-package-isolation
```
## 资源
13、[Bioconductor community blog](https://bioconductor.github.io/biocblog/)


![](https://files.mdnice.com/user/38451/918db15e-1f88-4d98-a56c-c5803125fc96.png)


Bioconducter社区博客地址：https://bioconductor.github.io/biocblog/ 


14、 [R包CheatSheet](https://github.com/GraphicsPrinciples/CheatSheet) 


![](https://files.mdnice.com/user/38451/ce6c9b04-39b2-4bfd-b668-525b5ea4602a.png)


该R包可以快速将“小抄”会以捆绑的形式发送到自己的电脑。


15、[Shiny开发资源](https://shinydevseries.com) 


![](https://files.mdnice.com/user/38451/26f6f916-b9be-471a-bd1f-92973c8d93bd.png)


该系列将展示shiny生态系统中的创新应用程序和软件包，以及背后的杰出开发人员，包括访谈、视频教程和直播以及播客。

## 历史上的本周

- 2022年1月：[第 15 期：科学家的层次](https://mp.weixin.qq.com/s/kcwqdJK9kWJ6Ff48TG4z6A)

## 贡献者（GitHub ID）

「Openbiox 生信周刊」运维小队：

- `@ShixiangWang`（王诗翔）
- `@kkjtmac`（阚科佳）
- `@NiEntropy`（赵启祥）
- `@He-Kai-fly`（何凯）
- `@JnanZhang`（张佳楠）
- `@Tomcxf`（陈啸枫）
- `@wangdepin`（王德品）

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。


![](https://files.mdnice.com/user/38451/be3fadf5-2122-4bfe-94f5-fabf800ca684.png)


（完）


>>>>>>> b1a26142567867d7589f4394698b54b2528000c7