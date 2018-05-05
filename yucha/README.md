# 基于vue.js写的webapp [线上访问地址](http://yucha.3keji.com/)


### 安装

项目地址：（`git clone`）

```shell
git clone https://github.com/q-qin/github.git
```

通过`npm`安装本地服务第三方依赖模块(需要已安装[Node.js](https://nodejs.org/))

```
npm install
```

启动服务(http://localhost:8008)

```
npm run dev
```

发布代码
```
npm run build
```

### 开发

### 目录结构
<pre>
.
├── README.md           
├── build              // 构建服务和webpack配置
├── config             // 项目不同环境的配置
├── dist               // 项目build目录
├── index.html         // 项目入口文件
├── package.json       // 项目配置文件
├── src                // 生产目录
│   ├── components     // 各种组件
│   ├── config         // 配置文件
│   ├── images         // 图片资源
│   ├── page           // 各种页面
│   ├── router         // 页面路由
│   ├── statistics     // 统计
│   ├── store          // vuex状态管理器
│   ├── style          // css 资源
│   ├── filters.js     // 各种过滤器
│   └── main.js        // Webpack 预编译入口
</pre>

