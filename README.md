[TOC]
## 虚拟机版本

- VM VMware 12

## 创建虚拟机

安装 VMware 12 完成后，启动软件进行如下操作。

### 1. 新建虚拟机向导

- 选择“文件” - “新建虚拟机”，出现以下界面。
- 选择“自定义（高级）”，点击下一步。

![](https://raw.githubusercontent.com/MorphiNerd/LinuxNote_1/master/img/001.%E6%96%B0%E5%BB%BA%E8%99%9A%E6%8B%9F%E6%9C%BA%E5%90%91%E5%AF%BC.png)

### 2. 选择虚拟机硬件兼容性

- 默认不进行修改，点击下一步。

![](https://raw.githubusercontent.com/MorphiNerd/LinuxNote_1/master/img/002.%E8%99%9A%E6%8B%9F%E6%9C%BA%E7%A1%AC%E4%BB%B6%E5%85%BC%E5%AE%B9%E6%80%A7.png)

### 3. 安装客户端操作系统

- 选择最后一项“稍后安装操作系统”，点击下一步。

![](https://raw.githubusercontent.com/MorphiNerd/LinuxNote_1/master/img/003.%E5%AE%89%E8%A3%85%E5%AE%A2%E6%88%B7%E7%AB%AF%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.png)

### 4. 选择客户端操作系统

- 选择Linux，版本选择CentOS 64 位，点击下一步。

![](https://raw.githubusercontent.com/MorphiNerd/LinuxNote_1/master/img/004.%E9%80%89%E6%8B%A9%E5%AE%A2%E6%88%B7%E7%AB%AF%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.png)

### 5. 命名虚拟机和选择虚拟机位置

- 输入虚拟机名称，并选择虚拟机文件存放路径，点击下一步。

![](https://raw.githubusercontent.com/MorphiNerd/LinuxNote_1/master/img/005.%E5%91%BD%E5%90%8D%E8%99%9A%E6%8B%9F%E6%9C%BA%E5%92%8C%E9%80%89%E6%8B%A9%E8%99%9A%E6%8B%9F%E6%9C%BA%E4%BD%8D%E7%BD%AE.png)

### 6. 处理器配置

- 为虚拟机选择处理器配置，默认即可。当然也可以根据自己的电脑配置进行选择。选择完成后，点击下一步。

![](https://raw.githubusercontent.com/MorphiNerd/LinuxNote_1/master/img/006.%E5%A4%84%E7%90%86%E5%99%A8%E9%85%8D%E7%BD%AE.png)

### 7. 虚拟机内存配置

- 为虚拟机分配内存，最低为 1G 。也可根据自己电脑配置进行选择，完成后点击下一步。

![](https://raw.githubusercontent.com/MorphiNerd/LinuxNote_1/master/img/007.%E8%99%9A%E6%8B%9F%E6%9C%BA%E5%86%85%E5%AD%98%E9%85%8D%E7%BD%AE.png)

### 8. 网络类型

- 选择 “使用网络地址转换（NAT）”,点击下一步。

![](https://raw.githubusercontent.com/MorphiNerd/LinuxNote_1/master/img/008.%E7%BD%91%E7%BB%9C%E7%B1%BB%E5%9E%8B.png)

### 9. 选择I/O 控制器类型

- 选择 LSI Logic ，点击下一步。

![](https://raw.githubusercontent.com/MorphiNerd/LinuxNote_1/master/img/009.%E9%80%89%E6%8B%A9IO%E6%8E%A7%E5%88%B6%E5%99%A8%E7%B1%BB%E5%9E%8B.png)

### 10. 选择磁盘类型

- 选择 SCSI ,点击下一步。

![](https://raw.githubusercontent.com/MorphiNerd/LinuxNote_1/master/img/010.%E9%80%89%E6%8B%A9%E7%A3%81%E7%9B%98%E7%B1%BB%E5%9E%8B.png)

### 11. 选择磁盘

- 选择 “创建新虚拟磁盘” ，点击下一步。

![](https://github.com/MorphiNerd/LinuxNote_1/blob/master/img/011.%E9%80%89%E6%8B%A9%E7%A3%81%E7%9B%98.png?raw=true)

### 12. 指定磁盘容量

- 最大磁盘大小可根据电脑配置情况自行选择。
- - [ ]  立即分配所有磁盘空间，该项不要Check。

![](https://github.com/MorphiNerd/LinuxNote_1/blob/master/img/012.%E6%8C%87%E5%AE%9A%E7%A3%81%E7%9B%98%E5%AE%B9%E9%87%8F.png?raw=true)


### 13. 指定磁盘文件

- 默认下一步即可。

![](https://github.com/MorphiNerd/LinuxNote_1/blob/master/img/013.%E6%8C%87%E5%AE%9A%E7%A3%81%E7%9B%98%E6%96%87%E4%BB%B6.png?raw=true)

### 14. 已准备好创建虚拟机

- 点击“完成”，即完成创建虚拟机。

![](https://github.com/MorphiNerd/LinuxNote_1/blob/master/img/014.%E5%B7%B2%E5%87%86%E5%A4%87%E5%A5%BD%E5%88%9B%E5%BB%BA%E8%99%9A%E6%8B%9F%E6%9C%BA.png?raw=true)


