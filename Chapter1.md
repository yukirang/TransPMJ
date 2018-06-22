# 第一章 ECMAScriptt 和JavaScript的未来

JavaScript已经从1995的营销策略中获得了策略优势，成为2017年世界上应用最广泛的应用程序运行时平台上的核心程序设计经验。
它不仅能在浏览器中运行，而且还用于在硬件设备中，甚至是NASA的宇航服设计中创建桌面和移动应用程序。
JavaScript是如何成功的，接下来又将如何发展呢？

## Javascript标准简史

早在1995年，Netscape公司就设想过一个HTML无法实现的动态网络。
布兰登·艾奇被引入Netscape后，他开始开发用于浏览器的，功能类似于Scheme的语言。
他加入时，得知上级管理层希望它看起来像Java。他们之间的协议就此开始。

布兰登用Scheme的优秀函数和Self的原型为主要原料，在10天内创建了第一个JavaScript原型。JavaScript的初始版本代号为Mocha。它没有数组或对象，并且每个错误都会引起警告（alert）。缺少异常处理是到今天为止许多操作都会导致NaN或undefined的原因。布兰登在0级DOM和JavaScript第一版上的工作，为标准化工作奠定了基础。

1995年9月，JavaScript版本LiveScript被应用于Netscape Navigator 2.0 beta版。1995年12月，在Navigator 2 Beta 3发布时，它被重命名为JavaScript（由Sun公司商标化，现在归Oracle所有。这次发布后不久，Netscape推出了用于Netscape Enterprise Server脚本的服务器端JavaScript，并将其命名为LiveWire.[1] JScript，微软的反向工程JavaScript实现，于1996年捆绑的IE3。JScript是可用的Internet服务器端信息服务器（IIS）。

1996年，ECMA的技术委员会（TCMA）将JavaScript在ECMA-262规范中的ECMAScript名称（ES）下进行了标准化。Sun公司不会把JavaScript商标所有权转让给ECMA。当微软提出JScript时，其他成员公司不愿使用这个名称，因而ECMAScript遇到了瓶颈。

微软的JScript和Netscape和的JavaScript这两种实现的争端，主导了当时大部分的TC39标准委员会会议。尽管如此，委员会仍然取得了成果：确立向后兼容性为一条黄金法则，提出严格的等于运算符（`===` 和`!==`)而不是打破现有的依赖于松散的相等比较算法（Equality Comparison Algorithm）的程序。

EMA-262第一版于1997年6月发布。一年后的1998年6月，经过国家ISO主体的大量审查，该规范在ISO/IEC 16262国际标准下细化，正式发布第二版。

于1999年12月发布的第三版，标准化了表达式、`switch`语句、`do`/`while`、`try`/`catch` 以及`Object#hasOwnProperty`，并伴有其他一些变化。这些特性中的大部分已经能够在Netscape的JavaScript运行时SpiderMonkey的自然环境下使用。

很快，ES4规范草案由TC39发布。在ES4上的早期工作促成了2000年年中发布的JScript.NET (你可以在微软页面(2000年7月)上阅读[原始声明](https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/scripting-articles/ms974588(v=msdn.10)))并最终促成了2006年发布的在Flash中使用的ActionScript 3。（在JavaScript JabBoT podcast中听布兰登·艾奇讨论JavaScript的起源）

关于JavaScript如何向前推进的冲突观点，使规范化的工作陷入瓶颈。对于Web标准来说，这是一个微妙的时期：微软几乎垄断了网络，并且对标准的发展毫无兴趣。

2003年，AOL解雇了50名Netscape员工，你可以从2003年7月的[The Mac Observer](https://github.com/mjavascript/practical-modern-javascript/blob/master/ch01.asciidoc)中读到一篇新闻报道。同年Mozilla基金会成立。当时超过95%的网络浏览市场份额在微软手中，TC39被解散。

现就职于Mozilla的布兰登花了两年时间，通过使用Firefox日益增长的市场份额作为杠杆来让微软重返市场，进行了ECMA的TC39复活工作。到2005年年中，TC39重启定期会议。对于ES4，有计划引入模块系统、类、迭代器、生成器、解构、类型注释、适当的尾部调用、代数类型和各种其他的特征。由于项目过于激进，ES4的工作被一再推迟。

到2007年，委员会被分为两个：对ES3和ES4提出了一个更为渐进的方法的ES3.1，以及过度设计并不足的ES4。直到2008年8月,几乎是ES3发布10年以后，布兰登·里奇才发邮件给ES讨论列表，总结了[现状](https://mjavascript.com/out/harmony)。当ES3.1被认可为前进方向后被改写为ES5。虽然ES4被放弃了，但它的许多特征最终被写入ES6（在该决议的时候被称为Harmony），而其中一些仍在考虑中，还有一些被抛弃、拒绝或撤回。以ES3.1更新作为基础，ES4规范可以在上面进行碎片化的修改。

2009年12月，在ES3发布10周年后，第五版EcMAScript发布。该版本对在浏览器实现中常见的语言规范进行了扩展，添加了GET和SET存取器、对数组原型的功能进行了改进、反思和内省，并提供了JSON解析和严格模式的本地支持。

几年后，在2011年6月，该规范再次被审查和编辑，成为国际标准ISO/IEC 16262:2011的第三版，并在ECMAScript 5.1中正式化。

TC39又用了四年的时间，于在2015年6月将ECMAScript 6正式化。第六版是对JavaScript最大的更新，并进行了出版。它实现了许多ES4提议，这些提议推迟成为和谐解决方案的一部分。在这本书中，我们将深入探索ES6。

References：

[1] A booklet from 1998 explains the intricacies of server-side JavaScript with LiveWire.
