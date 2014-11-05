title: 猫窝建立备忘
date: 2014-11-04 15:27:24
tags:
- tech
- hexo
---
折腾了半天终于是把这玩意搭起来了。

写下备忘，

####安装
这没什么好说的
```
npm install hexo
```
由于是内网，不论是git还是npm都要设置代理，其中比较坑的是，git一直无法通过powershell连上，估计是内网firewall把22端口和443端口都封了，只能通过客户端来连接github。

####设立github Page
也没什么好说的，new 一个名为username.github.io的repo就好了，刚开始没看文档，写成了username.github.com……还傻逼地看了半天

####写博文
```
hexo new <title>
```

####生成&展开
hexo generate --deploy

####写在最后的备忘
别忘了改掉config文件。。。
最后的最后：终于有node的静态博客引擎了，喜闻乐见~