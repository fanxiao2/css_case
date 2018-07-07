[TOC]

# CSS 使用

## 文本样式

### font-family用法(指定元素字体)
* 字体系列：特定的字体系列（如Times New Roman或Arial）
* 通用族：一组具有相似外观的字体族（如Serif或Monospace）

### font-size用法（设置字体大小）常见属性值：
* xx-small
* small
* medium
* large
* larger
* 等等...  当然，也别忽略了像素（px）和单位(em) 字体大小也是可以通过单位属性来设置的

### font-style用法 （指定斜体文本）常用属性值：

* normal
* italic
* oblique

### font-weight用法 （设置文本字体粗细）常用属性值：

* normal (默认)
* bold
* bolder
* lighter
* 也可以使用 100-900 区间的值来设定想要的字体大小 400 相当于 normal 700 相当于 bold 

### font-variant用法 （设置转换所有大小写字母）常用属性值：

* normal
* small-caps
* inherit 

### color 用法 （设置文本颜色）常用属性颇多：

* red
* blue
* green
* #ffffff
* #009220

### text-align 用法 （设置文本水平对齐方式） 常用属性值：

* left
* right
* center
* justify

### vertical-aling (设置垂直对齐) 常用属性值：

* top
* middle
* bottom
* baseline
* sub
* super
* %
* px
* pt或（cm）

### text-decoration 用法 （制定文本的装饰方法）常用属性值：

* none
* inherit
* overline
* underline
* line-through
* blink (是文字闪烁，貌似很多浏览器已经弃用！)

### text-indent 用法 （文本缩进）

* 80px

### text-shadow 用法 （添加文本阴影）常用属性值：

* 第一个值：定义阴影在x（水平）方向的距离
* 第二个值：定义y（垂直）方向的距离
* 第三个值：定义阴影的模糊
* 第四个值：设置颜色