# React Boilerplate 依赖包

## 前端业务形态

- PC Web 端
- PC Native 端
- 类库（Library）
- Mobile Web 端
- Mobile Native 端

## 核心

> 基本

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[react](https://reactjs.org/docs/installation.html) | - | 生产 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/react/next.svg)](https://github.com/facebook/react) | [![npm](https://img.shields.io/npm/v/react.svg)](https://github.com/facebook/react) | v15.6.1 | 用户界面库
[react-dom](https://reactjs.org/docs/installation.html) | - | 生产 | PCWeb、PCNative、MobileWeb | [![npm (tag)](https://img.shields.io/npm/v/react-dom/next.svg)](https://github.com/facebook/react) | [![npm](https://img.shields.io/npm/v/react-dom.svg)](https://github.com/facebook/react) | v15.6.1 | 用户界面 DOM 绑定库
[~~prop-types~~](https://reactjs.org/docs/typechecking-with-proptypes.html) | - | 生产 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/prop-types/next.svg)](https://github.com/facebook/prop-types) | [![npm](https://img.shields.io/npm/v/prop-types.svg)](https://github.com/facebook/prop-types) | v15.5.10 | Prop 类型检查
[~~react-router-dom~~](https://reacttraining.com/react-router/web/guides/quick-start) | [~~history~~](https://github.com/ReactTraining/history)、[~~react-router~~](https://github.com/ReactTraining/react-router/tree/master/packages/react-router) | 生产 | PCWeb、PCNative、MobileWeb | [![npm (tag)](https://img.shields.io/npm/v/react-router-dom/next.svg)](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom) | [![npm](https://img.shields.io/npm/v/react-router-dom.svg)](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom) | v4.2.2 | React Router 的 DOM 绑定
[~~redux~~](http://redux.js.org/) | - | 生产 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/redux/next.svg)](https://github.com/reactjs/redux) | [![npm](https://img.shields.io/npm/v/redux.svg)](https://github.com/reactjs/redux) | v3.7.2 | 可预测的状态管理容器
[~~react-redux~~](http://redux.js.org/docs/basics/UsageWithReact.html) | - | 生产 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/react-redux/next.svg)](https://github.com/reactjs/react-redux) | [![npm](https://img.shields.io/npm/v/react-redux.svg)](https://github.com/reactjs/react-redux) | v5.0.6 | React 的 Redux 绑定库
[~~redux-saga~~](https://redux-saga.js.org/) | - | 生产 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/redux-saga/next.svg)](https://github.com/redux-saga/redux-saga) | [![npm](https://img.shields.io/npm/v/redux-saga.svg)](https://github.com/redux-saga/redux-saga) | v0.15.6 | React 的 副作用模型（异步流处理）
[axios](https://github.com/axios/axios) | - | 生产 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/axios/next.svg)](https://github.com/axios/axios) | [![npm](https://img.shields.io/npm/v/axios.svg)](https://github.com/axios/axios) | v0.16.2 | HTTP 请求处理器
[~~react-hot-loader~~](http://gaearon.github.io/react-hot-loader/) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/react-hot-loader/next.svg)](https://github.com/gaearon/react-hot-loader) | [![npm](https://img.shields.io/npm/v/react-hot-loader.svg)](https://github.com/gaearon/react-hot-loader) | v3.0.0-beta.7 | React 热加载
[webpack](https://webpack.js.org/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/webpack/next.svg)](https://github.com/webpack/webpack) | [![npm](https://img.shields.io/npm/v/webpack.svg)](https://github.com/webpack/webpack) | v3.5.6 | 前端构建系统
[webpack-dev-server](https://github.com/webpack/webpack-dev-server) | - | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/webpack-dev-server/next.svg)](https://github.com/webpack/webpack-dev-server) | [![npm](https://img.shields.io/npm/v/webpack-dev-server.svg)](https://github.com/webpack/webpack-dev-server) | v2.7.1 | 前端开发服务
[webpack-merge](https://github.com/survivejs/webpack-merge) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/webpack-merge/next.svg)](https://github.com/survivejs/webpack-merge) | [![npm](https://img.shields.io/npm/v/webpack-merge.svg)](https://github.com/survivejs/webpack-merge) | v4.1.0 | Webpack 配置合并处理
[babel-register](https://babeljs.io/docs/usage/babel-register/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/babel-register/next.svg)](https://babeljs.io/docs/usage/babel-register/) | [![npm](https://img.shields.io/npm/v/babel-register.svg)](https://babeljs.io/docs/usage/babel-register/) | v6.26.0 | Webpack 配置文件支持 ES6 语法
[cross-env](https://github.com/kentcdodds/cross-env) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/cross-env/next.svg)](https://github.com/kentcdodds/cross-env) | [![npm](https://img.shields.io/npm/v/cross-env.svg)](https://github.com/kentcdodds/cross-env) | v5.0.5 | 跨平台设置脚本环境

> Redux Framework

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[dva](https://github.com/dvajs/dva) | [react-async-component](https://github.com/ctrlplusb/react-async-component/) | 生产 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/dva/next.svg)](https://github.com/dvajs/dva) | [![npm](https://img.shields.io/npm/v/dva.svg)](https://github.com/dvajs/dva) | v2.1.0 | 基于 React 和 Redux 的轻量级 elm-style 的框架
[dva-loading](https://github.com/dvajs/dva/tree/master/packages/dva-loading) | - | 生产 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/dva-loading/next.svg)](https://github.com/dvajs/dva/tree/master/packages/dva-loading) | [![npm](https://img.shields.io/npm/v/dva-loading.svg)](https://github.com/dvajs/dva/tree/master/packages/dva-loading) | v1.0.4 | Dva 的自动加载插件
[dva-model-extend](https://github.com/dvajs/dva-model-extend) | - | 生产 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/dva-model-extend/next.svg)](https://github.com/dvajs/dva-model-extend) | [![npm](https://img.shields.io/npm/v/dva-model-extend.svg)](https://github.com/dvajs/dva-model-extend) | 0.1.2 | 扩展 dva 模型的实用方法
[babel-plugin-dva-hmr](https://github.com/dvajs/babel-plugin-dva-hmr) | [redbox-react](https://github.com/commissure/redbox-react) | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/babel-plugin-dva-hmr/next.svg)](https://github.com/dvajs/babel-plugin-dva-hmr) | [![npm](https://img.shields.io/npm/v/babel-plugin-dva-hmr.svg)](https://github.com/dvajs/babel-plugin-dva-hmr) | v0.4.0 | Dva 的 HMR Babel 插件
[babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | - | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/babel-plugin-add-module-exports/next.svg)](https://github.com/59naga/babel-plugin-add-module-exports) | [![npm](https://img.shields.io/npm/v/babel-plugin-add-module-exports.svg)](https://github.com/59naga/babel-plugin-add-module-exports) | v0.2.1 | Follow the babel@5 behavior for babel@6

- dva@2.1.0
  - dva-core@1.1.0
  - react-router-dom@4.2.2
    - history@4.7.2
    - react-router@4.2.0
    - prop-types@15.6.0
  - react-router-redux@5.0.0-alpha.6
  - redux@3.7.2
  - react-redux@5.0.6
  - redux-saga@0.15.6
  - react-async-component@1.0.2
  - isomorphic-fetch@2.2.1
    - node-fetch@1.7.3
    - whatwg-fetch@2.0.3
  - babel-runtime@6.26.0
    - regenerator-runtime@0.11.0
- dva-loading@1.0.4
- dva-model-extend@0.1.2
- babel-plugin-dva-hmr@0.4.0
  - redbox-react@1.5.0
- babel-plugin-add-module-exports@0.2.1

> JavaScript

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[babel-loader](https://babeljs.io/docs/setup/#installation) | `babel-core` | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/babel-loader/next.svg)](https://github.com/babel/babel-loader) | [![npm](https://img.shields.io/npm/v/babel-loader.svg)](https://github.com/babel/babel-loader) | v7.1.2 | JavaScript 编译转换器
[babel-preset-env](https://babeljs.io/docs/plugins/preset-env/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/babel-preset-env/next.svg)](https://github.com/babel/babel-preset-env) | [![npm](https://img.shields.io/npm/v/babel-preset-env.svg)](https://github.com/babel/babel-preset-env) | v1.6.0 | ECMAScript 新特性转换
[babel-polyfill](https://babeljs.io/docs/usage/polyfill/) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/babel-polyfill/next.svg)](https://babeljs.io/docs/usage/polyfill/) | [![npm](https://img.shields.io/npm/v/babel-polyfill.svg)](https://babeljs.io/docs/usage/polyfill/) | v6.26.0 | JavaScript 编译转换器-兼容旧浏览器
[babel-preset-react](https://babeljs.io/docs/plugins/preset-react/) | - | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/babel-preset-react/next.svg)](https://babeljs.io/docs/plugins/preset-react/) | [![npm](https://img.shields.io/npm/v/babel-preset-react.svg)](https://babeljs.io/docs/plugins/preset-react/) | v6.24.1 | JSX 语法转换
[babel-preset-stage-2](https://babeljs.io/docs/plugins/preset-stage-2/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/babel-preset-stage-2/next.svg)](https://babeljs.io/docs/plugins/preset-stage-2/) | [![npm](https://img.shields.io/npm/v/babel-preset-stage-2.svg)](https://babeljs.io/docs/plugins/preset-stage-2/) | v6.24.1 | 支持 “draft-草稿”、“candidate-候选” 阶段的 ES 语法解析
[babel-plugin-transform-react-remove-prop-types](https://github.com/oliviertassinari/babel-plugin-transform-react-remove-prop-types) | - | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/babel-plugin-transform-react-remove-prop-types/next.svg)](https://github.com/oliviertassinari/babel-plugin-transform-react-remove-prop-types) | [![npm](https://img.shields.io/npm/v/babel-plugin-transform-react-remove-prop-types.svg)](https://github.com/oliviertassinari/babel-plugin-transform-react-remove-prop-types) | v0.4.8 | 从生产环境下移除 propTypes
[~~bundle-loader~~](https://github.com/webpack-contrib/bundle-loader) | - | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/bundle-loader/next.svg)](https://github.com/webpack-contrib/bundle-loader) | [![npm](https://img.shields.io/npm/v/bundle-loader.svg)](https://github.com/webpack-contrib/bundle-loader) | v0.5.5 | 代码分割

> CSS

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[style-loader](https://github.com/webpack-contrib/style-loader) | - | 开发 | PCWeb、PCNative、MobileWeb | [![npm (tag)](https://img.shields.io/npm/v/style-loader/next.svg)](https://github.com/webpack-contrib/style-loader) | [![npm](https://img.shields.io/npm/v/style-loader.svg)](https://github.com/webpack-contrib/style-loader) | v0.18.2 | 通过注入一个 `<style>` 标签将 CSS 添加到 DOM 中
[css-loader](https://github.com/webpack-contrib/css-loader) | - | 开发 | PCWeb、PCNative、MobileWeb | [![npm (tag)](https://img.shields.io/npm/v/css-loader/next.svg)](https://github.com/webpack-contrib/css-loader) | [![npm](https://img.shields.io/npm/v/css-loader.svg)](https://github.com/webpack-contrib/css-loader) | v0.28.7 | 解析 CSS 中的 `@import` 和 `url()`，就像 `import/require()`
[postcss-loader](https://github.com/postcss/postcss-loader) | - | 开发 | PCWeb、PCNative、MobileWeb | [![npm (tag)](https://img.shields.io/npm/v/postcss-loader/next.svg)](https://github.com/postcss/postcss-loader) | [![npm](https://img.shields.io/npm/v/postcss-loader.svg)](https://github.com/postcss/postcss-loader) | v2.0.6 | PostCSS 的 Webpack 加载器
[autoprefixer](https://github.com/postcss/autoprefixer) | - | 开发 | PCWeb、PCNative、MobileWeb | [![npm (tag)](https://img.shields.io/npm/v/autoprefixer/next.svg)](https://github.com/postcss/autoprefixer) | [![npm](https://img.shields.io/npm/v/autoprefixer.svg)](https://github.com/postcss/autoprefixer) | v7.1.4 | PostCSS 插件；自动添加浏览器供应商前缀
[postcss-pxtorem](https://github.com/cuth/postcss-pxtorem) | - | 开发 | MobileWeb | [![npm (tag)](https://img.shields.io/npm/v/postcss-pxtorem/next.svg)](https://github.com/cuth/postcss-pxtorem) | [![npm](https://img.shields.io/npm/v/postcss-pxtorem.svg)](https://github.com/cuth/postcss-pxtorem) | v4.0.1 | PostCSS 插件；将 px 单位转换为 rem
[less-loader](https://github.com/webpack-contrib/less-loader) | `less` | 开发 | PCWeb、PCNative、MobileWeb | [![npm (tag)](https://img.shields.io/npm/v/less-loader/next.svg)](https://github.com/webpack-contrib/less-loader) | [![npm](https://img.shields.io/npm/v/less-loader.svg)](https://github.com/webpack-contrib/less-loader) | v4.0.5 | 编译 Less 为 CSS
[extract-text-webpack-plugin](https://github.com/webpack-contrib/extract-text-webpack-plugin) | - | 开发 | PCWeb、PCNative、MobileWeb | [![npm (tag)](https://img.shields.io/npm/v/extract-text-webpack-plugin/next.svg)](https://github.com/webpack-contrib/extract-text-webpack-plugin) | [![npm](https://img.shields.io/npm/v/extract-text-webpack-plugin.svg)](https://github.com/webpack-contrib/extract-text-webpack-plugin) | v3.0.0 | 提取 CSS 到一个文件中

> 资源（文件）

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[file-loader](https://github.com/webpack-contrib/file-loader) | - | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/file-loader/next.svg)](https://github.com/webpack-contrib/file-loader) | [![npm](https://img.shields.io/npm/v/file-loader.svg)](https://github.com/webpack-contrib/file-loader) | v0.11.2 | 文件加载器
[url-loader](https://github.com/webpack-contrib/url-loader) | - | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/url-loader/next.svg)](https://github.com/webpack-contrib/url-loader) | [![npm](https://img.shields.io/npm/v/url-loader.svg)](https://github.com/webpack-contrib/url-loader) | v0.5.9 | 类似于 `file-loader`, 但是当文件小于限定的字节时，可以返回一个 data URL
[assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | - | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/assets-webpack-plugin/next.svg)](https://github.com/kossnocorp/assets-webpack-plugin) | [![npm](https://img.shields.io/npm/v/assets-webpack-plugin.svg)](https://github.com/kossnocorp/assets-webpack-plugin) | v3.5.1 | 输出一个资源的 json 对象

> 资源（图片）

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[image-webpack-loader](https://github.com/tcoopman/image-webpack-loader) | - | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/image-webpack-loader/next.svg)](https://github.com/tcoopman/image-webpack-loader) | [![npm](https://img.shields.io/npm/v/image-webpack-loader.svg)](https://github.com/tcoopman/image-webpack-loader) | v3.4.2 | 压缩图片资源
[webpack-spritesmith](https://github.com/mixtur/webpack-spritesmith) | - | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/webpack-spritesmith/next.svg)](https://github.com/mixtur/webpack-spritesmith) | [![npm](https://img.shields.io/npm/v/webpack-spritesmith.svg)](https://github.com/mixtur/webpack-spritesmith) | v0.3.3 | 生成 CSS Sprite 图

> 资源（SVG）

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | - | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/svg-sprite-loader/next.svg)](https://github.com/kisenka/svg-sprite-loader) | [![npm](https://img.shields.io/npm/v/svg-sprite-loader.svg)](https://github.com/kisenka/svg-sprite-loader) | v3.2.5 | 生成 SVG Sprite 图

> HTML

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin) | - | 开发 | PCWeb、PCNative、MobileWeb、MobileNative | [![npm (tag)](https://img.shields.io/npm/v/html-webpack-plugin/next.svg)](https://github.com/jantimon/html-webpack-plugin) | [![npm](https://img.shields.io/npm/v/html-webpack-plugin.svg)](https://github.com/jantimon/html-webpack-plugin) | v2.30.1 | 简化创建 HTML 文件

## 工具助手

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/axios-mock-adapter/next.svg)](https://github.com/ctimmerm/axios-mock-adapter) | [![npm](https://img.shields.io/npm/v/axios-mock-adapter.svg)](https://github.com/ctimmerm/axios-mock-adapter) | v1.9.0 | Axios 请求数据模拟适配器
[mockjs](http://mockjs.com/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/mockjs/next.svg)](https://github.com/nuysoft/Mock) | [![npm](https://img.shields.io/npm/v/mockjs.svg)](https://github.com/nuysoft/Mock) | v1.0.1-beta3 | 数据模拟
[copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/copy-webpack-plugin/next.svg)](https://github.com/webpack-contrib/copy-webpack-plugin) | [![npm](https://img.shields.io/npm/v/copy-webpack-plugin.svg)](https://github.com/webpack-contrib/copy-webpack-plugin) | v4.0.1 | 复制文件及目录
[clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/clean-webpack-plugin/next.svg)](https://github.com/johnagan/clean-webpack-plugin) | [![npm](https://img.shields.io/npm/v/clean-webpack-plugin.svg)](https://github.com/johnagan/clean-webpack-plugin) | v0.1.16 | 删除文件和目录
[~~redux-auth-wrapper~~](https://mjrussell.github.io/redux-auth-wrapper/) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/redux-auth-wrapper/next.svg)](https://github.com/mjrussell/redux-auth-wrapper) | [![npm](https://img.shields.io/npm/v/redux-auth-wrapper.svg)](https://github.com/mjrussell/redux-auth-wrapper) | v2.0.1 | Redux 身份验证和授权处理
[classnames](https://github.com/JedWatson/classnames) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/classnames/next.svg)](https://github.com/JedWatson/classnames) | [![npm](https://img.shields.io/npm/v/classnames.svg)](https://github.com/JedWatson/classnames) | v2.2.5 | CSS 类名操作
[crypto-js](https://github.com/brix/crypto-js) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/crypto-js/next.svg)](https://github.com/brix/crypto-js) | [![npm](https://img.shields.io/npm/v/crypto-js.svg)](https://github.com/brix/crypto-js) | - | JavaScript 前端加密处理
[uuid](https://github.com/kelektiv/node-uuid) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/uuid/next.svg)](https://github.com/kelektiv/node-uuid) | [![npm](https://img.shields.io/npm/v/uuid.svg)](https://github.com/kelektiv/node-uuid) | v3.1.0 | 生产随机数（UUIDS）
[lodash](https://lodash.com/) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/lodash/next.svg)](https://github.com/lodash/lodash) | [![npm](https://img.shields.io/npm/v/lodash.svg)](https://github.com/lodash/lodash) | v4.17.4 | JavaScript 工具库
[babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/babel-plugin-lodash/next.svg)](https://github.com/lodash/babel-plugin-lodash) | [![npm](https://img.shields.io/npm/v/babel-plugin-lodash.svg)](https://github.com/lodash/babel-plugin-lodash) | v3.2.11 | 模块化导入 lodash 方法
[lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/lodash-webpack-plugin/next.svg)](https://github.com/lodash/lodash-webpack-plugin) | [![npm](https://img.shields.io/npm/v/lodash-webpack-plugin.svg)](https://github.com/lodash/lodash-webpack-plugin) | v0.11.4 | 补充 babel-plugin-lodash，创建更小的 lodash 模块构建
[ramda](http://ramdajs.com/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/ramda/next.svg)](https://github.com/ramda/ramda) | [![npm](https://img.shields.io/npm/v/ramda.svg)](https://github.com/ramda/ramda) | v0.24.1 | JavaScript 实用功能
[babel-plugin-ramda](https://github.com/megawac/babel-plugin-ramda) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/babel-plugin-ramda/next.svg)](https://github.com/megawac/babel-plugin-ramda) | [![npm](https://img.shields.io/npm/v/babel-plugin-ramda.svg)](https://github.com/megawac/babel-plugin-ramda) | v1.4.3 | 模块化加载 Ramda
[browser-sync-webpack-plugin](https://github.com/Va1/browser-sync-webpack-plugin) | `browser-sync` | 开发 | MobileWeb | [![npm (tag)](https://img.shields.io/npm/v/browser-sync-webpack-plugin/next.svg)](https://github.com/Va1/browser-sync-webpack-plugin) | [![npm](https://img.shields.io/npm/v/browser-sync-webpack-plugin.svg)](https://github.com/Va1/browser-sync-webpack-plugin) | v1.2.0 | 浏览器同步
[normalizr](https://github.com/paularmstrong/normalizr/) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/normalizr/next.svg)](https://github.com/paularmstrong/normalizr) | [![npm](https://img.shields.io/npm/v/normalizr.svg)](https://github.com/paularmstrong/normalizr) | v3.2.3 | 按照模式规范化嵌套的 JSON
[~~redux-reqs~~](https://github.com/hengkx/redux-reqs) | 'redux-actions'、'redux-nprogress' | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/redux-reqs/next.svg)](https://github.com/hengkx/redux-reqs) | [![npm](https://img.shields.io/npm/v/redux-reqs.svg)](https://github.com/hengkx/redux-reqs) | v0.4.2 | 异步请求助手
[rework.less](https://github.com/yincw/rework.less) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/rework.less/next.svg)](https://github.com/yincw/rework.less) | [![npm](https://img.shields.io/npm/v/rework.less.svg)](https://github.com/yincw/rework.less) | v1.0.0 | CSS 解决方案
[babel-cli](http://babeljs.io/docs/usage/cli/) | - | 开发 | Library | [![npm (tag)](https://img.shields.io/npm/v/babel-cli/next.svg)](http://babeljs.io/docs/usage/cli/) | [![npm](https://img.shields.io/npm/v/babel-cli.svg)](http://babeljs.io/docs/usage/cli/) | v6.26.0 | Babel Cli 工具

## 动画

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[react-motion](https://github.com/chenglou/react-motion) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/react-motion/next.svg)](https://github.com/chenglou/react-motion) | [![npm](https://img.shields.io/npm/v/react-motion.svg)](https://github.com/chenglou/react-motion) | v0.5.1 | React 动画库
[velocity-react](https://github.com/google-fabric/velocity-react) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/velocity-react/next.svg)](https://github.com/google-fabric/velocity-react) | [![npm](https://img.shields.io/npm/v/velocity-react.svg)](https://github.com/google-fabric/velocity-react) | - | React 动画库
[Ant Motion](http://motion.ant.design/) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/rc-animate/next.svg)](https://github.com/ant-design/ant-motion) | [![npm](https://img.shields.io/npm/v/rc-animate.svg)](https://github.com/ant-design/ant-motion) | - | React 动画库
[react-transition-group](https://github.com/reactjs/react-transition-group) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/react-transition-group/next.svg)](https://github.com/reactjs/react-transition-group) | [![npm](https://img.shields.io/npm/v/react-transition-group.svg)](https://github.com/reactjs/react-transition-group) | - | React 动画库

## UI 库

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[antd](https://ant.design) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/antd/next.svg)](https://github.com/ant-design/ant-design) | [![npm](https://img.shields.io/npm/v/antd.svg)](https://github.com/ant-design/ant-design) | v2.13.0 | Ant Design
[babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/babel-plugin-import/next.svg)](https://github.com/ant-design/babel-plugin-import) | [![npm](https://img.shields.io/npm/v/babel-plugin-import.svg)](https://github.com/ant-design/babel-plugin-import) | v1.4.0 | 模块化导入 antd 、antd-mobile 组件
[antd-mobile](https://mobile.ant.design/) | - | 生产 | 移动 Web 端 | [![npm (tag)](https://img.shields.io/npm/v/antd-mobile/next.svg)](https://github.com/ant-design/ant-design-mobile) | [![npm](https://img.shields.io/npm/v/antd-mobile.svg)](https://github.com/ant-design/ant-design-mobile) | v1.6.5 | Ant Design Mobile
[recharts](http://recharts.org/) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/recharts/next.svg)](https://github.com/recharts/recharts) | [![npm](https://img.shields.io/npm/v/recharts.svg)](https://github.com/recharts/recharts) | v1.0.0-alpha.4 | 图表库
[babel-plugin-recharts](https://github.com/recharts/babel-plugin-recharts) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/babel-plugin-recharts/next.svg)](https://github.com/recharts/babel-plugin-recharts) | [![npm](https://img.shields.io/npm/v/babel-plugin-recharts.svg)](https://github.com/recharts/babel-plugin-recharts) | v1.1.0 | 模块化导入 recharts 组件
[react-konva](https://github.com/lavrton/react-konva) | `konva` | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/react-konva/next.svg)](https://github.com/lavrton/react-konva) | [![npm](https://img.shields.io/npm/v/react-konva.svg)](https://github.com/lavrton/react-konva) | v1.1.4 | 图形库
[redux-nprogress](https://github.com/jaredt67/redux-nprogress) | `nprogress` | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/redux-nprogress/next.svg)](https://github.com/jaredt67/redux-nprogress) | [![npm](https://img.shields.io/npm/v/redux-nprogress.svg)](https://github.com/jaredt67/redux-nprogress) | v1.0.2 | 异步请求进度条
[react-custom-scrollbars](https://github.com/malte-wessel/react-custom-scrollbars) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/react-custom-scrollbars/next.svg)](https://github.com/malte-wessel/react-custom-scrollbars) | [![npm](https://img.shields.io/npm/v/react-custom-scrollbars.svg)](https://github.com/malte-wessel/react-custom-scrollbars) | - | 滚动条

## 性能优化

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[immutable](http://facebook.github.io/immutable-js/) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/immutable/next.svg)](https://github.com/facebook/immutable-js) | [![npm](https://img.shields.io/npm/v/immutable.svg)](https://github.com/facebook/immutable-js) | v3.8.1 | 不可变数据
[reselect](https://github.com/reactjs/reselect) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/reselect/next.svg)](https://github.com/reactjs/reselect) | [![npm](https://img.shields.io/npm/v/reselect.svg)](https://github.com/reactjs/reselect) | v3.0.1 | Redux 数据选择库
[redux-observable](https://redux-observable.js.org/) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/redux-observable/next.svg)](https://github.com/redux-observable/redux-observable) | [![npm](https://img.shields.io/npm/v/redux-observable.svg)](https://github.com/redux-observable/redux-observable) | - | RxJS 中间件
[webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | - | 生产 | All | [![npm (tag)](https://img.shields.io/npm/v/webpack-bundle-analyzer/next.svg)](https://github.com/webpack-contrib/webpack-bundle-analyzer) | [![npm](https://img.shields.io/npm/v/webpack-bundle-analyzer.svg)](https://github.com/webpack-contrib/webpack-bundle-analyzer) | v2.9.0 | webpack 优化

## 语法检测

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[babel-eslint](https://github.com/babel/babel-eslint/) | `eslint` | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/babel-eslint/next.svg)](https://github.com/babel/babel-eslint) | [![npm](https://img.shields.io/npm/v/babel-eslint.svg)](https://github.com/babel/babel-eslint) | - | ESLint 使用 Babel 作为解析
[eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/eslint-plugin-react/next.svg)](https://github.com/yannickcr/eslint-plugin-react) | [![npm](https://img.shields.io/npm/v/eslint-plugin-react.svg)](https://github.com/yannickcr/eslint-plugin-react) | v7.3.0 | ESLint 的 React 插件
[eslint-plugin-compat](https://github.com/amilajack/eslint-plugin-compat/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/eslint-plugin-compat/next.svg)](https://github.com/amilajack/eslint-plugin-compat) | [![npm](https://img.shields.io/npm/v/eslint-plugin-compat.svg)](https://github.com/amilajack/eslint-plugin-compat) | v1.0.4 | 在你的代码中检查浏览器兼容性
[eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/eslint-plugin-import/next.svg)](https://github.com/benmosher/eslint-plugin-import) | [![npm](https://img.shields.io/npm/v/eslint-plugin-import.svg)](https://github.com/benmosher/eslint-plugin-import) | v2.7.0 | ESLint 的 import 语法规则插件
[eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/eslint-plugin-immutable/next.svg)](https://github.com/jhusain/eslint-plugin-immutable) | [![npm](https://img.shields.io/npm/v/eslint-plugin-immutable.svg)](https://github.com/jhusain/eslint-plugin-immutable) | - | ESLint 插件，在 JavaScript 中禁用所有突变
[eslint-plugin-jsx-a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/eslint-plugin-jsx-a11y/next.svg)](https://github.com/evcohen/eslint-plugin-jsx-a11y) | [![npm](https://img.shields.io/npm/v/eslint-plugin-jsx-a11y.svg)](https://github.com/evcohen/eslint-plugin-jsx-a11y) | - | 针对JSX元素的a11y规则的静态AST检查器
[eslint-plugin-promise](https://github.com/xjamundx/eslint-plugin-promise/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/eslint-plugin-promise/next.svg)](https://github.com/xjamundx/eslint-plugin-promise) | [![npm](https://img.shields.io/npm/v/eslint-plugin-promise.svg)](https://github.com/xjamundx/eslint-plugin-promise) | - | 执行 JavaScript 承诺的最佳实践
[eslint-plugin-babel](https://github.com/babel/eslint-plugin-babel/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/eslint-plugin-babel/next.svg)](https://github.com/babel/eslint-plugin-babel) | [![npm](https://img.shields.io/npm/v/eslint-plugin-babel.svg)](https://github.com/babel/eslint-plugin-babel) | - | Eslint 规则插件，与 babel-eslint 配套

## 单元测试

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[babel-jest](https://github.com/facebook/jest/tree/master/packages/babel-jest/) | `jest` | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/babel-jest/next.svg)](https://github.com/facebook/jest/tree/master/packages/babel-jest) | [![npm](https://img.shields.io/npm/v/babel-jest.svg)](https://github.com/facebook/jest/tree/master/packages/babel-jest) | v21.0.0 | 测试框架 jest 的 babel 插件
[enzyme-adapter-react-16](http://airbnb.io/enzyme/) | `enzyme` | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/enzyme/next.svg)](https://github.com/airbnb/enzyme) | [![npm](https://img.shields.io/npm/v/enzyme.svg)](https://github.com/airbnb/enzyme) | v2.9.1 | React 单元测试工具
[enzyme-to-json](https://github.com/adriantoine/enzyme-to-json) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/enzyme-to-json/next.svg)](https://github.com/adriantoine/enzyme-to-json) | [![npm](https://img.shields.io/npm/v/enzyme-to-json.svg)](https://github.com/adriantoine/enzyme-to-json) | v1.5.1 | 测试你的 Enzyme 包装器
[react-test-renderer](https://reactjs.org/docs/test-renderer.html) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/react-test-renderer/next.svg)](https://github.com/facebook/react/tree/master/packages/react-test-renderer) | [![npm](https://img.shields.io/npm/v/react-test-renderer.svg)](https://github.com/facebook/react/tree/master/packages/react-test-renderer) | v15.6.1 | React 测试工具

## 平台

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[react-native](http://facebook.github.io/react-native/) | - | 生产 | 移动客户端 | [![npm (tag)](https://img.shields.io/npm/v/react-native/next.svg)](https://github.com/facebook/react-native) | [![npm](https://img.shields.io/npm/v/react-native.svg)](https://github.com/facebook/react-native) | - | 移动应用程序用户界面库
[electron](https://electron.atom.io/) | - | 生产 | PC 客户端 | [![npm (tag)](https://img.shields.io/npm/v/electron/next.svg)](https://github.com/electron/electron) | [![npm](https://img.shields.io/npm/v/electron.svg)](https://github.com/electron/electron) | v1.7.5 | 跨平台的桌面应用开发框架
[electron-packager](https://github.com/electron-userland/electron-packager/) | - | 开发 | PC 客户端 | [![npm (tag)](https://img.shields.io/npm/v/electron-packager/next.svg)](https://github.com/electron-userland/electron-packager) | [![npm](https://img.shields.io/npm/v/electron-packager.svg)](https://github.com/electron-userland/electron-packager) | - | Electron 应用打包工具
[electron-builder](https://electron.build/) | - | 开发 | PC 客户端 | [![npm (tag)](https://img.shields.io/npm/v/electron-builder/next.svg)](https://github.com/electron-userland/electron-builder) | [![npm](https://img.shields.io/npm/v/electron-builder.svg)](https://github.com/electron-userland/electron-builder) | v19.24.1 | Electron 应用打包工具
[menubar](https://github.com/maxogden/menubar/) | - | 开发 | PC 客户端 | [![npm (tag)](https://img.shields.io/npm/v/menubar/next.svg)](https://github.com/maxogden/menubar) | [![npm](https://img.shields.io/npm/v/menubar.svg)](https://github.com/maxogden/menubar) | - | Electron 应用菜单栏
[electron-debug](https://github.com/sindresorhus/electron-debug/) | - | 开发 | PC 客户端 | [![npm (tag)](https://img.shields.io/npm/v/electron-debug/next.svg)](https://github.com/sindresorhus/electron-debug) | [![npm](https://img.shields.io/npm/v/electron-debug.svg)](https://github.com/sindresorhus/electron-debug) | v1.4.0 | Electron debug 扩展

## 开发工具

名称 | 依赖 | 环境 | 适用形态 | 下一个版本 | 当前版本 | VD 内置版本 | 说明
---|---|---|---|---|---|---|---
[Storybook](https://storybook.js.org/) | - | 开发 | All | - | - | - | UI 组件的互动开发和测试环境
[styled-components](http://styled-components.com/) | - | 开发 | 移动客户端 | [![npm (tag)](https://img.shields.io/npm/v/styled-components/next.svg)](https://github.com/styled-components/styled-components) | [![npm](https://img.shields.io/npm/v/styled-components.svg)](https://github.com/styled-components/styled-components) | - | CSS-in-JS 实现
[webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/webpack-dashboard/next.svg)](https://github.com/FormidableLabs/webpack-dashboard) | [![npm](https://img.shields.io/npm/v/webpack-dashboard.svg)](https://github.com/FormidableLabs/webpack-dashboard) | - | Webpack 仪表盘
[Electron Desktop GUI for Webpack Dashboard](https://github.com/FormidableLabs/electron-webpack-dashboard) | - | 开发 | All | - | - | - | Webpack 仪表盘 GUI
[React Developer Tools](https://github.com/facebook/react-devtools) | - | 开发 | All | - | - | - | React 开发者工具
[Redux DevTools Extension](https://github.com/zalmoxisus/redux-devtools-extension) | - | 开发 | All | - | - | - | Redux 开发者工具浏览器扩展
[Reactotron](https://github.com/infinitered/reactotron) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/reactotron/next.svg)](https://github.com/infinitered/reactotron) | [![npm](https://img.shields.io/npm/v/reactotron.svg)](https://github.com/infinitered/reactotron) | - | 用来检查你的 React 和 React Native 应用
[react-styleguidist](https://react-styleguidist.js.org/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/react-styleguidist/next.svg)](https://github.com/styleguidist/react-styleguidist) | [![npm](https://img.shields.io/npm/v/react-styleguidist.svg)](https://github.com/styleguidist/react-styleguidist) | - | React 示例文档生成
[react-blessed](https://github.com/Yomguithereal/react-blessed/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/react-blessed/next.svg)](https://github.com/Yomguithereal/react-blessed) | [![npm](https://img.shields.io/npm/v/react-blessed.svg)](https://github.com/Yomguithereal/react-blessed) | - | React 应用 log 分类
[happypack](https://github.com/amireh/happypack/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/happypack/next.svg)](https://github.com/amireh/happypack) | [![npm](https://img.shields.io/npm/v/happypack.svg)](https://github.com/amireh/happypack) | - | 更快的 Webpack 构建时间
[react-monocle](https://github.com/team-gryff/react-monocle/) | - | 开发 | All | [![npm (tag)](https://img.shields.io/npm/v/react-monocle/next.svg)](https://github.com/team-gryff/react-monocle) | [![npm](https://img.shields.io/npm/v/react-monocle.svg)](https://github.com/team-gryff/react-monocle) | - | 可视化应用程序组件层次结构
