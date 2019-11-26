# learn-java
main Java knowledeg

一、Java基础知识梳理

1.Java变量
（1）局部变量：定义在方法，构造方法，代码块中的变量。
（2）成员变量（或实例变量）：定义在类中，非static；这种变量在创建对象的时候实例化。
（3）类变量：有static

2.Java中的日期时间
  （1）将Date类型转换为String类型需要用到SimpleDateFormat的format方法：
  Date date = new Date( );
  SimpleDateFormat sdf = new SimpleDateFormat ("yyyy-MM-dd hh:mm:ss");
  System.out.println("当前时间为: " + sdf.format(date));

  （2）String转为Date，用SimpleDateFormat的parse方法：
  SimpleDateFormat sdf = new SimpleDateFormat ("yyyy-MM-dd"); 
  String str = "1818-11-11" ; 
  Date date; 
  date = sdf.parse(str); 
  
3.Java中的内部类

4.Java中的static
