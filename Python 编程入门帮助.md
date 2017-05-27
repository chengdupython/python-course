# 文档目的
说明：本文档主要针对从零开始学习 Python 编程语言进行各个相关方面的介绍，主要是围绕 Web 开发方面。为起步带来一些帮助，同时也收集一些资料、链接，作为一个参考文档。  
注意：部分链接需要翻墙才能打开，如果还是打不开，Google是你的好朋友，有时候Bing也是，而百度知道可以查下火车票什么的……

# Web开发指南和参考（Python）
## 关于环境和语言的选择
说明：编程的主要工具，一是语言，二就是IDE/编辑器。Windows下强烈建议安装一个 Linux 虚拟机（如 Ubuntu ），可以用 Virtualbox，也可以用 Vmware。关于编辑器，强者当然都用VIM或者Emacs啦，完全可以无视这里的介绍。

1. Python 的版本问题
最新版是Python 3.6，上一个主流版本是2.7.
由于 Python 3 对 2的不兼容，因此不少库在 3上还无法使用。但3是大势所趋， Django目前已经支持3，入门的话最好是从3开始。不过也可以双修双练。

2. Python 二三事
[面向初学者介绍Python相关的一些工具，以及可能遇到的常见问题][1]

3. 程序员的好伙伴

IDE 的话推荐 PyCharm 社区版免费，包括了 virtualenv, 版本控制等集成支持，收费版还支持 Django。
[介绍 Windows 环境下的文本编辑器，命令行的使用，版本控制软件以及相关话题][2]
[程序员的完美文本编辑器 － Sublime Text2][3]

## 入门教程
说明：从Python开始，Django是web开发的框架，主要使用Python语言，同时需要基本的web开发知识，如http链接，响应等。

1. 笨办法学 Python
《笨办法学 Python》(Learn Python The Hard Way)是 Zed Shaw 编写的一本 Python 入门书籍。适合对计算机了解不多，没有学过编程，但对编程感兴趣的朋友学习使用。
链接1：
http://lpthw-cn.ducktypist.com/en/latest/index.html
链接2：
http://readthedocs.org/docs/learn-python-the-hard-way-zh\_cn-translation/en/1.0/index.html

