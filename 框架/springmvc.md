## 一、软件的三层架构

### 1.1  表现层

​	也就是web层，负责接收浏览器发送的请求，并向浏览器返回处理结果。

### 1.2  业务层

​	负责业务处理，与项目需求有关系

### 1.3 持久层

​	负责将数据持久化到数据库中

## 二、mvc模型

​	MVC全称是 Modul View Controller,是模型，视图和控制器的简称，是一种web程序表现层的一种模式，职责分别如下：

### 	2.1 Modul

​		通常指的是数据模型，一般用于封装数据

### 	2.2 View

​		指的是视图层，一般指jsp或者html，

### 	2.3 Controller

​		是应用程序中处理用户交互的部分，作用一般就是处理程序的逻辑的。

## 三、SpringMVC

### 3.1 定义

​	SpringMVC 是一种基于 Java 的实现 MVC 设计模型的请求驱动类型的轻量级 Web 框架，属于 Spring  

FrameWork 的后续产品，已经融合在 Spring Web Flow 里面。Spring 框架提供了构建 Web 应用程序的全功 

能 MVC 模块。使用 Spring 可插入的 MVC 架构，从而在使用 Spring 进行 WEB 开发时，可以选择使用 Spring 的 Spring MVC 框架或集成其他 MVC 开发框架，如 Struts1(现在一般不用)，Struts2 等。 

SpringMVC 已经成为目前最主流的 MVC 框架之一，并且随着 Spring3.0 的发布，全面超越 Struts2，成 

为最优秀的 MVC 框架。 它通过一套注解，让一个简单的 Java 类成为处理请求的控制器，而无须实现任何接口。同时它还支持 RESTful 编程风格的请求。 

### 3.2 架构图



![springMVC](C:\Users\双子座k2\Desktop\面试准备\imge\springMVC.png)

### 3.3 SpringMVC的三大组件

#### 3.3.1 处理器映射器

#### 3.3.2 处理器适配器

#### 3.3.3 视图解析器

