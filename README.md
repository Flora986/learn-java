# learn-java
main Java knowledeg

#一、Java基础知识梳理

##1.Java变量
+ （1）局部变量：定义在方法，构造方法，代码块中的变量。
+ （2）成员变量（或实例变量）：定义在类中，非static；这种变量在创建对象的时候实例化。
+ （3）类变量：有static

##2.Java中的日期时间
 + （1）将Date类型转换为String类型需要用到SimpleDateFormat的format方法：
  Date date = new Date( );
  SimpleDateFormat sdf = new SimpleDateFormat ("yyyy-MM-dd hh:mm:ss");
  System.out.println("当前时间为: " + sdf.format(date));

  + （2）String转为Date，用SimpleDateFormat的parse方法：
  SimpleDateFormat sdf = new SimpleDateFormat ("yyyy-MM-dd"); 
  String str = "1818-11-11" ; 
  Date date; 
  date = sdf.parse(str); 
  
##3.Java中的内部类

##4.Java中的static

##5.Java数组的内容
+ 冒泡排序：
+ 1.定义一个数组：int[] a = {1,6,2,8};
+ 2.定义外层for循环int i= 1;i < 数组的length；i++。
+ 3.定义内层for循环int j= 1;j < 数组的length-i;j++;
+ 4.内层for循环中添加if判断：如果a[j] >  a[j+1]，
+ 5.定义临时变量交换数值：int temp = a[j];a[j]=a[j+1];a[j+1] = temp;
+ 6.排序后输出数组System.out.println(Arrays.toString(a));
