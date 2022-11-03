# frontend-developer-roadmap
前端学习之路, 记录前端小白成长历程, 学习总结, 工具汇总, 打造开箱即用的学习体验, 欢迎点击 [issue](https://github.com/MrXujiang/frontend-developer-roadmap/issues) **推荐 / 自荐**项目.

## 常用js库汇总

**前端**由于入行门槛低, 更新换代很快, 每年都会有大量新的框架和库出现, 也有大量库被淘汰(比如 `JQuery`, 但是学习它的设计思想很有必要). 所以我们大可不必担心, 保持自己的学习步伐, 按需学习即可. 比如说你对移动端比较感兴趣, 工作中也刚好涉及到一些技术的应用,那么我可以专门研究移动端相关的技术和框架, 又或者你对企业后台/中台产品感兴趣, 比较喜欢开发PC端项目, 那么我们可以专门研究这种类型的js库或者框架, 接下来笔者也是按照不同前端业务的需求, 来整理一份能快速应用到工作中的js库, 以提高大家的开发效率. 

## Relative developer-roadmap
* [React学习必备](https://github.com/MrXujiang/frontend-developer-roadmap/blob/main/React.md)
* [完整前端成长路线](http://h5.dooring.cn/blog/guides/afrontend)
* [前端可视化技术文档](http://h5.dooring.cn/docz)
* [HelloWorld开发者社区, 你要的技术都在这里](https://https://www.helloworld.net)

## Javascript 项目库

#### js 常用工具类

1. [**lodash**](https://www.lodashjs.com/) 一个一致性、模块化、高性能的 JavaScript 实用工具库。
2. [**xijs**](http://h5.dooring.cn/xijs/) 一款面向复杂业务场景的 javascript 工具库
3. [**ramda**](https://ramda.cn/docs/) 一个很重要的库，提供了许多有用的方法，每个 JavaScript 程序员都应该掌握这个工具
4. [**day.js**](https://dayjs.gitee.io/zh-CN/) 一个轻量的处理时间和日期的 JavaScript 库，和 Moment.js 的 API 设计保持完全一样, 体积只有 2kb
5. [**big.js**](https://github.com/MikeMcl/big.js/) 一个小型，快速的 JavaScript 库，用于任意精度的十进制算术运算
6. [**qs**](https://github.com/ljharb/qs) 一个 url 参数转化 (parse 和 stringify)的轻量级 js 库
7. [**decimal.js**](https://github.com/MikeMcl/decimal.js/) 实现 JavaScript 的任意精度的十进制类型库

#### 表单校验

1. [**Validator.js**](https://github.com/validatorjs/validator.js) 一个强大的 js 表单校验库
2. [**Validate.js**](https://github.com/ansman/validate.js) 致力于提供一种验证数据的跨框架和跨语言方式的 js 库, 已通过 100％代码覆盖率的单元测试

#### dom 库

1. [**JQuery**](https://jquery.com/) 封装了各种 dom/事件操作, 设计思想值得研究借鉴
2. [**zepto**](https://zeptojs.bootcss.com/) jquery 的轻量级版本, 适合移动端操作
3. [**fastclick**](https://github.com/ftlabs/fastclick) 一个简单易用的库，它消除了移动端浏览器上的物理点击和触发一个 click 事件之间的 300ms 的延迟。目的就是在不干扰你目前的逻辑的同时，让你的应用感觉不到延迟，反应更加灵敏。

#### 文件处理

1. [**file-saver**](https://www.npmjs.com/package/file-saver) 一个在客户端保存文件的解决方案，非常适合在客户端上生成文件的 Web 应用程序
2. [**js-xlsx**](https://www.npmjs.com/package/js-xlsx) 一个强大的解析和编写 excel 文件的库

#### 网络请求

1. [**Axios**](https://github.com/axios/axios) 一个基于 Promise 的 HTTP 库，可用在 Node.js 和浏览器上发起 HTTP 请求，支持所有现代浏览器，甚至包括 IE8+
2. [**Superagent**](https://github.com/visionmedia/superagent) 基于 Ajax 的优化, 可以与 Node.js HTTP 客户端搭配使用
3. [**fly.js**](https://github.com/wendux/fly) 一个基于 promise 的 http 请求库, 可以用在 node.js, Weex, 微信小程序, 浏览器, React Native 中

#### 动画库

1. [**Anime.js**](https://github.com/juliangarnier/anime) 一个 JavaScript 动画库，可以处理 CSS 属性，单个 CSS 转换，SVG 或任何 DOM 属性以及 JavaScript 对象
2. [**Velocity**](https://github.com/julianshapiro/velocity) 一个高效的 Javascript 动画引擎，与 jQuery 的 $.animate() 有相同的 API, 同时还支持彩色动画、转换、循环、画架、SVG 支持和滚动等效果
3. [**Vivus**](https://github.com/maxwellito/vivus) 一个零依赖的 JavaScript 动画库，可以让我们用 SVG 制作动画，使其具有被绘制的外观
4. [**GreenSock JS**](https://github.com/greensock/GSAP) 一个 JavaScript 动画库，用于创建高性能、零依赖、跨浏览器动画，已在超过 400 万个网站上使用, 并且可以在 React、Vue、Angular 项目中使用
5. [**Scroll Reveal**](https://github.com/jlmakes/scrollreveal) 零依赖，为 web 和移动浏览器提供了简单的滚动动画，以动画的方式显示滚动中的内容
6. [**Kute.js**](https://github.com/thednp/kute.js/) 一个强大高性能且可扩展的原生 JavaScript 动画引擎，具有跨浏览器动画的基本功能
7. [**Typed.js**](https://github.com/mattboldt/typed.js/) 一个轻松实现打字效果的 js 插件
8. [**fullPage.js**](https://github.com/alvarotrigo/fullPage.js/) 一个可轻易创建全屏滚动网站的 js 滚动动画库, 兼容性无可替代
9. [**iscroll**](https://github.com/cubiq/iscroll) 移动端使用的一款轻量级滚动插件
10. [**swiper.js**](https://www.swiper.com.cn/api/index.html) 一款强大的 js 跨端触摸滑动插件
11. [**MixItUp**](https://github.com/patrickkunka/mixitup) 是用于 DOM 操作的高性能，无依赖库，使您能够使用精美的动画过滤，排序，添加和删除 DOM 元素的 js 动画库
12. [**Lottie**](https://github.com/airbnb/lottie-web) 一个用于 Android，iOS，Web 和 Windows 的库，用于解析使用 Bodymovin 导出为 json 的 Adobe After Effects 动画，并在移动设备和网络上呈现它们

#### 鼠标/键盘相关

1. [**KeyboardJS**](https://github.com/RobertWHurst/KeyboardJS) 一个在浏览器中使用的库（与 node.js 兼容）.它使开发人员可以轻松设置键绑定和使用组合键来设置复杂的绑定.
2. [**SortableJS**](https://github.com/SortableJS/) 功能强大的 JavaScript 拖拽库

#### 图形/图像处理库

1. [**html2canvas**](https://github.com/niklasvh/html2canvas) 一个强大的使用 js 开发的浏览器网页截图工具
2. [**dom-to-image**](https://github.com/tsayen/dom-to-image) 一个可以将任意 DOM 节点转换为用 JavaScript 编写的矢量（SVG）或光栅（PNG 或 JPEG）图像的库
3. [**pica**](https://github.com/nodeca/pica) 一个在浏览器中调整图像大小，而不会出现像素失真，处理速度非常快的图片处理库
4. [**Lena.js**](https://github.com/davidsonfellipe/lena.js/) 一个轻量级的可以给你图像加各种滤镜的 js 库
5. [**Compressor.js**](https://github.com/fengyuanchen/compressorjs) 一个使用本地 canvas.toBlob API 进行图像有损压缩的 js 库
6. [**Fabric.js**](https://github.com/fabricjs) 一个易于使用的基于 HTML5 canvas 元素的图片编辑器
7. [**merge-images**](https://github.com/MarcGodard/merge-images-v2) 一个将多张图片合并成一张图的 js 插件
8. [**cropperjs**](https://github.com/fengyuanchen/cropperjs) 一款强大的图片裁切库, 支持灵活的图片裁切方式
9. [**Grade**](https://github.com/benhowdle89/grade) 一个基于图像中的前 2 种主要颜色生成互补渐变背景的库

#### 可视化
1. [**chartist**](https://gionkunz.github.io/chartist-js/api-documentation.html) 非常轻量的可视化图表库

#### 表单表格

1. [**x-spreadsheet**](https://github.com/myliang/x-spreadsheet) 一个基于 web 的简单易用的表格插件
2. [**rc-table](https://www.npmjs.com/package/rc-table) 高性能可扩展的Table组件库
3. [grid.js](https://gridjs.io/docs/examples/stock-market) 支持多框架的高级表格插件

## Css 相关库

## React 相关库

[react-cropper-pro | 图片一键上传/裁切/压缩](https://github.com/MrXujiang/react-cropper-pro)

## Vue 相关库

## Nodejs 相关库

## 优秀开源项目集合<Badge>学习进阶必备</Badge>


以上这些库不必每一样都去了解和深究, 技术都是为业务服务的, 所以我们按需使用和学习即可. 至于像 react 或者 vue 这种框架的相关生态, 笔者这里就不一一介绍了, 官网文档上都有非常详细的生态集, 感兴趣的朋友自行了解即可.

## Partner project
* [Blink - 一款自定义的生成故障艺术动画的组件库](https://github.com/MrXujiang/blink)
* [H5-Dooring | 一个所见即所得的H5编辑器](https://github.com/MrXujiang/h5-Dooring)


## 持续更新 | Continuous upgrades
每周定期更新, 敬请期待...

## 技术反馈和交流 | Technical feedback and communication
微信：beautifulFront


<img src="http://cdn.dooring.cn/dr/qtqd_code.png" width="180px" />

## 技术交流群(加作者微信进群) | chat whit author
<img src="http://cdn.dooring.cn/dr/lowcode.jpeg" width="180px" />
