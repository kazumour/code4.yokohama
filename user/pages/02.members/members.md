---
name: null
title: Members
blog_url: blog
body_classes: 'header-image fullwidth'
sitemap:
    changefreq: monthly
    priority: 1.03
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    limit: 16
    pagination: true
feed:
    description: 'Sample Blog Description'
    limit: 10
pagination: true
---
