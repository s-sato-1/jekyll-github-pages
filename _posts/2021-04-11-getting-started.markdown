---
layout: post
title:  "Getting Started!"
date:   2021-04-11 20:33:00 +0900
categories: getting started
---

### 1. Jekyllとは

JekyllとはRuby製の静的サイトジェネレータ

### 2. インストール

<!-- code -->
{% highlight shell %}
$ ruby -v
ruby 2.7.0p0 (2019-12-25 revision 647ee6f091) [x86_64-linux-gnu]
$ gem -v
3.1.2
$ gem install jekyll bundler
$ jekyll new jekyll-github-pages
$ cd jekyll-github-pages

$ bundle exec jekyll serve
// Or
$ bundle exec jekyll s
{% endhighlight %}
<!-- // code -->

### 3. \_config.ymlをいじる

\_config.yml内のurlとbaseurlを、自環境に合わせる

+ url
  - ex. "https://s-sato-1.github.io"
+ baseurl
  - ex. "/jekyll-github-pages"

### 4. \_postsに記事を作成

+ ネーミングルール
  - `YEAR-MONTH-DAY-title.MARKUP`
