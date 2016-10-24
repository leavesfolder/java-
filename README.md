﻿# java-
作为刚刚入门的小白菜，我在github上学到很多东西，此时也收到了offer，所以将自己的面试做一个总结，也希望能够帮助到正在求职的小伙伴们。
首先说点题外话，个人认为学习java需要专注，java的知识体系很庞大，有很多细枝末节的东西可以拿出来作为一个考点，可能实用价值不是那么明显，但是get到相应的点，你就会对这门语言多一层理解，至少当面试官问你的时候，你可以拽一些自己专业名词来糊弄过去，而不是看着面试官一脸的轻蔑与嘲笑。


首先是java基础部分：
1.java的八种基本类型与字节？（这个问题很基础，这就是阴沟里的那条船！）
  byte（1个字节）、short（2个字节）、int（4个字节）、long（8个字节）、
  float（4个字节）、double（8个字节）、char（2个字节）、boolean（1个字节）。
2.java的逻辑运算都有哪些？有没有听过异或运算符，使用规则？
  java的逻辑运算无非就是：&&、||、！
  异或运算符：^,使用规则：1^1=0，1^0=1,0^1=1,0^0=0
3.静态变量与实例变量的区别？（还有其他问法：static学过没有，讲一下static？）
  <1>静态变量使用static修饰，实例变量不用；
  <2>静态变量存储在方法区里，属于类，只有一份，而实例变量存储在堆内存中，使用new关键字可以创建很多份；
  <3>静态变量可以使用类名调用，实例变量则不能。
