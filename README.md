# HackPKU 2021 活动主页

本仓库存储第四届北京大学新工科黑客马拉松活动主页源码，至今仍部署于腾讯云 CloudBase ，可通过 [https://www.hackpku.com/](https://www.hackpku.com/) 访问。该活动已于 2021 年 5 月 10 日结束，相关报道见微信公众号“大信科”，如《[报名 | 2021北京大学“新工科”黑客马拉松报名直通车](https://mp.weixin.qq.com/s/mHdaCXicpUEhuTGImBiRFQ)》等。本仓库内容现作为 Javascript 语言 Web 程序设计课程实践作业提交。

本网页基于 [Vue.js](https://vuejs.org/) 框架实现，并使用了 [Vuetify](https://vuetifyjs.com/en/) 组件库。除文字内容、网页中使用的 Vuetify 组件、图标、字体外，其余内容均为自行设计，并针对不同访问设备做出了响应式优化。

本仓库内容应可表明学生对于 Javascript 语言 Web 程序设计课程内容的学习理解程度，其实践了课程覆盖的大部分内容：

- Web 页面编程入门：HTML、CSS、Javascript
- Javascript 核心特性：函数、Object、模块化机制
- Web 页面编程深入：事件处理、异步编程

但亦有部分内容未做实践，其中有因使用框架而无需自行实现的内容，如：在 Javascript 中直接访问 DOM 、浏览器原生事件处理方法等；有在 ECMAScript 新标准下无需使用的内容，如：基于闭包与原型链的面向对象实现等；有在项目中无需使用的特性，如：作为方法调用的函数、accessor 属性等。还可结合课程作业一（计算器）了解学生对于课程内容的掌握情况，其中已经实践了 class 封装、Symbol 属性等内容。

本项目除 Vue.js 外，还使用了 [pug](https://pugjs.org/) 、[Sass](https://sass-lang.com/) 等库以优化代码编写复杂度，依据 [Lighthouse](https://developers.google.com/web/tools/lighthouse) 优化访问速度，使用 [ESLint](https://eslint.org/) 与 [Prettier](https://prettier.io/) 规范代码格式，使用腾讯云 CloudBase 结合 Github Action 进行 CI/CD 。

本仓库内代码在 Vue.js 模块组织上仍有优化空间，但网页鉴于已经部署而活动已经结束，且需一定的重构才能解决问题，没有进一步修改代码。但整体实现应当能反映学生对于 Vue.js 组件化思想的理解。

## 本地访问

克隆仓库代码后使用 yarn（或 npm）安装依赖，执行 `serve` 命令。

```sh
git clone https://github.com/FerricIon/HackPKU2021_webpage
cd HackPKU2021_webpage
yarn
yarn serve
```
