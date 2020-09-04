# java_study_summary
JAVA知识代码汇总

# 工具类
* Timer 定时任务调度

# I/O流
* 常用字节流与字符流API的基础使用方式，同时并有简单的拷贝文件例子实现
* **BIO** 配合多线程的简单实现方式
* **NIO** 的实现，以多人网络通信聊天为例子实现

# 数据结构
### 集合
* ArrayList、LinkedList 基础使用
* HashSet 基础使用
* HashMap、Hashtable 基础使用
### 链表
* 链表翻转：递归方式、迭代方式
* 跳表：增删、查询
### 树
* 哈夫曼树构建实例

# Java 设计模式
### 代理模式（结构）
* 静态代理：继承方式、聚合方式
* 动态代理：jdk、cglib
### 工厂模式（创建）
* 简单工厂模式
* 工厂方法模式
* 抽象工厂模式
### 适配器模式（结构）
* 类适配器
* 对象适配器
* 接口适配器
### 策略模式（行为）
* 简单使用（数值加减操作）
* if..else 过多情况处理（以不同状态码不同处理方式为例）
### 建造者模式（创建）
* 以抽象/具体建造者、指导者、产品四个角色为基础实现简单例子（制造机器人）
* 去除指导者，将具体建造者作为静态内部类放在产品类中，也可灵活控制建造细节（造房子）
### 外观模式（结构）
* 模拟 KFC 套餐购买，系统包含多个食品购买，由外观类包装系统的多个接口来构成一个简洁的高层接口
### 模板模式（行为）
* 模拟游戏运行，构建相同的运行抽象模板（方法），由具体模板根据需要重写部分功能（方法）
### 观察者模式（行为）
* 根据被观察者的状态（整型数值）转变，触发观察者输出不同进制下的数值
### 责任链模式（行为）
* 根据日志信息级别调用对应的日志处理对象
### 装饰器模式（结构）
* 简单装饰图形接口，并增加涂色功能的例子（该模式可直接参考 Java IO 相关类）

# Java8 lambda 表达式/Stream API 基础使用
* 常用函数式接口
* 方法引用
* Stream API：filter(筛选)、map(映射)、reduce(归约)
* 自定义收集器 Collector、分割迭代器 Spliterator


