培训手册链接：https://chiseled-chili-ce0.notion.site/0afe1a66699f4c51ad53649e63bd61bb  
如何使用markdown链接：https://blog.csdn.net/qq_40818172/article/details/126260661
# 一、第一阶段任务总览
1. 开发工具学习：Pycharm / VSCode使用篇，两个开发工具二选一(推荐vscode)
2. docker/Conda基础入门篇,要求可以实现自己开发环境搭建，分别在docker和conda下完成python环境搭建（以python可以输出hello word为标准）
3. Linux 基础入门篇熟悉Linux基础命令（对常见命令进行操作，要求截图下来命令执行结果，这里Linux系统大家可以使用本地虚拟机）
## 1.vscode使用
## 2.anaconda使用
### 什么是anaconda？
anaconda——环境管理工具；base理解为一个大厅，建立一些环境，比如说我简历bai_3_8，里面就包含我安装的torch、torchvision、numpy等安装包。
## 3.linux基础命令
### linux简介
很多公司会基于linux内核来开发属于自己的操作系统，linux包含了内核、系统库、shell、应用程序等等
+ **内核** ：是linux系统的核心、基础，负责管理系统的硬件和提供最基本的系统服务，包含设备驱动管理、进程管理、内存管理、文件系统、网络协议栈等等关键的底层功能和组件
+ **系统库**：用于支持应用程序开发的软件库，提供了一些常用的函数和接口，方便基于这些接口来开发应用程序，eg:C标准库、数学库、动态链接库、线程库、第三方库
+ **shell**：命令行解释器，类似于套在内核外面的一个壳，使用户使用linux系统的接口，接受用户输入的各种命令，然后把他们传递给操操作系统来执行
+ **应用程序**：平时使用的各种应用软件  

linux发行版：包括内核、应用软件、系统工具、库文件、图形界面、shell、包管理器组成的一个完整的操作系统，提供了一个预先配置好的linux环境，使我们能够方便的安装、配置和使用linux系统，每个发行版都有自己的包管理器、桌面环境和一些特定的工具，选择发行版一般取决于用户的需求或者偏好，eg:ubuntu适用于个人桌面用户，kali适用于网络安全和渗透测试；alpine由于体积小，适用于容器化的应用等等
### 如何安装配置linux系统
虚拟机软件、容器安装、云服务器
虚拟机软件的有点是不会影响到我们正常使用的系统，而且可以随时的打开和关闭，市面上的虚拟机工具有很多种，如果使用的是windows系统的话，推荐使用**vmware**和**virtualbos**，都比较成熟、比较流行，直接使用虚拟机，安装一个linux系统就好；如果是mac电脑的话，可以使用Mutipass，优点是轻量、快速、支持命令行，缺点是只支持乌班图系统，最大的优点是使用命令来创建和管理虚拟机
云服务器可以随时随地访问，缺点是需要支付一定的费用

安装过程：先安装vmware虚拟机；vm官网：https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion

## 4.git使用方法