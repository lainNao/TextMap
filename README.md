TextMap
====
シンプルな（マインド、テキスト）マップ作成ウェブアプリです
  
URL: <https://neji205.github.io/TextMap>  （※現在PCのGoogle Chromeのみで動作確認）
  
  
  

## 用途
* プロット作成時、何日にも分けて考えるからプロットの分岐をいろいろと思いつくけれども、単なるテキストエディタ上じゃそのアイデアのいくつもの分岐が管理しづらいからマインドマップ的なもので管理したいけれども、一般のマインドマップがなんか使いづらい…と感じた時
* 普通にシンプルめなマインドマップ的なものを使いたい時


## デモ（プロットのアイデア分岐管理）  

（黄色い円はキャプチャソフト側の演出です）
![result](https://github.com/neji205/TextMap/blob/master/example.gif)


  
    
  
  
　  

## 特徴
***とにかくプロット作成用途のために作成***。よってプロット管理がしやすい可能性がある。  

***ありがちな中央ノードが無い***。マインドマップにはありがちな中央に居座るでかいやつが無い。  

***ノードはいろいろ自由***。左ドラッグで自由に動かせるし接続も大きさ変更も自由。例えば「この前考えた最初のシーンのさらに前に別のシーンを思いついた」等のときに融通が効く。  

***ノードはフォルダにもなるからいろいろできそうかもしれない***。ノードはテキストでもありながら同時にフォルダにもなるようにした要はパソコンのファイルエクスプローラーの簡易ビジュアライズバージョンのようなものになってるはず

|          | このテキストマップ | 他のマインドマップ |
|:---------|:------------:|:------------:|
| 中央ノード | 💯無し | 邪魔なのがある |
| ノード位置 | 💯自由 | 強制固定なイメージ |
| ノード作成 | 楽 | 知らん |
| 線の繋げ方 | 自由 | めんどそう |
| フォルダ機能 | 💯あり | 知らん |
| 操作性 | シンプル | 独自機能多い |
| サービス終了 | 💯無い | しちゃいそう |
| メディア貼付機能 | いらない | あり💯 |
  
  
## 操作
  
***基本***
* ***ノード作成*** 　「フォーカスが他のに無い時にSpaceキー」
* ***ノードに文字書込***　「ノードを左クリックしてからキーボードタイプ」
* ***ノード移動***　「ノードを左ドラッグ」
* ***ノード全移動***　「画面を左ドラッグ」
* ***ノード接続***　「ノードから他ノードへ右ドラッグ」
* ***ノードリサイズ***　「ノードの右下の部分を左ドラッグ」
* ***作ったマップを保存***　「右上のdownloadボタン押す」
* ***作ったマップを読込***　「downloadボタンを押した時にダウンロードしたファイルを画面にドラッグ＆ドロップ」

***他***
* ***ノードをノードに入れる***　「ノードをノードへドラッグ＆ドロップ」
* ***ノード内に移動***　「ノード上でマウスホイール上」
* ***ノードを出る***　「どこでもいいからマウスホイール下」
* ***保存するファイル名変更***　「右上の「your map」を変更」
* ***その他***　「右側の設定いじる」
* （裏コマンドとしてctrl + マウスホイールすれば画面全体の大きさが変わったりするけどまだ甘く表示がバグりがち）



## 動作
* 現在PCのGoogle Chromeのみで動作確認



## その他
* 骨格はできましたがスタイルはまだ詰めてません。例えば一度接続した線を消す機能がありません。燃え尽き症候群が収まったら機能追加します
* ノード一斉移動がカクカクしているのはCPU付加を最小限に抑えるためにあえてやってます


## Licence
[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)


## Author
[@popoponnponpopo](https://twitter.com/popoponnponpopo)
