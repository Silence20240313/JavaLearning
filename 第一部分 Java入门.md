# JAVA学习日记
## 第一部分 Java入门
###  IDEA软件  
1.  安装下载：官网 Intellij idea  
2.  项目--模块--包--类  
    小区--楼栋--层--户

### 如何在IEDA中创建一个工程
1. 创建工程：Project（空工程）  
   (名称:javasepro 路径后面也加上项目名称)
2. 创建模块：在工程上新建Module(File-new-module(java模块) )  
   (名称：helloworld-app)
3. 创建包：在Module下的src中新建Package，公司域名倒着写  
   com.itheima.hello（小写)  
   src是源代码的位置
4. 创建类：在包上新建类-JavaClass  
   > 首字母大写，全部用英文 HelloWorld
5. ①main/psvm:提示执行架子                  sout:提示打印语句(Hello World.sout--回车)  
   ②右键RUN：程序跑起来--运行结果在操控台查看  
   ③OUT目录：CLASS文件所在处  
   ④2级包在Scr下建   
   ⑤直接进入工程：右键--OPEN IN--EXPLORER
![img.png](img.png)  

###  IDEA的设置  
1.  设置皮肤颜色：  
    File--Setting--Appearance--Theme--选颜色(intellij light)--OK  
2.  设置字体大小：  
    Appearance--Editor--font--size--OK  
    代码一页30行比较合适  
3.  设置代码的背景色:  
    Editor--color scheme--General--Text--Default text--background--选颜色--OK
    (豆沙绿 204--238--200)  
4.  删除类名称：右键--DELETE  
5.  修改类名称：右键--Refactor--Rename--Refactor(把勾都去掉)  
6.  删除模块：右键--Remove Module(进入到工程目录再次删除 Ctrl＋D)  
6.  修改模块：右键--Refactor--Rename--选第三个Rename Module and directory  
7.  打开工程：File--open--输入需要打开工程的路径--小黑点--OK  
8.  关闭工程：File--Close Project  
9.  导入模块：  
    ①  复制要导入的模块的src的com，粘贴到一个新建的模块的src里--OK  
    ②  复制要导入的模块--粘贴到我的工程中(code文件夹)--复制code中的要导入模块的路径的链接--File--New--module from existing sources--粘贴路径--点小黑点--OK  
    ③  先找到要导入模块的位置，COPY它的路径--进入到File--New--module from existing sources粘贴路径--点小黑点--OK  

###  IDEA的快捷键
![img_1.png](img_1.png)  
1.  格式化代码：规范代码位置  
2.  撤销上一步操作：Ctrl＋Z  

###  Java的基础语法
1.  注释  
    ①单行注释：输入//--回车，只能注释一行内容  
    ②多行注释：输入/*--回车  
    ③文档注释：输入/**-回车，可以在里面输入多句话， 数据可以自动的提取到文档说明书中去  
注：注释不影响程序的执行
   ![img_3.png](img_3.png)![img_4.png](img_4.png)   
对代码进行快捷注释      ![img_5.png](img_5.png)
2.  字面量  
    就是告诉程序员，数据在程序中的书写格式
![img_6.png](img_6.png)  
![img_9.png](img_9.png)  
3.   变量  
数据类型：  
    ①int：整数类型  
    ②double：小数类型  
     注：变量中装的数据可以被替换
     ![img_11.png](img_11.png)
     ![img_12.png](img_12.png)  
     ![img_13.png](img_13.png)
注意事项：![img_18.png](img_18.png)  
        ![img_19.png](img_19.png)  
4.   关键字  
Java语言自己用到的一些词，有特殊作用的，如public,class,int,double  
关键字不能用来做为类名,变量名，否则会报错  
5.   标识符  
就是名字，我们写程序时会起一些名字，如类名，变量名等等都是标识符  
要求：①组成：由字母，数字，下划线，美元符号，中文组成  
     ②强制要求：不能以数字开头，不能用关键字做为名字，且是区分大小写的  
     ③标识符的建议规范  
     变量名称：满足标识符规则，同时建议用英文，有意义，首字母小写，满足驼峰模式，eg:int StudyNumber=5;  
     类名称：满足标识符规则，建议全英文，有意义，首字母大写，满足驼峰模式，eg:HelloWorld,Student




