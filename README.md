关于ZOOM
=======

### 概要

> zoom CSS 属性会根据[@viewport](https://developer.mozilla.org/zh-CN/docs/Web/CSS/@viewport)来初始化一个缩放因数

> 当设置'zoom:1/100%'时表示不缩放。而设置'zoom:2/200%'时该标签则会放大为原来的两倍，反之亦然。

### 语法

```js
	
	/* Keyword value */
	zoom: auto;
	
	/* <number> values */
	zoom: 0.8;
	zoom: 2.0;
	
	/* <percentage> values */
	zoom: 150%;

```

#### 值

* auto - 根据viewport来既定当前标签的缩放
* <number> - 必须是一个非负数。1表示没有缩放，大于1表示放大的倍数，小于1依然。
* <percentage> - 必须是一个非负的百分比，以100%为基础进行缩放

### 形式语法

> auto | [<number>](https://developer.mozilla.org/zh-CN/docs/Web/CSS/number) | [<percentage>](https://developer.mozilla.org/zh-CN/docs/Web/CSS/percentage)

> 在平常的css编写过程中，zoom：1能够比较神奇的解决ie下比较奇葩的bug
> 譬如外边距（margin）的重叠，譬如浮动的清除，欺辱触发ie的haslayout属性等等。

未完待续。。。。
