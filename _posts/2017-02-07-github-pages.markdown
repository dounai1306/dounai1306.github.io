---
layout: post
title:  "GitHub Pages"
date:   2017-02-07 15:07:14 +0800
categories: GitHub
---
### Project site

由于github改版的原因，之前网上很多教程在教初学者使用GitHub Pages时，会提到 `Launch automatic page generator`。在新版本里，已经不存在这个按钮。

正常操作流程如下：Repository -> Settings -> Options -> GitHub Pages

Source选择master，然后Save

Theme chooser选择一个主题


### User or organization site

新建一个repository，Repository name里填写username.github.io。

clone下来后，新建一个index.html，并输入内容，push上去即可。


### jekyll GitHub Pages
正常安装相关软件
`gem install jekyll bundler`

`jekyll new myblog`

`cd myblog`

`bundle exec jekyll serve`

打开http://127.0.0.1:4000/

push 到 username.github.io，使用username.github.io访问即可。

[官方文档](https://pages.github.com/)