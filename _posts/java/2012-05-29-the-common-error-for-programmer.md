---
layout: post
title: 程序员看法上的几个典型错误
description: 今天我不谈抱负理想，也不谈具体的技术，我来谈几个看法上的典型错误。下面的这些问题都是我曾经遇到，或者是我的朋友们遇到过的问题，这些都是我个人的理解，希望对大家有帮助。
keywords: 程序员, 编程, 错误
category : other
tags : [程序员]
---

今天我不谈抱负理想，也不谈具体的技术，我来谈几个看法上的典型错误。
下面的这些问题都是我曾经遇到，或者是我的朋友们遇到过的问题，这些都是我个人的理解，希望对大家有帮助。


## 关于设计模式、设计原则

有人认为，熟悉了设计模式、设计原则，就学会了设计。
其实，设计模式和设计原则，只是前人根据设计实践做的总结和提炼，**设计，归根到底是要解决问题的，把具体问题的解决办法，经过一定的抽象，变成程序员的语言**。

我见过一些人，他们知识渊博、见识广博，甚至理论可以给你阐述得冠冕堂皇，但是到了实际需要解决问题的时候，他们却拿不出巧妙的、优雅的办法，这是典型的象牙塔人。

另一方面，也有一些人看不起学习设计模式的人，他们觉得他们已经掌握了软件设计的奥义，这些对他们来说是毫无意义的词汇，对此大可以一笑置之。

有时候我们**反而被设计模式或设计原则粗暴的掌握束缚了手脚**，譬如我遇到这样一件事情，某位努力的程序员，设计的代码用遍了组合（例如把User对象放置到Administrator里面），
我好奇地问，有一些类和对象之间的关系很明显符合继承的特征，为什么不愿意用它？他说，设计原则告诉我们，要多用组合，少用继承。
我想，对这些优秀的模式、原则、方法论，如果不能透彻地掌握，不能根据实际场景合适地运用，是不是反而不如对其不了解来的好呢？


## 关于多种计算机语言的学习

有人觉得学习一种语言就可以了，学习那么多语言没有必要。
事实上，**多掌握一门合适的计算机语言不仅仅是多掌握一种谋生的工具**，如果一种新的语言能够很大程度上改变你对编程、对设计的看法，那么兴许它就值得你去学习。

譬如C语言，可以培养严谨的思维；譬如动态语言，它可以帮助程序员更好地做面向对象的coding；譬如函数式语言，它在工业生产、运算领域有着不可替代的作用。

当然话说回来，所谓术业有专攻，对于某一门计算机语言（包括该语言所需的运行时环境、其中的编译或解释的原理）深入的掌握，是很有必要的。

另外，我们时常看到诸多计算机语言孰优孰劣的争论，计算机语言归根到底是一种工具，工具是随着时代发展升级和变更的，单纯的优劣争论没有太大意义。



## 关于英语

中国人为什么要学英语，程序员为什么要学英语，当我把那些方法名、变量名全部取成拼音，一样可以，谁下的这个破规定？

遗憾的是，诸多学习材料、论文、技术资料（尤其是一些刚出不久的技术），都是英语的；
另一方面，国际标准、程序员交流的通用方式，都是英文的，我想肯定很难想象，那些有名的framework、lib的源码，如果用拼音来写变量名会成什么样子。

所以，**如果你的英语不好（至少读写不好），就不要给自己找太借口，英语是一个掌握其他工具的工具**，除非你坚信，中文很快就会在计算机界变成世界第一通用的语言。



## 关于算法

算法有多重要，这一件事的争议一直都很大。

软件归根到底是用来解决问题的，提到算法就不能不提到数学（这也是为什么很多软件领域的大师都具备相当的数学背景），对于解决问题，这里可以简单归纳成两步：

1. 把实际的问题抽象成简化的数学模型;
2. 用算法去解决这个数学问题;

算法，在这里应该是一个广义的概念（这里的算法并不仅仅指大学里学习的狭义的具体算法），**算法是解决上述数学问题的办法**。
如果工作中你并未意识到它的存在，那只是说明，你抽象出的数学模型比较简单，解决这个模型的办法也很简单，或者有现成的方式可以模仿，或者有现成的框架帮你完成了，以至于你不去关注它、在乎它。

如果你做的事情是充满创新意义的，是别人从没有做过的，这时候算法兴许就成了决定你成败的因素。

在当前中国的环境下，视野广阔和经历丰富的人很好找，但是企业要招到具备上述两点能力来解决问题的人，其实是非常困难的。

## 关于经验

唯经验论者的人有很多，他们认为，在软件企业的职位、薪水、甚至决策能力，都取决于经验，一个5年经验的工程师，肯定比3年经验的工程师能找到更好的饭碗：

> “我是老员工，我工作5年了，凭什么工作3年的他薪水比我高那么多”

实际上，很多因素，包括领域积累（这是业务上的，例如互联网领域、传统软件领域，这和所谓的纯技术没有直接关系）、视野、承受压力的能力等等往往都在很大程度上取决于“经验”的积累，但是，这并不是绝对的。
有句话叫做“事业一半是干出来的，一半是总结出来的”，也确实有一些出色的程序员，他们**善于总结、善于观察和积累，并且善于不断地思考**，这样的程序员就是拥有更多优秀的经验。

另一方面，程序员是要来解决问题的，经验不能代替解决问题，有的人具备更优秀的解决问题的能力，他为什么就不能得到更优厚的薪水？

