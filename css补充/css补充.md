# 渐变色

简介：

从一种颜色慢慢过渡到另外一种颜色。 `双色渐变`

在多种颜色中慢慢过渡。 `多色渐变`

语法：

```css
/* 
background: linear-gradient(hotpink,deepskyblue) ;
					
background 可以用于设置背景图，颜色，背景图位置...
linear-gradient() 渐变色					
linear-gradient(开始颜色,结束颜色)
linear-gradient(to 结束方向,开始颜色,结束颜色);
开始颜色在结束方向的对向，结束颜色则在结束方向的正向
linear-gradient(to 结束方向,开始颜色 与下个颜色开始位置(%),结束颜色 与下个颜色开始位置(%),...); 可以设置多个颜色渐变

渐变色的开始位置与下一个颜色之间的开始位置，形成渐变区域（颜色与颜色之间的过渡）
*/
background: linear-gradient(black,blue); /*默认渐变方向，从上至下*/
background: linear-gradient(to 目标方向,black,blue);
background: linear-gradient(to 目标方向,black 90%,blue 20%);
```

# 圆角

简介

- 与边有关系
- 将矩形的四个直角，进行弧度化，整个矩形最大不超过360度

属性

```css
border-radius:4个角;
border-radius:左上角+右下角 右上角+左下角;
border-radius:左上角 右上角 右下角 左下角;
```

属性详解

![image-20200416181033624](imgs\image-20200416181033624.png)

## 圆形

将圆角的弧度设置为height/2即可



1. 取height/2  px，则左右两边为半圆形
2. 直接设置为 50%，则为方圆或者椭圆



