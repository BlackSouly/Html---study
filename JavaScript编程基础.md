### JavaScript编程基础###

1. 在HTML中引入JavaScript方法有两种：内嵌式：在HTML中直接嵌入JavaScript脚本。

   ​                                                                   外链式：链接外部JavaScript脚本

- 内嵌式：通过<script>标签及相关属性引入JavaScript代码，例：

```Java Script
<head>
<script type="text/javascript">
//此处为JavaScript代码
</script>
</head>
```

- 注意JavaScript的关键字，即保留字

2. 变量的声明与赋值

var 变量名

3. prompt()函数：用于显示和提示用户输入信息对话框

`windows.prompt(提示信息字符串，默认输入值);`

4. alter()函数:alter()括号内的文本信息用于显示在警示对话框中

`windows.alter("hellow world");`

5. console.log()函数：用于标准输出流的输出
6. 函数使用关键字function来定义，格式如下：

```
<script type="text/javascript">
function 函数名 ([参数1，参数2，参数3……]){
   函数体
}
</script>
```

- 函数需要按一定要求调用才可在页面显示

7. Array数组对象

在JavaScript中，使用内置对象类Array可以创建数组对象，语法如下

```
var arrayname=new Array();
var arrayname=new Array(n);
var arrayname=new Array(元素1，元素2……);
```

8. for ……in……语句

处理与数组和对象相关的循环

9. 数组对象常用属性和方法：

| 属性/方法  |             说明             |
| :--------: | :--------------------------: |
|   length   |      返回数组中元素个数      |
| toString() | 返回字符串，包含数组所有元素 |

10. DOM节点树

> 文档对象模型，表示和处理文档应用程序接口，可用于动态访问，更新文档，构成等级关系

- 元素对象常用操作

```
var h1=document.createElement("h1");                   //创建一个<h1>元素节点
var text=document.createTextNode("Hellow");            //创建一个文本节点
h1.appendChild(text);                                  //为<h1>元素追加文本节点
```

11. JavaScript采用弱类型方式，数据可以不事先声明，在使用或赋值时再说明其数据类型

- 单引号可括起一个或多个字符

