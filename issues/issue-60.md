---
comments: true
---

# 生信爱好者周刊（第 60 期）：孟德尔诞辰 200 周年

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/ShixiangWang/weekly/discussions "「生信周刊讨论区」")

## 封面图



![](https://files.mdnice.com/user/38451/10feee82-416a-499d-a785-950d01ac8b35.png)


[AI R包生成的艺术照片](https://github.com/cutterkom/generativeart)

## 本周话题：[孟德尔诞辰 200 周年](https://mp.weixin.qq.com/s/k795DYd0FMZXbMbNNyzCLA)  

> 1822 年 7 月 20 日，现代遗传学之父孟德尔出生于奥地利帝国西里西亚海因策道夫村。2022年是孟德尔诞辰 200 周年纪念。借用饶毅老师在他文章中的说法：生物学有两座智力高峰：第一次是 1854 年至 1866 年孟德尔独自一人；第二次是 1951 年至 1965 年克里克 (Francis Crick) 及其合作者们。两个高峰碰巧相隔一百年。今天重读孟德尔的论文，追寻孟德尔的思路，思考孟德尔的环境，仍然很有意义。

@wangdepin - 2022年是孟德尔诞辰200周年，同时也是巴斯德诞辰200周年。孟德尔（Gregor Johann Mendel,1822-1884）发现了遗传学定律，找到了决定生命现象的本质；巴斯德（Louis Pasteur,1822-1895）开创了微生物学和免疫学，为人类的健康做出了巨大的贡献。很多学者写了纪念他们的文章，中国遗传学会也专门举办了一系列讲座来纪念这一重要日子，足见孟德尔在生命科学史上的重要地位。详细了解这些伟大科学家在当时所创造的一系列科研重大发现的过程，给我们这些后辈在科研路上带来很大的启发。

## 生信研究


1、[生信研究｜Nat Mach Intell｜基于 AI 算法预测基因组错义变异的功能影响](https://mp.weixin.qq.com/s/F-jDB9tOzCid7j2pjazOgw)



![](https://files.mdnice.com/user/38451/87b4ff33-becc-41c3-9731-9a29399fea1a.png)



美国哥伦比亚大学系统生物学系和生物医学信息学系副教授沈宇锋博士及其团队前博士后张海仓，开发了一种新方法 gMVP 来预测哪些错义变异具有潜在功能影响。gMVP 使用最新的机器学习技术深度图注意力神经网络模型，来抽取相关特征并预测哪些变异具有功能影响。gMVP 方法使用蛋白质中氨基酸 - 氨基酸间的共进化信息来确定不同位置间是否在功能上相关，这使得 gMVP 不仅可以刻画变异所在的一维序列环境，也可以刻画变异所在的蛋白质三维结构环境。研究团队在多个不同的独立数据集上评估了 gMVP 的性能，涉及的应用包括临床基因测试以及致病新风险基因的发现。 在所有测试中，gMVP 的表现明显优于其他方法。

- Paper链接：https://www.nature.com/articles/s42256-022-00561-w

2、[生信研究| 超越 Neural ODE，新机器学习模型显著提升计算速度与性能](https://www.linkresearcher.com/theses/cd942fde-b3b4-496c-805d-603a6386ff0a)



![](https://files.mdnice.com/user/38451/115bc866-ec5d-4b93-9729-8acdbf2b9608.png)



近日，MIT的研究人员在 **Nature Machine Intelligenc**e 杂志上发表论文，提出了一类新的机器学习模型——闭合形式连续时间神经网络（Closed-form continuous-time neural networks，CfC），以闭合的形式逼近神经元和突触之间的相互作用。CfC模型具有因果性、紧凑性和可解释性，在通过运动传感器识别人类活动，模拟步行机器人的物理动力学建模，以及基于事件的序列图像处理方面具有更快的速度和更好的性能。此外，模型还可以帮助建立具有数十亿细胞的大脑计算模型，为理解智能开启新的研究途径。

- Paper链接：https://www.nature.com/articles/s42256-022-00556-7

3、[Clin Chem | PacBio和ONT测序平台对血浆cfDNA分析性能比较成果](https://mp.weixin.qq.com/s/WY_zqjj36g6wFwqqibHByA)

![image](https://user-images.githubusercontent.com/25057508/210954729-a3a63aa3-432f-4f39-866c-9f99e9fb3303.png)

本研究比较了PacBio和ONT测序在血浆cfDNA分析中的应用，分析了来自不同妊娠期的女性、乙型肝炎病毒（HBV）携带者和HCC患者的血浆cfDNA样本。比较了两个平台的测序结果，包括大小和片段末端图谱，以及基于cfDNA单分子甲基化模式的组织来源分析。其中一个发现是，PacBio测序的血浆cfDNA比ONT测序平台得到的更长，PacBio中大于1kb的cfDNA片段比例是ONT的30倍左右。cfDNA片段图谱中，cfDNA短片段有10 bp的周期性峰，这在PacBio的数据中很明显，但在未来研究中，还是很有必要使用非测序为基础的方法进一步验证血浆中长片段cfDNA的存在。（整体上看PacBio在这里是有优势的）

- Paper链接：https://doi.org/10.1093/clinchem/hvac180

4、[Cancer Discov | 肝癌全基因组cfDNA片段化特征检测方法DELFI，可高灵敏度、特异性筛查高危人群](https://mp.weixin.qq.com/s/OSDvfIAueHYLeURsXYvvYg)


![](https://files.mdnice.com/user/38451/06b43a87-8496-477e-8c93-71ab795f75b4.png)

-Paper链接：https://doi.org/10.1158/2159-8290.CD-22-0659


约翰霍普金斯大学研究团队开发出一种基于血液的全基因组cfDNA片段化特征检测方法,对HCC具有高灵敏度和特异性。研究表明片段化概况捕获了基因组和染色质特征，包括已知在HCC中很重要的改变。cfDNA片段化组分析方法“DELFI”是第一个在单独的高风险人群中独立验证的全基因组片段化分析，在检测HCC方面具有稳定和强大的性能，包括非常早期的疾病，且与疾病病因无关。


## 博文资讯

5、[ 20 个更有效地使用谷歌搜索的技巧 ](https://juejin.cn/post/6844903788520669191)


![](https://files.mdnice.com/user/38451/6a9d562f-d447-467f-ac65-44a8d8c17067.png)



我们每天都在用goole搜索，学会一些小技巧更有利于搜索出更好的结果。

6、[为了搞清楚CDN的原理，我头都秃了...](https://mp.weixin.qq.com/s/8IzDE4blQ_yC6z90q55UhA)


![](https://files.mdnice.com/user/38451/8cef0c22-8a30-4640-bb8b-1bc37abb0863.png)


本文深入浅出介绍了CDN的概念、工作原理和缓存策略以及相关名字解释。

7、[重新定义了什么叫摸鱼！](https://mp.weixin.qq.com/s/nGomzsEHQHSpWBLcW9yPCg)



![](https://files.mdnice.com/user/38451/07ce4a51-37a4-4ad1-9b14-8bdc0bd022a5.png)


有人已经开发出gpchatteR包，和机器人聊聊天就把活给干了。

8、[redis入门](https://mp.weixin.qq.com/s/cH5YVGcMp22ZpgSK1kNh3A)


![](https://files.mdnice.com/user/38451/5c999f32-f995-4b2b-ac8d-3bea5eb08e89.png)



Redis 是一个开源（BSD许可）的，内存中的数据结构存储系统，它可以用作数据库、缓存和消息中间件。本文将会从：Redis 使用场景与介绍 -> 数据结构与简单使用 -> 小功能大用处 -> 持久化、主从同步与缓存设计 -> 知识拓展 来进行介绍。

## 工具

9、[Scidown文献下载工具](https://www.scidown.cn/)



![](https://files.mdnice.com/user/38451/e4c15e63-0e1d-4607-a332-295f20521013.png)



Scidown是又一国产文献下载网页工具，注册账号后输入对应的DOI号就能获取大部分文献，感兴趣的小伙伴可以尝试一下~


10、[https://github.com/leiurayer/downkyi ](https://github.com/leiurayer/downkyi )


![](https://files.mdnice.com/user/38451/2dd341cc-d6b2-46d1-9c46-206fd9ab5f7d.png)


哔哩下载姬（DownKyi）是一个简单易用的哔哩哔哩视频下载工具，具有简洁的界面，流畅的操作逻辑。哔哩下载姬可以下载几乎所有的B站视频，并输出mp4格式的文件；采用Aria下载器多线程下载，采用FFmpeg对视频进行混流、提取音视频等操作。



11、[cronologia-创建交互性时间轴](https://github.com/feddelegrand7/cronologia)



![](https://files.mdnice.com/user/38451/cd925474-98c4-436b-94d6-ce8562167a2e.png)



cronologia的目标是在RMarkdown文档和Shiny应用程序中创建一个交互式时间轴小部件。


12、[R 包 - Sigminer](https://github.com/ShixiangWang/sigminer)


![](https://files.mdnice.com/user/38451/44070321-a782-459b-a101-35d6e3ca2ecc.png)


Sigminer 是一个一站式的癌症基因组变异模式（Mutational Signature）分析工具，提供了对多种变异类型（SBS、DBS、INDEL、CNV、Rearrangement）和多种计算解析算法的支持（NMF、SigProfiler 等），可以通过 GitHub/CRAN/Bioconda/Docker 等途径下载和使用。

- 包文档：https://shixiangwang.github.io/sigminer-book/
- 函数文档：https://shixiangwang.github.io/sigminer/reference/index.html

## 资源
13、[爱思唯尔出版社课程 | 成为有资质的审稿人](https://researcheracademy.elsevier.com/navigating-peer-review/certified-peer-reviewer-course)



![](https://files.mdnice.com/user/38451/47641569-4647-4952-a099-f72350fb5c1f.png)



爱思唯尔出版社开设的关于如何成为一个合格的审稿人的课程，总共分为12个模块，总计约4小时左右。
![](https://files.mdnice.com/user/38451/42907593-78cd-4a01-8da9-f33465f10acb.png)

![](https://files.mdnice.com/user/38451/691bb929-3285-4b0f-90d8-67abddcf471a.png)
 


14、 [远程工作岗位资源推荐](https://github.com/remoteintech/remote-jobs)



![](https://files.mdnice.com/user/38451/5e0b36aa-6a76-40aa-b592-9818db9848ff.png)



一个github仓库以及网站，包含互联网相关公司远程工作或者半远程工作岗位。希望这样的岗位越来越多，特别是生信相关的。


15、[https://github.com/jiqizhixin/Artificial-Intelligence-Terminology-Database](https://github.com/jiqizhixin/Artificial-Intelligence-Terminology-Database)


![](https://files.mdnice.com/user/38451/1c9cb893-50d0-44aa-b77a-0ec68074b7a3.png)


人工智能领域英中技术词汇的综合映射数据库。本术语库目前拥有专业术语约 2442 个、专项领域篇 2 篇，主要为人工智能领域基础概念和术语。

## 历史上的本周

- 2022年：[第 20 期：科研苦行](https://mp.weixin.qq.com/s/ylmCWaJlF2g-DQ7YCbos3g)

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

