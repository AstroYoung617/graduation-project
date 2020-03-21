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
    
    **JavaScript 中，常见的是驼峰法的命名规则，如 lastName (而不是lastname)。** 
    
## JavaScript语法
    
1. JavaScript是一种弱类型的语言但是**对大小写非常敏感**，所以都使用var来定义不同的数据类型，例如：数字、字符串、数组、对象等。

2. JavaScript函数：
    
```
    function myFunction(a, b) {
   	return a * b;                                // 返回 a 乘以 b 的结果
}
```

3. JavaScript使用Unicode字符集。

## JavaScript语句

1. JavaScript语句是JavaScript发给HTML的命令：
    可以使用代码块，即让代码块中的代码一并执行。
    
```
    function myFunction()
{
    document.getElementById("demo").innerHTML="你好Dolly";
    document.getElementById("myDIV").innerHTML="你最近怎么样?";
}
```

2. 可以在文本字符串中使用反斜杠对代码行进行换行。

```
document.write("你好 \
世界!");
```

*JavaScript是脚本语言，所以在执行时是一步一步执行的，不同于一般的编程语言，不需要将全部的代码编译后再执行。*


## JavaScript注释

1. 单行注释以 **//** 开头

2. 多行注释以 /* 开始，以 */ 结尾。

## JavaScript数据类型

1. 值类型(基本类型)：字符串（String）、数字(Number)、布尔(Boolean)、对空（Null）、未定义（Undefined）、Symbol。

2. 引用数据类型：对象(Object)、数组(Array)、函数(Function)。

    （**JavaScript 拥有动态类型**）
    
  ### JavaScript 字符串
  
  用于存储字符，可以用单引号也可以用双引号。
  
  ### JavaScript 数组
  
```
  var cars=new Array();
  cars[0]="Saab";
  cars[1]="Volvo";
  cars[2]="BMW";
```

  ### JavaScript 对象
  
  1. 对象由花括号分隔。在括号内部，对象的属性以名称和值对的形式 (name : value) 来定义。属性由逗号分隔：

```
  var person={firstname:"John", lastname:"Doe", id:5566};
```

  2. 对象的寻址：
  
  ```
  name=person.lastname;
  name=person["lastname"];
  ```
  
  3. javascript对象是键值对的容器即：name：value
