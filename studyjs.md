# 复习JavaScript记录

* 那些老旧的实例可能会在 <script> 标签中使用 **type="text/javascript"**。现在已经不必这样做了。JavaScript 是**所有现代浏览器以及 HTML5 中的默认脚本语言**。

* 现在的JavaScript只需要这样：
```[javascript]
<script>
  alert("hello world");
<script>
```
## JavaScript用法

1. 页面加载时执行，即将JavaScript写入HTML的**body**标签中。

    这样在网页加载时便会执行JavaScript脚本。

2. 编写JavaScript函数，在事件发生时调用函数。
  
    比如点击按钮或是翻页等操作。

  * *在head标签中编写函数*

  * *在body标签中编写函数*
  
  * *在外部文件中编写函数*
  
## JavaScript输出

1. window.alert

    *可以弹出提示框*

2. document.write

    *将内容写入到HTML内容中*

3. innerHTML

    *写入到某一个HTML元素*
  
4. console.log()

    *写入到浏览器的控制台*
