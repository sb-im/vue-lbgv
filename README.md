# vue-lbgv
> login backgound video

![demo](docs/gif.gif)

基于vue的背景视频播放组件

```javascript

import VueLbgv from 'vue-lbgv'

    components: {
      'vue-lbgv': VueLbgv
    }
```

#### Attribute

| 参数       | 说明                             | 类型   | 可选值 | 默认值 |
| ---------- | -------------------------------- | ------ | ------ | ------ |
|videos      |视频地址组，每次随机选一个视频播放|Array   |--      |--      |
|image       |当视频播放失败是切换为背景图片    |String  |--      |--      |

#### Slot
| 参数       | 说明
| ---------- | -----------
|--          | 登录窗口

部分代码参考来自这里

https://github.com/bitkylin/ClusterDeviceControlPlatform-Web/blob/master/src/views/login/index.vue
