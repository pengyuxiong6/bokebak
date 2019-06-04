---
title: 使用hexo github搭建个人博客
date: 2019-06-04 17:25:41
tags:
---
## 一，服务器安装git
第一步：先安装git工具
```shell
    yum -y i git

```
输入git命令测试，若出现相应的提示说明安装成功。

第二步：新建一个用户起名git
```shell
    adduser git

```
第三步：在/home/git/
目录下创建一个名为.ssh的文件夹,在其.ssh目录
