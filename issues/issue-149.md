---
date: 2024-12-01
comments: true
---
# 生信爱好者周刊（第 149 期）：人类细胞图谱计划

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/33257/f27f5d18-3c7f-44af-9d42-7a152fe73966.jpg)
人类细胞图谱计划最新成果登Nature封面

## 本周话题：人类细胞图谱计划

@kkjtmac  HCA计划对于理解人类生物学和疾病具有深远的意义，它有助于揭示细胞功能、发育过程以及疾病状态下的细胞变化。HCA对数据共享的重视，不仅促进了科学发现，也为人工智能和计算工具的发展提供了丰富的资源。最近Nature发表的一篇《A cell atlas foundation model for scalable search of similar human cells》也是充分结合利用该项目的成果。

## 生信研究
1、[Nature Communications | 基于深度生成模型（PRnet）进行新化合物扰动转录响应预测加速药物研发](https://mp.weixin.qq.com/s/AQaMsDj1bEWZ4jYEYYJnzA)

![](https://files.mdnice.com/user/33257/be43b2e6-2ed3-4aff-8101-44c7300a359d.jpg)

中国科学院赵屹教授团队和四川大学杨胜勇教授团队合作开发了基于深度生成模型PRnet的新化合物扰动转录响应预测模型，该模型的基本原理是利用深度生成模型，通过编码器-解码器架构来预测新化合物对细胞转录响应的影响。它包括扰动适配器、扰动编码和扰动解码器三个关键组件，能够将化合物结构、剂量信息与未受扰动的转录谱作为输入，预测扰动后的转录响应变化。PRnet在大规模高通量筛选数据集上进行训练，确保了其在面对未知疾病和化合物时的准确性和泛化能力。

- 论文链接：https://www.nature.com/articles/s41467-024-53457-1


2、[Cell | 开发CRISPR-Cas13筛选技术并鉴定人类必需lncRNA](https://mp.weixin.qq.com/s/atgr-e2zY4tqdo4wYxUgjQ)

![](https://files.mdnice.com/user/33257/34137c33-ff87-403c-9f78-7fa2a179a99c.jpg)

纽约大学Neville E. Sanjana团队在《Cell》杂志上发表的研究中，开发了一种CRISPR-Cas13系统，用于在转录组层面上进行大规模RNA靶向筛选，成功鉴定出778个对人类细胞生存至关重要的长链非编码RNA（lncRNA）。这项技术允许研究者以更高的特异性干扰lncRNA，避免了传统CRISPR-Cas9技术可能影响附近基因的问题。研究发现，这些必需lncRNA显示出细胞类型特异性，与蛋白质编码基因的必需性相比，它们在不同细胞系之间的共享性较低。此外，这些lncRNA在发育和癌症进展中扮演着重要角色，它们的表达变化与特定肿瘤类型的生存率相关，为未来的生物标志物发现和治疗靶点识别提供了新的视角。这项研究不仅加深了我们对lncRNA功能的理解，也为非编码RNA的系统性研究提供了强大的工具。

- 论文链接：https://www.cell.com/cell/fulltext/S0092-8674(24)01203-0

3、[Nature | 肿瘤从多克隆至单克隆转变的早期演化新模式](https://mp.weixin.qq.com/s/yTepOGa-IbqiTmMGnHR1Cw)

![](https://files.mdnice.com/user/33257/5fd5948d-06e1-44ae-8b5a-c44a16aee142.png)

理解肿瘤的早期发生机制，对实现肿瘤的早期精准筛查和防治至关重要。对早期肿瘤起源和发生机制的认识不足，极大地限制了我们在肿瘤精准筛查和早期干预上的突破。研究团队首次在哺乳动物中建立了基于碱基编辑器的细胞谱系示踪技术（称为SMALT），实现了小鼠体内单细胞分辨率的高精度谱系追踪。SMALT技术结合了胞苷脱氨酶（AID）、人工DNA条形码序列和Tet-On可诱导表达系统，通过AID介导的靶向突变和后续DNA测序，能够大规模、高精确地重建单细胞谱系树（图1a）。研究团队利用携带SMALT系统的转基因小鼠，构建了两种小鼠肠癌模型：炎症诱导肠癌模型（AOM/DSS模型）和多发性息肉模型（ApcMin/+模型）。基于高分辨率谱系树分析，团队发现大多数（66.7%）炎症诱导的早期肠癌和所有Apc息肉均表现出多克隆起源（图1b）。通过整合DNA条形码测序、全基因组测序和单细胞转录组数据，研究团队进一步发现单克隆肿瘤（图1c）比多克隆肿瘤具有更高的恶性程度，这表明单克隆肿瘤可能代表肿瘤发生的更“晚期”阶段。基于这些发现，团队提出了肿瘤发生的“多克隆向单克隆转变”新模型（图1d），为早期肿瘤演化提供了新的理论框架。

- 论文链接：https://www.nature.com/articles/s41586-024-08133-1

4、[Nature Genetics | 基于62.6万个细胞构建迄今最全面的人类子宫内膜单细胞综合参考图谱](https://mp.weixin.qq.com/s/4U5hDF5S5CX5bEOEh170EA)

![](https://files.mdnice.com/user/33257/953e3625-d8a3-4f6b-9300-1b9679cbfc31.jpg)

英国Wellcome Sanger研究所和牛津大学的研究者们在《Nature Genetics》上发表了一项突破性研究，创建了人类子宫内膜单细胞参考图谱（HECA），涵盖了62.6万个细胞，是迄今为止最全面的图谱。该图谱不仅揭示了多种之前未发现的细胞类型，还详细描述了这些细胞在月经周期中的动态变化。研究发现，蜕膜化基质细胞和巨噬细胞可能在子宫内膜异位症中失调，为理解子宫内膜异位症的病理提供了新见解。HECA的建立为子宫内膜生理学和疾病研究提供了一个重要工具，有助于开发与生理相关的人类子宫内膜体外模型系统。

- 论文链接：https://www.nature.com/articles/s41588-024-01873-w

## 博文资讯
5、[单细胞Ro/e分析学习和整理](https://mp.weixin.qq.com/s/MYIGKrskIWp5FXhSQffSYA)

![](https://files.mdnice.com/user/33257/245d18b9-e556-4a3f-a6e3-fd69247f61bc.png)

Ro/e（Representation Odds Ratio to Expected）是一种用于单细胞分析的统计工具，它旨在评估特定细胞类型在不同组织中的分布是否显著偏离随机分布的期望值。这个工具提供了一种比较细胞类型在不同组织中的相对丰度的方法。
下面是对Ro/e概念的详细解释：
- 随机期望值：
在没有任何生物学差异的情况下，我们期望每种细胞类型在各个组织中的分布是随机的。这个随机期望值是基于所有细胞类型在所有组织中的分布计算得出的。
- Ro/e > 1（富集）：
如果某个细胞簇在特定组织中的Ro/e值大于1，这意味着该细胞簇在该组织中的细胞数量高于随机分布的期望值。换句话说，该细胞簇在该组织中是富集的，或者说在该组织中过度表示。
- Ro/e < 1（消耗）：
相反，如果Ro/e值小于1，这表明该细胞簇在特定组织中的细胞数量低于随机分布的期望值。这意味着该细胞簇在该组织中是消耗的，或者说在该组织中表示不足。
- 与卡方检验的区别：
卡方检验是一种统计方法，用于确定观察到的频率与期望频率之间是否存在显著差异。然而，卡方检验只能告诉你是否存在偏离随机期望的情况，但不能告诉你具体是哪些细胞簇在特定组织中富集或消耗。
Ro/e则提供了更详细的信息，它不仅能够显示偏离的程度，还能够指出具体是哪些细胞簇在特定组织中表现出富集或消耗。
- Ro/e的应用：
在单细胞分析中，Ro/e可以帮助研究人员识别特定组织中的关键细胞类型，这些细胞类型可能在疾病状态下或特定生物学过程中发挥作用。
通过比较不同组织中细胞类型的Ro/e值，研究人员可以更好地理解细胞类型的组织特异性和功能。
总结来说，Ro/e是一个强大的工具，它通过比较实际观察到的细胞分布与随机期望值，帮助研究人员识别和理解细胞类型在不同组织中的分布模式。这种方法提供了一种量化细胞类型组织特异性的方法，对于揭示细胞类型的生物学意义和功能具有重要价值。

6、[独立开发的100个思考](https://www.icebeer.top/%e7%8b%ac%e7%ab%8b%e5%bc%80%e5%8f%91%e7%9a%84100%e4%b8%aa%e6%80%9d%e8%80%83/ "独立开发的100个思考")

![](https://files.mdnice.com/user/33257/7a689487-69c2-49f2-b9ac-a6948002a6bf.png)

这是一个关于独立开发的100个思考归档，涵盖从竞争、工作模式重构、行动时机、开发者挑战、合作选择、成功策略、智囊团组建到成本控制等多个维度。这些思考旨在帮助独立开发者优化工作流程、提升效率、洞察用户需求，并在竞争激烈的市场中脱颖而出。内容强调创新和降维打击的重要性，以及在独立开发过程中避免沉没成本、寻找合作伙伴和构建个人智囊团的策略。

7、[Top 25 R Packages in 2024](https://mp.weixin.qq.com/s/uP_tAnOopFMeAUyiVbvonA)
![image](https://github.com/user-attachments/assets/50d4aa8e-9230-4e5c-8579-9429c8801483)
这篇文章主要介绍了2024年前沿的25个R语言包，涵盖了数据清理、数据总结、用户界面、代码模块化、数据处理、包管理、缺失数据处理、机器学习、表格制作、表格式可视化、深度学习、API构建、文件系统操作、相关性分析、日期时间处理、并行处理、图形组合、交互式可视化、文档自动化、Shiny应用构建、全栈开发、优化框架和地图功能等多个方面。


8、[刘钝：为何说中国的知识分子应读一读竺可桢？](https://mp.weixin.qq.com/s/S9wlwGpSjxBPPOKY63qOQQ)
![image](https://github.com/user-attachments/assets/7a6de7d5-3d48-4b23-bb4b-f3635ce531d7)
本文主要阐述了竺可桢作为气象学、地理学及教育学家的卓越贡献，并强调了当代知识分子应学习竺可桢的道德操守与献身精神。

## 工具
9、[Scplotter | 单细胞数据可视化的R包](https://github.com/pwwang/scplotter/ "Scplotter | 单细胞数据可视化的R包")
![image](https://github.com/user-attachments/assets/945ea895-9fe2-4dca-8fd6-06121166b40d)
scplotter是一个建立在plotthis的基础上，提供了一套函数，以轻松高效的方式可视化单细胞测序数据的R包,支持 TCR/BCR 分析并与 scRepertoire 兼容。 

10、[xPipe ｜ 你的服务器基础设施尽在指尖](https://github.com/xpipe-io/xpipe "xPipe ｜ 你的服务器基础设施尽在指尖")

![](https://files.mdnice.com/user/33257/dc7c9509-554e-4e04-98f4-eccd45aba7d0.png)
XPipe允许用户通过一个平台管理所有的服务器连接、配置文件和隧道，支持多种工具和环境，如 SSH、Docker、Podman、LXD 容器实例等。XPipe 的设计理念是高度集成和可扩展，使得用户可以轻松地添加对更多工具的支持或通过模块化扩展系统实现自定义功能。

11、[frpc-desktop | 跨平台的内网穿透配置桌面客户端](https://github.com/luckjiawei/frpc-desktop "frpc-desktop | 跨平台的内网穿透配置桌面客户端")

![](https://files.mdnice.com/user/33257/8c26e0e5-3899-4048-bbac-f9b4bcc72371.png)

frpc-desktop目前支持所有版本的 frp（Fast Reverse Proxy），旨在通过可视化配置实现内网穿透，实现远程访问公司、家庭内部的设备，简化用户操作。

- 教程链接：https://jwinks.com/p/frp/#frp%E6%98%AF%E4%BB%80%E4%B9%88

## 资源
12、[高性能计算中文翻译计划](https://github.com/realYurkOfGitHub/translation-Introduction-to-HPC "高性能计算中文翻译计划")

![](https://files.mdnice.com/user/33257/1a2aa06c-be3a-4401-bd2c-d251fb08934f.jpg)

本书涵盖了一名合格的计算科学家需要掌握的基础知识，可以作为研究生或高级本科生的教材；或者您也可以把它作为额外的参考，也可以当作阅读练习的材料。
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

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。


![](https://files.mdnice.com/user/33257/1ca7c26a-82bf-4a14-a8d4-9a781945dc18.png)


（完）