# refactoring-the-d2l-neural-style-code

《动手学深度学习》： https://github.com/d2l-ai/d2l-zh

我学习使用的代码是从 https://D2L.ai 下载到的jupyter notebook（pytorch版），参考了李沐老师在bilibili的视频
https://www.bilibili.com/video/BV1Eh41167GN/?spm_id_from=333.999.0.0&vd_source=387b6dd8c8fe08b91f4f45e6eabf1ea8

## 介绍

重构 d2l jupyter notebook 的 chapter_computer-vision/neural-style.ipynb

---
【注】使用此仓库代码，需要自己去下载vgg19-dcbb9e9d.pth

https://download.pytorch.org/models/vgg19-dcbb9e9d.pth

---

课程中，想要让 rainier.jpg 学习到 autumn-oak.jpg 的风格。

使用了vgg19提取内容层特征、风格层特征：

 