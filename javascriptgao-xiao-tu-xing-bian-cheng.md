# JavaScript高效图形编程

# 0. 总结

这里的demo很多...

不过不知道代码在哪里可以下,运行执行的效果可能会好很多

大篇幅的代码...感觉有点烦躁

这本书比较有用的是前几章教别人使用CSS DOM和canvas...

总页数232 评价(2.5)

# 1. 代码的重用和优化

一些比较基本的css,dom优化

# 2. DHTML基础

距离了一个控制CSS的案例

# 3. 滚动

操作DOM使动画...

感觉这样的应该要淘汰了吧

# 4. 高级UI

旋转木马......

# 5. JavaScript游戏介绍

### 5.2.5 碰撞检测

对页面计切成成方格

只对周围方格的对象进行检测

# 6. HTML5画布

### 6.7.4 绘制直线好曲线

1. beginPath(): 开始新路径
2. moveTo(x, y): 设置路径的起始位置
3. LineTo(x, y): 定义从当前位置开始的直线
4. arc(x, y, 圆半径, 起始角度, 结束角度, 绘制弧线的方向): 定义弧
5. arcrTo(x1, y1, x2, y2, 弧度): 定义从当前位置开始的弧,方便制作直线之间的圆角
6. quadraticCureTo: 定义从当前位置开始的二次曲线
7. bezierCurveTo: 定义从当前位置开始的贝塞尔曲线
8. closePath: 结束路径
9. stroke: 勾画路径
10. fill: 填充颜色,会自动执行closePath命令

`to`是命令(LineTo, bezierCurveTo) ,to命令的结束位置也定义了下一个to的开始位置,可以把to想象成在纸上连续地画线

而moveTo就是领你将笔离开纸面,从其他地方重新开始画

### 6.7.5 绘制位图图像

drawImage函数可以载入图像,img标签,canvas标签或video便签

api:

1. drawImage(source,x, y): 简单的把图片源复制到画布的(x,y)
2. drawImage(source,x, y, width, height): 在1的基础上 缩放图像到所需大小
3. drawImage(source, sx, sy, swidth, sheight, x, y, width, height): 2~5参数制定源图像中的源矩形块,6~9绘制画布上的目标

drawImage在FF或Opera 绘制小数点的像素位置,会导致严重的性能损失

最好先 Math.floor(x) 或 (x>>0)


# 7. 游戏和模拟中的向量

# 8. 谷歌可视化

国人喜欢echart

# 9. 使用jquery mobile为移动设备开发

# 10. PhoneGap创建Android应用


