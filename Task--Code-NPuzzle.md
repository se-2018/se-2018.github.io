---
layout: page
menu: false
---


# 阶段三 Jigsaw 代码提交

 - 命名：`Jigsaw.zip`
 - 要求：打包**Solution.java**
 - 提示：提交前请确保能正常运行`test.sh`，否则评测会是0分。
 - 文件结构
    ```shell
    .
    └── Solution.java
    ```
 - [作业来源](https://se-2018.github.io/Stage3--NPuzzle)
 - [评分以100分为满分，以下分数为折后分数(16分)](https://se-2018.github.io/Stage3--ReviewForm)
    - 拼图部分（共16分）

        **此部分不需要助教检查，会对`Solution.java`进行离线评判，分数由机器评判给出。请仔细阅读[代码包](./resources/jigsaw_code.zip)中[README](./Task--Code-NPuzzle)并遵守提交规范，否则评判结果会是0分。**
        - （Demo）运行演示脚本RunnerDemo，求解随机8数码问题（3*3拼图）。
        - 利用广度优先搜索求出指定8-数码问题（3*3拼图）的最优解（Offline Judge）（2分）
        - 利用启发式搜索求解随机生成的24-数码问题（5*5拼图）（Offline Judge）（14分）
            - 运行三次，访问节点总数分别记为`n1`, `n2`, `n3`， 平均访问节点总数`n` = (`n1` + `n2` + `n3`) / 3

## 附录

### 代码中的README

**Please make sure that you can pass `test.sh` before submission.**

#### Demo
```shell
# compile
mkdir -p build
javac -encoding UTF-8 -d build -cp src src/Runners/*.java

# run
java -cp build Runners.RunnerDemo
java -cp build Runners.RunnerPart1
java -cp build Runners.RunnerPart2
```


#### Judge

##### Constraints

| Item | Limit | Notes |
| :--: | :--: | :--: |
| Time | < 1 secs | guarantee shortest path length no more than 11 in `BFSearch` |
| Memory | < 32 MB | / |
| Code length | < 1MB | / |
| System call | forbid | / |

##### Description
Finish class `Solution`.
 - `BFSearch`
 - `estimateValue`

##### Input
You don't need to handle input.

##### Ouput
You don't need to handle output.


##### Sample Input
```
Score
11
22 1 2 3 4 5 6 7 8 9 10 11 18 12 14 15 21 16 13 19 20 17 0 22 23 24
16 1 2 3 4 5 6 7 8 9 10 11 18 12 14 15 0 16 13 19 20 21 17 22 23 24
1 0 1 8 23 24 16 4 9 7 20 12 3 10 15 17 6 22 5 19 14 21 2 18 11 13
24 8 2 13 9 3 15 22 5 6 21 12 4 14 11 1 18 20 19 7 17 23 24 16 0 10
```

##### Sample Output
```
Jigsaw AStar Search Result:
Begin state:{16,1,2,3,4,5,6,7,8,9,10,11,18,12,14,15,0,16,13,19,20,21,17,22,23,24}
End state:{25,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,0}
Total number of searched nodes:169
Depth of the current node is:9
Jigsaw AStar Search Result:
Begin state:{1,0,1,8,23,24,16,4,9,7,20,12,3,10,15,17,6,22,5,19,14,21,2,18,11,13}
End state:{25,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,0}
Total number of searched nodes:29000
Depth of the current node is:210
Jigsaw AStar Search Result:
Begin state:{24,8,2,13,9,3,15,22,5,6,21,12,4,14,11,1,18,20,19,7,17,23,24,16,0,10}
End state:{25,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,0}
Total number of searched nodes:29000
Depth of the current node is:289

Score:4

```

##### Run
See `test.sh`.
```shell
mkdir -p build
javac -encoding UTF-8 -d build -cp lib/jigsaw.jar src/solution/Solution.java
java -cp lib/jigsaw.jar:build judge.main
```

