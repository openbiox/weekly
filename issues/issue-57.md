---
date: 2023-04-05
comments: true
---

# 生信爱好者周刊（第 57 期）：深度学习并非“简单的统计”，二者距离已越来越远

这里记录每周值得分享的生信相关内容，周日发布。 

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。 

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/5208/b0edc0a9-83bc-4c10-882e-51880aa1d483.png)

## 本周话题：[深度学习并非“简单的统计”，二者距离已越来越远](https://mp.weixin.qq.com/s/upMFm3UEZ60U8oXq_sqS9w)

> 统计学习在深度学习中扮演着重要的角色，这是毋庸置疑的。但可以肯定的是，统计角度无法为理解深度学习提供完整的画面，要理解深度学习的不同方面，仍需要人们从不同的角度出发来实现

@He-Kai-fly - 深度学习就是用统计学从数据中找到隐藏规律，并且都是建立在大量数学运算的情况下，其中一部分都建立在统计学的基础上但又不完全是。

## 生信研究

1、[Nature Communication | 单细胞环形RNA分析技术及表达图谱](https://mp.weixin.qq.com/s/WmvecCIBYo904QSIaG13BA)


![](https://files.mdnice.com/user/5208/47ab1319-3b30-4f59-a712-8e13855cc8ed.png)


赵方庆团队基于海量单细胞全长转录组测序数据集，实现了单细胞分辨率下环形RNA的高效识别及深度挖掘，基于大规模时空组学数据的整合分析，对环形RNA的细胞异质性进行了深入探究，揭示了环形RNA作为细胞类型标志物的应用潜力。该研究将目前环形RNA研究从传统组织水平提升至单细胞水平，为探索不同细胞类型中环形RNA的生物学功能提供了重要的数据资源和分析技术。

- 数据库地址：http://circatlas.biols.ac.cn/
- 论文链接：https://www.nature.com/articles/s41467-022-30963-8



2、[iMeta | 南农沈其荣团队发布微生物网络分析和可视化R包ggClusterNet](https://mp.weixin.qq.com/s/FKitWMfuWCOY1hJTMep7UQ) 


![](https://files.mdnice.com/user/5208/04cef4d9-5ff8-49cf-88f3-a1b1915ce275.png)


> 网络分析逐渐被生态学家们重视并持续应用于生态学领域，开发更为强大和方便的网络分析工具十分必要。文章开发了名为**ggClusterNet**的R包，展示微生物网络模块化信息，用于更加容易的进行网络数据分析挖掘和可视化。在ggClusterNet包中设计了数十种网络布局算法用于更好的展示微生物网络模块化信息

- Paper地址：https://onlinelibrary.wiley.com/doi/10.1002/imt2.32 
- Bilibili: https://www.bilibili.com/video/BV1ig411Q7cw/
- Youtube：https://youtu.be/XQ4xhCo_p0s
- Github: https://github.com/taowenmicro/ggClusterNet/



3、 [Sci Adv | 岳峰团队开发深度学习模型EagleC 捕捉癌症基因组结构变异](https://mp.weixin.qq.com/s/hmXqV3_K3lekGV6RY8JzSg)


![](https://files.mdnice.com/user/5208/6832129f-14f4-4712-8236-2bea939836c2.png)


该项工作基于深度学习和集成学习策略，提出一个全新的捕捉癌症基因组中SV的计算框架EagleC。EagleC能够用于多种染色质构象捕获技术，比如Hi-C，Micro-C，HiChIP。更为重要的是，这个深度学习的模型可以直接用在单细胞Hi-C上，从而可以监测到癌症组织里的不同癌细胞结构变异的异质性。

- 论文链接：https://www.science.org/doi/epdf/10.1126/sciadv.abn9215


4、NBT| 高歌课题组单细胞多组学数据整合与调控推断新方法（GLUE）


![](https://files.mdnice.com/user/5208/b8e51445-15a0-462b-aebb-6f532efd9fe3.png)


基于图耦联策略的深度学习方法GLUE，实现了对百万级单细胞多组学数据的无监督精准整合与调控推断

- 论文链接：https://www.nature.com/articles/s41587-022-01284-4



## 博文资讯

5、[基于 R 语言的深度学习——简单回归案例](https://mp.weixin.qq.com/s/wZSu94BjTtlJ7RPR-qLmBA)


![](https://files.mdnice.com/user/5208/4d409ab1-6be6-46e2-9414-eddec84b30f9.png)


以一个例子介绍了如何使用神经网络来处理简单问题（数据量较小的回归问题），但在实际过程中还会遇到很多问题，相关资源可见：[基于 R 语言的深度学习——简介及资料分享](http://mp.weixin.qq.com/s?__biz=MzI1NjUwMjQxMQ==&mid=2247509537&idx=1&sn=e0dccb2101dd72a824a1953d60b35a2e&chksm=ea2759c5dd50d0d30ccd5e6a2f9514db2c33bce6c818a374f97f4f87db955680c13c36dc9cf2&scene=21#wechat_redirect)

6、[构建工具 Taskfile 介绍](https://mp.weixin.qq.com/s/Cyj6C09At9u5O1rzk43mGg)


![](https://files.mdnice.com/user/5208/6bb08bf2-5e56-47a2-997b-65af2d93508b.png)


Makefile 是一个常见的配置驱动的构建系统。这篇文章介绍 Taskfile：
> Taskfile 通过 yaml 来描述各种执行任务, 其核心采用 go 编写; 相较于 Makefile 的 tab 分割和 bash 结合语法 Taskfile 显得更加现代化和易于使用(虽然会变成 yaml 工程师). Taskfile 内置了动态变量、操作系统等环境变量识别等高级功能都更贴合现代化的 Coding 方式。
- 文档：https://taskfile.dev/


7、[在环形热图上添加文字标签](https://mp.weixin.qq.com/s/uE5mmC9fT5C7sbnMsFWZDQ)


![](https://files.mdnice.com/user/5208/c3f9a6b0-a248-4e1d-ac43-203b5685daee.png)


本文演示了利用**circlize**R包绘制环形热图，并添加文字标签



## 工具

8、staticmiports静态导入函数到R包中


![](https://files.mdnice.com/user/5208/22795de9-ef48-4a18-a4e2-cf306326bf1d.png)

staticimports可以很容易地将函数静态地导入到R项目或包中。静态导入意味着函数作为文本复制到项目中，而不是在运行时从单独的包中加载。

- Github：https://github.com/wch/staticimports


9、[Fluent Reader | 一款新颖的桌面RSS阅读器](https://github.com/yang991178/fluent-reader "Fluent Reader | 一款新颖的桌面RSS阅读器")


![](https://files.mdnice.com/user/5208/69fb861c-1ca3-4e22-b9ce-746fb139a91e.png)


Fluent Reader是一款支持windows和mac平台的RSS阅读器。

10、[R 包 - eventloop](https://github.com/coolbutuseless/eventloop "R 包 - eventloop")


![](https://files.mdnice.com/user/5208/c848bfb8-b68d-45b0-945c-443c34bf3fba.png)


> 很多人可能不知道 R 也可以写 GUI 的，虽然说不能脱离 R 环境独立运行。

`{eventloop}` 包提供了一个框架，用于呈现交互式图形，并以足够快的速度处理用户的鼠标+键盘事件，以满足游戏和其他实时应用程序的需求。

11、tkinter-helper - 一款为Tkinter打造的布局助手


![](https://files.mdnice.com/user/5208/fdfd3564-e625-4315-9cd8-5eb93a5cb372.png)


**TkinterHelper**（Tkinter布局助手）是一款为Tkinter打造，仅需拖拽组件进行布局，所见即所得，非常方便就能做出一个GUI界面，再配合 pyinstaller 库将程序打包成exe，简直是开发小工具的利器。

- Github: https://github.com/iamxcd/tkinter-helper
- Gitee: https://gitee.com/iamxcd/tkinter-helper

12、[KAAS-KEGG注释工具](https://www.genome.jp/tools/kaas/ "KAAS-KEGG注释工具")


![](https://files.mdnice.com/user/5208/0d793116-4162-4b70-ad57-b0b6c73b9ef8.png)


方便用于宏基因组分箱（binning）后的单菌基因组fasta或faa文件的KEGG注释，挖掘线索支持后续验证

## 资源

13、[vscode.dev-轻量级版本的Vscode](https://code.visualstudio.com/blogs/2021/10/20/vscode-dev#_bringing-vs-code-to-the-browser "vscode.dev-轻量级版本的Vscode")


![](https://files.mdnice.com/user/5208/adce006d-7587-45e3-b7f5-d285fcf43587.png)


一个完全在浏览器中运行轻量级版本的VS Code。可在本地机器上打开一个文件夹并直接开始编码。

- 地址：https://vscode.dev

14、 [TIP : Tracking Tumor Immunophenotype](https://github.com/dengchunyu/TIP "TIP : Tracking Tumor Immunophenotype")


![](https://files.mdnice.com/user/5208/1b055c4e-15d1-4dd6-8cf6-6330a847e91c.png)


TIP是一个用户友好的一站式网络工具，用于使用RNA-seq或微阵列数据跟踪、分析和可视化抗癌免疫状态和肿瘤浸润免疫细胞在七步癌症免疫周期中的比例。

- TIP 平台 : http://biocc.hrbmu.edu.cn/TIP/
- github : https://github.com/dengchunyu/TIP

15、[visR | 将临床数据简单快速可视化的R包](https://github.com/openpharma/visR "visR | 将临床数据简单快速可视化的R包")


![](https://files.mdnice.com/user/5208/e8aad0b9-e938-40ef-bf79-3864ec996304.png)


## 历史上的本周
- 2022年1月：[第 17 期：Cox比例风险模型著作者离世](https://mp.weixin.qq.com/s/oqG8E_DlfusIV8u1fg8fjQ)
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

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）