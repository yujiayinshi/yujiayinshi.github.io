---
title: 使用Hexo搭建博客
tags: [Hexo]
categories: 教程
---
很久以前，就想要写技术博客，写过一段时间CSDN博客，也会在简书上面写一些，也折腾过Jekyll、Hexo，最后还是选择使用[Hexo](https://hexo.io/)，主题选用了[Hexo-theme-hiker](https://github.com/iTimeTraveler/hexo-theme-hiker)，风格简单清新，整体很舒服，个人觉得是很不错的主题。

## 快速开始

### 安装

``` bash
$ npm install hexo-cli -g
$ hexo init blog
```
下载Hexo-theme-hiker，置于hexo项目的theme目录下，修改_config.yml文件中的theme为hiker。

### 创建一篇文章或页面

``` bash
$ hexo new "My New Post"
$ hexo new page about
```

更多:  [Writing](https://hexo.io/docs/writing.html)

### 运行

``` bash
$ hexo server
```

更多:  [Server](https://hexo.io/docs/server.html)

### 生成静态文件

``` bash
$ hexo generate
```

更多:  [Generating](https://hexo.io/docs/generating.html)

### 部署至站点

同步到git，安装git插件，并修改_config.yml文件中，将deploy下的type设为git
``` bash
$ npm install hexo-deployer-git –save
$ hexo deploy
```

直接部署
``` bash
$ hexo deploy
```

更多:  [Deployment](https://hexo.io/docs/deployment.html)
