---
title: Anki知识卡片，复习好工具
published: 2026-05-22
updated: 2026-05-22
pinned: false
description: 基于间隔重复理论的智能卡片学习软件Anki，从下载安装到进阶配置，让你的复习效率翻倍。
tags:
  - 教程
  - Markdown
  - Anki
  - 知识
  - 效率工具
  - 学习方法
draft: false
category: 工具教程
image: api
---
# 高效复习的工具--Anki知识卡片
> 多图警告，注意流量消耗。
> 本文档中涉及的外部链接及软件版本可能随时间变化，若发现失效请访问 Anki 官网获取最新信息。

相信很多朋友在复习的时候都遇见过这些困扰：
- 这个知识点明明刚刚背了，翻到下一页之后就记不起来了；
- 一次看到一整面密密麻麻的知识点，无从下手；
- 背过的知识点总是忘了又背、背了又忘。

## 什么是Anki？
Anki在日语中意为“记忆”，是一款基于**间隔重复（Spaced Repetition）** 理论的智能卡片学习软件。它的核心理念并不复杂：在我们即将忘记某个知识点的时候，恰好再次复习它，就能以最高效率把知识牢牢刻在长期记忆里。

简单来说，Anki就像一个聪明的记忆管家。你往里面存入学习资料（制成卡片），它会根据你的掌握程度，自动安排在最适合的时间提醒你复习——容易的卡片间隔越来越长，困难的卡片频繁出现直到你记住为止。

全球有数百万人在使用Anki，从医学生记忆解剖术语，到语言学习者掌握数千个单词，再到程序员背诵算法和命令——只要有需要记忆的内容，Anki都能派上用场。

