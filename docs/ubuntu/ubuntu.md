## 一、 Ubuntu 的任务栏

![img](https://gitee.com/zgf1366/pic_store/raw/master/img/20210119161547.jpg)

## 二、 窗口操作按钮

![img](https://gitee.com/zgf1366/pic_store/raw/master/img/20210119161602.jpg)

## 三、窗口菜单条

![img](https://gitee.com/zgf1366/pic_store/raw/master/img/20210119161612.jpg)

## 四、软件安装

### 1. 通过 apt 安装／卸载软件

- apt 是 `Advanced Packaging Tool`，是 Linux 下的一款安装包管理工具
- 可以在终端中方便的 **安装**／**卸载**／**更新软件包**

```bash
# 1. 安装软件
$ sudo apt install 软件包

# 2. 卸载软件
$ sudo apt remove 软件名

# 3. 更新已安装的包
$ sudo apt upgrade 
```

### 2. 配置软件源

- 如果希望在 `ubuntu` 中安装软件，**更加快速**，可以通过设置**镜像源**，选择一个访问网速更快的服务器，来提供软件下载／安装服务
- 提示：更换服务器之后，需要一个相对比较长时间的更新过程，需要耐心等待。更新完成后，再安装软件都会从新设置的服务器下载软件了

> 所谓镜像源，就是所有服务器的内容是相同的（镜像），但是根据所在位置不同，国内服务器通常速度会更快一些！

![003_镜像服务器示意图](https://gitee.com/zgf1366/pic_store/raw/master/img/20210119172202.png)

![001_ubuntu设置软件源](https://gitee.com/zgf1366/pic_store/raw/master/img/20210119172209.png)