[PDF download][4]
Instagram 创始人的女朋友 Kaitlyn Trigger 为情人节学编程，创建 Lovestagram，教材是[learn python the hard way]http://t.cn/a9qdKx），[中文版在这里][5] 没有任何编程基础的朋友们可以开始了。
2. Python 3 入门
dive into python 3中文版, 里面的例子很不错，从一个处理罗马数字的实例开始，一步步进阶。
http://code.google.com/p/openbookproject/downloads/detail?name=diveintopython3-zh.7z&can=2&q=#makechanges
3. Django 入门
[官方文档（含入门教程）][6]
从 Django 1.11版本开始
[Django book 在线][7]
下载版本：[Django 入门、进阶必读《DjangoBook2.0》中文版\_redice's Blog][8]
**Django 实践**
[Django专栏   \[ 推荐阅读 ]][9]  
Django实战，Django与Ruby on Rails (RoR)的对比，深入Django框架。 这里提到的针对代码写测试，是很好的开发习惯！值得重视。

[介绍 · Django Girls Tutorial][10]

[rosarior/awesome-django: A curated list of awesome Django apps, projects and resources.][11]

3. 进阶：版本管理和协同开发
Git and Github
4. Web开发基础
[参考知乎上面的][12]
> 网站开发开发大概分为前台和后端，前台又可以分为美工，交互设计，js编程。后端了解不多，前端的话，可以按如下思路学习系统学习：
> 
> 基础知识： 
> 1. html + css 这部分建议在 www.w3school.com.cn 上学习，边学边练，每章后还有小测试。之后可以模仿一些网站做些页面。在实践中积累了一些经验后，可以系统的读一两本书，推荐《head first html 与 css 中文版》，这本书讲的太细了，我没能拿出耐心细读。你可以根据情况斟酌。 
> 2. javascript 要学的内容实在很多，如果没有其他编程语言的基础的话，学起来可能要费些力，还是建议先在 w3school上学习。之后建议马上看《javascript语言精粹》，js是一门很混乱的语言，这本书能够帮助你区分哪些是语言的精华，哪些是糟粕，对于语言精华，应该深入学习。糟粕部分能看懂别人写的代码就行，自己就不用尝试了。
> 进阶：
> 有了以上基础，就可以进行一般的静态网页设计，不过对于复杂的页面还学进一步学习。
> 1. css。必看《精通css》，看完这本书你应该对：盒子模型，流动，block，inline，层叠，样式优先级，等概念非常了解了。作为练习可以看下《css艺门之匠》这本书，它对标题，背景，圆角，导航条，table，表单等主题都有详细的介绍。
> 2. javascript。上面提到内容还不足以让你胜任js编程。在有了基础之后，进一步学习内容包括：
> a) 框架。推荐jQuery，简单易用，我的第一web项目就是在w3school简单学习后，直接上手jQuery完成的，真的很简单，很好用。jQuery适用环境有限，对于那些对性能要求很高的页面无法胜任。推荐了解一下 YUI 或百度的 tangram ，都很好用，学习方法也很简单，照着产品文档做几个页面就行了，不用面面俱到，以后遇到问题查文档就行了。框架可以帮你屏蔽浏览器的差异性，让你能更专注与web开发学习的精髓部分。
> b) javascript 语言范式 。这个名字可能并不恰当，只是我找不到可以描述“面向对象”，“函数式”这个两个概念的概念。javascript不完全是一个面向对象的语言，它的很多设计理念都有函数编程语言的影子，甚至说如果你不用面向对象，完全可以把它理解成一门函数式编程语言。javascript的很多语言特性，都是因为他具有函数是语言的特点才存在的。这部分推荐先学习面向对象的基本理论，对封装，继承，多态等概念要理解，维基百科，百度百科会是你的帮手，另外推荐《object oriented javascript》，应该有中文版。对与函数式编程我了解的也不系统，不好多说，可以自己百度一下。
> c) javascript 语言内部机制。必须弄清如下概念：js中变量的作用域，变量传递方式，函数的定义环境与执行环境，闭包，函数的四种调用方式（一般函数，对象的方法，apply，call），以及四种调用方式下，‘this'指向的是谁。这部分内容你会在《javascript语言精粹》中详细了解。另外，你必须理解json。
> d) dom编程，这个web前端工程师的核心技能之一。必读《dom编程艺术》，另外《高性能javascript》这本书中关于dom编程的部分讲的也很好。
> e) ajax编程，这是另一核心技术。ajax建议在网上查些资料，了解这个概念的来龙去脉，百度百科，维基百科上的内容就足够了。真正编程是很容易的，如今几乎所有框架都对ajax有良好的封装，编程并不复杂。
> f) 了解浏览器差异性。这部分包括css和js两部分，浏览器差异内容很多，建议在实践中多多积累。另外对于浏览器的渲染模式，DOCTYPE等内容应该系统学习。
> 再进一阶：
> 有了以上知识，对于大多数小型网站，你应该已经可以写出能够工作的代码了。但写出可以运行的代码，只是编程的最初级阶段。更高要求大概还有三方面：1易维护，2可测试，3高性能，如果页面流量有要求，那第四个就是，4低流量。 
> 1. 易维护。对于页面你该理解‘样式’，‘数据’，‘行为’三者分离，对应的当然就是css,html,js。对于js代码，你最好了解设计模式，重构，MVC等内容。
> 2. 可测性。js代码可测性的主题，我正在研究，欢迎感兴趣的同学联系我，共同学习
> 3. 高性能。必读《高性能javascript》
> 4. 低流量。技巧性太强，非一朝一夕之功，不多说\> 
> 补充：
> 对于前端开发，核心部分基本就这些了，可以根据自己的兴趣爱好选择性学习以下内容。
> 1. 美工。 大公司都有专业的美工人员，不过如果爱好也可以了解
> 2. 交互设计。大公司依然有专业人士搞这些，不过如果爱好也可了解。推荐《简约至上》。
> 3. 后端。应该说前段工程师必须至少了解一门后端语言，不过如果爱好也可深入学习，入手难度比较低的应该是php了。这部分由可分为基于页面，基于框架两种。大型项目都是基于框架开发的，建议至少了解一个MVC框架，php的zend，asp.net 的 asp.net mvc等等太多了，好还框架的设计思想都大同小异。
> 4. flash。我并没有吧flash作为前端工程的核心技能之一，因为我不会，不过ActionScript应该和js大同小异，可以根据工作需要学习。不过我的原则是能不用就尽量不用，其实很多效果通过js，css都可以实现，完全不需要flash。而且随着html5的发展flash早晚会淘汰。
> 5. html5和css3 。html5的标准到现在还没有正式发布，不过目前几乎所有新的浏览器都已经开始支持，手机上就更是如此，建议学习，很好，很强大。

# 参考信息
## 网络资源

这个不错，有中文翻译
http://pycoders-weekly-chinese.readthedocs.org/en/latest/index.html

书单

## 涉及技术
开发工具Develop tools: Python + Django + PostgreSQL (or MySql)  
开发环境：Server base: Linux(Debian) + Nginx(or Apache)

[1]:	http://pre-sence.com/archives/python-intro/
[2]:	http://pre-sence.com/archives/programmers-pals/
[3]:	http://gchen.cn/2011/12/ten-amazing-features-of-sublime-text-2/
[4]:	http://cdn.bitbucket.org/gastlygem/lpthw/downloads/LearnPythonTheHardWay.pdf
[5]:	http://t.cn/a9bXAm
[6]:	https://docs.djangoproject.com/en/1.11/
[7]:	http://djangobook.py3k.cn/2.0/
[8]:	http://www.redicecn.com/html/blog/Django/2011/0501/267.html
[9]:	http://blog.csdn.net/column/details/django.html
[10]:	https://tutorial.djangogirls.org/zh/
[11]:	https://github.com/rosarior/awesome-django
[12]:	http://www.zhihu.com/question/19834302?nr=1&noti_id=14349372#723217
