---
layout: page
title: 环境配置
parent: Stage1.md
weight: 3
---

# 环境配置及GridWorld运行指南

* TOC
{:toc}


----------


## 资源
**云平台的资源放在 /opt/resources 目录下， 包括：**

 - **grid-world 项目驱动代码**
 - **需要的安装包**


## 配置

 1. 云平台中已经预装好Java (openJDK) 环境，在终端中输入以下命令可以看到java的版本信息。
    ```shell
    java -version
    ```

 2. 云平台中已经预装好了apache ant 环境，在 shell命令行敲入以下命令：
    ```shell
    ant
    ```
    如果显示以下信息，则表明已安装 ant。
    ```shell
    Buildfile: build.xml does not exist!
    Build failed
    ```

 3. 在 shell 命令行中编译以及执行 `BugRunner` 的方法

    路径中有空格的可使用''包含路径。
    ```shell
    ## 编译
    javac -classpath .:gridworld.jar 所要编译的 java 文件所在目录路径/BugRunner.java
    ## 执行
    java -classpath .:gridworld.jar:所要执行的 class 文件所在的目录路径  BugRunner
    ```

    如果将gridworld.jar文件包含到JAVA的安装目录中，并在CLASSPATH中引用gridworld.jar包，则可以这样执行
    ```shell
    ## 编译：
    javac 要编译的java文件所在的目录路径/BugRunner.java
    ## 执行：
    java 所要执行的 class 文件所在的目录路径  BugRunner
    ```

    推荐一个java教程：[http://www.cnblogs.com/vamei/archive/2013/03/31/2991531.html](http://www.cnblogs.com/vamei/archive/2013/03/31/2991531.html)

    然后ant的直接build+run闪退的看这里：[http://hellokenlee.blog.163.com/blog/static/213933032201462282950245/](http://hellokenlee.blog.163.com/blog/static/213933032201462282950245/)

 4. first project运行：
    命令行进入到 `$Gridworld_Project/GridWorldCode/projects/firstProject`
    ```shell
    ## 编译：
    javac -classpath .:./../../gridworld.jar BugRunner.java
    ## 执行：
    java  -classpath .:./../../gridworld.jar BugRunner
    ```

    `gridworld.jar`是预先打包构建好的，为本次实训提供教学框架的代码包(jar)，在各个阶段开发中，需要将其引入到我们的编译之中。


