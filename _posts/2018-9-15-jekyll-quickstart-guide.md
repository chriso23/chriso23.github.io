---
layout: post
title: "Jekyll: Quickstart Guide"
date: 2018-9-15
author: Chris Oung
---

Jekyll is one of the most popular [static site generators](https://www.staticgen.com) used today. Static site generators are database-free websites that populate all the pages with content locally before you publish the files on your web server. Jekyll is open source, free, easy to use, and extremely flexible.


## Instructions

1. Install a full [Ruby development environment](/docs/installation/)

2. Install Jekyll and [bundler](/docs/ruby-101/#bundler) [gems](/docs/ruby-101/#gems)
```
gem install jekyll bundler
```

3. Create a new Jekyll site at `./blog`
```
jekyll new blog
```

4. Go to your site’s directory
```
cd blog
```

5. Build the site and make it available on a local server
```
bundle exec jekyll serve
```

6. Now browse to [http://localhost:4000](http://localhost:4000){:target="_blank"}


<br/>

#### References
---

[1] Source: *[Transform your plain text into static websites and blogs](https://jekyllrb.com/)*