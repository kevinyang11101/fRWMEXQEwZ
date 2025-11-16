# 知识图谱问答系统简介 python658

## 项目概述

本项目是基于Python实现的知识图谱问答系统，通过结合Django框架和Neo4j图形数据库技术，提供一问一答的交互方式，旨在为用户解答相关问题。

## 技术栈

- 开发语言：Python
- 数据库：MySQL
- 框架：Django
- 图形数据库：Neo4j
- 开发工具：PyCharm、Navicat

## 系统角色

- 管理员
- 普通用户

## 功能模块

### 用户登录

系统的必备功能，支持用户进行登录。

### 管理员首页

展示系统概览，包括注册用户数、问答总数等指标。

### 知识问答页面

提供一问一答的交互模式，引导用户提出问题。未登录用户也可咨询问题，但不显示历史问答信息。

### 问答管理

管理员可以通过页面表格查看和管理已回答的问题，支持信息查询、模糊搜索、删除问题以及分页显示。

### 修改密码

用户可通过弹框直接修改密码，新密码需要输入两次以确认。

### 个人信息


## 运行环境

- Python环境
- MySQL数据库
- 支持Django的服务器

## 部署步骤

1. 配置Python环境。
2. 安装Django框架。
3. 配置MySQL数据库。
4. 部署Neo4j图数据库。
5. 部署应用服务器。

## 目录结构

```
knowledge_graph_qa/
├── apps/
│   └── main/
│       ├── admin.py
│       ├── apps.py
│       ├── models.py
│       ├── tests.py
│       └── views.py
├── knowledge_graph/
│   └── neomodels.py
├── manage.py
└── ...
```

## 核心亮点

- 结合Django框架和Neo4j，有效管理知识图谱数据。
- 管理员端提供高效的问题管理功能。

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img10.360buyimg.com/ddimg/jfs/t1/325408/12/23525/22976/68d4f4cfF5e67b224/7a9a0b6cbb3fa651.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/294406/39/8218/30996/68d4f4cfFac6a1eee/1487918f78f03d87.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/342775/6/7281/19153/68d4f4cfFea716b4a/f9ff1d29e995a574.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/241073/4/29987/25628/68d4f4d0F02cee04d/bb397070737eff3b.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/351038/35/7395/57450/68d4f4d0Ff890e20f/1d57305267269443.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/323601/11/23749/8423/68d4f4d0Faadf48eb/d8a4f36f38c6c302.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/330146/35/17249/20847/68d4f4d0F91224217/512c909e699169a8.jpg)
