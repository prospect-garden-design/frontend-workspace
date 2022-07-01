# introduction
- common
  - https://hub.fastgit.xyz/prospect-garden-design/frontend-workspace/blob/main/log-yaoo/intro.md
  - https://github.com/prospect-garden-design/frontend-workspace
# 0701-视频预习 + github上传下载
- github上传下载
  - 先把ssh-key放到了github设置里面
  - 安装 依赖 git 工具包
  - 在terminal/终端/命令行实现上传下载

- 1. 将本地文件夹和github repo关联，一个repo只要做一次
```shell
# git仓库初始化
git init

# 将本地文件夹和远程repo建立关联
git remote add origin  复制的链接

```
- 2. 上传下载

```shell

# 每次上传前，先添加文件，再写描述
git add .
git ci -m'chore: commit'
git ci -m'add: file'

# 第一次上传 

git push -u origin main

# 以后上传 
git push

# 以后
git pull
```

- repository类似文件夹，类似网盘

- terminal 终端 命令行 ，意思相同

- github相关的资料周六我带你做一遍比看文档有效多了，你不用看了，有问题直接搜索即可；
- 今天你先看这个文档 0702的内容，然后主要看第一个视频，看5-10个即可，，，记得在笔记本电脑上做些笔记
# 0630-environment-dev

## good habit

- 将今天学到的一些有意思的东西像这个文档一样记一下，以后每天都这样
  - 不需要很长，只记自己觉得有意思的、或重要的、或容易忘的小点
  - 每个小点尽量不超过一行文字
  - 每行以短横开头，写成类似这样  `- mac可以三指拖拽`; 
  - 写的时候像这篇文档一样，有意识地多用简单的英文单词

## 电脑环境配置与进一步熟悉

- 调整电脑头像、常用网站头像，头像统一用 512x512 px像素大小
- 电脑重要设置项调整
  - 配置时，选择地点默认选 美国 united states，问题更少
  - Trackpad 触摸板，每个勾选都了解下意思，自己打些勾配置成自己喜欢的手势
  - 键盘，勾选使用F1～F12做为功能键
- 熟悉spotlight，快速搜索电脑文件
- 常用操作使用键盘，而不是鼠标
  - 文件 复制、粘贴、移动
  - 截图部分
  - 浏览器切换标签页
- 自己觉得操作不习惯的，或看到其他小技巧，就在知乎和google搜索一下

## github熟悉

- 在知乎搜索 github教程 ，开始了解工作网站github
  - 尝试搜索 github desktop 教程
  - 自己在github上创建仓库，尝试一下，跟着教程做一做

- markdown (暂时不看)
# 0629-environment
- 待安装软件
  - microsoft edge 浏览器

- 常用网站 (国内 > 国外)
  - 百度
    - google
  - 腾讯
    - facebook
  - 阿里
    - amazon
  - https://gitee.com
    - https://github.com
  - zhihu.com
    - https://stackoverflow.com

- 电脑系统
  - 操作系统 windows，MacOS, Linux(ubuntu/debian/centos)
# 0629-熟悉使用MacBook笔记本电脑

## prepare-sign-up

- https://www.icloud.com/#
- https://outlook.live.com/mail/
- https://www.zhihu.com/

## install

- 腾讯会议
- 百度网盘/阿里云盘
- xcode

## 熟悉使用macbook笔记本电脑的小技巧和快捷键

- Mac使用技巧大整合：基础篇+进阶篇
  - https://zhuanlan.zhihu.com/p/89987302

- 如何高效记住 Mac 的快捷键？
  - https://www.zhihu.com/question/24757023

> 就看这两篇，有什么不清楚的，你自己在 https://www.zhihu.com/ 网站搜索，你需要注册一个知乎账号

- 使用Mac的100个小技巧 (可不看，只需了解下留个印象)
  - https://www.bilibili.com/video/BV1Xc411h7ve
# 0702-前端第一课

## 职业方向

## 日常习惯

- 对于不了解的东西
  - wikipedia为主，百度百科为辅
  - mozilla-mdn为主，书籍、博客blog为辅

## 什么是开发

## 开发工作流程

- github 介绍
  - star
  - fork

## 开发小计划

- design system 设计系统目录
- 统计局数据与图表目录
- markdown 预览

## 参考资料 references

- 原则
  - 看视频并不能让你找到工作，目的是通过练习打好基础
  - 先动手做东西，再去寻找原理

- 前端基础视频
  - 黑马程序员pink老师前端入门教程 HTML5+CSS3+移动端
    - https://www.bilibili.com/video/BV14J4114768
    - 移动端从 P398 开始
    - 不需要看bootstrap部分
  - 黑马pink js+echarts
    - https://www.bilibili.com/video/BV1Sy4y1C7ha
  - 尚硅谷Web前端零基础入门 HTML5+CSS3
    - https://www.bilibili.com/video/BV1XJ411X7Ud
  - 尚硅谷JavaScript
    - https://www.bilibili.com/video/BV1YW411T7GX

- 前端高级视频
  - 黑马web前后端交互 Ajax
    - https://www.bilibili.com/video/BV1ji4y1876Y
  - 尚硅谷React教程
    - https://www.bilibili.com/video/BV1wy4y1D7JT
  - 尚硅谷Vue2.0+Vue3.0全套教程
    - https://www.bilibili.com/video/BV1Zy4y1K7SH

- 千古前端图文教程，超详细的 Web 前端入门到进阶学习笔记。
  - https://github.com/qianguyihao/Web
  - https://web.qianguyihao.com/
  - 看文档效率虽然快，但是很枯燥，不适合小白入门，入门还是要看视频

- learn to code
  - https://www.freecodecamp.org/learn/2022/responsive-web-design/
