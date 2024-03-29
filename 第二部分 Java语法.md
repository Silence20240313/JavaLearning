
# 第二部分 Java语法
##   数据类型
###  数据类型的大小
1.  计算机中表示数据的最小单元：字节(简称B)  
    字节中的每个二进制位就称为位，(简称b)  
    一个字节等于8个二进制位：1B=8b  
    在B的基础上，计算机发展出了KB,MB,GB,TB..这些数据单位  
    ![img_23.png](img_23.png)  
2.  十进制转二进制：除二取余法    
    二进制转十进制：命令行窗口输入calc打开计算器左上角选择程序员  
3.  计算一个数据的二进制形式：除二取余法
4.  数据在计算机底层的存储：采用二进制，使用0 1，按照逢2进1的规则表示数据来存储  
    字符在计算机中的存储：ASCII编码表中对应的数字的二进制形式  
    eg:字符a对应的数字是97    字符A对应的数字是65    字符0对应的数字是48  
![img_21.png](img_21.png)
5. 注意： 

   ![img_22.png](img_22.png)

###  数据类型的分类
分为：基本数据类型和引用数据类型  
![img_24.png](img_24.png)
![img_25.png](img_25.png)  

###  类型转换  
1.  自动类型转换： 类型范围小的变量，可以直接赋值给类型范围大的变量  
eg:byte类型的赋值给int类型  
![img_26.png](img_26.png)![img_27.png](img_27.png)  
2.  表达式的自动类型转换：在表达式中，小范围类型的变量，会自动转换成表达式中较大范围的类型，再参与运算  
表达式的最终结果类型由表达式中的最高类型决定  
在表达式中，byte,short,char是直接转换成int类型参与运算的  
![img_28.png](img_28.png)  
![img_29.png](img_29.png)  
3.  强制类型转换：类型范围大的数据或者变量，直接赋值给类型范围小的变量，会报错  
强行将类型范围大的变量，数据赋值给类型范围小的变量  
注意：小数型强转成整型，直接丢掉小数部分，保留整数部分返回  
![img_30.png](img_30.png)  
![img_32.png](img_32.png)  

###  运算符  
对变量，字面量进行运算的符号  
1.  基本的算术运算符  
![img_33.png](img_33.png)  
![img_34.png](img_34.png)  
2. "+"符号可以做连接符  
"abc+5"--"abc5"  
什么时候是连接符，什么时候是加法：能算则算，不能算就在一起  
![img_35.png](img_35.png)  
3.  自增自减运算符  
方便的对变量的值进行+1或-1  
++，--只能操作变量，不能操作字面量  
    ![img_36.png](img_36.png)  
++，--如果不是单独使用，放在变量前后会存在明显区别  
  ![img_38.png](img_38.png)  
![img_39.png](img_39.png)  
4.  赋值运算符  
"="  从右往左看  
扩展赋值运算符  
![img_40.png](img_40.png)  
![img_41.png](img_41.png)  
5.  关系运算符  
判断数据是否满足条件，最终会返回一个判断的结果，这个结果的布尔类型的值：true或者false  
![img_43.png](img_43.png)  
![img_44.png](img_44.png)  
6.  逻辑运算符  
把多个条件放在一起运算，最终返回布尔类型的值：ture/false  
![img_48.png](img_48.png)
![img_49.png](img_49.png)  
![img_50.png](img_50.png)  
7. 三元运算符  
格式：条件表达式？值1：值2；  
执行流程：首先计算关系表达式的值，如果值为true,返回值1，如果为false,返回值2  
![img_51.png](img_51.png)    
8. 运算符优先级  
在表达式中，哪个运算符先执行后执行是要看优先级的  
![img_52.png](img_52.png)  
9. API  
Java写好的程序，咱们可以直接调用  
API文档：Java提供的程序使用说明书  
10. Java程序中如何实现接收用户键盘输入的数据  
![img_53.png](img_53.png)  
![img_54.png](img_54.png)  

















 
