# zooc-widgets组件库

zooc-widgets是一个基于Vue2和Element-UI的开源UI组件库，旨在为Web开发人员提供易于使用和高度可定制的UI组件。

## 特点
```
• 包含各种常用的UI组件，如按钮、表单、菜单、模态框等。
• 使用Element-UI作为基础组件，同时提供自定义组件，以适应任何项目的需求。
• 可以轻松地自定义样式和主题，以满足不同项目的需求。
• 遵循现代Web标准，支持响应式设计和无障碍性。
• 使用简单，易于集成到现有项目中。
```
## 安装

zooc-widgets可以通过npm安装：

npm install zooc-widgets


## 使用

在您的项目中全局导入组件，例如：

```javascript
import Vue from 'vue'
import App from './App.vue'

import ZoocWidgets from 'zooc-widgets'  //引入element-ui库

Vue.config.productionTip = false

Vue.use(ZoocWidgets)  //全局注册ZoocWidgets

new Vue({
  render: h => h(App),
}).$mount('#app')
```
