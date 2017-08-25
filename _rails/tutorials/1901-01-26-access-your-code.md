---
gitlinks: [ "https://github.com/cloud66/help/edit/feature/inlines/_includes/_inlines/Tutorials/common/1901-01-26-access-your-code/1901-01-26-access-your-code_public-repositories.html", "https://github.com/cloud66/help/edit/feature/inlines/_includes/_inlines/Tutorials/common/1901-01-26-access-your-code/1901-01-26-access-your-code_notice.html", "https://github.com/cloud66/help/edit/feature/inlines/_includes/_inlines/Tutorials/common/1901-01-26-access-your-code/1901-01-26-access-your-code_private-repositories.html", "https://github.com/cloud66/help/edit/feature/inlines/_includes/_inlines/Tutorials/common/1901-01-26-access-your-code/1901-01-26-access-your-code_github-example.html", "https://github.com/cloud66/help/edit/feature/inlines/_includes/_inlines/Tutorials/common/1901-01-26-access-your-code/1901-01-26-access-your-code_bitbucket-example.html" ]
layout: post
template: one-col
title: Accessing your Git repository
categories: Tutorials
lead: ""
legacy: false

---

{% assign thingy = page.url | split: '/' %}
{% assign product = thingy[1] %}
{% assign product = "common" %}

{% include _inlines/Tutorials/common/1901-01-26-access-your-code/1901-01-26-access-your-code_public-repositories.md  product = product %}
{% include _inlines/Tutorials/common/1901-01-26-access-your-code/1901-01-26-access-your-code_notice.md  product = product %}
{% include _inlines/Tutorials/common/1901-01-26-access-your-code/1901-01-26-access-your-code_private-repositories.md  product = product %}
{% include _inlines/Tutorials/common/1901-01-26-access-your-code/1901-01-26-access-your-code_github-example.md  product = product %}
{% include _inlines/Tutorials/common/1901-01-26-access-your-code/1901-01-26-access-your-code_bitbucket-example.md  product = product %}