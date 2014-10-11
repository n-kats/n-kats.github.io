---
layout: post
title: かぜっぽい、ちょっとだけtypescript
date: 2014-10-11 19:54:13
categories: jekyll update
---
typescriptの本をぱらぱら見ながらなんかしてみようと，ひとまずnode.jsのサーバーを書いてみようとするも，一行目に詰まる．

require関係のところだけど，VisualStudioは波線を出すし，コンパイルも文句を言われる．
型の指定などを設定するファイルをどうにかしないといけないらしいというところがわかってもコンパイル時のmoduleの使い方が分からん･･･

と悩んでいたけどよくhelpをみたら `--module`のあとにはcommonjsかamdが入るらしい．
適当にcommonjsと書いて，ファイルにもnode.d.tsへの依存関係を書いてコンパイルしたら通った．

買った本がnode.jsでサーバーを立ててないあたりで身構えるべきだった気もする．
