---
title: "Build Bolg"
date: 2021-02-08T22:23:57+08:00
draft: true
---

1.下载windows版本hugo  
2.hugo创建一个站点   
    `hugo new www`  
3.在其中创建文章  
    `hugo new post/first.md`  
4.下载主题  
    `git clone https://github.com/spf13/hyde.git`   
5.运行Hugo   
    `hugo server --theme=hyde --buildDrafts`  
6.部署  
    `hugo --theme=hyde --baseUrl="http://LiuHao321.github.io/"`  
