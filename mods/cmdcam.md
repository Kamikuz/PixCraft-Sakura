# CMDcam <small>摄影MOD</small>

## 介绍

一款可以在MC里进行高级摄影的mod。

## 使用介绍

?>由于客户端里面可能有键位冲突，请自行设置按键！

按 <kbd>P</kbd> 添加一个关键帧.

按 <kbd>U</kbd> 开始动画 (默认为 **10** 秒)

`/cam add [number]` register a point at the current position

`/cam start <time|ms|s|m|h|d>` 使用设定的时间开始动画

`/cam clear` 删除所有的关键帧

`/cam goto <index>` 传送至所选关键帧

`/cam set <index>` 更新所选关键帧至目前位置

`/cam remove <index>` 删除所选关键帧

`/cam target <none:self>` 设置摄像头目标 *如果你留空,右键点击一个实体或者方块以设置目标*

`/cam mode <default:outside>` 设置动画模式

`/cam interpolation <linear,cosine,cubic,hermite>` 设置动画移动参数 默认是`hermite`
- linear 线性
- cosine 余弦
- cubic 立体
- hermite 矩阵

`/cam follow-speed <number>` 设置相机追踪(目标)速度, 默认速率`1.0`

按 <kbd>V</kbd> 放大, 按 <kbd>N</kbd> 缩小 and <kbd>B</kbd> 重置缩放

按 <kbd>G</kbd> 向左转, <kbd>J</kbd> 向右转 and <kbd>H</kbd> to 重置转动

`/cam show <all:linear,cosine,cubic,hermite>` 显示所加参数的动画路径

`/cam hide <all:linear,cosine,cubic,hermite>` 影藏所加参数的动画路径
