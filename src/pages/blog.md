---
title: Blog
description: 'Look! Blog posts!'
layout: blog
pagination:
  data: collections.posts
  size: 6
permalink: 'blog/{% if pagination.pageNumber >=1  %}page-{{ pagination.pageNumber + 1 }}/{% endif %}index.html'
---

This page shows the **{{ pagination.size }}** most recents posts! Look at the older posts on the next pages.
