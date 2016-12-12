# Awesome Express

这个仓库主要是收集 `Express` 好用的中间件、新闻资讯、网站等，这是我在基于`Express`开发web应用过程中搜集到的一些插件和看到的一些好的内容。

## 目录

- [官方网站](#官方网站)
- [中文文档](#中文文档)
- [中间件](#中间件)
- [工具](#工具)
- [例子](#例子)
- [文章](#文章)

## 官方网站

- [Official website](http://expressjs.com) - Express官方网站
- [GitHub repository](https://github.com/expressjs/express) - Express GitHub仓库

## 中文文档

- [Express](http://expressjs.jser.us/) - 中文文档( node.js Web应用框架 )
- [Express](http://www.expressjs.com.cn/) - 基于 Node.js 平台的 web 应用开发框架

## 中间件

- [Multer](https://github.com/expressjs/multer) - 官方推荐的文件上传中间件。
- [body-parser](https://github.com/expressjs/body-parser) - 转换body内容的中间件，用于处理 JSON, Raw, Text 和 URL 编码的数据。
- <del>[connect-multiparty](https://github.com/expressjs/connect-multiparty)</del> - 官方的文件上传中间件(不推荐使用)
- [cors](https://github.com/expressjs/cors) - 跨域资源共享。
    - [HTTP访问控制(CORS)](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Access_control_CORS)
- [morgan](https://github.com/expressjs/morgan) - HTTP请求日志中间件。
- [cluster](https://nodejs.org/api/cluster.html) - Nodejs应用生成多个进程，并行运行。
- [compression](https://github.com/expressjs/compression) - 中间件负责压缩响应的json数据和静态文件为GZIP格式，Nginx做此类事情效率更高。
- [helmet](https://github.com/helmetjs/helmet) - 最大程度的确保我们 API 的安全性，应用程序应对多种类型的攻击。
部分 Express 中间件组件：
- [body-parser](https://github.com/expressjs/body-parser) - 中间件用来解析http请求体，先前为 express.bodyParser、json 和 urlencoded。另请参阅：
  - [body](https://github.com/raynos/body)
  - [co-body](https://github.com/visionmedia/co-body)
  - [raw-body](https://github.com/stream-utils/raw-body)
- [compression](https://github.com/expressjs/compression) - 压缩和处理静态内容。
- [connect-image-optimus](https://github.com/msemenistyi/connect-image-optimus)  用于提供最优映像的 Connect/Express 中间件模块。如有可能，可将映像切换为 .webp 或 .jxr。
- [connect-timeout](https://github.com/expressjs/timeout) - 先前为 express.timeout。
- [cookie-parser](https://github.com/expressjs/cookie-parser) - 先前为 express.cookieParser。
- [cookie-session](https://github.com/expressjs/cookie-session) - 先前为 express.cookieSession。
- [csurf](https://github.com/expressjs/csurf) - 先前为 express.csrf。
- [errorhandler](https://github.com/expressjs/errorhandler) - 先前为 express.errorHandler。
- [express-debug](https://github.com/devoidfury/express-debug) - 不引人注目的开发工具，用于向应用程序添加一个选项卡，其中包含有关模板变量（本地）、当前会话、有用请求数据等方面的信息。
- [express-partial-response](https://github.com/nemtsov/express-partial-response) - Express 中间件模块，使用 Google API 的 Partial Response，根据 fields 查询字符串过滤掉 JSON 响应的各个部分。
- [express-session](https://github.com/expressjs/session) - 先前为 express.session。
- [express-simple-cdn](https://github.com/jamiesteven/express-simple-cdn) - Express 中间件模块，将 CDN 用于静态资产，具有多主机支持（例如:cdn1.host.com、cdn2.host.com）。
- [express-slash](https://github.com/ericf/express-slash) - Express 中间件模块，适用于对末尾斜杠有很严格要求的人员。
- [express-stormpath](https://github.com/stormpath/stormpath-express) - 实现用户存储、认证、授权、SSO 和数据安全性的 Express 中间件模块。
- [express-uncapitalize](https://github.com/jamiesteven/express-uncapitalize) - 中间件模块，用于将包含大写字母的 HTTP 请求转换为标准的小写形式。
- [express-http-proxy](https://github.com/villadora/express-http-proxy) - 解决跨域问题。
- [helmet](https://github.com/helmetjs/helmet) - 一个模块，用于通过设置各种 HTTP 头来帮助保护应用程序。
- [join-io](https://github.com/coderaiser/join-io) - 一个模块，用于实时联接文件以减少请求数目。
- [method-override](https://github.com/expressjs/method-override) - 先前为 express.methodOverride。
- [morgan](https://github.com/expressjs/morgan) - 先前为 logger。
- [passport](https://github.com/jaredhanson/passport) - 用于认证的 Express 中间件模块。
- [response-time](https://github.com/expressjs/response-time) - 先前为 express.responseTime。
- [serve-favicon](https://github.com/expressjs/serve-favicon) - 先前为 express.favicon。
- [serve-index](https://github.com/expressjs/serve-index) - 先前为 express.directory。
- [serve-static](https://github.com/expressjs/serve-static) - 用于提供静态内容的模块。
- [static-expiry](https://github.com/paulwalker/connect-static-expiry) - 静态资产的指纹式 URL 或高速缓存头，包含对一个或多个外部域的支持。
- [vhost](https://github.com/expressjs/vhost) - 先前为 express.vhost。
- [view-helpers](https://github.com/madhums/node-view-helpers) - Express 中间件模块，用于向视图提供常见助手方法。
- [sriracha-admin](https://github.com/hdngr/siracha) - Express 中间件模块，为 Mongoose 动态生成管理站点。
- [express-jwt](https://github.com/auth0/express-jwt) - 产生唯一的基于用户信息.令牌

## 工具

_Node工具不依赖Express框架_

- [generator-express](https://github.com/petecoop/generator-express) - 命令行工具Yeoman 生成 Express 应用程序
- [express-generator](https://github.com/expressjs/generator) - 命令行工具 Express 应用程序生成器
- [Express workshop](https://github.com/azat-co/expressworks) - Express.js 基础课程，一个基于[workshopper](https://github.com/workshopper/workshopper)命令行学习工具。
- [cross-env](https://www.npmjs.com/package/cross-env) - 处理跨平台环境变量设置的插件 
- [node-images](https://github.com/zhangyuanwei/node-images) - 轻量级跨平台图像编解码库。
- [lwip](https://github.com/EyalAr/lwip) - 对于Nodejs轻量级的图像处理器。

## 文章

_关于Express教程、新闻等文章搜集_

- [阮一峰 - Express框架](http://javascript.ruanyifeng.com/nodejs/express.html)
- [Express - 简单介绍 Express·简单心理技术团队](https://jiandanxinli.github.io/2016-08-09.html)
- [教你从零开始搭建一款前端脚手架工具](https://segmentfault.com/a/1190000006190814)
- [使用 Express 和 waterline 创建简单 Restful API](https://segmentfault.com/a/1190000004996659)
- [构建 Express Api 五个有用的中间件](https://fe.ele.me/gou-jian-express-api-wu-ge-you-yong-de-zhong-jian-jian/)
- [10个Node.js开发者最易犯的错误](https://zhuanlan.zhihu.com/p/19944110)
- [chyingp - Nodejs学习笔记](https://github.com/chyingp/nodejs-learning-guide)
- [Express结合Passport实现登陆认证](http://blog.fens.me/nodejs-express-passport/)
- [Passport现实社交网络OAuth登陆](http://blog.fens.me/nodejs-oauth-passport/)
- [webpack+vue+vux+express+lowdb实践](https://segmentfault.com/a/1190000006998791)
- [基于 Express+Gulp+BrowserSync 搭建高性能的前端开发环境](https://www.kisnows.com/2015/11/02/dev-environment-Express-Gulp-BrowserSync/)
- [Express深入解读](http://www.html-js.com/article/Express-indepth-understanding-of-learning-notes%203213)
- 关于 Express 4.8.x 的相关基础文档
  - [概述](http://www.html-js.cn/details/E1LuMa5ee.html)
  - [安装和使用](http://www.html-js.cn/details/NJ0nXpqxg.html)
  - [编写第一个Express应用](http://www.html-js.cn/details/EyCvEpqxe.html)
  - [配置应用程序](http://www.html-js.cn/details/NkQMr65gl.html)
  - [路由器、响应与渲染](http://www.html-js.cn/details/E1zH8p9gg.html)
  - [路由详解](http://www.html-js.cn/details/416QvT5le.html)
  - [Request 对象实例讲解](http://www.html-js.cn/details/Ey2Cwpcll.html)
  - [Response 响应对象](http://www.html-js.cn/details/N1GMY6clx.html)
  - [路由权限控制技巧](http://www.html-js.cn/details/N1LYtaqgl.html)
  - [资源分离技巧](http://www.html-js.cn/details/VyP-cacgx.html)
  - [Express 中间件原理](http://www.html-js.cn/details/Vy1t969gx.html)
  - [必备中间件的使用](http://www.html-js.cn/details/Ek6Zja9xg.html)
  - [EJS 模版引擎](http://www.html-js.cn/details/E1hKsp9eg.html)
  - [JADE模版引擎](http://www.html-js.cn/details/4y8Lnp5eg.html)
  - [mongoose的增删改](http://www.html-js.cn/details/EyE4TTcex.html)
  - [mongoose 查询操作](http://www.html-js.cn/details/EJJnTT9xg.html)
- [socket.io 集成到express4通过路由访问](http://www.html-js.com/article/3285)
- [用 Docker 搭建 Node Express 应用](http://docs-static.daocloud.io/docker-frontend/docker-node-express)
- [基于 PhantomJS + Node + Express + VueJS 1.x 的服务端渲染实践](https://segmentfault.com/a/1190000006695341)
- [Node 进阶：express 默认日志组件 morgan 从入门使用到源码剖析](https://gold.xitu.io/post/584e00490ce463005c60b032?utm_source=gold_browser_extension)

## 例子

_Express的Demo例子搜集_

- [reactjs官方例子express-react-views](https://github.com/reactjs/express-react-views)
- [V-Tom - 一个基于Node.js,Express,Mongodb,vue的博客](https://github.com/hstarorg/rest-express)
- [利用express简化rest api开发](https://github.com/hstarorg/rest-express)
- [前端基于webpack+vue+vux，后端基于express+lowdb](https://github.com/lianer/meal-ticket)
- [Express + MongoDB + Vue.js 搭建的 Web 应用](https://github.com/WecanStudio/wecanstudio-site)
- [简单的 Vue2 + Webpack2 + Express + 热更新工程模板](https://github.com/hilongjw/vue-express-hot-simple)
- [Express 4.x + MongoDB 实现CRUD](https://github.com/liuxuanqiang/Express_MongoDb_Demo)
- [使用 Express + MongoDB 搭建多人博客](https://github.com/nswbmw/N-blog)
- [使用 Nodejs (Express) 编写的团体订餐程序](https://github.com/willerce/canku)
- [个人博客系统, 基于RESTful架构,Express, MongoDB, Redis, Token Auth, 七牛云存储](https://github.com/jackhutu/jackblog-api-express)
- [Express搭建微信公共账号服务](https://github.com/node-weixin/node-weixin-express)
- [简单的 Vue2 + Webpack2  + Express + 热更新工程模板](https://github.com/hilongjw/vue-ssr-hmr-template)
- [Node + Express + VueJS 1.x 的服务端渲染实践](https://github.com/jrainlau/vue1.x-ssr-demo)
- [一个简单的例子使用Express+mongoose+passport登录验证](https://github.com/madhums/node-express-mongoose-demo)