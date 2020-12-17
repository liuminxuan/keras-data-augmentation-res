# 深層学習のための訓練データ拡張に関する研究


## コードについて

- **generate_images.py**：基本的なシフトを行うことで、1つの画像から100枚の画像を生成できます。
- **train.py**：Kerasに基づいたCNNの構築です。 ResNetのコンストラクトを使用して作成しました。 これは、ResNetの簡単な構築と見なすことができます。/keras-data-augmentation-res/pyimagesearch/resnet.py　は一緒に構成するものです。
- **classify.py**：トレーニングされたモデルをテストできます。 テストデータは、exampleという名前のフォルダに保存されました。

## 訓練データ

このペーパーでは、<Kaggle：Dogs vs. Cats dataset>のトレーニングデータを使用します。 しかし、私はその一部を使用しました。 詳細については下記のURLにアクセスしてください。　https://www.kaggle.com/c/dogs-vs-cats　

## 使用許可

[MIT](https://choosealicense.com/licenses/mit/) © liuminxuan
