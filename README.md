# understandVue

## 介绍
  Vue.js原理简单分析，记录了个人学习Vue.js实现过程中的一些心得以及收获。

## vue(MVVM框架)的三大要素
**响应式：vue如何监听到data每个属性的变化？**

**模板引擎：vue的模板如何被解析，指令如何处理**

**渲染： vue的模板如何被渲染成html? 以及渲染过程是怎样的**

## vue的整个实现流程
#### 第一步：解析模板成render函数
[模板是什么](./docs/模板的本质.md)

[render函数](./docs/render函数.md)

[render函数和vdom](./docs/render函数和vdom.md)

#### 第二步：响应式开始监听
[响应式的原理](./docs/响应式的原理.md)

#### 第三步：首次渲染，显示页面，且绑定依赖

#### 第四步：data属性变化，触发rerender
