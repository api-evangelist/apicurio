---
title: "Securing Apicurio Registry 2.4.x using Azure Entra ID"
url: "https://www.apicur.io/blog/2023/07/13/registry-azure-ad"
date: "2023-07-13"
author: "Carles Arnal Castello"
feed_url: "https://www.apicur.io/blog/feed.xml"
---
Hey everyone, in recent Apicurio Registry versions we’ve introduced support for securing the application using different OpenID Connect (OIDC) servers, and not just Keycloak. In this blog post, I will explain how to configure the application to secure it using Microsoft Azure Entra ID. Core Features In this blog post, we will cover the following: Authentication based on Azure Entra ID - optionally protect Apicurio Registry so that the registry API and web console require users to authenticate (OAuth Authorization Code Flow supported) Azure Entra ID Configuration Authentication based on Azure A
