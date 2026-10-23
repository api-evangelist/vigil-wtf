---
title: "The 125-second LLM API timeout and the streaming fix"
url: "https://www.vigil.tools/blog/streaming-and-the-125-second-edge-timeout"
date: "2026-09-01"
feed_url: "https://www.vigil.wtf/blog/rss.xml"
---
A CDN edge closes idle connections at about 125 seconds, and a long non-streaming LLM call looks idle. Your SDK gets a 524 page, not the provider's reply.
