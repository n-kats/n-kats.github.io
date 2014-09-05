---
layout: post
title: railsでPDFを扱う方法
date: 2014-09-05 20:43:15
categories: jekyll update
---
##iframe

PDFに限らず，iframeを使うと他URLのページを表示できる．これとtwitter bootstrapを使ってPDFをタブ切り替えで表示させれるようにした．

##railsでPDF
画像をrailsのデータベースに記録する方法と同様にbinaryとして登録する仕組みを用いればよい．PDF単体が開けるページを用意して，そこにリンクする形でiframeを使えば好きなところに表示できる．今後，これを実際に使っていきたい．
