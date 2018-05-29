---
title: 念随心生
layout: single
sidebar:
  nav: docs
permalink: "/docs/structure/"
excerpt: How the theme is organized and what all of the files are for.
modified: '2016-08-08 16:25:30 -0400'
---

原谅我从心而发 :wink:. 心感知了时空的波动，此时的你，或品读我，或回首你岁月的旧亿，或沉思，或无觉.
这个时代，有人说`喜爱也好，梦想也罢，人生在世总得有点追求，万一实现了呢！`.有好多人说了好多，我们终是会有点思考的，成长还分高下对错吗！我听闻`大道三千，择其一而从之。流水三千，取—瓢而饮之`，听闻`要有最朴素的生活，和最遥远的梦想，即使明日天寒地冻，路遥马亡`,好多好多，我驻足良久的岁月，我深思梦呓的深情，我痛苦流涕期许的故事。
最后的最后，我以我的所有，勾画文明的古卷，清秋月仅仅是浩瀚无尽时空域的一份子。愿不久的将来，时空域中，繁华无尽


```bash
minimal-mistakes
├── _data                      # data files for customizing the theme
|  ├── navigation.yml          # main navigation links
|  └── ui-text.yml             # text used throughout the theme's UI
├── _includes
|  ├── analytics-providers     # snippets for analytics (Google and custom)
|  ├── comments-providers      # snippets for comments (Disqus, Facebook, Google+, and custom)
|  ├── footer                  # custom snippets to add to site footer
|  ├── head                    # custom snippets to add to site head
|  ├── base_path               # site.url + site.baseurl shortcut
|  ├── feature_row             # feature row helper
|  ├── gallery                 # image gallery helper
|  ├── group-by-array          # group by array helper for archives
|  ├── nav_list                # navigation list helper
|  ├── toc                     # table of contents helper
|  └── ...
├── _layouts
|  ├── archive-taxonomy.html   # tag/category archive for Jekyll Archives plugin
|  ├── archive.html            # archive listing documents in an array
|  ├── compress.html           # compresses HTML in pure Liquid
|  ├── default.html            # base for all other layouts
|  ├── single.html             # single document (post/page/etc)
|  └── splash.html             # splash page
├── _sass                      # SCSS partials
├── assets
|  ├── css
|  |  └── main.scss            # main stylesheet, loads SCSS partials from _sass
|  ├── fonts
|  |  └── fontawesome-webfont  # Font Awesome webfonts
|  ├── js
|  |  ├── plugins              # jQuery plugins
|  |  ├── vendor               # vendor scripts
|  |  ├── _main.js             # plugin settings and other scripts to load after jQuery
|  |  └── main.min.js          # optimized and concatenated script file loaded before </body>
├── images                     # image assets for posts/pages/collections/etc.
├── _config.yml                # site configuration
├── Gemfile                    # gem file dependencies
├── Gemfile.lock               # gem file dependencies
├── index.html                 # paginated home page showing recent posts
└── package.json               # NPM build scripts
```