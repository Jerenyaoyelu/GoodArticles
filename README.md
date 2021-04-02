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

<br/>

## 微信小程序
- [同层渲染原理](https://developers.weixin.qq.com/community/develop/article/doc/000c4e433707c072c1793e56f5c813)


<br/>

## 前端工程化
- [前端工程化实践总结](https://cloud.tencent.com/developer/article/1505471)
- [微信小程序工程化探索](https://codertw.com/%E7%A8%8B%E5%BC%8F%E8%AA%9E%E8%A8%80/742008/)
- [小程序工程化探索](https://github.com/listenzz/MyMina)
- [webpack5小程序工程化example](https://github.com/Jerenyaoyelu/miniprogram_webpack)

<br/>

## 性能优化

> 微信小程序篇
- [渲染性能调优](https://segmentfault.com/a/1190000019910111)

<br/>

## 电子书
- [现代浏览器工作原理](https://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/)


<br/>

## 其他杂文
- [通俗易懂的解释什么是RPC](https://zhuanlan.zhihu.com/p/36427583)
