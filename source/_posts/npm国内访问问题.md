---
title: npm国内访问问题
date: 2018-12-23 18:19:23
categories:
- Linux
tags: 
- npm
- macOS
- 采坑
---

# 使用npm安装失败 报错rollbackFailedOptional 

亲自试过是可以用的，网上给了好多，在这说一下我筛选后的方法。

+ 1.通过config
```
npm config set registry https://registry.npm.taobao.org 
npm info underscore 

```
+ 2.通过命令行
```
npm --registry https://registry.npm.taobao.org info underscore 

```

设置好即可使用npm了。





