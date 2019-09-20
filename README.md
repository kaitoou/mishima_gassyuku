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

中間ファイルを削除したい

```rm *.gz```とかでいけるか？

とりあえず、0,1で分ける感じで作る

どのファイルを残すか？

完成　テストではうまく消えた。

・初めての[Pull Request](https://github.com/yyoshiaki/ikra/pull/51)

・逆転写しにくいRNAがあることがあることを聞く。逆に言えばRNAが安定？



## ３日目　19/9/19
・今日は念願の富士山が見えた！



<img src="https://user-images.githubusercontent.com/48924412/65228259-1ed36280-db05-11e9-98ee-df3b532c1b37.jpg" width="300" >

・寄生蜂　セイボウとかが好きで、寄生蜂のことは知っていたが、一つの胚から多数のソルジャーが生まれることは知らなかった。昆虫は奥が深いなぁ

・nimについて学びつつRNAseq

・nimの解説やパッケージなどを読み漁る

・ようやくファイルから行列を作成できるパッケージを発見

・エラーとの対決

・大体のエラーが、データ型に関する文句だった→省略はやめとこう。

・RNAseqの勉強再開

・nimについてわかったことなどを[Googleドキュメント](https://docs.google.com/document/d/1hReGudWqvT0wp_ZeaoK2Jnh55IkOp7fv0iRXtI7MTwg/edit)にまとめていくことに決定

>>Previewでは向きが変わっているのにブラウザに反映されない問題発生

<img width="300" alt="スクリーンショット 2019-09-19 23 30 38" src="https://user-images.githubusercontent.com/48924412/65253587-d8e2c280-db35-11e9-9320-f7bcf4d5252d.png">

## 4日目　19/9/20

・githubをHPにできる機能があることを先輩から教えてもらう

・RNAseqの解析　kallisto

・nimの勉強(詳細はGoogleドキュメントや↓のコーナーを)

・先生に[データベースの利用法](https://www.amazon.co.jp/%E7%94%9F%E5%91%BD%E7%A7%91%E5%AD%A6%E3%83%87%E3%83%BC%E3%82%BF%E3%83%99%E3%83%BC%E3%82%B9%E3%83%BB%E3%82%A6%E3%82%A7%E3%83%96%E3%83%84%E3%83%BC%E3%83%AB-%E5%9B%B3%E8%A7%A3%E3%81%A8%E5%8B%95%E7%94%BB%E3%81%A7%E4%BD%BF%E3%81%84%E6%96%B9%E3%81%8C%E3%82%8F%E3%81%8B%E3%82%8B-%E7%A0%94%E7%A9%B6%E3%81%8C%E3%81%AF%E3%81%8B%E3%81%A9%E3%82%8B%E5%AE%9A%E7%95%AA18%E9%81%B8-%E5%9D%8A%E8%BE%B2%E7%A7%80%E9%9B%85/dp/4815701431)を教えていただく

・CHIP-Atlas,Metascape,COSMIC,gnomAD,TogoVar,GWASあたり使えるようになりたい

・gitpitchかっこいい！

・[Allie](http://allie.dbcls.jp/short/exact/Any/CWL.html)

・お土産やさんに連れて行っていただきありがとうございましたm(_ _)m



## [nimの勉強](https://docs.google.com/document/d/1hReGudWqvT0wp_ZeaoK2Jnh55IkOp7fv0iRXtI7MTwg/edit)

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

・```proc(引数):データ型 =  ```

#### その他
・ループとか条件分岐とかは、pythonとほぼ同じ

・拡張機能でCode Runnerを入れると快適になった

・代数計算パッケージとしてneoを使っていく予定

・他にも見つけたので、一考の余地あり

・split関数はあるが、pythonと少し違って区切る文字によって様々種類があり、引数とかもかなり変わる

・"."で関数繋いでいくやり方はなんかうまく生きにくいので引数として重ねていくスタイルがいいような気がする

・データ型も自分で作れたり、慣れればなんでもできる素晴らしい関数であることを感じてきた。



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

### >19/9/20
#### >>昼
激ウマ　エビ豚骨つけ麺　もかすけ

<img src="https://user-images.githubusercontent.com/48924412/65325724-962ef200-dbea-11e9-8fb4-3956fe2fbefe.jpg" width="300">
