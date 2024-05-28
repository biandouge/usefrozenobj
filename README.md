## \# Vue 项目名称

 usefrozenobj

## 介绍

这是一个使用Vue.js框架创建的项目，用于说明使用被冻结的对象能够提高js的运行效率。

有些对象，比如商品的列表等，是不需要改变的，只能看不能操作的，就不需要去遍历它把它变成响应式。在vue里，一旦发现你给它提供了一个冻结的对象，它就不再去遍历这个对象，不再给它提供响应式，这就提高了我们的效率。

分别点击两个按钮，返回结果后，打开谷歌性能分析工具，可以很清楚的分析两个点击事件的运行情况。

##  安装

确保你已经安装了Node.js和npm。



## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
