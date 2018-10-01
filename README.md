
TextMap
====
🐹 テキストオンリーのシンプルな（マインド、テキスト）マップ作成用ウェブアプリ  です🐤

<font size="3">URL: </font><https://neji205.github.io/TextMap>  
<font size="2" color="gray"> （※現在<font color="red">PCのGoogle Chromeのみ</font>で動作確認）</font>
<br>
<br>＜想定用途＞
* <font size="3">プロット作成時、何日にも分けて考えるから<font color="red">プロットの分岐をいろいろ</font>と思いつくけれども、<font color="red">単なるテキストエディタ上じゃそのアイデアのいくつもの分岐が管理しづらい</font>からマインドマップ的なもので管理したいけれども、一般のマインドマップがなんか使いづらい…と感じた時
* <font size="3">普通にシンプルめなマインドマップ的なものを使いたい時

<br>
<br>  
<br>  


## デモ動画（プロットのアイデア分岐管理）
<font size="2" color="gray">（黄色い円はキャプチャソフト側の演出です）</font>  
![result](https://github.com/neji205/TextMap/blob/master/example.gif)
<br>  
<br>  


 

## 特徴 & 他との違い




  
* **シナリオ作成に中央ノードはいらない！🐺**
  * <font size="2">ただただいらないから無い</font>
<br>
* **ノードがいろいろ自由🐰**
  * <font size="2">左ドラッグで自由に動かせるし接続も大きさ変更も自由</font>
  * <font size="2">例えば「この前考えた最初のシーンのさらに前に別のシーンを思いついた」等のときに融通が効く</font> 
<br> 
* **ノードはフォルダとしても使用可🐭**
  * <font size="2">ノードはテキストでもありながら同時にフォルダにもなるようにした</font>
  * <font size="2">要はパソコンのファイルエクスプローラーの簡易ビジュアライズバージョンのようなものになってるはず</font>
<br>
* **たぶんシンプル🐶**
  * <font size="2">無駄な機能無し</font>
  * <font size="2">CPU負荷も高まらないように少しした</font>
  * <font size="2">メディア貼り付け機能なんかいらない。黙って文字</font>
<br>
* **サービス終了が無い🐤**
  * <font size="2">githubが潰れない限り公開しっぱなしなはず</font>
  * <font size="2">仮に公開消えたとしても、不安ならソースコード上がってるから、このhtmlファイルをブラウザにドロップすればどこでも使えるからダウンロードしとくとネット環境なしでも作業可能だし、それで作業できる（ファイルもブラウザでブックマークもできる）からサービス終了がありえない</font>



<br><br>

|          | このテキストマップ | 他のマインドマップ |
|:---------|:------------:|:------------:|
| 中央ノード | <font color="red">無し | 邪魔なのがある |
| ノード位置 | <font color="red">自由 | 強制固定なイメージ |
| ノード作成 | <font color="red">楽 | 知らん |
| 線の繋げ方 | <font color="red">自由 | めんどそう |
| フォルダ機能 | <font color="red">あり | 知らん |
| 操作性 | <font color="red">シンプル | 独自機能多い |
| サービス終了 | <font color="red">無い | しちゃいそう |
| メディア貼付機能 | <font color="gray" size="1">いらないよね?🐹 | <font color="red">あり |
<br>
<br><br>

## 操作方法（大体感覚と同じなので読まなくていい）
<font size="5">＜基本＞</font>
ノード作成<font color="gray" size="2">　フォーカスが画面にある時にSpaceキー</font>
ノード書込<font color="gray" size="2">　ノードを左クリックしてからキーボードタイプ</font>
ノード接続<font color="gray" size="2">　ノードから他ノードへ右ドラッグ</font>
作ったマップ保存<font color="gray" size="2">　右上のdownloadボタン押す</font>
作ったマップ読込<font color="gray" size="2">　downloadボタンを押した時にダウンロードしたファイルを画面にドラッグ＆ドロップ</font>

<font size="5">＜その他＞</font>
ノード移動<font color="gray" size="2">　ノードを左ドラッグ</font>
全ノード移動<font color="gray" size="2">　画面を左ドラッグ</font>
ノードリサイズ<font color="gray" size="2">　ノードの右下の部分を左ドラッグ</font>
ノードをノードに入れる<font color="gray" size="2">　ノードをノードへドラッグ＆ドロップ</font>
ノード内に移動<font color="gray" size="2">　ノード上でマウスホイール上</font>
ノードを出る<font color="gray" size="2">　どこでもいいからマウスホイール下</font>
保存するファイル名変更<font color="gray" size="2">　右上の「your map」を変更</font>
<font size="4" color="green">その他右側にある変更可能な設定をいじる</font>
<font color="gray" size="2">（裏コマンドとしてctrl + マウスホイールすれば画面全体の大きさが変わったりするけどまだ甘く表示がバグりがち）</font>
<br>
<br>


## 対応環境
* 現在PCのGoogle Chromeのみで動作確認
<br>
<br>

## その他
* 動作の骨格はできましたがスタイルはまだ詰めてません。例えば一度接続した線を消す機能がありません。燃え尽き症候群が収まったら機能追加します
* ノード一斉移動がカクカクしているのはCPU付加を低く抑えるためにあえてやってます。あえてだからね？🐤❓🐰
<br>
<br>

## Licence
[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)



## Author
[@popoponnponpopo](https://twitter.com/popoponnponpopo)
