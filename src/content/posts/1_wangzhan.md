---
title: 【知识地图#0】bardoの网站
date: 2025-08-14
summary: 重拾一下之前的网站
category: 知识地图
tags: [学习, 前端, 后端, github, vscode]
comments: true
---

# 介绍

讲述这个网站是如何被建立的，以及记录关键开发部分。

# github以及astro模板部分

一步一步地跟着视频走就行

<!-- 修改后的嵌入代码，添加autoplay=0参数 -->
<iframe 
  src="https://player.bilibili.com/player.html?bvid=BV1oxsDesEwt&page=1&autoplay=0" 
  scrolling="no" 
  border="0" 
  frameborder="no" 
  framespacing="0" 
  allowfullscreen="false"
  width="800" 
  height="450">
</iframe>

# vscode部分

首先需要在vscode中的资源管理器部分打开博客本地文件夹，随后调出终端。

- ## 主要指令

```
  cd .\bardolight.github.io\
```

**代码作用**：切换终端的文件夹路径，改成bardolight.github.io这个里面。

```
  pnpm i
```

**代码作用**：下载或更新依赖

```
  pnpm dev
```

**代码作用**：建立一个本地可以*实时观看改动*的网站，与最后发行版本有区别。

ctrl+c中断

```
  git add .
  git commit -m "feat: test"
```

**代码作用**：第一行是把文件提交到暂存区，第二行是把暂存区的内容打包成一个“快照”（commit），
其中feat后面的就是这次提交版本的名称

```
  git push
```

**代码作用**：**发行！！！**

::codepen{#NPGwpGY author="Chris Bolson"}

# 写在最后

> 和她相遇的那天，我的脑海中只有一句话：草在结它的种子，风在摇它的叶子。我们站着，不说话，就十分美好。——顾城《门前》
