# frontend-developer-roadmap
前端学习之路, 记录前端小白成长历程, 学习总结, 工具汇总, 打造开箱即用的学习体验

## 常用js库汇总
之前有很多人问学好前端需要学习哪些 js 库, 主流框架应该学 vue 还是 react ? 针对这些问题, 笔者来说说自己的看法和学习总结. 

首先我觉得在学习任何知识之前必须要有一个明确的学习目标, 知道自己为什么要学它, 而不是看网上说的一股脑的给你灌输各种知识, 让你学习各种库, 从而不断的制造大家的焦虑感.

**前端**由于入行门槛低, 更新换代很快, 每年都会有大量新的框架和库出现, 也有大量库被淘汰(比如 `JQuery`, 但是学习它的设计思想很有必要). 所以我们大可不必担心, 保持自己的学习步伐, 按需学习即可. 比如说你对移动端比较感兴趣, 工作中也刚好涉及到一些技术的应用,那么我可以专门研究移动端相关的技术和框架, 又或者你对企业后台/中台产品感兴趣, 比较喜欢开发PC端项目, 那么我们可以专门研究这种类型的js库或者框架, 接下来笔者也是按照不同前端业务的需求, 来整理一份能快速应用到工作中的js库, 以提高大家的开发效率. 

## Relative developer-roadmap
* [React学习必备](https://github.com/MrXujiang/frontend-developer-roadmap/blob/main/React.md)
* [HelloWorld开发者社区, 你要的技术都在这里](https://https://www.helloworld.net)

## js常用工具类

![](https://imgkr2.cn-bj.ufileos.com/70f4ed18-437e-47fd-b4c8-642fbb27f9ce.png?UCloudPublicKey=TOKEN_8d8b72be-579a-4e83-bfd0-5f6ce1546f13&Signature=L7M5OG4npvrg2szPBspndAXMYeE%253D&Expires=1606373404)

1. **lodash** 一个一致性、模块化、高性能的 JavaScript 实用工具库。
2. **ramda** 一个很重要的库，提供了许多有用的方法，每个 JavaScript 程序员都应该掌握这个工具
3. **day.js** 一个轻量的处理时间和日期的 JavaScript 库，和 Moment.js 的 API 设计保持完全一样, 体积只有2kb
4. **big.js** 一个小型，快速的JavaScript库，用于任意精度的十进制算术运算
5. **qs** 一个 url参数转化 (parse和stringify)的轻量级js库
6. **decimal.js** 实现JavaScript的任意精度的十进制类型库

## 表单校验

1. **Validator.js** 一个强大的js表单校验库, github地址: https://github.com/validatorjs/validator.js
2. **Validate.js** 致力于提供一种验证数据的跨框架和跨语言方式的js库, 已通过100％代码覆盖率的单元测试  github地址: https://github.com/ansman/validate.js


## dom库

![](https://imgkr2.cn-bj.ufileos.com/4f24ff47-2fa1-4b21-bff4-5bf5fb641a28.png?UCloudPublicKey=TOKEN_8d8b72be-579a-4e83-bfd0-5f6ce1546f13&Signature=3SXuiSkxST%252Fm1GXkwNZDUtEurlU%253D&Expires=1606373747)

1. **JQuery** 封装了各种dom/事件操作, 设计思想值得研究借鉴
2. **zepto** jquery的轻量级版本, 适合移动端操作
3. **fastclick** 一个简单易用的库，它消除了移动端浏览器上的物理点击和触发一个 click 事件之间的 300ms 的延迟。目的就是在不干扰你目前的逻辑的同时，让你的应用感觉不到延迟，反应更加灵敏。

## 文件处理

![](https://imgkr2.cn-bj.ufileos.com/6fffb6be-2509-4f58-88b2-84ab2a5e580d.png?UCloudPublicKey=TOKEN_8d8b72be-579a-4e83-bfd0-5f6ce1546f13&Signature=PCjaDBK6Fd6tGyZROCJjeYF6WyM%253D&Expires=1606373771)

1. **file-saver** 一个在客户端保存文件的解决方案，非常适合在客户端上生成文件的Web应用程序
2. **js-xlsx** 一个强大的解析和编写excel文件的库

## 网络请求

![](https://imgkr2.cn-bj.ufileos.com/a3b2597a-2e30-42ab-a651-bded3020e3f4.png?UCloudPublicKey=TOKEN_8d8b72be-579a-4e83-bfd0-5f6ce1546f13&Signature=dNLoHeQKYj2WkYjiBRt%252F1196i%252FI%253D&Expires=1606373841)

1. **Axios** 一个基于 Promise 的 HTTP 库，可用在 Node.js 和浏览器上发起 HTTP 请求，支持所有现代浏览器，甚至包括 IE8+
2. **Superagent** 基于Ajax的优化, 可以与 Node.js HTTP 客户端搭配使用
3. **fly.js** 一个基于promise的http请求库, 可以用在node.js, Weex, 微信小程序, 浏览器, React Native中

## 动画库

![](https://imgkr2.cn-bj.ufileos.com/b2ffa921-0a1e-4073-a1a1-2f94cab1ba3e.png?UCloudPublicKey=TOKEN_8d8b72be-579a-4e83-bfd0-5f6ce1546f13&Signature=ObehVdsQTGt8AzBkaW0BSXoyy68%253D&Expires=1606373938)

1. **Anime.js** 一个JavaScript动画库，可以处理CSS属性，单个CSS转换，SVG或任何DOM属性以及JavaScript对象
2. **Velocity** 一个高效的 Javascript 动画引擎，与jQuery的 $.animate() 有相同的API, 同时还支持彩色动画、转换、循环、画架、SVG支持和滚动等效果
3. **Vivus** 一个零依赖的JavaScript动画库，可以让我们用SVG制作动画，使其具有被绘制的外观
4. **GreenSock JS** 一个JavaScript动画库，用于创建高性能、零依赖、跨浏览器动画，已在超过400万个网站上使用, 并且可以在React、Vue、Angular项目中使用
5. **Scroll Reveal** 零依赖，为 web 和移动浏览器提供了简单的滚动动画，以动画的方式显示滚动中的内容
6. **Kute.js** 一个强大高性能且可扩展的原生JavaScript动画引擎，具有跨浏览器动画的基本功能
7. **Typed.js** 一个轻松实现打字效果的js插件
8. **fullPage.js** 一个可轻易创建全屏滚动网站的js滚动动画库, 兼容性无可替代
9. **iscroll** 移动端使用的一款轻量级滚动插件
10. **swiper.js** 一款强大的js跨端触摸滑动插件, 使用地址: https://www.swiper.com.cn/api/index.html
11. **MixItUp** 是用于DOM操作的高性能，无依赖库，使您能够使用精美的动画过滤，排序，添加和删除DOM元素的js动画库
12. **Lottie** 一个用于Android，iOS，Web和Windows的库，用于解析使用Bodymovin导出为json的Adobe After Effects动画，并在移动设备和网络上呈现它们, github: https://github.com/airbnb/lottie-web

## 鼠标/键盘相关

![](https://imgkr2.cn-bj.ufileos.com/b304ef27-9e7f-42ee-8d9c-db6f99a280d5.png?UCloudPublicKey=TOKEN_8d8b72be-579a-4e83-bfd0-5f6ce1546f13&Signature=DS5nSUfhrhLpoePoqYNZ%252BGsGOBg%253D&Expires=1606374234)

1. **KeyboardJS** 一个在浏览器中使用的库（与node.js兼容）.它使开发人员可以轻松设置键绑定和使用组合键来设置复杂的绑定.
2. **SortableJS** 功能强大的JavaScript 拖拽库

## 图形/图像处理库

![](https://imgkr2.cn-bj.ufileos.com/dc3c2c46-8bfb-4fd2-954e-8a1804d001e1.png?UCloudPublicKey=TOKEN_8d8b72be-579a-4e83-bfd0-5f6ce1546f13&Signature=p42ZBxD3nBRscoFlFIgYZpPpucU%253D&Expires=1606374499)

1. **html2canvas** 一个强大的使用js开发的浏览器网页截图工具
2. **dom-to-image** 一个可以将任意DOM节点转换为用JavaScript编写的矢量（SVG）或光栅（PNG或JPEG）图像的库
3. **pica** 一个在浏览器中调整图像大小，而不会出现像素失真，处理速度非常快的图片处理库
4. **Lena.js** 一个轻量级的可以给你图像加各种滤镜的js库
5. **Compressor.js** 一个使用本地canvas.toBlob API进行图像有损压缩的js库
6. **Fabric.js** 一个易于使用的基于HTML5 canvas元素的图片编辑器
7. **merge-images** 一个将多张图片合并成一张图的js插件
8. **cropperjs** 一款强大的图片裁切库, 支持灵活的图片裁切方式
9. **Grade** 一个基于图像中的前2种主要颜色生成互补渐变背景的库

## 表单表格

1. **x-spreadsheet** 一个基于web的简单易用的表格插件  github: https://github.com/myliang/x-spreadsheet

以上这些js库不必每一样都去了解和深究, 技术都是为业务服务的, 所以我们按需使用和学习即可. 至于像react或者vue这种框架的相关生态, 笔者这里就不一一介绍了, 官网文档上都有非常详细的生态集, 感兴趣的朋友自行了解即可. 

## Partner project
* [Blink - 一款自定义的生成故障艺术动画的组件库](https://github.com/MrXujiang/blink)
* [H5-Dooring | 一个所见即所得的H5编辑器](https://github.com/MrXujiang/h5-Dooring)


## 持续更新 | Continuous upgrades
每周定期更新, 敬请期待...

## 技术反馈和交流 | Technical feedback and communication
微信：beautifulFront


<img src="http://io.nainor.com/uploads/code_1741c445027.png" width="180px" />

## 技术交流群(加作者微信进群) | chat whit author
<img src="http://io.nainor.com/uploads/WechatIMG3_175231f6420.jpeg" width="180px" />
