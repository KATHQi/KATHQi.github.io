[TOC]

# 摘要
本项目从基于计算机视觉的机器学习出发，实现了对几种特定手势的识别，并通过从摄像头视频采集到的手势来实现对游戏的控制。机器学习部分利用HOG特征提取方法结合SVM进行模型训练，得到的模型在测试集上得到91%的准确率。利用模型识别手势前对采集图像进行预处理，利用人体皮肤特征对感兴趣区域进行提取最终分离手臂，使得模型在最大程度上识别稳定。游戏部分使用objective-c 与c++混编，利用cocos2d游戏引擎，box2d物理引擎，openGL ES工具，json读入游戏信息。<br>
<b>关键字:</b>机器学习，HOG，SVM，计算机视觉，图像处理

## 数据集
<img src='https://github.com/KATHQi/KATHQi.github.io/blob/main/Game1/img/1.png'>

## HOG+SVM流程
<img src='https://github.com/KATHQi/KATHQi.github.io/blob/main/Game1/img/3.png'>
<img src='https://github.com/KATHQi/KATHQi.github.io/blob/main/Game1/img/4.png'>
## 手势识别流程

<img src='https://github.com/KATHQi/KATHQi.github.io/blob/main/Game1/img/5.png'>
<img src='https://github.com/KATHQi/KATHQi.github.io/blob/main/Game1/img/6.png'>
<img src='https://github.com/KATHQi/KATHQi.github.io/blob/main/Game1/img/7.png'>
复杂环境下的识别效果
<img src='https://github.com/KATHQi/KATHQi.github.io/blob/main/Game1/img/8.png'>

## 游戏demo演示
<!-- <iframe src="//player.bilibili.com/player.html?aid=206394245&bvid=BV1Mh411h7nz&cid=361851491&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe> -->
<div style="position: relative; padding: 30% 45%;">
<iframe src="https://www.bilibili.com/video/BV1Mh411h7nz?share_source=copy_web" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;"> </iframe>



