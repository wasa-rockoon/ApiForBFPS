# ティー&#257;ウィリム&#257;ティー

[![ドキュメントの現状]](https://readthedocs.org/projects/tawhiri/badge/?version=latest)](https://readthedocs.org/projects/tawhiri/?badge=latest)

## はじめに

Tawhiri "はCUSF着陸予測ソフトの次期バージョンの名称である。
おそらく現在のバージョン（下記参照）とは十分に異なるものになると思われる。
(下記参照)。

名前の由来は
[M&#257;ori](http://en.wikipedia.org/wiki/M%C4%81ori_people)に由来する。
天候を司る神に由来する。
タンガロアとその子孫を海に追いやった；
[(WP)](http://en.wikipedia.org/wiki/Tawhiri)。

## 詳細は

CUSFウィキ](http://www.cusf.co.uk/wiki/)を参照。
タウヒリ](http://www.cusf.co.uk/wiki/tawhiri:start)と[予言全般](http://www.cusf.co.uk/wiki/tawhiri:start)のページがあります。
一般](http://www.cusf.co.uk/wiki/landing_predictor)のページがあります。

[より詳細なAPIとセットアップのドキュメント](http://tawhiri.cusf.co.uk/).

## セットアップ

### 予測

...はPython 3用に書かれており、Python 2と互換性があり、Cythonが必要です：

```bash
$ virtualenv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
$ python setup.py build_ext --inplace
```

最後の行はCython拡張を(再度)ビルドするので、`.pyx`を変更した後にもう一度実行する必要があります。
.pyx` ファイルを変更した後に再度実行する必要があります。

### ダウンローダー

ダウンローダーは Python が優れた協調並行処理をサポートするようになる前に書かれました。
がサポートされる前に書かれたものなので、代わりに Othon の [separate application]()
アプリケーション](https://github.com/cuspaceflight/tawhiri-downloader) です。

## ライセンス
Tawhiriの著作権は2014年(AUTHORS & individual filesを参照)に帰属し、ライセンスは[GNU GPL 3]()に基づいています。
GNU GPL 3](http://gplv3.fsf.org/) (LICENSE 参照)に基づいてライセンスされています。