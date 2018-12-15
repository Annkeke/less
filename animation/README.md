# 教师上课系统前端实现 可以考虑补充上BEM的规范(参考地址[](http://bem.info/))
# pages 存放前台页面相关
# plugins存放用到的前端插件
# js存放pages里面用到的js
# img存放图片
# css存放pages里面用到的样式表

# pages
# 

# plugins
# bootstrap(http://www.bootcss.com/ ,根据看的视频来看英文版的配置介绍好像相对中文全?建议看英文版)
# 前端展示自适应框架多用于自适应移动端,由于老项目用的是这个,暂时选用它实现页面多终端兼容
# daterangepicker(http://www.daterangepicker.com/) 
# js插件是bootstrap js的插件, 参数默认参数加 ranges (with example predefined ranges)
# 用在了选择日期范围在salary页面下的Search Completed Classes选项卡下

# js
# js页面公共使用的js common.js 还未抽取,等页面做的差不多了抽取
# jquery bootstrap插件需要引入的js框架,也很方便,jquery语法比js简单
# es6 暂时未使用,使用了会补上

# img
# icon相关的图标统一的放在了common下面
# common
# 导航栏使用了的或者页面公用了的

# css
# 改用sass对变量引用以及样式继承与类名嵌套会很友好,由于页面做了几个了,暂时不改
# 由于bootstrap现在的样式是less生成的,因为改用了less编译样式
# common.css
# 导航栏样式,暂时没有看到设计的底部,还可以放置其它公共样式
# 可能需要新增reset.css来重置bootstrap.min.css不符合产品原型的部分html 元素样式
# less编写动画  参考[LESS animation keyframes mixin](https://codepen.io/zvuc/pen/xvoys/)
# classTable.css
# salary.css
# personData.css
# 