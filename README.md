### 下厨房前端题目：使用  ReactJS 实现 iOS 端的购物车

```
 - PaymentUI
   - ItemsTable
     - Item
   - BottomBar
```


#### 零、ReactJS 学习笔记

1. 在 React 里，数据流是从父节点到子节点单方向传递的

2. 不要直接修改 `this.state`，通过 `setState` 方法来修改，然后 React 便会重绘

3. 用 React 就不能用j Query 以 DOM 为核心的设计思路，React 是声明式的我们要去声明在不同的时间点 UI 的形态，另外通过数据去改变也是数据驱动，React 会管好剩下的事情。

#### 一、编程中遇到的一些问题及解决方案

1. 复选框点击事件与状态判定在 React 中应该如何实现？
2. React 组件间通信：父组件如何得到子组件的状态？