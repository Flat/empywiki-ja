﻿# エムピリアン展開

## 依存関係
* Python 3  
* MongoDB  
* (任意信号) pip  

### Python
(pipをインストールと```pip install -r requirements.txt```を実行しますはPythonの依存関係をインストールします。)  

* Flask
* PyYaml
* python-magic
* uwsgi
* Pillow
* Flask-Security
* Flask-Admin
* Flask-SQLAlchemy
* Flask-MongoEngine
* Flask-CORS
* bcrypt

## 説明書  
(このページにアップデート中 http://blog.bob131.so/2015/02/24/deploying-empyrean-redux.html を読む下さい。（英語）)

[[コンフィグ|Configuration]]

[[ヤハウェの新しい設定|Yahweh#first-time-setup]]

## ディストリビューション特定説明書

### Debian 8と上

pymongoバージョン2.8の上が使いできません。

追加的な依存関係:

* ```python3-cffi```

pip使いなら:

* パッケージをインストール ```python3-pip```
* ```pip3 install -r requirements.txt``` を実行します 
* pymongoのバージョン2.8に下げる ```pip3 install pymongo==2.8```を実行します
