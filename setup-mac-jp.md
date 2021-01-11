# Macのセットアップ

## ターミナルの起動

アプリケーション （Application） フォルダの中にあるターミナル （Terminal） をダブルクリックする。

## コマンドライン・デベロッパ・ツールのインストール

ターミナルに以下のコマンドを入力することで、コマンドライン・デベロッパ・ツールをインストールする

```
$ xcode-select --install
```

> **Tips**  `$` で始まっているのは、シェル（bashとか）での一般ユーザーが実行することを意味しています。

## Anacondaのインストール

Anacondaは、データサイエンスや機械学習のためのPythonおよびRのディストリビューションである。

Anacondaに含まれるパッケージ管理ツールcondaを使うことにより、簡単にソフトウェアのインストールを行うことができる。

1. https://www.anaconda.com/products/individual にアクセスする
2. 下の方にスクロールし、Windows、Mac、Linux用のインストーラーが並んでいるところまでページ内移動する
3. 使用するOSの欄から「64-Bit Graphical Installer」のダウンロードボタンをクリックして、インストーラーをダウンロードする
4. ダウンロードされた「拡張子が.dmgであるファイル」をダブルクリックし、インストーラーの指示に従ってインストールする
5. 以下のコマンドで、Anacondaをインストールしたことを確認する。

```
$ python --version
Python 3.7.6 :: Anaconda, Inc.
```

> **Tips**  上のコマンドで表示されるPythonのバージョンは違っていることもあります。

## Jupyter notebookまたはJupyter Labの起動

Anaconda をインストールすると、Jupyterのインストールされています。

Jupyter notebookの起動

```
$ jupyter notebook
```

Jupyter Labの起動

```
$ jupyter lab
```

