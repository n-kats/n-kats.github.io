---
layout: post
title:  "Introduce Jekyll!"
date:   2014-08-27 13:40:29
categories: jekyll update
---
`_post`ディレクトリに`YYYY-MM-DD-name-of-post.ext`の形式で書く．
`jekyll serve --watch`と唱えれば，手元で動く

コードの例
{% highlight ruby %}
def sample
  puts "sample"
end
{% endhighlight %}
`rouge`をインストール後，`_config.yml`に`highlighter: rouge`と追加すれば，windows環境下でもエラーがでない．

ドキュメント [Jekyll docs][jekyll]
Jekyllレポジトリ [Jekyll's GitHub repo][jekyll-gh]
ヘルプ [Jekyll's dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
