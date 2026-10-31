---
layout: page
title: My Books
permalink: /books
---

# My Books

{% assign bs = site.books | sort: 'order' %}
{% include book-grid.html books=bs %}
