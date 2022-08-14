# 生信爱好者周刊（第 40 期）：bTMB指导肿瘤免疫治疗临床研究

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo) | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community)

## 封面图


![](https://user-images.githubusercontent.com/25057508/183819838-65de5316-88c0-4c1a-bde7-a26215e562f7.jpg)

几内亚猪（豚鼠）[via](https://pixabay.com/zh/photos/cavia-caviidae-guinea-pig-7318119/)

## 本周话题：[bTMB指导肿瘤免疫治疗临床研究](https://mp.weixin.qq.com/s/yYwAZK6GddC7DpE0hRn-ug)

> blood TMB 是对血浆中游离DNA片段进行测序分析，计算得到的肿瘤突变负荷。既往多项回顾性研究已经证实了bTMB对PD-1/PD-L1抑制剂疗效预测的有效性，但目前尚缺少前瞻性研究证据。由希望之城国家医疗中心的Edward S Kim教授和克利夫兰诊所的Vamsidhar Velcheti教授领衔的研究团队，在著名期刊《自然·医学》发表重要研究成果，公布了首个bTMB前瞻性临床研究的最终分析结果。这一研究前瞻性地论证了bTMB对免疫治疗疗效的预测价值，同时也提出了bTMB未来的优化方向，为bTMB进入临床实践，向标准化检测进军，奠定了重要的基础。

`ShixiangWang` - 这项研究结果打消了一些质疑，说明TMB确实可以去指导临床治疗，而不仅仅是回顾性的分析。同时我们也需要关注到本文一些方法学的设计，包括MSAF的设定、倾向匹配评分的校正。


## 生信研究

1、[QB | 哈佛大学John Quackenbush教授回顾基因组研究的前二十年](https://mp.weixin.qq.com/s/LQPDxEUQ-O88q1oohTfitQ)


![](https://files.mdnice.com/user/4331/a5346b9f-3f5e-44d2-b918-d13313e52e23.png)

目前关于基因组还有很多问题有待回答，比如人类基因的数量、基因的定义等等，我们目前得到的任何版本的基因组都仍然是不完美、不精确的，但是是非常有用的。回顾基因组研究这前二十年，John教授提出了“技术和数据是最重要的”，“生物系统的复杂性”，“开放式科学的重要性”和“提出没有答案的问题是有价值的”这四条宝贵的经验。

论文链接：https://journal.hep.com.cn/qb/EN/10.15302/J-QB-021-0286

2、[Nature | 破解精神分裂症的遗传起源](https://mp.weixin.qq.com/s/MaoURA0UUqHQm4CpJt3YyQ)


![](https://files.mdnice.com/user/4331/af202290-635e-47fd-932f-2a89d41fb039.png)


4月初时，两篇关于精神分裂症的重磅文章以背靠背的形式发表于顶刊《自然》上，首次为我们详细分析了精神分裂症的遗传因素。这两项研究分别由精神疾病基因组学协会（Psychiatric Genomics Consortium，PGC）、精神分裂症外显子组测序元分析协会（Schizophrenia Exome Sequencing Meta-Analysis，SCHEMA）完成，汇集来自于40多个国家、数百个机构的研究人员。基于不同的研究侧重点以及鼎力合作，他们寻找到与精神分裂症相关的常见或罕见遗传变异，并对其分子机制提出突破性的见解——**精神分裂症是由神经突触的通讯中断所引起**，为精神分裂症提供了新的治疗靶点。

论文链接：

- https://doi.org/10.1038/s41586-022-04556-w
- https://doi.org/10.1038/s41586-022-04434-5
- https://doi.org/10.1038/s41588-022-01034-x

3、[NEJM 评论| 刻画肿瘤浸润T细胞的泛癌图谱](https://mp.weixin.qq.com/s/VM_mdcGsTS6VvTZfRGpgQg)


![](https://files.mdnice.com/user/4331/b02780a2-22c3-4c5f-b429-adee0b0647eb.png)

本文对对北京大学张泽民团队在Science上发表的文章Pan-Cancer Single Cell Landscape of Tumor-Infiltrating T Cells进行了点评，肯定了其工作对于泛癌T细胞免疫微环境的深入剖析以及未来可能的免疫新疗法做出的突出贡献。

论文链接：https://www.nejm.org/doi/full/10.1056/NEJMcibr2119477


4、[Cell Reports | 人类癌症预后特征的全基因组鉴定及分析结果](https://mp.weixin.qq.com/s/jPa7Sg2Em_2YSkwa4hRXSw)


![](https://files.mdnice.com/user/4331/abd02b30-63b6-4ded-ba42-7bdb24e96831.png)

研究团队对TCGA中所有类型的肿瘤患者和所有基因组数据平台进行无偏倚的生存分析，深入解析了侵袭性肿瘤和惰性肿瘤之间的分子差异，并严格评估了临床前研究中患者预后数据的利用。通过来自10,884名患者的基因表达、拷贝数、甲基化和突变数据构建了全基因组生存模型，生成了超过300万个Cox比例风险模型的丰富数据集，并在33种肿瘤类型中识别了超过10万个显著的预后生物标志物。

论文链接：https://www.cell.com/cell-reports/fulltext/S2211-1247(22)00313-8

5、[iMeta | 德国国家肿瘤中心顾祖光发表复杂热图(ComplexHeatmap)可视化方法](https://mp.weixin.qq.com/s/ncvGZ_ucxGPQZ84XkRiFuw)


![](https://files.mdnice.com/user/4331/46795966-4c55-484c-a1d3-b1f241f47ffd.png)


热图是一种广泛针使用的针对矩阵数据的统计可视化方法，其用于揭示存在于矩阵中相似模式。目前R中有许多用于可视化热图的包，而ComplexHeatmap包为构建高度可定制的热图提供了最丰富的工具集，通过自动拼接和调整多个热图以及复杂注释，轻松建立多个来源信息之间的关联，本文全面介绍了ComplexHeatmap的设计、功能及应用场景。

论文链接：https://onlinelibrary.wiley.com/doi/10.1002/imt2.43

## 博文资讯

6、[生物计算解码免疫：百图生科发布《计算免疫问题白皮书》](https://mp.weixin.qq.com/s/IcbYqzjzeoYiBVbEfkXIDw)


![](https://files.mdnice.com/user/4331/fa79b0f2-afbf-45eb-803a-726853aa009e.png)

最近，百图生科（BioMap）对外宣布成立百图生科免疫专家委员会。在免疫专家委员会第一次全体工作会议上，专家们结合免疫生物学的进展和未满足的临床需求，创新性地提出了五大高价值且有望利用生物计算手段加速提供解决方案的免疫学问题（即“五大计算免疫问题”），并就每个方向进行了深入的探讨和阐述。


7、[使用Kubernetes和Future包轻松并行化云中的R](https://www.jottr.org/2021/04/08/future-and-kubernetes/)


![](https://files.mdnice.com/user/4331/5a7aa7a5-8bf8-4615-ae74-19567094736b.png)

在这篇文章中将演示你如何在运行云中的机器集群上轻松地使用R中的future包，特别是在Kubernetes集群上。这允许你在云计算中轻松地使用R进行并行计算。在云中这样做的一个优点是能够轻松地扩展(虚拟)机器的数量和类型，你可以在这些机器上运行并行计算。


8、[ggplot 分面的细节调整汇总](https://mp.weixin.qq.com/s/fzcGJugs0VxJpM6nb25hLA)


![](https://files.mdnice.com/user/4331/d8d0794b-adcf-4cbb-893e-54ff6c28bac8.png)

本文通过具体的实例，详细的介绍了如何在ggplot2调整分面细节。


9、[DNS 查询原理详解](https://mp.weixin.qq.com/s/Kur84cigXkiTs3vimS3wQA)


![](https://files.mdnice.com/user/4331/c4ead672-19d6-4783-a844-051047ebdf33.png)

DNS是域名系统，是用来实现域名和IP地址相互映射的一个分布式数据库, 而访问网络资源的第一步就必须经过DNS解析过程，通过查询得到域名的IP地址才可访问网站，本文通过一些实例来详细介绍DNS查询到底是怎么完成的。

10、[GATK 的 germline CNV 流程--肿瘤基因组测序数据分析专栏](https://mp.weixin.qq.com/s/VUe2wvbnp68qmjw1v0o3yQ)


![](https://files.mdnice.com/user/4331/022b145e-ed84-45d4-8c42-31ccc0d8de60.png)

GATK流程中体细胞拷贝数变异（germline CNV）的中文教程。

- 教程：https://gatk.broadinstitute.org/hc/en-us/articles/360035531152



## 工具

11、[EvoFreq](https://github.com/MathOnco/EvoFreq)

![](https://files.mdnice.com/user/4331/916dbd4b-0527-4fa3-88fe-7672c60cd707.png)

高通量序列数据为研究群体的分子特征提供了有力的支持，当记录大量的时间步骤后，这样的数据可以通过跟踪基因型频率的变化随着时间的推移从而来揭示所研究的种群的进化动力学。因此我们需要一种简单而灵活的方法来可视化日益复杂的数据集。本文开发的EvoFreq包大大扩展了之前的克隆、时间动态可视化方法，并为用户提供了一系列显示序列或模型数据的选项。

论文链接：https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3173-y

12、[ezASCAT - 方便地从R中的Tumor-normal或Tumor only BAM文件执行ASCAT拷贝数分析](https://github.com/CompEpigen/ezASCAT)

该工具由maftools作者开发，主要功能是ASCAT软件的一个包装器。

13、[fastverse - 高效数据计算R包集合]( https://github.com/SebKrantz/fastverse)

![](https://files.mdnice.com/user/4331/5d8a8737-7e03-4164-ab06-0fd49be426f5.png)


14、[rdataretriever](https://github.com/ropensci/rdataretriever)

rdataretriever提供数百个常用公共数据集中处理过的干净的数据，同时也可对数据进行清理、存储和存档。

数据集列表：https://retriever.readthedocs.io/en/latest/datasets_list.html

15、[wxpython](https://www.wxpython.org/)


![](https://files.mdnice.com/user/4331/7e73b2c4-7482-46bf-bc59-f06516c02a51.png)


wxPython是Python语言的跨平台GUI工具包。使用wxPython软件开发人员可以为他们的Python应用程序创建真正的本地用户界面，在Windows、mac和Linux或其他类unix系统上运行，只需要很少或不需要修改。

Hello world:

```python
# First things, first. Import the wxPython package.
import wx

# Next, create an application object.
app = wx.App()

# Then a frame.
frm = wx.Frame(None, title="Hello World")

# Show it.
frm.Show()

# Start the event loop.
app.MainLoop()
```

## 资源

16、[图书：Applied Data Skills: Processing & Presenting Data](https://github.com/PsyTeachR/ads-v1)


![](https://files.mdnice.com/user/4331/067f82d8-4972-41c3-b179-3f790f6d1b9b.png)


这本书提供了将原始数据转化为有信息的摘要和在专业报告和演示中呈现的可视化所需的基本技能的概述。

图书链接：https://psyteachr.github.io/ads-v1/

17、[ci4cc-informatics-resources - 癌症中心的癌症信息学 (CI4CC)：建立一个专注于分享想法，致力于改善癌症护理和患者结果的非营利性生信社区。](https://github.com/seandavi/ci4cc-informatics-resources)


![](https://files.mdnice.com/user/4331/2abbec72-7007-4e62-9083-b8fd84ae972b.png)


![](https://files.mdnice.com/user/4331/d0cf2760-7b45-409b-b257-3e6f4924dbe1.png)

成员遍布全球，每半年发起一次面对面会议，作为信息学领导者讨论在各自癌症领域面临的挑战和问题。

- 社区链接：https://www.ci4cc.org/


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

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

