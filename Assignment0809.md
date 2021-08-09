# 安装JDK

## 双击jdk-8u301-windows-x64.exe文件执行安装

## 新建系统环境变量（如果无法访问系统环境变量，则新建用户环境变量，下同）：
JAVA_HOME
c:\Program Files\Java\jdk1.8.0_301

![image](https://user-images.githubusercontent.com/87031851/128666472-2db07ded-88ef-41b1-8fef-582ccfe08fcf.png)

## 新建系统环境变量：
classpath
.;%JAVA_HOME%\lib

![image](https://user-images.githubusercontent.com/87031851/128666519-1b0d8073-c5d2-4c52-b394-298e173542f3.png)


在已有系统环境变量Path增加以下内容：
%JAVA_HOME%\bin

![image](https://user-images.githubusercontent.com/87031851/128666551-2de1056f-1846-41ee-b559-0bff2efd5ed5.png)




验证安装配置结果
运行CMD，执行下命令
java -version

显示结果:
java version "1.8.0_301"
Java(TM) SE Runtime Environment (build 1.8.0_301-b12)
Java HotSpot(TM) 64-Bit Server VM (build 25.301-b12, mixed mode)

![image](https://user-images.githubusercontent.com/87031851/128666618-2663aaa0-07d7-4c0c-8980-2bd925dd82f8.png)

