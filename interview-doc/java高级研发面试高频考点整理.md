# java高级研发面试高频考点整理
## 高频大类整理
### 必考大类
1.java集合框架类（数据结构和实现原理）<br>
2.jvm内存模型和垃圾回收策略<br>
3.多线程的使用<br>
4.spring ioc<br>
5.数据结构和时间复杂度<br>

### 高频大类
1.spring aop<br>
2.spring事务<br>
3.juc包使用情况<br>
4.动态代理<br>
5.mybatis使用情况<br>
6.jvm内存溢出和监控工具等<br>
7.spring mvc<br>
8.数据库事务和锁、以及索引和优化器<br>
9.java反射机制<br>
10.java io流<br>
11.dubbo的基本使用及原理<br>

### 中频大类
1.redis使用情况<br>
2.mybatis原理及各对象生命周期<br>
3.网络传输协议<br>
4.class文件结构<br>

## 具体考点整理（重要程度以S表示，如SSSSS代表必考，SSSS代表极高频，SSS代表高频，SS代表中频，S代表一般考点）
### 集合框架部分
1.hashmap数据结构（SSSSS）<br>
2.hashmap数据存储及读取（SSSS）<br>
3.hashmap极端情况下的时间复杂度（SSSS）<br>
4.hashmap优化策略（SSSS）<br>
5.hashmap扩容（SSSS）<br>
6.hashmap的映射策略（SSS）<br>
7.hashmap桶容量和负载因子（SSS）<br>
8.hashmap和hashset之间的联系（SSS）<br>
9.hashmap的扰动策略（SS）<br>
10.treemap的使用场景及数据结构（SSSS）<br>
11.arrayList和linkedList的数据结构及差异(SSS)<br>

### jvm内存模型和垃圾回收策略
1.jvm内存模型介绍（SSSSS）<br>
2.堆内存模型介绍 （SSSS）<br>
3.新生代内存模型（SSS）<br>
4.垃圾回收各个阶段内存占用情况（SSS）<br>
5.新生代和年老代分别对内存的影响，还有对系统的影响（SSS）<br>

### 多线程使用
1.列举在实际项目中对多线程的使用（SSSSS）<br>
2.volilate关键字的作用（SSSS）<br>
3.volilate能否在高并发情况下使用（SSSS）<br>
4.死锁（SSS）<br>
5.线程池参数基本参数介绍（SSSS）<br>
6.线程池常用类及常用方法介绍（SSS）<br>
7.ThreadLoacl使用情况和数据结构介绍(SSSS)<br>

### spring ioc
1.ioc基本概念及项目中的使用 （SSSSS）<br>
2.spring ioc的实现（SSSS）<br>
3.spring中各对象的创建以及初始化顺序（SSSS）<br>
4.spring解决循环依赖的策略，构造器循环依赖和setter循环依赖的区别(SS)<br>
5.介绍spring ioc的一些重要的类以及方法（SSS）<br>

### 数据结构和时间复杂度（这个部分一般不会单独考，但谈到jdk源码时一般会聊到这一块）
1.用大O表示法各种数据结构的时间复杂度(SSSSS)<br>
2.红黑树概念和规则介绍(SSSS)<br>
3.红黑树保持平衡的策略(SSSS)<br>
4.红黑树在新增或删除节点时的几种变色和旋转情况(SS)<br>

### spring aop
1.介绍spring aop在项目中的使用(SSSS)<br>
2.spring aop的实现原理(SSS)<br>

### spring事务
1.spring事务传播属性（SSSS）<br>
2.spring事务的实现原理及底层调用的方法(SSS）<br>
3.spring事务指定回滚的异常(SSS)<br>

### juc包使用情况
1.ConcurrentHashMap的使用及实现原理(SSSS)<br>
2.分段锁介绍(SSSS)<br>
3.ConcurrentHashSet有吗，没有的话如何创建(SSS)<br>
4.介绍用过的juc包下面的类(SSS)<br>
5.ConcurrentHashMap和HashTable的差异介绍(SSS）<br>

### 动态代理
1.在spring框架中动态代理如何选择(SSS)<br>
2.jdk代理和cglib代理的运行速度、创建速度及其他差异对比(SSS)<br>

### mybatis使用情况
1.使用mybatis时如何防止sql注入 (SSSS)<br>
2.mybatis相对于hibernate框架的优点（SSSS）<br>
3.mybatis的事务介绍(SS)<br>

### jvm内存溢出和监控工具等
1.在项目中是否出现过jvm内存溢出的情况(SSSS)<br>
2.内存溢出时如何排查(SSSS)<br>
3.使用过哪些监控内存的工具(SSSS)<br>

### spring mvc
1.spring mvc的入口和实现原理(SSSS)<br>
2.spring mvc容器和spring容器的交互(SS)<br>
3.spring mvc创建的对象是单例还是多例(SS)<br>
4.用spring mvc开发业务代码时如何保证线程安全(SS)<br>

### 数据库事务和锁、以及索引和优化器
1.有没有使用过数据事务和数据库锁（SSS）<br>
2.数据库事务的隔离级别有几种(SSS)<br>
3.介绍下建索引的原则(SSS)<br>
4.平时使用oracle优化器是基于花费的还是基于规则的(SSS)<br>

### java反射机制
1.介绍下你使用过的反射方法 （SS）<br>
2.spring创建对象时调用过哪些反射方法(SS) <br>

### java io流
1.介绍下字节流跟字符流的区别(SSS) <br>

### dubbo的基本使用及原理
1.介绍dubbo的实现原理 （SSS）<br>
2.dubbo提供服务和消费的配置代码分别是怎样的 (SS) <br>

### redis使用情况
1.redis在项目中的使用情况（SSS）<br>
2.redis客户端和服务端如何连接(SS)<br>

### mybatis原理及各对象生命周期
1.mybatis是如何运行和工作的(SSS)<br>
2.介绍下mybatis的几个核心对象的生命周期(SS)<br>

### 网络传输协议
1.有了解过哪些传输协议，分别介绍一下原理(S)<br>

### class文件结构
1.有了解过class文件的结构吗(SS)<br>
2.平时用什么工具或者命令查看class文件(SS)<br>