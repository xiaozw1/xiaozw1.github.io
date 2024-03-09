+++
title = '在ubuntu系统里安装mysql'
date = 2024-03-09T16:49:05+08:00
draft = true
+++

# 在ubuntu系统里安装mysql

1. 打开终端，输入以下命令更新软件包列表：


sudo apt-get update


复制代码运行
2. 输入以下命令安装MySQL服务器：


sudo apt-get install mysql-server


复制代码运行
3. 安装过程中，系统会提示你设置MySQL的root用户密码。设置好密码后，
   MySQL服务器将自动启动。
4. 使用以下命令检查MySQL服务的状态：


sudo systemctl status mysql


复制代码运行
5. 如果一切正常，你应该能看到MySQL服务处于运行状态。

![abc](https://raw.githubusercontent.com/xiaozw1/picgo/main/img/20240309171553.png)