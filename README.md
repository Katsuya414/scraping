# scraping
## 作ったもの
 https://folio-sec.com/theme/<テーマ名>というURLになっているが
 そのテーマ名を入力として受け取り指定したテーマの銘柄一覧を見れるようにするサーバーアプリケーション

## 選択言語
Python

## 実際に構築した環境について
OS macOS ver 10.13.6

python version Python 2.7.15

追加ライブラリー requests, bs4

## 環境構築方法
Homebrewのインストール

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

pipのインストール
```
brew install python
```

追加ライブラリーのインストール
```
pip install requests
pip install bs4
```

## サーバアプリケーションを動かす方法
```
python2 scraping.py
```

実行結果の例

```
shimakatsuyanoMacBook-puro:kadai shimakatsuya$ python2 scraping.py
Please Enter theme: shibuya
ディー・エヌ・エー
パルコ
サイバーエージェント
ＧＭＯペイメントゲートウェイ
カカクコム
エービーシー・マート
ＧＭＯインターネット
インフォコム
東京急行電鉄
デジタルガレージ

shimakatsuyanoMacBook-puro:kadai shimakatsuya$ python2 scraping.py
Please Enter theme: virtual-reality
ソニー
クリーク・アンド・リバー社
カドカワ
エレコム
ＩＭＡＧＩＣＡ　ＧＲＯＵＰ
バンダイナムコＨＬＤＧ
カプコン
ディー・エヌ・エー
スクウェア・エニックスＨＬＤＧ
セガサミーＨＬＤＧ
```
