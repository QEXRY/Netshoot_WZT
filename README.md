# Netshoot

腾讯游戏客户端公开课作业使用项目。

提出样例项目中的一个bug，玩家在死亡重生后所在的位置不在原来的位置，这是定位玩家变换失败导致的，具体可以修改蓝图类**MyGameMode**里的**RespawnPlayerEvent**事件的结尾部分：
<img src="https://my-notion-blog-blue.vercel.app/_next/image?url=https%3A%2F%2Fs3.us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fd21c3f65-59d4-4277-8ffa-416392184d2e%2F%25E5%258F%25AA%25E7%258B%25BC.jpg%3FX-Amz-Algorithm%3DAWS4-HMAC-SHA256%26X-Amz-Content-Sha256%3DUNSIGNED-PAYLOAD%26X-Amz-Credential%3DAKIAT73L2G45EIPT3X45%252F20220729%252Fus-west-2%252Fs3%252Faws4_request%26X-Amz-Date%3D20220729T084057Z%26X-Amz-Expires%3D86400%26X-Amz-Signature%3D9d2fb082818f0cb4ad9251bc04da27b4834b594c930c3b0e84838962674c4b3a%26X-Amz-SignedHeaders%3Dhost%26x-id%3DGetObject&w=3840&q=75">
此处的应该由Get第1个元素改为第0个元素，即可让玩家在死亡后重生在正确的位置。

## 第二次课作业演示视频

链接：<https://pan.baidu.com/s/1LYcgD9y1XfO4uOdlbi6-Tg>
提取码：xqkz
