# 第二十一章

命令模式（Command）：将请求与实现解耦，并封装成独立对象，从而使不同的请求对客户端的实现参数化。

* 1.js - 命令模式

命令模式是将执行的命令封装，解决命令的发起者与命令的执行者之间的耦合。每一条命令实质上是一个操作。命令的使用者不必要了解命令的执行者（命令对象）的命令接口是如何实现的，命令式如何接收的，命令式如何执行的。所有的命令都被存储在命令对象中。

命令模式的有点自然是解决命令使用者之间的耦合。新的命令很容易加入到命令系统中，供使用者使用。命令的使用具有一致性，多数的命令在一定程度上是简化操作方法的使用的。

命令模式是对一些操作的封装，这就造成每执行一次操作都要调用一次命令对象，增加了系统的复杂度。