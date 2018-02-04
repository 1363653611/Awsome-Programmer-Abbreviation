> 程序员的世界里充斥着很多的专业名词和英文缩写，我打算对一些常见的词汇进行一个汇总，同时会在 GitHub 上进行同步：[https://github.com/Panmax/Awsome-Programmer-Abbreviation](https://github.com/Panmax/Awsome-Programmer-Abbreviation)，欢迎 PR。
	
### 英文缩写

#### API

应用程序接口（英语：Application Programming Interface，简称：API），又称为应用编程接口，就是软件系统不同组成部分衔接的约定。由于近年来软件的规模日益庞大，常常需要把复杂的系统划分成小的组成部分，编程接口的设计十分重要。程序设计的实践中，编程接口的设计首先要使软件系统的职责得到合理划分。良好的接口设计可以降低系统各部分的相互依赖，提高组成单元的内聚性，降低组成单元间的耦合程度，从而提高系统的维护性和扩展性。

#### ACID

ACID，是指数据库管理系统（DBMS）在写入或更新资料的过程中，为保证事务（transaction）是正确可靠的，所必须具备的四个特性：原子性（atomicity，或称不可分割性）、一致性（consistency）、隔离性（isolation，又称独立性）、持久性（durability）。

#### CAS

1. 比较并交换(compare and swap, CAS)，是原子操作的一种，可用于在多线程编程中实现不被打断的数据交换操作，从而避免多线程同时改写某一数据时由于执行顺序不确定性以及中断的不可预知性产生的数据不一致问题。 该操作通过将内存中的值与指定数据进行比较，当数值一样时将内存中的数据替换为新的值。
2. 集中式认证服务（英语：Central Authentication Service，缩写CAS）是一种针对万维网的单点登录协议。它的目的是允许一个用户访问多个应用程序，而只需提供一次凭证（如用户名和密码）。它还允许web应用程序在没有获得用户的安全凭据（如密码）的情况下对用户进行身份验证。“CAS”也指实现了该协议的软件包。

#### JPA

JPA 是 Java Persistence API 的简称，中文名 Java 持久层 API，是 JDK 5.0 注解或 XML 描述对象－关系表的映射关系，并将运行期的实体对象持久化到数据库中。 

#### POJO

POJO（Plain Ordinary Java Object）简单的 Java 对象，实际就是普通 Java Beans。使用 POJO 名称是为了避免和 EJB 混淆起来，而且简称比较直接。其中有一些属性及其 getter setter 方法的类，没有业务逻辑，有时可以作为VO(Value Object) 或 DTO(Data Transform Object) 来使用。当然，如果你有一个简单的运算属性也是可以的，但不允许有业务方法，也不能携带有 connection 之类的方法。

#### DSL

领域专用语言（Domain Specific Language/DSL），其基本思想是「求专不求全」，不像通用目的语言那样目标范围涵盖一切软件问题，而是专门针对某一特定问题的计算机语言。

#### GC

在计算机科学中，垃圾回收（英语：Garbage Collection，缩写为GC）是一种自动的内存管理机制。当一个电脑上的动态内存不再需要时，就应该予以释放，以让出内存，这种内存资源管理，称为垃圾回收。垃圾回收器可以让程序员减轻许多负担，也减少程序员犯错的机会。垃圾回收最早起源于LISP语言。目前许多语言如 Smalltalk、Java、C# 和 D 语言都支持垃圾回收器。

#### DML

数据操纵语言（Data Manipulation Language, DML）是 SQL 语言中，负责对数据库对象运行数据访问工作的指令集，以 INSERT、UPDATE、DELETE 三种指令为核心，分别代表插入、更新与删除，是开发以数据为中心的应用程序必定会使用到的指令，因此有很多开发人员都把加上SQL的SELECT语句的四大指令以“CRUD”来称呼。

#### DDL

数据定义语言（Data Definition Language，DDL）是 SQL 语言集中负责数据结构定义与数据库对象定义的语言，由 CREATE、ALTER 与 DROP 三个语法所组成，最早是由Codasyl（Conference on Data Systems Languages）数据模型开始，现在被纳入 SQL 指令中作为其中一个子集。

#### DI

Dependency Injection，依赖注入。在软件工程中，依赖注入是种实现控制反转用于解决依赖性设计模式。一个依赖关系指的是可被利用的一种对象（即服务提供端） 。依赖注入是将所依赖的传递给将使用的从属对象（即客户端）。该服务是将会变成客户端的状态的一部分。 传递服务给客户端，而非允许客户端来建立或寻找服务，是本设计模式的基本要求。

#### IOC

控制反转（Inversion of Control，缩写为IoC），是面向对象编程中的一种设计原则，可以用来减低计算机代码之间的耦合度。其中最常见的方式叫做依赖注入（Dependency Injection，简称DI），还有一种方式叫“依赖查找”（Dependency Lookup）。通过控制反转，对象在被创建的时候，由一个调控系统内所有对象的外界实体，将其所依赖的对象的引用传递给它。也可以说，依赖被注入到对象中。


#### LDAP

轻型目录存取协定（英文：Lightweight Directory Access Protocol）是一个开放的，中立的，工业标准的应用协议，通过IP协议提供访问控制和维护分布式信息的目录信息。

#### OLAP

联机分析处理（英语：On-Line Analytical Processing），是一套以多维度方式分析数据，而能弹性地提供积存（英语：Roll-up）、下钻（英语：Drill-down）、和透视分析（英语：pivot）等操作，呈现集成性决策信息的方法，多用于决策支持系统、商务智能或数据仓库。其主要的功能，在于方便大规模数据分析及统计计算，对决策提供参考和支持。与之相区别的是联机交易处理（OLTP）。

#### SQL

SQL（结构化查询语言）是一种特定目的程序语言，用于管理关系数据库管理系统（RDBMS），或在关系流数据管理系统（RDSMS）中进行流处理。

#### NoSQL

NoSQL 是对不同于传统的关系数据库的数据库管理系统的统称。

---


### 专业名词

#### 乐观锁

在关系数据库管理系统里，乐观并发控制（又名“乐观锁”，Optimistic Concurrency Control，缩写“OCC”）是一种并发控制的方法。它假设多用户并发的事务在处理时不会彼此互相影响，各事务能够在不产生锁的情况下处理各自影响的那部分数据。在提交数据更新之前，每个事务会先检查在该事务读取数据后，有没有其他事务又修改了该数据。如果其他事务有更新的话，正在提交的事务会进行回滚。乐观事务控制最早是由孔祥重（H.T.Kung）教授提出[1]。

#### 悲观锁

在关系数据库管理系统里，悲观并发控制（又名“悲观锁”，Pessimistic Concurrency Control，缩写“PCC”）是一种并发控制的方法。它可以阻止一个事务以影响其他用户的方式来修改数据。如果一个事务执行的操作读某行数据应用了锁，那只有当这个事务把锁释放，其他事务才能够执行与该锁冲突的操作。

#### 自旋锁

自旋锁是计算机科学用于多线程同步的一种锁，线程反复检查锁变量是否可用。由于线程在这一过程中保持执行，因此是一种忙等待。一旦获取了自旋锁，线程会一直保持该锁，直至显式释放自旋锁。

#### 递归

递归（英语：Recursion），又译为递回，在数学与计算机科学中，是指在函数的定义中使用函数自身的方法。递归一词还较常用于描述以自相似方法重复事物的过程。例如，当两面镜子相互之间近似平行时，镜中嵌套的图像是以无限递归的形式出现的。也可以理解为自我复制的过程。

#### 主键

主键，又称主码（英语：primary key或unique key）。数据库表中对储存数据对象予以唯一和完整标识的数据列或属性的组合。一个数据列只能有一个主键，且主键的取值不能缺失，即不能为空值（Null）。

#### 外键

外键（英语：foreign key，台湾译外来键，又称外部键）。其实在关系数据库中，每个数据表都是由关系来连系彼此的关系，父数据表（Parent Entity）的主键（primary key）会放在另一个数据表，当做属性以创建彼此的关系，而这个属性就是外键。
