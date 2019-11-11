# 前端智能

## DEMO

- [看图识花](http://allan5.com/FE-AI/flower.html "看图识花")
> 可识别的分类：雏菊、蒲公英、玫瑰、向日葵、郁金香
- [人脸检测](http://allan5.com/FE-AI/face-api.html "人脸检测") ` 支持摄像头`
> 识别人脸、情绪、年龄
- [手部追踪](http://allan5.com/FE-AI/handtrack.html "手部追踪") 
> 识别人体手部
- [图像分类](http://allan5.com/FE-AI/mobilenet.html "图像分类") ` 支持摄像头`
> 可识别的分类：https://github.com/tensorflow/tfjs-models/blob/master/mobilenet/src/imagenet_classes.ts
- [目标识别](http://allan5.com/FE-AI/object_detection.html "目标识别")    ` 支持摄像头`
> 可识别的目标：https://github.com/tensorflow/tfjs-models/blob/master/coco-ssd/src/classes.ts
- [人物分割](http://allan5.com/FE-AI/bodypix.html "人物分割")  ` 支持摄像头`
> 可识别人体轮廓
- [姿态检测](http://allan5.com/FE-AI/posenet.html "姿态检测")  ` 支持摄像头`
> 识别人体关键点


## Tips

- 在本地预览和调试，建议使用http-server: ` npm install http-server -g` 

- 为保持项目尽量简单易懂，暂未兼容多端和多数浏览器，请用chrome 70+测试访问。

- 为了保持每个DEMO都单独简单可用可读，未抽离梳理统一公用函数

- tfjs有些官方模型暂不支持自定义模型的地址，需要访问外网。已给官方提[issue](https://github.com/tensorflow/tfjs/issues/2338)，等待官方修复。


