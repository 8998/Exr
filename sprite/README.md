### �ƶ���ʵ��Sprite����ͼ����Ӧ

> ѩ��ͼ���������ڶ�ʹ���˺ܶ�Сͼ�����վ�ϡ�����ڰ�ÿ��Сͼ����.png��ʽ�ļ�����ʽ���õ�ҳ���ϣ�ʹ��ѩ��ͼֻ��Ҫ����һ��ͼƬ�����ڴ�ʹ�������Ѻá�

#### ˵��
1. Demoʹ����JS�����REM��λ����Ƹ����640px*1136px��Ĭ�ϸ�����Ϊ100px����1rem=100px��
2. ͼƬ�ߴ�Ϊ72px * 632px��ÿ��Сͼ��Ŀ��Ϊ36px * 36px��ͼ����ͼ������¼����4px��
    #### ��ͼ��
![spriteIMG](./ico_collection.png)

### ʵ��
�����������PC��ʵ�ֹ�ѩ��ͼ����ô���֪��background-position���Կ��԰������Ƕ��屳����X��Y���λ��,
ͬ�������ƶ�����Ҳ����ʵ�֡�

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





