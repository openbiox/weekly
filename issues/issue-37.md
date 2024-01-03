---
date: 2023-03-15
comments: true
---

# 生信爱好者周刊（第 37 期）：抛弃“影响”因子，计算颠覆因子！

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图


![](https://files.mdnice.com/user/4331/aa6a4169-fe9f-408b-b3f8-27343e94062d.png)



## 本周话题：[抛弃“影响”因子，计算颠覆因子！](https://blog.sciencenet.cn/home.php?mod=space&uid=472757&do=blog&id=1345692)

> 颠覆因子（Disruption）是Wu，Wang和Evans在2019年的Nature的文章推出的。这个因子是指引用了该论文，但没有引用该论文所引用的论文的论文数（ni）减去那些同时引用了该论文及该论文所引用论文的论文数（nj），然后用引用该论文的论文数(ni+nj)加上那些没有引用该论文却引用了该论文所引用论文的论文数(nk)来归一`[D=(ni-nj)/(ni+nj+nk)]`。这个颠覆因子可以衡量一篇论文是后来工作的起点（原创性工作，D～1），还是研究工作发展中的中转站（跟风、发展性工作，D～-1）。他们用诺贝尔获奖论文（高颠覆因子）、综述论文（低颠覆因子）、专家的调查、关键词汇的使用验证了颠覆因子的可靠性。

`ShixiangWang`：研究前沿的演进是快速的，但习惯和范式的转变却是间断/阶段性的，更多学术评价指标的的开发和提出有利于丰富学术圈的群体意识，不过任何指标都有其利弊，未来是否通用性地适配还是不同领域百花齐放都尚未可知。

## 生信研究

1、[Nature | 世界首个全年龄段人脑发育图谱](https://mp.weixin.qq.com/s/v7MPciKHuwoYnwW_D5L1yw)


![](https://files.mdnice.com/user/4331/b499de2f-85ae-4019-bfa2-7882b9f7b1b2.png)

本研究对101457名不同年龄层次人群（从受孕后115天到100岁）的123984次MRI数据进行分析，定义了大脑与年龄相关的变化特征，绘制了世界上首个涵盖整个年龄段的人脑发育图谱，识别出了多个此前未被报道过的脑生长发育关键时期，并且发现多种疾病患者（如阿尔茨海默病与精神疾病）的脑结构与正常人群存在不同。据了解，这是迄今最大规模的神经影像学研究，为神经科学研究提供了重要的参考资源。

论文链接：<https://www.nature.com/articles/s41586-022-04554-y>


2、[Nature Communication | 生物科学领域应用深度学习的当前进展和公开挑战](https://mp.weixin.qq.com/s/NW6mKEIC3POK1LZc6OEN4g)


![](https://files.mdnice.com/user/4331/47374231-43ac-488f-874f-add54de939b3.png)

该综述从蛋白质结构预测、蛋白质功能预测、基因组工程、系统生物学、数据整合以及系统发生学这五个方面论述了应用深度学习进行上述领域研究的最新进展、现有瓶颈和未来前景。

论文链接：<https://www.nature.com/articles/s41587-022-01261-x>


3、[Nature Communication | 将核酸绝对定量用于同一样本拷贝数变异和突变检测的新技术——QASeq](https://mp.weixin.qq.com/s/0J5v4As_bHmH2JUrXjADWQ)


![](https://files.mdnice.com/user/4331/828c7fe8-295b-4023-9d43-cff8d21aec13.png)

QASeq是一项可精确测定拷贝数变化（CNV）的新技术。与被认为“金标准”的数字PCR技术相比，QASeq在单个位点的检测上表现出了更好的灵敏度和稳定性，可以从有限的FFPE组织样本和cfDNA 中检测到低至5%杂合单拷贝扩增或缺失的 CNV，以及低至0.1% 变异等位基因频率 (VAF) 的突变，且这种精确定量可以同时靶向上百个位点甚至更多。其在临床应用和RNA表达谱靶向预测方面的潜力很大。

文章链接：<https://www.nature.com/articles/s41467-022-29487-y>


4、[QB | 人物 - 李衍达院士：永不止步的先驱者、探索者与奠基人](https://mp.weixin.qq.com/s/Evfp-mUnqbrCByA9tOt1JQ)


![](https://files.mdnice.com/user/4331/73a242bb-84b5-4370-b08e-2ffafa370de8.png)

今年是李衍达院士86岁诞辰。虽然他已于2018年正式退休，却仍然积极参与学术活动，与年轻教师和学生们讨论。他提出，从数据中理解复杂生命系统的关键是发现看似无关的数据中潜藏的关联。他经常建议年轻的研究人员不要被学科界限禁锢了想象力，不要害怕思考没有人涉足过的问题和解决方法。过去的60年里，李衍达院士指导了超过100多名研究生，其中的许多学生现已成为全球多所顶尖大学的老师，还有学生已成为相关领域的行业领导者。


## 博文资讯

5、[免疫治疗队列数据IMvigor210CoreBiologies包](https://mp.weixin.qq.com/s/ncWZ_MkI3TK7S43GN8L-MQ)


![](https://files.mdnice.com/user/4331/50a0d974-e36b-4357-b610-a129c99fdcb9.png)

发表在nature上的尿路上皮癌（BLCA）的免疫治疗队列数据，太贴心了！！！数据和每张图的代码都给了！！！很好的学习素材，快来试试自己研究的基因与免疫治疗的疗效有没有相关性，给论文凑张图。

- 论文链接：<https://www.nature.com/articles/nature25501>
- R包介绍：<http://research-pub.gene.com/IMvigor210CoreBiologies/>


6、[ggcharts 快速绘制优美图形](https://mp.weixin.qq.com/s/_WrCrj0JGs7DuxH45WQojg)


![](https://files.mdnice.com/user/4331/db5c50ae-ef65-422d-bdb7-a234a0126cc6.png)


本文介绍了如何使用ggcharts包简单快速绘制一些常用的Figure。

Github: <https://github.com/thomas-neitmann/ggcharts>

7、[使用R包PreMSIm根据基因表达量来预测微卫星不稳定](https://mp.weixin.qq.com/s/QgDNZ-_ewKKGb-8uHUYoiQ)


![](https://files.mdnice.com/user/4331/02282469-3660-4b4f-9505-ecc5c254a526.png)

通过TCGA转录组数据和临床信息-微卫星不稳定（MSI）构建模型，预测样本微卫星不稳定。思路清晰，代码简洁，对初学者很友好，可以模仿作者思路构建模型，开启你的机器学习之旅。

还有曾老师的作业：任意选择TCGA的一个癌症，做一个类似的分类模型，可以是区分癌症样品和对照组织，也可以是区分不同TMN分期分级的癌症，或者是不同的分子分型哦！

- 论文链接：<https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7113609/>
- R包介绍：<https://github.com/WangX-Lab/PreMSIm>

8、[生物学家掌握机器学习指南 - AI](https://mp.weixin.qq.com/s/aVopzi9grSwAe-BZ6LdsXg)


![](https://files.mdnice.com/user/4331/7308ea26-d694-47a7-9598-2c4231641a2a.png)

本次学习指南的内容为人工神经网络。指南将从概念、基本原理、训练和改进等方面入手，并介绍四种经典的人工神经网络。




## 工具

9、[Notero - Zotero插件连通Zotero和Notion](https://github.com/dvanoni/notero)


![](https://files.mdnice.com/user/4331/e2169405-1b34-4b26-822e-2346365c6191.png)


10、[khroma](https://github.com/tesselle/khroma)


![](https://files.mdnice.com/user/4331/9438872c-f746-49f8-bc58-4001b51e1047.png)

做图不仅是一种艺术，也是一门颇深的科学。如何将图画的即美观又对更多人友好，就是本R包的宗旨。Khroma提供了 Okabe ， Ito , Tol，Crameri这些主题配色方案，意在使绘出图片对色盲患者更加友好。


11、[r-minimal - 最小R docker镜像](https://github.com/r-hub/r-minimal)


![](https://files.mdnice.com/user/4331/8a4b12e5-3932-498b-ae92-225a83391a25.png)


12、[quarto](https://quarto.org/)


![](https://files.mdnice.com/user/4331/4f6bb930-18ac-4729-b2bd-59f8105f01e7.png)

官网：<https://quarto.org/>

Quarto是一个基于Pandoc的开源科研出版系统，设计初衷是为了摆脱Rmarkdon对特定编程语言的依赖，用户可通过qmd文档的yaml自由选择python、Julia和Observable等其它多种语言创建动态内容编译文档 ，并允许转换为多种输出格式。


13、[ecotyper](https://github.com/digitalcytometry/ecotyper)


![](https://files.mdnice.com/user/4331/7d1a6e8b-7df4-4ac4-a17e-da26952c1f4a.png)


[EcoTyper](https://ecotyper.stanford.edu/)是一个机器学习框架，用于从批量和单细胞(scRNA-seq)表达数据中大规模识别细胞类型特异性的转录状态及其共同关联模式。


14、[restic - 快速、安全、高效的备份程序](https://github.com/restic/restic)


![](https://files.mdnice.com/user/4331/897f0a27-357d-4036-93bc-b222f6bc8b4b.png)


15、[easyScholar](https://github.com/Nixiak-nan/easyScholar)


![](https://files.mdnice.com/user/4331/31d87556-d6a4-47ce-89fc-58435a1f1c5d.png)

官网：<https://easyscholar.cc/>

一款专为科研人员设计的浏览器插件，宗旨: 简洁、高效、好用！

主要功能：

- 【显示会议、期刊等级】各大论文搜索网站上，显示各种会议、期刊等级;
- 【在线翻译】在所有网站上，提供简洁的一键翻译功能；
- 【文献管理】提供轻量的文献管理功能，快速的为文献添加类别；
- 【刊物等级查询】便捷的查询某个刊物在各大数据集中的数据。



## 资源

16、[机器学习陷阱](https://github.com/shwhalen/ml-pitfalls)


该资料为文章*Navigating the Pitfalls of Applying Machine Learning in Genomics*的笔记本，描述了基因组学中应用机器学习算法的常见陷阱。


![](https://files.mdnice.com/user/4331/6a8935c5-4284-46a3-bece-8da4369bae74.png)


17、[figdraw - 绘制你的研究模式图](https://www.figdraw.com/static/index.html#)


![](https://files.mdnice.com/user/4331/c22fafd7-131f-4fef-bff7-bed7f290a187.png)



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

