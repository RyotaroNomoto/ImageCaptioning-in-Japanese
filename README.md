# 画像キャプション自動生成モデルのチュートリアル（コードも動くかわかりません。日々更新しています。）
Pytorchを利用した画像キャプション自動生成モデルのチュートリアルです。
エンコーダにCLIP(ViT)を、デコーダにTransformerのデコーダ部を利用したモデルとなっています。
流れは以下のようになっています。
* data.ipynb
  * モデルの構築・学習・推論に使用するデータの準備
* main.ipynb
  * データの前処理
  * モデルの構築・学習・推論と評価

本モデルの学習には、[STAIR Captions](https://github.com/STAIR-Lab-CIT/STAIR-captions)を使用しています。

## インストール
```
$ pip install json
$ pip install io
```
# To Do
* Mecabのダウンロード
* fasttextのダウンロード
* モジュールのバージョン(更新版はおいおい作る)
