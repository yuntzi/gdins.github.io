# 关于 Wolfram 语言和 Mathematica 的常见问题

> 本项目试图建立一个对最常被遇见、被问及的 Wolfram 语言和 Mathematica 问题的实用、详尽的中文解答，以减少相关中文社区的建设者的重复劳动。当有人在为他人解答某一常见问题时，可以引用、链接此处内容。

计划逐步翻译如下网页： [What are the most common pitfalls awaiting new users?](https://mathematica.stackexchange.com/questions/18393/what-are-the-most-common-pitfalls-awaiting-new-users)

欢迎为此项目贡献，原仓库：[`gitee链接，by wlcnfaq`](https://gitee.com/rnotlnglgq/wlcnfaq)
鉴于我最近要为强基做准备，预计两年的时间内此页面将不会再得到更新。
此项目与帮助文档不同之处，是帮助文档很不易为初学者所接受，而且往往解决得不彻底、不全面，故开此网站，以飨同仁来者。
在此对项目发起者wlcnfaq致以感谢。

姜尧耕(渔樵耕牍)于2022/2/17
个人站：https://gdins.github.io


## 问题索引
###快捷查询(按英文首字母顺序)：
#### 【#】
[`mma激活最全避坑指南(这点是百度mma吧吧主的友情链接)`](https://tiebamma.github.io/InstallTutorial/)
#### 【D】
[`DSolve::deqn"Equation or list of equations expected instead of True in the first argument T/F."`](FAQ/TagProtected.html)
#### 【F】
[`FindRoot::nlnum`](FAQ/NestedNumericalComputation.html) 
#### 【G】
[`General::ivar: X is not a valid variable.`](FAQ/SetDelayedAndSymbolsAsSlots.html) 
#### 【S】
[`Set(Delayed)::write"Tag someSymbol in somePattern is Protected."`](FAQ/TrueFalseEquation.html) 

### 核心语言

#### 入门

运算符与表达式

语句块

语义式匹配

`Equal`与 `SameQ`

`With` `Block` `Module`

[消息：表达式中的标签被保护](FAQ/TagProtected.html)

[消息：应当是方程或方程列表，而不是True](FAQ/TrueFalseEquation.html)

一般表达式还是列表索引？

[在数值函数定义中使用要求形式参数的函数](FAQ/SetDelayedAndSymbolsAsSlots.html)

#### 进阶

定义的自动排序

编译法则

`Paclet` 镜像

### 数学计算

#### 入门

`Dot` 和矩阵乘法

`FourierTransform` 的 `FourierParameters` 选项

符号矩阵/维度数未定的矩阵

`Abs'`

#### 进阶

`WorkingPrecision` 和 `PerformanceGoal`

[FindRoot 的 Evaluated 选项与 NumericQ](FAQ/NestedNumericalComputation.html)

自定义概率分布

避免 `DSolve` 使用逆函数

### 可视化

#### 入门

空白绘图

#### 进阶

提高绘图质量

### Mathematica

#### 入门

`$OutputForms`

下标

上下文：自建笔记本、帮助文档之间的变量共享

#### 进阶

内置调试器

### 安装与运行

## 精品教程

### 通用知识

[从前端到后端再到前端：Mathematica 表达式计算的前世今生](Tutorial/FrontEndAndKernel.html)

为什么应当避免使用下标？难道这个功能没有实际意义？

Wolfram语言内置函数与自定义函数的设计范式

### 常见的专门化需求

定制你的前端