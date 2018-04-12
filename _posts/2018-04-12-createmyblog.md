---
layout: post
title: 个人博客搭建
date: 2018-04-10
categories: 博客搭建
tags: 博客搭建
music-id: 108251
cover: https://codingstyle-cn.b0.upaiyun.com/photo/2015/de7a9fa3b0d7df4f3bb2c6143ebcdbd0.png

## 材料
* git（非必须，但便于管理）
* github 账号

## 过程
* 在github 账号下创建一个格式为: github用户名.github.io 的仓库
* 利用git 将空仓库克隆到本地
* 在[jekyll themes](http://jekyllthemes.org/)  挑选自己满意的主题 并download
下载下来的文件为 zip压缩包
解压将里面的内容复制到克隆下来的本地仓库中，与.git文件夹同目录
如图![](https://upload-images.jianshu.io/upload_images/8980525-e2e65ee052baf4e5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
红框框内为复制内容；
* 对模版进行修改加工，_config.yml 为全局配置文件，博客内容在post 文件夹中，每一个主题的操作方法有些不同，README.md 文件中就会详细的介绍主要操作方法（博客内容的编写需要用到markdown语法）
* 通过git 命令
```
git status 
git add
git commit -m " "
git remote add origin 仓库ssh
git push -u origin master
```
将博客文档上传至远程仓库；

## 结束
在浏览器地址框输入 http:// github用户名.github.io 就可以浏览自己的个人博客啦

![](https://upload-images.jianshu.io/upload_images/8980525-c386aa041ddf2b76.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
