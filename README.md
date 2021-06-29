# Theme pinghsu-jekyll

a jekyll theme which is based on a typecho theme pinghsu

## How to start

- fill the file `_config.yml`

example

```yaml
name: 勇丶敢做自己 Blog
author: justbeyourself
url: https://justbeyourself.github.io/
resume_site: https://justbeyourself.github.io/
baseurl: 
description: 随便写写
github_username: justbeyourself
github: https://justbeyourself.github.io/
plugins: [jekyll-paginate]
permalink: /:year-:month-:day-:title
paginate: 12
paginate_path: "/page/:num/"
exclude: ['README.md', 'Gemfile.lock', 'Gemfile', 'Rakefile']
highlighter: rouge
markdown: kramdown
comments :
  gitalk:
    clientID: 0d23ccf72e53ceec07dd
    clientSecret: 4bab3e418b9d32dce244dd50a707f7f58d63a353
    repo: justbeyourself.github.io
    owner: justbeyourself

```

- add your post in path `./_post`, format : 

```md
---
layout: post
title: A Example Post
date:   1970-01-01 00:00:00 +0800
category: tutorial
thumbnail: /style/image/thumbnail.jpg
icon: book
---


* content
{:toc}

## sub title

page...

## about thumbnail

add the thumbnail url

## about icon

such as book, code, web, chat, note, game, link, design, image
```

some config about gitalk, please reference to [gitalk](https://github.com/gitalk/gitalk)

run `bundle install` and `jekyll server` to preview site on you computer, more question about jekyll, reference to [jekyll](http://jekyllrb.com)



## Developer

- [chakhsu](https://github.com/chakhsu)
- [lightfish-zhang](https://github.com/lightfish-zhang)

## Thanks

- [jekyll](http://jekyllrb.com) git page engine
- [pinghsu](https://github.com/chakhsu/pinghsu), a typecho theme, it's a great design.
- [gitalk](https://github.com/gitalk/gitalk) git page comment engine, it depends on github issue.
- [smoothscroll](https://www.smoothscroll.net/mac/) SmoothScroll will give your mouse wheel (Finder, Safari, Chrome, etc.) buttery smooth scrolling
