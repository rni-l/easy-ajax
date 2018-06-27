# easy-ajax

> 简单的 ajax 使用，基于 promise

## 功能

```javascript
// 使用
ajax.get(...)
ajax.post(...)
ajax.put(...)
ajax.xxx(...)

ajax({
  method: 'get',
  url: '...',
  data: {...}
})

```

* 可配置参数
  * method
  * url
  * params
  * headers
  * timeout
  * responseType
  * responseEncoding
  * transformRequest -- 发起请求时，可以统一修改参数、header
  * transformReponse -- 接收相应前，统一修改数据
* 可配置默认参数
* 拥有拦截器功能
* 可终止请求
* 基于 promise

## 使用

> 使用的时候，可调用的方法、属性

