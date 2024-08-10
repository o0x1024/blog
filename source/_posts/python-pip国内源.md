---
title: python pip国内源
date: 2024-08-10 23:03:11
tags: tool
description: 收录了一些国内python安装库文件的源
---


### 1.指定包名安装，package改成要安装的包名
```
pip install package -i http://mirrors.aliyun.com/pypi/simple/ --trusted-host mirrors.aliyun.com
```
### 2.依据requirements.txt安装
```
pip install -r requirements.txt -i http://mirrors.aliyun.com/pypi/simple/ --trusted-host mirrors.aliyun.com
```

### 3.设置为全局源
```
pip config set global.index-url mirrors.aliyun.com/pypi
pip config set install.trusted-host mirrors.aliyun.com
```


### 4.国内常用镜像
https://pypi.tuna.tsinghua.edu.cn/simple     #清华
http://mirrors.aliyun.com/pypi/simple/       #阿里云
https://pypi.mirrors.ustc.edu.cn/simple/     #中国科技大学
http://pypi.hustunique.com/                  #华中理工大学
http://pypi.sdutlinux.org/                   #山东理工大学
http://pypi.douban.com/simple/               #豆瓣   