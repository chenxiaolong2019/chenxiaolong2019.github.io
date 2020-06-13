---
layout: page
title: 索洛增长模型的推导
author: Chen
---
*参考资料 《西方经济学——宏观部分》第七版 高鸿业，《西方经济学 下册》马克思主义理论研究和建设工程*

## 基本假定与思路
新古典增长模型，也被称为索洛增长模型是建立在一个新古典生产方程体系之上，强调了一个封闭的没有政府部门的经济中储蓄、人口增长及技术进步对增长的作用，它关注的焦点是经济增长的直接原因。新古典增长模型的基本假定是：
> (1)经济由一个部门组成，该部门生产一种既可用于投资也可用于消费的商品

> (2)该经济为不存在国际贸易的**封闭经济**，且政府部门被忽略

> (3)**技术水平(z)既定**

> (3)生产的**规模报酬不变**,**Y=Z × F(K,N)**

>>说明: 
>> <img src="http://latex.codecogs.com/gif.latex?Y=Z\cdot F(K,N)"> 
>> 有<img src="http://latex.codecogs.com/gif.latex?aY=Z\cdot F(aK,aN)"> 令<img src="http://latex.codecogs.com/gif.latex?a=\frac{1}{N}"> 
>> <img src="http://latex.codecogs.com/gif.latex?Y\cdot \frac{1}{N}=Z\cdot F(K\cdot \frac{1}{N},N\cdot \frac{1}{N})"> 
>> <img src="http://latex.codecogs.com/gif.latex?y=z\cdot f(k,1)=zf(k)"> *k*为人均资本,人均收入是人均资本的函数

> (4)社会储蓄函数为S=ξY，ξ为储蓄率
>> 说明
>> <img src="http://latex.codecogs.com/gif.latex?s=\xi \cdot y=\xi \cdot zf(k)"> 
>> z不变则,<img src="http://latex.codecogs.com/gif.latex?\xi \cdot zf(k)=\xi \cdot f(k)"> 

>(5)人口是劳动力数,且人口增长率为常数n

>(6)资本折旧率δ为常数

## 人均收入与人均储蓄函数
由生产函数推导人均收入函数 *y=f(k)*<br>
由储蓄函数推导人均储蓄函数*S=sy=sf(k)*<br>
人均消费*c=y-S*<br>

### 人均收入与人均储蓄曲线

<center>
    <img src="http://chenxiaolong2019.github.io/ed/document/image/geogebra-export.png" style="zoom:20%"> 
</center>

> 稻田条件(Inada Conditions)<br>
1. y= f(k),f(0)=0 
2. <img src="http://latex.codecogs.com/gif.latex?\dot{f}(k)>0"> 斜率为正
3. <img src="http://latex.codecogs.com/gif.latex?f\ddot (k)<0"> 随着k的增加所带来的y的增量递减
4. <img src="http://latex.codecogs.com/gif.latex?\lim_{k \to 0}{\dot{f}(k)=\infty }"> 
5. <img src="http://latex.codecogs.com/gif.latex?\lim_{k \to \infty}{\dot{f}(k)=0 }"> 

## 索洛稳态增长条件（经济呈现一种收敛式的增长）
经济均衡时，由*C+S=Y=S+I* ，有<img src="http://latex.codecogs.com/gif.latex?I=S"> 
<img src="http://latex.codecogs.com/gif.latex?I=\Delta K+\delta K"> 
<img src="http://latex.codecogs.com/gif.latex?\Delta K=I=\delta K=sY-\delta K"> (I=S=sY)

<center>
    <img src="http://latex.codecogs.com/gif.latex?\frac{\Delta K}{N}=s\cdot \frac{Y}{N}-\delta \cdot \frac{K}{N}=sy-\delta k"> 
    <img src="http://latex.codecogs.com/gif.latex?\dot{k} = \dot{(\frac{K}{N})} =\dot{K} - \dot{N} =\frac{\delta K}{N}- \frac{\delta N}{N}"> 
    <img src="http://latex.codecogs.com/gif.latex?\frac{\Delta K}{N}=\frac{\Delta k}{k}\cdot \frac{K}{N}+n\cdot \frac{K}{N}=\Delta k+nk"> 
</center>

联立
<center>
    <img src="http://latex.codecogs.com/gif.latex?\frac{\Delta K}{N}=s\cdot \frac{Y}{N}-\delta \cdot \frac{K}{N}=sy-\delta k">
    <img src="http://latex.codecogs.com/gif.latex?\frac{\Delta K}{N}=\frac{\Delta k}{k}\cdot \frac{K}{N}+n\cdot \frac{K}{N}=\Delta k+nk"> 
</center>
得

<img src="http://latex.codecogs.com/gif.latex?\Delta k=sy-(n+\delta )k">
<img src="http://latex.codecogs.com/gif.latex?\Delta k=0">
<img src="http://latex.codecogs.com/gif.latex?sy=(n-\delta )k">
**Δk=sy-(n+δ)k** &#160;是人均资本增量的决定，Δk人均资本增量，sy人均储蓄，人均储蓄要满足资本折旧的需要sk，要为新增人口投资nk，剩下的余额必会导致人均资本的增加

Δk＞0，人均资本在增加，经济没有稳态增长。经济稳态增长，要求Δk=0，人均资本时常数，是收敛的，有<br>
<center><b>sy=(n+d)k<br>(经济稳态增长条件)</b></center>
