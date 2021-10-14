---
title: CentOS 7(2) 系统服务管理方式
tags: ['CentOS']
categories: ['CentOS']
date: 2016-05-05 05:43:55
---

## 关闭防火墙：
```
   systemctl stop firewalld.service   # 关闭
   systemctl disable firewalld.service # 开机不自启动
```
