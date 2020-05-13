## UniApp+ColorUI开发模板

### 创建UniApp模板项目

在点击工具栏里的文件 -> 新建 -> 项目：

<img src="http://ww1.sinaimg.cn/large/006DFWgBgy1geqjql0w9ej30hi09wt99.jpg" alt="create1.png" style="zoom: 80%;" />

选择`uni-app`类型，输入工程名，选择模板，点击创建，即可成功创建。

uni-app自带的模板有 Hello uni-app ，是官方的组件和API示例。还有一个重要模板是 uni ui项目模板，日常开发推荐使用该模板，已内置大量常用组件。

<img src="http://ww1.sinaimg.cn/large/006DFWgBgy1geqjy8f724j30nc0hsdgf.jpg" alt="16500b76169e55d3349899cfc5915ed.png" style="zoom: 80%;" />

### 引入ColorUI文件

下载源码解压获得`/Colorui-UniApp`文件夹，复制目录下的 `/colorui` 文件夹到你的项目根目录

App.vue` 引入关键Css `main.css` `icon.css

```
<style>
@import "colorui/main.css";
@import "colorui/icon.css";
@import "app.css"; /* 你的项目css */
....
</style>
```

