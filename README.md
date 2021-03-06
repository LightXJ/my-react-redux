# 使用了网上React 脚手架 

### 链接地址：https://npm.runkit.com/generator-z-react-cli

## webpack Feature

   - 可以解析JSX语法
   - 可以解析ES6语法新特性
   - 支持LESS、SCSS预处理器
   - 编译完成自动打开浏览器
   - 单独分离CSS样式文件
   - 支持文件MD5戳，解决文件缓存问题
   - 支持图片、图标字体等资源的编译
   - 支持浏览器源码调试
   - 实现组件级热更新
   - 实现代码的热替换，浏览器实时刷新查看效果
   - 区分开发环境和生产环境
   - 分离业务功能代码和公共依赖代码  
   
    
##  目录结构
```
  z-react-cli
  |-- index.html // 启动页(主页)
  |-- build //构建目录，遵循发布系统规范
  |    |-- index.html   //静态页面
  |    |-- static       //资源文件发布到cdn,或发布到服务器  
  |
  |-- src                     //源码目录
  |    |--component           // 组件
  |    |      |-- common      //公共组件
  |    |      |-- temp        //父组件
  |    |--Config              //工具方法
  |    |--Image               //图片资源
  |    |--Redux               // react-redux 数据状态管理
  |    |      |-- action.jsx  // 派发数据的 action
  |    |      |-- reducer.jsx //用于处理 action 的 reducer
  |    |      |-- store.jsx   //数据管理器
  |    |-- Router           //路由
  |    |-- Style            //样式
  |    |-- template         //编译html模板
  |    |-- App.jsx          //js 入口文件
  |-- static                // 源码静态资源(公共资源)
  |
  |-- webpack.config.hot       // 本地热编译
  |-- webpack.config.buildt    // 编译发布测试环境
  |-- webpack.config.online    // 编译发布线上环境
 
```
   
 