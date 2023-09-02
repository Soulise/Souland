---
title: Test
date: 2023-09-02T02:27:04+08:00
tags:
  - test
draft: true
---

大黄狗阅后即焚 



1. 如何写一篇文章

- 转到Souland目录，手动或者在终端执行`cd ~/Souland`命令
- 生成文章草稿，在Souland目录下在终端执行`hugo new content/posts/[你的文档名字.md]`
- 写完后预览效果，在终端执行`hugo server -D`，可以在浏览器打开`http://localhost:1313/`预览
- 修改啊草稿标志，果确认没有问题，就`cltr + c`终止预览，在博客最上面那个`draft: true` 改成`draft: false`，如果是草稿，网站是不会发布的，所以要改成非草稿
- 发布到网站，输入命令`sh deploy.sh`发布到网站上，你可以在`https://github.com/Soulise/Souland/actions`上看到你的发布过程，一般1min不到
- 浏览器输入`https://soulise.github.io/Souland/`可以观摩一下自己的小站，查看最新的内容
- 当上传不成功时：开启终端代理proxy，结束命令proxyOFF

2. 接下来

- 搜索一下hugo常用命令
- 更改`Souland/hugo.toml`里面的配置来配置你的狗窝
- 删掉这篇博客
- 写更多或者更改更多内容
