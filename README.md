# LinuxExample

`Linux / Unix` Example：文章中的所有例子均在 MacOS / UOS 上面编译成功。

<br>

**💻：**  `UOS20 (Debian8+)` 📎 `gcc/g++ 8.3.0` 📎 `gdb 8.0`

**💻：**  `MacOS 10.14.6 ` 📎 `gcc/g++ 9.2.0` 📎 `gdb 8.3`

<br>

## 目录：

### 服务器开发之 Linux 基础编程：

##### gcc/g++:

- [在MacOS上面通过brew命令安装gcc编译器集](https://blog.csdn.net/qq_33154343/article/details/104639656) 
- [gcc和g++的区别，编译.c和.cpp文件的区别](https://blog.csdn.net/qq_33154343/article/details/104645129) 
- [gcc工作流程：预处理，编译，汇编，链接](https://blog.csdn.net/qq_33154343/article/details/104693603)
- [Linux下使用gcc生成静态库.a和调用（图文并茂，坑已踩完）](https://blog.csdn.net/qq_33154343/article/details/104692241) 
- [Linux下使用gcc生成动态库.so和调用（图文并茂，坑已踩完）](https://blog.csdn.net/qq_33154343/article/details/104692370) 
- [在Linux中，编写入门的makefile文件，然后逐渐迭代](https://blog.csdn.net/qq_33154343/article/details/104758512)

<br>

##### gdb:

- [ 在MacOS10.14.6安装最新gdb8.3的详细教程，含可能遇到的所有坑(网上最新教程)](https://blog.csdn.net/qq_33154343/article/details/104784641)
- [gdb调试器的使用，初探全貌](https://blog.csdn.net/qq_33154343/article/details/104904798)

<br>

##### 程序运行原理，文件描述符，PCB：

- [Linux中文件操作，软硬链接ln，用户权限chmod、chown，文件查找和检索find、grep，压缩gz，bz2](https://blog.csdn.net/qq_33154343/article/details/105010222)
- [Linux中虚拟地址空间、pcb、文件描述符、C库函数工作流程、标准库和系统库函数区别](https://blog.csdn.net/qq_33154343/article/details/105029261)
- [Linux中man手册，阻塞和非阻塞，stat，文件操作和遍历，文件描述符复制dup()](https://blog.csdn.net/qq_33154343/article/details/105031987) 

<br>

### 服务器开发之 Linux 系统编程：

##### 进程间通信：

- [Linux中fork创建兄弟子进程，验证进程之间全局变量不共享，exec函数族](https://blog.csdn.net/qq_33154343/article/details/105157044)
- [Linux中孤儿进程，僵尸进程，进程回收wait、waitpid函数](https://blog.csdn.net/qq_33154343/article/details/105164215)
- [父子进程、兄弟子进程之间通信方式--匿名管道pipe(适用于有血缘关系的进程)](https://blog.csdn.net/qq_33154343/article/details/105254078)
- [Linux中普通的进程间通信方式--有名管道fifo(适用于无血缘关系的进程)](https://xmuli.blog.csdn.net/article/details/105266919) 
- [Linux中进程间的通信方式--内存映射区mmap()](https://xmuli.blog.csdn.net/article/details/105322927) 

<br>

##### 信号和守护进程：

- [Linux中系统信号初识，和函数kill，raise，abort，alarm，setitimer](https://xmuli.blog.csdn.net/article/details/105357886) 
- [Linux中未决信号集和阻塞信号集的状态关系sigaddset，以及捕捉信号函数](https://xmuli.blog.csdn.net/article/details/105448914) 
- [Linux中创建守护进程setsid()](https://xmuli.blog.csdn.net/article/details/105453850)

<br>

##### 多线程：

- [Linux中创建多线程实例pthread_create()](https://xmuli.blog.csdn.net/article/details/105546234) 
- [Linux中多线程操作函数pthread_exit()、pthread_jion()、pthread_detach()、pthread_cancel()](https://xmuli.blog.csdn.net/article/details/105620043) 
- [Linux中使用使用互斥量(锁)Mutex来操持多线程同步执行pthread_mutex_lock()](https://xmuli.blog.csdn.net/article/details/105779111) 
- [Linux中原子操作，死锁原因以及解决方法，读写锁的属性和函数使用pthread_rwlock_wrlock()](https://xmuli.blog.csdn.net/article/details/105800949) 
- [Linux中多线程使用条件变量阻塞线程，和pthread_cond_wait()函数使用](https://xmuli.blog.csdn.net/article/details/105885580)
- [Linux中多线程使用信号量(信号灯)，和sem_wait()函数使用](https://xmuli.blog.csdn.net/article/details/105885816)

<br>

### 服务器开发之 Linux 网络编程：

感觉基础的网络理论基础知识已会，写过一些实战项目的代码，可以参考 [QtExamples](https://github.com/xmuli/QtExamples) 第十章部分

后面深入底层网络完成，有空再整理文章，

待续...
