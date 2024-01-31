## 概要
**VGG16_CrossValidation.ipynb**は、ラベルごとにフォルダ分けした画像データに対して、VGG16モデル（転移学習・ファインチューニング）により交差検証（k-Fold Cross Validation）を行うプログラムです。

## 動作環境
**Google Colabolatry**で動作します（2024.1.31現在）。

## 使い方
- **VGG16_CrossValidation.ipynb**を**Google Drive**に入れ、**Google Colabolatry**に読み込みます。
- プログラム中の
data_path = '/content/gdrive/My Drive/data/fracture'
output_path = '/content/gdrive/My Drive/data'
は適当に書き換えてください。<br>
上記のまま走らせるには、**data**フォルダおよびその下に **fracture**フォルダを作り、**fracture**フォルダの下にラベルごとにフォルダを作り、これらのフォルダに画像ファイルを格納してください。<br>
フォルダの作成例<br>

![フォルダ](https://github.com/repositoryfiles/VGG16_CrossValidation/assets/91704559/42beab24-2ea9-4907-8124-aa4c4870aac4)

## ご利用に関して
ご利用結果について当方は責任は負いません。
