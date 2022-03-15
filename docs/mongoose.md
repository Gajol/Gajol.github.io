---
layout: page
title: "Mongoose DJN"
permalink: /database/
category: database nosql
---

# Doug
Doug was Here .

## Gajol Github Repositories - Liquid Markup
{% comment %}
List repositories in Gajol's Github
{% endcomment %}

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

# Mongoose
mongodb object modeling for node.js
[mongoose](https://mongoosejs.com/)


Welcome to My Home Page

{% assign date = '2022-01-09T10:20:00Z' %}
- Original date - {{ date | date: "%a, %b %d, %y" }}, {{ date | timeago }}, see [Liquid Date Format](https://www.shopify.ca/partners/blog/liquid-date-format)
- note *timeago* does not work on github pages


# MongoDB

- [ ] Still a bit confused.   I used Mongo Atlas, so what is this MongoDB.  This four-part tutorial might be good as it installs mongodb locally [codingthesmartway.com MERN CRUD Tutorial](https://codingthesmartway.com/the-mern-stack-tutorial-building-a-react-crud-application-from-start-to-finish-part-1)

- reference - https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-content-to-your-github-pages-site-using-jekyll


- [MongoDB Introduction](https://mongodb.github.io/node-mongodb-native/api-articles/nodekoarticle1.html)

- [MongDB - Roles - Administration, etc](https://docs.mongodb.com/manual/reference/built-in-roles/)
