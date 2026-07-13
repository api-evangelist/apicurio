---
title: "Integrating Apicurio Registry with OpenShift's Built-in OAuth Server"
url: "https://www.apicur.io/blog/2026/03/17/openshift-oauth-integration"
date: "2026-03-17"
feed_url: "https://www.apicur.io/blog/feed.xml"
---
If you’re running Apicurio Registry on OpenShift, you might be wondering: can I use OpenShift’s built-in OAuth server for authentication instead of deploying a separate identity provider like Keycloak? The answer is yes — with some caveats. In this post, I’ll walk you through how we got it working, what the limitations are, and the technical details behind the integration.
