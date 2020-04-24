# 实现一个带缓存功能的 fetch 函数

```js
// url: 要请求的url
// options.age: 缓存时间。
function fetch(url, options){
    // TODO!!!
}


// e.g.
fetch("/api/xxx", {age: 1000}); // 从网络请求（缓存1s）

// 0.5s后
fetch("/api/xxx");  // 从缓存读取（不经过网络）

// 2s 后
fetch("/api/xxx");  // 从网络请求（缓存失效）
```
