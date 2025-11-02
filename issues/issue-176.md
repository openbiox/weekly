# 生信爱好者周刊（第176期）：有组织科研，是不是学阀大杀四方，片甲不留？

这里记录值得分享的生信相关内容，每半月发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")
 
## 封面图  

![](https://files.mdnice.com/user/143074/fc635e0c-2467-4935-be68-e0287e196044.jpg)

## 本周话题：[有组织科研，是不是学阀大杀四方，片甲不留？](https://mp.weixin.qq.com/s/6CDn4D8gKWWraD6cju4-7g)
> 科研人员太多单打独斗，无法集中优势资源，优化配置。而如华为这般大型企业，通过各方资源整合，在科技、成果、经济等方面都走在了前列。换个角度来讲，也许，是科研人员更需要有组织科研，来完整的实现科研价值，成为可以站上庆功宴的人。    

## 生信研究

1、[Science | 异常克隆扩张驱动肺癌早期演变](https://mp.weixin.qq.com/s/8U3pM2cxVRnpmRgJEUOjpA)

![](https://files.mdnice.com/user/143074/ce1f3b50-c6e3-446f-be55-e16645d0139f.jpg)

基底细胞是气道上皮的主要组成部分，且其标志物如KRT5和p63在LUSC中广泛表达，因此被认为可能是LUSC的起源细胞。研究发现，致癌物暴露导致肺基底细胞发生异常的克隆扩增和迁移，少数高度突变的克隆在支气管区域主导并形成癌前病变。通过多点测序，验证了这些病变之间的克隆相关性，揭示了基底细胞克隆动态和命运转变是肺部“癌变场域效应”的关键驱动因素。    
- 论文链接：https://www.science.org/doi/10.1126/science.ads9145

2、[Cell |李汉杰团队利用单细胞测序技术发现与体型大小相关的免疫细胞：外周小胶质细胞](https://mp.weixin.qq.com/s/KYcmizQGt54CZBcDm2eISQ)  

![](https://files.mdnice.com/user/143074/c0b2700f-9b12-4c2a-90ab-72cd948962ac.png)

该研究通过跨物种、高时空分辨率的单细胞转录组测序技术，结合多组学分析手段，首次在外周神经系统中发现了一群与中枢神经系统小胶质细胞具有相同分子特征、且与物种体型大小相关的小胶质细胞，并将其命名为PNS microglia。
- 论文链接：https://www.sciencedirect.com/science/article/abs/pii/S0092867425001928    

3、[ChatNT：首个支持DNA/RNA/蛋白的生物ChatGPT来了！](https://mp.weixin.qq.com/s/kXd3k30tutofiQRyC7BgFQ)   

![](https://files.mdnice.com/user/143074/3ec65b4c-08ac-4514-821d-9d1bdc397d55.jpg)

该研究介绍了由InstaDeep和BioNTech联合推出的全新生物AI助手——ChatNT。ChatNT 让生物序列第一次“说人话”，也让科研人员第一次不写代码就能高效提问基因组。它是生物界的 ChatGPT，正在开启通用生物智能助手的新时代。
- 论文链接：https://www.nature.com/articles/s42256-025-01047-1

## 博文资讯
4、[Transformer到底解决什么问题？](https://mp.weixin.qq.com/s/BxpWFwXFbpur_gTuzSEsSA)

![](https://files.mdnice.com/user/143074/fa4bfc79-71e8-4fca-b0f8-00437fad6b31.jpg)

本文希望围绕“Transformer到底是解决什么问题的”这个角度，阐述NLP发展以来遇到的关键问题和解法，通过这些问题引出Transformer实现原理，帮助初学者理解。   

5、[基因选择压力分析 | Ka/Ks, Dn/Ds 大规模计算，更快更准！](https://mp.weixin.qq.com/s/3JiDuTRLjvvcZLuX8uo4mQ)   

![](https://files.mdnice.com/user/143074/10add087-9b96-4c3a-b0e4-b062178ff3da.png)

本文介绍了TBtools软件中基因对Ka/Ks计算功能的高效实现方案。与传统Emboss Needle程序或常见的MUSCLE调用方案相比，TBtools通过自研算法实现了速度的百倍提升，将万对基因的计算从数小时缩短至一分钟内，并在速度与准确性上取得了最佳平衡。

6、[使用corrplot包绘制相关性图及美化](https://mp.weixin.qq.com/s/GeVREhz2h9A8KM6DdaeoaQ)  

![](https://files.mdnice.com/user/143074/b08580e7-1cbb-47ec-9553-a555a5944ec0.png)

本文介绍了R包corrplot，其提供了多种相关矩阵可视化方法，支持显著性检测、矩阵重排序以及置信区间展示，适用于生物信息数据的探索性分析。

7、[ggtreebar 绘制条形树图](https://mp.weixin.qq.com/s/B9m_KiAU4KiqX-0Yb0yY6g)


![](https://files.mdnice.com/user/143074/cad6f3b8-1f56-4118-a6c7-512d0c73c165.png)

本文介绍了用于绘制条形图的R包ggtreebar的基本用法，提供了一种简洁有效的方式来展示数据的层次结构。

## 工具   
8、[三维太复杂？FlatProt上线：用二维“展平”蛋白质结构，精准比对一目了然！](https://mp.weixin.qq.com/s/gGHnX2uJU8LKJ68esWcuQw)

![](https://files.mdnice.com/user/143074/5491cd34-2494-43a3-944b-78ab758413dc.png)

FlatProt是一款用于将蛋白质三维结构转化为标准化二维图形的开源工具。它通过快速的结构对齐和简化，可帮助科研人员高效地进行蛋白家族的结构比对与保守性分析，支持快速生成高质量SVG图形，适用于AlphaFold结果分析、结构域演化研究等多种场景。   
- 工具链接：https://github.com/t03i/FlatProt    
- 文章链接：https://www.biorxiv.org/content/10.1101/2025.04.22.650077v1.full.pdf  

 9、[告别 LaTeX 排版烦恼：TeXtidote，你的智能代码矫正写作伙伴！](https://mp.weixin.qq.com/s/qDA1qTcy6FymJHgPUYPGiQ)   
 
![](https://files.mdnice.com/user/143074/0690d478-ceb9-407c-8404-869eae242c80.png)

TeXtidote 是一款专为 LaTeX 文档设计的智能校对工具，能精准进行拼写、语法检查，并支持 LaTeX 特有的内容，如图表引用和标题规范。它通过命令行运行，支持多种输出格式，帮助用户高效提升文档质量，简化写作过程。
- 工具链接：https://github.com/sylvainhalle/textidote    

10、[MTiOpenScreen: 一个在线虚拟筛选平台](https://mp.weixin.qq.com/s/3cx3SnEIsBssYHslCMEpAg)

![](https://files.mdnice.com/user/143074/3a393be1-745f-46f0-a5c0-960bb5b679fa.png)

MTiOpenScreen 是一个在线虚拟筛选平台，提供基于 AutoDock 和 AutoDock Vina 的两大核心服务：MTiAutoDock（小分子对接）和 MTiOpenScreen（化学库虚拟筛选）。它支持用户上传自己的分子库或选择预定义的药物库，支持最多 5000 个分子的筛选。   

## 资源   
11、[ggplot-extension-club](https://github.com/ggplot2-extenders/ggplot-extension-club "ggplot-extension-club")   

![](https://files.mdnice.com/user/143074/a025ef35-d0a2-435b-b888-24d2246a6c87.png)     

一个专为ggplot2扩展开发者提供的资源库，包含插件介绍、开发文档和最佳实践等。    

12、[NODESCHOOL](https://nodeschool.io/ "NODESCHOOL")

![](https://files.mdnice.com/user/143074/d4cb02d1-2938-4e69-be87-06ea51183a2a.png)

一个基于Node.js的开放式技术学习平台。它提供了一系列交互式命令行教程作为核心学习资源。这些资源覆盖了从JavaScript、Node.js基础到Git、npm、Electron等全栈开发的系统化课程，所有课程均可通过npm命令免费安装并支持离线学习。