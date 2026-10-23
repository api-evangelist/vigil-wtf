---
title: "LLM API error handling when the error body is HTML"
url: "https://www.vigil.tools/blog/when-the-error-body-is-html-classifying-provider-failures"
date: "2026-09-02"
feed_url: "https://www.vigil.wtf/blog/rss.xml"
---
A timed-out upstream returned Cloudflare's HTML error page, not a JSON error. Two rules for LLM API errors: store the code, not the message; trust neither.
