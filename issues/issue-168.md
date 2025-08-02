---
date: 2025-06-17
comments: true
---
# 生信爱好者周刊（第 168 期）：”future you“ AI工具，可模拟未来的自己


这里记录值得分享的生信相关内容，每半月发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图


![](https://files.mdnice.com/user/77986/a35691fe-9546-4e62-832e-7fb343c8562f.png)


## 本周话题：[”future you“ AI工具，可模拟未来的自己](https://link.mail.beehiiv.com/ss/c/u001.vEfF-7mPRRMxHoaM7zwG0r1SnOLcokYHCT3ydEJp8WHw75p9n8PN9Wa-Zvbh6UeFOhtE8L7P47nZKH2Hfg5Aj8Qyi3BXm8A27ZJIbcFZ4xuc81pAw6Jc6vMnSzCadwqMWjmPbDWbv909OKHk0XIfBqVR0UOrH89arTjm96ZX4af4paHVJEeMz3kRZNshstI61pDpgjeazVEUyOyQ-ZfKd_SsaKtNUQtJ1P9VchXTGCC4PE_sd6LutgrmhstsLa4Hps5Spdx9_dd8ndPMKRzlvi9CzBHc2gIP6433tUXx_UUjz7fT95wSfbD5XMEnq82e/4af/ZL1ziPqWRrOseLstfoyWwQ/h3/h001.7b-2ly31c5t3GyaY7IMX6noLiXHiU9hEt30T8R8T3YM "”future you“ AI工具，可模拟未来的自己")

麻省理工的研究人员推出了一款名为“未来的你”(Future You)的AI工具，可以模拟用户30年后的状态。该工具会要求用户回答一系列关于目前生活状况的问题，然后根据回答为用户模拟30年后的生活状态，如果用户上传自己的照片，还能生成30年后的外貌。

## 生信研究
1、[Nature | 通过整合全基因组关联研究和空间转录组数据定位复杂疾病相关细胞的空间分布](https://mp.weixin.qq.com/s/tndB5cG7ZW4mwoOUnY6zeA)


![](https://files.mdnice.com/user/77986/861dc4f1-d412-478e-9ec4-b5876c49f3bf.png)


文章开发了一种新的分析方法gsMap，通过整合全基因组关联研究数据和空间转录组数据，描绘了人类复杂疾病（性状）相关的细胞在组织中的空间分布。

- 文章链接：https://www.nature.com/articles/s41586-025-08757-x

2、[Nat Commun | 跨越39种人类细胞类型的等位基因特异性DNA甲基化综合图谱](https://mp.weixin.qq.com/s/vDYCA1sGKwBguIrqyF-8NA)


![](https://files.mdnice.com/user/77986/bde1d270-84d9-4995-91fe-87c2dd7f513a.png)


文章绘制了跨越39种人类细胞类型的等位基因特异性DNA甲基化综合图谱。除利用深度全基因组测序、涵盖所有主要人类细胞类型等特点外，该图谱的一个突出优势就是基于纯化的、新鲜分离的各细胞类型的DNA绘制。

- 文章链接：https://www.nature.com/articles/s41467-025-57433-1

3、[Genome Biol | 纳米孔RNA直测新方法DEMINERS](https://mp.weixin.qq.com/s/p5Rgx_fM1B-1tZImL0dy2Q)   


![](https://files.mdnice.com/user/77986/59f2ad5b-189c-43cc-bf77-cbc2bccb5640.png)


研究开发出一款名为DEMINERS的创新纳米孔直接RNA测序（DRS）盒分析框架，突破了传统DRS技术在样本混合、碱基识别及数据分析方面的局限，实现了多达24个样本的同时直接测序以及高达93.54%的碱基识别准确率。   

- 文章链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03536-3
## 博文资讯

4、[让conda与Rstudio无缝衔接](https://mp.weixin.qq.com/s/6-sSQgNTwCrHNCsRLh5xcw)


![](https://files.mdnice.com/user/77986/b1c77274-5af1-47f4-852d-28f55cb0029f.png)


推文介绍了如何通过创建 Conda 环境并修改 Rstudio 配置来使用 Conda 环境中配置的 R 版本。

5、 [EBiomedicine | 用 R 快速重建 eBioMedicine 分段回归图](https://mp.weixin.qq.com/s/zoz_2hWDFukBcaj0XfmdPw)


![](https://files.mdnice.com/user/77986/595c6fde-6727-4598-8b5a-e9553334dad4.png)

推文使用模拟数据复现了BPFI （Blood Pressure Response Index）与死亡风险的非线性关系，并使用 R 快速重建了分段回归图。
- 文章链接：https://pubmed.ncbi.nlm.nih.gov/39059317/

6、[Rust Coreutils 0.1 正式发布：性能超越 GNU，重新定义命令行工具](https://mp.weixin.qq.com/s/2xu8d9sTyHeoSzFo-kyrIg)

推文介绍了Rust Coreutils 0.1该工具的优点。相对于传统的Coreutils而言，用Rust重写的Coreutils命令功能得到强化，其速度更快,占用内存更低,运维体验更好。
## 工具

7、 [Deep-Live-Cam | 一种基于 AI 技术的开源的人脸替换工具](https://github.com/hacksider/Deep-Live-Cam "Deep-Live-Cam | 一种基于 AI 技术的开源的人脸替换工具")



Deep-Live-Cam是一款深度伪造软件，它可以帮助艺术家为自定义角色制作动画、创作引人入胜的内容，甚至可以使用模型进行服装设计。

8、[tinytable | R中的简单和可定制表格](https://github.com/vincentarelbundock/tinytable "tinytable | R中的简单和可定制表格")


![](https://files.mdnice.com/user/77986/c2d76903-16e9-4697-9c48-47aec140fd91.png)


9、[DSCRIPT | 一种针对蛋白质-蛋白质相互作用序列预测的结构感知可解释深度学习模型](https://github.com/samsledje/D-SCRIPT "DSCRIPT | 一种针对蛋白质-蛋白质相互作用序列预测的结构感知可解释深度学习模型")


![](https://files.mdnice.com/user/77986/83f3611e-e388-4368-971f-df1866e2ae04.png)


- 官网：https://dscript.csail.mit.edu/

## 资源

10、[Arc细胞虚拟图谱](https://github.com/ArcInstitute/arc-virtual-cell-atlas "Arc细胞虚拟图谱")

“Arc虚拟细胞图谱”是一个由高质量、精心策划的开放数据集组成的集合，旨在加速虚拟细胞模型的创建。该图谱包含了超过3.3亿个细胞（且数据量在不断增长）的观察数据和扰动数据。

11、[Posit Cheatsheets](https://posit.co/resources/cheatsheets/ "Posit Cheatsheets")


![](https://files.mdnice.com/user/77986/8f60796b-5acb-4672-aeba-cf417fb8e7bd.png)

Posit Cheatsheets网页上提供了常见的使用软件包及教程的链接，会定时更新。



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

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413112010173.png)

（完）

