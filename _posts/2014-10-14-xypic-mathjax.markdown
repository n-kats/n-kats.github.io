---
layout: post
title: mathjax版xypicをいじる
date: 2014-10-14 21:02:43
categories: jekyll update
---
MathJaxをさわろうとmathjaxのxypic.jsを触ってみる･･･まさか，つまるわけが･･･

ええ，つまりました．図が表示されない．なぜかリロードするとごく稀にうまくいく･･･

そのうちエラーが出たので原因が分かった．jQueryを外のリンクで書いていたんだけど，これをファイルをbowerでDLして適当に配置．
そしたらリロードとかをしなくてもよくなった．jQueryはDLして使ったほうがよさそう．
