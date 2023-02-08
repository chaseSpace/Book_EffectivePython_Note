# Book_EffectivePython_Note

本笔记对应书籍《EffectivePython》第二版（译），第二版只关注Python3（3.0\~3.8）。

### 书籍介绍

《EffectivePython》 [ 美 ] **Brett Slatkin** 著 爱飞翔 译  
- 编写高质量Python代码的90个有效方法  
- 原书第二版
- 作者是谷歌首席软件工程师

### 目录介绍

- [第一章：培养 Pythonic 思维（已完成）](./0.培养Pythonic思维.md)
  - 查询自己使用的Python版本
  - 遵循PEP8风格指南
  - 了解bytes与str的区别
  - 用支持插值的f-string取代C风格的格式字符串与str.format方法
  - 用辅助函数取代复杂的表达式
  - 将数据结构直接拆分到多个变量里，不要专门通过下标访问
  - 尽量用enumerate取代range
  - 用zip函数同时遍历两个迭代器
  - 不要在for与while循环后面写else块
  - 用赋值表达式减少重复代码
- [第二章：列表与字典（更新中）](./1.列表与字典.md)
  - 学会对序列做切片
  - 不要在切片里同时指定起止下标与步长
  - 通过带星号的unpacking操作来捕获多个元素，不要用切片
  - 用sort方法的key参数来表示复杂的排序逻辑
  - 不要过分依赖给字典添加条目时所用的顺序
  - 用get处理键不在字典中的情况，不要使用in与KeyError
  - 用defaultdict处理内部状态缺失的元素，而不要用setdefault
  - 学会利用__missing__构造依赖键的默认值