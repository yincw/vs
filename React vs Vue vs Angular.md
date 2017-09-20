## React vs Vue vs Angular

基本信息 | React | Vue | Angular
---|---|---|---
Website | https://facebook.github.io/react/ | https://vuejs.org/ | https://angular.io/
Github | https://github.com/facebook/react | https://github.com/vuejs/vue | https://github.com/angular/angular
Github Star | 76016 | 67600 | 27996
Recommended language | JavaScript | JavaScript | [TypeScript](http://www.typescriptlang.org/)
Version | v15.6.1 | v2.4.4 | v4.4.2
Author | Facebook, Inc. | Yuxi (Evan) You | Google, Inc.
License | [BSD licensed](https://github.com/facebook/react/blob/master/LICENSE) + [patent grant](https://github.com/facebook/react/blob/master/PATENTS)(专利许可) | [MIT](https://github.com/vuejs/vue/blob/dev/LICENSE) | [MIT](https://github.com/angular/angular/blob/master/LICENSE)
Compatibility | IE 9+ | IE 9+ | IE 9+
模块系统 | ES Modules + Webpack | ES Modules + Webpack | ES Modules + ngModel
组件化 | ES6 Class Syntax | `Vue.component({})` | `@Component({})`
模板引擎  | [JSX](https://facebook.github.io/react/docs/introducing-jsx.html)、[ES6](https://facebook.github.io/react/docs/react-without-es6.html) | [HTML](https://vuejs.org/v2/guide/syntax.html) | [HTML](https://angular.io/guide/template-syntax)
数据绑定  | 单向绑定 | 单向、双向绑定 | 双向绑定


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
Github Star | 53609 | 14939 | 31368
Recommended language | JavaScript | JavaScript | [TypeScript](http://www.typescriptlang.org/)
Version | v0.48 | v0.13.0 | v3.10.3
Author | Facebook, Inc. | Alibaba, Inc. | Drifty Co.
License | [BSD licensed](https://github.com/facebook/react-native/blob/master/LICENSE) + [patent grant](https://github.com/facebook/react-native/blob/master/PATENTS) | [Apache License 2.0](https://github.com/apache/incubator-weex/blob/master/LICENSE) | [MIT](https://github.com/ionic-team/ionic/blob/master/LICENSE)
Render Engine | React | Vue | Angular
Compatibility | - | - | -


其它方案 | Preact | Riot | Inferno | Marko | Rax
---|---|---|---|---|---
Website | https://preactjs.com/ | http://riotjs.com/ | https://infernojs.org/ | http://markojs.com/ | https://alibaba.github.io/rax/
Github | https://github.com/developit/preact/ | https://github.com/riot/riot | https://github.com/infernojs/inferno | https://github.com/marko-js/marko | https://github.com/alibaba/rax
Github Star | 15049 | 12363 | 11256 | 5201 | 3484
Recommended language | JavaScript | JavaScript | JavaScript | JavaScript | JavaScript
Version | v8.2.5 | v3.7.0 | v3.9.0 | v4.4.28 | v0.4.13
Author | Jason Miller | Muut Inc. | Dominic Gannaway | eBay Inc | Alibaba Group Holding Limited.
License | [MIT](https://github.com/developit/preact/blob/master/LICENSE) | [MIT](https://github.com/riot/riot/blob/master/LICENSE.txt) | [MIT](https://github.com/infernojs/inferno/blob/master/LICENSE.md) | [MIT](https://github.com/marko-js/marko/blob/master/LICENSE) | [BSD](https://github.com/alibaba/rax/blob/master/LICENSE)
Compatibility | IE 9+ | IE 10+ | IE 11+ | - | -
