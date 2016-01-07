### 移动端实现Sprite背景图自适应

> 雪碧图被运用在众多使用了很多小图标的网站上。相对于把每张小图标以.png格式文件的形式引用到页面上，使用雪碧图只需要引用一张图片，对内存和带宽更加友好。

#### 说明
1. Demo使用了JS计算出REM单位，设计稿采用640px*1136px，默认根字体为100px，即1rem=100px。
2. 图片尺寸为72px * 632px，每个小图标的宽高为36px * 36px，图标与图标的上下间距有4px。
    #### 如图：
![spriteIMG](./ico_collection.png)

### 实现
如果你曾经在PC上实现过雪碧图，那么你就知道background-position属性可以帮助我们定义背景的X、Y轴的位置,
同样，在移动端中也可以实现。

`.item:first-child:after {
 	content:'';
 	width:0.36rem;
 	height:0.36rem;
 	position:absolute;
 	top:0.04rem;
 	left:0.2rem;
 	background:url("ico_collection.png") no-repeat 0 0;
 	/*background-size:auto 6.32rem;*/
 	background-size:auto 3.16rem;
 } `