## 下载Anki
### 电脑端（Windows/Linux/MacOS）
[Anki官方网站](https://apps.ankiweb.net/)在这里,点击即可到达。
![官网照片](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlERDJvUlp5MlBaTFhqN1dLLWxjVVhHakVUUHk1QkFBS25GMnNiRDd1UVZQMmZ0MG5pbUo5M0FRQURBZ0FEZHdBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTI1NDAwMDU3LndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjY2Mzc4LCJ0IjoxNzc5NTI1NDIyMzIxLCJtaWQiOjc4M30.jBUGCCwpxdOlcTD1ntVZ57pVKhi0hyO71v_eRE7Nu_s.webp)
#### Windows:
1. 访问官网
2. 点击“Download”按钮
3. 运行下载的.exe文件

另外，Windows x64下载链接贴在下面：
[官方下载链接](https://github.com/ankitects/anki/releases/download/25.09/anki-launcher-25.09-windows.exe)Github线路
[Naitang 线路](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQlFBQ0FnVUFBeUVHQUFUcVduQ2pBQUlERVdvUmJHeGwxLVJTMV9vYUJ6blJnZTFMdUNIeUFBS09KUUFDRDd1UVZOSloxdzRHQWFyYU93USIsImUiOiJleGUiLCJuIjoiYW5raS1sYXVuY2hlci0yNS4wOS13aW5kb3dzLmV4ZSIsIm0iOiJhcHBsaWNhdGlvbi94LW1zZG93bmxvYWQiLCJzIjoxMjU5OTgxNiwidCI6MTc3OTUyNjc2NDcyNCwibWlkIjo3ODV9.U9HPbwUwZfyXxC1w4UOvqTqnEKXSm49_xiPtC5xRfK8.exe)Cloudflare线路

Windows运行安装程序，可以选择更换默认安装路径。
![Anki安装](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlERTJvUmI1ZEJwZjRvTW1INWNJOUN6U0JNeEswNEFBSy1GMnNiRDd1UVZQR0J0cDk1SVpfVEFRQURBZ0FEZUFBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTI3NTU4Nzc2LndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjEzMDIwLCJ0IjoxNzc5NTI3NTc2MTk1LCJtaWQiOjc4N30.PRvoEt3-uDxChbcLIEMs843tTR6cn4fEhFf1Nh-CJqM.webp)
出现命令行窗口，按照提示选择。
![安装页面](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlERldvUmNKUnA1LWtGRDBydGV4XzE4NmVma2NyX0FBTEJGMnNiRDd1UVZQVVkxa1pJaHBVVEFRQURBZ0FEZVFBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTI3ODEzOTIxLndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjE2Njg4LCJ0IjoxNzc5NTI3ODI4ODI5LCJtaWQiOjc4OX0.0gOpCNbXs8ctecySUY2PhKRF4qX7dmeu7UkFWYaDXH0.webp)
注意，这一步最好配置：选项7 镜像-China ，否则可能因为网络问题安装失败。
![修改镜像源](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlERjJvUmNyNmxkazVvbndHWEtEUDV4TlBUenR4bUFBTElGMnNiRDd1UVZNcWwtZkRwbnFyZUFRQURBZ0FEZVFBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTI4MzYzMTkzLndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjI2NzEwLCJ0IjoxNzc5NTI4MzgzMTQ0LCJtaWQiOjc5MX0.v5PkR_pFNdSwOE-qDqyG88muSDVSbbL4LnkzUbURG5Q.webp)
```txt
选项7）配置镜像源
enter/回车键
选项2）China/中国镜像源
enter/回车键
选项1）最新版本（默认值）
enter/回车键
```
之后等待安装即可。
> 注意：选项5) beta版本 一般情况下无需打开，保持off即可。
> 如果beta出现问题请前往Anki官方社区寻找解决办法。

#### Linux：
```bash
# Ubuntu/Debian
sudo apt install anki

# Arch Linux
sudo pacman -S anki

# 使用 Flatpak
flatpak install flathub net.ankiweb.Anki
```
**我相信使用Linux系统的人会自己学会安装的。**
#### macOS
**作者没有macOS设备，请自行前往Anki官网寻找安装办法。**

### 移动端
#### Android：
Anki官方app叫做“AnkiDroid”，完全免费。在各大应用商店都能找到。
不过注意，由于软件开源，第三方软件比较多，请认准名字。
这是Github链接：
AnkiDroid项目[Releases · ankidroid/Anki-Android](https://github.com/ankidroid/Anki-Android/releases)

同样贴一下下载链接：
Github Release下载[AnkiDroid-2.24.0-arm64-v8a.apk](https://github.com/ankidroid/Anki-Android/releases/download/v2.24.0/AnkiDroid-2.24.0-arm64-v8a.apk)
Naitang代理[AnkiDroid-2.24.0-arm64-v8a.apk](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQlFBQ0FnVUFBeUVHQUFUcVduQ2pBQUlER1dvUmRmRkRMUUdfNlYzcjNrQVpXUTZjeUx5NEFBS3VKUUFDRDd1UVZEU21sdG5JQXlhSk93USIsImUiOiJhcGsiLCJuIjoiQW5raURyb2lkLTIuMjQuMC1hcm02NC12OGEuYXBrIiwibSI6ImFwcGxpY2F0aW9uL3ZuZC5hbmRyb2lkLnBhY2thZ2UtYXJjaGl2ZSIsInMiOjM4OTAwOTI4LCJ0IjoxNzc5NTI5MjAyMjE1LCJtaWQiOjc5M30.-URioAnEsL2WoxmrGPpCXkweNgG3Mf9NF0oGmv5x9Uk.apk)
> 此处链接更新时间为2026/05/23，注意时效性，可能为过时内容。
#### IOS
**作者没有IOS设备，下方内容出自ai。**

iOS用户注意： Anki官方App名为“AnkiMobile Flashcards”，售价约¥168元。
这可能是你为学习花的最值得的一笔钱——收入会直接支持Anki的开发。
不过免费替代方案是使用AnkiWeb网页版。
## 配置Anki
![Anki主页面](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlERzJvUmx6bDFDUlNVM0hYX1A0eEhsTzNCQjdhNUFBS09FR3NidmlpUVZIVU84N3B6akdCQUFRQURBZ0FEZVFBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTM3NzA4MzY1LndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjIyNzM2LCJ0IjoxNzc5NTM3NzIyMjIyLCJtaWQiOjc5NX0.SmQUug51o0a9PfeRiywxP9A7g4N6rgiglwrbEd-K-j8.webp)
在开始使用前，先理解几个关键概念：
- 卡片（Card）：最小学习单元，正面是问题，背面是答案
- 笔记（Note）：原始信息，Anki会根据笔记类型自动生成一张或多张卡片
- 牌组（Deck）：卡片的集合，就像文件夹一样组织学习材料
- 复习间隔：根据你的记忆反馈，Anki自动计算的下次复习时间
- 牌组设置：每个牌组可以独立设置每日新卡片数、复习上限等参数
### 创建你的第一张卡片
1. 打开Anki，点击“**创建牌组**”，命名为“**英语学习**”
2. 点击顶栏“**添加**”，进入新窗口`添加`窗口
3. 在“正面”输入：“**苹果**”
4. 在“背面”输入：“**apple**”
5. 点击“**添加**”按钮![添加卡片](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlESFdvUm1ObHF6WUZyZjVIODhObllvQ2MyQnpiZkFBS1ZFR3NidmlpUVZDN3U1alBKY05VY0FRQURBZ0FEZVFBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTM4MTIzOTA5LndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjE1OTk2LCJ0IjoxNzc5NTM4MTM3NDg0LCJtaWQiOjc5N30.5-waUIx2gP07v7GFjI9FgV8zquZSE1HqdxMFhtNRDl4.webp)
6. 回到主界面，点击“**英语学习**”->“**开始学习**”![开始学习](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlESVdvUm1TcVNBQUdmVGZtS1lubWVBdEg4LXNCVXBBQUNseEJyRzc0b2tGUWxTcVJyVFF2NTl3RUFBd0lBQTNrQUF6c0UiLCJlIjoid2VicCIsIm4iOiJjbGlwYm9hcmRfMTc3OTUzODIwNTc3Mi53ZWJwIiwibSI6ImltYWdlL3dlYnAiLCJzIjoyMjc4MCwidCI6MTc3OTUzODIxODUyMiwibWlkIjo4MDF9.YihnO_QLcfQTixdNiQOKqdswPylNS-K1Z5RA7GdLKkE.webp)
学习时你会看到：
- 正面：苹果 
点击“**显示答案**”
- 背面：apple -> 根据记忆情况选择：
	- 重来（完全忘记了）
	- 困难（想起来了但很吃力）
	- 良好（正常回忆）
	- 简单（太简单了）
你的每次选择都会影响这张卡片下次出现的时间。![学习卡片示例](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlESTJvUm1lSjIxMHNvWWxCLWd2ZVVCaVlwSWJEWUFBS1lFR3NidmlpUVZLNk5CXzUzNnJlUUFRQURBZ0FEZVFBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTM4Mzg5ODg3LndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjEzOTg0LCJ0IjoxNzc5NTM4NDAyNTU5LCJtaWQiOjgwM30.IOLQ4NuC8TLHUbdFj1q7UhtmcnQ7Os-hPDBEmvQSm1M.webp)
### 进阶配置
#### 1. 基础设置（每个新牌组都建议调整）

点击牌组旁边的**齿轮图标** -> **选项**：

- **新卡片/天**：初学者建议20张以内，贪多嚼不烂
- **复习上限**：默认100张足够，如果觉得任务太重可调低
- **最大间隔**：默认100年(36500天)`是的你没看错`，通常保持即可
- **搁置相关卡片**：建议勾选，避免同一笔记的多张卡片同时出现

#### 2. 学习步骤自定义

在“**选项**” -> “**新卡片**” -> “**学习阶段**”中：

默认是`1m 10m`（1分钟后第一次复习，10分钟后第二次）。根据内容难度可以调整为：
- 简单词汇：`1m 5m`
- 复杂概念：`5m 20m 60m`
#### 3. 复习节奏调整

在“**复习**”板块：
- **简单间隔**：默认4天，感觉太慢可改为3
- **初始简易度**：默认2.5（不要轻易调整，这是经过科学验证的最佳值）
## ->模板与样式
### 基础->模板
Anki内置了多种模板：
- **基础**：一张正面一张背面
- **基础（含反卡）**：自动生成正向和反向两张卡片
- **填空**：挖空式记忆，如“{{c1::苹果}}是红色的”
### 添加音频和图片
**添加图片：**
- 方法一：直接把图片拖入编辑框
- 方法二：点击编辑栏的图片图标，选择文件
**添加音频：**
- 拖入`.mp3`或`.wav`文件
- 或点击麦克风图标直接录音
学习时音频会自动播放，非常适合语言学习。
### 自定义->模板
浏览卡片 -> 点击“卡片...” -> 找到“样式”框，输入你的css代码。
**注意：不懂得css代码的请不要轻易更改！**
下方是一个示例：

```css
.card {
  font-family: "Microsoft YaHei", "PingFang SC";
  font-size: 28px;
  text-align: center;
  color: #2c3e50;
  background-color: #f8f9fa;
}

.nightMode {
  background-color: #1a1a2e;
  color: #eee;
}
```
### ->模板推荐
Anki基础的->模板十分简洁，功能与拓展性不强。在此推荐一些我个人使用的->模板。
> 文件来源于网络，部分内容难以找到来源。侵权请联系删除。

考研英语：[1 考研英语.apkg](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQlFBQ0FnVUFBeUVHQUFUcVduQ2pBQUlESldvUm5BOTU0TXRVWUlfZ05tbDduRHlKNUJUa0FBSkdKQUFDdmlpUVZNXzdoTlltYjNmaE93USIsImUiOiJhcGtnIiwibiI6IjEg6ICD56CU6Iux6K-tLmFwa2ciLCJtIjoiIiwicyI6NTIyNzg3NjYsInQiOjE3Nzk1Mzg5NjAxMDAsIm1pZCI6ODA1fQ.wzOLiCwp5YZ66t5dGjJqEW0smHRwqYu9VN6nFRAcZYQ.apkg)![考研英语模板截图](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlESzJvUm5jbERjenhLX0tFdEJXWk5QelhPM0xjTkFBS3VFR3NidmlpUVZFTmhxU3luS3RROEFRQURBZ0FEZHdBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTM5Mzg3ODI1LndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjExMjM0MiwidCI6MTc3OTUzOTQwMTc4NSwibWlkIjo4MTF9.tC2jQAej6FOVnv_BIDRTtlIZKnNOiOcIQze5UhNvmrA.webp)
选择题->模板：[CPA.apkg](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQlFBQ0FnVUFBeUVHQUFUcVduQ2pBQUlESjJvUm5MU0hVQjZ4ZmVocWZEelRuZ1Q0ZjZIb0FBSkpKQUFDdmlpUVZEVjRKUUpmTVhQN093USIsImUiOiJhcGtnIiwibiI6IkNQQS5hcGtnIiwibSI6ImFwcGxpY2F0aW9uL29jdGV0LXN0cmVhbSIsInMiOjczNzkxLCJ0IjoxNzc5NTM5MTI0ODA1LCJtaWQiOjgwN30.T2xsyQC_aRjdotuGXSEQ0cbjRGEv_VsfiZ-kv_5Xrok.apkg)![选择题模板截图](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlETFdvUm5mTHVMbnhUYW9tSS16dmRvVDh5blU5VkFBS3dFR3NidmlpUVZDNmpRdFhWYUVWdkFRQURBZ0FEZHdBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTM5NDI5MTg2LndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjk1MTA0LCJ0IjoxNzc5NTM5NDQyODMwLCJtaWQiOjgxM30.hc0mCmZEIfypxs9_KQzToodGh4DrDIAmytKRhsLaXNs.webp)
问答+解析：[Earth Science.apkg](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQlFBQ0FnVUFBeUVHQUFUcVduQ2pBQUlES1dvUm5ZSUhURUlqMG5tTy1feER6bk5pSVRNV0FBSk1KQUFDdmlpUVZFU1FIVlN5N2lidU93USIsImUiOiJhcGtnIiwibiI6IkVhcnRoIFNjaWVuY2UuYXBrZyIsIm0iOiJhcHBsaWNhdGlvbi9vY3RldC1zdHJlYW0iLCJzIjo2NDYwNywidCI6MTc3OTUzOTMzMDk1MSwibWlkIjo4MDl9.dIUT1nHDi9RTe4UwZne8Np8bu9nRvVk1ZCVn5TmLvqo.apkg)![问答解析模板截图](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlETDJvUm5oWkNhVE5reHpkaFRCNW4tVHdXUHowakFBS3hFR3NidmlpUVZBVGRhT2lPRE5TUUFRQURBZ0FEZVFBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTM5NDY1NDAxLndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjI1ODEyLCJ0IjoxNzc5NTM5NDc4NDIyLCJtaWQiOjgxNX0.T2bn3TC_kVt4Isw_OkD6NDVHl4q6lIq3ji3uPR8Ax0c.webp)

## 在线账号与同步
Anki官方的在线账号是[AnkiWeb](https://ankiweb.net/)账号。
### 注册账号
你可以提前在前往[AnkiWeb](https://ankiweb.net/)注册自己的账号。
![AnkiWeb页面](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlETldvUm42ZGg5RmpqRFA3RldIT2tKXzl6OG1kckFBSzZFR3NidmlpUVZGN0JoSTB1OE12QkFRQURBZ0FEZVFBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTM5ODY2NTMzLndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjQwOTcyLCJ0IjoxNzc5NTM5ODc5NTIzLCJtaWQiOjgyMX0.0RZuuYW_So8_Ni3FgyghMBPffgdRVkMzxelI7oRUuFc.webp)
1. 点击右上角“**Sign Up**”按钮前往注册![AnkiWeb注册](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlETTJvUm4yX3pnV2xpUGhHbkh2TEp4T2NHbUY0cUFBSzVFR3NidmlpUVZGSzM0a2ZydXhvZ0FRQURBZ0FEZVFBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTM5ODEwNTU3LndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjIxMzY0LCJ0IjoxNzc5NTM5ODIzNjM4LCJtaWQiOjgxOX0.RGDJK1XTBFDAu_yNXBsv6SkkdqCe6m5gf_Oc-_EXixI.webp)
2. 通过邮箱注册。
3. 点击注册会跳转到“**条款与条件**”页面，下滑到最底部点击继续即可。
4. 通过注册邮箱收到的链接验证邮箱。![AnkiWeb验证邮箱](https://imgdb.yunaitang.top/file/tgs_eyJ2IjoxLCJmIjoiQWdBQ0FnVUFBeUVHQUFUcVduQ2pBQUlETjJvUm9EQVV2YmZNUHZSN3NxVnU1eGtrakl1X0FBSzdFR3NidmlpUVZHVWNZVUpPaDlGekFRQURBZ0FEZVFBRE93USIsImUiOiJ3ZWJwIiwibiI6ImNsaXBib2FyZF8xNzc5NTQwMDA0MTIzLndlYnAiLCJtIjoiaW1hZ2Uvd2VicCIsInMiOjI5NjAwLCJ0IjoxNzc5NTQwMDE3MTk0LCJtaWQiOjgyM30.qP7i6FHucgvzhEcD8TW_zjmiQ1j6hZ2kDsNBldUAP9E.webp)
> 注意：非常见邮箱域名可能无法接受验证邮件，更换邮件即可。
### 登录
点击菜单栏“**同步**”，在弹出页面输入账号密码即可。

## 常见问题解答

**Q：Anki和背单词App（如百词斩、不背单词）有什么区别？**
A：Anki是通用工具，不限于背单词。它让你自己掌控学习内容，算法也更科学。百词斩等App帮你规划好了路径，但自由度低。

**Q：需要付费吗？**
A：Windows/macOS/Linux/Android全部免费，iOS官方App需付费。AnkiWeb也免费。

**Q：我的数据安全吗？**
A：Anki是本地软件，你的所有卡片都存在电脑上。AnkiWeb同步过程是通过HTTPS加密的，可以放心使用。

**Q：卡片太多会不会背不完？**
A：这正是间隔重复的魅力——系统会自动控制每天的复习量。只要你坚持，就不会出现“欠债”现象。

## 写在最后

Anki不是灵丹妙药，它只是一个工具。再好的工具，不拿起使用也是摆设。很多人的误区是花大量时间研究配置、美化模板，却很少真正去学习卡片里的内容。

我的建议是：**先上手，再优化**。用最简单的卡片开始，每天坚持，一周后你会惊讶于自己的进步，一个月后你会感谢现在的决定。

现在就打开电脑或手机，创建你的第一张卡片吧。记住：
> A year from now, you’ll wish you had started today.

---

*希望这篇指南对你有帮助。如果你在使用的过程中遇到问题，欢迎留言交流。让我们一起，用Anki把知识真正变成自己的。*