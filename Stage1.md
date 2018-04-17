---
layout: page
title: 阶段1：项目启动
weight: 2
---

# GridWorld阶段1：项目启动

* TOC
{:toc}


----------


### 摘要
本阶段主要是为实训项目做基本的技术准备，学会使用**Vi**, **JAVA**, **Ant** 和 **Junit**, 以及熟悉GridWorld的使用，并完成指定的任务。

时间：**2018.04.08~2018.04.15**


### 制品

 1.  个人任务：**Vi,Java,Ant和Junit的自学报告**
 2.  个人任务：**熟悉JAVA、Ant、Junit环境**
 3.  个人任务：**编写Java小程序**
 4.  个人任务：**学习并配置SonarQube**
 5.  个人任务：**编译运行BugRunner**
 6.  个人任务：**完成Part1的问题和练习**


### 提交规范

| 制品 | 提交命名 | 备注 | 提交时间 |
| :----: | :----: | :----: | :----: |
| Vi,Java,Ant,Junit的自学报告 | ~~`studyreport.md`~~ | [Markdown](https://en.wikipedia.org/wiki/Markdown)格式 | **04月15日23:30之前** |
| 任务2,3,4,5,6的代码 | `calculator.zip` | 必须包含HelloWorld代码，Junit测试代码，`build.xml`，`sonar-project.properties`，[Java小程序](./Stage1--Calculator)代码，[README](https://en.wikipedia.org/wiki/README) | **04月15日23:30之前** |
| [Part1](./Stage1--Part1)的问题和练习 | / | 建议用英文书写，**可用中文** | **04月15日23:30之前** |


----------


### 任务
推荐：
 - [xwy27委员长](https://github.com/xwy27)的[**云桌面配置**](https://github.com/se-2018/se-2018.github.io/issues/5)
 - [Huangscar菇](https://github.com/Huangscar)的[**ANT 入门教程**](https://github.com/se-2018/se-2018.github.io/issues/11)
 - [不知名gyakkun](https://github.com/gyakkun)的[**环境配置及Sonar错误处理**](https://github.com/se-2018/se-2018.github.io/issues/13)

**以下给出的[vi/vim](http://my.ss.sysu.edu.cn/wiki/pages/viewpage.action?pageId=7962701)、[JAVA](http://my.ss.sysu.edu.cn/wiki/pages/viewpage.action?pageId=21299305)、[Ant](http://my.ss.sysu.edu.cn/wiki/pages/viewpage.action?pageId=6521011)、[Junit](http://my.ss.sysu.edu.cn/wiki/pages/viewpage.action?pageId=21299308)学习链接仅供参考，可不看。**

 1. 学习[vi/vim编辑器的使用](http://my.ss.sysu.edu.cn/wiki/pages/viewpage.action?pageId=7962701)
 2. 熟悉JDK的环境并学习[JAVA语言](http://my.ss.sysu.edu.cn/wiki/pages/viewpage.action?pageId=21299305)，完成HelloWorld的编译运行
 3. 熟悉[Ant的环境](http://my.ss.sysu.edu.cn/wiki/pages/viewpage.action?pageId=6521011)并学习Ant，利用Ant实现HelloWorld的自动编译
 4. 学习Java语言，并编写Java小程序，完成要求请参考[Java小程序完成要求](./Stage1--Calculator)
 5. 学习[Junit](http://my.ss.sysu.edu.cn/wiki/pages/viewpage.action?pageId=21299308)，利用Ant、Junit测试通过HelloWorld
 6. 学习并[配置SonarQube](./resources/sonarqube-tutorial-v1.pdf)，利用SonarQube测试自己昨天写的Java小程序

    注意：Sonar 和 Sonar-runner 可以不下载，已放在云平台的`/opt/resources`目录
 7. 将代码打包，上传至[Matrix](https://vmatrix.org.cn)
 8. 完成[GridWorld](./resources/gridworld.zip)的[环境配置](./Stage1--EnvironmentalConfiguration)，学习`gridworld.jar`的引用，编译运行`BugRunner`
 9. 登录[Matrix](https://vmatrix.org.cn)完成[Part1](./Stage1--Part1)的问题和练习
 10. 完成检查，具体见下节"检查"

### 检查
请在**04月15日23:30之前**完成检查。检查具体时间、地点及流程见[概述](./Home)页中提要第六点"作业检查"。
 1. 检查ANT、Junit。主要是通过检查HelloWorld是否通过编译，部署和测试。（检查点：1.是否使用ANT；2.是否使用Junit）
 2. 检测SonarQube的使用情况。（SonarQube是否正常运行，Java小程序的分析结果）
 3. 检查BugRunner。（检查点：BugRunner是否能正确编译、运行）
 4. 对"自学报告"进行批改。给分标准请参照[GridWorld阶段1评审表](./Stage1--ReviewForm)。


----------


### 阶段结束
完成上述各步骤后，TA将约各小组约定检查地点，当面检查小组各项制品，并根据"软件工程实训考核规定"中的条款和"[GridWorld阶段1评审表](./Stage1--ReviewForm)"检查评估小组表现。获得及格的团队进入下一阶段，不及格的团队需要根据TA意见进行整改，得到TA认可后，进入下一阶段。整改通过后，阶段分数维持整改前分数不变。
