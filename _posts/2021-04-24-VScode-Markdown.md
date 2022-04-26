---
title: VScode-Markdown
date: 2022-04-24 10:34:00 +0800
categories: [随笔]
tags: [生活]
pin: true
author: TXY

toc: true
comments: true
math: false
mermaid: true

---

# VScode一站式解决Markdown文档问题

## 除Typora外Markdown文档管理选择
目前Typora增加了付费管理，并在逐步规范老版本规避升级的漏洞，因此本文给出基于VScode的解决方案，针对Markdown文档的编辑、查看、导出目录版PDF等给出简单指导，欢迎大家讨论补充。

## VScode的Markdown文档支持说明
VScode本身支持md文档的编辑与编译等功能，然而对于文档的查看与导出等管理不够完善，需要额外插件进行管理，具体操作如下：

 - 打开一个md文件，点击右上方侧边预览即可看到编译生成的预览文档

![在这里插入图片描述](https://img-blog.csdnimg.cn/5cd9b36d9aa849d99835d3925c6b303c.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAY2FsbGluZ3R4eQ==,size_20,color_FFFFFF,t_70,g_se,x_16)

- 点击左侧栏的拓展，输入markdown找到Markdown All in One插件，点击安装

![在这里插入图片描述](https://img-blog.csdnimg.cn/4f87dfe9136a44388d0306a0cde6b64b.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAY2FsbGluZ3R4eQ==,size_13,color_FFFFFF,t_70,g_se,x_16)

- 安装成功后再次点击侧边预览时可以看到插件生效后生成了md预览文件

![在这里插入图片描述](https://img-blog.csdnimg.cn/a0d3a4b246af4fcfb601fb9ecc6b5a5a.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAY2FsbGluZ3R4eQ==,size_20,color_FFFFFF,t_70,g_se,x_16)

- 在预览文档中右键选择pdf

![在这里插入图片描述](https://img-blog.csdnimg.cn/4c669c4d8113458db6f3ea4530b42056.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAY2FsbGluZ3R4eQ==,size_20,color_FFFFFF,t_70,g_se,x_16)

**此处点击pdf后可能会报错："princexml" is required to be installed**，具体解决办法参考[此篇文章](https://www.likecs.com/show-204406576.html)

- 点击pdf后即可得到生成好的，带有书签目录导航的pdf文件

![在这里插入图片描述](https://img-blog.csdnimg.cn/485353c939414b3ab33ad3f549011cae.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAY2FsbGluZ3R4eQ==,size_20,color_FFFFFF,t_70,g_se,x_16)