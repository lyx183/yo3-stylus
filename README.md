# yo3-stylus

## 介绍
```
-在移动端项目开发过程中使用的是stylus编写的样式文件
-但是在编写一些有兼容性问题的样式时，比如一像素边框，css3的一些特性书写起来非常复杂
-在以往的项目中使用的是yo3移动前端开发框架，yo3专注为移动应用提供快速且专业的构建方式
-但是yo3的样式是使用scss编写，（Sass、LESS和Stylus是众多优秀的CSS预处理器语言中最优秀的）
-虽然stylus和scss大体差距不大，stylus也可以使用scss的一些语法，但是为了以后更好的使用stylus兼容解决方案
-于是将一些yo3框架的一些兼容性方案的底层scss代码提取出来改造并封装成了stylus文件，这样在项目中引入后便可愉快地进行编码
```
## 各文件的功能及原理

### border.styl
```
  -此文件封装了边框的样式，可用于解决一像素的边框在不同dpr设备上的显示粗细问题
  -使用方法举例
    -border 1px 0 0 0, #ccc
```

### ellipsis.styl
```
  -此文件封装了单行或多行文字溢出时显示省略号
  -使用方法举例
    -单行文字溢出 ellipsis()
    -多行文字溢出 ellipsis(n)
```

### reset.styl
```
  -此文件是yo3框架的样式重置文件
```


## 持续更新中。。。