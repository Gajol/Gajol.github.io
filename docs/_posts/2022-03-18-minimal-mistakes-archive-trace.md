---
layout: post
title:  "Tracing how Minimal Mistakes does the archiving!"
date:   2022-03-18 11:55:59 -0500
excerpt: I found it hard to trace how the post archives worked due to my lack of understanding of Jekyll, Ruby and the Minimal Mistakes theme.  
categories: jekyll
tags: archive minimal mistakes
---
I found it hard to trace how the post archives worked due to my lack of understanding of Jekyll, Ruby and the Minimal Mistakes theme.  

Here is an overview of the logic.

1. Minimal Mistakes - posts.html
  The `posts.html` file is located where your gems are installed; typically `~/gems/gems/minimal-mistakes-jekyll-4.24.0/_layouts`.
  - The posts.html has Liquid templating logic to iterate through all the site posts, using the post's date.   For each post in a year and archive entry is created using the `archive-single.html` template (in the _includes folder in the same gems location of Minimal Mistakes gem)).  
  - The archive-single.html takes a single post, converts the title to markdown, sets the appropriate HTML classes, adds the post link and any teaser image if associated to the post.
