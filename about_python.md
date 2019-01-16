# 关于Python（About Python）

Python是一种可以做到 _简单_ 且 _强大_ 的定义的语言。你会自己惊喜地发现，把注意力集中在解决问题上是多么容易，而不是集中在你正在编程的语言的语法和结构上。

Python官方介绍是这样的：

> Python是一种易于学习、功能强大的编程语言。它具有高效的高级数据结构和一种简单但有效的面向对象编程方法。Python优雅的语法和动态类型，加上它的解释性质，使它成为大多数平台上许多领域中脚本编写和快速应用程序开发的理想语言。

在下一节中，我将更详细地讨论其中的大部分特性。

## 这个名字背后的故事（Story behind the name）

Guido van Rossum，Python语言的创造者，是以BBC节目“Monty
Python's Flying Circus”命名的。他特别不喜欢蛇类通过缠绕杀死动物作为食物。它们长长的身体环绕着它们，把它们压扁。

## Python的特性（Features of Python）

### 简单（Simple）

Python是一种极简的语言。读一个好的python程序就像读英语，虽然是很严格的英语！Python的这种伪代码特性是它最大的优点之一。它允许您集中精力解决问题，而不是语言本身。

### 易于学习（Easy to Learn）

如你所见，Python非常容易入门。正如上面提到过的，，Python有非常简单的语法。

### 免费和开源（Free and Open Source）

python是一个 _FLOSS_（免费和开源的软件）的例子。简单地说，您可以免费分发此软件的副本，读取其源代码，对其进行更改，并在新的免费程序中使用其中的部分。FLOSS是基于一个共享知识社区的概念。这就是为什么Python如此优秀的原因之一——它是由一个只想看到更好的Python的社区创建并不断改进的。

### 高级语言（High-level Language）

当你用Python编写程序时，你不需要为低级的细节而烦恼，比如管理程序使用的内存等等。

### 可移植性（Portable）

由于其开源特性，Python被移植到许多平台上（也就是说，为了让它在上面工作而进行了更改）。如果您足够小心地避免任何依赖于系统的特性，那么所有的Python程序都可以在这些平台上工作而不需要任何更改。

您可以在GNU/Linux, Windows, FreeBSD, Macintosh, Solaris, OS/2, Amiga, AROS, AS/400, BeOS, OS/390, z/OS, Palm OS, QNX, VMS, Psion, Acorn RISC OS, VxWorks, PlayStation, Sharp Zaurus, Windows CE and PocketPC上使用Python！

你甚至可以使用 [Kivy](http://kivy.org) 这样的平台为你的电脑创建游戏，也可以为iPhone、iPad和Android创建游戏。

### 解释性（Interpreted）

用C语言或C++编写的程序从源语言（C或C++）转换成计算机的语言（二进制代码，即0和1），编译器使用各种标志和选项。运行程序时，链接器/加载程序软件会将程序从硬盘复制到内存并开始运行。

另一方面，Python不需要编译为二进制。您只需直接从源代码运行程序。在内部，Python将源代码转换为称为字节码的中间形式，然后将其转换为计算机的本机语言，然后运行它。实际上，所有这些都使得使用Python变得更加容易，因为您不必担心编译程序，确保正确的库被链接和加载，等等。这也使得您的Python程序更加具有可移植，因为您可以将您的Python程序复制到另一台计算机上，它就可以工作了！
### 面向对象（Object Oriented）

Python支持面向过程的编程和面向对象的编程。在面向过程的语言中，程序是围绕程序或函数构建的，这些程序或函数只是程序的可重用部分。在面向对象的语言中，程序是围绕结合了数据和功能的对象构建的。Python有一个非常强大但简单化的OOP方式，尤其是与C++或Java等大型语言相比。

### 可扩展性（Extensible）

如果您需要一段关键的代码来运行得非常快，或者希望某段算法不被打开，您可以用C或C++编写程序的那部分代码，然后从您的python程序中使用它。

### 可嵌入式（Embeddable）

您可以将Python嵌入C/C++程序中，为程序的用户提供 _脚本_ 功能。

### 齐全的软件库（Extensive Libraries）

The Python Standard Library is huge indeed. It can help you do various things involving regular expressions,documentation generation, unit testing, threading, databases, web browsers, CGI, FTP, email, XML, XML-RPC, HTML, WAV files, cryptography, GUI (graphical user interfaces), and other system-dependent stuff. Remember, all this is always available wherever Python is installed. This is called the _Batteries Included_ philosophy of Python.

Besides the standard library, there are various other high-quality libraries which you can find at  here [Python Package Index](http://pypi.python.org/pypi).

Python标准库确实很大。它可以帮助您执行各种操作，包括正则表达式、文档生成、单元测试、线程、数据库、Web浏览器、CGI、FTP、电子邮件、XML、XML-RPC、HTML、WAV文件、加密、GUI（图形用户界面）和其他与系统相关的内容。记住，所有这些在安装python的任何地方都是可用的。这被称为“功能齐备”的Python哲学。

除了标准库，[这里](http://pypi.python.org/pypi) 还有很多其他高质量的软件库
### 简介（Summary）

Python确实是一种令人兴奋和强大的语言。它有正确的性能和特性组合，使得用Python编写程序既有趣又简单。

## Python 3和2对比（Python 3 versus 2）

如果您对 Python 2 和 Python 3 之间的区别不感兴趣，可以忽略此部分。但是请注意您使用的是哪个版本。这本书是为 Python 3 编写的。

记住，一旦你正确理解并学会使用一个版本，你就可以很容易地学习到不同之处并使用另一个版本。最困难的部分是学习编程和了解Python语言本身的基础知识。这是我们在本书中的目标，一旦您达到了这个目标，您就可以根据您的情况轻松地使用Python 2或Python 3。

一下是有关python 2和python 3之间差异的详细信息：

- [Python 2的未来](http://lwn.net/Articles/547191/)
- [将Python 2代码移植到Python 3](https://docs.python.org/3/howto/pyporting.html)
- [编写在Python2和3下运行的代码](https://wiki.python.org/moin/PortingToPy3k/BilingualQuickRef)
- [支持Python 3：深入的指南](http://python3porting.com)

## 程序员怎么说（What Programmers Say）

你可能会发现阅读像ESR这样的伟大黑客对Python的评论很有趣：

- _埃里克·S·雷蒙德_ 是《大教堂和集市》("The Cathedral and the Bazaar")的作者，也是“开源”一词的创造者。他说[Python已经成为他最喜欢的编程语言](http://www.python.org/about/success/esr/)。这篇文章是我第一次使用Python时的真正灵感。

- _布鲁斯•埃克尔勒_ 是著名的“Thinking in Java”和“Thinking in C++”书籍的作者。他说没有任何一种语言能让他比Python更有效率。他说，Python可能是唯一一种专注于使程序员更容易操作的语言。阅读[完整访谈](http://www.artima.com/intv/aboutme.html)了解更多详细信息。

- _Peter Norvig_ 是著名的Lisp作者和谷歌搜索质量总监（感谢Guido van Rossum指出这一点）。他说[写python就像用伪代码写一样](https://news.ycombinator.com/item？ID＝1803815)。他说，python一直是谷歌不可或缺的一部分。您可以通过查看[Google Jobs](http://www.google.com/jobs/index.html)页面来验证此声明，该页面将python知识列为软件工程师的要求。
