---
title: "Prompt caching with tools: order is part of the key"
url: "https://www.vigil.tools/blog/reordering-your-tools-busts-your-cache"
date: "2026-08-26"
feed_url: "https://www.vigil.wtf/blog/rss.xml"
---
Tool definitions sit ahead of the system prompt in the cached prefix, so one changed tool, or the same tools reordered, invalidates everything after them.
