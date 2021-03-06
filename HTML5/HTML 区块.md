# 区块

|标签|描述|
|--|--|
|\<div>|定义文档的区域，块级(block-level)|
|\<span>|用来组合文档中的行内元素，内联元素(line)|

### 区块元素

+ 块级元素在浏览器显示时，通常会以新行来开始（和结束）。如：\<h1>, \<p>, \<ul>, \<table>

### 内联元素

+ 内联元素在显示时通常不会以新行开始。如: \<b>, \<td>, \<a>, \<img>

### \<div> 元素

+ HTML \<div> 元素是块级元素，它可用于组合其他 HTML 元素的容器。

+ \<div> 元素没有特定的含义。除此之外，由于它属于块级元素，浏览器会在其前后显示折行。

+ 如果与 CSS 一同使用，\<div> 元素可用于对大的内容块设置样式属性。

+ \<div> 元素的另一个常见的用途是文档布局。它取代了使用表格定义布局的老式方法。

### \<span> 元素

+ HTML \<span> 元素是内联元素，可用作文本的容器

+ \<span> 元素也没有特定的含义。

+ 当与 CSS 一同使用时，\<span> 元素可用于为部分文本设置样式属性。

实例：

```(html)
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>菜鸟教程(runoob.com)</title>
</head>
<body>

<div id="container" style="width:500px">

<div id="header" style="background-color:#FFA500;">
<h1 style="margin-bottom:0;">主要的网页标题</h1></div>

<div id="menu" style="background-color:#FFD700;height:200px;width:100px;float:left;">
<b>菜单</b><br>
HTML<br>
CSS<br>
JavaScript</div>

<div id="content" style="background-color:#EEEEEE;height:200px;width:400px;float:left;">
内容在这里</div>

<div id="footer" style="background-color:#FFA500;clear:both;text-align:center;">
版权 © runoob.com</div>

</div>

</body>
</html>
```
