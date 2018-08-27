# 为什么要用<!DOCTYPE>声明 html 文档

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>

</body>
</html>
```

答：为了使浏览器明白要使用哪一种规范来解释 html 文档，如果没有此标记，浏览器则会以`怪异模式`渲染页面，各个浏览器在怪异模式下对元素的渲染效果和标准模式有差异，会使得同一个样式在两种模式下的表现效果不同。例如 ie 浏览器的两种模式下盒模型的计算方式不同。

# 如何理解 html5 标签的语义化

答：传统网页布局一般采用 div+css 的方式，但此种方式会使得 html 代码结构不够清晰，而且也不利于搜索引擎爬虫抓取，所以在 html5 标准中引入了一批新的标签元素来解决这些问题。这些标签拥有更加丰富的含义，方便开发和维护，搜索引擎可以更加容易得识别页面各个区域代表的含义，对有阅读障碍的人士友好，例如屏幕阅读器。常见的新增标签有：

```html
<article>、<section>、<nav>、<aside>、<header>、<footer>
```

# 浏览器内核组成

浏览器的内核一般由渲染引擎和 javascript 引擎组成。不同的浏览器的渲染引擎和 javascript 引擎都可能不同。以 chrome 浏览器为例，其渲染引擎为 webkit，javascript 引擎为 v8。
