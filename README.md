# Material Silde

这里是一个使用`mdui`制作Material Design的幻灯片的项目

这里是[Demo](https://enter-tainer.github.io/MaterialSlide/)

## 使用方法

1. 克隆/下载本项目

2. 在`<div class="mdui-container">`中写自己的内容，类似于
``` html
<div class="mdui-container">
    <!--以下是第一张-->
    <div style="height: 94px" id="p1"></div> <!--防止标题栏遮挡内容-->
    <!--Your content here-->
    <div style="height: 1000px"></div> <!--占位-->


    <!--以下是第二张-->
    <div style="height: 94px" id="p2"></div> <!--防止标题栏遮挡内容-->
    <!--Your content here-->
    <div style="height: 1000px"></div> <!--占位-->


    <!--以下是第三张-->
    <div style="height: 94px" id="p3"></div> <!--防止标题栏遮挡内容-->
    <!--Your content here-->
    <div style="height: 1000px"></div> <!--占位-->
</div>
```

可以使用右下角的浮动按钮进行页面切换

祝使用愉快