# 三島合宿日誌
三島合宿　2019/9/16-9/22
[坊農先生](https://twitter.com/bonohu)のご厚意で一週間DBCLSで合宿させていただけることになりました。その中で学んだことをまとめます。

## 今回のお宿　[ドーミーイン三島](https://www.hotespa.net/hotels/mishima/)

宿からの景色（写真は更新していく予定）↓

<img src="https://user-images.githubusercontent.com/48924412/64964513-2c56d580-d8d6-11e9-9df7-f5c87731c9ff.jpg" width="400">



温泉（写真はまだないですが）がとても良い！

wifiルーターを借りれば通信速度もなかなか速い


## 前乗りの日にAWSのつなぎ方等を学習 19/9/16

```open -e```　の威力に驚く

公開鍵の取得

sshにikraをcloneしてみたり、Rstudioを立ち上げてみたり

AWSなかなかややこしい汗


[kyamada先輩](https://github.com/ykohki)にgithubでのmarkdownについて教えていただく　

## 1日目　19/9/17

DBCLSに到着

サーバールームの見学をさせていただく

コマンドラインの使い方を学んでる途中で昼食へ

ご飯が並盛りとは思えないレベルのボリューム！とても美味しい

<img src="https://user-images.githubusercontent.com/48924412/65013210-2fdd7180-d955-11e9-8ed8-99fd42b6f55d.jpg" width="200">

コマンドラインの使い方　了

発現解析に移行


## ２日目　19/9/18

今日はまずikraのブラッシュアップ

中間ファイルを削除したい

```rm *.gz```とかでいけるか？

とりあえず、0,1で分ける感じで作る

どのファイルを残すか？

完成　テストではうまく消えた。

ここで昼食へ

とても美味しいお寿司！特に生しらす軍艦が美味しい

ご馳走様ですm(_ _)m

<img src="https://user-images.githubusercontent.com/48924412/65120743-13ab0480-da29-11e9-867a-4a300a26a36b.jpg" width="200" rotate="90">

ikra.shへの初めてのPull Request













### nimの勉強

 そもそも環境構築からスタート

 VScodeの拡張機能でできるみたい？→できた！

 Jupyter notebookでやろうとしたらエラーが出る

 関数は基本pythonと同じ感じ？

 変数宣言が特に慣れない

 ##### 宣言が３種類

 ```var a: int #データ型の情報がいる(判定できればいらない場合もある)```

 ```const b = 2 #変更不可```

 ```let c = 3 #変更不可(ただしコンパイル時に値が指定されていなくてもいい)```

 #### 関数定義

 ```proc name(): #defではない！```

```return```の他に```result```も考える。

ループとか条件分岐とかは、pythonとほぼ同じ

拡張機能でCode Runnerを入れると快適になった
