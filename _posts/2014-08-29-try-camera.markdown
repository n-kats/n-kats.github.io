---
layout: post
title: ウェブカメを使おうとしてみる
date: 2014-08-29 16:41:04
categories: jekyll update
---
研究過程の記録に写真や短い動画があるのは望ましい．

ひとまず，カメラの画像を受け取って表示することを目指した．

C#で頑張ろうと思ったがよくわからなかった．なので，いろいろ探してみたら，Processingが簡単にできるらしい．

他の選択肢を求めて，ほとんどしたことのないJavaをさわってみたけど，**JMF**やら**Webcam Capture**といったものがあることは分かったが，netbeansがよく分からず，あきらめ．

ひょっとしてHTML5ならと思ったらできるらしい．
**WebRTC**というもの．ただし，ブラウザによって上手くいかない場合があるみたい．
Firefoxはhtmlファイルを開くだけでちゃんと動くが，chromeはこれでは上手くいかず，一度サーバーを通さないといけないみたい．外部のサーバーじゃないといけないのかと思ったら，一か八かで試したらローカルのサーバーでもよかった．
sinatraでサーバーを立てて，publicフォルダに置くという方法．別にどうとでもできると思う．

昨日作った自動投稿プログラムの中身に書いていたりするから，
これをブラウザか何かからするようにしたい．

