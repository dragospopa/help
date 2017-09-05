---
menuheaders: [ "About deploying Elasticsearch", "Features", "Database deployment types", "How to connect to your Elasticsearch database", "Environment Variables", "Customize your database configuration", "About Scaling your Elasticsearch Cluster", "General Recommendations" ]
layout: post
template: one-col
title: Elasticsearch with Cloud 66 Node
categories: Databases
lead: "Using Elasticsearch on Cloud 66 for node stacks"
legacy: false
recommendedName: [ "Backup"]
recommendedLinks: [ "backup.html" ]
keywords: []
permalink: /:collection/:path
---

{% assign dbtype = "elasticsearch" %}

<a href="#about-deploying-{{ dbtype }}"></a>{% include _inlines/Databases/common/elasticsearch/about-deploying-elasticsearch-header-v1.md  product = page.collection %}
{% include _inlines/Databases/common/common/about-deploying-dbs-v1.md  product = page.collection %}
<a href="#features"></a>{% include _inlines/Databases/common/common/features-v1.md  product = page.collection %}
<a href="#database-deployment-types"></a>{% include _inlines/Databases/common/common/deployment-types-v1.md  product = page.collection %}
<a href="#how-to-connect-to-your-{{ dbtype }}-database"></a>{% include _inlines/Databases/common/common/how-to-connect-v1.md  product = page.collection %}
<a href="#environment-variables"></a>{% include _inlines/Databases/common/common/env-vars-v1.md  product = page.collection dbtype = dbtype %} 
<a href="#customize-your-database-configuration"></a>{% include _inlines/Databases/common/common/customize-v1.md  product = page.collection dbtype = dbtype %}
<a href="#about-scaling-your-elasticsearch-cluster"></a>{% include _inlines/Databases/common/elasticsearch-scaling/elasticsearch-scaling_about-scaling-your-elasticsearch-clus-v1.md  product = page.collection %}
<a href="#general-recommendations"></a>{% include _inlines/Databases/common/elasticsearch-scaling/elasticsearch-scaling_general-recommendations-v1.md  product = page.collection %}