# MTCNN state-of-the-art face detection method

## 概述

[MTCNN](https://kpzhang93.github.io/MTCNN_face_detection_alignment/index.html)是[Kaipeng Zhang](https://kpzhang93.github.io/)等人提出的多任务级联卷积神经网络进行人脸检测的方法，是迄今为止开放源码的效果最好的人脸检测器之一，[在fddb上有100个误报时的检出率高达90%以上](https://github.com/imistyrain/fddb-windows)，作者提供的版本为[matlab版](https://github.com/kpzhang93/MTCNN_face_detection_alignment),它最终的效果如图所示：

![](https://i.imgur.com/FbglxoX.jpg)

## OpenCV版 C++

将本项目中的Fast-MTCNN设为启动项，安装opencv3.3及以上版本（3.2及以下版本需自行编译dnn库）

添加对应的头文件路径和库文件路径


## 参考

*  [MTCNN with all platforms](https://github.com/imistyrain/MTCNN)