---
title: 欢迎来到刘小刚的小站
layout: default
---

# 欢迎来到我的个人网站

![个人头像](https://github.com/iuang0305/gangliu/blob/main/assets/images/gangliu.jpg) 
*这是我的个人空间*

## 关于我

我是刘小刚(xiaogangliu)，这是我的个人网站，主要分享：

- 技术博客
- 项目展示
- 学习笔记

## 最新动态

{% for post in site.posts limit:3 %}
### [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%Y-%m-%d" }}  
{{ post.excerpt }}
{% endfor %}

[查看全部文章](/blog)

## 联系我

📧 邮箱：phyiuang0305@gmail.com 
💻 GitHub: [xiaogangliu](https://github.com/iuang0305)
