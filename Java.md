# Java类错题

## Java垃圾回收算法CMS执行的顺序是（）
- A. 初始标记->并发标记->并发预清理->重新标记->并发清理->并发重置 
- B. 初始标记->并发标记->重新标记->并发预清理->并发清理->并发重置
- C. 初始标记->并发预清理->并发标记->重新标记->并发清理->并发重置
- D. 初始标记->并发标记->重新标记->并发预清理->并发重置->并发清理

答案：A. 初始标记->并发标记->并发预清理->重新标记->并发清理->并发重置 

## 下面有关java类加载器，说法正确的是？
- A. 引导类加载器（bootstrap class loader）：它用来加载Java的核心库，是用原生代码来实现的
- B. 扩展类加载器（extensions class loader）：它用来加载Java的扩展库
- C. 系统类加载器（system class loader）：它根据Java应用的类路径（CLASSPATH）来加载Java类
- D. Tomcat为每个APP创建一个Loader，里面保存着此WebApp的ClassLoader。需要加载WebApp下的类时，就取出ClassLoader来使用

答案：ABCD

## 下面哪些说法是正确的？（ ）
- A. java语言是真正的面向对象的语言，任何代码都是类的一部分。
- B. 运行java程序必须需要java运行环境的支持，例如需要java虚拟机JVM。
- C. 使用Visual J++在windows下开发的所有java程序可以不加修改的在Unix下运行，这是java程序“一次编写，到处运行”的特点决定的。
- D. java语言的类加载器可以实现从互联网上加载java程序。

答案：BCD

## 下面哪个方法是 public void  example(){...} 的重载方法？ ( )
- A. public void Example( int m){...}
- B. public int example(){...}
- C. public void example2(){...}
- D. public int example ( int m, float f){...}

答案：D

解析：方法重载要求函数名完全相同，参数列表不同（数量，类型或位置均可）；返回值类型、方法修饰符不影响。


