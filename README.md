# A Research Of Training Data Augmentation For Deep Learning

### This is the source code of my graduation thesis.

## About the code

- **generate_images.py**: It can generate 100 pieces of picture from one picture with doing some basic shift on it.
- **train.py**: It is a construction of CNN based on Keras. I used the construct of ResNet to create it. we can regard it as a simplify ResNet construction.It relates to the /keras-data-augmentation-res/pyimagesearch/resnet.py
- **classify.py**: It can test the model which has been trained. The test data was saved in the fold named example.

## training data

In this paper, I use the training data from < Kaggle: Dogs vs. Cats　dataset >. But I just usesd a part of it. If you want to learn more, please visit the URL: https://www.kaggle.com/c/dogs-vs-cats
 
 
---  
    

# 深層学習のための訓練データ拡張に関する研究

### これは私の卒業論文のソースコードである。

## コードについて

- **generate_images.py**：基本的なシフトを行うことで、1つの画像から100枚の画像を生成できる。
- **train.py**：Kerasに基づいたCNNの構築である。 ResNetのコンストラクトを使用して作成した。 これは、ResNetの簡単な構築と見なすことができる。/keras-data-augmentation-res/pyimagesearch/resnet.py　は一緒に構成するものである。
- **classify.py**：トレーニングされたモデルをテストできる。 テストデータは、exampleという名前のフォルダに保存された。

## トレーニングデータ

このペーパーでは、<Kaggle：Dogs vs. Cats dataset>のトレーニングデータを使用する。 しかし、私はその一部を使用した。 詳細については　https://www.kaggle.com/c/dogs-vs-cats　のURLにアクセスしてください。

---

# 关于深度学习中训练数据增广的研究

### 这是我毕业论文的源代码。

## 关于代码

- **generate_images.py**：这个文件可以从将1枚图像进行基本变换操作从而生成100枚图像。
- **train.py**：这是基于Keras构筑的CNN结构。其中借用了ResNet结构的思想。可以视作简单的ResNet结构。结构的另一部分在 /keras-data-augmentation-res/pyimagesearch/resnet.py 中。
- **classify.py**：可以对已经训练完成的模型进行测试。测试集存储在example文件夹中。

## 训练集

在本论文中， 我使用了< Kaggle: Dogs vs. Cats　dataset > 作为训练集。但是我只是使用了其中的一部分。想了解更多，请访问：https://www.kaggle.com/c/dogs-vs-cats

