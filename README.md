# Newchat

* 这是一个 Vue 仿微信客户端
* 前端技术栈: vue 2.0、vue-cli、vuex、vue-router、webpack 2.x、pug、sass、babel等；
* 后端技术栈：Node.js、Express、express-session、WebSocket(ws)、MongoDB、mongoose、ES6等。


### Intro
* 学习vue有段时间了，但是公司并不使用vue，为了练习vue大大小小也做过几个个人项目，模仿过微信的pc版，由于sockit.io不能刷新，导致在pc端体验并不好，一刷新就要重新登陆才可以发消息给好友。
* 在公司用的多的就是ionic，一个专注于移动端webapp的偏UI框架，里面也用到了angularjs框架。打包用的是cordova，后面就想到了用vue做一个微信客户端，用cordova打包。
* 目前手机的硬件已经很好了，基本cordova打包的app体验还是很流畅的，配合vue的单页面应用基本可以无差原生app了。
* 前端部分使用 vue-cli 构建、打包, 配合 vue全家桶（vue、vuex、vue-router）进行编码
* 使用 axios 进行资源请求
* 后台使用 Node.js的express架构开发，目前接口不多，不过会持续更新。


### Tips
* 无法注册或者获取数据，因为我配置的后台接口是我的服务器，你可以自己下载后台代码，部署到自己服务器，不过一般情况是可以访问的。
* 如果你要自己搭建服务器，你除了要安装node相关的依赖外，你还需要安装MongoDB数据库


- 高仿微信客户端的界面设计风格，具有push、pop、modal、dismiss等转场动画；
- 注册、登陆和注销功能，可记住登录状态，避免多次登录；
- 聊天室功能，所有在线用户可进行群聊；
- 添加好友，目前必须保证对方在线才能正确添加；
- 用户私聊，目前必须保证对方在线方可正常聊天；
- 目前只支持纯文本聊天。

