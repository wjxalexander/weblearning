## 组件名称： js-component-tab
## 组件功能
原生JS实现在父容器下点击序列标签页可切换展示对应的面板
## 组件实现方式
- 构造Tab函数，把传入参数（目标dom节点)。
- 在Tab的prototype属性上添加实现方法：init:  在传入参数下通过事件委托绑定点击事件 bind，利用切换被点击的子元素的class实现tab的切换。

## 如何使用
通过new一个Tab函数，传入参数为需要实现tab切换功能的DOM节点。

