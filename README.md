# jigsaw
canvas滑动验证码

## [演示地址](https://yeild.github.io/jigsaw/demo.html)

### 用法：
1. 引入jigsaw.js 和 jigsaw.css

2.
```
jigsaw.init({
  el: document.getElementById('container'),
  onSuccess: function () { ... },
  onFail: function () { ... },
  onRefresh: function () { ... }
})
```

### Tips：

1. 图片从 https://picsum.photos/ 随机获取，然后用canvas裁剪生成滑块。

2. 未编译ES6语法，建议使用现代浏览器体验。

3. 纯前端验证对安全性没意义，因此本项目仅供学习交流，不考虑实用性。
