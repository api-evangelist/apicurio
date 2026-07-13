---
title: "Apicurio Registry - JSON Schema dereference"
url: "https://www.apicur.io/blog/2024/05/14/registry-dereference"
date: "2024-05-14"
author: "Carles Arnal Castello"
feed_url: "https://www.apicur.io/blog/feed.xml"
---
Apicurio Registry allows to manage artifacts with references as shown in the documentation . One of the cool features we’ve added on top of this is the possibility of using a dereference parameter for certain API endpoints that optionally allows you to fetch the full content of an artifact with all the references inlined within the same content. This is especially useful in certain contexts to reduce the number of HTTP requests in the Kafka Serializers and Deserializers, as you will see in this blog.
