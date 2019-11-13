# 前端智能

## DEMO
- [风格迁移](https://allan5.com/FE-AI/style-transfer.html "风格转移")
> 抽取图像上的特征应用到其他图片
- [看图识花](https://allan5.com/FE-AI/flower.html "看图识花")
> 可识别的分类：雏菊、蒲公英、玫瑰、向日葵、郁金香
- [人脸检测](https://allan5.com/FE-AI/face-api.html "人脸检测")  ` 支持摄像头`
> 识别人脸、情绪、年龄
- [手部追踪](https://allan5.com/FE-AI/handtrack.html "手部追踪") 
> 识别人体手部
- [图像分类](https://allan5.com/FE-AI/mobilenet.html "图像分类")   ` 支持摄像头`
> 可识别的分类：https://github.com/tensorflow/tfjs-models/blob/master/mobilenet/src/imagenet_classes.ts
- [目标识别](https://allan5.com/FE-AI/object_detection.html "目标识别")    ` 支持摄像头`
> 可识别的目标：https://github.com/tensorflow/tfjs-models/blob/master/coco-ssd/src/classes.ts
- [人物分割](https://allan5.com/FE-AI/bodypix.html "人物分割")  ` 支持摄像头`
> 可识别人体轮廓
- [姿态检测](https://allan5.com/FE-AI/posenet.html "姿态检测")  ` 支持摄像头`
> 识别人体关键点


## Tips

- 在本地预览和调试，建议使用http-server: ` npm install http-server -g` 

- 为保持项目尽量简单易懂，暂未兼容多端和多数浏览器，请用chrome 70+测试访问。

- 为了保持每个DEMO都单独简单可用可读，未抽离梳理统一公用函数，未美化代码。

- 因为CN的特殊的网络环境，大部分模型已下载到本地，如发现示例改变参数后无法加载模型，请反馈。

