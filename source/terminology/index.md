# 术语表

## 多路复用

## webpack中的module、chunk、bundle

[webpack 中，module，chunk 和 bundle 的区别是什么？](https://www.cnblogs.com/skychx/p/webpack-module-chunk-bundle.html)

* module: 源码里的每一个文件都是一个module，不管是ESM、commonJS或者是AMD
* chunk: 简单理解，一个入口就是一个chunk，是webpack中间产物
* bundle: 最终输出的文件，bundle包含经过加载和编译的最终文件


我们直接写出来的是 module，webpack 处理时是 chunk，最后生成浏览器可以直接运行的 bundle。