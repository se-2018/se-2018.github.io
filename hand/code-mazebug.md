# 阶段三 MazeBug 代码提交

 - 命名：`Mazebug.zip`
 - 要求：必须包含 **MazeBug.java**，和[README](https://en.wikipedia.org/wiki/README)一起打包
 - 文件结构
    ```shell
    .
    ├── MazeBug.java
    ├── README.md
    └── ...
    ```
 - [作业来源](https://se-2018.github.io/Stage3--MazeBug)
 - [评分以100分为满分，以下分数为折后分数(10分)](https://se-2018.github.io/Stage3--ReviewForm)
    - 走迷宫部分（共8分）
        - 基础部分：定义一个继承Bug类的MazeBug类，使虫子的行走方向只有东南西北四个方向，且在碰到迷宫出口（红石头）时，虫子会自动停下来。（TA检查）（2分）
        - 提高部分：深度优先搜索（TA检查）（2分）
        - 进阶部分：增加方向概率估计（TA检查）（2分）
        - 迷宫部分的代码（TA评审）（2分）
    - **Sonar**代码分析2分
        1. Comments（注释）：注释不得少于10%，少于10%扣2分
        2. Duplications（重复）：允许重复行数最多为10行；多于10行的，每多10行扣1分（少于10行算10行）
        3. Rules compliance（遵守规则）：遵守的规则至少为60%；低于60%的，少10%就扣1分；

            注：每出现1个Critical（严重）或者Blocker（阻断）问题，扣5分；

