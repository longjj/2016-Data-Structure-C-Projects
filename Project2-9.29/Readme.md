# Project 2 总结

## 0. 项目编译运行指南
1. p1p2p3p4p5使用本目录下的makefile即可全部编译出来
2. p5的代码请进入P5_only的文件夹进行单独编译运行。
3. 具体的实验题目描述可以参考本目录下的Project2实验报告.docx

## 1. 收获
1. template 模板类的编译makefile写法
2. makefile 的通配符方法: %通杀  [参考博客](http://blog.csdn.net/xiaozhi_su/article/details/4202324)这样可以简化我们的makefile使之更加程序员:)


----

## 2. 不足与总结与改进

1.  在整个项目开始之前，需要所有开发人员认真看书，知道代码的整体流程布局，然后进行讨论，明确好分配的任务
2.  先明确好解决问题的思路，再开始打代码
3.  在打代码之前需要讨论需求分析，比如说，使用什么样的输出形式，需要明确好任务的分配，比如说，谁实现图形化界面的输出，谁实现数据获得后的数据处理，谁来完成代码的某一些部分，每个人根据自己对于任务的理解，对于自己能力的估计去思考自己应该负责哪一个部分，确定好了之后就应该是要完全完成这个问题，自己尽可能想办法去解决，争取每个人在完成了自己的任务后都能有所收获，要么是巩固了一遍不熟悉的基础，要么是学习了一个新的方法。

----


### 打代码之前应该要解决这么几个事情：
1. 整个项目的文件结构，什么文件夹存什么东西**（这次的代码结构就非常混乱）**
2. project的输出应该以什么方式保存，应该以什么格式存储，怎么存储
3. 我们需要获得什么数据，需要用来模拟出什么样的结果
4. 要完成总的实验项目可以分成哪几个耦合度不太高的子任务进行分治，子任务之间的联系关系处理好，不要到时候互相甩锅
5. 有什么拓展任务的大新闻想要搞，确定可行性，具体使用什么方法，学习成本是多少
6. 确认好实验报告的大纲形式，然后在开发的过程中逐步完善，初步的解决方案是使用谷歌文档在云端进行开发


### 打代码的时候需要注意什么
1. 请学会git的熟练使用，使用分支开发，然后要明确，commit应该是自己的完全成功版本，不能是半吊子版本就push上去，之前我们要这样子做就是因为分工太不明确了，然后任务分配之间的耦合度太高（好像rebase可以处理这个问题）
	+ 几个觉得比较重点的内容需要补
		+ .gitignore 的使用
		+ git stash 的使用（在开发过程中修理bug，参考廖雪峰）
2. 还是要注意使用统一的开发规范
3. 实验报告的形式要实时更新，可能的话要引用scrum的站立会议模式


---
### 初步分工
1. 代码开发者
2. gtest测试者
3. 数据分析者
4. UI设计者（可选）

---

> 暂时就想到这么多,以后有机会就再补充
> 如果是自己开发遇到了什么好的问题以及解决方法，也欢迎大家普遍写上来commit！提出问题以及解决参考的相关资料链接！