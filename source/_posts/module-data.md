---
title: 数据存储模块
---

> 保存中间临时数据

程序运行过程中，可能会发生数据丢失的情况，防止数据丢失，将数据临时持久化到硬盘，如果运行过程中gc丢失之后，重写读取硬盘数据。


## 使用

### 添加仓库

     maven { url("http://nexus.mhw828.com/repository/maven-releases/") }

### 添加依赖

    implementation "com.ms:android-module-impl-data:latest-RELEASE"
