---
layout: post
title: neobundleに移行
date: 2014-09-10 20:23:38
categories: jekyll update
---
普段使うエディタはvimだけど，これまでプラグインの管理にpathogenを使っていたのをneobundleに移行．

##目的
「**○○するなら入れておきたいプラグイン**」というような記事を目にすると使ってみたいが，pathogenのように自分でファイルをダウンロードするのが面倒．neobundleはそれができる！

virtual boxのvimのほうでneobundleを使った感じ難しくなかったのでそのうちしようとしていた．

##変更内容
pathogenでいれていたプラグインたちを排除．（一部使わなくなったものを抹消）

今後も使うものを_vimrcに書いてインストール．（neobundleについてはぐぐれ）

ついでに_gvimrcに書いていたものの一部を_vimrcにお引越し．

まあ，プラグインを入れても使い方を頭にいれないと意味ないものがあったりするんですけどね～
