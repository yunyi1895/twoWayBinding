
# 渐进实现简单的vue双向绑定
 
 vue 双向绑定的实现原理是通过[Object.defineProperty](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperty)里面的set进行数据监控，每次数据变化都更新DOM;兼容性ie8+,所以Vue只能用于ie8+的浏览器;

 具体实现请查看demo