---
description: Open Minecraft Server
---

# Minecraft 开服教程

{% hint style="info" %}
服务端下载可访问灵工艺资源广场:[https://mcres.net/](https://mcres.net/) 或 前往[用户交流群](https://jq.qq.com/?\_wv=1027\&k=5CNpRf5)下载\
(灵工艺资源广场**不提供**一些**过老**的资源)
{% endhint %}

## 了解服务端

### 服务端类型

我的世界服务端拥有很多种类,但永远离不开以下 **`3`** 种大类型

1. 纯插件类 如 **`PaperSpigot` 、`Spigot` 、`CraftBukkit`**
2. 纯模组类 如 **`Sponge`**
3. 插件/模组同时支持类 $$^{1}$$ 如 **`CatServer(1.12.2)`** **、`Thermos(1.7.10)`**

例如: **`PaperSpigot`** 就是一个仅支持插件的服务端，这也是我们推荐的服务端，它是优化版的**`Spigot`**服务端，拥有更好的性能与兼容绝大部分**`Spigot`**的插件

例如: **`Thermos`** 就是一个兼容普通插件与模组的服务端，但大部分插件模组端都没有完整的版本分支，此端最新版目前为 1.7.10-forge1614 版

> $$^{1}$$有些同时支持服务端的插件是以模组形式使用的，与其他插件端插件不兼容，**换句话说不是一个东西**\
> 例如 **`Sponge`** 服务端

### 服务端大致版本分布

由于市面上有两大分支类型的服务端 **插件**、**模组** 其类型均由**非官方**制作**，**所以版本**不一定**能跟上**官方最新版**本 例如

1. 插件端，现在常用的插件端一般都会跟随官方版本发布对应的端
2. 模组端，一般无法跟随官方版本，固定停留在一些大版本上进行更新 如 **1.7.10**、**1.12.2、**等，具体要前往服务端官网查看最大支持版本。
3. 官方纯净端安装Forge 添加模组，需要根据Forge作者提供对应版本

### 服务端结构

对于 **`插件服`** 和 **`模组服(模组+插件服)`** 的文件结构是不一样的，插件端都是单个核心文件，只要涉及到模组，就会带有 **`libraries`** 文件夹 有时还会带有多个核心jar 如 **`minecraft_serverx.xx.jar`** 或 **`forgex.xx.jar`** 一般模组服都会提供压缩包格式，里面的文件要全部解压并放置到开服器下的 **`Server`** 文件夹内

## 开服前准备

### 下载灵工艺开服软件

(我们现在优先推荐使用轻开服器，功能更多，性能更高)

{% content-ref url="../software/minecraft-server-lite.md" %}
[minecraft-server-lite.md](../software/minecraft-server-lite.md)
{% endcontent-ref %}

{% content-ref url="../outdated/minecraft-server-pro.md" %}
[minecraft-server-pro.md](../outdated/minecraft-server-pro.md)
{% endcontent-ref %}

### 开启服务器

这里我们使用灵工艺我的世界轻开服器进行演示说明，操作步骤可兼容C#Pro版。

首先，打开软件，软件会自动在软件目录下生成 **`server`** 文件夹，此文件夹将用于存放服务端与数据，将你的核心所有内容复制进 **`server`** 进入轻开服器的本体设置，可以在核心选择中快速设定启动的服务端核心，Pro版需要手动修改核心名称为 **`start.jar`** \[ **!** ] 注意拓展名

对于模组端的启动核心，大家可自行一个一个尝试。

选择好核心后进入控制面板，点击开启服务器，不出问题服务器就成功开启了，如果遇到无法成功开启，可查看此页

{% content-ref url="../issue/server.md" %}
[server.md](../issue/server.md)
{% endcontent-ref %}
