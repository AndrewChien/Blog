<img src='https://github.com/AndrewChien/Blog/blob/master/source/photo.png' align='right'/>

# 引子

&emsp;&emsp;突然发现简书上面有很多好文章！</br>

&emsp;&emsp;最近我在学习MarkDown语法，找着就找到简书上的几篇文章 [Markdown基本语法](https://www.jianshu.com/p/191d1e21f7ed)、[Markdown 语法整理大集合2017](https://www.jianshu.com/p/b03a8d7b1719) ，于是想来练习一下。正好GitHub支持MarkDown语法，且 [johnnian](https://github.com/johnnian/Blog) 等作者正好有文章 [如何用Github Issues写技术博客？](https://www.jianshu.com/p/7c2cce028d29) 是介绍GitHub博客的，于是我的小店正式开张！</br>

&emsp;&emsp;所以以后就在GitHub写博客了，本博客以技术博客为主。。</br>

&emsp;&emsp;以下为博客目录：

- [Python](https://github.com/AndrewChien/Blog/projects/1)
- [.NET](https://github.com/AndrewChien/Blog/projects/2)
- [C++](https://github.com/AndrewChien/Blog/projects/3)
- [JAVA](https://github.com/AndrewChien/Blog/projects/4)
- [框架与工具](https://github.com/AndrewChien/Blog/projects/6)
- [杂谈](https://github.com/AndrewChien/Blog/projects/5)

------

# 技术类

## Python

&emsp;&emsp;我之所以把Python放在第一位，首先当然是我最近正在使用它，并且对它评价很高！这门语言真的是缩进了普通人与以往人们脑海中程序员（写C++、Assembly的那种）的距离。

&emsp;&emsp;我准备用Python来做蜘蛛和图像处理类工具，当然还有日常可以用到的其它部分。

### Python蜘蛛
* [python学习经典例子（涵盖bs、lxml、re、pool等各种基本蜘蛛技术）](https://github.com/AndrewChien/PythonSpiders)
* [用selenium+ocr对某网盘下载网站进行有验证码登录和自动连续下载文件](https://github.com/AndrewChien/Blog/issues/1)

### PyQt开发


## .NET

&emsp;&emsp;emm，我是做C#起步的，虽然大学入门语言是c、c++，大学也学过java，但第一份工作用的是c#。怎么说呢？两个字，感激。且今天dotnet core的出现真的是让我大开眼界，dotnet core的未来无疑将是无比灿烂和辉煌的。

### dotnet core
* [用蜘蛛抓取的资源组建的一个XX网站（你懂得）](https://github.com/AndrewChien/EvilLyo)

### web服务器
* [C#写的运行asp.net的小型web服务器，替代iis的那种](https://github.com/AndrewChien/LyoServer)

### 商城及后台管理
&emsp;&emsp;本来我是不做商城及网站后台类的管理软件，NFine缘起于QQ群及现实中的一位朋友：[飞天](https://github.com/Feaskye)以及他的商用后台管理框架[SkyMallCore](https://github.com/Feaskye/SkyMallCore)
* [dotnet core+mysql改良版的NFine框架]()

### P/Invoke技术
* [是我做过的最复杂的P/Invoke例子，掌握了基本上不惧任何P/Invoke](https://github.com/AndrewChien/EVRCTest)

### c#蜘蛛
* [C#其实也适合做蜘蛛，只不过没有Python蜘蛛那么耀眼](https://github.com/AndrewChien/SharpSpider)

### 工业级开发
* [C#的净土：上位机开发](https://github.com/AndrewChien/SharpModbus)
* [古老的wince开发技术](https://github.com/AndrewChien/SharpWinceDemo)
* [工业大数据平台（以前公司所做，未完工）](https://github.com/AndrewChien/MaintenancePlatform)

### 其他demo
* [C#经典异步：AsyncAwait](https://github.com/AndrewChien/SharpAsyncAwaitDemo)

## C++

&emsp;&emsp;c++，传说中高级语言里面最难的。它难不是难在语法，而是难在想熟练掌握它，你必须首先对你的操作系统要相当的熟悉！在windows大行其道的时候，人们学MFC真的是苦！第一，windows不是开源的，遇到了一些疑难杂症想解决它真的是千辛万苦；第二，windows一向以来都是以严谨著称，他的技术框架基本上都是以大型、封装、复杂的为主。windows的开发文档读起来心有余悸！

&emsp;&emsp;但是，这里我还是要说一句，没有掌握C++的程序员，都不是真正的程序员！

### OpenCV
* [人脸识别及运动检测](https://github.com/AndrewChien/FaceAndMoveDetect)

### QT开发
* [LyoGo围棋游戏大厅](https://github.com/AndrewChien/LyoGo)

## JAVA

&emsp;&emsp;java，这门中国目前使用最多的语言，的确优秀！并不是语法优秀、并不是本身超越时空，而是它的生态圈太好了！当所有人都围着它转的时候，他不想耀眼都难！（想想苦命的.net，要是微软当初在c#刚创建的时候就开源，哪有今天java的事。。。）

&emsp;&emsp;java的语法，又丑又难用。使用过c#的人，真的不愿意再使用这个语法。但很多时候并不是什么好用就能决定它的地位的，而是使用者的数量决定的。

&emsp;&emsp;在当今JDK1.8以上版本需要收费以后，java使用者要么停滞在1.8版本，要么逼着你使用openjdk，openjdk创建至今为时不短，但为什么没能像oracle jdk这么使用普遍，大家心里有数，无疑是不好用、有bug、维护困难等等开源软件的通病。另外，java是使用GPL这个有传染性的开源许可的，其对企业的适用性明显比不上MIT/Apache2协议（如dotnet core使用的是这种，这也给了dotnet core一个挽回开发者和公司使用者的机会，参考张善友的文章 [[年末展望：Oracle 对 JDK收费和.NET Core 给我们的机遇](https://www.cnblogs.com/shanyou/p/10198757.html) ，这是题外话）。

### jni与jna
* [jna示例](https://github.com/AndrewChien/JavaInvokeDemos)
* [复杂情况下的jna调用技术](https://github.com/AndrewChien/ComplexJnaInvoke)

## 框架与工具

&emsp;&emsp;一些平时使用到的架构、框架及工具的使用易出错的地方等记录。



# 杂谈

&emsp;&emsp;扯淡。
