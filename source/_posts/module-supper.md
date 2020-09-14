---
title: 接口定义模块
---

> 接口功能定义和客户端操作API


- api模块
- common模块
- 开关控制模块
- 数据模块
- 数据存储模块
- 异常处理模块
- 日志模块
- 缓冲模块
- 网络
- 动态权限
- 工具类


## 使用

    implementation "com.ms:module-super:debug-latest"

## API

> Modules 类

        // 获取日志模块
        Modules.getLogModule();

        // 获取工具类模块
        Modules.getUtilsModule();

        // 阿里云日志模块
        Modules.getAliyuLogModule();

        // 数据模块
        Modules.getDataModule();

        // 获取APP数据
        Modules.getDataModule().getAppData();


