### JavaScript时间处理相关学习笔记###

JavaScript调用事件处理程序的两种方法：

1. 首先获得处理对象的引用，然后将要执行的处理函数赋值给对应的事件

```
<script type="text/javascript">
     var btn=document.getElementById("save");
     btn.onclick=function()
     {
         alert("真乖，居然点开了");
     }
</script>
```

2. 在HTML标签中添加相应的事件，并在其中执行要执行的代码或函数名

```
<input type="button" name="btn" value="点击按钮" onclick="alter('哈哈，又傻掉了');"/>
```

3. BOM是浏览器对象模型，提供一系列对象用于与浏览器窗口进行交互，BOM对象包括window（窗口），navigator（浏览器程序），screen（屏幕），location(地址)，history（历史）和document（文档）等对象。
4. window对象中，"window.open()用于打开新窗口"，"window.close()用于关闭窗口"。
5. 数据类型转化分为隐式类型转化和显式类型转化：隐式类型转化指程序运行时，系统根据当前需要，自动将数据从一种类型转化为另一种类型，例如window对象的alert（）方法，最终都转化为字符串类型。显式转化需要手动转化到目标类型


