---
layout: page
menu: false
---


# 阶段三 Jigsaw 代码提交

 - 命名：`Jigsaw.zip`
 - 要求：必须包含 **Jigsaw.java**，和[README](https://en.wikipedia.org/wiki/README)一起打包
 - 文件结构
    ```shell
    .
    ├── Jigsaw.java
    ├── README.md
    └── ...
    ```
 - [作业来源](https://se-2018.github.io/Stage3--NPuzzle)
 - [评分以100分为满分，以下分数为折后分数(10分)](https://se-2018.github.io/Stage3--ReviewForm)
    - 拼图部分（共8分）
        - （Demo）运行演示脚本RunnerDemo，求解随机8数码问题（3*3拼图）。
        - 利用广度优先搜索求出指定8-数码问题（3*3拼图）的最优解（TA检查）（3分）
        - 利用启发式搜索求解随机生成的24-数码问题（5*5拼图）（TA检查）（3分）
        - 拼图部分的代码（TA评审）（2分）
    - **Sonar**代码分析2分
        1. Comments（注释）：注释不得少于10%，少于10%扣2分
        2. Duplications（重复）：允许重复行数最多为10行；多于10行的，每多10行扣1分（少于10行算10行）
        3. Rules compliance（遵守规则）：遵守的规则至少为60%；低于60%的，少10%就扣1分；

            注：每出现1个Critical（严重）或者Blocker（阻断）问题，扣5分；

