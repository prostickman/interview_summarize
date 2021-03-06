** 说明 **

此文为西安活跃网络技术电话面试相关问题

### 说说你理解的OOP？
* 面向对象可以理解成对待每一个问题，都是首先要确定这个问题由几个部分组成，而每一个部分其实就是一个对象。然后再分别设计这些对象，最后得到整个程序。传统的程序设计多是基于功能的思想来进行考虑和设计的，而面向对象的程序设计则是基于对象的角度来考虑问题。这样做能够使得程序更加简洁、清晰。

理解面向对象的编程的思想，首先我想给大家一个非常熟悉的一个例子，让大家对面向对象和面向过程有一个大致的理解，想必大家都知道那个“老张开车去东北”的例子，用面向过程的思路理解:你首先得造一个车，然后包括挂档，每一步都得自己一步一步的线性去完成；用面向对象的思路来理解的话，直接调个车，找个司机，然后告诉他去东北，然后其他的就不用你管了，你可能隐约的感觉到，面向对象的思路似乎省了不少事。  

* 面向对象的三大特征是什么？
  * 封装： 是指一个对象将自己的数据和操作合理的有效的封装在一起
  * 继成：子类可以遗传父类的操作和数据，且自己也能有自己的操作和数据
  * 多态： 有两种意义上的多态，一种操作名称上的，即，具有多个名称相同的操作，但是他们接受的消息类型不一样，另一种：和继承有关，同一个操作被不同的类继承覆盖
  * 参考图：
  * [!图片](http://images.51cto.com/files/uploadimg/20100331/114910755.jpg)
 
### 拓展问题：面向过程和面向对象有什么区别？

面向过程就是指分析出解决问题所需要的步骤，然后用函数把这些步骤一步一步实现，使用的时候一个一个依次调用就可以了。

面向对象是把构成问题的事务分解成各个对象，建立对象的目的不是为了完成一个步骤，而是为了描叙某个事物在整个解决问题步骤中的行为。

面向对象面向的是数据结构，面向过程面向的是算法。虽然面向对象在数据构造方面优于面向过程，但是面向过程是算法设计的实现基础，面向对象的程序设计最终还要转化为面向过程。
  
### 鸭子类型怎么实现的？
* 在鸭子类型中，关注的不是对象的类型本身，而是它是如何使用的,在被调用的对象中不管你是什么类型，你只有有这个方法就行。


### include和extende的区别？
 * include 包涵，聚合，组合的关系，可以多个， include后是类的实例方法
 * extende 继承关系，只能一个，extend是变成类方法
 * 模块不能实例化，类不能include

### 分析过Ruby、Rails 源码？ Ruby的底层实现？


### Rails的启动流程？ 内部底层架构？
 * 比如我们每次使用rails c, rails s等，相关命令后的流程，深入理解？
 
### Rails本身自带了哪些缓存？有哪些缓存方法？
 * key <-> value ，key在Rails中是什么？，  id 和 updated_at 
 
### Rails 自带缓存有哪些？
* 页面缓存
* 动作缓存
* 片段缓存
* 底层缓存
* SQL 缓存
* http://guides.ruby-china.org/caching_with_rails.html#activesupport::cache::memcachestore
* http://rails-everyday.group.iteye.com/group/wiki/1160




### Rails中只读一个字段，或者累加某一个field的关键字是什么？

### 符合和字符串的区别是什么？
* 字符串和符号，都是Ruby中表示文本的方式
* 相同的符号是一个对象，相同的字符并不一定是一个对象
* 处理符号相比字符串，占用更少的资源
* 由于字符串变量必须具有各种修改其内容的功能，所以字符串的维护和处理的开销就很大

### 网页优化，从前端到后端有哪些方式？
* https://github.com/NoonTechnology/interview_summarize/blob/master/%E5%94%B1%E5%90%A7%E9%9D%A2%E8%AF%95.md

### 说我github上面的项目有些混杂

### 我有哪些特长在面试中没有被问道的？
