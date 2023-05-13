这里记录每周值得分享的生信相关内容，周日发布。 

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。 

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo "「生信周刊讨论区（语雀）」") | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community "「生信讨论区（Gitter）」")

## 封面图

![](https://files.mdnice.com/user/5208/d1cd33aa-6e56-426d-8a28-8f588a289ecd.png)
[图片:A critique of academic criticism](https://medium.com/bits-and-behavior/a-critique-of-academic-criticism-fce30c73947d "图片:A critique of academic criticism")

## 本周话题：[学术需要批判氛围](https://mp.weixin.qq.com/s/xdoL9pe3jOfxhnQFk4hkiQ)


> 我们的大学和学术界普遍缺乏批判氛围，这既有历史文化传统中长者为尊的因素，也有大学教师自身原因。正如钱理群先生提到某些中国知识分子的精致主义，就是只顾自己利益，凡是对我个人不利的事情坚决不做，而批评别人，尤其是批评某些权威人士往往就会伤害到自己。事不关己高高挂起，明哲保身是精致主义的典型特征，这与批判精神相悖。

@He-Kai-fly - 只有把握好学术批判利弊之间微妙的客观思想和个人情感的平衡，个人和社会才能有所进步和提高。

## 生信研究

1、[Cancer Discovery | 多区域单细胞测序解析肺腺癌的空间和细胞结构](https://mp.weixin.qq.com/s/ldAdS3AXH4NnnZDAqYLztA)


![](https://files.mdnice.com/user/5208/7cf22214-feaa-406f-8cbe-67b7fca2264d.png)

> 德克萨斯大学安德森癌症中心的研究团队利用单细胞测序技术系统地研究了人早期肺腺癌（lung adenocarcinoma，LUAD）组织及癌旁和远端肺样本的单细胞数据，构建了肺上皮细胞、免疫细胞等其他多个细胞群体的转录组学数据集，揭示了早期肺癌演化的特征，为研究LUAD演化轨迹和制定早期肺癌治疗策略提供了宝贵资源。感谢董炜投稿。


- 论文链接：https://aacrjournals.org/cancerdiscovery/article/11/10/2506/665617/Resolving-the-Spatial-and-Cellular-Architecture-of

2、[Nature Machine intelligence| 华大智造研发团队发布基于对比学习的多模态单细胞算法，快速实现千万级单细胞多组学数据建模](https://github.com/ShixiangWang/weekly/issues/964 "Nature Machine intelligence| 华大智造研发团队发布基于对比学习的多模态单细胞算法，快速实现千万级单细胞多组学数据建模")

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202305092158345.png)



> 近日，**华大智造研发团队**在**Nature Machine intelligence**（IF=25.898）上在线发表了题为“Contrastive learning enables rapid mapping to multimodal single-cell atlas of multimillion scale”的研究成果。研究人员开发了一种基于对比学习的多模态单细胞算法工具——Concerto（协奏曲）。”协奏曲”的命名， 既包含了“对比学习建模细胞表征”的英文首字母，又暗含了组织器官中不同类型、不同状态的细胞协同发挥作用之意。**该算法通过自监督训练的方式，可快速对千万级无标注的单细胞多组学数据进行建模，得到的细胞表征（cell embedding）可以用于自动注释、多模态整合、聚类、跨批次整合、参考映射注释等下游应用**。目前，Concerto在各项任务都展现了优异的性能，进一步丰富了单细胞大数据领域的算法工具。

- 论文链接：https://www.nature.com/articles/s42256-022-00518-z


3、 [Nature发布15万人全基因组测序研究成果，揭示多个罕见变异的性状关联](https://mp.weixin.qq.com/s/79DlODtn6nakGJpf_TOiNQ)

![](https://user-images.githubusercontent.com/13445428/235963109-c1de1e4b-eb22-44df-8fba-5d4c758fb961.png)

> 冰岛雷克雅未克大学联合deCODE Genetics公司、安进公司等团队对来自英国生物银行（UKB）的150119个个体的WGS数据进行分析，重点介绍了发现的具有较大影响的罕见变异性状关联，这些信息是WES和SNP阵列数据集难以鉴定或无法鉴定的。这是迄今规模最大的全基因组测序工作。该研究结果已发表Nature上。

- 论文链接：https://www.nature.com/articles/s41586-022-04965-x

4、[Nat Med | 基于73万人遗传和健康数据揭示遗传风险因素对寿命的影响](https://mp.weixin.qq.com/s/mgEimL558jbX6OWPbKmNCw)

![](https://files.mdnice.com/user/5208/3fdd0f8f-34ae-423e-9429-72c8b6477378.png)

> 芬兰赫尔辛基大学FIMM分子医学研究所的研究团队将来自两项生物库研究的80种疾病的遗传关联结果与2019年GBD研究的DALY预估值相结合，阐述了遗传变异对个人和群体层面上健康寿命年数损失的影响。该研究将不同的遗传风险因素按其对健康的影响进行排序，并将遗传风险因素与传统的可改变风险因素进行比较，提出了遗传风险因素的比较风险评估模板。
- 论文链接：https://www.nature.com/articles/s41591-022-01957-2


5、[Nat Commun | 利用机器学习准确分析FFPE样本的基因组学特征，解锁临床癌症样本的遗传密码](https://mp.weixin.qq.com/s/nS2VvRCPa_NsPaDc2KjJLw)


![](https://files.mdnice.com/user/5208/8961bddc-9d9d-47d4-a861-4384669b82dc.png)


> 美国赫尔辛基大学研究团队从FFPE样本中提取了福尔马林暴露导致的全基因组突变特征，并设计了FFPEsig算法。该算法能够准确分析癌症活检FFPE样本中基因组学数据，使用机器学习方法校正了受损DNA，并揭示肿瘤样本中真正的突变过程。该方法能够对FFPE样本进行稳健的突变特征分析，从而为使用FFPE-WGS数据进行临床应用铺平了道路，有助于在数百万现有癌症储存样本中释放巨大的医学价值。

- 论文链接：https://www.nature.com/articles/s41467-022-32041-5

## 博文咨询
6、[Wasmtime 1.0 正式发布：快速、安全、可用于生产环境](https://github.com/ShixiangWang/weekly/issues/1027 "Wasmtime 1.0 正式发布：快速、安全、可用于生产环境")


![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202305092220646.png)
> 历经三年开发，Bytecode Alliance（字节码联盟）宣布 WebAssembly runtime —— Wasmtime 1.0 正式发布，并可用于生产环境。Wasmtime 是 Bytecode Alliance 开发的 WebAssembly runtime，采用 Rust 编写，构建于编译器 Cranelift 之上。Wasmtime 完全开源，符合 WASI 标准，还支持与 C/C++、Python、.NET、Go 和其他编程语言集成，可运行在 Windows/Linux/macOS 等平台。

- Release Process: https://docs.wasmtime.dev/stability-release.html
- 发布公告：https://bytecodealliance.org/articles/wasmtime-1-0-fast-safe-and-production-ready



7、[使用TPM/FPKM/RPKM进行差异分析真的可以消除系统误差吗？](https://mp.weixin.qq.com/s/L5ikz6qmCTSoO4ut4ahQvg)


![](https://files.mdnice.com/user/5208/068909c5-2397-4d33-8c92-92de60eeffe6.png)


> 本文通过解读一篇文章探索差异表达分析一个比较有意思的数据科学问题：虽然TPM/FPKM/RPKM是一种“全局归一化”，在理论上可以消除线性系统误差。但是，研究者认为这种假设对组学数据分析来说太天真了，并且强调组学数据的非线性系统误差没有生物信息学方法可以消除，并以GSE159751为例进行了相关分析。


## 工具
8、[3D图解神经网络](https://mp.weixin.qq.com/s/30SivE60s4bbqJRWuX1fcQ)  


![](https://files.mdnice.com/user/5208/d3352a74-b1cd-423b-9faf-0c3ec83b84a9.png)


> 一位来自维也纳的3D特效师创建了一个CNN可视化工具。该工具的主要功能包括，卷积、最大池化和完全连接层的可视化表示，以及各种能实现更清晰可视化的简化机制等等，让初学者通过最直观的方式，来get到CNN的重点。

- Github: https://github.com/julrog/nn_vis

9、[cellRatioPlot 浅浅的画个细胞比例](https://mp.weixin.qq.com/s/ZZ2IIvOTp1Vp0r9t9fJ_4w)


![](https://files.mdnice.com/user/5208/346f31b0-c7f3-4027-a8bd-277c7be66c5e.png)


本文介绍了 scRNAtoolVis 包新增的一个可视化功能，方便用户快速绘制美观的单细胞常见比例图形。  

## 工具
10、[使用G2.js交互可视化图形](https://github.com/devOpifex/g2r "使用G2.js交互可视化图形")

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202305092256423.png)


> g2r是G2.js JavaScript可视化库的接口。G2.js本身就是一个图形语法(GG ~= 2G)，尽管在某些方面与R对ggplot2中实现的语法的一般理解有所不同，但有些地方与ggplot2类似。



- Github: https://github.com/devOpifex/g2r
- Get start: https://g2r.opifex.org/articles/get-started.html  

11、 使用brename对文件批量重命名

> brename是一个跨平台命令行工具，其可以通过正则表达式安全地批量重命名文件或目录。


![](https://files.mdnice.com/user/5208/fb1e0108-2cfd-4f63-878d-9f9c52daef31.png)

链接：https://github.com/shenwei356/brename


## 资源
12、[工具 | AI大神李沐开源新手剪辑神器！只看字幕就能剪视频，卡壳重复片段一键删除](https://zhuanlan.zhihu.com/p/581800816 "工具 | AI大神李沐开源新手剪辑神器！只看字幕就能剪视频，卡壳重复片段一键删除") 


![](https://files.mdnice.com/user/5208/d288d905-0c70-4590-925f-feae38273e48.png)

> AL大神李沐最近开发了一款软件-AutoCut。它可以对视频自动生成字幕，接下来，用户就可以对照字幕，将空白停顿、反复重读的地方进行删除，AutoCut也将自动对视频中对应的片段裁切并保存。该软件使用户无需使用视频编辑软件，只需要编辑文本即可完成剪切。

13、[helix：一个基于Rust的文本编辑器](https://helix-editor.com/ "helix：一个基于Rust的文本编辑器") 


![](https://files.mdnice.com/user/5208/93fc9e6d-77fd-46e1-8f06-89f9410ba6c9.png)


> helix是一个基于Rust的文本编辑器，其类似 Vim 的模态编辑，并支持多选、通过树形定位器进行智能的增量语法突出显示和代码编辑等功能，并内置语言服务器。  
## 资源
14、[一次搞定所有的富集分析](https://mp.weixin.qq.com/s/17ItITYzILmWv_Hcs80fAA)

![](https://files.mdnice.com/user/5208/9cecb158-727b-4e75-a13a-8818a520cb55.png)

`gson包`可一次搞定所有的富集分析。

15、[人人都能用英语](https://github.com/ShixiangWang/weekly/issues/1219 "人人都能用英语")


![](https://files.mdnice.com/user/5208/618ddcf5-b2f7-4803-bfe0-8c1a74682e5a.png)


> 李笑来写的关于如何学习以及使用英语的小册子，李笑来虽然因为在币圈割韭菜的事情风评不好，但是他一直在学习，并且持续输出的能力还是值得学习的，这个小册子可以翻翻。

16、[scRNA-seq相关工具和基因组数据分析资源](https://github.com/mdozmorov/scRNA-seq_notes "scRNA-seq相关工具和基因组数据分析资源")


![](https://files.mdnice.com/user/5208/51657f1a-6c05-4cb3-b342-9d15d4e3fef9.png)

网站归类整理了各种单细胞测序和基因组数据相关的出版资料和工具，方便读者挑选感兴趣的内容阅读学习。


## 历史上的本周
第34期：[中国百万人群大队列，何去何从](https://shixiangwang.github.io/weekly/issue-34/ "生信爱好者周刊（第34期）：中国百万人群大队列，何去何从")

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

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

