### vue cli项目初始化
1. 项目初始化之后只有简单的vue文件，添加eslint, vuex, router还需要再另外添加插件(vue add 命令)
2. vue初始化项目有几个方便好用的特性
	- 组件style标签上加scoped可以实现样式组件化；
	- 在router文件中用require()动态引入组件可以实现代码分块，延迟加载；
3. 添加jsconfig.json可对webpack的路径别名进行支持

### 移动端页面初始化
1. 引入reset.css样式，解决不用手机端的默认样式不一致问题；
2. 引入相关样式，解决移动端高倍屏(retina)边框宽度问题(声明为1px，可实际显示不是1px)；
3. 引入fastclick.js解决移动端点击事件触发有300s延迟的问题；

### 移动端插件
1. 滚动：betterScroll