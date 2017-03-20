![zhiliao](http://zhiliao-10068775.cos.myqcloud.com/%E7%9F%A5%E4%BA%86.png)
# zhiliao_one 知了
跨平台移动通知应用 - 服务器端
## 简介
知了是一个简单方便的跨平台移动通知应用系统, 支持软件通知, 邮箱通知, 短信通知三种通知方式.

## 技术概述
* 前后端分离开发, 后端使用web api架构, 前端使用mvvm框架vue.js
* web端: vue.js (版本:2.x)
* 移动端: weex (版本:1.x)
* 服务器端: asp.net core webpai (版本:1.1)
* 数据库: mysql
* 版本管理: git
* 代码仓库: [github](https://github.com) 、[coding](https://coding.net/)

## 技术栈

### 后端:
* 跨域方案: [CORS]()
* 短信服务: [阿里大于](https://www.alidayu.com/)
* 邮件发送: [MailKit](https://github.com/jstedfast/MailKit)
* 对象存储: [腾讯云cos](https://console.qcloud.com/cos)
* 权限验证: [JWT](https://jwt.io/)

### 前端
* 开发框架: [Vue.js](https://vuefe.cn/v2/guide/)
* UI框架爱: [Muse UI](https://museui.github.io)、[Element UI](http://element.eleme.io/#/zh-CN/component/installation)
* 路由: [Vue-Router](https://router.vuejs.org/zh-cn/)
* 状态管理: [Vuex](https://vuex.vuejs.org/zh-cn/)
* HTTP 请求: [axios](https://github.com/mzabriskie/axios)

### 移动端
* 开发框架: [Weex](https://weex-project.io/cn/)

## 开发进度
-  基本
    - [x] 登录,注册
    - [x] 权限验证
    - [ ] 邮件,短信集成
    - [ ] 找回密码 `要么不做, 要么做短信验证码后修改`
    
- 用户管理
    - [x] 用户头像修改
    - [x] 用户信息修改
    
- 群管理
    - [x] 创建群
    - [x] 加入群
    - [x] 群列表
    - [x] 群用户列表
    
- 通知管理
    - [x] 创建通知
    - [x] 接收通知列表
    - [x] 已发送通知列表
    - [ ] 对未回复用户进行短信提醒
    - [ ] 接收通知【回复】
    
- 其他
    - [x] cos文件上传
    - [x] vuex状态管理
    - [x] storage存储
    - [ ] 移动端:worried::worried::worried:
