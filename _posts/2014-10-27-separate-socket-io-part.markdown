---
layout: post
title: socket.ioの部分を分離
date: 2014-10-27 17:23:22
categories: jekyll update
---
昨日のCPU使用率が･･･って奴はファイル更新時にいろいろ再起動するnodemonやliveloadを使っている関係だとおもう．ファイル更新を頻繁にしたいときは，ローカルのサーバを止めておいた方がよさそう．

socket.ioが悪者じゃなかったということで，使い込んでいきたいのだが，app.jsに書き込んでいくのはどうかと思うので分離．config/socket.jsに全体の設定等の処理を書いて，app/socketsに各機能を実装するというようした．
