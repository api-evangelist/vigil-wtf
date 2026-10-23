---
title: "Fail open vs fail closed: a missing env var, no auth"
url: "https://www.vigil.tools/blog/fail-open-auth-when-a-missing-env-var-disables-your-security"
date: "2026-09-08"
feed_url: "https://www.vigil.wtf/blog/rss.xml"
---
Our API-key check defaulted to off when its env var was unset, empty or misspelled, so deleting one variable disabled auth. The fix, and a rule about 401s.
