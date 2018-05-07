---
layout: page
title: 评审表
parent: Stage2.md
weight: 0
---

## GridWorld阶段2评审表

* TOC
{:toc}


---


### 标准
此阶段占作业成绩的45%。要求：

 - 问答题
    - 正确性
        1. 正确： 回答准备无误（不扣分）
        2. 基本正确： 回答大体正确，有小错误（扣一半分数）
        3. 错误： 回答有严重错误（无分）
    - 简洁性
    - 全面性
        - 按比例扣分
    - 排版
        1. 整齐（不扣分）
        2. 混乱（扣一半分数）
    - **源码支撑**
        1. 无源码（从源码中抽取的javadoc可视作源码）依据（无分）
        2. 不指出源码所在位置（无分）
        3. 多余的源码10行以上（无分）

        示范： 
        - 问题：Does the bug always move to a new location? Explain.
        - 回答：No. A bug will only move to the location in front of it if the cell exists and is empty or if there is a flower in the cell.
            - if the cell exists：
                ```java
                // @file: info/gridworld/actor/Bug.java
                // @line: 98~99
                if (!gr.isValid(next))
                    return false;
                ```
            - if is empty or if there is a flower in the cell
                ```java
                // @file: info/gridworld/actor/Bug.java
                // @line: 101
                return (neighbor == null) || (neighbor instanceof Flower);
                ```

 - 代码题：运行无误；相关代码规范查看sonar的运行结果。

    a. 如果无抄袭现象，可获得该部分全部分数。

    b. 如发现抄袭，当天的所有工作0分。


----------


### 细则

#### **Part 2** 和 **Part 3**的所有问答题与代码练习（TA检查）（共12分）
参照问答题和代码题目的标准。
 1. Part 2 问答题部分3分，代码运行检查2分（共5分）
 2. Part 3 问答题部分及文档5分，代码运行检查2分（共7分）

#### **Part 4** 和 **Part 5**的所有问答题与代码练习（共20分）
参照问答题和代码题目的标准。
 1. Part 4 问答题部分5分，代码运行检查5分（共10分）
 2. Part 5 问答题部分4分，代码运行检查6分（共10分）


----------


#### **Sonar**代码分析结果基本标准（共10分）

 1. Comments（注释）：注释不得少于10%，少于10%扣2分
 2. Duplications（重复）：允许重复行数最多为10行；多于10行的，每多10行扣1分（少于10行算10行）
 3. Rules compliance（遵守规则）：遵守的规则至少为60%；低于60%的，少10%就扣1分；

    注：每出现1个Critical（严重）或者Blocker（阻断）问题，扣5分；
    
每部分给分：Part 2（3分），Part 3（2分），Part 4（3分），Part 5（2分）；

如果以上三个基本标准都达到了，且TA检查了代码风格较好，则可以得到每部分的全部分数。

每位同学在TA检查前都可以无限次修改自己的代码并进行分析。


----------


#### **代码检测部分**（3分）

 1. 如果无抄袭现象，可获得该部分全部分数。
 2. 如发现抄袭，当天的所有工作0分。

