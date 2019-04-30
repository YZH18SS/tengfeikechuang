## 一、

一开始做这个任务的时候想的是能不能单靠java实现全景图的制作，为此需要解决的问题主要有两个：

一是两张图片的任意拼接，即拼接位置的任意性；

二是获取像素值以进行复数图片的定位，即如何将大块像素相同的区域重合到一起,从而使系列图片能组合成一个整体

第一个问题的解决需要创建**Graphics**对象和建立**BufferedImage**，核心是createGraphics\(\)和drawImage\(\)，如此可将图片并到一起。第二个问题同样涉及**Graphics**对象和**BufferedImage**，可以通过getRgb\(\)获取图片各个像素的值再移位运算将rbg转为数字。但是一张图片中有很多像素值重复的区块，并且代码在运行过程中总是出现莫名其妙的问题，因此这个纯理论的想法没能实现。

## 二、

后来开始学习使用opencv，因为opencv开发大多使用c++\(其实我对c/c++和java的区别没有具体了解\)。用stitch类就很容易实现图片的拼接。现在还在学习java上的opencv使用

附上教程网站：[https://blog.csdn.net/haikuotiankong7?t=1](https://blog.csdn.net/haikuotiankong7?t=1)

[https://blog.csdn.net/luckyfairy17/article/details/81239356](https://blog.csdn.net/luckyfairy17/article/details/81239356)

