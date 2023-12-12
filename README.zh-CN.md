# vue-easy-treeline


## 介绍

一款vue-easy-tree改造的树组件。


基于[element-ui](https://element.eleme.cn/#/zh-CN/component/tree)(License:MIT)中抽取的tree样式和功能，结合[vue-virtual-scroller](https://github.com/Akryum/vue-virtual-scroller)(License:MIT)所做的树组件。

## 修改的功能列表

-  新增了tree-line属性，使得结构更加明显
-  新增了is-user-node 的类名，区分虚拟dom下的组和用户


## 安装

```
npm i vue-easy-treeline
```

或

```
yarn add vue-easy-treeline

```

## 引入

### 全局引入

在 `main.js` 文件中引入：

```JS
import Vue from "vue";
import VueEasyTreeline from 'vue-easy-treeline'
import 'vue-easy-treeline/src/assets/index.scss'

Vue.use(VueEasyTreeline)
```

### 组件引入

在组件中引入：

```JS
import VueEasyTreeline from 'vue-easy-treeline'
import 'vue-easy-treeline/src/assets/index.scss'

export default {
  components: {
    VueEasyTreeline
  }
}
```

## License

[MIT](http://www.opensource.org/licenses/mit-license.php)
