[TOC]



## 禁用缩放

在移动设备浏览器上，通过为 **viewport meta** 标签添加 *user-scalable=no* 可以禁用其缩放（zooming）功能。

通常情况下，*maximum-scale=1.0* 与 user-scalable=no 一起使用。这样禁用缩放功能后，用户只能滚动屏幕，就能让您的网站看上去更像原生应用的感觉。

```
<meta name="viewport" content="width=device-width, 
                                     initial-scale=1.0, 
                                     maximum-scale=1.0, 
                                     user-scalable=no">
```

## 响应式图像

```
<img src="..." class="img-responsive" alt="响应式图像">
```

```
.img-responsive {
  display: block;
  height: auto;
  max-width: 100%;
}
```

## html引入css

```
<link href="jisuan.css" rel=”stylesheet” type=”text/css” />
```

# 书签

https://www.runoob.com/bootstrap/bootstrap-css-overview.html 全局显示、排版和链接

​																																													2021年4月13日, PM 07:45:20

------

