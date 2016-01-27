# PL0-compiler-SLR
a simple compiler of PL/0 by Java
这是一个采用SLR分析方法实现的简单的PL/0编译器，采用Java语言

主要实现了： 

1. 词法分析
2. 语法分析
3. 语义分析（未采用完整的语法制导翻译所以语义部分还不太完善）
4. 模拟运行

此编译器特殊之处在于实现了部分Yacc的功能，所以可以通过动态的修改文法来改变语言的语法规则
  
