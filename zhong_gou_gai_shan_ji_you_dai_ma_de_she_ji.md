# 重构改善既有代码的设计

重构是在不改变软件可观察行为的前提下改善其内部结构

## 1.重构第一个案例

重构步骤

1. 写好测试,保证输入输出一致
2. 提取冗长的`switch`
3. 每次修改的篇幅尽量原子,更容易发现错误
4. 重构时,变量改名也重要.
5. 函数应该放在它所使用的数据的所属对象内
5. 去除临时变量
6. 对于常改复杂的switch,建立多态取代switch

## 2. 重构原则

重构: 对软件内部结果的一种调整,目的是在不改变软件可观察行为的前提下,提高其理解性,降低其修改成本

重构的意义

1. 让代码更有结构性
2. 消除重复代码 
3. 把设计模式看出来
4. 重构帮助找到BUG
5. 重构能提高编程速度

何时重构 : 随时随地的进行

基本情况是一下三种,但这三种基本伴随着项目生命周期

1. 添加功能时 : 当我添加功能感觉到困难时,我就会尝试重构能否给我带来便利
2. 修补错误时重构 : 当调试时无法理解代码,就用重构加深自己的理解