# 制图

临时记录 ， 后期修改

## svg&canvas 
H5的新特性svg/canvas，用于在浏览器创建图形

### svg
SVG 是一种使用 XML 描述 2D 图形的语言。

SVG 基于 XML，这意味着 SVG DOM 中的每个元素都是可用的。您可以为某个元素附加 JavaScript 事件处理器。

在 SVG 中，每个被绘制的图形均被视为对象。如果 SVG 对象的属性发生变化，那么浏览器能够自动重现图形。

### canvas
Canvas 通过 JavaScript 来绘制 2D 图形。

Canvas 是逐像素进行渲染的。

在 canvas 中，一旦图形被绘制完成，它就不会继续得到浏览器的关注。如果其位置发生变化，那么整个场景也需要重新绘制，包括任何或许已被图形覆盖的对象。

### 特点
Canvas

生成的是位图

最适合图像密集型的游戏，其中的许多对象会被频繁重绘

SVG

生成的是矢量图

适合带有大型渲染的，如地图。不适合游戏应用

复杂度高会减慢渲染速度（任何过度使用 DOM 的应用都不快）


## ECharts

https://echarts.apache.org/examples/zh/index.html

https://www.runoob.com/echarts

涵盖各种图标，满足绝大部分展示数据需求

### 使用
1.引入配置文件

2.设置容器

3.挂载插件

4.绘制图标


参考文献：w3school，runoob，echarts
