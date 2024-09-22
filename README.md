# 全目录

[更多系统、论文，供君选择 ~~>](https://www.yuque.com/wisebit/blog)

# 90.EnglishLearningManagementSystem

<p>群: 983063232(入群获取sql文件)</p>
<p>QQ: 206157502(加好友获取sql文件)</p>

<p><h1 align="center">90.学习英语管理系统</h1></p>

<p align="center">
	<img src="https://img.shields.io/badge/jdk-1.8-orange.svg"/>
    <img src="https://img.shields.io/badge/springboot-2.x-blue.svg"/>
    <img src="https://img.shields.io/badge/maven-3.x-blue.svg"/>
    <img src="https://img.shields.io/badge/html-5.x-lightgrey.svg"/>
</p>

# 简介

> 本代码来源于网络,仅供学习参考使用,请入群(983063232)后联系群主索要sql文件!
>
> 提供1.远程部署/2.修改代码/3.设计文档指导/4.框架代码讲解等服务
> 
> 用户登录地址: http://localhost:8080/
> 
> 用户名: 9048595701@qq.com   密码: 123456
> 
> 管理员登录地址: http://localhost:8080/toAdmin
> 
> 用户名: 904859570@qq.com   密码: 123456





**本项目用到的技术和框架**<br>
1.项目构建：Maven<br>
2.web框架：Springboot<br>
3.数据库ORM：Mybatis<br>
4.数据库：MySQL<br>
5.前端框架：BootStrap<br>
6.模板引擎：Thymeleaf<br>
7.文章展示：Editor.md<br>
# 环境

- <b>IntelliJ IDEA 2009.3</b>

- <b>Mysql 5.7.26</b>

- <b>Maven</b>

- <b>JDK 1.8</b>

## 功能介绍
本学习系统分为注册登录模块，公告展示模块，背单词模块，听力练习模块，阅读书籍模块，每日一句模块，个人中心模块，以及后台管理模块。
#### 登录注册模块
- 登录功能
    - 验证信息：输入邮箱与密码，如果正确则进入网站首页，如果错误则提示错误信息
    - 登录拦截：在进入网站页面之前，系统会检测用户是否带有Session，如果没有则没有权限进入其他页面
- 注册功能
    - 新用户可以输入邮箱与密码进行注册，提交信息后返回登录页面提示去邮箱激活
    - 系统通过QQ邮箱服务器发送给新用户，新用户点击收到激活网站进行注册
#### 公告展示模块
- 网站首页会展示管理员发布的公告
- 用户可以查看发布的历史公告

#### 每日一句模块
- 网站首页会随机展示句子与翻译
- 图片展示使用了必应的每日一图api

#### 背单词模块
- 选择单词
    - 用户可以根据单词的等级进行学习
- 学习单词
    - 会从未学习过的单词之中随机抽取相应等级的单词
    - 页面会展示该单词是否被收藏，以及当前的学习进度
    - 用户可以点击收藏，认识，不认识，下一个等按钮进行学习

#### 听力练习模块
- 用户可以选择哪些年份的真题与等级
- 用户可以播放听力，以及查看真题

#### 阅读书籍模块
- 用户可以选择喜欢的书籍进行阅读
#### 个人中心模块
- 用户可以自行修改自己的名字，邮箱以及密码

#### 后台管理模块
- 管理员可以进入后台，对系统的用户，单词，书籍，公告进行管理

## 缩略图

![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/898f339f-0415-422a-a986-930c9bb0dd08.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/096177bd-d96e-4d97-8571-fc4ea841b732.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/c84e94a7-2fef-45fd-b855-0b136325e737.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/43954126-82b2-4d45-8521-b71d52c70476.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/276ee9cb-fd2e-42bf-ac93-226ff03b1c62.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/9b49385a-7ea6-48f8-b5e0-158869c8ff52.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/cd55e9b2-a16b-4f79-9248-e6fa76637a1e.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/1f11947d-dc3a-469c-8880-fbf1687641eb.png)



