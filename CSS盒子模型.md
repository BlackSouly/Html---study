###盒子模型相关知识###

![1524397028795](E:\网页制作相关学习笔记\网页制作笔记\images\CSS盒子模型图1.png)

1. <div>标记：是一个区块容器标记，可以将网页分割为独立的，不同的部分，以实现网页的规划和布局，<div>与</div>之间相当于一个容器，可以容纳段落，标题，图像等各种网页信息。

- <div>是一个通用元素，主要用于布局,最大意义在于和浮动属性float配合，实现网页布局

2. 对盒子使用border-style进行单边设计时，必须按上右下左 的顺序，例如将上边设置为虚线，其他三边为单实线时，可以使用如下语句：

​       p{border-style:dashed solid solid solid;}

- 设置边框颜色时必须设置边框样式，若未设置样式或设置为none，则其他边框属性无效

3. padding属性：用于设置内边距，使用复合属性padding定义内边距时，必须按顺时针顺序采用值复制，一个值为四边，两个值为上下/左右，三个值为上/左右/下

- margin属性用于设置外边距，其关于属性的设置与padding相同
- CSS中，网页元素的背景颜色使用background-color属性来设置

4. 可以使用background-image属性来设置背景图像，例

`body{`

`background-color:#ccc;`

`background-image:url(images/****.jpg);`

`}`

- 设置背景图平铺：可以通过background-repeat属性来控制
- 使用background-position设置图像的位置
- 使用background-attachment属性设置背景图片是否随页面滚动条移动而滚动
- scroll:图像随页面一起滚动；
- fixed:图像固定在屏幕上





