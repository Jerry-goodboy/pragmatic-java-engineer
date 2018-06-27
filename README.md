《Java工程师修炼之道》
--

<img src="img/book.png" width="180"/>

- [书籍](book)
- [代码](source)
- [勘误](https://github.com/superhj1987/pragmatic-java-engineer/wiki/Mistakes)


**已开源章节**

> - [1.1 后端基础设施](book/chapter1-servertech/server-basic.md)
> - [1.2 Java后端技术概览](book/chapter1-servertech/server-tech-tree.md)
> - [1.3 如何学习后端技术](book/chapter1-servertech/how-to-study.md)

[**购买链接**](https://item.jd.com/12325207.html)


### 后续计划

> 此书一开始是计划有一章专门讲述大数据开发技术，毕竟现在越来越多的公司在构建自己的大数据平台，大数据技术也逐渐成了Java工程师的必备技能。但自己此方面经验较少，自认并没有达到可以向别人输出知识的程度，于是暂时搁置此部分。

逐步把部分内容开源在此项目中，并补充一些新的内容进来。

- Zookeepr本来是想放在大数据一章，现在会作为数据存储的一节补充进来。
- 异步响应式Web框架会补充在开发框架一章，以Vert.x为主，Spring Flux为辅。
- Redis加入新版本的特性，并补充如何使用Redis实现分布式锁。
- Kafka加入最新版本的特性，尤其是Kafka Streams和Exactly one语义。
- Elasticsearch基于5.0版本更新。
- 补充协程到并发编程中。
- 补充Netty到网络编程中。
- 使用Hystrix做资源隔离和限流会补充在Java开发利器中。
- 补充RxJava的使用在Java开发利器中。
- 补充Java10和Kotlin的部分到Java新版本特性。

### 内容介绍

目前互联网行业如火如荼，进入这个行业的技术人员也越来越多。对于研发来说，从工程角度主要分为：前端工程师、客户端工程师（又分为iOS和Android工程师）、后端工程师、算法工程师等职位。本书所说的Java工程师指的是以Java做为主要开发语言的后端工程师。

从2008年还未毕业时做一些小的项目至今做后端开发已经有差不多十年时间。经历过刚学Java时的迷茫，第一次写出Java程序时的激动，第一次写出一个Web系统的醍醐灌顶，一直到接触到Java更底层的东西，对Java有了一个系统的认识，对后端技术体系有了一个宏观的感受。这期间，用过各式各样的编程语言，尝试过各种开源软件，挖过各种坑，也填过各种坑。就单单针对后端的技术来说，自己的这些知识体系，还是觉得是有一定价值的。

此外，还记得笔者毕业后进入第一家公司时，入职培训的课程对于自己来说虽然不难，但确实让自己有种恍然大悟的感觉。业界的最佳实践和自己在学校里学到的、使用到的差别还是非常大的。直到后来加入当前的这家公司，做过一系列后端技术的培训课程，并且在校招的笔试和面试过程中，深刻体会到了学校中的知识与业界脱节之严重，在平时的社招中也遇到很多对后端技术缺乏系统性认识、技能点不足的工程师们，也经常被人问起如何学习Java后端技术。于是就打算写一下目前后端工程师一些比较主流前沿的技术以及实际工作中会用到的一些技能并串联起来，给刚上大学以后打算以Java后端为职业的学生、刚毕业入职的应届生以及初学者们一些入门的指引，避免走一些弯路，也给一些有经验的工程师们提供一个参考手册将零散的知识点串起来，减少在解决某些实际问题时无头绪搜索带来的时间成本，同时也是对自己的一个阶段性总结和查漏补缺。需要注意的一点是，像数据结构、计算机网络等计算机科学基础知识以及JavaSE基本用法，笔者认为是从事程序开发工作的Java工程师应该必备的知识点，因此并不包括在内。

本书会针对Java后端开发工作中经常用到的关键技能点去做阐述，会尽量覆盖在实际工作中需要的所有技能点。但由于很多技能点并非一两篇文章就能讲述完成的，本书仅仅是做一些实践性的经验总结和阐述，更加详细和深入地学习则需要参考专门的书籍或者官方文档。**因此，如果是对内容深度有要求的读者，那么本书并不适合。**

本书的大部分内容都来自笔者的博客以及平时工作、学习中的一些自我总结和笔记，记录了笔者进入这个行业以来的一些经验教训和思考。

此外，笔者的学习、工作笔记是平时工作中查阅网上资料并经过辨伪后记录下来的零散知识点，难免会有一些对网上资料的引用，因此特别对这些资料的原创者表示感谢，如果有侵权可以联系我。

### 读者对象
>
>- 未入门或者刚入门的Java工程师
>
>    包括未来以Java后端开发为职业方向的在校学生、刚毕业入职的Java工程师以及未形成知识体系的Java工程师。通过阅读本书能够对Java工程师的必备技能有一个全局的认识，逐步形成自>己的Java技术体系。
>    
>- 有经验的Java工程师
>
>    有经验的Java工程师可以通过此书查漏补缺，巩固自己的开发技能，进一步加强自身的Java技术体系。
>    
>- 对Java后端开发感兴趣的非Java工程师
>
>    非Java工程师可以通过此书了解Java工程师的技能体系，尤其对于其他语言的后端工程师来说，本书的很多内容也是通用的，并不局限于Java开发。
>
### 内容概览
>
>- 第一章 后端技术导言
>
>    本章主要从总体上描述后端技术的概念、组成、作用、需要的知识点，并给出了学习后端技术的建议。
>
>- 第二章 Java项目工程化
>
>    本章主要讲述Java项目工程化需要掌握的软件、技能等。
>
>- 第三章 开发框架
>
>    本章主要讲述Java后端开发中的一些主流框架的使用。
>    
>- 第四章 Spring
>
>    本章主要讲述Spring核心、数据操作以及一些常用组件的使用。
>
>- 第五章 数据存储
>
>    本章主要讲述Java应用中数据存储上使用的一些软件、服务等。
>
>- 第六章 数据通信
>
>    本章主要讲述Java应用中数据传输、通信上使用的一些软件、服务等。
>
>- 第七章 Java编程进阶
>
>    本章主要介绍一些Java开发中的高级特性以及在Java开发中非常流行的类库。
>
>- 第八章 性能调优
>
>    本章主要讲述如何对Java应用的性能进行分析和调优，并给出了开发建议。
>    
>- 第九章 安全技术
>
>    本章主要对Java开发中常用的加密技术、HTTP以及防范各种攻击的方案做了阐述。

### 推荐

>2013年，我和本书作者的接触是从基于网易的一个大型互联网应用合作开始的，我见证了从第一行代码到整个系统服务于亿级用户的过程，并且相信这种经历对开发者来说是一笔巨大的财富，其中大量的开发和实战经验都会在本书中得到充分的体现，相信读者能从书中直接领略到丰富的实战知识。在与本书作者的合作过程中，其对Java技术的热爱与追求孜孜不倦，对问题刨根问底，直到理解透彻、灵活应用，这些都令我印象深刻。这些年，我与本书作者一直保持沟通交流、相互学习，他将近十年的实战经验沉底于本书以实现对后端技术的探索、布道，非常值得开发者与近高窗卧听秋。
>
>后端技术涉及内容非常广泛，Java语言也是互联网开发行业使用的主流语言，相信后续也将继续流行很长一段时间，而本书作者也一直从事Java后端开发工作。在本书中作者比较系统地从总体上描述了后端技术相关的理论知识，包括基础设施、网关服务及框架选型等基本原则，然后以实际经验进行示例说明，接着详细梳理了Java的后端技术，相信读者读完本书后会更全面地理解后端技术。互联网的业务建设需要不同角色的开发者共同协作完成，因此，系统工程化是开发者首先要共同遵守的规范或约定，包括代码规范、版本管理和代码质量检查等。
>
>开发框架的选型进一步地为工程化提供了基础，也能加速推进互联网开发，尽管是否重复造轮子是一个恒久的话题，但是没有永远的银弹，只要在合适的时间里根据团队的能力选择合适的技术框架就好。一般来讲，目前常用的框架包括基本的依赖注入、AOP、事务管理、连接池管理、数据操作、日志服务等，在众多的框架中，本书作者选用目前在Java领域使用最广泛的Spring做深入的分析，详细地说明各组件的基础知识、基本原理和实际使用案例，最难得的是把较多开发者遇到的坑都用真实的示例进行了说明，可以帮助开发者快速地跳过这些伤心地带，同时也把最佳实践画龙点睛地带给开发者。
>
>数据存储无疑是所有系统应用中非常重要的一环，应用的场景用例也和数据库的选型有极其重要的关系，开发者选择关系型数据库还是非关系型数据库是需要根据软件成本与人力成本来进行权衡的，比如是选择MySQL、Oracle等开源或商业的数据库。本书重点从数据库的基础知识、索引和表优化等方面以详尽的示例为更好地选择数据库的存储类型提供了更多的知识。

>早期的关系型数据库一般能满足数据达到一定规模的企业的需求，而在互联网业务领域，特别是移动互联网领域内的元数据或者日志数据等，达到亿数量级别是很常见的，这时通常使用非关系型数据库，在非关系型数据库里使用非常多的有MongoDB、HBase等分布式数据库系统。作者在自身的企业开发实践中，得到了大量的使用经验和最佳实践。为了加速后端应用，缓存热数据是加速业务、提高业务性能、提升用户体验的重要手段，通过使用本地缓存、远程缓存进行数据加速、数据预热或提高数据的命中率，是开发者在应用开发的过程中常会遇到的场景。
>
>“路漫漫其修远兮，吾将上下而求索”，后端技术每年都在不断发展，所用技术也有变化，近些年Java语言的发展速度不那么快了，但是总体是在不断前进发展的，本书作者带领的团队一直深耕此领域并希望通过本书为技术开发人员带来更多帮助。 
>
>-- **尧飘海，网易云基础服务（蜂巢）首席架构师**

---

>Hey！新来的读者，为了吸引你的注意力我真是煞费苦心，但最终还是没能写出一句特别吸引眼球的话来，毕竟写序的我不是标题党出生。此刻我真的非常能理解你拿到新书之后那渴望知识的心情，所以你恨不得一个字的“序”也不要看到，直接到达“最有价值”的知识点。但作为一名资深转业码农（对！你没看错，是“转业”，不是“专业”）还是想说一句，你先看完序，5分钟后到达知识的战场，会更稳！
>
>相信你已经在看“序”了，那么我们来说点正经事。
>
>你的知识体系的养成有3个关键阶段：看山是山、看山不是山、看山还是山。本书的适用人群是“看山不是山”的那些人，如果你恰好处于这个阶段，恭喜你！书钱没白花。
>
>Java是一门非常容易入门的语言，初学者经过初期的学习之后基本能掌握DEMO级别的编程应用。相信读者你已经度过了这个阶段，但是Java庞大的体系可能会把你绕晕，又或者你还没看到Java的生态系统有多么复杂。此时，你需要本书。从事程序员这个工作，到比较高阶的时候，其实是不挑语言的，语言只是工具，而你可以在纷繁复杂中游刃有余。但几乎每一位高手都是先深入一个领域，再横向发展的。你可以不用着急后续的横向发展，先坚定自己学习Java的信心！因为，从广泛的应用场景、顶级的开源生态、未来可期的薪水和职位来说，Java都是非常不错的选择。
>
>敲黑板，画重点！下面来解释一下，为什么本书面向的是“看山不是山”的人群。在度过Java的入门期之后，会有一个烦恼，那就是面对Java这么庞大的体系，我们究竟应该学习什么？选择方向，往往比努力更重要！是使用J2SE编写桌面程序？是使用J2ME编写嵌入式应用？还是使用J2EE编写企业级应用？这些是我们那个泛黄的年代特有的烦恼。而现在的烦恼可能是学Android？还是学Java后端？即便大方向你已经十分坚定，而且选择了Java后端编程，但因为复杂的知识体系和Google发布的各种教程文档，眼前看到的已经不再是清晰的山脉，而是一片迷雾。此时，你需要本书，因为它给你指明了努力的方向。
>
>本书的结构、阐述的方式和大部分的“指南”书籍有较大的区别，本书是以笔记和要点的形式进行呈现的，用现在的话说就是捞干货。本书涵盖的知识，是以现代工程实践中的实际案例出发来组织的，所以知识点范围非常广泛，每一个点都对最关键的“Best Practice”简明扼要地进行了说明。你在阅读本书的时候需要一些相关经验，不然无法跟上作者的节奏，建议在有一定的知识准备后再阅读本书，这样你会受益匪浅。从另外一个角度看，在你有了一定的基础积累之后，本书可以帮助你全面地了解一个现代化的最先进的工程实践是怎样的。本书讲述了目前行业中最常用的，经过了实践的工程方案，这将是你快速进阶的最佳指引。 
>
>-- **孙建，随身云（中华万年历）联合创始人&CEO**

---

>扎实的基础理论知识是内功底子，丰富的实践经验是招式。如本书作者所说，精妙的招式决定了你的武功下限，而深厚的内功底蕴会承载你所能企及的高度。那么，在后端技术栈中，内功与招式之间如何去关联起来，本书作者以其多年的钻研与实践结合心得，通过本书为你一一梳理。 
>
>-- **阙杭宁，网易云信CTO**

---

>作者是一位技术人,有多年的Java技术积累,是极少数真正热爱技术的人。在随身云架构师的工作让他有机会站在更高的层次进行系统架构的工作,这些实践经验和平时感悟都沉淀在作者的著作和博客中,相信每位Java工程师都能从中获取帮助。
>
>-- **秦绪震，十露盘科技联合创始人，技术负责人**

---

>本书作者根据自身多年的JAVA后台开发经验, 提纲挈领的总结JAVA后台开发的各个关键技术点，这些知识点都是一个合格的JAVA工程师必须掌握的技能。它既可以作为新人的技术学习指南，也可以帮助老手对于自己的知识面进行查漏补缺，是一本非常好的技术指南。 
>
>-- **饶洵（蜚天），阿里巴巴技术专家**

---

>作为一个在后端摸爬多年的Java开发工程师，这本书让我温故而知新。书中介绍的Java相关的知识技能树，不仅涵盖了我个人多年的Java开发技术知识点，也对我所陌生的一些知识点进行了详解，让我突然有一种继续学习的冲动。
>
>一个Java开发工程师的成长，不仅要对Java语言及其特性有深层次的理解，也需要掌握与Java相关的框架、生态及后端开发知识。这本书正是将后端开发工程师需要掌握的技能做了总结，对于提高开发技能有很好的指导作用。
>
>我推荐这本书，对于具有一定Java基础和后端开发知识的读者来说，该书不仅具有仔细学习的价值，同时也是一本可以经常翻阅的工具书籍，对于Java开发工程师的成长和进阶有很大的指导作用。
>
> 一本好的技术书籍，不仅要仔细阅读、学习理解，还需要进行较多的实践，将所看所学进行应用，通过不断地实践，加深知识点印象，从而形成永久的记忆和技能。希望各位读者能够通过掌握书中的知识和技能，逐步成长为技术骨干和专家，从而创造更多的技术输出、产品输出，创造更多的财富。 
>
> -- **张小川，网易考拉海购架构师，供应链技术主管**