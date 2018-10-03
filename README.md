TextMap
====
シンプルな（マインド、テキスト）マップ作成ウェブアプリです
  
URL: <https://neji205.github.io/TextMap>  （※現在PCのGoogle Chromeのみで動作確認）
  
  

## 用途
* プロット作成中複数のアイデアを並列に管理したい時（テキストファイルだと少し根本的な厳しさがある）
* 普通にシンプルめなマインドマップ的なものを使いたい時



## デモ（プロットのアイデア分岐管理）  

（黄色い円はキャプチャソフト側の演出）
![result](https://github.com/neji205/TextMap/blob/master/example.gif)

  
## 操作

ファイル操作

|     | 操作 | 
| --- | --- |
| ファイル名変更 | 右側 file name を変更 |
| ファイル保存 | 右上の download ボタン |
| ファイル読み込み | 画面上にファイルをドラッグ＆ドロップ |

ノード操作

|     | 操作 |
| --- | --- |
| ノード作成 | （フォーカスがノードにない時に）Spaceキー |
| ノード書き込み | ノードを選択してからタイピング |
| ノード移動 | 左ドラッグ |
| ノード接続 | ノードを別ノードへ右ドラッグ |
| ノードリサイズ | ノード右下部分を左ドラッグ |
| ノードをフォルダ化| ノード上で上ホイール |
| ノードをフォルダ内へ移行| ノードを別ノードへ左ドラッグ |
| フォルダ移動| ノード上で上ホイール・サイト上で下ホイール |
| フォルダ名変更 | 右側 dir name を変更 |
| フォーカスをキー操作で移動 | Tab + 矢印キー |
  
スタイル設定＞

|     | 操作 |
| --- | --- |
| フォントサイズ変更 | 右側 font size を変更 |
| デフォルトのノード幅変更 | 右側 node default width を変更 |
| デフォルトのノード高変更 | 右側 node default height を変更|

（裏コマンドとしてctrl + マウスホイールすれば画面全体の大きさが変わったりしますがまだ動作調整中）



## 動作
* 現在PCのGoogle Chromeのみで動作確認



## その他
* index.hmlをダウンロードしてもらってブラウザにそれをドラッグ＆ドロップしてもらえるだけで全く同じものが使えるので、サービス終了によるマップ消失は無い。↑のURLはそのindex.htmlをサーバーにアップすることで同時に色んな人が使えるようにしたものなだけで、ダウンロードすればサイトに繋がずとも使える。
* 骨格はできましたがスタイルはまだ詰めてません。例えば一度接続した線を消す機能がありません。燃え尽き症候群が収まったら機能追加します
* ノード一斉移動がカクカクしているのはCPU付加を最小限に抑えるためにあえてやってます



## Licence
[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)



## Author
[@popoponnponpopo](https://twitter.com/popoponnponpopo)
