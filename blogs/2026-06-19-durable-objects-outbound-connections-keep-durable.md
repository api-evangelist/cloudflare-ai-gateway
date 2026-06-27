---
title: "Durable Objects - Outbound connections keep Durable Objects alive"
url: "https://developers.cloudflare.com/changelog/post/2026-06-19-outbound-connections-keep-dos-alive/"
date: "2026-06-19"
feed_url: "https://developers.cloudflare.com/changelog/rss/index.xml"
---
Durable Objects remain active during outbound TCP or WebSocket connections via connect(). Each active connection prevents eviction for up to 15 minutes, solving the problem of eviction cutting off streaming responses mid-operation.
