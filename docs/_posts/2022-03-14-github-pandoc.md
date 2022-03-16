
---
layout: post
title:  "Github Actions"
date:   2022-03-04 14:55:59 -0500
categories: pandoc
tags: pandoc github-actions
---

Try to get the actions and the makefile to work on the gulp-generated MD file.   The gulp-generated MD file is a version-controlled file in Github.   The file is generated on the Linux server and pushed to github.

The makefile generates the PDF, but pandoc does not process the markdown syntax.   For example, the headers and lists show with #, ##, and - instead of being formatted.

- [Pandoc Github Action Examples](https://github.com/pandoc/pandoc-action-example)
- [Github - Using Workflows](https://docs.github.com/en/actions/using-workflows#referencing-a-container-on-docker-hub)
