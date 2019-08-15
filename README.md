### 状态管理的解决方案

---

### Flux
![](./images/flow.png)
特点: 数据单向流动

- 不同组件的state，存放在一个外部的、公共的 Store 上面。
- 组件订阅 Store 的不同部分。
- 组件发送（dispatch）动作（action），引发 Store 的更新。


### 目前流行的两个 React 架构
React 架构的最重要作用：管理 Store 与 View 之间的关系
- MobX：响应式（Reactive）管理，state 是可变对象，适合中小型项目
- Redux：函数式（Functional）管理，state 是不可变对象，适合大型项目
