### 移动端实现Sprite背景图自适应

> 雪碧图被运用在众多使用了很多小图标的网站上。相对于把每张小图标以.png格式文件的形式引用到页面上，使用雪碧图只需要引用一张图片，对内存和带宽更加友好。

#### 说明
1. Demo使用了JS计算出REM单位，设计稿采用640px*1136px，默认根字体为100px，即1rem=100px。
2. 图片尺寸为72px * 632px，每个小图标的宽高为72px * 72px，图标与图标的上下间距有8px。
3. viewport被设置**width=device-width**，所以设计稿里面的2px，等于手机上的1个物理像素

### 实现
如果你曾经在PC上实现过雪碧图，那么你就知道background-position属性可以帮助我们定义背景的X、Y轴的位置,
同样，在移动端中也可以实现。

``.icon {width:0.72rem;height:0.72rem;background: url("ico_collection.png") no-repeat;background-size:auto 6.32rem;}``

``.icon__foo{background-position: 0 -0.8rem;}``

``.icon__bar{background-position:  0 -1.6rem;}``

``.icon__baz{background-position: 0 -2.4rem;}``


***

background-size属性的第一个值为图片宽，使用auto就可以了，第二个值为图片高，这里**必须**是图片高度。

background-position属性的第二个值在设置成对应的rem值即可。

