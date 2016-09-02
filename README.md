# study
## 自我的水平认知 ##
刚开始接触编程是从2011年开始，做为一名软件工程（JAVA）方向的大学生而言，我并不知道JAVA是什么，更不清楚将来会从事软件开发这一行业，一直到大三面临着还有一年毕业和就业以及对前途的迷茫，终于有一天我发现我不得不去正面的面对这些问题，但是在这时候，我发现我对于自己的专业真的很陌生，而且对去JAVA以及开发而言仅仅是导师在上课的时候用键盘敲了一个P就出现的Public这个单词，感叹自己没有学习的同时也下决心去学习作为一个软件开发专业大学生应有的技能。
于是我就开始了解JAVA和TA想关的一切，这个过程中了解了软件开发以及JAVA的衍生出来的东西。发现Android这个手机系统，而且当时我也在用Samsung，随后对Android的开发产生了浓厚的兴趣。后来便去寻找自己的机遇，学习，工作。到现在已经快2年了，在这期间上线过很多项目，不管是独立开发以及团队协作一步一步走过来，到目前，在工作空余，我总觉得自己在技术上有缺陷，后来慢慢总结发现自己开发中总是去运用而不是深究以及自己的基础不是很好，虽然不管公司的工作都能完成，但是总是磕磕碰碰的，所以鉴于自身的一个情况，下绝心重新去梳理自己的所学以及修补自己技术中的不足。去更深层次的学习JAVA基础和Android开发。同时文章也献给刚开始学习Android开发的朋友以及和我存在同样问题的开发人员。

## 重新认识Android ##
Android 使用Java语言开发。Android SDK 工具编译代码—以及任意数据并连同相关资源打包进一个Android 包内,它是一个以.apk 为后缀的压缩文件。 一个 .apk 文件中的 所有代码就是一个程序。这个.apk文件就用于在Android设备上安装这个程序（[官方解释](http://www.android-doc.com/guide/components/fundamentals.html)）。这个.apk文件就是我们需要开发的东西。
##Android系统架构 ##
![Android系统架构图](http://img.blog.csdn.net/20160810153350023)

 1. Application（应用层）
	 顾名思义就是Android手机的应用层，包括电话，浏览器，日历，电话本等等应用，也是我们开发的APP存在的地方。
 2. Application Framework（应用框架层）
	 就是开发APP时所用到的组件，以及管理上的地方，开发人员可以使用该层所提供的View，内容提供（Content Provider），资源管理等。
 3. Library（库文件层）
	Android 包含一些C/C++库，这些库能被Android系统中不同的组件使用。它们通过 Android 应用程序框架为开发者提供服务。
 4. Android Runtime（运行库）
	Android 每个程序的运行编译的地方。
 5. Linux Kernel（Linux内核）
	Android 的核心系统服务依赖于 Linux 2.6 内核，如安全性，内存管理，进程管理， 网络协议栈和驱动模型。 Linux 内核也同时作为硬件和软件栈之间的抽象层。
## 准备工作 ##
 6. 一台电脑（Windows，Mac）因为我们开发Android所用的语言为Java具有跨平台性。
 7. JDK：Java语言必要的开发环境（Mac自带）。[下载链接](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)     [安装教程](http://jingyan.baidu.com/article/647f01157fc0c57f2148a82a.html)
![这里写图片描述](http://img.blog.csdn.net/20160810161603667)
 
 8. 开发工具（eclipse或者Android Studio）推荐：Android Studio[下载链接](http://www.android-doc.com/tools/index.html)  [安装教程](http://jingyan.baidu.com/article/ad310e80a9328a1849f49e30.html)

## 开始Android之旅：创建项目 ##
![这里写图片描述](http://img.blog.csdn.net/20160810162915383)
我们这里选择创建一个新的项目
![这里写图片描述](http://img.blog.csdn.net/20160810163549706)
填写项目需要的项目名和公司名（这里可以随便填写）
![这里写图片描述](http://img.blog.csdn.net/20160810165300230)
选择一中Activity作为项目的界面
![这里写图片描述](http://img.blog.csdn.net/20160810165322244)
点击Finnish完成项目创建
![这里写图片描述](http://img.blog.csdn.net/20160810165716749)
这样我们的第一个项目就已经创建成功了
## Android studio中的一些目录认识 ##
![这里写图片描述](http://img.blog.csdn.net/20160810171105269)
