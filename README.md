# AsynLogSystem

## 项目概述

本项目基于**libevent**网络库实现文件上传服务，支持上传下载和展示功能，支持多种存储等级的存储服务，并携带了异步日志系统，支持备份重要日志，多线程并发写日志等功能。
src下的client为win客户端，也可以不实现，直接使用web端与服务端交互。

## 环境准备

Ubuntu22.04 LTS

g++安装

```bash
sudo update
sudo apt install g++
```

包含日志部分和存储部分
