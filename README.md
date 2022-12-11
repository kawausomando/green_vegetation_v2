# green_vegetation_v2

## モデル
DeepLab v3 plus

## Deep Lab v3 plusの論文
https://arxiv.org/pdf/1802.02611.pdf

## 学習済みモデル
下記リンクの`xception65_cityscapes_trainfine`ってやつ
* https://github.com/tensorflow/models/blob/master/research/deeplab/g3doc/model_zoo.md#model-details-1

## データセット
* CityScape
https://www.cityscapes-dataset.comhttps://www.cityscapes-dataset.comhttps://www.cityscapes-dataset.com
* ImageNet
http://www.image-net.org/

## 実行手順

1. 以下コマンド実行
```
cd green_vegetation_v2
jupyter notebook
```
2. 上記コマンド実行後、表示されるリンクにブラウザでアクセス
3. imagesフォルダ以下にセグメントしたい画像を配置
4. DeepLab.ipynbを開く
5. 必要に応じて編集し、初めから実行。
