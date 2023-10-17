# ImageClassification
#### いくつかの画像を比較して、類似する系統ごとにまとめる画像クラスタリングを実装します。

## TODO

#### 画像の特徴量抽出
事前学習済みモデルを用いて、入力画像から特徴ベクトルを取得する。

#### x-meansによる画像クラスタリング
複数の特徴ベクトルを、いくつかのクラスタに分類する。

### 参考
torchvision の事前学習済みモデルMobilenetV3で入力画像の特徴量を抽出<br>
https://www.system-server.com/wp/blog/441/

X-meansで画像の特徴量をクラスタリングし、画像を分類する<br>
https://pystyle.info/pytorch-how-to-use-pretrained-model/