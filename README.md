## casual-markdown-blog

Build blog site by markdown files. 

It is very handy to build simple web-site from markdown files, and host on static web hosting. For example, 

* Self-host on github: https://raw.githack.com/casualwriter/casual-markdown-blog/main/source/index.html
* Casual-Markdown's Blog: https://casualwriter.github.io/casual-markdown/blog
* Dark theme: https://casualwriter.github.io/casual-markdown/blog?theme=dark
* Dark (always): https://casualwriter.github.io/casual-markdown/blog?home=index-dark.md
* Nav at right-side: https://casualwriter.github.io/casual-markdown/blog?home=index-right.md 

What you need is one file [index.html](source/index.html) and config home page at [index.md](source/index.md)

then start write post in markdown!

### Features

* single html
* no dependence in vanilla javascript
* support all browser (include IE9)
* dark mode or dark theme
* responsive, support mobile
* customized theme (by css style)

### Usage Guide

simply copy [index.html](https://github.com/casualwriter/casual-markdown-page/blob/main/source/index.html) to web server. 

* config site at index.md (title, subtitle, header-color, navigation, etc..)
* start to write blog post using markdown
* to publish, just update post at index.md by syntax 

~~~
* yyyy/mm/dd: [post-title](md-file) { #tags }
~~~

index.md is also shown as HOME page of blog site.

below is sample setup from [Sample Blog: index.md](https://raw.githubusercontent.com/casualwriter/casual-markdown-blog/main/source/index.md)

~~~  
-----------------------------------------------------------------------------
github     : https://github.com/casualwriter/casual-markdown-blog
title      : Casual-Markdown's Blog 
subtitle   : Simple is the best
nav-group  : featured, new-3, tags, months
nav-width  : 320px
css-header : background:linear-gradient(to bottom right, #06c, #fc0); color:white
menu       : 
   Home    : ?
   Dark    : javascript:darkmode()
   About   : ?page=about.md
-----------------------------------------------------------------------------

<style comment="additional style">
......
</style>

<div id="md-post">

home page in markdown syntax

## Archive

* yyyy/mm/dd: [Post Title](md file)  { #tag1, #tag2 }
* yyyy/mm/dd: [Post Title](md file)  { #tag1, #tag2 }
...
* yyyy/mm/dd: [Post Title](md file)  { #tag1, #tag2 }

</div>
~~~ 


### History

* 2022/08/24: 0.60, first release

 
