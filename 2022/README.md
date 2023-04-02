# rustOS

十二月
| MON | TUE | WED | THU | FRI | SAT | SUN |
| --- | --- | --- | --- | --- | --- | --- |
|     |     |     | 1   | 2   | 3   | 4   |
| 5   | 6   | 7   | 8   | 9   | 10  | 11  |
| 12  | 13  | 14  | 15  | 16  | 17  | 18  |
| 19  | 20  | 21  | 22  | 23  | 24  | 25  |
| 26  | 27  | 28  | 29  | 30  |     |     |

十一月
| MON | TUE     | WED     | THU     | FRI     | SAT     | SUN |
| --- | ------- | ------- | ------- | ------- | ------- | --- |
|     | 1([D3]) | 2([D4]) | 3([D5]) | 4([D6]) | 5([D7]) | 6   |
| 7   | 8       | 9       | 10      | 11      | 12      | 13  |
| 14  | 15      | 16      | 17      | 18      | 19      | 20  |
| 21  | 22      | 23      | 24      | 25      | 26      | 27  |
| 28  | 29      | 30      |         |         |         |     |

## 第一周计划：Day0-Day7，至2022-11-05

1. 根据[study resource of system programming in RUST · rcore-os/rCore Wiki](https://github.com/rcore-os/rCore/wiki/study-resource-of-system-programming-in-RUST)的方案四
    - [ ] 完成15道中等以上难度的算法题

2. 预习RISC-V系统结构
   - [ ] 《RISC-V手册：一本开源指令集的指南》
   - [ ] 《RISC-V汇编手册》

### Day7 2022-11-05

- [ ] rustlings再来一遍
- [ ] 完成《RISC-V手册：一本开源指令集的指南》的阅读
- [ ] 《RISC-V汇编手册》
- [ ] 为lab0, lab1做预备，阅读《Open-Source-OS-Training-Camp-2022 文档》前三章
- [ ] 完成中等难度算法10题

如果完成后没别的事干了，可以再看一看

- [ ] 《rCore-Tutorial-Book-v3 3.6.0-alpha.1 文档》

### Day6 2022-11-04

- [x] lunarvim配置rust环境，或者VScode要能跳转定义，不然之后没法进行系统编程
- [ ] Rust圣经，按照能写正确Rust风格的链表的目标去看，想办法按Rust风格正确地写一个链表、一棵树，完成中等算法5题
- [ ] 搭建lab0环境
- [ ] 《RISC-V汇编手册》
- [ ] 《RISC-V手册：一本开源指令集的指南》前60页

1. IDE的问题最终在WSL上解决了，谜底是相关作者在为lunarvim设计rust部分插件的时候没有把windows上的情况考虑进来，所以不能在windows上用

小结1：什么是理性地debug？

看了谜底会发现，由于作者本就没有支持相应的特性，自己无论怎么样在网上查都不可能找到简单解决方案的……（除非自己hack）……类似的，各类问题应该限制debug时间，开一个日志记录debug的过程中发掘出的信息、尝试的不同方案，半小时内没有出来，那就保存日志，然后过半天再回来debug。要是总计一小时了还没出来，而且debug的方案已经试得差不多了，那应该总结这份日志然后去“智慧地提问”。这样才是理性地debug。切忌无限制投入时间……

### Day5 2022-11-03

之前制定的方案有些比较激进，应该稍微缓和一些。  
Rust程序设计训练的课程知识还不是很够。能写代码，但是在关键概念的理解上还是比较模糊的，应该看一看《Rust圣经》

- [ ] lunarvim配置rust环境
- [x] rustlings 84/84  
- [ ] LeetCode 简单2题，中等3题
- [ ] 复习Rust，写《Rust入门小结》
- [x] Rust圣经，针对rustlings和写算法过程中遇到的问题定向阅读，不定量

目前的一些问题：

1. IDE仍然存在问题，VScode也无法跳转定义……迷惑……
2. Rust课程后半部分的东西大多没有在rustlings中出现，学了但没练，根据过往经验，这不好
   1. Rust中有很大一部分是接口、库如何联调的知识，需要积累相应的例子。应该针对性地学习

自己定的学习还是过于激进，不可变数据结构要完成15题算法不太可能完成。应该边看Rust圣经边推进。

### Day4 2022-11-02

- [ ] lunarvim配置rust环境
- [x] Rust程序设计训练，第七讲，I/O与异步编程  
- [x] Rust程序设计训练，第八讲，高级特性与编程语言综述  
- [ ] rustlings 84/84  
- [ ] LeetCode 简单2题，中等1题  
- [ ] 写《Rust入门小结》

lunarvim无法配置rust-analyzer，暂用vscode。但是还是不太方便，开多文件时无法跳转定义
rustlings 54/84，错误处理的部分卡了比较久

### Day3 2022-11-01

本来的预定目标：

- [ ] lunarvim配置rust环境
- [ ] Rust程序设计训练，第七讲，I/O与异步编程  
- [ ] Rust程序设计训练，第八讲，高级特性与编程语言综述  
- [ ] rustlings 84/84  
- [ ] LeetCode 简单2题，中等1题  
- [ ] 写《Rust入门小结》

但因为有事，中断一天学习

### Day2 2022-10-31

十月
| MON      | TUE | WED | THU | FRI | SAT      | SUN      |
| -------- | --- | --- | --- | --- | -------- | -------- |
|          |     |     |     |     | 1        | 2        |
| 3        | 4   | 5   | 6   | 7   | 8        | 9        |
| 10       | 11  | 12  | 13  | 14  | 15       | 16       |
| 17       | 18  | 19  | 20  | 21  | 22       | 23       |
| 24       | 25  | 26  | 27  | 28  | 29([D0]) | 30([D1]) |
| 31([D2]) |     |     |     |     |          |          |

完成情况：  
Rust程序设计训练，第四讲，泛型、特型与生命周期  
Rust程序设计训练，第五讲，项目管理与常用库  
Rust程序设计训练，第六讲，并发编程  

### Day1 2022-10-30

完成情况：  
Rust程序设计训练，第二讲，所有权与结构化数据  
Rust程序设计训练，第三讲，标准库  
rustlings 44/84

### Day0 2022-10-29

完成情况：  
Rust程序设计训练，第一讲，基本语法

[D7]: #day7-2022-11-05
[D6]: #day6-2022-11-04
[D5]: #day5-2022-11-03
[D4]: #day4-2022-11-02
[D3]: #day3-2022-11-01
[D2]: #day2-2022-10-31
[D1]: #day1-2022-10-30
[D0]: #day0-2022-10-29