# Deep_stereo_brush---prd
项目需求文档（自用）：

## 行业背景
深度立体刷软件主要服务于单镜视频源（2D）生成立体视频（S3D）。从2010年《阿凡达》上映以来，3D成为技术革新的“引爆点”，如下图所示，2008-2012年期间，3D电影在北美院线的数量呈递增趋势，然而同样，我们也可以观察到，3D电影数量已从2016年的51部跌至2019年的35部，跌幅达32%。近年来，3D技术不再作为一个电影制作公司对于影视大作的必选项，如时代华纳公司，最近的一部3D大作可以追溯到2015年的《星球大战：原力觉醒》，3D电视行业同样收到了极大的打击。随着2013年4K，OLED等屏幕技术的问世，电视的3D功能作为一个逐渐趋于鸡肋化的功能也被更多的电视厂商抛弃。
![img](https://github.com/kabiyangyang/Deep_stereo_brush---prd/blob/main/img/截屏2021-08-17%2012.55.56.png)


## 痛点分析
1. __成本问题__ : 相对低廉的成本是转制3D比直拍3D更受片方青睐的决定性因素之一。这里所说的成本，同时包含了金钱和时间。不同于实机拍摄需要两台3D摄影机精确同步输出左、右眼各自对应的影像，转制3D利用的仍是2D视频素材，对拍摄精度相对要求较低，能够明显缩短拍摄用时，因此很多演员档期比较紧张的国产片都很依赖于这样的方式。市场上一部普通的2D转3D影片如果改用直拍3D制作，虽然视觉效果会大大提升，但成本也会相应扩大10倍以上。

2. __精度问题__:目前业内大多使用的是人工画图的方式,因为相较于传统的软件对影像资料进行蓝绿屏抠像、景深加深和画面合成，人工画图有更加直观的渲染和视觉提升。但是带来的问题就是人工画图的精度始终比不上直接的3D制作，主要技术难点在于人工渲染对于景深数据没有一个直观的感受。同时对于每一帧的3D渲染对于人工的时间和精力依旧是很大的考验。

3. __专业性问题__:3D技术之所欲无法普及（3D电视等技术），主要原因在于用户对于2D转3D软件背后的技术了解不够深刻，在片源方不再提供3D节目的情况下，普罗大众无法通过一些比较简易，轻松的操作自己制作一些具有3D效果的视频或电影，因此对于存在一定溢价的3D电视的需求量也变的越来越少。

4. __利润问题__: 在当前的内地影市中，2D和3D格式影片还存在着一定的票价差异。也就是说上座率相同的情况下，3D影片会相应得到更高的票房收益。基于此大环境下，诸多制作成本不高的小影视制造公司，也希望可以在3D电影市场分一杯羹，但依然受限于痛点 __1, 2, 3__，无法给自己带来实质性的利润提升。


## 用户分析 （TODO）
1.核心用户：电影，动漫行业制片方，公司广告，宣传部门等

2.次要用户：电影，游戏爱好者，追求及享受视觉冲击，愿意为自己感兴趣的游戏或电影使用该技术。

3.小众用户：数码科技爱好者，对科技前沿比较关注的用户。仅出于兴趣了解或测评等

4.负面用户：


## 需求分析
1. 基础需求

 |核心用户    | 次要用户    | 小众用户  |
 | :----:| :----: | :----: | 
| 2D视频读取   | 2D视频读取    | 2D视频读取 |   
 |读取视频展示  | 读取视频展示    | 读取视频展示|
 | 立体刷编辑视频 | 立体刷编辑视频 | 立体刷编辑视频|
 |立体刷粗细可调 | 立体刷粗细可调 | 立体刷粗细可调|
 |自定义深度值 | 自定义深度值 | 自定义深度值|
  |3D转换模块  | 3D转换模块   | 3D转换模块|
  |深度图展示 | 深度图展示 | 无|
  |帮助栏 | 帮助栏 | 帮助栏|
  |3D视频展示  | 3D视频展示   | 3D视频展示|
  |3D视频输出  | 3D视频输出  | 3D视频输出|
  
2. 优化需求

 | 核心用户    | 次要用户    | 小众用户  |
 | :----:| :----: | :----: | 
 深度曲线可拉动（类PS) | 深度曲线可拉动（类PS) | 深度曲线可拉动（类PS) 
 对象颜色可选 | 对象颜色可选 | 对象颜色可选 
 关键帧推荐 | 关键帧推荐 | 固定帧推荐 
 大内存视频分批加载 | 大内存视频分批加载 | 无
  
 
 3.兴奋需求
 
| 核心用户 | 次要用户 | 小众用户| 
 | :----:| :----: | :----: | 
 |多算法可调试|无|无|
 |精度提升参数可调|无|无|
 3D效果多方位展示 |3D效果多方位展示 |3D效果多方位展示
 
 
 
 
 
 
 
 




