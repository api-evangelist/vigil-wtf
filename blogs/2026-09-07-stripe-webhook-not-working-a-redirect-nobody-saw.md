---
title: "Stripe webhook not working: a redirect nobody saw"
url: "https://www.vigil.tools/blog/our-stripe-webhook-had-never-delivered-once"
date: "2026-09-07"
feed_url: "https://www.vigil.wtf/blog/rss.xml"
---
Our apex domain 308-redirected to www, and Stripe does not follow redirects, so every webhook since launch died one hop before our well-tested code.
