# これは何？
Python3個人練習用のリポジトリです。

# インストール（Mac向け）
[参考URL](#reference)
## HomeBrewをインストール
下記にアクセスしてインストールする。
http://brew.sh/index_ja.html

## Python3をインストール

### Python3とpip3をインストール
Python3がインストールされているか確認
`which python3` を実行して、
/usr/local/bin/python3 がかえってこれば既にインストールされているのでそのままでOKです。

/opt/anaconda/〜/python3
と表示される場合はanacondaがインストールされているので、anacondaを使わない場合はopt/anacondaディレクトリを削除してインストールし直すことを推奨します。

インストールされていなければ、
`brew install python3` を実行する。
pythonのバージョン管理システムpipがインストールされていることを確認する。
`which pip3` を実行して、
/usr/local/bin/pip3
と表示されれば既にインストールされているのでそのままでOKです。
インストールされていなければ、
`brew install pip3` を実行してインストールする。

### ライブラリたちをインストール
下記を実行する。
```
pip3 install numpy  # 線形代数
pip3 install scipy  # 数式処理
pip3 install matplotlib   # 描画
pip3 install pandas  # データ操作
pip3 install scikit-learn # 機械学習で使用するライブラリ
pip3 install chainer # ディープラーニングを扱う際に使う
pip3 install jupyter # python実行環境です。
```

# 起動
作業用ディレクトリ内で、`jupyter notebook`を実行してください。
デフォルトではブラウザでlocalhost:8888にてJupyter Notebookが立ち上がります。


<a id="reference"></a>
# 参考
https://play.kikagaku.co.jp/src/00_mac.html
