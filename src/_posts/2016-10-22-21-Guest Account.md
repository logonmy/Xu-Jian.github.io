---
layout: post
title: Guest Account  
tags: Misc
categories: 💻-Win
---

## Guest Account

关闭 guest  启用高级共享密码 进行访问
启用 guest  关闭高级共享密码  进行访问


Guest 账户 进入系统 很多权限会受限: 软件安装 文件夹创立.

电脑需要给别人用,为了更好的保护隐私 就需要创建 Guest 账户.

Guest 账户安全性原则 : 不能被其他计算机访问.

方便 打印机共享 文件共享 不要密码(就算你登录电脑是要密码的)

1. 先开启 guest 功能
2. 允许网络访问: 默认是拒绝 从网络访问 Guest 账户的. 
gpedit.msc 计算机设置  windows 设置 安全设置 本地策略 用户权限分配
拒绝从网络访问这台计算机 → 删除 Guest 账户.
3. 文件夹 或者 打印机 共享里面添加 guest



