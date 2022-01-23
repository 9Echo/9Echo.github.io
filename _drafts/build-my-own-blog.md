---
layout: post
title: "build my own blog"
date: 2022-01-22
---

- [x] 添加blog（archive）、category、tag、tool、cv等其他页面
- [x] 修改post样式，各标题大小、前后间隔等
- [x] 重新设计html，是否需要添加分隔栏等
- [ ] 添加中文字体
- [x] 添加网页图片
- [ ] 设计主页面（index.html）
- [ ] 设计四个分页面
  - [x] tags页面设计：显示所有的tag，以及每个tag下对应该tag的文章（按时间排序），格式参考[这里](http://codinfox.github.io/blog/tags/)
  - [ ] categories页面设计：同tags页面，增加选择，选择不同的categories，显示所选的post，按时间排序
  - [ ] archive页面：显示所有的post，按时间排序，最近的优先显示
  - [ ] about页面设计：自我介绍
- [ ] post页面添加可折叠目录


# How

该博客是由GitHub pages+Jekyll 搭建，域名自行购买

修改域名：CNAME文件



# What

### 我做了哪些修改？

- 添加网站logo

  > 具体参考[这里](https://medium.com/@xiang_zhou/how-to-add-a-favicon-to-your-jekyll-site-2ac2179cc2ed)

- 添加目录页面

  > 具体参考[这里](https://blog.webjeda.com/jekyll-categories/)
  
- 添加tags页面

  > 具体参考[该博客tags设置](https://github.com/Gabriel-Chen/Nice_Blog/blob/master/tags.html)

1. layouts 修改
   - 去掉head、footer的border线条
   - site-header居中
   - nav位于header下方
2. scss 修改
   - block quote的背景颜色
   - 字体、颜色以及link添加对应下划线
3. pages 添加
   - 添加blog（archive）、category、tag等页面，后续可以继续添加tools，cv等页面

# Why

学习、生活、工作记录

名字（A Room of My Own）

来源：伍尔夫：一个人的房间