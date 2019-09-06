# Hellfire

DeepLearningの実験を管理するためのシステムと，
その操作のためのコマンドラインスクリプト．

*特徴*
- 実験結果，プログラム，データセットの場所を設定ファイルで管理する．
    - それぞれのサーバーで設定ファイルを準備しておくことで同じ様に実験することが可能．
- 実験設定も設定ファイルで管理する．
    - 設定ファイルの内容から様々なモジュールの動的importをする．疎な結合．一度作成したモジュールの書き変えをなるべく減らし，利用できるようになるため実験結果の再現が容易．
- (TODO)実験結果の状況を確認して途中から実行をできるようにする．
- 自由に改変可能なサンプルプログラムを用意
- (TODO)ユーティリティ関数を用意

## インストール
```
pip install git+https://github.com/yuuho/Hellfire
```

## アンインストール
```
pip uninstall hellfire
```

## アップグレード
```
pip install git+https://github.com/yuuho/Hellfire -U
```

## サブコマンド
``hellfire``の後に続けて使う
- ``train`` : 学習システムの起動
- ``doctor`` : hellfire環境のチェック


## ドキュメント
[document](.doc/index.md)
