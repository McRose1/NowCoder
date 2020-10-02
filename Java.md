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
