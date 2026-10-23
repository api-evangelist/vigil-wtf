---
title: "Bedrock API keys are bearer tokens. Caching cares."
url: "https://www.vigil.tools/blog/bedrock-api-keys-are-bearer-tokens"
date: "2026-09-13"
feed_url: "https://www.vigil.wtf/blog/rss.xml"
---
SigV4 signs the request body, so no proxy can add a cache breakpoint without the secret key. A Bedrock API key signs no body, and that decides caching.
