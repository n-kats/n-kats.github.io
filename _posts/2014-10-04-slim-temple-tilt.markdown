---
layout: post
title: Slimを調べていたらいろいろ
date: 2014-10-04 18:17:18
categories: jekyll update
---
imgとかbrとかは勝手にタグを閉じるけど，これってどういう基準でえらんでいるの？ってのを調べようとしてSlimのソースを眺めてみたら，いろいろ複雑．

templeとtiltを読み込んでいる．で，Slim::Template.newするとき，さっそくこれらの登場となる･･･

初期のSlimのソースの牧歌的な処理はどこでされているのやら．

今日は用事があるからこの程度で

