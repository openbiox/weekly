---
date: 2024-09-01
comments: true
---

# 生信爱好者周刊（第 138 期）：35岁危机之前，大学青年教师们要爬多少阶梯？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo "「生信周刊讨论区（语雀）」") | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community "「生信讨论区（Gitter）」")

## 封面图


![](https://files.mdnice.com/user/37191/6350c4af-2e3e-41c6-a99d-4ac3ae064cd6.jpg)


## 本周话题：[35岁危机之前，大学青年教师们要爬多少阶梯？](https://mp.weixin.qq.com/s/K3YBXEQ7jzRajjpAPeHuiQ)

![](https://files.mdnice.com/user/37191/8ac034f2-fb7e-49f3-8360-d833247ceab3.png)


>近期，不少高校陆续公布了博士拟录取名单。2022 年，中国博士在校生的规模就已超过 55 万。然而，扩招潮之下，许多博士的职业前路——高校教师，在“非升即走”的影响下正愈发逼仄。
>
>今年是陈微（化名）成为大学讲师第 4 年。2020 年博士毕业后，陈微获得了上海一所高校的教职。他认为自己的工作强度不亚于读博，“一个博士四年只干一件事，但青年老师起码要干五件事。”“除了过年大概 3 到 5 天会回家陪陪父母，平时每天我都会来学校。”
>
>陈微已经顺利进入了第二个聘期，但他也目睹过认识的老师因为没有通过考核或没有晋升成功，而被迫离开。没有官方数字直接披露通过预聘制考核的比例，陈微表示“我们大概知道如果有 10 个人申请晋升，只能有 3、4 个可以吧。”
>
>读博看似拉长了人生的时间尺度、站在了新的广阔平台，但又只是“学术阶梯”的最低一层，并且一步比别人慢了，以后也可能更加吃力。

## 生信研究
1. [Nat Commun | 结合机器学习与血浆蛋白质组质谱分析可提前7年预测帕金森病，准确率达79%](https://mp.weixin.qq.com/s/JBp2mctPneBeTRYR0MIOow)


![](https://files.mdnice.com/user/37191/a145984a-1fb3-4620-857b-f229b4fe3a3f.png)


近日，英国伦敦大学学院大奥蒙德街儿童健康研究所和哥廷根大学医学中心的科研人员在*Nature Communications* 发表了题为“Plasma proteomics identify biomarkers predicting Parkinson’s disease up to 7 years before symptom onset”的文章。研究团队对最近确诊的运动型帕金森病(PD)患者、患有孤立性快速眼动睡眠行为障碍（iRBD）的运动前个体和健康对照（HC）组的血液样本进行靶向多重质谱分析，发现了8种与PD相关的血液生物标志物；随后，通过机器学习模型分析8种蛋白质的表达，准确识别了所有PD患者，并在运动发作前7年对79%的运动前个体进行分类预测，其中许多生物标志物与症状严重程度相关。该研究表明，血浆蛋白质组检测或有助于在运动症状出现前7年预测PD的发生。

- 论文链接：https://www.nature.com/articles/s41467-024-48961-3


2. [Nature Methods | EpiChem技术揭示药物与染色质结合的单细胞层面机制](https://mp.weixin.qq.com/s/uLrl4z-3HmzylQ-eBzwIrg)


<img width="1300" alt="image" src="https://github.com/user-attachments/assets/bd5b929f-23f2-4a15-9371-43e55f79bdd3">


这篇文献介绍了一种名为EpiChem的新技术，它能够在单细胞水平上同时测量小分子药物与染色质的结合以及多模态的表观基因组特征。这项技术通过裂池条形码和蛋白A-Tn5抗体定向标签的方法，成功应用于研究人类结直肠癌（CRC）类器官中的多种药物相互作用。EpiChem技术揭示了药物与已知蛋白靶点之间共享和特有的结合位点，为药物基因组结合的深入研究提供了新的工具和方法，有望推动个性化和精准化癌症治疗的发展。

- 论文链接：https://www.nature.com/articles/s41592-024-02360-0

3. [Nature Communications | 基于长读长测序高分辨率解析完整端粒序列，揭示端粒与衰老、癌症等的新关联](https://mp.weixin.qq.com/s/Swmp_C5gZuMGqjczegDPdw)

**Telometer技术:** 
<img width="664" alt="image" src="https://github.com/user-attachments/assets/51392a6d-b450-4eb9-9aad-9b89f94aaa5c">

**Telo-seq技术:** 
<img width="487" alt="image" src="https://github.com/user-attachments/assets/043ebf2e-28db-4974-a23f-e9ae80d49730">

研究人员基于长读长测序原理，开发了Telo-seq和Telometer，并发表于 *Nature Communications*。这两项技术能高分辨率地解析端粒序列，揭示端粒在衰老和癌症中的作用。其中，Telo-seq能确定染色体上端粒的完整序列和长度，而Telometer则通过数字端粒测量区分健康衰老和疾病。这些技术有助于理解端粒生物学及开发新的治疗和诊断方法。

- 论文链接：https://doi.org/10.1038/s41467-024-48917-7；https://doi.org/10.1038/s41467-024-49007-4

4. [Cell ｜ 德国MDC开创OPEN-ST一种三维空转方法](ttps://doi.org/10.1016/j.cell.2024.05.055)

![](https://github.com/user-attachments/assets/477ff70d-7720-4353-9d2c-c817e6094670)

研究人员开发了一种易于使用、高分辨率、具有成本效益和3D可扩展的方法，测序了成年小鼠海马、胚胎鼠脑和人转移性淋巴瘤样本。

感谢`@OlafTobark42 `投稿。

- 论文链接：https://doi.org/10.1016/j.cell.2024.05.055
- 网站：https://rajewsky-lab.github.io/openst/main/


## 博文资讯

5. [如何更改 Docker 的数据目录](https://linuxiac.com/how-to-change-docker-data-directory)

![](https://github.com/user-attachments/assets/6c4af70f-5bdb-4988-952a-f58ddfa52477)

Docker 默认使用系统根目录，一般这种磁盘空间非常小，本文介绍了如何更改该目录。

<img width="726" alt="image" src="https://github.com/user-attachments/assets/138186f1-ad4f-4ae8-bc46-fe61e71e4d2a">


6. [clustifyr｜单细胞全自动注释篇](https://mp.weixin.qq.com/s/GQiRQIbr1rx5xKYzC1My3Q)

![](https://github.com/user-attachments/assets/93afff87-9673-4aa8-8d31-df4cf74aff45)

7. [中国AI制药第一股市值180亿港元，3名麻省理工博士后今敲锣](https://mp.weixin.qq.com/s/G93qGlq-ZIgZvEjT--HJug)


![](https://files.mdnice.com/user/37191/6f9fb008-2fcd-4a3f-b2f8-518c8c934380.png)


2024年6月13日，由温书豪、马健和赖力鹏联合创立的晶泰科技在港交所成功敲锣。至此，晶泰科技成为了港股18C第一家上市公司，亦是“中国AI制药第一股”。

上市首日，晶泰科技发行价报5.28港元，按发行价计算晶泰科技市值近180亿港元。

明星资本光环加持，又顶着港股18C第一家上市公司的名头，人们也不免好奇，晶泰科技的三剑客是如何用AI撬开新药研发这把锁，绘制出如今的AI制药版图？以及在AI大模型掀起“狂欢”浪潮时，它又会续写怎样的新故事？


## 工具

8. [GAPIT](https://github.com/jiabowang/GAPIT)


![](https://files.mdnice.com/user/37191/4dd6280d-7bd0-4659-9db0-fe1bc318fd2a.png)


GAPIT是第三代基因组关联和预测集成工具，其为一个R包，可进行GWAS等数据分析工作。

9. [worklenz](https://worklenz.com/)


![](https://files.mdnice.com/user/37191/68c0e876-9d88-42c8-a5c7-28944152f865.png)

worklenz是一款强大的开源项目管理工具。

10. [dooit | 一款简洁高效的TUI待办事项管理器](https://mp.weixin.qq.com/s/teA0H77zRhZOyKae6kfO3w)


![](https://files.mdnice.com/user/37191/f990f54c-1299-4ee0-b264-9588604b5b48.png)


dooit是一个开源文本用户界面（TUI）待办事项管理器，旨在提供简单高效的任务管理，允许用户通过终端界面快速添加、编辑和完成任务。它具有文本用户界面、简单易用、快速操作、任务管理、数据持久化和自定义配置等特点。dooit支持Windows、Linux、Mac OS系统，用户可以通过键盘快捷操作进行任务管理，适合喜欢在命令行中工作的人士使用。

- 工具链接：https://github.com/kraanzu/dooit

## 资源

11. [Open source plugins of Hiplot ORG](https://github.com/openbiox/hiplot-org-plugins?tab=readme-ov-file)

<img width="1781" alt="image" src="https://github.com/user-attachments/assets/a56bfead-1fdf-4619-9d01-c7143bd440a0">

本资源提供了[hiplot](https://hiplot.cn/)在线绘图网站中的部分插件源码。

12. [软件工程师的必读书单](https://newsletter.techworld-with-milan.com/p/learn-things-that-dont-change?open=false#%C2%A7books-every-software-engineer-must-read-in)


![](https://files.mdnice.com/user/37191/c09ddce8-f162-4c3c-a022-3721917561cb.png)


## 历史上的本周
- 2023 [生信爱好者周刊（第 98 期）：自然选择主要作用于基因上吗？](https://mp.weixin.qq.com/s/_vSHyD1mN4KRaNdLPOvZCQ)

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

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。


![](https://files.mdnice.com/user/37191/484e56e7-6d4d-41a3-a70c-53e240bb2dcd.png)


（完）