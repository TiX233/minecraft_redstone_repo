# 我的世界红石

## 一、项目介绍

这是一个尝试在现实中实现红石的小项目，因为一些缺陷，将放弃模拟方案，转为数字方案

![rs](./Pic/封面2.png)

效果演示：[【Bilibili】红石中继器进度报告](https://www.bilibili.com/video/BV1awhPzsEa1)

硬件开源地址：[【Oshwhub】@realTiX - 我的世界红石_模拟方案](https://oshwhub.com/realtix/mc_redstone_analog)

## 二、仓库介绍

本仓库使用 repo 管理，以便管理多种红石器件

### 1、repo 介绍

[【CSDN】repo 简单搭建学习记录](https://blog.csdn.net/realTiX/article/details/142501192)  
[【CSDN】windows 下 repo 安装](https://blog.csdn.net/weixin_42107504/article/details/140709590)

### 2、本项目使用方法

**repo 初始化**  

```shell
repo init -u https://gitee.com/TiX233/minecraft_redstone_repo -b master -m analog_gitee.xml
```

**repo 同步**  

```shell
repo sync
```

### 3、不想使用 repo？

那么打开对应的 xml 文件，从中手动克隆所需红石元件即可
