## Java入门知识
### JDK(Java开发者工具包)
1. 下载安装:官网 www.oracle.com    必须安装JDK才能使用Java  
   注：安装路径中不要包含中文和空格 所有的开发工具最好安装到统一目录
2. 企业级用LTS(长期支持版)，教学使用JDK17
3. 组成  
①JRE  (Java的运行环境)  
  JVM：Java虚拟机，真正运行Java程序的地方  
  核心类库：Java自己写好的程序，给程序员自己的程序  
②开发工具  
  Java Javac  
4. 配置  
① Path环境变量： 用于记住环境路径，方便在命令窗口的任意目录启动程序(eg:在命令行窗口启动QQ)  
我的电脑--属性--高级系统设置--高级--环境变量--双击Path--新建--粘贴路径--确定  
② JAVA-HOME:JDK的安装位置  
将来其他技术要通过这个环境变量找JDK  Path%JAVA-HOME%\bin  

### 命令行窗口
1. 打开：win键＋R--cmd--回车
2. 常用命令  
①切换盘符：盘加:   (eg:D: 冒号为英文模式下)  
②查看当前路径下的文件信息：dir  
③进入目录：cd 目录名--回车(cd和目录名中间有一个空格)  
  回退到上一级目录：cd..  
  回退到盘符根目录：CD\
④清屏：cls  

### 第一个程序  Hello World
1.  桌面新建文件夹 code,用于存放代码  
2.  新建记事本-文件名(全英文 首字母大写 后缀.java)--源代码文件
    javac编译--Hello World.class 字节码文件--使用Java运行  
    保存：CTRL＋S  
    文件扩展名.Java  

### 杂
1. 编写代码--编译代码(javac)--运行代码(java)
2. Tab键 补全
3. Java:一次编译 处处可用
4. DEBUG解决问题的意思

