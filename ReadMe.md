# From NUIST 2023 编译原理课程设计

## 课程设计概述

使用ANTLR作为工具，定义自己的语言产生式，实现了对简单语法结构的识别与分析

## 课程设计要求

课程设计要求见文件：编译原理综合实践要求

## 文件说明

FinishedProduct.g4可以识别形似下方实例代码的语言结构

```java
#include <stdio.h>
#include <String>

String studentName = xiaowang;

Function("hello",studentName);

Int studentNum = 123;

```

Expr.g4是官方文档中的小例子，官方地址：[ANTLR](https://www.antlr.org/index.html)

test1.g4和FinishedProduct.g4差不多

test2.g4是个类似于识别函数的小语法



