# JS 使用和基本编程

## 写代码

请完成以下文件中的编码需求：

- [查看 `clone.js`](./clone.js)   
- [查看 `get-host.js`](./get-host.js)
- [查看 `get-sum.js`](./get-sum.js)

## 方法论

如果你有一定的开发经验，并且追求代码的质量。  
那么你一定知道一些实践技巧，简答 3 ～ 10 条即可。

例如：

> 面向对象编程，代码逻辑可以内聚。
> 禁止使用 var，不可变数据用 const 声明，可变数据用 let 声明。

答：1、map方法会返回一个同等长度的新数组，foreach，return最后得到的是undefined，需要将数据装入一个新数组。2、可根据type类型复用一个组件。3、三目运算比if简洁
## 请问以下代码做了什么事情

```js
const getLoglevel = () => {
  return localStorage.loglevel ?? 'INFO';
};
```

答：判断浏览器是否存了loglevel字段，如果localStorage.loglevel为null或undefined，则返回'INFO',否则返回获取到的值。
