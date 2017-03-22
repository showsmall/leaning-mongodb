# 安装

以 MongoDB Community Edition 为例，参考官方文档

https://docs.mongodb.com/manual/installation/

## 下载

在官方下载页面

https://www.mongodb.com/download-center

选择需要的版本，如

- Ubuntu 16.04 Linux 64-bit x64
- Windows Server 2008 R2 64-bit and later, with SSL support x64

## 安装

### Ubuntu 16.04

- 直接解压

    解压缩前面下载的安装文件，如 `mongodb-linux-x86_64-ubuntu1604-3.4.2.tgz`， 就可以直接用的，无需安装。bin目录下就是各个执行文件，直接跑起来就是。

    ```bash
    mv mongodb-linux-x86_64-ubuntu1604-3.4.2 /youpath/mongodb
    cd /youpath/mongodb/bin
    ./mongod
    ```

	为了使用方便，可以将 `/youpath/mongodb/bin` 路径加入到PATH路径。

- apt-get 安装

	也可以使用 apt-get 安装，具体命令请参考官网说明：

	https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/





