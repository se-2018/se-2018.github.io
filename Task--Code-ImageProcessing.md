---
layout: page
menu: false
---


# 阶段三 ImageReader 代码提交

 - 命名：`ImageReader.zip`
 - 要求：必须包含**ImplementImageIO.java**, **ImplementImageProcessor.java**, **ImageProcessorTest.java**，和[README](https://en.wikipedia.org/wiki/README)一起打包
 - 文件结构
    ```shell
    .
    ├── ImageProcessorTest.java
    ├── ImplementImageIO.java
    ├── ImplementImageProcessor.java
    ├── README.md
    └── ...
    ```
 - [作业来源](https://se-2018.github.io/Stage3--ImageProcessing)
 - [评分以100分为满分，以下分数为折后分数(10分)](https://se-2018.github.io/Stage3--ReviewForm)
    - 图像处理部分（共8分）
        - 利用二进制流读取Bitmap位图文件。注意，这里要求不能使用Java提供的API进行读取（TA检查）（2分）；
        - 把读取彩色图像转换成灰度图像（TA检查）（1分）；
        - 提取并且显示彩色图像各个色彩通道（TA检查）（1分）；
        - 把处理完的图像保存为bmp格式图像。注意，这里可以使用Java提供的API完成，但本文档不提供，希望各位同学自行上网查找资料自学。如果学有余力的同学，可以实现按照二进制流输出保存bmp图像（TA检查）（1分）；
        - Junit测试（TA检查）（1分）
        - 图像处理部分的代码（TA评审）（2分）
    - **Sonar**代码分析2分
        1. Comments（注释）：注释不得少于10%，少于10%扣2分
        2. Duplications（重复）：允许重复行数最多为10行；多于10行的，每多10行扣1分（少于10行算10行）
        3. Rules compliance（遵守规则）：遵守的规则至少为60%；低于60%的，少10%就扣1分；

            注：每出现1个Critical（严重）或者Blocker（阻断）问题，扣5分；

