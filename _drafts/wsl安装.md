---
layout: post
title: "WSL安装"
date: 2023-03-24
description: "WSL安装记录"
tag: 踩坑日记
---   


# wsl安装
关于windows安装wsl，出现WslRegisterDistribution failed with error: 0x8007019e The Windows Subsystem错误的解决方案：
powershell输入Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
wsl --install
# docker安装
官网下载；无脑next；
官方教程：https://learn.microsoft.com/zh-cn/windows/wsl/tutorials/wsl-containers 但没啥用
# Jekyll使用
