title: 梦想在路上
categories:
  - 杂
date: 2015-09-26 16:39:54
tags:
  - 留学
  - 梦想
---

## 写在前面

距离[上次聊聊梦想](/about-my-dream.html)这个略感严肃的话题已经一年有余了，时间真是个好东西，生活中的很多事情都在发生巨大的变化。这次谈谈简单的，梦想还是要有，但是随着心态的变化，还有很多事需要踏实的践行，原本打算回顾这一年来的收获与教训，但仔细想想收获相对与今后的规划来说实在太小，教训倒是有许多，后面会提到。因此，这里主要谈谈开学两月有余学习生活的一些感受，兼谈下美帝的生活体验。


这个标题看似是呼应之前的[我所理解的梦想](/about-my-dream.html)，那时还在为毕业后的人生思考，也在忙着准备留学相关的事宜。而今已然身在美帝，此时的心境有很大不同。（9.26）

## 学习状况

今天已是10月29了，转眼间一个月又倏忽不见，貌似不紧张的课程学习似乎和这种节凑背道而驰，却又不然。这学期共有5门课，其中两个核心课程（算法和操作系统）难度很大而且必须要过（至少 A-，因为对PhD 来说是 [qualifier](https://www.cs.stonybrook.edu/students/Graduate-Studies/PhDProgram){fn|如感兴趣，还可以看看石溪 cs 的[研究生手册](https://www.cs.stonybrook.edu/sites/default/files/wwwfiles/drupalfiles/basicpage/handbook.pdf)，了解国外的研究生和博士生主要做什么} ），而 TA 的 [CSE310](http://www3.cs.stonybrook.edu/~ellenyliu/310/) 工作量也很大（看课程链接就知道有3次考试，5次 lab，80人的体量），另外还有两个 seminar 需要准备 paper presentation（幸好其中一个已经 present 过了??）。因此看似不紧张的课程其实工作学习量也是很大的，主要原因还是本科欠债太多了。
<!-- more -->

### 算法

[Algorithm](http://www3.cs.stonybrook.edu/~rezaul/CSE548-F15.html) 的课程有一个 section 的老师课程据说并不太难但是这学期只能 master 选了（我们只能选 PhD section），而想学好算法却又不知情的我碰上的老师讲课内容确实有些难度，比如：

- 我们熟悉的分析时间复杂度的技巧在这里讲到各种数学证明推导，幸好微积分的内容还记得不少；
- 还有傅里叶变换的应用如多项式相乘等等，这些理解弄懂还不行，需要吸收精髓，不然 homework 的作业是不可能做出来的，最近才发现老师是负责系里 ACM 的因此才每年 homework 自己出新题（??）
- 平摊分析（Amortized Analysis）讲的很深入，直到现在还未完全弄透（需要学苦功夫了）
- 作业和考试题每年完全自己出题，不可能找到现成答案，基本上都是网上常见算法题的进阶版，印象很深的一个就是为 midterm 复习时去做 [12Fall midterm 卷子](http://www3.cs.stonybrook.edu/~rezaul/Fall-2012/CSE548/CSE548-midterm.pdf)，第一题第一问就是 leetcode 上的 two sum 问题，而第二问如果不联想到快速多项式相乘 FFT 之类（如果不是 class 讲过和有经验，这种跨越式思维实在难以想象）的根本就觉得不能做。

目前最大的感受就是老师很追求算法的分析优化（课上讲解）及应用（作业考试的要求），而非仅仅是将传统的技巧讲授就完事了，比如从第一堂课的分治算法引入，以及后面课程中对Dijkstra-SSSP 的算法用 Fibonacci Heaps 改进可见一斑。虽然这门课程的压力很大（midterm 都不到均值），但某种程度上是一种幸运，能在这种环境下学习和被引导，只要扎实去学，分析问题运用算法的能力必然会有较大的提升。

### 操作系统

[OS](http://compas.cs.stonybrook.edu/courses/cse506-f15/)课程对于做 system 相关方向的 PhD 来说几乎是必修课，重要程度和含金量也不言而喻。重要事因为搞系统的基本上都绕不开 Unix 系的各种设计思想、发展渊源{fn|Unix 传奇上下篇值得一看，上篇http://coolshell.cn/articles/2322.html}，含金量搞因为 coding 量大，需要的技能也多，我们的课程 project 就是要求写一个基本功能的64bit kernel。本科的教训就是没学好 OS 底层的知识，有段时间还老是觉得是老师自己没讲清楚又枯燥乏味，后来才发现学习的资源那么多，只是当时并没有把心思放在好好听讲、认真学习上，也因此对整个 OS 并没有开窍。因此，这门课的价值实际上相当于本科时的 OS、微机接口、计算机组成原理三门课，因为写代码实现 kernel 必须要懂硬件的基本原理、一些设备的操作、汇编调用底层功能等等，确实通过对比这边的上课所学很多东西本科就算没认真学过但也觉得本科的课程质量太低了，枯燥的讲一堆原理然并卵（严重怀疑老师自己是否弄懂，更谈不上自己会不会写代码了）。而这边的老师（以教 OS 的为例）大多真功夫实战，既能 coding 也能 research，而且水平都不低，OS 课另一个master section 老师据说（一个他手的phd 学长听来的）是linux kernel 的 committer，我们老师也会在 piazza 上回答很多 coding 相关的问题，不懂不写代码是不可能的，而从他们的 website 也能看到发表过一些 top conference 的 paper，**这些都是最好的言传身教**。

需要学习的太多，开心的是每次解决一个问题都会带来成就感，尤其是看到自己理解了原理之后看到代码成功的 run 了的那种兴奋。当然，由于欠债太多，挫败感常有，但只要坚定信念，扎实去学，最后必定不负自己的努力。


### Seminar
其实国内很多学校的研究生也开 seminar，也会读些论文拿来讨论，但总体的氛围并不太好，原因就我观察到的而言就是在于不是真正地去做学术，往往是为了发 paper 而读或写 paper，也不是真正的 research。始终觉得，没有research 所需的 background （比如基本的 coding 能力、分析论证实验能力等等）而强行做 research 不会取得  outstanding 的成果。

seminar 的目的除了在于了解最新的领域内研究进展外，重要的在于大家一起交流，discuss，从而形成 critical thinking 的态度和能力，不已此为目的那叫开 ”routine“ 会， 而不是研讨会。这学期的两个 seminar 一个是 [networking](http://nrg.cs.stonybrook.edu/courses/cse658_fall2015/)， 另一个是 [security](https://groups.google.com/forum/#!forum/nsisecurityreadinggroup)。一个很大的感受就是往往 faculty 们很激烈的提问讨论，而我们学生貌似不太积极，原因可能有很多，比如对领域不熟悉等，最大的收获也许就是听这些讨论如何提问，怎么去 critique 这些 top papers。

已经做过 presentation 的 networking seminar 其实感觉还有很大的提升空间，比如流畅地解释清楚一些基本概念的能力，英语表达的清晰度（就算发音不准），present 时逻辑的理解等等，幸好让学长帮忙录下来给自己作为反馈了。希望下下周的 security presentation 上有些进步。

### 石溪本科课程
首先直观的认识就是 TA 的 CSE310 computer networks 这门课，对比自己本科的计算机网络，质量高低立见分晓：

- 课本的选择是很重要的问题，这边基本都会用主流教材{fn|比如这门课用的是 [Computer Networking: A Top-Down Approach, 6th edition](http://book.douban.com/subject/10573157/)}。好的教材能覆盖基本而重要的知识，这本书对于本科教学来说质量确实很高，如果放国内来说，谢希仁的教材也还不错，不过还是有差距。

- 课程实验是这门课的一个重要部分，共有6次 lab，基本上是需要自己动手利用 WireShark 软件分析 packet 的数据，结合原理来回答一些问题，这样能加深对 network 如何工作的理解。（PS：我当初学完了计算机网络竟然还没分析过数据包。）

其他的本科课程可以看看这里：https://www.cs.stonybrook.edu/students/Undergraduate-Studies/csecourses。具体不做过多评论。

另外，本科生的各种资源挺丰富，比如系里分配有 server（包括 unix 系和 windows remote access 账户），还有其他的很多资源以后会详细谈到，比如正版软件的问题。

### 总结

来美国留学就是来学习来的，练好基本功是做好 research 的前提，没有捷径，也没有任何的借口，踏实和坚持进步就是最好的行动证明。

## 生活体验

这里简略说说来美国生活的一些见闻，等寒假有空了可以拓展一篇图文并茂的详细介绍文章。

### 吃住行

出门没车简直不行了，公交晚点不准时是常事、住的还算舒服（太贵了??）、吃主要自己解决（食堂难吃又贵）

### 消费

信用卡真心方便，基本很少会见到用现金。另外，各种 tax 很头疼，买东西的价格不是标的，一定记得加上消费税！

## 后记

“雄关漫道真如铁，而今迈步从头越”，相信前行路上不忘此心，正如博客底栏所言：
    
   >Better or not, that determines who you are. 
   Keep making a difference everyday !

---  



