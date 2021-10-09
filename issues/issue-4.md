# 生信爱好者周刊（第 4 期）：生信有一天可以得诺贝尔奖吗

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/ShixiangWang/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/ShixiangWang/weekly/issues/59)

## 封面图

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-8/1633681283849-134331979-41bf44aa-e319-4845-8651-d318ba3bbb48.png)

光环。（[via](https://twitter.com/thomasp85/status/1440581341167247360)）

## 本周话题：生信有一天可以得诺贝尔奖吗

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-8/1633680917866-1633680831596-image.png)

[【2021年诺贝尔生理学或医学奖揭晓】](https://mp.weixin.qq.com/s/775TSPD1GNe1ilWs0lVJig)北京时间10月4日下午，2021年诺贝尔生理学或医学奖揭晓。美国科学家David Julies、Ardem Patapoutian获奖，以表彰他们“发现温度和触觉的受体”。

人们对热、冷和触觉的感知能力对生存至关重要，支撑着我们与周围世界的互动。在日常生活中，我们认为这些感觉理所当然，但神经冲动是如何产生的，从而使温度和压力可以被感知？今年的诺贝尔奖得主解决了这个问题。

**生信发展了几十年，为各类生物医学研究进展立下汗马功劳。但生信技术中一些核心的原创性方法、目前不断变更的测序手段是否能够在未来获得诺贝尔奖呢**？你知道有哪些重要的生信方法和技术手段？你觉得它们能值一个诺贝尔奖吗？


## 生信科技动态

1、[多款测序平台性能评估成果发布，华大智造测序仪可提供高质量WGS](https://mp.weixin.qq.com/s/R1tR3bz4oL6RDn2EkrINRw)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633776017061-image.png)


近日，由生物分子资源设施协会（Association of Biomolecular Resource Facilities, ARBF）主导的ABRF NGS II期研究成果发表于Nature Biotechnology，文章题为“Performance assessment of DNA sequencing platforms in the ABRF Next-Generation Sequencing Study”。研究团队基于来自Illumina、Pacific Biosciences、Thermo Fisher Scientific、BGI、Oxford Nanopore Technologies和Genapsys的多款测序平台，在多个实验室对同一人类基因组家族、三个单独菌株和十种细菌的宏基因组混合物进行测序，并将各平台数据进行全方位、系统性比较，分析各个测序平台的性能差异和测序质量，以提供真实全面的参考证据。

数据显示，在短读长测序平台中，Illumina的HiSeq 4000和HiSeq X10平台提供了最一致、最高的基因组覆盖率，华大智造的BGISEQ-500、MGISEQ-2000平台提供了最低的测序错误率。在长读长测序平台中，PacBio CCS具有最高的基于参考的映射率和最低的非映射率。PacBio CCS和Oxford Nanopore的PromethION、MinION平台在重复序列丰富的区域和跨均聚物检测中均显示出最佳的序列定位性能。NovaSeq 6000使用2×250 bp读取化学是捕获已知INDEL事件的最强大的仪器。

2、[基于结构分类预测EGFR突变型NSCLC的药物反应](https://mp.weixin.qq.com/s/EsrlFfDGV21IIdTEgippeQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633776576785-image.png)


近期，在Nature杂志上发表了一篇名为*Structure-based classification predicts drug response in EGFR-mutant NSCLC*的文章，描述了一种基于结构的方法来定义EGFR突变的功能群，这种方法可以有效地指导EGFR突变NSCLC患者的治疗和临床试验选择，并表明基于结构-功能的方法可以提高对不同癌基因靶向治疗药物敏感性的预测突变。

3、[ecDNA与线性DNA的表观遗传差异研究进展](https://mp.weixin.qq.com/s/suMMwB7O0AX11Vu9WQSq5A)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633776655298-image.png)

华大基因唐冲博士团队于近日在表观遗传与染色质研究权威期刊Epigenetics & Chromatin上发表题为*Sequencing of methylase-accessible regions in integral circular extrachromosomal DNA reveals differences in chromatin structure*的论文，开发出一种单分子层级研究ecDNA染色质开放性的新技术—— CCDA-seq。


4、[ctDNA对NSCLC的BRAF抑制剂耐药机制探索](https://mp.weixin.qq.com/s/mN0iLubkXTVGJasloYFzLg)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633775681691-image.png)

本文主要评估了ctDNA靶向测序的临床应用，作者选择了不同时期的患者样本进行ctDNA分析，结合KM分析观察BRAF突变及与其共发生的突变对疗效的影响，从而确定对BRAF靶向治疗耐药的因素和相关基因组改变，最终明确，对BRAF突变和其他共发生突变的连续检测在临床治疗策略的制定上是有意义的。


## 文章

1、[富集分析的p值是怎么算出来的？](https://mp.weixin.qq.com/s/87xT9sZEL5OrYZAsLx3dRw)

通常各种软件做GO富集性分析，都是使用超几何分布进行计算。超几何分布是偏态的，所以fisher.test默认的双侧检验，其实是使用单侧来计算p值，我们可以对数据进行测试，使用双侧和单侧的p值是一样的，不过会影响对置信区间的估计。

2、[Sina图](https://twitter.com/rfunctionaday/status/1440186155652169730)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633775093587-image.png)

在可视化分布时，箱线图可以隐藏双模态，而小提琴可以显示不存在的数据。Sina图，其中的点与密度成比例抖动，提供了一个很好的解决方案。[`ggforce::geom_sina`](https://ggforce.data-imaginist.com/reference/geom_sina.html)提供了ggplot2的layer支持！

3、[河流图](https://mp.weixin.qq.com/s/vj7s2msKaw5dgccXZ5Ozlw)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633776084038-image.png)

河流图（Streamg raph），有时候也叫做“主题河流图”（Theme River），是堆积面积图的一种变形，通过“流动”的形状来展示不同类别的数据随时间的变化情况。但不同于堆积面积图，河流图并不是将数据描绘在一个固定的、笔直的轴上（堆积图的基准线就是x轴），而是将数据分散到一个变化的中心基准线上（该基准线不一定是笔直的）。

4、[浅谈Chip-seq/DNase-seq/ATAC-seq](https://mp.weixin.qq.com/s/9QfJCa52cVss50Ms4pW8bg)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633776799152-image.png)


在生物信息领域，测序技术的学习是必不可少的一环，要知道生物信息这门学科的起源就来自于各种各样的测序技术。这里谈一下Chip-seq、DNase-seq以及ATAC-seq这三种常见且比较相似的测序技术。

5、[把你用R画的图（base或ggplot2）变成ASCII纯文本！](https://mp.weixin.qq.com/s/fZqi6wuI7G1kDeUSa_HzPA)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633776870317-image.png)



## 工具

1、[vcfstats](https://github.com/pwwang/vcfstats) - 强大的vcf统计与作图工具


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633774180172-image.png)


做生信免不了和vcf文件打交道，但是如何快速的统计其中的信息与作图并不是一件容易的事。vcfstats提供了一种快速提取vcf文件信息与作图的方式，强大，快速而且容易扩展。

2、[UCSCXenaShiny](https://github.com/openbiox/UCSCXenaShiny) - 基于UCSC Xena癌症数据库的R包和可视化Shiny应用

UCSCXenaShiny是一个交互式探索UCSCXena的R包。它主要是为了提供一个web应用程序（建立在Shiny框架和UCSCXenaTools包之上），用于下载、分析和可视化UCSCXena的数据集。

支持CRAN、Docker、Conda等下载、安装方式。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633774585309-WX20211009-181607@2x.png)

3、[officeverse](https://ardata-fr.github.io/officeverse/) - 为生成office文档提供强大支持


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633774926416-image.png)




4、[rustdesk](https://rustdesk.com/zh/) - 又一个强大的远程桌面软件


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633774350843-WX20211009-181152@2x.png)


远程桌面软件，开箱即用，无需任何配置。

5、[螺旋桨（PaddleHelix）](https://github.com/PaddlePaddle/PaddleHelix/blob/dev/README_cn.md)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633775219899-image.png)

螺旋桨（PaddleHelix）是一个生物计算工具集，是用机器学习的方法，特别是深度神经网络，致力于促进以下领域的发展：

- 新药发现。提供1)大规模预训练模型:化合物和蛋白质; 2)多种应用:分子属性预测,药物靶点亲和力预测,和分子生成。
- 疫苗设计。提供RNA设计算法,包括LinearFold和LinearPartition。
- 精准医疗。提供药物联用的应用。

6、[RectChr](https://github.com/BGI-shenzhen/RectChr)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633775452662-OUT%20(1).png)


RectChr主要用于基于Chr染色体水平上多层次的可视工具。

## 资源

1、[bioinformatics-workflows](https://github.com/GoekeLab/bioinformatics-workflows)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633775550223-image.png)

工作流管理器提供了一种简单直观的方法来简化管道开发。在这里，我们为选定的工作流管理器提供基本的概念验证实现。分析工作流是基于RNA-seq管道的一小部分，使用fastqc进行质量控制和鲑鱼进行转录物定量。

2、[ggplot2绘图视频课程](https://mp.weixin.qq.com/s/VRY-ugwcu3D_yj5fRxHJbA)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-10-9/1633775877135-image.png)

3、[最常用的R包整理](https://mp.weixin.qq.com/s/nh3SjUKpwuiYhojrXoDxqQ)

在实际工作中，每个数据科学项目各不相同，但基本都遵循一定的通用流程。具体如下：

- 数据导入
- 数据整理
- 数据转换
- 数据建模
- 数据可视化
- 统计推断
- 报告展示
- 自动化分析

本文列出每个步骤最有用的一些R包。

4、[现代科研指北](https://github.com/yufree/sciguide) - 图书

本书初稿写作于我处于学生与独立科研人员或转行的过渡期，也就是博士后阶段。在这一阶段身处海外的我意识到了现代科研的一些趋势与这个年龄段科研人员的种种迷茫，为了铭记，也为了启迪，我将这一阶段对于现代科研的一些思考整合为一本书。这本书是开源的，在初稿完成后开放协作，我也鼓励科研人员能记录自己的成长经历，如果实在不知从哪下手，可以参考这本书来整理。是否认可本书观点并不重要，但没有自己的科研思考过程对于科研人员是一种悲哀。

## 贡献者

- [@pwwang](https://github.com/pwwang)


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

感谢以下往期赞赏/捐赠的读者：

- 李淑娴
- \*书

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）
