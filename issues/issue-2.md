---
date: 2023-02-10
comments: true
---

# 生信爱好者周刊（第 2 期）：生信的境界与道路

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

讨论区的帖子[《谁在招人？》](https://github.com/openbiox/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/openbiox/weekly/issues/4)

## 封面图

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171837480.png)

如果先做一个菜鸟。（[via](https://www.alifeoverseas.com/what-in-the-world-to-do-with-newbies/)）

**让别人看到你在学习**～。



## 本周话题：[生信的境界与道路](http://blog.sciencenet.cn/blog-404304-834869.html)

华中科技大学教授薛宇翻译生物信息学研究的5个层次水平并加入自己的理解：

- 0级（Level 0）：为建模、而建模（modeling for modeling’s sake）。简称：渣级。

- 1级（Level 1）：给数据、能分析。简称：菜鸟级。

- 2级（Level 2）：想新招、玩数据。简称：肉鸟级。

- 3级（Level 3）：玩数据、作发现。简称：顶级。

- X级（Level X）：玩科学、讲政治。简称：神级。

希望每一位生信学习者都能从渣打到神级。

如果读者对本期话题感兴趣，欢迎到讨论区评论交流。



## 生信科技动态

1、[第十届全国生物信息学与系统生物学学术大会](https://mp.weixin.qq.com/s/Px9zP-lsUeXHoA2i8CKmXA)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171359615.png)

全国生物信息学与系统生物学学术大会自1998年首届召开以来，已成功举办九届，是中国生物信息学研究领域学术水平最高、影响最大的全国盛会。第十届全国生物信息学与系统生物学学术大会将于2021年10月25日至28日在四川省成都市召开。此次会议由中国生物信息学学会（筹）主办，四川省生物信息学学会承办，大会主题为“生物信息学前沿——人工智能大数据系统生物学与人类健康”。

2、[未来科学大奖公布：香港大学袁国勇/裴伟士因SARS获生命科学奖](https://mp.weixin.qq.com/s/cG1IKgHe3l15Yc9QorLjxQ)

![132978831-c2cbc61a-0c69-4695-bcaa-ffc901245a0c](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171351018.png)

未来科学大奖（Future Science Prize）是由华裔科学家、企业家群体共同发起的民间科学奖项，设置“生命科学”和“物质科学”、“数学与计算机科学奖”三大奖项，单项奖金100万美元，于2016年首次颁发。旨在奖励在大中华地区（包含中国大陆地区、香港、澳门及台湾）取得杰出科技成果的科学家。

2021年未来科学大奖生命科学奖获奖者为：袁国勇（香港大学）、裴伟士（香港大学）。

获奖原因：他们发现了冠状病毒（SARS-CoV-1）是导致2003年全球重症急性呼吸综合征（SARS）的病原，以及由动物到人的传染链，为人类应对MERS和COVID-19冠状病毒引起的传染病产生了重大影响。

3、[聚焦五大领域：浙江大学发布《重大领域交叉前沿方向2021》报告](https://mp.weixin.qq.com/s/GK2jNJ2FWU_QMTjy4OEQhQ)

以智能化为特征的第四次工业革命已经全面开启，会聚技术的不断涌现，正引领各领域创新突破性跃迁。学科交叉是这场变革的核心驱动力，主要表现为信息、生命、物质三大学科板块间的深度融合，最终将推动人类生产生活发生深刻变化。把握全球科技发展趋势，瞄准交叉前沿领域加快布局，对于抢抓创新竞争未来制高点具有重要意义。

> 很多内容应该可以更生信关联起来。

4、[Nat. Comput. Sci. | 深度学习建模基因调控网络](https://www.nature.com/articles/s43588-021-00099-8)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171353817.png)

【[drugAI](https://mp.weixin.qq.com/s/w2ThVaw6oMrrUnyW1a53OA)】单细胞测序技术的快速发展为生物学家研究细胞状态提供了前所未有的机会。而在批量测序数据中未发现的实验噪声会显着降低下游生物信息学分析结果的准确性。为了解决这个问题，人们利用深度学习通过模拟基因之间复杂的相互作用模式来过滤单细胞转录组数据中的噪声。先前的基于深度学习的方法虽然能更清晰的揭示细胞异质性，捕捉转录组学相似性和细胞之间的差异，但很难评估基因调控网络（GRN）结构或数据其他内部结构。而许多计算模型是将GRN推断和单细胞数据分析模型进行结合。然而，通常需要设计复杂的实验，并且还可能引入额外的噪声。此外，基于单细胞RNA测序（scRNA-seq）数据的方法也有明显的局限性。

针对上述问题，本文作者提出基于β-VAE框架的DeepSEM模型，可以联合嵌入基因表达数据，同时构建GRNs反映单细胞内基因相互作用的内部结构，而无需依赖任何额外信息，例如TF结合motif或单细胞ATAC测序（scATAC-seq）数据。作者在多个基准数据集上评估DeepSEM在各种单细胞任务中的性能都获得了不错的结果，并且由于VAE模型本身可以对潜在向量空间进行扰动来生成新的数据，因此在训练样本数据有限的情况下，仍能保证细胞类型分类的准确性。

5、[吃下去的药被肠道细菌吸收了？可能会降低药效并改变肠道菌群](https://mp.weixin.qq.com/s/5w9Q_IIMrUBT9oY8aN2Nuw)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171356241.png)

人体肠道自然包含许多不同种类的细菌群落，这些细菌对健康和疾病都很重要，它们被称为肠道微生物群。人与人之间的细菌种类组成差异很大，此前已有研究表明，肠道细菌的种类与肥胖、免疫反应和心理健康等多种疾病有关。

不仅如此，肠道细菌还可以通过生化反应来改变某些药物的特性，这一过程被称为生物转化。那么，与之相反，某些常用药物在肠道的累积是否会改变人体的肠道微生物群呢？

2021年9月8日，剑桥大学医学研究委员会毒理学部门和德国欧洲分子生物学实验室的研究人员在Nature上发表题为：*Bioaccumulation of therapeutic drugs by human gut bacteria*的研究论文。

这项研究首次表明，某些种类的肠道细菌会积累人体药物，并改变细菌的类型及其活动。这可能会直接改变药物的有效性，因为积累可能会减少药物对身体的可用性，同时也可能间接地改变细菌的功能和成分，因为可能会产生副作用。

6、[上海交通大学王卫庆/曹亚南团队发表用于中国人群准确基因型插补的ChinaMAP参考Panel](https://mp.weixin.qq.com/s/YWePM9hRVJTr2_1JkkqtrA)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171358791.png)

研究团队基于中国代谢分析项目（ChinaMAP）的WGS数据构建了该高分辨率和群体特异性参考panel。与此前的中国样本的参考panel相比，ChinaMAP参考panel在样本量、测序深度、插补准确性、精确度和灵敏度方面表现出显著优势。ChinaMAP插补服务器（www.mbiobank.com）可以为中国和东亚人群的遗传研究提供最佳插补方法，有助于中国人群遗传研究中更全面的插补和更新颖的发现。

7、[通过迁移学习将单细胞数据映射到参考图谱](https://www.nature.com/articles/s41587-021-01001-7)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171414991.png)

大的单细胞地图集现在经常被生成，作为小范围研究分析的参考。然而，由于数据集之间的批处理效应、有限的计算资源可用性以及原始数据的共享限制，从参考数据中学习变得复杂。在这里，我们介绍了一种深度学习策略，用于在引用之上映射查询数据集，称为单细胞架构手术（scArches）。scArches使用迁移学习和参数优化来实现高效、分散、迭代的参考构建和新数据集的上下文化，而无需共享原始数据。使用来自小鼠大脑、胰腺、免疫和全生物地图集的例子，我们表明，尽管使用的参数比从头整合少四个数量级，但能保留生物状态信息，同时消除批效应。scArches可推广到多模态参考映射，允许对缺失的模态进行归因。最后，scArches保留了2019冠状病毒病（COVID-19）的疾病变异，当映射到健康参考时，可以发现特定疾病的细胞状态。scArches将通过迭代构建、更新、共享和有效使用参考地图集来促进合作项目。

8、[基于机器学习的儿童遗传综合征评估模型](https://mp.weixin.qq.com/s/qz7XFZgxbSLSGUogjmVycg)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171420475.png)

目前，机器学习技术在解释图像以诊断各种疾病方面显示出潜力。虽然面部特征的计算分析已广泛用于一般的安全应用，但尚未被用于医疗诊断。前期的初步研究结果表明，使用面部分析和机器学习技术识别与遗传综合征相关的面部畸形是可行的。但那些研究只是为了支持专业医疗机构对预先筛查的患者进行临床诊断，没有解决确定哪些儿童有出现遗传综合征的风险并应寻求专业治疗的关键需求，且其纳入的研究人群较为局限。

近日，美国华盛顿国立儿童医院的研究团队在The Lancet Digital Health期刊在线发表了题为*Development and evaluation of a machine learning-based point-of-care screening tool for genetic syndromes in children: a multinational retrospective study*的文章。研究团队开发出一种基于深度神经网络和面部统计模型的遗传病筛查技术，并评估了其在儿童遗传综合征预测层面的性能。根据多个国家的多中心数据分析表明，该深度神经网络学习模型能够在一般的儿科人群中识别任何遗传畸形，解释与种族、年龄和性别相关的表型变异性。

## 文章

1、[在ggplot2散点图中自动添加回归系数或回归方程、R2、P值等](https://mp.weixin.qq.com/s/1gTxGLQH7qzS14LvPlmxeQ)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171402192.png)

有时候使用ggplot2绘制散点图展示两组变量的关系时，同时也做了一些描述二者关系的统计，如相关性分析、回归分析等，并期望将相关系数或回归方程、R2、P值等也添加在ggplot2的散点图中，该如何实现呢？

2、[学习如何分析肿瘤空间异质性](https://mp.weixin.qq.com/s/VDbnGMI_leTJ0NhWv-UA2g)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171401590.png)

分析肿瘤空间异质性是历来研究的热点，但也是难点。因此，今天为大家深度解读一篇2021年6月发表在《Cancer Discovery》(IF=39.397；中科院1区)上的文章，学习作者如何利用公共数据探索空间异质性的分子特征。

3、[生物网络中的小世界系数（small-world coefficient）及R语言计算](https://mp.weixin.qq.com/s/4psOlju1EOIkRvNuW1tufw)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171403287.png)

本文简介一种网络拓扑属性，小世界系数（small-world coefficient）。

4、[构建基本shell脚本](https://shixiangwang.github.io/home/cn/post/2017-08-11-basic-shell/)

本文介绍如何构建基本的Shell脚本，掌握Linux终端编程。

内容：

- 使用多个命令
- 创建脚本文件
- 显示消息
- 使用变量
- 输入输出重定向
- 管道
- 数学运算
- 退出脚本

5、[Linux数据处理命令工具](https://shixiangwang.github.io/home/cn/post/2017-09-03-linux-data-analysis-tools/)

```bash
step1 input.txt | less
step1 input.txt | step2 | less
step1 input.txt | step2 | step3 | less
```

> Linux管道

本文参考学习《Bioinformatics. Data. Skills》，这里简要地整理下Linux用来处理数据文本的工具。

该书的获取方式见上期。

6、[使用dplyr进行数据处理](https://shixiangwang.github.io/home/cn/post/2019-11-06-data-processing-with-dplyr/)

```R
delays <- flights %>%
    group_by(dest) %>%
    summarize(
        count = n(),
        dist = mean(distance, na.rm = TRUE),
        delay = mean(arr_delay, na.rm = TRUE)
    ) %>%
    filter(count > 20, dest != "HNL")
```

> dplyr管道与数据操作

本文参考学习《R for Data Science》，这里介绍dplyr数据处理和编程基础。

7、[单细胞RNAseq数据的矩阵分解](https://divingintogeneticsandgenomics.rbind.io/post/matrix-factorization-for-single-cell-rnaseq-data/)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171418010.png)

我有兴趣学习更多关于矩阵分解及其在scRNAseq数据中的应用。我想对Elana J. Fertig研究组的论文*Enter the Matrix: Factorization Uncovers Knowledge from Omics*进行深入学习。



## 工具

1、[datar: dplyr in python](https://github.com/pwwang/datar)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171421494.png)

在生信分析中，`R`是很常用的语言，`R`中数据处理的包，特别是`tidyverse`开发的包，包括dplyr、tidyr、 forcats等，很受欢迎。他们的API设计简单易记，配合`ggplot2`，简直数据分析+作图的神组合。而`python`中，`pandas`虽然强大，但API繁多且不容易记住。`datar`将`R`中相关的包在`python`中进行了实现，使得`python`中的数据分析也可以用上`dplyr`的语法。`datar`不仅实现了管道操作，并且尽量遵循原包的API设计，对R熟悉的同学很容易上手。

> 本工具是作者本人分享，我简单的看了下项目仓库以及与作者交流，不仅发现tidyverse中极多有用功能被纳入，而且是纯Python实现的（与简单提供R接口不同）。非常厉害的工具，称得上Python中的tidyverse，推荐大家尝试使用！

```python
from datar import f
from datar.dplyr import mutate, filter, if_else
from datar.tibble import tibble
# or
# from datar.all import f, mutate, filter, if_else, tibble

df = tibble(
    x=range(4),
    y=['zero', 'one', 'two', 'three']
)
df >> mutate(z=f.x)
"""# output
        x        y       z
  <int64> <object> <int64>
0       0     zero       0
1       1      one       1
2       2      two       2
3       3    three       3
"""

df >> mutate(z=if_else(f.x>1, 1, 0))
"""# output:
        x        y       z
  <int64> <object> <int64>
0       0     zero       0
1       1      one       0
2       2      two       1
3       3    three       1
"""

df >> filter(f.x>1)
"""# output:
        x        y
  <int64> <object>
0       2      two
1       3    three
"""

df >> mutate(z=if_else(f.x>1, 1, 0)) >> filter(f.z==1)
"""# output:
        x        y       z
  <int64> <object> <int64>
0       2      two       1
1       3    three       1
"""
```

2、[eulerr](https://github.com/jolars/eulerr)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171425065.png)

eulerr生成面积比例欧拉图，显示与圆或椭圆的集合关系(交、并、解)。欧拉图是维恩图，不要求所有集合的相互作用都存在（无论它们是空的还是空的），这意味着，根据输入，欧拉有时会产生维恩图，有时不会。

3、[gt](https://gt.rstudio.com/) - 表格制作神器

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171429572.svg)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171430744.svg)

使用gt包，任何人都可以使用R编程语言制作好看的表。gt的哲学是：我们可以用一组内聚的表部件来构造各种各样的有用的表。这包括表头、存根、列标签和跨组列标签、表主体和表脚。

4、[gtExtras](https://github.com/jthomasmock/gtExtras)

gtExtras的目标是提供一些额外的辅助函数来帮助使用gt创建漂亮的表。这些函数通常是对样板文件的包装，或者添加了gt中尚未内置的功能。gt包是惊人的，确保去阅读官方文档。

> 主题

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171428982.png)

> 数据高亮

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171428060.png)

5、[gtsummary](https://github.com/ddsjoberg/gtsummary) - 准备好的演示数据总结和分析结果表

gtsummary包提供了一种优雅而灵活的方法来使用R编程语言创建可发布的分析和汇总表。gtsummary包总结了数据集、回归模型等等，使用了具有高度可定制功能的合理默认值。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171433108.gif)

6、[mathpix](https://mathpix.com/) - 图片转公式神器

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171434247.png)

好用的公式提取工具。支持拷贝到Word和LaTex。

## 资源

1、[Cookbook for R 中文版](https://openbiox.github.io/Cookbook-for-R-Chinese/)

Cookbook for R 中文版 是由 Openbiox 小组第一批创建和维护的Cookbook for R中文翻译项目。这里以直观明了的问题/需求和方案为基本内容向读者介绍 R 的基础和如何解决常见的分析问题。从阅读中读者可以学习安装和使用三方包、操作基础的数据类型，学习数据的导入、操作和可视化，学习统计分析和编写脚本等内容。

2、[free self-taught education in Bioinformatics](https://github.com/ossu/bioinformatics) - 开源社会大学生信之路课程

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171436427.png)

对于那些想要在自己的时间免费完成生物信息学课程的人来说，这是一条坚实的道路，课程来自世界上最好的大学。

在我们的课程中，我们优先选择MOOC（大规模开放在线课程）风格的课程，因为这些课程是根据我们的学习风格创建的。

要成为一名生物信息学家，你必须学习大量的科学知识，所以要做好准备，比如生物、化学等。

3、[getting-started-with-genomics-tools-and-resources](https://github.com/crazyhottommy/getting-started-with-genomics-tools-and-resources)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171437548.png)

[Ming Tang](https://github.com/crazyhottommy)多年整理的维护的基因组分析学习和使用资源。

## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |



## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）
