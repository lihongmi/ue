# ue - 移动端UI框架

## github地址：https://github.com/tuxingsheng/ue.git
## 在线访问地址：https://tuxingsheng.github.io/ue/examples/

###框架理念
---
```objc
分离、独立、组件，ue框架之间保持低耦合，保持单个组件的独立性，不和框架本身绑定，即使某个组件功能单独拿出去当做
插件也可以使用，ue只包含必不可少的核心，具体使用哪些组件，需要单独引入具体的js和css，看起来很符合组件的概念(其
实是为了方便以后ue + vue相结合的ue+做的准备)
```

###ue框架核心
---
```objc
框架主体由ue-flex.js(压缩之后2kb) + ue.js(压缩之后40kb) + ue.css(压缩之后10kb)[共52kb]组成，ue-flex是
淘宝的flexible.js，动态计算rem，ue.js主要由Iscroll.js(v5.2.0) + touch.js组成，Iscroll.js主要是实现移
动端的滚动，touch.js主要是实现移动端的事件支持，包含tap、flick、swipe、drag、longtap、hold、pinch等事件
支持，默认已经支持tap事件
```
