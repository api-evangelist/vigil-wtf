---
title: "OpenAI streaming usage is zero unless you ask for it"
url: "https://www.vigil.tools/blog/openai-logs-zero-tokens-on-streamed-calls-unless-you-ask"
date: "2026-09-15"
feed_url: "https://www.vigil.wtf/blog/rss.xml"
---
Chat Completions sends no usage on a streamed call unless you set stream_options include_usage, so each streamed call meters as zero tokens and $0.00.
