## 1\. 了解 Lean🔗

按照惯例，介绍一门编程语言通常会编译并运行一个在控制台上显示「Hello, world!」的程序。这个简单的程序能确保语言工具安装正确，且程序员能够运行已编译的代码。

然而，自 20 世纪 70 年代以来，编程发生了许多变化。如今，编译器通常集成到了文本编辑器中，编程环境会在编写程序时提供反馈。 Lean 也是如此：它实现了语言服务器协议（Language Server Protocol，LSP）的扩展版本，允许它与文本编辑器通信并在用户键入时提供反馈。

从 Python、Haskell 到 JavaScript 等各种语言都提供 **读取-求值-打印-循环（REPL）** ， 也称为交互式顶层环境或浏览器控制台，可以在其中输入表达式或语句。然后，该语言会计算并显示用户输入的结果。另一方面，Lean 将这些特性集成到了与编辑器的交互中，它提供的命令能让文本编辑器将程序的反馈集成到程序文本中。本章简要介绍了在编辑器中与 Lean 的交互，而 [Hello, World!](https://www.leanprover.cn/fp-lean-zh/GettingToKnow/HelloWorld/#hello-world) 则描述了如何在批处理模式下以传统的命令行方式使用 Lean。

阅读本书最好的方式是在编辑器中打开 Lean，输入书中的每个示例并运行他们，然后看看会发生什么。

1. [1.1. 求值表达式](https://www.leanprover.cn/fp-lean-zh/GettingToKnow/GettingToKnow/Evaluating/#evaluating)
2. [1.2. 类型](https://www.leanprover.cn/fp-lean-zh/GettingToKnow/GettingToKnow/Types/#getting-to-know-types)
3. [1.3. 函数和定义](https://www.leanprover.cn/fp-lean-zh/GettingToKnow/GettingToKnow/FunctionsDefinitions/#functions-and-definitions)
4. [1.4. 结构](https://www.leanprover.cn/fp-lean-zh/GettingToKnow/GettingToKnow/Structures/#structures)
5. [1.5. 数据类型和模式匹配](https://www.leanprover.cn/fp-lean-zh/GettingToKnow/GettingToKnow/DatatypesPatterns/#datatypes-and-patterns)
6. [1.6. 多态性](https://www.leanprover.cn/fp-lean-zh/GettingToKnow/GettingToKnow/Polymorphism/#polymorphism)
7. [1.7. 附加语法](https://www.leanprover.cn/fp-lean-zh/GettingToKnow/GettingToKnow/Conveniences/#getting-to-know-conveniences)
8. [1.8. 总结](https://www.leanprover.cn/fp-lean-zh/GettingToKnow/GettingToKnow/Summary/#getting-to-know-summary)