---
description: NullCraft Minecraft Mods Updater
---

# 灵工艺我的世界模组更新器

## 软件信息 <a href="#ruan-jian-xin-xi" id="ruan-jian-xin-xi"></a>

> 本软件由 [NullCraft Studio (灵工艺工作室)](https://nullcraft.org) 开发\
> 运行支持库 [.NET4.0或更高版本](https://www.microsoft.com/zh-cn/download/details.aspx?id=17718)

### 使用前准备

* 确定自己有一个直连URL服务例如 https://abc.com/123.zip 这种 \[[没有?购买灵工艺存储服务](https://unnocloud.com/cloud/oss/)]
* 拥有熟练的 Windows 复制/粘贴/等操作
* 拥有熟练的压缩包打包技术 (.zip)
* 确认电脑已安装 .NET 4.0 或更高版本 [.NET4.0 下载](https://www.microsoft.com/zh-cn/download/details.aspx?id=17718)
* 确认当前软件最新版本或官方发布版本 [MCBBS发布帖](https://www.mcbbs.net/thread-791922-1-1.html)

## 配置在线文件

### 文件包下载地址

此选项里填写更新文件的直连下载地址

{% hint style="info" %}
例如 [https://你的服务器域名/IP/文件包.zip](https://xn--6qq22fh5a56du8bd04b1xy/IP/%E6%96%87%E4%BB%B6%E5%8C%85.zip)\
如果没有可以购买灵工艺的存储服务**6RMB/月** [了解一下](https://unnocloud.com/cloud/oss/)
{% endhint %}

{% hint style="warning" %}
文件包请务必使用 **`ZIP格式`** 下载地址必须为直连!
{% endhint %}

### 文件包版本

此选项是用来判断是否拥有更新的,每次更新包文件吧版本号加 `0.1` 即可

{% hint style="info" %}
本地版本号更新后会自我升级,不用担心出现无更新等情况
{% endhint %}

### 备用下载

备用即为无法使用直连下载提供的备份下载功能,可以使用 `直连` 或 `网盘`

{% hint style="info" %}
直接下载失败后会自动开启备用下载按钮
{% endhint %}

### 文件更新类型

#### **`替换式更新`** 即为将**`模组`**与**`模组配置文件夹`**全部删除放入全新的模组与配置文件

替换式更新是会删除全部用户 **`mods与config`** 文件夹的内容然后放入打包文件里的 **`mods与config`** 文件

例如用户老版本的 **`mods和config`** 文件夹里有2个模组分别是 **`例子1.jar和例子2.jar`** 替换式更新就会**删除**它们然后放入你打包ZIP里的文件

#### **`新加文件式更新`** 即为在不动原文件的情况下更新

例如今天要**单独或追加**更新 **`例子模组.jar 和 例子模组的配置文件` ** 我们就需要将它们打包到对应文件夹

最后ZIP目录结构是这样的:

mods/例子模组.jar\
config/例子模组的配置文件

> Tips:如果想更新模组版本仅需使用 `新加文件式更新` 将更新模组名命名为老模组名即可替换

### 更新内容

即为更新时显示的本次更新内容,可写,可不写

## 配置本地文件

### 读取地址

即为 **`在线文件`** 的访问地址

{% hint style="info" %}
例如 [https://你的服务器域名/IP/Version.json](https://xn--6qq22fh5a56du8bd04b1xy/IP/Version.json)\
如果没有可以购买灵工艺的存储服务**6RMB/月** [了解一下](https://unnocloud.com/cloud/oss/)
{% endhint %}

{% hint style="warning" %}
**`Version.json`** 为在线文件默认文件名,可自定义
{% endhint %}

### 服务器名称

即为更新时软件上方显示的名称

### 文件包版本

与在线文件类似,与在线版本不符即视为拥有更新,双方默认均为 **`1.0`**

### 更新后启动启动器

即为更新完毕后自动启动整合包内的默然启动器,填写启动器名称即可 **不用带拓展名**

### 更新后删除下载文件

即为更新后删除本地下载缓存包

{% hint style="info" %}
Tips:不删除可以防止更新出现问题作为备份让用户自行更新替换
{% endhint %}
