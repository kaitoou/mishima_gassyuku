# 三島合宿日誌
三島合宿　2019/9/16-9/22
[坊農先生](https://twitter.com/bonohu)のご厚意で一週間DBCLSで合宿させていただけることになりました。その中で学んだことをまとめます。

## 今回のお宿　[ドーミーイン三島](https://www.hotespa.net/hotels/mishima/)

宿からの景色

<img src="https://user-images.githubusercontent.com/48924412/64964513-2c56d580-d8d6-11e9-9df7-f5c87731c9ff.jpg" width="300">

温泉がとても良い！

<img src="https://user-images.githubusercontent.com/48924412/65252596-36760f80-db34-11e9-9083-ce9dfb60bc59.jpg" width="300">

wifiルーターを借りれば通信速度もなかなか速い


## 前乗りの日にAWSのつなぎ方等を学習 19/9/16

・```open -e```　の威力に驚く

・公開鍵の取得

・sshにikraをcloneしてみたり、Rstudioを立ち上げてみたり

・AWSなかなかややこしい汗


・[kyamada先輩](https://github.com/ykohki)にgithubでのmarkdownについて教えていただく　

## 1日目　19/9/17

・DBCLSに到着

・サーバールームの見学をさせていただく

・コマンドラインの使い方を学ぶ

・コマンドラインの使い方　了

・発現解析に移行


## ２日目　19/9/18

・今日はまずikraのブラッシュアップ

・中間ファイルを削除したい

・```rm *.gz```とかでいけるか？

・とりあえず、0,1で分ける感じで作る

・どのファイルを残すか？

・完成　テストではうまく消えた。

・初めての[Pull Request](https://github.com/yyoshiaki/ikra/pull/51)


## ３日目　19/9/19
・今日は念願の富士山が見えた！



<img src="https://user-images.githubusercontent.com/48924412/65228259-1ed36280-db05-11e9-98ee-df3b532c1b37.jpg" width="300" >

・nimについて学びつつRNAseq

・nimの解説やパッケージなどを読み漁る

・ようやくファイルから行列を作成できるパッケージを発見

・エラーとの対決

・大体のエラーが、データ型に関する文句だった→省略はやめとこう。

・RNAseqの勉強再開

・nimについてわかったことなどを[Googleドキュメント](https://docs.google.com/document/d/1hReGudWqvT0wp_ZeaoK2Jnh55IkOp7fv0iRXtI7MTwg/edit)にまとめていくことに決定

>>Previewでは向きが変わっているのにブラウザに反映されない問題発生

<img width="300" alt="スクリーンショット 2019-09-19 23 30 38" src="https://user-images.githubusercontent.com/48924412/65253587-d8e2c280-db35-11e9-9320-f7bcf4d5252d.png">


### nimの勉強

・そもそも環境構築からスタート

・VScodeの拡張機能でできるみたい？→できた！

・Jupyter notebookでやろうとしたらエラーが出る

・関数は基本pythonと同じ感じ？

・変数宣言が特に慣れない

 #### 変数の宣言

・データ型を類推してくれる時も多いが、ややこしいとかエラーが出てるとかなら大人しくデータ型をしっかり書いた方がうまくいくことが多い




 #### 関数定義

・```#defではない！```

・```return```の他に```result```も考える。

#### その他
・ループとか条件分岐とかは、pythonとほぼ同じ

・拡張機能でCode Runnerを入れると快適になった

・代数計算パッケージとしてneoを使っていく予定

・他にも見つけたので、一考の余地あり


### nimdata
・pythonのpandasにそっくりなパッケージ

・これはかなり使えそう





## ★三島グルメ紀行 ★

### >19/9/16
#### >>夜

近くのG系ラーメン屋さん
ふじもり
<div style="position:relative;left:70px;top:200px">
<img src="https://user-images.githubusercontent.com/48924412/65251764-e0ed3300-db32-11e9-8e4f-1030e1903695.jpg" width="200" style="transform: rotate(90deg);transform-origin:right top;">
</div>

### >19/9/17
#### >>昼
超がっつり系食堂　しんちゃん

並とは思えないボリューム！

<div style="position:relative;left:-200px">
<img src="https://user-images.githubusercontent.com/48924412/65013210-2fdd7180-d955-11e9-8ed8-99fd42b6f55d.jpg" width="200" style="transform: rotate(-90deg);transform-origin:right top;">
</div>

### >19/9/18
#### >>昼
激ウマ　お寿司　もろこし

ごちそうさまでしたm(_ _)m

<div style="position:relative;left:70px;top:200px">
<img src="https://user-images.githubusercontent.com/48924412/65120743-13ab0480-da29-11e9-867a-4a300a26a36b.jpg" width="200" style="transform: rotate(90deg);transform-origin:right top;">
</div>

### >19/9/19
#### >>昼
写真を撮り忘れる痛恨のミス

油そば(広義タピオカ)　七転八起

#### >>夜
北口の牛タン

<div style="position:relative;left:70px;top:200px">
<img src="https://user-images.githubusercontent.com/48924412/65252606-3c6bf080-db34-11e9-8d16-3fcfcbab7c6e.jpg" width="200" style="transform: rotate(90deg);transform-origin:right top;">
</div>
