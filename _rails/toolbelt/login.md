---
menuheaders: [ "Cloud 66 Easy Login", "Access Control for Toolbelt Login" ]
gitlinks: [ "https://github.com/cloud66/help/edit/feature/inlines/_includes/_inlines/Toolbelt/common/login/login_cloud-66-easy-login.md", "https://github.com/cloud66/help/edit/feature/inlines/_includes/_inlines/Toolbelt/common/login/login_access-control-for-toolbelt-login.md" ]
layout: post
template: one-col
title: Easy Login
categories: Toolbelt
lead: ""
legacy: false

---

{% assign thingy = page.url | split: '/' %}
{% assign product = thingy[1] %}

<a name="1"></a>{% include _inlines/Toolbelt/common/login/login_cloud-66-easy-login.md  product = product %}
<a name="2"></a>{% include _inlines/Toolbelt/common/login/login_access-control-for-toolbelt-login.md  product = product %}