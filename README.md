# cron-elementui

   这是基于Vue.js和Element-UI以及cron-parser封装一个crontab表达式的组件，可以方便、快捷直观地定义cron表达式，并支持给定开始时间后的预览执行时间点列表，方便排除错误。只支持英文版，修复了参考版本中的BUG.

.Only Support English

.JS Element-ui cron-parser

.V-model

.Support multiple crontab expression

.Support cron expression validator



Dependencies:

vue-2.5.2  -support 2.X

element-ui-2.12.0  -support 2.X

cron-parser-2.13.0  -support 2.X

    版本参考自：http://www.easysb.cn/2019/04/210.html 基于iview实现的中文版本[若需预览功能，请参考此网站]；基于该版本进行如下重构：
    1、把iView 替换成 Element-UI
    2、国际化 (将中文翻译为英文，现今版本只支持英文)
    3、修复该版本的表达式执行预览的BUG（BUG描述：表达式0 */3 * * * ? 执行预览前台显示不正确）
    4、样式优化
    
## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
