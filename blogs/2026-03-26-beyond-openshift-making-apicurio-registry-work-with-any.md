---
title: "Beyond OpenShift: Making Apicurio Registry Work with Any OAuth Provider via Dex"
url: "https://www.apicur.io/blog/2026/03/26/universal-oauth-with-dex"
date: "2026-03-26"
author: ""
feed_url: "https://www.apicur.io/blog/feed.xml"
---
In a previous post , we showed how to connect Apicurio Registry directly to OpenShift’s built-in OAuth server. It worked for API-level authentication and role-based authorization, but three important features were broken: UI login, principal identity (artifact ownership), and owner-based authorization. And it only worked on OpenShift. We wanted to do better. We wanted a solution that works with...
