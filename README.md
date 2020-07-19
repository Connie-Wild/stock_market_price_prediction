# 機械学習による株式価格予測
CNN+LSTMを利用して、米国株式の予測モデルを作成する。

## 実行環境
Windows10(1909)+GTX980  
python 3.6.8  
TensorFlow 2.2.0  
TensorFlowでGPUを利用するための環境構築方法は[こちら](https://qiita.com/ConnieWild/items/2a6f7698506bee32441a)を参考にどうぞ  

## 必要なモジュールインストール
```bash
pip install -U pip
pip install -U -r requirements.txt
```

## ファイル
・`jupyterlab.bat` : jupyterを起動  
・`stock_cnn+lstm.ipynb` : 今回のノートブック  
