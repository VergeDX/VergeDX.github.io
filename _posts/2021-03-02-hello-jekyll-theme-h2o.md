---
layout: post
title: 'Hello jekyll-theme-H2O'
date: 2021-03-02
author: Vanilla
cover: ''
tags: 
---

老规矩，第一篇博客是讲述搭建过程的。

> Jekyll 是一个简单的静态网站生成器，用于生成个人，项目或组织的网站。 它由 GitHub 联合创始人汤姆・普雷斯顿・沃纳 用 Ruby 编写，并根据 MIT 许可证发布。
本次选择主题 [kaeyleo/jekyll-theme-H2O](https://github.com/kaeyleo/jekyll-theme-H2O) 来进行搭建。

### Ruby
Jekyll 由 Ruby 写成，所以首先需要安装 Ruby 及其包管理器 gem。
根据 [Ruby 的描述](https://www.ruby-lang.org/en/documentation/installation/#homebrew)，从 macOS El Capitan (10.11) 开始，系统中已预装好 Ruby 2.0 版本。若是在其它平台，可以参考 [Jekyll 的教程](https://jekyllrb.com/docs/installation/)。

### Jekyll
在 macOS 上，[根据描述](https://jekyllrb.com/docs/installation/macos/#global-install)，使用命令 `sudo gem install bundler jekyll` 即可安装。

### 使用 kaeyleo/jekyll-theme-H2O 主题
把仓库拉下来，在 **根目录** 运行命令 `jekyll server`，将会在本地开启服务器，以供预览。
