## React vs Vue vs Angular

Update Time: 2017-09-26

基本信息 | React | Vue | Angular
---|---|---|---
Website | https://facebook.github.io/react/ | https://vuejs.org/ | https://angular.io/
Github | https://github.com/facebook/react | https://github.com/vuejs/vue | https://github.com/angular/angular
Github Star | [![GitHub stars](https://img.shields.io/github/stars/facebook/react.svg?style=social&label=Stars)](https://github.com/facebook/react) | [![GitHub stars](https://img.shields.io/github/stars/vuejs/vue.svg?style=social&label=Stars)](https://github.com/vuejs/vue) | [![GitHub stars](https://img.shields.io/github/stars/angular/angular.svg?style=social&label=Stars)](https://github.com/angular/angular)
Recommended language | JavaScript | JavaScript | [TypeScript](http://www.typescriptlang.org/)
Version | [![npm](https://img.shields.io/npm/v/react.svg)](https://github.com/facebook/react) | [![npm](https://img.shields.io/npm/v/vue.svg)](https://github.com/vuejs/vue) | [![npm](https://img.shields.io/npm/v/@angular/core.svg)](https://github.com/angular/angular)
Next Version | [![npm (tag)](https://img.shields.io/npm/v/react/next.svg)](https://github.com/facebook/react) | [![npm (tag)](https://img.shields.io/npm/v/vue/next.svg)](https://github.com/vuejs/vue) | [![npm (tag)](https://img.shields.io/npm/v/@angular/core/next.svg)](https://github.com/angular/angular)
Author | Facebook, Inc. | Yuxi (Evan) You | Google, Inc.
License | [![npm](https://img.shields.io/npm/l/react.svg)](https://github.com/facebook/react) | [![npm](https://img.shields.io/npm/l/vue.svg)](https://github.com/vuejs/vue) | [![npm](https://img.shields.io/npm/l/@angular/core.svg)](https://github.com/angular/angular)
Compatibility | IE 9+ | IE 9+ | IE 9+
模块系统 | ES Modules + Webpack | ES Modules + Webpack | ES Modules + ngModel
组件化 | ES6 Class Syntax | `Vue.component({})` | `@Component({})`
模板引擎  | [JSX](https://facebook.github.io/react/docs/introducing-jsx.html)、[ES6](https://facebook.github.io/react/docs/react-without-es6.html) | [HTML](https://vuejs.org/v2/guide/syntax.html) | [HTML](https://angular.io/guide/template-syntax)
数据绑定  | 单向绑定 | 单向、双向绑定 | 双向绑定

> React 从 v15.6.2 开始，License 改成 MIT，
> 之前为  BSD licensed + patent grant (专利许可)

生态系统 | React | Vue | Angular
---|---|---|---
项目脚手架 | [create-react-app](https://github.com/facebookincubator/create-react-app) | [vue-cli](https://github.com/vuejs/vue-cli) | [@angular/cli](https://github.com/angular/angular-cli)
构建系统 | [Webpack](https://webpack.js.org/) | [Webpack](https://webpack.js.org/)、[cooking-cli](https://github.com/ElemeFE/cooking) | [Webpack](https://webpack.js.org/)、[angular-starter](https://github.com/AngularClass/angular-starter)
路由 | [react-router](https://github.com/ReactTraining/react-router) | [vue-router](https://github.com/vuejs/vue-router) | [@angular/router](https://angular.io/guide/router)
HTTP | [axios](https://github.com/mzabriskie/axios)、~~[fetch](https://github.com/github/fetch)~~ | [vue-resource](https://github.com/pagekit/vue-resource) | [@angular/common/http](https://angular.io/guide/http)
应用状态管理 | [redux](https://github.com/reactjs/redux)、[mobx](https://github.com/mobxjs/mobx) | [vuex](https://github.com/vuejs/vuex) | [@ngrx/store](https://github.com/ngrx/platform)
状态绑定 | [react-redux](https://github.com/reactjs/react-redux) | - | -
RxJS 整合 | [redux-observable](https://github.com/redux-observable/redux-observable) | [vue-rx](https://github.com/vuejs/vue-rx)、[vuex-observable](https://github.com/vuejs/vuex-observable) | [@ngrx/store](https://github.com/ngrx/platform)
绑定 Store 到路由 | [react-router-redux](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-redux) | [vuex-router-sync](https://github.com/vuejs/vuex-router-sync) | [@ngrx/router-store](https://github.com/ngrx/platform)
副作用模型（side effect model） | [redux-saga](https://github.com/redux-saga/redux-saga) | - | [@ngrx/effects](https://github.com/ngrx/platform)
开发工具（Devtools）  | [react-devtools](https://github.com/facebook/react-devtools)、[redux-devtools](https://github.com/gaearon/redux-devtools)、[mobx-react-devtools](https://github.com/mobxjs/mobx-react-devtools) | [vue-devtools](https://github.com/vuejs/vue-devtools) | [@ngrx/store-devtools](https://github.com/ngrx/platform)
UI 库 | PC Web: [material-ui](https://github.com/callemall/material-ui)、[antd](https://github.com/ant-design/ant-design)、[react-desktop](https://github.com/gabrielbull/react-desktop)、[reactstrap](https://github.com/reactstrap/reactstrap) <br /> Mobile Web: [antd-mobile](https://github.com/ant-design/ant-design-mobile)、[react-weui](https://github.com/weui/react-weui) | PC Web: [element-ui](https://github.com/ElemeFE/element)、[iview](https://github.com/iview/iview)、[muse-ui](https://github.com/museui/muse-ui) <br /> Mobile Web: [vux](https://github.com/airyland/vux)、[mint-ui](https://github.com/ElemeFE/mint-ui/)、[vue-onsenui](https://github.com/OnsenUI/OnsenUI) | PC Web: [angular-ui](https://github.com/angular-ui) <br /> Mobile Web: [ngx-onsenui](https://github.com/OnsenUI/OnsenUI)


移动客户端<br/>生态系统 | React Native | Weex | Ionic
---|---|---|---
Website | http://facebook.github.io/react-native/ | https://weex.apache.org/cn/ | https://ionicframework.com/
Github | https://github.com/facebook/react-native | https://github.com/alibaba/weex | https://github.com/ionic-team/ionic
Github Star | [![GitHub stars](https://img.shields.io/github/stars/facebook/react-native.svg?style=social&label=Stars)](https://github.com/facebook/react-native) | [![GitHub stars](https://img.shields.io/github/stars/alibaba/weex.svg?style=social&label=Stars)](https://github.com/alibaba/weex) | [![GitHub stars](https://img.shields.io/github/stars/ionic-team/ionic.svg?style=social&label=Stars)](https://github.com/ionic-team/ionic)
Recommended language | JavaScript | JavaScript | [TypeScript](http://www.typescriptlang.org/)
Version | [![npm](https://img.shields.io/npm/v/react-native.svg)](https://github.com/facebook/react-native) | [![npm](https://img.shields.io/npm/v/weex-toolkit.svg)](https://github.com/weexteam/weex-toolkit) | [![npm](https://img.shields.io/npm/v/ionic.svg)](https://github.com/ionic-team/ionic)
Next Version | [![npm (tag)](https://img.shields.io/npm/v/react-native/next.svg)](https://github.com/facebook/react-native) | [![npm (tag)](https://img.shields.io/npm/v/weex-toolkit/next.svg)](https://github.com/weexteam/weex-toolkit) | [![npm (tag)](https://img.shields.io/npm/v/ionic/next.svg)](https://github.com/ionic-team/ionic)
Author | Facebook, Inc. | Alibaba, Inc. | Drifty Co.
License | [![npm](https://img.shields.io/npm/l/react-native.svg)](https://github.com/facebook/react-native) | [![npm](https://img.shields.io/npm/l/weex.svg)](https://github.com/alibaba/weex) | [![npm](https://img.shields.io/npm/l/ionic.svg)](https://github.com/ionic-team/ionic)
Render Engine | React | Vue | Angular
Compatibility | - | - | -


其它方案 | Preact | Riot | Inferno | Marko | Rax
---|---|---|---|---|---
Website | https://preactjs.com/ | http://riotjs.com/ | https://infernojs.org/ | http://markojs.com/ | https://alibaba.github.io/rax/
Github | https://github.com/developit/preact/ | https://github.com/riot/riot | https://github.com/infernojs/inferno | https://github.com/marko-js/marko | https://github.com/alibaba/rax
Github Star | [![GitHub stars](https://img.shields.io/github/stars/developit/preact.svg?style=social&label=Stars)](https://github.com/developit/preact/) | [![GitHub stars](https://img.shields.io/github/stars/riot/riot.svg?style=social&label=Stars)](https://github.com/riot/riot) | [![GitHub stars](https://img.shields.io/github/stars/infernojs/inferno.svg?style=social&label=Stars)](https://github.com/infernojs/inferno) | [![GitHub stars](https://img.shields.io/github/stars/marko-js/marko.svg?style=social&label=Stars)](https://github.com/marko-js/marko) | [![GitHub stars](https://img.shields.io/github/stars/alibaba/rax.svg?style=social&label=Stars)](https://github.com/alibaba/rax)
Recommended language | JavaScript | JavaScript | JavaScript | JavaScript | JavaScript
Version | [![npm](https://img.shields.io/npm/v/preact.svg)](https://github.com/developit/preact/) | [![npm](https://img.shields.io/npm/v/riot.svg)](https://github.com/riot/riot) | [![npm](https://img.shields.io/npm/v/inferno.svg)](https://github.com/infernojs/inferno) | [![npm](https://img.shields.io/npm/v/marko.svg)](https://github.com/marko-js/marko) | [![npm](https://img.shields.io/npm/v/rax.svg)](https://github.com/alibaba/rax)
Next Version | [![npm](https://img.shields.io/npm/v/preact/next.svg)](https://github.com/developit/preact/) | [![npm](https://img.shields.io/npm/v/riot/next.svg)](https://github.com/riot/riot) | [![npm](https://img.shields.io/npm/v/inferno/next.svg)](https://github.com/infernojs/inferno) | [![npm](https://img.shields.io/npm/v/marko/next.svg)](https://github.com/marko-js/marko) | [![npm](https://img.shields.io/npm/v/rax/next.svg)](https://github.com/alibaba/rax)
Author | Jason Miller | Muut Inc. | Dominic Gannaway | eBay Inc | Alibaba Group Holding Limited.
License | [![npm](https://img.shields.io/npm/l/preact.svg)](https://github.com/developit/preact/) | [![npm](https://img.shields.io/npm/l/riot.svg)](https://github.com/riot/riot) | [![npm](https://img.shields.io/npm/l/inferno.svg)](https://github.com/infernojs/inferno) | [![npm](https://img.shields.io/npm/l/marko.svg)](https://github.com/marko-js/marko) | [![npm](https://img.shields.io/npm/l/rax.svg)](https://github.com/alibaba/rax)
Compatibility | IE 9+ | IE 10+ | IE 11+ | - | -
