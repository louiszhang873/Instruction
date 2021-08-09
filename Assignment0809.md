# 安装JDK

## 双击jdk-8u301-windows-x64.exe文件执行安装

## 新建系统环境变量（如果无法访问系统环境变量，则新建用户环境变量，下同）：
JAVA_HOME
c:\Program Files\Java\jdk1.8.0_301


## 新建系统环境变量：
classpath
.;%JAVA_HOME%\lib

在已有系统环境变量Path增加以下内容：
%JAVA_HOME%\bin

验证安装配置结果
运行CMD，执行下命令
java -version

显示结果:
java version "1.8.0_301"
Java(TM) SE Runtime Environment (build 1.8.0_301-b12)
Java HotSpot(TM) 64-Bit Server VM (build 25.301-b12, mixed mode)
