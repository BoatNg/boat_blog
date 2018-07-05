---
title: 又好又快部署https证书的若干建议
subTitle: https证书部署莞式服务
category: "Operation"
cover: cover.jpg
---

### 本文主要内容包括以下方面
* https的好处
* https证书常识
* https证书获取
* https证书部署
* 其他https证书部署方法

### 前置知识及注意事项
##### *如果您对以下内容有疑惑，请先通过百度或Google解决相关问题，否则阅读本文会有不同程度的困难*
* 本文所有的操作在Linux系统下进行，默认该系统已安装nginx，且nginx成功运行
* 您已拥有至少一个域名
* Linux基础知识
* vi/vim 编辑器基础命令
* nginx配置基础知识
* 本文涉及的https证书均免费

***

### 正文

#### https的好处
https最主要的好处是安全，目前chrome浏览已经对不是https的网站提示不安全，微信已经不接受http协议的网站接入等等，这些大厂的行动说明https的时代已经来临。
次要的好处是，防止网页被挟持。2015年底曾发生过小米科技与腾讯、微博、今日头条等六家互联网公司联合呼吁运营商打击流量劫持 [:)我是一条link](https://www.zhihu.com/question/38861118)。
当然还有其他好处，但本文就不一一细说

#### https证书常识
https证书是由某一权威中心颁发，针对域名认证的。

> 未完待续...



