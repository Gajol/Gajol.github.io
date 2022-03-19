---
layout: post
title:  "View Markdown in Linux"
date:   2022-03-18 14:55:59 -0500
categories: markdown
excerpt: A guide on how to view markdown on a linux terminal using pandow and lynx.
tags: markdown view linux
---

It is suggested to use pandoc and lynx to view markdown on a Linux terminal as text.  Images and other rich-media are not displayed..  This guide shows the install and usage.

# Installation
1. Install [pandoc](https://pandoc.org/installing.html)

  `sudo apt-get install pandoc`

2. Install [lynx](https://lynx.invisible-island.net/).

  `sudo apt install lynx`

# usage
Terminal viewing a markdown file:
`pandoc file.md | lynx -stdin`

# Notes
For PDF output, you need to use LaTex.  You could install TeX Live as described in the [][pandoc installation](https://pandoc.org/installing.html)].  
