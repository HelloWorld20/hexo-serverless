# 术语表

## REPL模式

REPL 是 4 个单词的首字母组：Read Eval Print Loop。或者是read-eval-print loop，也就是交互式模式。

首次遇到是: [Node.js 多线程 —— worker_threads 初体验](https://blog.skk.moe/post/say-hello-to-nodejs-worker-thread/)


## [BFF架构](https://juejin.cn/post/6844903959333699598)

是Backends For Frontends单词的缩写。主要是用于服务前端的后台应用程序，来解决多访问终端业务耦合问题。

区别于传统的接口设计，传统的接口往往都是与业务强耦合的，很难在多个环境复用。BFF架构更多的是在前端、后端数据接口中间新增一层BFF服务接口，用于为前端服务。

## webpack中的module、chunk、bundle

[webpack 中，module，chunk 和 bundle 的区别是什么？](https://www.cnblogs.com/skychx/p/webpack-module-chunk-bundle.html)

* module: 源码里的每一个文件都是一个module，不管是ESM、commonJS或者是AMD
* chunk: 简单理解，一个入口就是一个chunk，是webpack中间产物
* bundle: 最终输出的文件，bundle包含经过加载和编译的最终文件


我们直接写出来的是 module，webpack 处理时是 chunk，最后生成浏览器可以直接运行的 bundle。

## 心智模型

首次听到这个词汇是在卡颂大佬的[React技术揭秘](https://react.iamkasong.com/process/fiber-mental.html)里看到，后面在Vue3文档中也看到。

按照百度百科的定义，心智模型是指深植我们心中关于我们自己、别人、组织及周围世界每个层面的假设、形象和故事。并深受习惯思维、定势思维、已有知识的局限。

简单说就是一种思维定式

放在开发界，心智模型可以理解为，我们“熟悉的写法”。

比如，React的Hooks出来之前，就非常不一致。开发者往往需要推翻原来对React的理解，重新构建认知，才能对Hooks有正确的理解。

Vue文档中提到，SSR有统一的心智模型。意思大概就是，开发SSR不需要修改太多的“思维"，开发者还是可以用前端SPA的”思维“来开发SSR。