# 关于深度学习中训练数据增广的研究
- [English](https://github.com/liuminxuan/keras-data-augmentation-res/blob/master/README_EN.md) 
- [Japanese](https://github.com/liuminxuan/keras-data-augmentation-res/blob/master/README_JP.md)
这是我毕业论文的源代码.

## 关于代码
generate_images.py：这个文件可以从将1枚图像进行基本变换操作从而生成100枚图像。
train.py：这是基于Keras构筑的CNN结构。其中借用了ResNet结构的思想。可以视作简单的ResNet结构。结构的另一部分在 /keras-data-augmentation-res/pyimagesearch/resnet.py 中。
classify.py：可以对已经训练完成的模型进行测试。测试集存储在example文件夹中。

## 训练集
在本论文中， 我使用了< Kaggle: Dogs vs. Cats　dataset > 作为训练集。但是我只是使用了其中的一部分。想了解更多，请访问：https://www.kaggle.com/c/dogs-vs-cats

## 使用许可
[MIT](https://choosealicense.com/licenses/mit/) © liuminxuan
