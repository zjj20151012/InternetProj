# Internet大作业 -- 技术沙龙

>  本大作业基于Vue 2.0,采用ajax进行网络请求，实现了瀑布流的效果
> 
>  朱佳杰  计算机科学与技术  140601175

###首先

***
>*  感谢[gank.io](http://gank.io/)提供的api接口

### 项目技术架构
***
*  vue-cli
*  vue 2.0
*  vue-resource
*  vue-router
*  vuex
*  vue-awesome-swiper
*  vue-infinite-scroll
*  stylus
*  webpack

### 运行前的准备
安装 vue-cli

```
npm install -g vue-cli

```
安装 vue-cli eslint

```
npm install -g eslint
```

安装依赖 friendly-errors-webpack-plugin

```
npm install friendly-errors-webpack-plugin --save-dev
```

### 运行
***
项目地址：（`git clone`）

```
git clone https://github.com/zjj20151012/InternetProj.git
```

通过`npm`安装本地服务第三方依赖模块(需要已安装[Node.js](https://nodejs.org/))

```
npm install
```
启动服务(http://localhost:9090) 默认侦听9090端口

```
npm run dev
```

###目录结构
***
<pre>
├── build              // 构建服务和webpack配置
├── config             // 项目不同环境的配置
├── dist               // 项目build目录
├── index.html         // 项目入口文件
├── package.json       // 项目配置文件
├── src                // 生产目录
│   ├── assets         // 图片资源
│   ├── common         // 公共的css js 资源
│   ├── components     // 各种组件
│   ├── App.vue        // 主页面 
│   ├── vuex           // vuex状态管理器
│   ├── router.js      // 路由配置器
│   └── main.js        // Webpack 预编译入口
</pre>

###实现的功能
***
* 瀑布流布局
* 无限滚动
* 侧边导航
* 图片懒加载
* 左右滑动切换
* 等等

