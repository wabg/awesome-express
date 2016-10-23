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
- [Express workshop](https://github.com/azat-co/expressworks) - Express.js 基础课程，一个基于workshopper命令行学习工具。
- [cross-env](https://www.npmjs.com/package/cross-env) - 处理跨平台环境变量设置的插件 
- [node-images](https://github.com/zhangyuanwei/node-images) - 轻量级跨平台图像编解码库。
- [lwip](https://github.com/EyalAr/lwip) - 对于Nodejs轻量级的图像处理器。

## 文章

_关于Express教程、新闻等文章搜集_

- [Express - 简单介绍 Express·简单心理技术团队](https://jiandanxinli.github.io/2016-08-09.html)
- [教你从零开始搭建一款前端脚手架工具](https://segmentfault.com/a/1190000006190814)
- [使用 Express 和 waterline 创建简单 Restful API](https://segmentfault.com/a/1190000004996659)
- [构建 Express Api 五个有用的中间件](https://fe.ele.me/gou-jian-express-api-wu-ge-you-yong-de-zhong-jian-jian/)

## 例子
_Express的Demo例子搜集_

- [Express + MongoDB + Vue.js 搭建的 Web 应用](https://github.com/WecanStudio/wecanstudio-site)
- [简单的 Vue2 + Webpack2 + Express + 热更新工程模板](https://github.com/hilongjw/vue-express-hot-simple)
- [Express 4.x + MongoDB 实现CRUD](https://github.com/liuxuanqiang/Express_MongoDb_Demo)
- [使用 Express + MongoDB 搭建多人博客](https://github.com/nswbmw/N-blog)
- [使用 Nodejs (Express) 编写的团体订餐程序](https://github.com/willerce/canku)
- [个人博客系统, 基于RESTful架构,Express, MongoDB, Redis, Token Auth, 七牛云存储](https://github.com/jackhutu/jackblog-api-express)
- [微信公共账号服务](https://github.com/node-weixin/node-weixin-express)