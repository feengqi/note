# note
随时记录

- JS内存空间分为栈(stack)，堆(heap)，池(一般也会归类为栈中)，其中栈存放变量，堆存放复杂对象，池存放常量。
- 闭包中的变量并不保存在栈内存中，而是保存在堆内存中，这就是函数之后为什么闭包还能引用函数内的变量的原因。
- [JavaScript的Proxy可以做哪些有意思的事儿](https://zhuanlan.zhihu.com/p/69106037)
- [babel工作原理](https://mp.weixin.qq.com/s/iVD5KnCURo-dZis3FkN45A)
  - 1，Parse（解析）：将源代码转换成更加抽象的表示方法（例如抽象语法树）。
  - 2，Transform（转换）：对（语法树）做一些特殊处理，让它符合编译器的期望。
  - 3，Generate（代码生成）：将第二步经过转换过的（抽象语法树）生成新的代码。
