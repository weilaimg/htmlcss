# Html/Css 布局摘要

## 全局定义

```css
margin:0
padding:0
font-size:12px
```

定义边距及字号

## body标签

```css
background-color:#F5F5F5
```

定义网页整体背景色

## background属性

当设置背景为图片时，可用

```css
background: url(../images/top_bg.jpg) repeat-x;
```

使图片正确加载并在x轴平铺

```css
background: url(../images/search.jpg) no-repeat right center;
```

靠右居中

## ul>li

修改无序表开头符号：

```css
list-style-image: url(../images/li_bg.gif);
```

去除无序表开头符号：

```css
list-style-type: none;
```

若要设置垂直居中，可以先设置行高，

```css
line-height: 40px;
```

再上下padding auto(可省略)

```css
padding: auto;
```



## a标签

### a:link -> 链接的初始状态

### a:visited -> 链接点击后的状态

### a:hover -> 鼠标在链接上的状态

### a:active -> 鼠标点击时的状态

## img标签

设置垂直居中

```css
vertical-align: middle;
```

