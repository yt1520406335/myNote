## tips

- ref的回调函数执行时机为
    - 组件被挂载后，回调函数被立即执行，回调函数的参数为该组件的具体实例。
    - 组件被卸载或者原有的ref属性本身发生变化时，回调也会被立即执行，此时回调函数参数为null，以确保内存泄露
    
另一种高阶函数： 函数（执行结果是返回新的组件）作为子组件传入，在父组件的render方法中执行此函数，

## 几个重要的概念

- effect
- expirationTime
- updateEqueue

## issues

- 更高优先级任务被执行时fiber是如何恢复被打断的work的
- __REACT_DEVTOOLS_GLOBAL_HOOK__作用

## 阅读链接

- [高阶组件](https://juejin.im/post/59b36b416fb9a00a636a207e)