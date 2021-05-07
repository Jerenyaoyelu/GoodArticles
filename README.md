# 技术好文收集中心
> 收集/转载一些平时浏览到的写的还不错的好的技术文章/帖子

> 每次转载力求转载原帖，如若不是，欢迎指出

<br/>

## 前端三剑客
> CSS篇
- [理解堆叠顺序和堆叠上下文](https://www.cnblogs.com/BUBU-Sourire/p/11158470.html)
```text
层叠顺序（自底而上）：

堆叠上下文根元素 >> 负z-index >> background >> border >> 块级元素 >> 浮动元素 >> 内联元素 >> z-index为0/auto的定位元素（不为static） >> 正z-index
```

- 外边距合并规则
  - [图文并茂解释合并](https://www.w3school.com.cn/css/css_margin_collapse.asp)
  - [合并规则及阻止方法](https://juejin.cn/post/6844903487172509704)
```text
当两个普通文档流中的块级元素的垂直外边距相遇时，会发生边界重叠，两个合并成一个（两者中的较大者）。水平外边距和行内框、浮动框或绝对定位之间的垂直外边距不会合并。
```

<br/>

## 前端框架
- [剖析Vue实现原理 - 如何实现双向绑定mvvm](https://github.com/DMQ/mvvm)
- [理解Vue生命周期](https://mp.weixin.qq.com/s?__biz=MzU1OTgxNDQ1Nw==&mid=2247484176&idx=1&sn=5623421ed2678046ed9e438aadf6e26f&chksm=fc10c146cb67485015f24f7e9f5862c4c685fc33485fe30e1b375a534b4031978439c554e0c0&scene=21#wechat_redirect)
> ![](./assets/lifecycle.png)
- [理解Vue数据双向绑定原理](https://mp.weixin.qq.com/s?__biz=MzU1OTgxNDQ1Nw%3D%3D&chksm=fc10c151cb6748476008dab2f4e6c6264f5d19678305955c85cec1b619e56e8f7457b7357fb9&idx=1&mid=2247484167&scene=21&sn=7b00b4333ab2722f25f12586b70667ca#wechat_redirect)
> ![](./assets/mvvm.png)

<br/>

## 微信小程序
- [同层渲染原理](https://developers.weixin.qq.com/community/develop/article/doc/000c4e433707c072c1793e56f5c813)


<br/>

## nodejs
- [区分`exports`/`exports default`/`module export`](https://segmentfault.com/a/1190000010426778)
```text
- module.exports/exports: CommonJS规范 （exports是前者的一个引用）
- export/import: es6规范
- require: CommonJS和es6都支持

>> CommonJS定义的模块分为: 模块标识(module)、模块定义(exports) 、模块引用(require)
```
- [node.js模块的接口设计模式](https://gywbd.github.io/posts/2014/11/using-exports-nodejs-interface-design-pattern.html)


<br/>

## 前端工程化
- [前端工程化实践总结](https://cloud.tencent.com/developer/article/1505471)
- [微信小程序工程化探索](https://codertw.com/%E7%A8%8B%E5%BC%8F%E8%AA%9E%E8%A8%80/742008/)
- [小程序工程化探索](https://github.com/listenzz/MyMina)
- [webpack5小程序工程化example](https://github.com/Jerenyaoyelu/miniprogram_webpack)

<br/>

## 性能优化
### Web
- [SPA 的 SEO 方案对比、最终实践](https://markdowner.net/article/73058307795021824?spm=a2c6h.12873639.0.0.30d150b5BHHvCA?spm=a2c6h.12873639.0.0.30d150b5BHHvCA)

### 微信小程序篇
- [渲染性能调优](https://segmentfault.com/a/1190000019910111)

### 打包
- [Tree-Shaking性能优化实践 - 原理篇](https://juejin.cn/post/6844903544756109319)
```text
tree-shaking消除无用的代码，以减少需要加载的js文件体积，使得整体执行时间缩短而达到性能优化的效果。
```

<br/>

## 电子书
- [TypeScript 入门教程](https://ts.xcatliu.com/)
```text
阮一峰：

《TypeScript 入门教程》全面介绍了 TypeScript 强大的类型系统，完整而简洁，示例丰富，比官方文档更易读，非常适合作为初学者学习 TypeScript 的第一本书。
```
- [现代浏览器工作原理](https://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/)


<br/>

## 其他杂文
- [通俗易懂的解释什么是RPC](https://zhuanlan.zhihu.com/p/36427583)
- [实现gitlab PR自动流程处理机器人](https://hellogithub2014.github.io/2019/06/06/gitlab-webhook/)
- [只是痒点需求的产品，怎么做起来？！](http://www.woshipm.com/pd/1046272.html)

<br/>

## 声明
以上内容皆为转载，如有涉及侵权，请联系删除

