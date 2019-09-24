# 三島合宿日誌
三島合宿　2019/9/16-9/22
[坊農先生](https://twitter.com/bonohu)のご厚意で一週間[DBCLS](https://dbcls.rois.ac.jp/)で合宿させていただけることになりました。

その中で学んだことをまとめます。

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

・今日はまず[ikra](https://github.com/yyoshiaki/ikra)のブラッシュアップ

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

・寄生蜂　セイボウとかが好きで、寄生蜂のことは知っていたが、

　一つの胚から多数のソルジャーが生まれることは知らなかった。昆虫は奥が深いなぁ

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

・お土産屋さんに連れて行っていただきありがとうございましたm(_ _)m

## 5日目　19/9/21

・[Mishima.syk #14](https://connpass.com/event/137642/)に参加させていただく

・https://plot.ly/dash/

・拙いプレゼン(飯テロ)をしました。

<img src="https://user-images.githubusercontent.com/48924412/65483835-9542dc80-ded8-11e9-98cb-dc1df97d93aa.jpg" width="300">
<img src="https://user-images.githubusercontent.com/48924412/65483888-c3c0b780-ded8-11e9-8a28-e1f34bdddfcd.jpg" width="300">

・皆さんのプレゼンはとてもレベルが高く、理解しきれていない部分が多々あるので、

   勉強したいと思いますm(_ _)m

# 総括

大変お忙しい中、僕たちの急な受け入れを快諾してくださった

[坊農先生](https://github.com/bonohu)をはじめとする[DBCLS](https://dbcls.rois.ac.jp/)の皆様本当にありがとうございました。

一週間見学させていただいたり、質問に答えていただいたりして大変勉強になりました。

先生方に教えていただいたご飯屋さんは、本当に美味しくて

三島には美味しいものしかないのか、

先生方の美味しいものへの探究心がすごすぎるのか笑

特にご馳走していただいたお寿司の生しらすが美味しすぎて忘れられません笑

本当に何から何までお世話になり、ありがとうございました。

勉強をさせてもらいに来たのに、本当に楽しくてもう少し居たかったです笑

本当にありがとうございました。

また、

この自主研究の機会を与えてくださった[yyoshiaki先輩](https://github.com/yyoshiaki)に感謝したいと思います。

様々な面で、支えてくださり本当にありがとうございます。

引き続きよろしくお願いします。

そして、

一緒に合宿に参加した[kyamada先輩](https://github.com/ykohki)にも色々教えていただき、
ありがとうございました。

先輩は、もともとわかっておられることが、多いからだと思うのですが、

吸収していくスピードや量がすごくて、横で見ていて圧倒されました。

<br />
<br />

この合宿で教えていただいた様々なことを、

しっかり自主研究に活かしていけるように頑張りたいと思います。

本当にありがとうございました。


## 6日目 19/9/22（番外編）

・少し観光してから大阪に帰ることに

・念願の沼津深海魚水族館へ

・深海魚しかいない水族館はとても楽しかったですが、かなり混んでいたので、

　５時間滞在予定が、２時間に。

<img src="https://user-images.githubusercontent.com/48924412/65384758-ff387600-dd60-11e9-9ccc-78a79daa0681.jpg" width="300" >









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

### 【19/9/16】
#### 【夜】

近くのG系ラーメン屋さん
ふじもり

<img src="https://user-images.githubusercontent.com/48924412/65373523-934f0280-dcb9-11e9-9e33-d158b18fd3eb.jpg" width="300">


### 【19/9/17】
#### 【昼】
超がっつり系食堂　しんちゃん

並とは思えないボリューム！


<img src="https://user-images.githubusercontent.com/48924412/65373557-0a849680-dcba-11e9-95e2-02befc4242c9.jpg" width="300">

### 【19/9/18】
#### 【昼】
激ウマ　お寿司　もろこし

ごちそうさまでしたm(_ _)m


<img src="https://user-images.githubusercontent.com/48924412/65373593-af9f6f00-dcba-11e9-91b5-743a1605fbc0.jpg" width="300" >


### 【19/9/19】
#### 【昼】
写真を撮り忘れる痛恨のミス

油そば(広義タピオカ)　七転八起

#### 【夜】
北口の牛タン


<img src="https://user-images.githubusercontent.com/48924412/65373594-af9f6f00-dcba-11e9-9ac0-dc1dbf741ad7.jpg" width="300" >

### 【19/9/20】
#### 【昼】
激ウマ　エビ豚骨つけ麺　もかすけ

<img src="https://user-images.githubusercontent.com/48924412/65373597-b332f600-dcba-11e9-85bc-12bbb1dc2ef8.jpeg" width="300">

### 【19/9/21】
#### 【昼】
旨味がすごい　イワシの漬け丼　磯はる

<img src="https://user-images.githubusercontent.com/48924412/65367877-7099fb00-dc73-11e9-900f-561187babea8.jpg" width="300">

#### 【夜】
激ウマ　ジャンボポークソテー

<img src="https://user-images.githubusercontent.com/48924412/65373284-4e759c80-dcb6-11e9-9672-8bbd435470ec.jpg" width="300">

### 【19/9/22】
#### 【昼】
海鮮丼　佐政　セットが豪華

<img src="https://user-images.githubusercontent.com/48924412/65384759-ffd10c80-dd60-11e9-8a89-259fb914fe8e.JPG" width = "300">


三島のご飯はどれもとても美味しかったので、必ずまた個人的に来たいと思ってます笑
