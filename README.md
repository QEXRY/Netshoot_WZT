# Netshoot

腾讯游戏客户端公开课作业使用项目。

提出样例项目中的一个bug，玩家在死亡重生后所在的位置不在原来的位置，这是定位玩家变换失败导致的，具体可以修改蓝图类**MyGameMode**里的**RespawnPlayerEvent**事件的结尾部分：
<img src="https://wx3.sinaimg.cn/mw2000/006Kvkl5ly1h4nwbuaaodj30qg0f7gs5.jpg">
此处的应该由Get第1个元素改为第0个元素，即可让玩家在死亡后重生在正确的位置。

## 第二次课作业演示视频

链接：<https://pan.baidu.com/s/1LYcgD9y1XfO4uOdlbi6-Tg>
提取码：xqkz
