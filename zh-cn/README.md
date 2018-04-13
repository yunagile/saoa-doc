# 介绍

**weex-saoa 是基于 **[**weex**](https://weex-project.io/cn/)** 封装面向前端的 vue 写法的解决方案**

**由于 app 开发的特殊性，weex-saoa 则更偏重关心于整个 app 项目，由云南软捷科技有限公司app技术团队研发**

# 开发之前你需要知道

* 可简单了解node.js的基本原理
* 掌握git的使用，现在我们已经不使用svn进行代码的托管
* 一定要熟练使用 vue 开发
* 一定要详细阅读 weex 的文档，尤其是与 web 环境，vue 开发差异的部分。
* 在开发客户端应用中，会有遇到无数的环境问题，程序问题，代码问题，绝大多数问题都可以在网上查到对应解决方案，在提出问题的时候，还请先自行尝试解决
* 适当**了解**客户端开发打包流程\(android,ios\)

# 必备知识

开发之前您需要学习 weex 知识，并且能熟练使用 vue 开发，文档地址如下。

* [weex](http://weex.apache.org/cn/guide/)
* [vue](https://cn.vuejs.org/v2/guide/)

# 支持性

> 跟随着 weex 的支持性
>
> `但目前我们并不支持开发代码兼容 web 端，与我们当前的业务来看我们暂不需要web端`

* Android 4.1 \(API 16\)
* iOS 8.0+ 
* WebKit 534.30+ 

# weex-saoa 优点

weex-saoa 提供了:

* 简化环境搭建过程。
* 一套代码编译成 ios，android 两端原生应用。
* 封装了大量 weex module，让前端开发方便进行原生的操作。
* 提供了丰富的UI组件\(saui\)\(后期将提供UI组件的demo\)
* 完美与P9平台结合
* 支持真机和模拟器通过 `npm run saoa` 来实时调试，程序报错均会有报错日志弹窗提示。
* 后期将把应用于框架分离\(轻应用,整体实现思路待研究\)

后期完善后可通过脚手架：

* 直接生成开发最新模板。
* 启动服务进行实时开发效果查看和 debug 调试。
* 更新开发平台所需 weex-saoa 依赖。
* 支持生成全量包，增量包，并内置与更新服务器交互逻辑。
* 支持同步更新模板内容。

支持市面上流行的组件库：

* [weex-ui](https://github.com/alibaba/weex-ui) \( 阿里出品，推荐使用 \)
* [bui](https://github.com/bingo-oss/bui-weex)
* sui \(我们自己也将单独提出UI组件\)

# weex-saoa 不足

> 开发中也有很多限制，需要开发者自行斟酌。

* 尽管 weex 支持编译三端，**但 weex-saoa 目前不支持浏览器端**，目前只会专注于原生。
* 暂时不能自动使用 weex 市场，需要有原生开发能力的人支持，不过当下以集成大部分常用的Native插件。

# 原理视图

![工作原理](http://on-img.com/chart_image/59c5d743e4b0d34a18d69580.png)  
[大图地址](http://on-img.com/chart_image/59c5d743e4b0d34a18d69580.png)

# 社区贡献

* [eros 网易严选](https://github.com/bmfe/eros-yanxuan-demo-v2)
* [weex-eros-book 书籍阅读 app](https://github.com/wennjie/weex-book)
* [lygtq-eros-publish 服务器增量发布逻辑](https://github.com/hodgevk/lygtq-eros-publish)
* [eros-node-server 服务器增量发布逻辑](https://github.com/shawn-tangsc/eros-node-server)

# License

[MIT](https://opensource.org/licenses/MIT)

Copyright \(c\) 2013-2018, 云南软捷科技有限公司

