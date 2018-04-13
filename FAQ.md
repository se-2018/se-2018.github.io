---
layout: page
title: FAQ
weight: 5
---

## FAQ


* TOC
{:toc}


----------


提问前请先确认：
 1. 一切没有明文规定(内容包括学校规章制度，助教回复，本网站，[Matrix](https://vmatrix.org.cn)，实训群公告)的行为原则上都是允许的，但不允许钻空子(助教判断)。
 2. 右上角有搜索功能(字符串搜索，不支持模糊搜索)，请先搜索关键字。
 3. 实训群里搜索聊天记录，可能有人提问过并有解决方案。
 4. 在[Github Issues](https://github.com/se-2018/se-2018.github.io/issues)上提问优于实训群，实训群提问优于私戳提问。(最大程度上给后面遇到同样问题的同学一些信息)


### 忘记云桌面密码
发邮件到[244191469@qq.com](mailto:244191469@qq.com)，会尽快重置成学号。
邮件标题：中级实训-重置云平台密码
邮件内容：包括学号和姓名信息。

### 连接不上云桌面
请先询问其他人是否能连上，若其他人可以而自己不可以，请先排查网络问题。还是无法解决请私戳反馈。

### 云桌面配置
```shell
administrator@vinzor:~$ lsb_release -a
No LSB modules are available.
Distributor ID:    Ubuntu
Description:    Ubuntu 12.04.5 LTS
Release:    12.04
Codename:    precise

administrator@vinzor:~$ java -version
java version "1.8.0_91"
Java(TM) SE Runtime Environment (build 1.8.0_91-b14)
Java HotSpot(TM) 64-Bit Server VM (build 25.91-b14, mixed mode)

administrator@vinzor:~$ ant -version
Apache Ant(TM) version 1.8.2 compiled on December 3 2011

administrator@vinzor:~$ sonar-runner --version
SonarQube Runner 2.4
Java 1.8.0_91 Oracle Corporation (64-bit)
Linux 3.13.0-32-generic amd64

administrator@vinzor:~$ junit -help
junit 3.8.1 -- this version is modified by Takashi Okamoto <tora@debian.org> for Debian.
```

### 云桌面资源
```shell
administrator@vinzor:~$ ls -1 /opt/resources/
apache-ant-1.9.7-bin.tar.gz
eclipse-java-neon-R-linux-gtk-x86_64.tar.gz
grid-world.zip
junit-4.12.jar
junit-4.9.jar
sonar-3.7.4.zip
sonar-runner-dist-2.4.zip
sonar-scanner-2.6.1.zip
```
