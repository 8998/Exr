### �ƶ���ʵ��Sprite����ͼ����Ӧ

> ѩ��ͼ���������ڶ�ʹ���˺ܶ�Сͼ�����վ�ϡ�����ڰ�ÿ��Сͼ����.png��ʽ�ļ�����ʽ���õ�ҳ���ϣ�ʹ��ѩ��ͼֻ��Ҫ����һ��ͼƬ�����ڴ�ʹ�������Ѻá�

#### ˵��
1. Demoʹ����JS�����REM��λ����Ƹ����640px*1136px��Ĭ�ϸ�����Ϊ100px����1rem=100px��
2. ͼƬ�ߴ�Ϊ72px * 632px��ÿ��Сͼ��Ŀ��Ϊ72px * 72px��ͼ����ͼ������¼����8px��
3. viewport������**width=device-width**��������Ƹ������2px�������ֻ��ϵ�1����������

### ʵ��
�����������PC��ʵ�ֹ�ѩ��ͼ����ô���֪��background-position���Կ��԰������Ƕ��屳����X��Y���λ��,
ͬ�������ƶ�����Ҳ����ʵ�֡�

``.icon {width:0.72rem;height:0.72rem;background: url("ico_collection.png") no-repeat;background-size:auto 6.32rem;}``

``.icon__foo{background-position: 0 -0.8rem;}``

``.icon__bar{background-position:  0 -1.6rem;}``

``.icon__baz{background-position: 0 -2.4rem;}``


***

background-size���Եĵ�һ��ֵΪͼƬ��ʹ��auto�Ϳ����ˣ��ڶ���ֵΪͼƬ�ߣ�����**����**��ͼƬ�߶ȡ�

background-position���Եĵڶ���ֵ�����óɶ�Ӧ��remֵ���ɡ�

