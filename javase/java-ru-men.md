---
description: Java 介绍，包括简介、技术平台、JDK 下载和安装、IDEA 介绍
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Java入门

## 1. 简介

Java 是一门非常优秀的计算机语言，是目前学习开发的首选语言之一。

* Java 本身是其他很多语言的基础，无论是做 Web 开发、Android、iOS 的 Kotlin、Swift 开发，掌握 Java 都是入门第一步。
* 新入门的开发者，可以通过学习 Java 养成很好的开发习惯，例如命名规则、共通化意识、一场处理等。
* 对于初学者很有好，且资源丰富，有着庞大的资源社区。

## 2. Java的三大技术平台

* JavaSE：Java 语言的标准版，用于桌面应用开发
* JavaME：Java 语言的（小型版），用于嵌入式或移动设备开发
* JavaEE：企业版，用于企业应用开发和 Web 开发。

## 3. JDK

Java Development Kit 是 Java 的开发工具包，必须有 JDK 才能开发 Java。可以通过其[官网](https://www.oracle.com/cn/java/technologies/downloads/#java21)下载，企业常用版本是 JDK8，最新版本是 JDK21。

**JDK 的安装目录**

* bin：存放了 JDK 的各种工具命令
* conf：存放了 JDK 的相关配置文件
* include：存放了一些平台特定的头文件
* jmods：存放了 JDK 的各种模块
* legal：存放了 JDK 个模块的授权文档
* lib：存放了 JDK 工具的一些补充 JAR 包

## 4. Java 开发步骤

第一步：编程程序，文件后缀名是 `.java`，文件类型是 Java 文件

第二步：编译程序，在控制台输入 `javac className.java`

第三步：运行程序，在控制台输入 `java className`



## 5. IDEA

IDEA全称是 Intellij IDEA，是 JetBrain 公司开发的 Java 语言开发的集成环境。

下载地址：[https://www.jetbrains.com/](https://www.jetbrains.com/)

### 5.1 IDEA 构建项目

1. 进件一个空项目
2. 新建一个新模块
3. 在模块的 src 目录下新建一个包
4. 在包下新建一个类
5. 在类中编写代码
6. 运行代码

### 5.2 快捷输入

main 或 psvm 回车：创建main 方法

sout 回车：创建 `System.out.println();`

### 5.3 常用快捷键

* `Ctrl + D`：复制数据到下一行
* `Ctrl + X`：剪切数据，可以用来删除所在行
* `Ctrl + Alt + L`：格式化代码，建议自己写代码的时候就注意格式
* `Ctrl + /`：对选中的代码添加单行注释，如果想取消注释，再来一次即可
* `Ctrl + Shift + /`：对选中的代码添加多行注释，如果想取消注释，再来一次即可

### **5.4 IDEA中模块操作**

**新建模块：**File → Project Structure → Modules → <mark style="color:red;">`+`</mark> → Add New Module

**删除模块：**删除模块又分为从项目中移除（remove module）和彻底删除（delete module），你可以根据自己的需要，选择对应的方式进行删除

**导入模块：建议把模块复制到项目所在路径下**，然后找到新建模块的地方，选择**导入模块** Import Module。
